# VEIN
<!--Please remove these comments and irelevent parts for the server egg your adding before summiting a PR request-->

## From their [Steam](https://store.steampowered.com/app/1857950/VEIN/)

## [Documentation](https://ramjet.notion.site/Server-Hosting-85f92f43f32548c1b5b33797ddf456ad)


## 安装/系统要求
|  | 最低要求 | 推荐 |
|---------|---------|---------|
| 处理器 | Almost any proccessor will work (AMD64 only) | -|
| 内存 | 12 GiB | 16 GiB |
| 存储 | 15 GiB | 20 GiB |
| 网络 | Any reasonable speed |- |
| 游戏所有权 | Not needed | * |   

## 服务器端口

Ports required to run the server in a table format.

| 端口 | default |
|---------|---------|
| 游戏 | 7777    |
| 查询 | 27015   |

## 配置

Some config values can be changed under the startup tab.
Everything else must manual be changed in `Vein/Saved/Config/LinuxServer/Game.ini`

See [here](https://ramjet.notion.site/Server-Hosting-85f92f43f32548c1b5b33797ddf456ad) what every option means.

## Warning

Do not touch the `Vein/Saved/Config/LinuxServer/Engine.ini` file, it will brake the console!


