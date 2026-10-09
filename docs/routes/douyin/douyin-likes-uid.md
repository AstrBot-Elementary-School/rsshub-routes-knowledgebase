# 抖音直播 - 喜欢的视频

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/douyin/likes/:uid`
- Route Name: `喜欢的视频`
- Example: `/douyin/likes/self`
- URL: `douyin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `likes.ts`
- Source Module: `_None_`

## Description
只读取喜欢列表的首屏。设为私密的列表仅对应账号能够访问。发布时间为视频原始发布时间，点赞时间没有公开提供。

## Parameters
- `uid`: 用户页面 URL 中的 sec_user_id，或者 self 表示 DOUYIN_COOKIE 对应的登录账号。


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true
- `requireConfig`: [{"description": "订阅自己的喜欢列表时必须配置；其他用户的列表须对当前账号公开。", "name": "DOUYIN_COOKIE", "optional": true}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "只读取喜欢列表的首屏。设为私密的列表仅对应账号能够访问。发布时间为视频原始发布时间，点赞时间没有公开提供。",
  "example": "/douyin/likes/self",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "订阅自己的喜欢列表时必须配置；其他用户的列表须对当前账号公开。",
        "name": "DOUYIN_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "likes.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "喜欢的视频",
  "parameters": {
    "uid": "用户页面 URL 中的 sec_user_id，或者 self 表示 DOUYIN_COOKIE 对应的登录账号。"
  },
  "path": "/likes/:uid",
  "topFeeds": []
}
```
