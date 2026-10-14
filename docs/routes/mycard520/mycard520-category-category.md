# MyCard娛樂中心 - 遊戲新聞

## Coverage
`index-only`

## Route
- Namespace: `mycard520`
- Namespace Name: `MyCard娛樂中心`
- Route Path: `/mycard520/category/:category?`
- Route Name: `遊戲新聞`
- Example: `/mycard520/category/cardgame`
- URL: `app.mycard520.com.tw`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [最新遊戲](https://app.mycard520.com.tw/category/cardgame/)，网址为 `https://app.mycard520.com.tw/category/cardgame/`，请截取 `https://app.mycard520.com.tw/category/` 到末尾 `/` 的部分 `cardgame` 作为 `category` 参数填入，此时目标路由为 [`/mycard520/category/cardgame`](https://rsshub.app/mycard520/category/cardgame)。
:::

| [最新遊戲](https://app.mycard520.com.tw/category/cardgame/) | [手機遊戲](https://app.mycard520.com.tw/category/cardgame-mobile/)       | [PC 遊戲](https://app.mycard520.com.tw/category/cardgame-pc/)    | [電競賽事](https://app.mycard520.com.tw/category/cardgame-esports/)        | [實況直播](https://app.mycard520.com.tw/category/cardgame-live/)     |
| ----------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [cardgame](https://rsshub.app/mycard520/category/cardgame)  | [cardgame-mobile](https://rsshub.app/mycard520/category/cardgame-mobile) | [cardgame-pc](https://rsshub.app/mycard520/category/cardgame-pc) | [cardgame-esports](https://rsshub.app/mycard520/category/cardgame-esports) | [cardgame-live](https://rsshub.app/mycard520/category/cardgame-live) |

## Parameters
- `category`: {"description": "分类，默认为 `cardgame`，即最新遊戲，可在对应分类页 URL 中找到", "options": [{"label": "最新遊戲", "value": "cardgame"}, {"label": "手機遊戲", "value": "cardgame-mobile"}, {"label": "PC 遊戲", "value": "cardgame-pc"}, {"label": "電競賽事", "value": "cardgame-esports"}, {"label": "實況直播", "value": "cardgame-live"}]}


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
- `source`:
  - `app.mycard520.com.tw/category/:category`
- `target`: `/category/:category`
### Rule 2
- `title`: `最新遊戲`
- `source`:
  - `app.mycard520.com.tw/category/cardgame`
- `target`: `/category/cardgame`
### Rule 3
- `title`: `手機遊戲`
- `source`:
  - `app.mycard520.com.tw/category/cardgame-mobile`
- `target`: `/category/cardgame-mobile`
### Rule 4
- `title`: `PC 遊戲`
- `source`:
  - `app.mycard520.com.tw/category/cardgame-pc`
- `target`: `/category/cardgame-pc`
### Rule 5
- `title`: `電競賽事`
- `source`:
  - `app.mycard520.com.tw/category/cardgame-esports`
- `target`: `/category/cardgame-esports`
### Rule 6
- `title`: `實況直播`
- `source`:
  - `app.mycard520.com.tw/category/cardgame-live`
- `target`: `/category/cardgame-live`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [最新遊戲](https://app.mycard520.com.tw/category/cardgame/)，网址为 `https://app.mycard520.com.tw/category/cardgame/`，请截取 `https://app.mycard520.com.tw/category/` 到末尾 `/` 的部分 `cardgame` 作为 `category` 参数填入，此时目标路由为 [`/mycard520/category/cardgame`](https://rsshub.app/mycard520/category/cardgame)。\n:::\n\n| [最新遊戲](https://app.mycard520.com.tw/category/cardgame/) | [手機遊戲](https://app.mycard520.com.tw/category/cardgame-mobile/)       | [PC 遊戲](https://app.mycard520.com.tw/category/cardgame-pc/)    | [電競賽事](https://app.mycard520.com.tw/category/cardgame-esports/)        | [實況直播](https://app.mycard520.com.tw/category/cardgame-live/)     |\n| ----------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------- |\n| [cardgame](https://rsshub.app/mycard520/category/cardgame)  | [cardgame-mobile](https://rsshub.app/mycard520/category/cardgame-mobile) | [cardgame-pc](https://rsshub.app/mycard520/category/cardgame-pc) | [cardgame-esports](https://rsshub.app/mycard520/category/cardgame-esports) | [cardgame-live](https://rsshub.app/mycard520/category/cardgame-live) |",
  "example": "/mycard520/category/cardgame",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "遊戲新聞",
  "parameters": {
    "category": {
      "description": "分类，默认为 `cardgame`，即最新遊戲，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "最新遊戲",
          "value": "cardgame"
        },
        {
          "label": "手機遊戲",
          "value": "cardgame-mobile"
        },
        {
          "label": "PC 遊戲",
          "value": "cardgame-pc"
        },
        {
          "label": "電競賽事",
          "value": "cardgame-esports"
        },
        {
          "label": "實況直播",
          "value": "cardgame-live"
        }
      ]
    }
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "app.mycard520.com.tw/category/:category"
      ],
      "target": "/category/:category"
    },
    {
      "source": [
        "app.mycard520.com.tw/category/cardgame"
      ],
      "target": "/category/cardgame",
      "title": "最新遊戲"
    },
    {
      "source": [
        "app.mycard520.com.tw/category/cardgame-mobile"
      ],
      "target": "/category/cardgame-mobile",
      "title": "手機遊戲"
    },
    {
      "source": [
        "app.mycard520.com.tw/category/cardgame-pc"
      ],
      "target": "/category/cardgame-pc",
      "title": "PC 遊戲"
    },
    {
      "source": [
        "app.mycard520.com.tw/category/cardgame-esports"
      ],
      "target": "/category/cardgame-esports",
      "title": "電競賽事"
    },
    {
      "source": [
        "app.mycard520.com.tw/category/cardgame-live"
      ],
      "target": "/category/cardgame-live",
      "title": "實況直播"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "app.mycard520.com.tw",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [最新游戏](https://app.mycard520.com.tw/category/cardgame/)，网址为 `https://app.mycard520.com.tw/category/cardgame/`，请截取 `https://app.mycard520.com.tw/category/` 到末尾 `/` 的部分 `cardgame` 作为 `category` 参数填入，此时目标路由为 [`/mycard520/category/cardgame`](https://rsshub.app/mycard520/category/cardgame)。\n:::\n\n| [最新游戏](https://app.mycard520.com.tw/category/cardgame/) | [手机游戏](https://app.mycard520.com.tw/category/cardgame-mobile/)       | [PC 游戏](https://app.mycard520.com.tw/category/cardgame-pc/)    | [电竞赛事](https://app.mycard520.com.tw/category/cardgame-esports/)        | [实况直播](https://app.mycard520.com.tw/category/cardgame-live/)     |\n| ----------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------- |\n| [cardgame](https://rsshub.app/mycard520/category/cardgame)  | [cardgame-mobile](https://rsshub.app/mycard520/category/cardgame-mobile) | [cardgame-pc](https://rsshub.app/mycard520/category/cardgame-pc) | [cardgame-esports](https://rsshub.app/mycard520/category/cardgame-esports) | [cardgame-live](https://rsshub.app/mycard520/category/cardgame-live) |",
    "name": "游戏新闻",
    "parameters": {
      "category": {
        "description": "分类，默认为 `cardgame`，即最新游戏，可在对应分类页 URL 中找到",
        "options": [
          {
            "label": "最新游戏",
            "value": "cardgame"
          },
          {
            "label": "手机游戏",
            "value": "cardgame-mobile"
          },
          {
            "label": "PC 游戏",
            "value": "cardgame-pc"
          },
          {
            "label": "电竞赛事",
            "value": "cardgame-esports"
          },
          {
            "label": "实况直播",
            "value": "cardgame-live"
          }
        ]
      }
    }
  }
}
```
