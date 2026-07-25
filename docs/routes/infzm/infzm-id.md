# 南方周末 - 频道

## Coverage
`index-only`

## Route
- Namespace: `infzm`
- Namespace Name: `南方周末`
- Route Path: `/infzm/:id`
- Route Name: `频道`
- Example: `/infzm/1`
- URL: `www.infzm.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `KarasuShin, ranpox, xyqfer`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
下面给出部分参考：

| 推荐 | 新闻 | 观点 | 文化 | 人物 | 影像 | 专题 | 生活 | 视频 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1    | 2    | 3    | 4    | 7    | 8    | 6    | 5    | 131  |

## Parameters
- `id`: 南方周末频道 id, 可在该频道的 URL 中找到（即 https://www.infzm.com/contents?term_id=:id)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `infzm.com/contents`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "下面给出部分参考：\n\n| 推荐 | 新闻 | 观点 | 文化 | 人物 | 影像 | 专题 | 生活 | 视频 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 1    | 2    | 3    | 4    | 7    | 8    | 6    | 5    | 131  |",
  "example": "/infzm/1",
  "heat": 2891,
  "location": "index.ts",
  "maintainers": [
    "KarasuShin",
    "ranpox",
    "xyqfer"
  ],
  "name": "频道",
  "parameters": {
    "id": "南方周末频道 id, 可在该频道的 URL 中找到（即 https://www.infzm.com/contents?term_id=:id)"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "infzm.com/contents"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "南方周末-新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52508301310328842",
      "image": "https://www.infzm.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.infzm.com/contents?term_id=2",
      "title": "南方周末-新闻",
      "type": "feed",
      "url": "rsshub://infzm/2"
    },
    {
      "description": "南方周末-南方人物周刊 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53873114655474703",
      "image": "https://www.infzm.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.infzm.com/contents?term_id=156",
      "title": "南方周末-南方人物周刊",
      "type": "feed",
      "url": "rsshub://infzm/156"
    }
  ]
}
```
