# 豆瓣 - 新书速递

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/book/latest/:type?`
- Route Name: `新书速递`
- Example: `/douban/book/latest/fiction`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `fengkx, lyqluis`
- Source Location: `book/latest.ts`
- Source Module: `_None_`

## Description
| 文学          | 小说    | 历史文化 | 社会纪实  | 科学新知 | 艺术设计 | 商业经管 | 绘本漫画 |
| ------------- | ------- | -------- | --------- | -------- | -------- | -------- | -------- |
| prose\_poetry | fiction | history  | biography | science  | art      | business | comics   |

## Parameters
- `type`: 专题分类，可选，默认为 `all`


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
    "social-media"
  ],
  "description": "| 文学          | 小说    | 历史文化 | 社会纪实  | 科学新知 | 艺术设计 | 商业经管 | 绘本漫画 |\n| ------------- | ------- | -------- | --------- | -------- | -------- | -------- | -------- |\n| prose\\_poetry | fiction | history  | biography | science  | art      | business | comics   |",
  "example": "/douban/book/latest/fiction",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 214,
  "location": "book/latest.ts",
  "maintainers": [
    "fengkx",
    "lyqluis"
  ],
  "name": "新书速递",
  "parameters": {
    "type": "专题分类，可选，默认为 `all`"
  },
  "path": "/book/latest/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣新书速递 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53331366895638542",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://book.douban.com/latest",
      "title": "豆瓣新书速递",
      "type": "feed",
      "url": "rsshub://douban/book/latest"
    },
    {
      "description": "豆瓣新书速递-小说 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72931562996240384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://book.douban.com/latest?subcat=%E5%B0%8F%E8%AF%B4",
      "title": "豆瓣新书速递-小说",
      "type": "feed",
      "url": "rsshub://douban/book/latest/fiction"
    }
  ]
}
```
