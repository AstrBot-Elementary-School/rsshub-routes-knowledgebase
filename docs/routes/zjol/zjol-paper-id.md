# 浙江在线 - 浙报集团系列报刊

## Coverage
`index-only`

## Route
- Namespace: `zjol`
- Namespace Name: `浙江在线`
- Route Path: `/zjol/paper/:id?`
- Route Name: `浙报集团系列报刊`
- Example: `/zjol/paper/zjrb`
- URL: `zjol.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `paper.ts`
- Source Module: `_None_`

## Description
| 浙江日报 | 钱江晚报 | 美术报 | 浙江老年报 | 浙江法制报 | 江南游报 |
| -------- | -------- | ------ | ---------- | ---------- | -------- |
| zjrb     | qjwb     | msb    | zjlnb      | zjfzb      | jnyb     |

## Parameters
- `id`: 报纸 id，见下表，默认为 `zjrb`，即浙江日报


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
  "description": "| 浙江日报 | 钱江晚报 | 美术报 | 浙江老年报 | 浙江法制报 | 江南游报 |\n| -------- | -------- | ------ | ---------- | ---------- | -------- |\n| zjrb     | qjwb     | msb    | zjlnb      | zjfzb      | jnyb     |",
  "example": "/zjol/paper/zjrb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "paper.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "浙报集团系列报刊",
  "parameters": {
    "id": "报纸 id，见下表，默认为 `zjrb`，即浙江日报"
  },
  "path": "/paper/:id?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "浙江日报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62793359084414976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zjrb.zjol.com.cn/",
      "title": "浙江日报",
      "type": "feed",
      "url": "rsshub://zjol/paper/zjrb"
    },
    {
      "description": "浙江日报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150224065197180928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zjrb.zjol.com.cn/",
      "title": "浙江日报",
      "type": "feed",
      "url": "rsshub://zjol/paper"
    }
  ]
}
```
