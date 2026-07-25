# FT 中文网 - FT 中文网

## Coverage
`index-only`

## Route
- Namespace: `ftchinese`
- Namespace Name: `FT 中文网`
- Route Path: `/ftchinese/:language/:channel?`
- Route Name: `FT 中文网`
- Example: `/ftchinese/simplified/hotstoryby7day`
- URL: `ftchinese.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `HenryQW, xyqfer`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
::: tip

- 不支持付费文章。

:::

通过提取文章全文，以提供比官方源更佳的阅读体验。

支持所有频道，频道名称见 [官方频道 RSS](http://www.ftchinese.com/channel/rss.html).

- 频道为单一路径，如 `http://www.ftchinese.com/rss/news` 则为 `/ftchinese/simplified/news`.
- 频道包含多重路径，如 `http://www.ftchinese.com/rss/column/007000002` 则替换 `/` 为 `-` `/ftchinese/simplified/column-007000002`.

## Parameters
- `language`: 语言，简体 `simplified`，繁体 `traditional`
- `channel`: 频道，缺省为每日更新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n\n- 不支持付费文章。\n\n:::\n\n通过提取文章全文，以提供比官方源更佳的阅读体验。\n\n支持所有频道，频道名称见 [官方频道 RSS](http://www.ftchinese.com/channel/rss.html).\n\n- 频道为单一路径，如 `http://www.ftchinese.com/rss/news` 则为 `/ftchinese/simplified/news`.\n- 频道包含多重路径，如 `http://www.ftchinese.com/rss/column/007000002` 则替换 `/` 为 `-` `/ftchinese/simplified/column-007000002`.",
  "example": "/ftchinese/simplified/hotstoryby7day",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 997,
  "location": "channel.ts",
  "maintainers": [
    "HenryQW",
    "xyqfer"
  ],
  "name": "FT 中文网",
  "parameters": {
    "channel": "频道，缺省为每日更新",
    "language": "语言，简体 `simplified`，繁体 `traditional`"
  },
  "path": "/:language/:channel?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "FTChinese RSS - All Feed - Powered by RSSHub",
      "errorAt": "2026-07-09T06:29:25.553Z",
      "errorMessage": "[GET] \"https://www.ftchinese.com/story/001110411?full=y&archive\": 429 Too Many Requests\n[GET] \"https://www.ftchinese.com/story/001110411?full=y&archive\": 429 Too Many Requests\n[GET] \"https://www.ftchinese.com/story/001110411?full=y&archive\": 429 Too Many Requests\n[GET] \"https://www.ftchinese.com/story/001110411?full=y&archive\": 429 Too Many Requests\n[GET] \"https://www.ftchinese.com/story/001110375?full=y&archive\": 429 \n[GET] \"https://www.ftchinese.com/story/001110411?full=y&archive\": 429 Too Many Requests\n",
      "id": "61693185811247104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ftchinese.com/",
      "title": "FTChinese RSS - All Feed",
      "type": "feed",
      "url": "rsshub://ftchinese/simplified"
    },
    {
      "description": "FTChinese RSS - Hot Weekly - Powered by RSSHub",
      "errorAt": "2026-07-05T00:21:03.547Z",
      "errorMessage": "Cannot read properties of undefined (reading 'title')\nFailed to fetch\nCannot read properties of undefined (reading 'title')\n",
      "id": "41377818806739968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ftchinese.com/",
      "title": "FTChinese RSS - Hot Weekly",
      "type": "feed",
      "url": "rsshub://ftchinese/simplified/hotstoryby7day"
    }
  ]
}
```
