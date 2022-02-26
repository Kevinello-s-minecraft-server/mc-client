# Kevinello's Minecraft Server Guide

![2022-02-11_00.15.22 中](https://gitee.com/Kevinello/pic/raw/master/img/20220211111722.png)

自建的一个小型服务器（目前是白嫖服务器用爱发电的形态)

## 依赖安装

- **HMCL**启动器依赖的 `zulu jdk fx 11`:  https://www.azul.com/downloads/?version=java-11-lts&package=jdk-fx (高版本jdk在HMCL上有bug)
- **minecraft 1.18**依赖的`zulu jdk 17`: https://www.azul.com/downloads/?version=java-17-lts&package=jdk

注意对应上自己的系统和架构

## 下载整合包以及安装

目前我们推荐使用的是HMCL启动器，方便我们配置第三方登录验证以及兼容各架构设备

### 首次安装整合包

使用整合包内自带的启动器启动，启动时会自动安装整合包

### 后续更新整合包

下载好新整合包后，在HMCL的【游戏】中找到自己的游戏实例，点击进入游戏管理

![image-20220219142827131](https://gitee.com/Kevinello/pic/raw/master/20220219-142828.png)

点击更新整合包，拖入新整合包中的modpack.zip，点击安装即可完成更新

![image-20220225185456319](https://gitee.com/Kevinello/pic/raw/master/20220225-185457.png)

![image-20220225185625091](https://gitee.com/Kevinello/pic/raw/master/20220225-185625.png)

### littleSkin第三方验证

本服务器使用第三方认证服务器外置登录，配置方式如下：

点击进入账户页面

![image-20220225184157344](https://gitee.com/Kevinello/pic/raw/master/20220225-184158.png)

点击添加认证服务器

![image-20220225184247260](https://gitee.com/Kevinello/pic/raw/master/20220225-184248.png)

输入认证服务器地址： https://littleskin.cn/api/yggdrasil，点击下一步 -> 完成即可

![image-20220225184444017](https://gitee.com/Kevinello/pic/raw/master/20220225-184444.png)

## mod统计

**不包含依赖形mod（各种fabric API等）**

### 服务器已支持的功能性mod

| Mod名            | 说明                       | 客户端 | 服务端 |
| ---------------- | -------------------------- | ------ | ------ |
| wraith-waystones | 更优秀的传送系统（传送碑） | ✅      | ✅      |
| XaerosWorldMap   | 世界地图（已禁用地图传送） | ✅      | ✅      |
| The Wild Mod     | 1.19内容前瞻               | ✅      | ✅      |
| Campanion        | 户外主题拓展               | ✅      | ✅      |
| VanitySlots      | 盔甲隐藏                   | ✅      | ✅      |
| Promenade        | 生物群系拓展和自然建筑拓展 | ✅      | ✅      |
| Plasmovoice      | mc内置语音系统             | ✅      | ✅      |
| diggusmaximus    | 连锁挖掘                   | ✅      | ✅      |
| ferritecore      | mc内存优化                 | ✅      | ✅      |
| IronChests       | 更多箱子                   | ✅      | ✅      |
| krypton          | mc网络优化                 | ✅      | ✅      |

### 纯服务端mod

客户端必须安装的mod（不装可能会出现进不了服务器/区块加载错误等情况）

| Mod名              | 说明                                 | 客户端 | 服务端 |
| ------------------ | ------------------------------------ | ------ | ------ |
| BlueMap            | 实时web端地图                        | ❌      | ✅      |
| essential_commands | 常用便捷命令集合                     | ❌      | ✅      |
| Lithium            | mc全能优化(物理引擎，方块tick等)     | ❌      | ✅      |
| LuckPerms          | 命令权限管理系统                     | ❌      | ✅      |
| neutral-animals    | 更逼真的动物行为                     | ❌      | ✅      |
| phosphor           | mc光照引擎优化                       | ❌      | ✅      |
| tabtps             | 服务器延迟，吞吐量显示               | ❌      | ✅      |
| DungeonsArise      | 地下城主题生物群系拓展和自然建筑拓展 | ❌      | ✅      |

### 纯客户端mod

可自行选择安装的mod（不装也可以正常游玩服务器）

| Mod名                  | 说明                               | 客户端 | 服务端 |
| ---------------------- | ---------------------------------- | ------ | ------ |
| Better recipe book     | 更好的合成配方                     | ✅      | ❌      |
| continuity             | 无缝玻璃                           | ✅      | ❌      |
| Iris                   | 新时代光影mod                      | ✅      | ❌      |
| Sodium                 | 新时代渲染引擎，客户端优化         | ✅      | ❌      |
| Indium                 | Sodium附加包(Fabric Rendering API) | ✅      | ❌      |
| InventoryProfilesNext  | 背包整理                           | ✅      | ❌      |
| lambdynamiclights      | 动态光源优化                       | ✅      | ❌      |
| mod menu               | mod管理                            | ✅      | ❌      |
| pinglist               | 实时显示ping值                     | ✅      | ❌      |
| Sodium Extra           | 视频设置控制面板优化               | ✅      | ❌      |
| Reese's Sodium Options | 视频设置控制面板优化               | ✅      | ❌      |
| Starlight              | 光照引擎优化（与Phosphor不兼容）   | ✅      | ❌      |
| Xaeros_Minimap         | 地图面板显示                       | ✅      | ❌      |

## 注意事项

1. 多上线，多上线，多上线
1. 禁用高频红石，服务器资源有限

## Q&A

- 如何在arm架构的系统上运行客户端

  见另一篇文档[Run minecraft on mac m1 pro](./Run minecraft on mac m1 pro.md)

