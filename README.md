# forge-javadoc 仓库说明

本仓库用于托管 Forge 的 Javadoc 文档

## 🏷 分支版本对应关系

### `master` 分支
- 对应版本: **1.12.2**
- 特殊说明:  
  > 该分支文档生成方式已遗忘，原计划生成 2860 版本

### `forge-54.1` 分支
- 对应版本: **1.21.4-54.1**
- 源码来源:  
  [MinecraftForge/MinecraftForte @54.1](https://github.com/MinecraftForge/MinecraftForge/tree/54.1)
- 版本说明:  
  `本来想找54.1.3的，但未找到其他可用版本`
### `neoforge-1.21.7` 分支
- NeoForge 21.7.4-beta Modding API for Minecraft 1.21.7
- 2025/7/5 拉取自1.21.x分支，去掉了无法生成javadoc的base子项目（报错太多）

## 🚀 部署信息
采用 Vercel 平台进行静态页面部署：

| 分支名称       | 部署地址                               |
|----------------|----------------------------------------|
| `master`       | <https://forge-javadoc.vercel.app/>    |
| `forge-54.1`   | <https://forge-javadoc-git-forge-541-reyi2323s-projects.vercel.app/> |
| `neoforge-1.21.7` | <https://forge-javadoc-git-neoforge-1217-reyi2323s-projects.vercel.app/> |
