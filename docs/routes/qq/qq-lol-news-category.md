# 腾讯网 - 英雄联盟新闻

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/qq/lol/news/:category?`
- Route Name: `英雄联盟新闻`
- Example: `/qq/lol/news`
- URL: `lol.qq.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `lol/news.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [英雄联盟首页新闻列表 - 公告](https://lol.qq.com/news/index.shtml)，网址为 `https://lol.qq.com/news/index.shtml`，请选择 `24` 作为 `category` 参数填入，此时目标路由为 [`/qq/lol/news/24`](https://rsshub.app/qq/lol/news/24)。
:::

| 综合 | 公告 | 赛事 | 攻略 | 社区 |
| ---- | ---- | ---- | ---- | ---- |
| 23   | 24   | 25   | 27   | 28   |

## Parameters
- `category`: 分类，默认为 `23`，即综合，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `综合`
- `source`:
  - `lol.qq.com/news/index.shtml`
- `target`: `/lol/news/23`
### Rule 2
- `title`: `公告`
- `source`:
  - `lol.qq.com/news/index.shtml`
- `target`: `/lol/news/24`
### Rule 3
- `title`: `赛事`
- `source`:
  - `lol.qq.com/news/index.shtml`
- `target`: `/lol/news/25`
### Rule 4
- `title`: `攻略`
- `source`:
  - `lol.qq.com/news/index.shtml`
- `target`: `/lol/news/27`
### Rule 5
- `title`: `社区`
- `source`:
  - `lol.qq.com/news/index.shtml`
- `target`: `/lol/news/28`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [英雄联盟首页新闻列表 - 公告](https://lol.qq.com/news/index.shtml)，网址为 `https://lol.qq.com/news/index.shtml`，请选择 `24` 作为 `category` 参数填入，此时目标路由为 [`/qq/lol/news/24`](https://rsshub.app/qq/lol/news/24)。\n:::\n\n| 综合 | 公告 | 赛事 | 攻略 | 社区 |\n| ---- | ---- | ---- | ---- | ---- |\n| 23   | 24   | 25   | 27   | 28   |",
  "example": "/qq/lol/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 8,
  "location": "lol/news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "英雄联盟新闻",
  "parameters": {
    "category": "分类，默认为 `23`，即综合，见下表"
  },
  "path": "/lol/news/:category?",
  "radar": [
    {
      "source": [
        "lol.qq.com/news/index.shtml"
      ],
      "target": "/lol/news/23",
      "title": "综合"
    },
    {
      "source": [
        "lol.qq.com/news/index.shtml"
      ],
      "target": "/lol/news/24",
      "title": "公告"
    },
    {
      "source": [
        "lol.qq.com/news/index.shtml"
      ],
      "target": "/lol/news/25",
      "title": "赛事"
    },
    {
      "source": [
        "lol.qq.com/news/index.shtml"
      ],
      "target": "/lol/news/27",
      "title": "攻略"
    },
    {
      "source": [
        "lol.qq.com/news/index.shtml"
      ],
      "target": "/lol/news/28",
      "title": "社区"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "英雄联盟官方网站，海量风格各异的英雄，丰富、便捷的物品合成系统，游戏内置的匹配、排行和竞技系统，独创的“召唤师”系统及技能、符文、天赋等系统组合，必将带你进入一个崭新而又丰富多彩的游戏世界。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101911164632930304",
      "image": "https://game.gtimg.cn/images/lol/v3/logo-public.png",
      "ownerUserId": null,
      "siteUrl": "https://lol.qq.com/news/index.shtml",
      "title": "英雄联盟首页新闻列表 - 综合",
      "type": "feed",
      "url": "rsshub://qq/lol/news"
    },
    {
      "description": "英雄联盟官方网站，海量风格各异的英雄，丰富、便捷的物品合成系统，游戏内置的匹配、排行和竞技系统，独创的“召唤师”系统及技能、符文、天赋等系统组合，必将带你进入一个崭新而又丰富多彩的游戏世界。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "206218993552190464",
      "image": "https://game.gtimg.cn/images/lol/v3/logo-public.png",
      "ownerUserId": null,
      "siteUrl": "https://lol.qq.com/news/index.shtml",
      "title": "英雄联盟首页新闻列表 - 综合",
      "type": "feed",
      "url": "rsshub://qq/lol/news/23"
    }
  ],
  "url": "lol.qq.com",
  "view": 0
}
```
