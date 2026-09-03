# 三联生活周刊 - 标签

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/lifeweek/tag/:id`
- Route Name: `标签`
- Example: `/lifeweek/tag/122`
- URL: `lifeweek.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `changren-wcr`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
提取文章全文，获得更好的阅读体验。支持所有标签，标签名称见 [全部标签](https://www.lifeweek.com.cn/classify?type=1)。例如 [社会调查标签](https://www.lifeweek.com.cn/articleList/122) URL 最后的数字为标签 ID

| 社会调查 | 社会 | 经济 | 理财 | 热点 |
| -------- | ---- | ---- | ---- | ---- |
| 122      | 21   | 73   | 74   | 123  |

## Parameters
- `id`: 标签 ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/articleList/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "提取文章全文，获得更好的阅读体验。支持所有标签，标签名称见 [全部标签](https://www.lifeweek.com.cn/classify?type=1)。例如 [社会调查标签](https://www.lifeweek.com.cn/articleList/122) URL 最后的数字为标签 ID\n\n| 社会调查 | 社会 | 经济 | 理财 | 热点 |\n| -------- | ---- | ---- | ---- | ---- |\n| 122      | 21   | 73   | 74   | 123  |",
  "example": "/lifeweek/tag/122",
  "heat": 13,
  "location": "tag.ts",
  "maintainers": [
    "changren-wcr"
  ],
  "name": "标签",
  "parameters": {
    "id": "标签 ID"
  },
  "path": "/tag/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/articleList/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "人物 - Powered by RSSHub",
      "errorAt": "2026-09-02T07:12:39.190Z",
      "errorMessage": "[GET] \"https://www.lifeweek.com.cn/api/userWebFollow/getFollowTagContentList?type=4&sort=2&tagId=6\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 211.162.170.11:443, 211.162.170.16:443, 211.162.170.13:443, 211.162.170.14:443, 211.162.170.18:443, 211.162.170.17:443, 211.162.170.15:443, 211.162.170.12:443, timeout: 10000ms))\n",
      "id": "104794039452750848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/6",
      "title": "人物",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/6"
    },
    {
      "description": "生活方式 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152614722583832576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/7",
      "title": "生活方式",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/7"
    }
  ]
}
```
