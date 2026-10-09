# 抖音直播 - 收藏的视频

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/douyin/collection`
- Route Name: `收藏的视频`
- Example: `/douyin/collection`
- URL: `douyin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `collection.ts`
- Source Module: `_None_`

## Description
订阅 DOUYIN\_COOKIE 对应账号收藏的视频首屏。收藏夹、音乐、合集和短剧不在此路由范围内。发布时间为视频原始发布时间，收藏时间没有公开提供。

## Parameters
_None_


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true
- `requireConfig`: [{"description": "对应允许用于订阅的本人账号。", "name": "DOUYIN_COOKIE"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "订阅 DOUYIN\\_COOKIE 对应账号收藏的视频首屏。收藏夹、音乐、合集和短剧不在此路由范围内。发布时间为视频原始发布时间，收藏时间没有公开提供。",
  "example": "/douyin/collection",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "对应允许用于订阅的本人账号。",
        "name": "DOUYIN_COOKIE"
      }
    ],
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "collection.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "收藏的视频",
  "path": "/collection",
  "topFeeds": []
}
```
