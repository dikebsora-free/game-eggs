# SourceCoop

### Egg Authors / Contributors

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/lilkingjr1">
                <img src="https://avatars.githubusercontent.com/u/4533989" width="50px;" alt=""/><br /><sub><b>Red-Thirten</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=lilkingjr1" title="Codes">💻</a>
        </td>
    </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---

## 服务器描述

From their [Github](https://github.com/ampreeT/SourceCoop):
> SourceCoop is a cooperative server-side-only mod for multi-player Source Engine games (like Black Mesa), that enables players to play together on single-player campaigns or maps.

> [!IMPORTANT]
>
> This Egg ***only*** supports official Black Mesa maps, but it can easily be modified to support custom BM maps (see [Manual Configuration Topics](#manual-configuration-topics) for details).
>
> Support for other Source Engine games (eg. HL2) may be added in the future to SourceCoop and this Egg, but Black Mesa is currently the only formally supported game.

## Egg 功能

- Configuration of basic server settings via Startup Variables. This includes:
  - Server Name
  - Max Players
  - Server Password
    - Note: Clients may need to enter `password <your_password>` in their console before joining.
  - Starting Map
  - and Enable Friendly Fire
- Fix for some maps potentially crashing on Linux via "[Advanced] Enable `mod_forcetouchdata`" Startup Variable.
  - See SourceCoop [issue #121](https://github.com/ampreeT/SourceCoop/issues/121) for details.
- Fine-tune configuration of which versions/builds to download of SourceCoop and its dependencies (helpful in the event of SourceCoop updating).

## 安装/系统要求

|  | 最低要求 | 推荐 |
|---------|---------|---------|
| 处理器 | Recent x86/64 (AMD/Intel) processor. No ARM support. | ---- |
| 内存 | 512 MiB | 2048-4096 MiB |
| 存储 | 29696 MiB | 32768 MiB |
| 游戏所有权 | Not required at all. | ---- |

## 服务器端口

- Default server ports are listed below, but they can be changed freely.
- RCON will share the Game port and is only required if the server owner enables/uses RCON.

| 端口 | 默认值 | 协议 |
|---------|---------|---------|
| 游戏 | 27015 | UDP |
| RCON | (Same as Game) | TCP |

## Manual Configuration Topics

The following are various topics covering manual configuration procedures the Egg does not handle automatically that may be useful to server owners:

### Additional Config. / Addons / Plugins

This is best documented by their [Github](https://github.com/ampreeT/SourceCoop):

- [Features & Configuration](https://github.com/ampreeT/SourceCoop/wiki/Features-&-Configuration)
- [Workshop & Plugins](https://github.com/ampreeT/SourceCoop/wiki/Server-running-tips)

### Custom Maps

As stated above, this Egg formally supports official Black Mesa maps only. However, custom maps can still be loaded by editing the Egg's "Starting Map" Startup Variable to have an input rule of only `required|string`. This will allow custom map names to be entered. [Here is a link](https://steamcommunity.com/sharedfiles/filedetails/?id=2375865650) to a list of currently supported (by SourceCoop) custom maps.

### Different Games/Builds

As stated above, this Egg only formally supports the game Black Mesa. However, different builds of SourceCoop that support different games can be installed via the "[Advanced] SourceCoop Release Build Tag" Startup Variable. This tag should match text in the name of the release asset. Heavy, manual modification of the Egg would be required to make this work though.
