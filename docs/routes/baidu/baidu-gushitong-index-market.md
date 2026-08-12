# 百度 - 首页指数

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/gushitong/index/:market?`
- Route Name: `首页指数`
- Example: `/baidu/gushitong/index`
- URL: `finance.baidu.com/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `CaoMeiYouRen, hutianyu2006`
- Source Location: `gushitong/index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `market`: {"description": "市场分类，默认为亚洲市场，即上证指数、深圳成指、恒生指数、富时中国A50、日经225指数和韩国综合指数", "options": [{"label": "亚洲", "value": "asia"}, {"label": "美洲", "value": "america"}, {"label": "欧非", "value": "europeafrica"}, {"label": "外汇", "value": "foreign"}, {"label": "债券", "value": "bond"}, {"label": "其他", "value": "other"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `finance.baidu.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/baidu/gushitong/index",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 650,
  "location": "gushitong/index.tsx",
  "maintainers": [
    "CaoMeiYouRen",
    "hutianyu2006"
  ],
  "name": "首页指数",
  "parameters": {
    "market": {
      "description": "市场分类，默认为亚洲市场，即上证指数、深圳成指、恒生指数、富时中国A50、日经225指数和韩国综合指数",
      "options": [
        {
          "label": "亚洲",
          "value": "asia"
        },
        {
          "label": "美洲",
          "value": "america"
        },
        {
          "label": "欧非",
          "value": "europeafrica"
        },
        {
          "label": "外汇",
          "value": "foreign"
        },
        {
          "label": "债券",
          "value": "bond"
        },
        {
          "label": "其他",
          "value": "other"
        }
      ]
    }
  },
  "path": "/gushitong/index/:market?",
  "radar": [
    {
      "source": [
        "finance.baidu.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "FinScope，汇聚全球金融市场的股票、基金、外汇、期货等实时行情，7*24小时覆盖专业财经资讯，提供客观、准确、及时、全面的沪深港美上市公司股价、财务、股东、分红等信息，让用户在复杂的金融市场，更简单的获取投资信息。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64898003762100224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finance.baidu.com/",
      "title": "FinScope",
      "type": "feed",
      "url": "rsshub://baidu/gushitong/index"
    }
  ],
  "url": "finance.baidu.com/",
  "view": 5
}
```
