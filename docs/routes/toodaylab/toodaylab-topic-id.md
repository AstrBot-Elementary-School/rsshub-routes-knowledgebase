# 理想生活实验室 - 话题

## Coverage
`index-only`

## Route
- Namespace: `toodaylab`
- Namespace Name: `理想生活实验室`
- Route Path: `/toodaylab/topic/:id`
- Route Name: `话题`
- Example: `/toodaylab/topic/309`
- URL: `toodaylab.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 今日消费资讯 | 实验室带你过周末 | 实验室带你过假期 | 每日一图 | 每周一书 | 实验室数字 | 新鲜社会人 | 实验室 TV |
| ------------ | ---------------- | ---------------- | -------- | -------- | ---------- | ---------- | --------- |
| 309          | 37               | 40               | 32       | 33       | 310        | 316        | 476       |

## Parameters
- `id`: 话题 id，见下表，可在对应话题页 URL 中找到


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `toodaylab.com/topic/:id`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 今日消费资讯 | 实验室带你过周末 | 实验室带你过假期 | 每日一图 | 每周一书 | 实验室数字 | 新鲜社会人 | 实验室 TV |\n| ------------ | ---------------- | ---------------- | -------- | -------- | ---------- | ---------- | --------- |\n| 309          | 37               | 40               | 32       | 33       | 310        | 316        | 476       |",
  "example": "/toodaylab/topic/309",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "话题",
  "parameters": {
    "id": "话题 id，见下表，可在对应话题页 URL 中找到"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "toodaylab.com/topic/:id"
      ],
      "target": "/topic/:id"
    }
  ],
  "topFeeds": []
}
```
