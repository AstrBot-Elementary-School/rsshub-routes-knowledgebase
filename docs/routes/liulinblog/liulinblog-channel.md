# 木木博客 - 频道

## Coverage
`index-only`

## Route
- Namespace: `liulinblog`
- Namespace Name: `木木博客`
- Route Path: `/liulinblog/:channel?`
- Route Name: `频道`
- Example: `/liulinblog`
- URL: `liulinblog.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新 | 60 秒读懂世界 | 精品资源 | 视频资源 | 音频资源 |
| ---- | ------------- | -------- | -------- | -------- |
|      | kuaixun       | ziyuan   | video    | yinpin   |

| 绝版资源 | 实用文档 | PPT 素材  | 后期素材 | 技能教程  |
| -------- | -------- | --------- | -------- | --------- |
| jueban   | wendang  | ppt-sucai | sucai    | jiaocheng |

| 创业副业 | 单机游戏 | 冒险解谜 | 竞技格斗    | 赛车竞技 |
| -------- | -------- | -------- | ----------- | -------- |
| money    | game     | mxjm     | jingjigedou | saiche   |

| 模拟经营 | 角色扮演 | 飞行游戏 | 塔防策略 | 射击游戏 |
| -------- | -------- | -------- | -------- | -------- |
| moni     | jiaose   | feixing  | tafang   | sheji    |

| 恐怖冒险 | 策略生存 | 动作冒险 | 电商运营  | 互联网早报 |
| -------- | -------- | -------- | --------- | ---------- |
| kongbu   | celve    | dongzuo  | dianshang | internet   |

| 站长圈 | 自媒体运营 | 短视频      |
| ------ | ---------- | ----------- |
| seo    | zimeiti    | duan-shipin |

## Parameters
- `channel`: 频道 id，可在对应频道页 URL 中找到，见下表，默认为最新


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `liulinblog.com/:channel`
  - `liulinblog.com/`
- `target`: `/:channel`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新 | 60 秒读懂世界 | 精品资源 | 视频资源 | 音频资源 |\n| ---- | ------------- | -------- | -------- | -------- |\n|      | kuaixun       | ziyuan   | video    | yinpin   |\n\n| 绝版资源 | 实用文档 | PPT 素材  | 后期素材 | 技能教程  |\n| -------- | -------- | --------- | -------- | --------- |\n| jueban   | wendang  | ppt-sucai | sucai    | jiaocheng |\n\n| 创业副业 | 单机游戏 | 冒险解谜 | 竞技格斗    | 赛车竞技 |\n| -------- | -------- | -------- | ----------- | -------- |\n| money    | game     | mxjm     | jingjigedou | saiche   |\n\n| 模拟经营 | 角色扮演 | 飞行游戏 | 塔防策略 | 射击游戏 |\n| -------- | -------- | -------- | -------- | -------- |\n| moni     | jiaose   | feixing  | tafang   | sheji    |\n\n| 恐怖冒险 | 策略生存 | 动作冒险 | 电商运营  | 互联网早报 |\n| -------- | -------- | -------- | --------- | ---------- |\n| kongbu   | celve    | dongzuo  | dianshang | internet   |\n\n| 站长圈 | 自媒体运营 | 短视频      |\n| ------ | ---------- | ----------- |\n| seo    | zimeiti    | duan-shipin |",
  "example": "/liulinblog",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "频道",
  "parameters": {
    "channel": "频道 id，可在对应频道页 URL 中找到，见下表，默认为最新"
  },
  "path": "/:channel?",
  "radar": [
    {
      "source": [
        "liulinblog.com/:channel",
        "liulinblog.com/"
      ],
      "target": "/:channel"
    }
  ],
  "topFeeds": []
}
```
