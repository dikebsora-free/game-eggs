# ARK: Survival Ascended

Steam Description :
ARK is reimagined from the ground-up into the next-generation of video game technology with Unreal Engine 5! Form a tribe, tame & breed hundreds of unique dinosaurs and primeval creatures, explore, craft, build, and fight your way to the top of the food-chain. Your new world awaits!

### 作者 / 贡献者
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/dagbs">
                <img src="https://avatars.githubusercontent.com/u/133905860" width="50px;" alt=""/><br /><sub><b>Blood Shot</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=dagbs" title="Codes">💻</a>
            <a href="https://github.com/parkervcp/eggs/commits?author=dagbs" title="Maintains">🔨</a>
        <td align="center">
            <a href="https://github.com/gOOvER">
                <img src="https://avatars.githubusercontent.com/u/116325" width="50px;" alt=""/><br /><sub><b>gOOvER</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=gOOvER" title="Codes">💻</a>
        </td>
        <td align="center">
            <a href="https://github.com/hackles">
                <img src="https://avatars.githubusercontent.com/u/30584261" width="50px;" alt=""/><br /><sub><b>heckler</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=hackles" title="Codes">💻</a>
        </td>
        </td>
        <td align="center">
            <a href="https://github.com/Log1x">
                <img src="https://avatars.githubusercontent.com/u/5745907" width="50px;" alt=""/><br /><sub><b>Brandon</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=Log1x" title="Codes">💻</a>
        </td>  
        <td align="center">
            <a href="https://github.com/Ballaual">
                <img src="https://avatars.githubusercontent.com/u/38478976" width="50px;" alt=""/><br /><sub><b>Alexander Ballauf</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=Ballaual" title="Codes">💻</a>
        </td> 
        <td align="center">
            <a href="https://github.com/MachinegunMarty">
                <img src="https://avatars.githubusercontent.com/u/20025119" width="50px;" alt=""/><br /><sub><b>MachinegunMartyf</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=MachinegunMarty" title="Contributor">💡</a>
        </td>
        <td align="center">
            <a href="https://github.com/That411Guy">
                <img src="https://avatars.githubusercontent.com/u/100328348" width="50px;" alt=""/><br /><sub><b>That411Guy</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/commits?author=That411Guy" title="Codes">💻</a>
        </td>         
    </tr>
</table>
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

---
## Troubleshooting

1) Try starting the server with no mods on a fresh install.

2) If there are crash logs, they will be available in the Files at `ShooterGame/Saved/Crashes/UECC-Windows-*/CrashContext.runtime-xml`

### Crash Identifiers

Crashes will either stop the server or display 0-5% CPU usage.
The number is in reference to RAM/Memory usage.

1) Server crashing around 500MB is probably either a config issue or a corrupted install.

2) Server crashing around 750MB is probably commandline issue.

3) Server crashing around 1GB is probably either a MOD conflict or corrupted SavedArks files.


## 已知问题

1) Proxmox VM(s): You'll need to change your Processor Type to `Host` (Default: kvm64)

2) ARK's wiki heavily reference A:SE and not all features are available in A:SA.

## 推荐服务器配置

### Minimum RAM

This server requires about 11GB of RAM to run with no players on a 默认值 map.

See the following - <https://ark.wiki.gg/wiki/Dedicated_server_setup#RAM>

## 服务器端口

| 端口 | 默认值 |
| --------------- | ------- |
| 游戏 | 7777    |
| RCON（可选） | 37015   |
