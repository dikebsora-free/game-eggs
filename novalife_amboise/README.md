# Nova-Life: Amboise

<!--Please remove these comments and irelevent parts for the server egg your adding before summiting a PR request-->
Nova-Life: Amboise is a multiplayer role-play simulation video game. Create your character and start your second life! 

## 安装/系统要求
<!--Make changes to reflect the server minimum/recommended hardware specs-->
|  | 最低要求 | 推荐 |
|---------|---------|---------|
| 处理器 | *AMD64 only and 250% cpu* | *350% cpu* |
| 内存 | *8GiB* | *9GiB* |
| 存储 | *6GiB* | *8GiB* |
| 网络 | *Any* | */* |
| 游戏所有权 | *Not needed* | *Needed if you want to upload your own savegame* |

## 服务器端口

Ports required to run the server in a table format.

| 端口 | default |
|---------|---------|
| 游戏 | 7777    |

### 备注

<!--Notes about the server ports.-->
7777 is the default port, but any port can be used.

The egg created a default server on install based on the `Server Name` variable at `/home/container/Servers/<server_name>` and sets the port and max players in the config file. 

Because the directory can change their is no way if you upload your own `life.db` and `/home/container/Servers/<server_name>/Config/server.json` that we can parse the port so then you will have to manualy set the game port to the allocated port or you change the server name, hit reinstall and then replace the `life.db` file from the one the client generated.


### Variable parsing

As mentioned above all variable the client can see and change will only apply on reinstall.

### Errors

Because this game and server are still in development many errors will show in the console, those can safely be ignored.
