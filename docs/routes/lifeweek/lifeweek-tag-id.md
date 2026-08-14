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
  "heat": 12,
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
      "errorAt": null,
      "errorMessage": null,
      "id": "104794039452750848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/6",
      "title": "人物",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/6"
    },
    {
      "description": "文学 - Powered by RSSHub",
      "errorAt": "2026-08-13T06:30:12.157Z",
      "errorMessage": "[GET] \"https://www.lifeweek.com.cn/api/userWebFollow/getFollowTagContentList?type=4&sort=2&tagId=4\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 124.193.244.20:443, 124.193.244.26:443, 124.193.244.24:443, 124.193.244.25:443, 124.193.244.23:443, 124.193.244.21:443, 124.193.244.27:443, 124.193.244.22:443, timeout: 10000ms))\n",
      "id": "152614384793012224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/4",
      "title": "文学",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/4"
    }
  ]
}
```
