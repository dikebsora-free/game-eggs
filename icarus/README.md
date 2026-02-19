# Icarus

***NOTE: Server version currently marked as Beta by the developers.***
___

### 作者 / 贡献者

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/BolverBlitz">
                <img src="https://avatars.githubusercontent.com/u/35345288" width="50px;" alt=""/><br /><sub><b>BolverBlitz</b></sub>
            </a>
            <br />
            <a href="https://github.com/BolverBlitz" title="Codes">💻</a>
            <a href="https://github.com/BolverBlitz" title="Maintains">🔨</a>
        </td>
        <td align="center">
            <a href="https://github.com/Red-Banana-Official">
                <img src="https://avatars.githubusercontent.com/Red-Banana-Official" width="50px;" alt=""/><br /><sub><b>Red-Banana-Official</b></sub>
            </a>
            <br />
            <a href="https://github.com/Red-Banana-Official" title="Codes">💻</a>
        </td>
    </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

___

### 游戏简介

Icarus is a session-based survival game for up to 8 co-op players or solo players, where most gameplay occurs during timed missions. Players accept contracts for missions on a space station orbiting the planet, and drop down to its terrain to attempt the objectives. Once a mission timer is complete, the drop-pod returns to the station. If the player fails to return in time, their workshop items are left on the surface and their progress is lost. 
There is also support for an OpenWorld where without resets.

___

### Egg 功能

- Currently runs the Windows build of the server via wine.
- Auto-Updates on restart.

___

### 服务器端口

- Default server ports are listed below, but all three ports can be changed freely.
- Clients connect via the server list in game.

| 端口 | 默认值 | 协议 |
|---------|---------|----------|
| 游戏 | 17777   | UDP      |
| 查询 | 27015   | UDP      |

___

### 安装/系统要求

|           | 推荐 | Extra info  |
|-----------|--------------|-------------|
| 处理器 | Recent x86/64 (AMD/Intel) processor. No 32 bit or ARM support. | Unsubstantiated reports say that RCON uses significantly more CPU when enabled, but I have not been able to replicate myself. |
| 内存 |  8-16 GB     |
| 存储 |  14 GB (or more, depending on save size or frequency) |

___

#### Save File and Custom Settings Location

You can define a custom dir for settings by adding `-UserDir=` to the startparameter. [More Info](https://github.com/RocketWerkz/IcarusDedicatedServer/wiki/Server-Config-&-Launch-Parameters#-userdir)

#### Server Game Settings

[Server-Config & Launch-Parameters](https://github.com/RocketWerkz/IcarusDedicatedServer/wiki/Server-Config-&-Launch-Parameters)
