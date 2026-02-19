# Palworld

### Steam 简介
在这款全新的多人开放世界生存和建造游戏中，与被称为"伙伴"的神秘生物一起战斗、耕种、建造和工作！

### 作者 / 贡献者
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/Ballaual">
                <img src="https://avatars.githubusercontent.com/u/38478976" width="50px;" alt=""/><br /><sub><b>Alexander Ballauf</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1900216079" title="Codes">💻</a>
            <a href="https://github.com/parkervcp/eggs/commits?author=Ballaual" title="Maintains">🔨</a>
        </td>
        <td align="center">
            <a href="https://github.com/QuintenQVD0">
                <img src="https://avatars.githubusercontent.com/u/67589015" width="50px;" alt=""/><br /><sub><b>QuintenQVD0</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1899999796" title="Codes">💻</a>
        <td align="center">
            <a href="https://github.com/hackles">
                <img src="https://avatars.githubusercontent.com/u/30584261" width="50px;" alt=""/><br /><sub><b>heckler</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1900043987" title="Contributor">💡</a>
        </td>
        </td>
        <td align="center">
            <a href="https://github.com/danny6167">
                <img src="https://avatars.githubusercontent.com/u/388231" width="50px;" alt=""/><br /><sub><b>Daniel Barton</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1900100992" title="Codes">💻</a>
        </td>  
        <td align="center">
            <a href="https://github.com/Rodhin">
                <img src="https://avatars.githubusercontent.com/u/13395074" width="50px;" alt=""/><br /><sub><b>Rodhin</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1900153550" title="Codes">💻</a>
        </td> 
        <td align="center">
            <a href="https://github.com/B0rbor4d">
                <img src="https://avatars.githubusercontent.com/u/33213807" width="50px;" alt=""/><br /><sub><b>B0rbor4d</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1900213758" title="Contributor">💡</a>
        </td>
        <td align="center">
            <a href="https://github.com/Simsz">
                <img src="https://avatars.githubusercontent.com/u/12779829" width="50px;" alt=""/><br /><sub><b>Zach</b></sub>
            </a>
            <br />
            <a href="https://github.com/parkervcp/eggs/issues/2669#issuecomment-1899954711" title="Contributor">💡</a>
        </td>         
    </tr>
</table>

## 已知问题 / 常见问题

1) 服务器不会显示在社区服务器标签中。<br>
-> 这是一个已知问题，开发人员希望尽快修复。最佳选择是通过 IP 和密码连接。

2) 服务器存在内存泄漏。<br>
-> 这也是他们已知的问题。<br>
-> `bEnableInvaderEnemy` 选项似乎对当前内存使用有很大影响。禁用它可能是个选择。<br>
-> 提示：安排服务器每 6 小时重启一次。您可以根据系统情况调整该值！<br>

3) 服务器不会显示在 Steam 服务器列表中。<br>
-> 目前不支持，可能永远不会支持。

4) 配置文件在服务器重启时被删除/重置。<br>
-> 在编辑配置文件之前，务必先完全停止服务器。否则所有更改都不会被保存。

## 推荐服务器配置

### 内存

由于至少存在一个内存泄漏，服务器需要大约 16-32GB 内存。<br>
参考[官方文档](https://tech.palworldgame.com/dedicated-server-guide)，您可以用 8GB 启动服务器，但很快就会耗尽内存。<br>
最低应为 16GB，但目前相当推荐 32GB。<br>

### CPU

至少 4 核的 Intel / AMD 处理器。

### 存储

截至 2024 年 1 月 19 日，服务器需要大约 5GB 的存储容量。这可能会随着进一步的内容/更新而扩展。

## 服务器端口

| 端口            | 默认值 |
| --------------- | ------- |
| 游戏            | 8211    |
| RCON (可选) | 25575   |

RCON 端口不需要分配。

### 更新

1. 更新您的 egg
2. 将所有已创建服务器的启动项更新为 egg 中现在附带的启动项
3. 然后点击重新安装，因为需要下载解析器应用程序
4. 由于 Palworld 开发人员在 v0.1.5.0 中忘记在配置中添加新的 `bShowPlayerList` 键，您需要自己添加它。这可能在未来修复。其默认值为 False

配置结尾示例：`bUseAuth=True,bShowPlayerList=False,BanListURL="https://api.palworldgame.com/api/banlist.txt")`

### 变量解析

目前附带的解析器应用程序能够编辑截至 2024 年 2 月 1 日 Palworld 配置文件中存在的所有变量。

但是，egg 中仅存在最基本和必要的变量。
需要更多变量的人必须自己添加它们。

在[此处](https://github.com/QuintenQVD0/Palword-server-config-parser?tab=readme-ov-file#key-with-variables)查看键与变量的匹配列表

**不存在的变量将自动跳过解析，因此您不必担心它会清空您的配置文件**

### Proton

有一个特殊的 egg 使用 proton 而不是原生 Linux 版本，附带 `winmm.dll` 和 `RE-UE4SS`，因此想要运行模组的人可以使用它。

请记住，这个 egg 的控制台输出已损坏（感谢 proton / wine），所以您只会看到解析器输出。RCON 控制台仍然有效。


### 配置

配置文件位于以下路径：`Pal/Saved/Config/LinuxServer/PalWorldSettings.ini` 或者如果您正在运行 proton egg `Pal/Saved/Config/WindowsServer/PalWorldSettings.ini`

