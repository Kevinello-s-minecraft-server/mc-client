# Kevinello's Minecraft Server Guide

![mc-server-2](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151142619-4a938f.png)

![mc-server-1](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151230789-d56879.png)

自建的一个小型服务器(目前是白嫖服务器用爱发电的形态)
服主邮箱: 1051360477@qq.com
有意愿来我的服务器游玩请邮件至上述邮箱联系服主

## 依赖安装

- **HMCL**启动器依赖的 [`zulu jdk fx 11`](https://www.azul.com/downloads/?version=java-11-lts&package=jdk-fx)(高版本jdk在HMCL上有bug，新版本HMCL会自己尝试安装jdk fx)
- **minecraft 1.20**依赖的[`zulu jdk 19`](https://www.azul.com/downloads/?version=java-19-lts&package=jdk)，java 17+就行，高版本优化好些

注意对应上自己的系统和架构

## 下载整合包以及安装

整合包维护在client仓库的release中：[client release](https://github.com/Kevinello-s-minecraft-server/ClientPack/releases)

![image-20220410234559606](https://kevinello-1302687393.file.myqcloud.com/picgo/2023/09/15/202309151210485-9c07e7.png)

点击`vx.x.x.zip`即可下载

目前整合包内使用的是[HMCL启动器](https://github.com/huanghongxun/HMCL/releases)，方便我们配置第三方登录验证以及兼容各架构设备，如有个人使用习惯可使用其它启动器

### 首次安装整合包

使用整合包内自带的启动器启动，启动时会自动安装整合包（部分版本中不包含启动器，请在[HMCL release](https://github.com/huanghongxun/HMCL/releases)中下载最新版本并启动后将整合包拖入即可）

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

## mod统计

见我的[mod统计页面](https://www.notion.so/kevinello/e220b94930214646868e5379481cb10e?v=6040f972867f49e797a5e2adf68967cb&pvs=4)

## 注意事项

1. 多上线plz
1. 禁用高频红石，服务器资源有限

## Q&A

- 如何在arm架构的系统上运行客户端

  见另一篇文档[Run minecraft on mac m1 pro](https://kevinello.ltd/2022/04/11/Run-minecraft-on-mac-pro-m1/)
