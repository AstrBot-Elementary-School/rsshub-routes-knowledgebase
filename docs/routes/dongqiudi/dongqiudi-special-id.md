# 懂球帝 - 专题

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/dongqiudi/special/:id`
- Route Name: `专题`
- Example: `/dongqiudi/special/41`
- URL: `m.dongqiudi.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `dxmpalb`
- Source Location: `special.ts`
- Source Module: `_None_`

## Description
| 新闻大爆炸 | 懂球帝十佳球 | 懂球帝本周 MVP |
| ---------- | ------------ | -------------- |
| 41         | 52           | 53             |

## Parameters
- `id`: 专题 id, 可自行通过 https://www.dongqiudi.com/special/+数字匹配


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/special/:id`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "description": "| 新闻大爆炸 | 懂球帝十佳球 | 懂球帝本周 MVP |\n| ---------- | ------------ | -------------- |\n| 41         | 52           | 53             |",
  "example": "/dongqiudi/special/41",
  "heat": 432,
  "location": "special.ts",
  "maintainers": [
    "dxmpalb"
  ],
  "name": "专题",
  "parameters": {
    "id": "专题 id, 可自行通过 https://www.dongqiudi.com/special/+数字匹配"
  },
  "path": "/special/:id",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/special/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "足坛今天都发生了哪些事？ - Powered by RSSHub",
      "errorAt": "2026-08-27T11:18:04.285Z",
      "errorMessage": "200 ",
      "id": "61424740780593152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/special/48",
      "title": "懂球帝专题-早报",
      "type": "feed",
      "url": "rsshub://dongqiudi/special/48"
    },
    {
      "description": "世界那么大，除了足球还有这些 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66400977219680266",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/special/41",
      "title": "懂球帝专题-新闻大爆炸",
      "type": "feed",
      "url": "rsshub://dongqiudi/special/41"
    }
  ]
}
```
