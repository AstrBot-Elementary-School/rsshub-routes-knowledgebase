# 生命时报 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `lifetimes`
- Namespace Name: `生命时报`
- Route Path: `/lifetimes/:category?`
- Route Name: `栏目`
- Example: `/lifetimes`
- URL: `www.lifetimes.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 新闻 | 医药     | 养生            | 生活 | 母亲行动 | 长寿      | 视频  | 时评         | 调查    | 产业经济 |
| ---- | -------- | --------------- | ---- | -------- | --------- | ----- | ------------ | ------- | -------- |
| news | medicine | healthpromotion | life | mothers  | longevity | video | news-comment | hotspot | industry |

## Parameters
- `category`: 栏目，见下表，默认为新闻


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
  "description": "| 新闻 | 医药     | 养生            | 生活 | 母亲行动 | 长寿      | 视频  | 时评         | 调查    | 产业经济 |\n| ---- | -------- | --------------- | ---- | -------- | --------- | ----- | ------------ | ------- | -------- |\n| news | medicine | healthpromotion | life | mothers  | longevity | video | news-comment | hotspot | industry |",
  "example": "/lifetimes",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "category": "栏目，见下表，默认为新闻"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
