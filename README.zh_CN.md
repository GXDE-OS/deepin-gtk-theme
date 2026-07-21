![HEADER](./docs/img/header.png)

Deepin/GXDE风格的主题，支持GTK 2/3/4.

## 构建
构建脚本位于./build-deb, 这是个shell脚本，用于在调试时生成安装包，便于在调试机器上轻松部署与卸载。

首先先修改脚本权限:
```bash
$ chmod a+x ./build-deb
```

初次编译建议执行:
```bash
$ ./build-deb -d    # 安装依赖并构建
```
构建产物应该在项目根目录的上级目录。

构建完成后清理中间产物:
```bash
$ ./build-deb -c
```
注意这也会一并清除构建产物。

## 许可

本项目使用[GPLv3](LICENSE)或任何更高版本的GPL许可授权。
