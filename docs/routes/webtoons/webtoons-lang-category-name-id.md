# Webtoons - Comic updates

## Coverage
`index-only`

## Route
- Namespace: `webtoons`
- Namespace Name: `Webtoons`
- Route Path: `/webtoons/:lang/:category/:name/:id`
- Route Name: `Comic updates`
- Example: `/webtoons/zh-hant/drama/gongzhuweimian/894`
- URL: `www.webtoons.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `machsix`
- Source Location: `comic.ts`
- Source Module: `_None_`

## Description
For example: `https://www.webtoons.com/zh-hant/drama/gongzhuweimian/list?title_no=894`, `lang=zh-hant`,`category=drama`,`name=gongzhucheyeweimian`,`id=894`.

## Parameters
- `lang`: Language
- `category`: Category
- `name`: Name
- `id`: ID


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "For example: `https://www.webtoons.com/zh-hant/drama/gongzhuweimian/list?title_no=894`, `lang=zh-hant`,`category=drama`,`name=gongzhucheyeweimian`,`id=894`.",
  "example": "/webtoons/zh-hant/drama/gongzhuweimian/894",
  "heat": 0,
  "location": "comic.ts",
  "maintainers": [
    "machsix"
  ],
  "name": "Comic updates",
  "parameters": {
    "category": "Category",
    "id": "ID",
    "lang": "Language",
    "name": "Name"
  },
  "path": "/:lang/:category/:name/:id",
  "topFeeds": []
}
```
