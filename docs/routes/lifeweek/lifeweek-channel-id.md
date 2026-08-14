# 三联生活周刊 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/lifeweek/channel/:id`
- Route Name: `栏目`
- Example: `/lifeweek/channel/9`
- URL: `lifeweek.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `changren-wcr`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
提取文章全文，获得更好的阅读体验。支持所有频道，频道名称见 [杂志栏目](https://www.lifeweek.com.cn/classify?type=2)。例如 [调查栏目](https://www.lifeweek.com.cn/column/9) URL 最后的数字为栏目 ID

| 调查 | 热点 | 人物 | 社会 | 经济 | 文化 |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 9    | 6    | 10   | 2    | 3    | 4    |

## Parameters
- `id`: 栏目 ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/column/:channel`
- `target`: `/channel/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "提取文章全文，获得更好的阅读体验。支持所有频道，频道名称见 [杂志栏目](https://www.lifeweek.com.cn/classify?type=2)。例如 [调查栏目](https://www.lifeweek.com.cn/column/9) URL 最后的数字为栏目 ID\n\n| 调查 | 热点 | 人物 | 社会 | 经济 | 文化 |\n| ---- | ---- | ---- | ---- | ---- | ---- |\n| 9    | 6    | 10   | 2    | 3    | 4    |",
  "example": "/lifeweek/channel/9",
  "heat": 139,
  "location": "channel.ts",
  "maintainers": [
    "changren-wcr"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 ID"
  },
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/column/:channel"
      ],
      "target": "/channel/:channel"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "文化 - Powered by RSSHub",
      "errorAt": "2026-08-13T04:17:22.172Z",
      "errorMessage": "[GET] \"https://www.lifeweek.com.cn/api/userWebFollow/getFollowTagContentList?type=3&sort=2&tagId=4\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 182.51.127.57:443, 182.51.127.54:443, 182.51.127.63:443, 182.51.127.61:443, 182.51.127.60:443, 182.51.127.55:443, 182.51.127.62:443, 182.51.127.56:443, timeout: 10000ms))\n",
      "id": "74705665643397120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/column/4",
      "title": "文化",
      "type": "feed",
      "url": "rsshub://lifeweek/channel/4"
    },
    {
      "description": "经济 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77268471866082304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/column/3",
      "title": "经济",
      "type": "feed",
      "url": "rsshub://lifeweek/channel/3"
    }
  ]
}
```
