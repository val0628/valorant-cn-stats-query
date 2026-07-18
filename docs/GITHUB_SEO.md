# GitHub 搜索与引流设置

目标：让玩家搜索 `无畏契约战绩查询`、`瓦战绩查询`、`国服无畏契约战绩查询` 时，更容易找到 GitHub 项目，并从项目页进入主站。

主站：

```text
https://val.skzspro.cn/public
```

## 仓库名建议

推荐仓库名：

```text
valorant-cn-stats-query
```

备选：

```text
wuwei-qiyue-stats
valorant-cn-record
wgame-val-query
valorant-wegame-query
```

说明：

- 英文仓库名更适合 GitHub URL。
- README 标题使用中文关键词：`无畏契约战绩查询 | WGame VAL Query`。
- 仓库名不用太长，关键词放 README 和 About 里。

## GitHub About 设置

Description 建议：

```text
无畏契约战绩查询、国服 Valorant 近期战绩、当前对局助手、QQ 群战绩回复。输入昵称#ID，在线查看 KDA、ACS、地图、段位和 RR。
```

Website 填：

```text
https://val.skzspro.cn/public
```

Topics 建议：

```text
valorant
valorant-cn
valorant-stats
wuweiqiyue
无畏契约
无畏契约战绩查询
瓦战绩查询
wegame
qq-bot
game-stats
```

如果 GitHub 不接受中文 topic，就保留英文 topic，把中文关键词放 README。

## README 首屏要求

README 前 200 字必须自然出现这些词：

- 无畏契约战绩查询
- 国服无畏契约
- Valorant 战绩查询
- 昵称#ID
- 当前对局助手
- QQ 群战绩回复
- 主站地址

当前 README 已按这个方向写好。

## 搜索结果里要让用户马上知道什么

用户点进 GitHub 后，第一屏应该立刻看到：

1. 这是无畏契约战绩查询。
2. 可以输入昵称#ID。
3. 有在线网站。
4. 网站地址很明显。
5. 项目不是让用户自己部署，而是直接去主站用。

## 截图对转化很重要

最优先补这三张：

```text
assets/screenshots/recent-matches.png
assets/screenshots/live-assistant.png
assets/screenshots/ops-control-center.png
```

图片文件名也要带语义，方便搜索和传播。

## Issue 引导

建议开启 Issues，用来接收：

- 查询失败的昵称样例
- 玩家想要的新字段
- QQ 群机器人需求
- 当前对局助手建议

不要让用户提交 Cookie、token、抓包文件。

可以放一个置顶 Issue：

```text
【反馈入口】无畏契约战绩查询失败 / 新功能建议
```

## Star 引导文案

README 里的 Star 文案不要太硬，可以这样：

```text
如果你也想要一个更顺手的国服无畏契约战绩查询入口，欢迎点一个 Star。Star 能让更多玩家找到这个工具，也会推动我们继续优化当前对局助手和 QQ 群查询体验。
```

## 不建议做的事

- 不要在公开 README 写管理口令。
- 不要引导用户自己抓包。
- 不要上传核心服务端。
- 不要承诺 100% 可查所有玩家。
- 不要写“真实 IP 查询”这类容易引发误解的关键词。

推荐说法是：

```text
掌瓦公开 IP 属地
```

不要说：

```text
查询玩家真实 IP
```
