# cnBeta.COM - 分类

## Coverage
`index-only`

## Route
- Namespace: `cnbeta`
- Namespace Name: `cnBeta.COM`
- Route Path: `/cnbeta/category/:id`
- Route Name: `分类`
- Example: `/cnbeta/category/movie`
- URL: `cnbeta.com.tw`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 影视  | 音乐  | 游戏 | 动漫  | 趣闻  | 科学    | 软件 |
| ----- | ----- | ---- | ----- | ----- | ------- | ---- |
| movie | music | game | comic | funny | science | soft |

## Parameters
- `id`: 分类 id，可在对应分类页的 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cnbeta.com.tw/category/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 影视  | 音乐  | 游戏 | 动漫  | 趣闻  | 科学    | 软件 |\n| ----- | ----- | ---- | ----- | ----- | ------- | ---- |\n| movie | music | game | comic | funny | science | soft |",
  "example": "/cnbeta/category/movie",
  "heat": 66,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 id，可在对应分类页的 URL 中找到"
  },
  "path": "/category/:id",
  "radar": [
    {
      "source": [
        "cnbeta.com.tw/category/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "cnBeta.COM - 中文业界资讯站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61806357094007808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cnbeta.com.tw/",
      "title": "cnBeta.COM - 中文业界资讯站",
      "type": "feed",
      "url": "rsshub://cnbeta/category/movie"
    },
    {
      "description": "cnBeta.COM - 中文业界资讯站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80486406868729856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cnbeta.com.tw/",
      "title": "cnBeta.COM - 中文业界资讯站",
      "type": "feed",
      "url": "rsshub://cnbeta/category/soft"
    }
  ],
  "url": "cnbeta.com.tw"
}
```
