# 新京报 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bjnews`
- Namespace Name: `新京报`
- Route Path: `/bjnews/cat/:cat`
- Route Name: `分类`
- Example: `/bjnews/cat/depth`
- URL: `www.bjnews.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `cat.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cat`: 分类, 可从URL中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bjnews.com.cn/:cat`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bjnews/cat/depth",
  "features": {},
  "heat": 110,
  "location": "cat.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "分类",
  "parameters": {
    "cat": "分类, 可从URL中找到"
  },
  "path": "/cat/:cat",
  "radar": [
    {
      "source": [
        "www.bjnews.com.cn/:cat"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新京报 - 分类 - 深读 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60398727382272000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bjnews.com.cn/depth",
      "title": "新京报 - 分类 - 深读",
      "type": "feed",
      "url": "rsshub://bjnews/cat/depth"
    },
    {
      "description": "新京报 - 分类 - 文化 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84161318721934339",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bjnews.com.cn/culture",
      "title": "新京报 - 分类 - 文化",
      "type": "feed",
      "url": "rsshub://bjnews/cat/culture"
    }
  ],
  "url": "www.bjnews.com.cn"
}
```
