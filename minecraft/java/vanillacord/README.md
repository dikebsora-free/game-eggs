# VanillaCord

A patch for vanilla servers to work with BungeeCord's ip_forward setting.

This uses [ME1312's fork](https://github.com/ME1312/VanillaCord) of VanillaCord which has been updated for modern Minecraft.

## 备注

If you've set up Spigot, Paper or some other server with BungeeCord's IP forwarding you might know that you have to set online-mode to false. Due to the way that VanillaCord works this is not necessary with this Egg, you can (and should) leave online-mode as true.

## 服务器端口

The minecraft server requires a single port for access (default 25565) but plugins may require extra ports to enabled for the server.

| 端口 | default |
|-------|---------|
| 游戏 | 25565   |
