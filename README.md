# Kevinello's Minecraft Server Guide

![mc-server-2](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151142619-4a938f.png)

![mc-server-1](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151230789-d56879.png)

自建的一个小型服务器，服主邮箱: 1051360477@qq.com
有意愿来我的服务器游玩请邮件至上述邮箱联系服主

## 依赖安装

- [**HMCL**](https://github.com/HMCL-dev/HMCL/releases/tag/release-3.5.5) mc 启动器，windows、mac、linux通用，windows下可直接下载exe文件，mac、linux下下载jar文件，使用`java -jar HMCL-xxx.jar`运行
  ![alt text](https://kevinello-1302687393.file.myqcloud.com/picgo/2024/01/18/202401181721261-e79c34.png)
  如有个人使用习惯可使用其它启动器（PCL2，MultiMC等）
- **minecraft 1.20**依赖的[`zulu jdk 21`](https://www.azul.com/downloads/?version=java-21-lts&package=jdk-fx#zulu)，java 17+就行，高版本优化好些；注意选择系统和架构（大部分人都是x86-64，如不清晰可搜索一下自己的CPU型号）
  ![alt text](https://kevinello-1302687393.file.myqcloud.com/picgo/2024/01/18/202401181727227-c594a8.png)
  Nice to know: 选择 JDK FX 是因为启动HMCL需要FX库，这样一个JAVA版本解决
  
## 下载整合包以及安装

整合包维护在client仓库的release中：[client release](https://github.com/Kevinello-s-minecraft-server/ClientPack/releases)，一般找最新的release下载即可（有可能是pre release）

![image-20220410234559606](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151210485-9c07e7.png)

点击`vx.x.x.zip`即可下载

### 首次安装整合包

直接将整合包（.zip文件）拖入HMCL界面中即可自动安装

### 后续更新整合包

下载好新整合包后，在HMCL的【游戏】中找到自己的游戏实例，点击进入游戏管理

![image-20220219142827131](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151134890-805650.png)

点击更新整合包，拖入新整合包中的modpack.zip，点击安装即可完成更新

![image-20230915123141082](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/image-20230915123141082-3a05ac.png)

![image-20230915123126102](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/image-20230915123126102-a10d71.png)

### littleSkin第三方验证

本服务器使用第三方认证服务器外置登录，配置方式如下：

点击进入账户页面

![image-20230915123219823](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/image-20230915123219823-614ed4.png)

点击添加认证服务器

![image-20230915123300101](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/image-20230915123300101-cffd66.png)

输入认证服务器地址： https://littleskin.cn/api/yggdrasil，点击下一步 -> 完成即可（如图所示添加完成）

![image-20230915123406022](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/image-20230915123406022-265992.png)

## 整合包概述

版本介绍：https://kevinello.notion.site/v3-0-0-f4b111fcd96942368a22f760cc01416d?pvs=4
mod列表：https://kevinello.notion.site/e220b94930214646868e5379481cb10e?v=0c4f1a074e3e4d41aa68cf54eb08a8a1

## 注意事项

1. 多上线🙃
2. 禁用高频红石，服务器资源有限

## Q&A

- 如何在arm架构的系统上运行客户端

  见另一篇文档[Run minecraft on mac m1 pro](https://kevinello.ltd/2022/04/11/Run-minecraft-on-mac-pro-m1/)
