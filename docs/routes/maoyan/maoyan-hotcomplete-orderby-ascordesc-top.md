# 猫眼电影 - 正在热映 - 完整版

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/maoyan/hotComplete/:orderby?/:ascOrDesc?/:top?`
- Route Name: `正在热映 - 完整版`
- Example: `/maoyan/hotComplete`
- URL: `maoyan.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `chenbstack`
- Source Location: `hot-complete.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `orderby`: 排序条件，(score: 评分, pubDate: 发布时间)
- `ascOrDesc`: 正序或倒序 (asc: 正序, desc: 倒序) 默认倒序
- `top`: 取前多少条，默认取所有


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/hotComplete",
  "heat": 0,
  "location": "hot-complete.ts",
  "maintainers": [
    "chenbstack"
  ],
  "name": "正在热映 - 完整版",
  "parameters": {
    "ascOrDesc": "正序或倒序 (asc: 正序, desc: 倒序) 默认倒序",
    "orderby": "排序条件，(score: 评分, pubDate: 发布时间)",
    "top": "取前多少条，默认取所有"
  },
  "path": "/hotComplete/:orderby?/:ascOrDesc?/:top?",
  "topFeeds": []
}
```
