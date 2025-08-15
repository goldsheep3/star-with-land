---
title: 整合包半自助更新工具！
date: 2025-08-15
categories: minecraft
tags:
- Minecraft
- Python
---

> 工具链接：[goldsheep3/mcpack_update_pyinstaller](https://github.com/goldsheep3/mcpack_update_pyinstaller)

给流光的小服帮忙的时候，意识到如果小包想更新还是有点麻烦的。每次一点小更新，发个压缩包解压有人不太熟悉，发完整包还有点太大了很过分。
于是搞了这样一个小工具。

服主打包的时候，将 `mcpack_update.exe` 放在 Minecraft 版本目录（与版本 jar、json 文件同级），就可以啦。
玩家使用的时候，只需要下载包，将压缩包放到可以通过 PCL2 自动打开的版本文件夹，然后运行就可以跟着指引更新了。

## 服主创建压缩包

每次小更新的时候，将需要加入的内容压缩到 `mcpUpdate_xxxxxx.zip`（6位数字），这个就是合格的更新包了。

如果有想删除的文件或文件夹，就创建一个 `mcpUpdate_remove.txt` 也压缩到包内。
每行写一个需要删除的文件或目录的相对路径（相对于版本目录，分隔符用 `/` ），如：

```
mods/modB.jar
config/configB.cfg
options.txt
kubejs
```

特别确定的逻辑顺序是，删除操作会在解压前进行。
确保 `kubejs` 这样的目录能被彻底清理后再覆盖。
同时，程序运行结束后，更新包和删除列表也会自动清理，程序本身仍然留在原地。

## TODO

正在着手准备联网更新的方式，通过一个配置文件，直接自动获取并更新。
因为目前这样的程序够用，于是还没想怎么做。
