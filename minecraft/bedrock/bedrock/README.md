# Minecraft Bedrock

The official Minecraft Bedrock (Formerly Minecraft Pocket Edition) server.

This is an alpha release server from the mojang team.

### 服务器端口

Bedrock requires a single port (默认值 19132)

| 端口 | 默认值  |
|---------|----------|
| 游戏 | 19132    |

### 已知问题
Also see the [Mojang Issue tracker](https://bugs.mojang.com/projects/BDS/issues/)

* On start the server will report is is listening on port 19132 but is listening on the correct port
* Constant `NO LOG FILE` in the console before every log line.
* Server chat is not printed to the console.
* when you set ops in game they do not get saved.

### arm64
* The arm64 may not perform as expected due to the amd64 to arm emulaton.
