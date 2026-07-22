# 截图清单

这些截图用于 GitHub README、项目介绍页和后续宣传图。

推荐图片目录：

```text
assets/screenshots/
```

## 必备截图

当前已自动截取：

```text
assets/screenshots/room-teammates.png
assets/screenshots/room-teammates-long.png
assets/screenshots/current-match-real.png
assets/screenshots/battle-hit-distribution.png
assets/screenshots/party-analysis.png
assets/screenshots/player-record.png
assets/screenshots/query-real.png
assets/screenshots/control-center-real.png
assets/screenshots/collection-real.png
assets/screenshots/public-query.png
assets/screenshots/recent-matches.png
assets/screenshots/live-assistant.png
assets/screenshots/ops-control-center.png
assets/screenshots/battle-detail.png
assets/screenshots/party-insight.png
assets/screenshots/qq-summary.png
```

说明：

```text
新增的 *-real.png、room-teammates*.png、player-record.png、
battle-hit-distribution.png 和 party-analysis.png
均来自实际运行页面，昵称等可识别信息已做遮挡，且不包含内部查询标识。
party-insight.png 和 qq-summary.png 为演示数据生成图，用于展示产品形态。
```

### 1. 开局前房间队友近 3 场

文件名：

```text
assets/screenshots/room-teammates.png
```

画面包含：

- 房间成员与匹配队友人数。
- 4/4 等实时加载进度。
- 每名队友近 3 场战绩。
- 可直接复制到群聊的摘要。

完整详情使用 `room-teammates-long.png`。

### 2. 当前对局助手

文件名：

```text
assets/screenshots/current-match-real.png
```

画面包含：

- 左侧 10 名玩家英雄头像。
- 蓝色和红色阵营边框。
- 10/10 异步加载状态。
- 疑似组队关系参考。

### 3. 单个玩家近期战绩

文件名：

```text
assets/screenshots/player-record.png
```

画面包含英雄、KDA、ACS、地图、段位、RR 与高光数据。

### 4. 单局 10 人命中分布

文件名：

```text
assets/screenshots/battle-hit-distribution.png
```

画面展示双方 10 人的英雄、段位、K/D/A、ACS/分数、单局爆头率和头/身/腿命中分布。

### 5. 疑似组队共同对局分析

文件名：

```text
assets/screenshots/party-analysis.png
```

画面展示主动展开后的疑似小队、共同场次、友方/敌方关系和共同对局样例。

### 6. 公开查询页

文件名：

```text
assets/screenshots/query-real.png
```

打开地址：

```text
https://val.skzspro.cn/public
```

画面要求：

- 输入框中展示一个 `昵称#ID`。
- 页面干净，不露后台管理信息。
- 最好能看到主站品牌或页面标题。

### 7. 武器藏品

文件名：

```text
assets/screenshots/collection-real.png
```

画面展示武器外观列表和图片。

### 8. 控制中心

文件名：

```text
assets/screenshots/control-center-real.png
```

画面展示主要组件状态、HTTP 检查与登录态健康情况。

## 历史与概念图

### 近几场战绩结果

文件名：

```text
assets/screenshots/recent-matches.png
```

画面要求：

- 至少露出 5 场战绩。
- 能看到英雄、KDA、ACS、地图、段位、RR。
- 画面要让玩家一眼明白“这是拿来查战绩的”。

### 当前对局助手

文件名：

```text
assets/screenshots/live-assistant.png
```

画面要求：

- 左侧阵营栏露出。
- 上方我方，下方敌方。
- 右侧展示至少一个玩家的近 10 场战绩。
- 如果有 `10/10 已加载` 之类状态，也尽量露出来。

### 疑似组队关系

文件名：

```text
assets/screenshots/party-insight.png
```

画面要求：

- 截到疑似组队或交叉对局区域。
- 能看到玩家之间的关系。
- 能看到友方/敌方说明。

### QQ 群文本回复

文件名：

```text
assets/screenshots/qq-summary.png
```

画面要求：

- 用户发送 `查瓦 昵称#ID`。
- 机器人返回近 5 场战绩。
- 截图前遮挡 QQ 号、群名和头像。

### 控制中心

文件名：

```text
assets/screenshots/ops-control-center.png
```

画面要求：

- 能看到组件状态表。
- 能看到自动检测修复、日志查看等按钮。
- 最好大部分组件是绿色正常状态。

## README 推荐展示顺序

如果只放三张图，建议：

1. `room-teammates.png`
2. `current-match-real.png`
3. `battle-hit-distribution.png`
4. `party-analysis.png`
5. `player-record.png`
6. `query-real.png`
7. `control-center-real.png`

如果要做宣传图，建议标题：

```text
国服无畏契约战绩查询与当前对局助手
```

副标题：

```text
开局前看队友近3场 · 当前对局10人战绩 · 昵称#ID直查
```
