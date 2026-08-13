# Jones Lang LaSalle - Trends & Insights

## Coverage
`index-only`

## Route
- Namespace: `joneslanglasalle`
- Namespace Name: `Jones Lang LaSalle`
- Route Path: `/joneslanglasalle/:language?/:category{.+}?`
- Route Name: `Trends & Insights`
- Example: `/joneslanglasalle/en/trends-and-insights`
- URL: `joneslanglasalle.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [Trends & Insights (China)](https://www.joneslanglasalle.com.cn/en-cn/insights), use `en` as the language. For [Hong Kong Insights](https://www.jll.com/zh-hk/insights), use `zh-hk` as the language.
:::

| Region         | Language | Parameter |
| -------------- | -------- | --------- |
| China Mainland | 中文     | zh        |
| China Mainland | English  | en        |
| Hong Kong      | 中文     | zh-hk     |
| Hong Kong      | English  | en-hk     |

## Parameters
- `language`: Language, `zh` for China Mainland Chinese, `en` for China Mainland English, `zh-hk` for Hong Kong Chinese, `en-hk` for Hong Kong English, `zh` by default
- `category`: Category, `trends-and-insights` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `joneslanglasalle.com.cn/:language/:category`
### Rule 2
- `title`: `Latest`
- `source`:
  - `joneslanglasalle.com.cn/en-cn/insights`
- `target`: `/en/trends-and-insights`
### Rule 3
- `title`: `房地产趋势与洞察`
- `source`:
  - `joneslanglasalle.com.cn/zh-cn/insights`
- `target`: `/zh/trends-and-insights`
### Rule 4
- `source`:
  - `jll.com/zh-hk/insights`
- `target`: `/zh-hk/trends-and-insights`
### Rule 5
- `source`:
  - `jll.com/en-hk/insights`
- `target`: `/en-hk/trends-and-insights`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nIf you subscribe to [Trends & Insights (China)](https://www.joneslanglasalle.com.cn/en-cn/insights), use `en` as the language. For [Hong Kong Insights](https://www.jll.com/zh-hk/insights), use `zh-hk` as the language.\n:::\n\n| Region         | Language | Parameter |\n| -------------- | -------- | --------- |\n| China Mainland | 中文     | zh        |\n| China Mainland | English  | en        |\n| Hong Kong      | 中文     | zh-hk     |\n| Hong Kong      | English  | en-hk     |",
  "example": "/joneslanglasalle/en/trends-and-insights",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Trends & Insights",
  "parameters": {
    "category": "Category, `trends-and-insights` by default",
    "language": "Language, `zh` for China Mainland Chinese, `en` for China Mainland English, `zh-hk` for Hong Kong Chinese, `en-hk` for Hong Kong English, `zh` by default"
  },
  "path": "/:language?/:category{.+}?",
  "radar": [
    {
      "source": [
        "joneslanglasalle.com.cn/:language/:category"
      ]
    },
    {
      "source": [
        "joneslanglasalle.com.cn/en-cn/insights"
      ],
      "target": "/en/trends-and-insights",
      "title": "Latest"
    },
    {
      "source": [
        "joneslanglasalle.com.cn/zh-cn/insights"
      ],
      "target": "/zh/trends-and-insights",
      "title": "房地产趋势与洞察"
    },
    {
      "source": [
        "jll.com/zh-hk/insights"
      ],
      "target": "/zh-hk/trends-and-insights"
    },
    {
      "source": [
        "jll.com/en-hk/insights"
      ],
      "target": "/en-hk/trends-and-insights"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Insights - JLL China - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86976172947621888",
      "image": "https://www.joneslanglasalle.com.cn/content/dam/jll-com/images/logos/jll-logo-positive.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.joneslanglasalle.com.cn/en-cn/insights",
      "title": "Insights - JLL China",
      "type": "feed",
      "url": "rsshub://joneslanglasalle/en/trends-and-insights"
    }
  ],
  "url": "joneslanglasalle.com.cn",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [中国大陆洞察](https://www.joneslanglasalle.com.cn/zh-cn/insights)，语言参数为 `zh`。若订阅 [香港洞察](https://www.jll.com/zh-hk/insights)，语言参数为 `zh-hk`。\n:::\n\n| 地区     | 语言    | 参数  |\n| -------- | ------- | ----- |\n| 中国大陆 | 中文    | zh    |\n| 中国大陆 | English | en    |\n| 香港     | 中文    | zh-hk |\n| 香港     | English | en-hk |",
    "name": "房地产趋势与洞察",
    "parameters": {
      "category": "分类，默认为 `trends-and-insights`",
      "language": "语言，`zh` 为中国大陆中文，`en` 为中国大陆英文，`zh-hk` 为香港中文，`en-hk` 为香港英文，默认为 `zh`"
    }
  }
}
```
