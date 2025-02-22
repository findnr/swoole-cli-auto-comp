# 自动编译swoole-cli 增加了一此扩展
#### 增加的扩展列表
- +inotify
- +mongodb
- +xlswriter
#### 全程自动编译，每天都会执行，只要官方有更新，都是会编译的
#### 同时有x86_64和arm64两种架构
#### 切换swoole版本编译
- 要将 git submodule 切换到特定的较低版本，您可以按照以下步骤操作：
- 1. 首先，进入对应的子模块目录：
```sh
cd ext/swoole
```
- 2. 查看可用的版本/标签：
```sh
git tag -l
```
- 3. 切换到您想要的特定版本（比如 v4.8.12）：
```sh
git checkout v4.8.12
```
- 4.提交这个更改（可选）：(回到项目根目录)
```sh
git add ext/swoole
git commit -m "将 swoole 子模块版本切换到 v4.8.12"
```
