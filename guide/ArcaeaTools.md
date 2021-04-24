# ArcaeaTools

## Arcaea 账号管理

### 绑定账号

```
/arc bind <ArcaeaID>
```

注意：0开头的ArcaeaID 无法添加

### 取消绑定账号

```
/arc unbind
```

### 账号设定

#### 基本指令

```
/arc config
```

##### 更换主题

```
/arc config theme <Theme ID>
```

现在有以下主题：

| Theme ID | 详细                    |
| -------- | ----------------------- |
| text     | 文字查询                |
| arc      | Arcaea 风查分界面       |
| chiarc   | ChiBotの查分界面（WIP） |

## Arcaea 分数查询

### Arcaea 最近分数

```
/arc info
```

需要绑定账号

会有点慢，请不要重复查询

### Arcaea Best30

```
/arc b30
```

由于Best30的特殊性，所以会查得慢，请不要重复查询

## Arcaea 曲目

### Arcaea 曲目查询

```
/arc si <SongName>
```

## Arcaea比赛

### Arcaea比赛 开房间

```
/arc-mp <songsid> <difficult>
```

需要绑定账号，仅限4个人

#### difficult详细

| 0    | 过去（PST） |
| ---- | ----------- |
| 1    | 现在（PRE） |
| 2    | 未来（FTR） |
| 3    | 超越（BYD） |

### Arcaea比赛 加入比赛

```
/arc-mp-join <RoomID>
```

需要绑定账号

### Arcaea比赛 查看房间

```
/arc-mp-info
```

> 权限：房间房主

### Arcaea比赛 开始比赛

```
/arc-mp-start
```

> 权限：房间房主

### Arcaea比赛 删除房间

```
/arc-mp-del
```

> 权限：房间房主