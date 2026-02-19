# Avorion

A procedural co-op space sandbox where players can build their own space ships out of dynamically scalable blocks. Fight epic space battles, explore, mine, trade, wage wars and build your own empire to save your galaxy from being torn apart by an unknown enemy.

## 服务器端口

Avorion requires 4 ports to run.  Despite claiming to require 4 ports, the game port is the only one that appears to have a config option.

| 端口 | 默认值 |
|-------------|---------|
| 游戏 | 27000   |
| 查询 | 27003   |
| Steam Query | 27020   |
| Steam       | 27021   |

Additionally the server can be configured with an RCON port.  RCON will be disabled if a password is not specified.

| 端口 | 默认值 |
|-------------|---------|
| RCON        | 27015   |

## RCON

If you plan to use RCON it currently needs to be manually configured in the server.ini file.  At some point server variables will be added.

## 更新
Because with an update to this egg, the startup command changed, so if you update this egg, you will manually have to update the startup command for every server that was already made.
