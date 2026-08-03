# LogoNews 标志情报局 - 文章分类

## Coverage
`index-only`

## Route
- Namespace: `logonews`
- Namespace Name: `LogoNews 标志情报局`
- Route Path: `/logonews/category/:category/:type`
- Route Name: `文章分类`
- Example: `/logonews/category/news/newsletter`
- URL: `logonews.cn/`
- Language: `_None_`
- Categories: `design`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
如 [简讯 - 标志情报局](https://www.logonews.cn/category/news/newsletter) 的 URL 为 `https://www.logonews.cn/category/news/newsletter`，可得路由为 [`/logonews/category/news/newsletter`](https://rsshub.app/logonews/category/news/newsletter)。

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到
- `type`: 类型，可在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `logonews.cn/category/:category/:type?`
- `target`: `/category/:category/:type?`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "如 [简讯 - 标志情报局](https://www.logonews.cn/category/news/newsletter) 的 URL 为 `https://www.logonews.cn/category/news/newsletter`，可得路由为 [`/logonews/category/news/newsletter`](https://rsshub.app/logonews/category/news/newsletter)。",
  "example": "/logonews/category/news/newsletter",
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章分类",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到",
    "type": "类型，可在对应分类页 URL 中找到"
  },
  "path": "/category/:category/:type",
  "radar": [
    {
      "source": [
        "logonews.cn/category/:category/:type?"
      ],
      "target": "/category/:category/:type?"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "logonews.cn/"
}
```
