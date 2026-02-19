# Longvinter
Longvinter is a multiplayer, third-person sandbox game that implements Crafting, Farming, Building, Trading, and PVP.
___

### 服务器端口

- Default server ports are listed below, but all three ports can be changed freely.
- **Note:** The query ports does not seem to be used at all at the moment (at least on the linux server).

| 端口 | 默认值 |
|---------|---------|
| **Game (Primary Port in Pterodactyl)** | 7777 (UDP) |
| 查询 | 27015 (UDP/TCP) |
| Query +1 | 27016 (UDP/TCP) |

___

### 安装/系统要求

|  | Minimum | 
|---------|---------|
| 内存 | 2048 MiB |
| 存储 | 2 GB |

___

### 已知错误/警告

The following errors or warnings you see in the console can safely be ignored:

```log
[2022.05.15-00.07.35:353][508]LogEOS: Error: UpdateSession: 
Successfully updated session 'Test' with ID '18exxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
```

↑ This error is displayed regularly, but does not affect the server functions. An  [open issue](https://github.com/Uuvana-Studios/longvinter-linux-server/issues/40) already exists in the developers repository.