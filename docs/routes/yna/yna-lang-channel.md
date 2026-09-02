# Yonhap News Agency - News

## Coverage
`index-only`

## Route
- Namespace: `yna`
- Namespace Name: `Yonhap News Agency`
- Route Path: `/yna/:lang?/:channel?`
- Route Name: `News`
- Example: `/yna/en/national`
- URL: `yna.co.kr`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Language | 한국어 | English | 简体中文 | 日本語 | عربي | Español | Français |
| -------- | ------ | ------- | -------- | ------ | ---- | ------- | -------- |
| `:lang`  | `ko`   | `en`    | `cn`     | `jp`   | `ar` | `es`    | `fr`     |

For a full list of RSS Feed Channels, please refer to the RSS feed page of the corresponding language

| RSS Feed Page                                             |
| --------------------------------------------------------- |
| [한국어](https://www.yna.co.kr/rss/index?site=footer_rss) |
| [English](https://en.yna.co.kr/channel/index)             |
| [简体中文](https://cn.yna.co.kr/channel/index)            |
| [日本語](https://jp.yna.co.kr/channel/index)              |
| [عربي](https://ar.yna.co.kr/channel/index)                |
| [Español](https://sp.yna.co.kr/channel/index)             |
| [Français](https://fr.yna.co.kr/channel/index)            |

::: tip
For example, the path for the RSS feed url <https://www.yna.co.kr/rss/economy.xml> and <https://cn.yna.co.kr/RSS/news.xml> would be `/ko/economy` and `/cn/news` respectively.
:::

## Parameters
- `lang`: Language, see below, `ko` by default
- `channel`: RSS Feed Channel, see below, `news` by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Language | 한국어 | English | 简体中文 | 日本語 | عربي | Español | Français |\n| -------- | ------ | ------- | -------- | ------ | ---- | ------- | -------- |\n| `:lang`  | `ko`   | `en`    | `cn`     | `jp`   | `ar` | `es`    | `fr`     |\n\nFor a full list of RSS Feed Channels, please refer to the RSS feed page of the corresponding language\n\n| RSS Feed Page                                             |\n| --------------------------------------------------------- |\n| [한국어](https://www.yna.co.kr/rss/index?site=footer_rss) |\n| [English](https://en.yna.co.kr/channel/index)             |\n| [简体中文](https://cn.yna.co.kr/channel/index)            |\n| [日本語](https://jp.yna.co.kr/channel/index)              |\n| [عربي](https://ar.yna.co.kr/channel/index)                |\n| [Español](https://sp.yna.co.kr/channel/index)             |\n| [Français](https://fr.yna.co.kr/channel/index)            |\n\n::: tip\nFor example, the path for the RSS feed url <https://www.yna.co.kr/rss/economy.xml> and <https://cn.yna.co.kr/RSS/news.xml> would be `/ko/economy` and `/cn/news` respectively.\n:::",
  "example": "/yna/en/national",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "News",
  "parameters": {
    "channel": "RSS Feed Channel, see below, `news` by default",
    "lang": "Language, see below, `ko` by default"
  },
  "path": "/:lang?/:channel?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "韩国联合通讯社 | 滚动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87238542461270016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.yna.co.kr/news",
      "title": "韩国联合通讯社 | 滚动",
      "type": "feed",
      "url": "rsshub://yna/cn"
    },
    {
      "description": "연합뉴스 실시간 최신뉴스입니다 - Powered by RSSHub",
      "errorAt": "2026-05-03T00:09:17.115Z",
      "errorMessage": "Failed to fetch\n",
      "id": "91658914231308288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yna.co.kr/news",
      "title": "연합뉴스 최신기사",
      "type": "feed",
      "url": "rsshub://yna/ko/news"
    }
  ]
}
```
