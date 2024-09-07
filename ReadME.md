## MultiplePupils | 重瞳

<img src="https://socialify.git.ci/A-little-dragon/MultiplePupils/image?font=Jost&forks=1&issues=1&language=1&name=1&owner=1&pattern=Brick%20Wall&pulls=1&stargazers=1&theme=Dark" alt="MultiplePupils" width="640" height="320" />

### 0x01 工具描述

MultiplePupils 是TracelessSec团队开发的一款信息收集工具，主要用于红队渗透过程中网络空间资产收集，旨在方便渗透测试工程师的信息收集，并尽可能减少渗透过程中资产收集耗费的时间。

![](https://img.shields.io/github/release/A-little-dragon/MultiplePupils) ![](https://img.shields.io/badge/c++-E53236.svg?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+QysrPC90aXRsZT48cGF0aCBkPSJNMjIuMzk0IDZjLS4xNjctLjI5LS4zOTgtLjU0My0uNjUyLS42OUwxMi45MjYuMjJjLS41MDktLjI5NC0xLjM0LS4yOTQtMS44NDggMEwyLjI2IDUuMzFjLS41MDguMjkzLS45MjMgMS4wMTMtLjkyMyAxLjZ2MTAuMThjMCAuMjk0LjEwNC42Mi4yNzEuOTEuMTY3LjI5LjM5OC41NDMuNjUyLjY5bDguODE2IDUuMDljLjUwOC4yOTMgMS4zNC4yOTMgMS44NDggMGw4LjgxNi01LjA5Yy4yNTQtLjE0Ny40ODUtLjQuNjUyLS42OS4xNjctLjI5LjI3LS42MTYuMjctLjkxVjYuOTFjLjAwMy0uMjk0LS4xLS42Mi0uMjY4LS45MXpNMTIgMTkuMTFjLTMuOTIgMC03LjEwOS0zLjE5LTcuMTA5LTcuMTEgMC0zLjkyIDMuMTktNy4xMSA3LjExLTcuMTFhNy4xMzMgNy4xMzMgMCAwMTYuMTU2IDMuNTUzbC0zLjA3NiAxLjc4YTMuNTY3IDMuNTY3IDAgMDAtMy4wOC0xLjc4QTMuNTYgMy41NiAwIDAwOC40NDQgMTIgMy41NiAzLjU2IDAgMDAxMiAxNS41NTVhMy41NyAzLjU3IDAgMDAzLjA4LTEuNzc4bDMuMDc4IDEuNzhBNy4xMzUgNy4xMzUgMCAwMTEyIDE5LjExem03LjExLTYuNzE1aC0uNzl2Ljc5aC0uNzl2LS43OWgtLjc5di0uNzloLjc5di0uNzloLjc5di43OWguNzl6bTIuOTYyIDBoLS43OXYuNzloLS43OXYtLjc5aC0uNzl2LS43OWguNzl2LS43OWguNzl2Ljc5aC43OXoiLz48L3N2Zz4=) ![](https://img.shields.io/badge/QT-41CD52.svg?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+UXQ8L3RpdGxlPjxwYXRoIGQ9Ik0yMS42OTMgMy4xNjJIMy4zM0wwIDYuNDl2MTQuMzQ4aDIwLjY3MUwyNCAxNy41MVYzLjE2MnpNMTIuNzg1IDE4LjRsLTEuNTYyLjcyOC0xLjM1LTIuMjE3Yy0uMTk2LjA1Ny0uNDk5LjA5LS45MjQuMDktMS41NzkgMC0yLjY4My0uNDI1LTMuMzA1LTEuMjc2LS42MjItLjg1LS45MzItMi4yLS45MzItNC4wMzMgMC0xLjg0LjMxOS0zLjIwNi45NDktNC4wOTguNjMtLjg5MiAxLjcyNi0xLjM0MSAzLjI4OC0xLjM0MSAxLjU2MiAwIDIuNjU4LjQ0MSAzLjI4IDEuMzMzLjYzLjg4My45NCAyLjI1Ljk0IDQuMDk4IDAgMS4yMTktLjEzIDIuMi0uMzg0IDIuOTQ1LS4yNjEuNzUyLS42NzkgMS4zMjUtMS4yNjggMS43MTh6bTQuNzM2LTEuNTg3Yy0uODU4IDAtMS40NDctLjE5Ni0xLjc2Ni0uNTktLjMyLS4zOTItLjQ4My0xLjEzNi0uNDgzLTIuMjMydi0zLjUzNEgxNC4xMVY5LjA1MWgxLjE2MlY2Ljg0M2gxLjY0NFY5LjA1aDIuMDk0djEuNDE1aC0yLjA5NHYzLjM0NmMwIC42MjIuMDUgMS4wMy4xNCAxLjIyNy4wOS4yMDQuMzI2LjMwMy42OTUuMzAzbDEuMjQzLS4wNS4wNzMgMS4zMjZjLS42Ny4xMy0xLjE4Ni4xOTYtMS41NDYuMTk2em0tOC41OC05LjA4Yy0uOTUgMC0xLjYwNC4zMTEtMS45NjMuOTQtLjM1Mi42My0uNTMyIDEuNjI5LS41MzIgMy4wMTEgMCAxLjM3NC4xNzIgMi4zNjQuNTE1IDIuOTUzLjM0NC41ODkgMS4wMDYuODkyIDEuOTguODkyLjk3MyAwIDEuNjI4LS4yOTUgMS45NzEtLjg3Ni4zMzUtLjU4LjUwNy0xLjU3LjUwNy0yLjk1MyAwLTEuMzktLjE3Mi0yLjM5Ni0uNTIzLTMuMDI2LS4zNTItLjYzLTEuMDA2LS45NC0xLjk1NS0uOTRaIi8+PC9zdmc+)

### 0x02 目前支持的功能

1. 支持对FOFA、Quake、Hunter等平台的查询功能。
2. 支持Crt.sh平台证书透明度查询
3. 资产测绘功能支持显示ICON图标，并且点击图标时，会复制该图标对应平台的语法。
4. 支持翻页查询，且之前记录会一直保留
5. 支持导出CSV格式文件

### 0x03 下载方式

支持免安装和安装两种方式：
1. 免安装版 ==> MultiplePupils.zip
2. 安装版 ==> MultiplePupils-windows-x64-setup.exe

### 0x04 版本规划

- MultiplePupils v1.1.0 
  - 将支持 其他测绘平台查询功能，并增加浏览器hacker语法查询

- MultiplePupils v1.2.0 
  - 将支持查询结果导入数据库功能，该功能主要用于特征资产监控清洗等等。

### Star History

![Star History Chart](https://starchart.cc/A-little-dragon/MultiplePupils.svg)

### 0x05 工具展示

![72d970ce5c016165bb284de120f4fa7](./image/72d970ce5c016165bb284de120f4fa7.png)

![b871d68c3ec15812d9bf014b287e5c1](./image/b871d68c3ec15812d9bf014b287e5c1.png)

![b871d68c3ec15812d9bf014b287e5c1](./image/b871d68c3ec15812d9bf014b287e5c1-1725118325004-3.png)

![d0f7b247d892b778e0e9add3e84ef59](./image/d0f7b247d892b778e0e9add3e84ef59.png)

![152096296ac607cb7715ab1817bb85f](./image/152096296ac607cb7715ab1817bb85f.png)

![b51cff127913aaae9d73076eb8c94f6](./image/b51cff127913aaae9d73076eb8c94f6.png)

![b663666197a932d0beda51d688bae79](./image/b663666197a932d0beda51d688bae79.png)
