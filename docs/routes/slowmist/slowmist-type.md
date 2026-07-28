# 慢雾科技 - 动态

## Coverage
`index-only`

## Route
- Namespace: `slowmist`
- Namespace Name: `慢雾科技`
- Route Path: `/slowmist/:type?`
- Route Name: `动态`
- Example: `/slowmist/research`
- URL: `slowmist.com/zh/news.html`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `AtlasQuan`
- Source Location: `slowmist.ts`
- Source Module: `_None_`

## Description
| 公司新闻 | 漏洞披露 | 技术研究 |
| -------- | -------- | -------- |
| news     | vul      | research |

## Parameters
- `type`: 分类，见下表，默认为公司新闻


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
  - `slowmist.com/zh/news.html`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 公司新闻 | 漏洞披露 | 技术研究 |\n| -------- | -------- | -------- |\n| news     | vul      | research |",
  "example": "/slowmist/research",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 396,
  "location": "slowmist.ts",
  "maintainers": [
    "AtlasQuan"
  ],
  "name": "动态",
  "parameters": {
    "type": "分类，见下表，默认为公司新闻"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "slowmist.com/zh/news.html"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "慢雾科技 - 技术研究 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805272531998",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.slowmist.com/api/get_list?type=research",
      "title": "慢雾科技 - 技术研究",
      "type": "feed",
      "url": "rsshub://slowmist/research"
    }
  ],
  "url": "slowmist.com/zh/news.html"
}
```
