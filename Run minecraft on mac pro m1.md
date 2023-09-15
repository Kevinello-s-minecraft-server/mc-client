# Run minecraft on mac pro m1

由于MC自带的必要动态链接库LWJGL的架构是X86，不兼容mac pro m1处理器的arm64架构，原生的MC是无法在m1上启动的；同时由于Apple强推了Metal API，在部分mod / 光影 / 材质包上会有损失部分`Feature`的情况

## 基本设置

见[arm64 minecraft wrapper](https://github.com/Kevinello-s-minecraft-server/arm64-minecraft-wrapper)

完成配置后可正常启动`Minecraft`

## mod支持情况

部分图形渲染相关mod会出现无法渲染文字 / 图像的情况

## 光影支持情况

m1下仅支持部分光影（部分光影会因为Metal API产生Error）

### 经过测试已支持的光影：

https://github.com/MoustacheOff/AppleSilicon-Minecraft-Shaders
