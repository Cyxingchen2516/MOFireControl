# MOFireControl

《心灵终结 3.3.6》（Mental Omega 3.3.6）的客户端插件。

## 功能

- 对指定类型（默认冥卫坦克 CHRTNK、SUPR、TENGU、UMIN 等）接管射击目标选择
- 只处理载具/步兵，建筑不处理；无武器单位无动作

## 配置

```ini
[FireControl]
Enable=1
Types=      ; 留空 = 使用内置列表；填类型 ID 可追加
Log=1
```
## 安装

1. 需要先安装 [Syringe](https://github.com/Ares-Developers/Syringe)（心灵终结自带）。
2. 把本目录下的文件放进游戏根目录（`gamemd.exe` 所在目录）。
3. 启动游戏即可。删除文件即卸载。

## 说明

- 纯客户端插件：不修改游戏模拟数据、不发送指令，联机时对方无需安装。
