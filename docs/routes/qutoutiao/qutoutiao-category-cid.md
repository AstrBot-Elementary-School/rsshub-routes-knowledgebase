# 趣头条 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qutoutiao`
- Namespace Name: `趣头条`
- Route Path: `/qutoutiao/category/:cid`
- Route Name: `分类`
- Example: `/qutoutiao/category/1`
- URL: `home.qutoutiao.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `alphardex, LogicJake`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 推荐 | 热点 | 娱乐 | 健康 | 养生 | 励志 | 科技 | ... |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | --- |
| 255  | 1    | 6    | 42   | 5    | 4    | 7    | ... |

更多的 cid 可通过访问[官网](http://home.qutoutiao.net)切换分类，观察 url 获得。

## Parameters
- `cid`: 分类 id


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
  "description": "| 推荐 | 热点 | 娱乐 | 健康 | 养生 | 励志 | 科技 | ... |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | --- |\n| 255  | 1    | 6    | 42   | 5    | 4    | 7    | ... |\n\n更多的 cid 可通过访问[官网](http://home.qutoutiao.net)切换分类，观察 url 获得。",
  "example": "/qutoutiao/category/1",
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "alphardex",
    "LogicJake"
  ],
  "name": "分类",
  "parameters": {
    "cid": "分类 id"
  },
  "path": "/category/:cid",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
