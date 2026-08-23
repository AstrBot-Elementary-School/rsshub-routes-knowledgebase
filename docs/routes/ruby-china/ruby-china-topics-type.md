# Ruby China - 主题

## Coverage
`index-only`

## Route
- Namespace: `ruby-china`
- Namespace Name: `Ruby China`
- Route Path: `/ruby-china/topics/:type?`
- Route Name: `主题`
- Example: `/ruby-china/topics`
- URL: `ruby-china.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `ahonn`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
未登录状态下抓取页面非实时更新

| 主题类型 | type        |
| -------- | ----------- |
| 精华贴   | excellent   |
| 优质帖子 | popular     |
| 无人问津 | no\_reply   |
| 最新回复 | last\_reply |
| 最新发布 | last        |

## Parameters
- `type`: 主题类型，在 URL 可以找到


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "未登录状态下抓取页面非实时更新\n\n| 主题类型 | type        |\n| -------- | ----------- |\n| 精华贴   | excellent   |\n| 优质帖子 | popular     |\n| 无人问津 | no\\_reply   |\n| 最新回复 | last\\_reply |\n| 最新发布 | last        |",
  "example": "/ruby-china/topics",
  "heat": 0,
  "location": "topics.ts",
  "maintainers": [
    "ahonn"
  ],
  "name": "主题",
  "parameters": {
    "type": "主题类型，在 URL 可以找到"
  },
  "path": "/topics/:type?",
  "topFeeds": []
}
```
