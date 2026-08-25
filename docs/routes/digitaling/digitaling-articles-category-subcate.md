# 数英网 - 数英网文章专题

## Coverage
`index-only`

## Route
- Namespace: `digitaling`
- Namespace Name: `数英网`
- Route Path: `/digitaling/articles/:category/:subcate?`
- Route Name: `数英网文章专题`
- Example: `/digitaling/articles/latest`
- URL: `www.digitaling.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `occupy5`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 最新文章 | 头条     | 热文 | 精选   |
| -------- | -------- | ---- | ------ |
| latest   | headline | hot  | choice |

分类`hot`下的子类

| 近期热门文章 | 近期最多收藏 | 近期最多赞 |
| ------------ | ------------ | ---------- |
| views        | collects     | zan        |

## Parameters
- `category`: 文章专题分类
- `subcate`: hot 分类下的子类


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新文章 | 头条     | 热文 | 精选   |\n| -------- | -------- | ---- | ------ |\n| latest   | headline | hot  | choice |\n\n分类`hot`下的子类\n\n| 近期热门文章 | 近期最多收藏 | 近期最多赞 |\n| ------------ | ------------ | ---------- |\n| views        | collects     | zan        |",
  "example": "/digitaling/articles/latest",
  "heat": 0,
  "location": "article.ts",
  "maintainers": [
    "occupy5"
  ],
  "name": "数英网文章专题",
  "parameters": {
    "category": "文章专题分类",
    "subcate": "hot 分类下的子类"
  },
  "path": "/articles/:category/:subcate?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
