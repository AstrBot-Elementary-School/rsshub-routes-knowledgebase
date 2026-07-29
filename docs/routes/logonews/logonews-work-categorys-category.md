# LogoNews 标志情报局 - 作品分类

## Coverage
`index-only`

## Route
- Namespace: `logonews`
- Namespace Name: `LogoNews 标志情报局`
- Route Path: `/logonews/work/categorys/:category`
- Route Name: `作品分类`
- Example: `/logonews/work/categorys/hotel-catering`
- URL: `logonews.cn/`
- Language: `_None_`
- Categories: `design`
- Maintainers: `nczitzk`
- Source Location: `work-category.ts`
- Source Module: `_None_`

## Description
如 [LOGO 作品分类：酒店餐饮 - 标志情报局](https://www.logonews.cn/work/categorys/hotel-catering) 的 URL 为 `https://www.logonews.cn/work/categorys/hotel-catering`，可得路由为 [`/logonews/work/categorys/hotel-catering`](https://rsshub.app/logonews/work/categorys/hotel-catering)。

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `logonews.cn/work/categorys/:category`
- `target`: `/work/categorys/:category`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "如 [LOGO 作品分类：酒店餐饮 - 标志情报局](https://www.logonews.cn/work/categorys/hotel-catering) 的 URL 为 `https://www.logonews.cn/work/categorys/hotel-catering`，可得路由为 [`/logonews/work/categorys/hotel-catering`](https://rsshub.app/logonews/work/categorys/hotel-catering)。",
  "example": "/logonews/work/categorys/hotel-catering",
  "heat": 0,
  "location": "work-category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "作品分类",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到"
  },
  "path": "/work/categorys/:category",
  "radar": [
    {
      "source": [
        "logonews.cn/work/categorys/:category"
      ],
      "target": "/work/categorys/:category"
    }
  ],
  "topFeeds": [],
  "url": "logonews.cn/"
}
```
