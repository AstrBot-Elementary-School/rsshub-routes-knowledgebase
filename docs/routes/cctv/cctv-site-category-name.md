# 央视新闻 - 新闻联播

## Coverage
`index-only`

## Route
- Namespace: `cctv`
- Namespace Name: `央视新闻`
- Route Path: `/cctv/:site/:category/:name`
- Route Name: `新闻联播`
- Example: `/cctv/tv/lm/xwlb`
- URL: `tv.cctv.com/lm/xwlb`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `zengxs`
- Source Location: `xwlb.ts`
- Source Module: `_None_`

## Description
新闻联播内容摘要。

## Parameters
- `site`: 站点, 可选值如'tv', 既'央视节目'
- `category`: 分类名, 官网对应分类, 当前可选值'lm', 既'栏目大全'
- `name`: {"description": "栏目名称, 可在对应栏目页面 URL 中找到, 可选值如'xwlb',既'新闻联播'", "options": [{"label": "新闻联播", "value": "xwlb"}]}


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
  - `tv.cctv.com/lm/xwlb`
  - `tv.cctv.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "新闻联播内容摘要。",
  "example": "/cctv/tv/lm/xwlb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4505,
  "location": "xwlb.ts",
  "maintainers": [
    "zengxs"
  ],
  "name": "新闻联播",
  "parameters": {
    "category": "分类名, 官网对应分类, 当前可选值'lm', 既'栏目大全'",
    "name": {
      "description": "栏目名称, 可在对应栏目页面 URL 中找到, 可选值如'xwlb',既'新闻联播'",
      "options": [
        {
          "label": "新闻联播",
          "value": "xwlb"
        }
      ]
    },
    "site": "站点, 可选值如'tv', 既'央视节目'"
  },
  "path": "/:site/:category/:name",
  "radar": [
    {
      "source": [
        "tv.cctv.com/lm/xwlb",
        "tv.cctv.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "CCTV 新闻联播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59109731259240448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://tv.cctv.com/lm/xwlb/",
      "title": "CCTV 新闻联播",
      "type": "feed",
      "url": "rsshub://cctv/tv/lm/xwlb"
    },
    {
      "description": "undefined - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152525246751160320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://cctv/tv/Im/xwlb"
    }
  ],
  "url": "tv.cctv.com/lm/xwlb"
}
```
