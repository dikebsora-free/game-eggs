# Counter-Strike: Source

## From their [Steam Depot](https://steamdb.info/app/232330/)

A link to the site that you download the server files from.

## [Documentation]

A link to relevent documentation for the server.

The description of the server usually provided by the game/server maker.
<!--Example: Parkers Pterodactyl Eggs Repo. Server eggs for the Pterodactyl management panel-->

## Install notes

To get a persistent server (server that appears on the server list), you need to get a [Steam Server Login Token](https://steamcommunity.com/dev/managegameservers), it's not required though.

## 安装/系统要求
<!--Make changes to reflect the server minimum/recommended hardware specs-->
|  | 最低要求 | 推荐 |
|---------|---------|---------|
| 处理器 | Does not support ARM(?) | - |
| 内存 | 512MB | 1GB |
| 存储 | 3GB | 6GB |
| 网络 | 1Mbit/s | 5Mbit/s |
| 游戏所有权 | 否 | See **Install Notes** |

## 服务器端口

Ports required to run the server in a table format.

| 端口 | default |
|---------|---------|
| 游戏 | 27015   |
| Source TV | 27020 |
| Client  | 27005   |
| Steam   | 26900   |

### 备注

27015 is the default port, but any port can be used.
The only required port is the Game port, server can run perfectly fine without other allocations.
