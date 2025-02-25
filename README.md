<div align="center">
<h1>MMES</h1>
<h2>方便地将服务端和双端模组从模组文件夹复制出来吧!</h2>
</div>

这是我用C#给自己的MC服务器搓的小程序，~~闲的蛋疼就~~拿来开源了()

写的很石山，但是可以凑和着用，~~已经很棒了~~

## 环境要求
- Windows 系统
- Dotnet 8.0 运行环境
- 一个放了模组的文件夹
- 一个脑子

## 如何使用
首先打开程序 (awa
1. (可选) 输入setTargetPath以设定目标路径
2. 输入start，然后输入你需要分离出的模组的文件夹路径
3. 此时会自动识别模组的运行环境，将服务端和通用模组复制至目标路径
4. 如果一些模组没有设定环境，会询问是否要复制
5. 完成

## 加载器支持状况
| 加载器 | 符号 | 支持状况 | 原因 |
| ------ | --- | ------- | ---- |
| Fabric | ✔ | 完全支持 | N/A |
| Quilt  | ✔ | 完全支持 | N/A |
| NeoForge | ⚠ | 部分支持 | 目前无法识别部分模组的环境 |
| Forge | 🚧 | 长期决议 | 暂未寻找到识别模组环境的方式 |

## TODO
- 多线程处理模组
- 优化命令行系统
- 支持其他系统
- 以及其它......

## 协议
### MIT
