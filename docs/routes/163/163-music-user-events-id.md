# 网易公开课 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/user/events/:id`
- Route Name: `用户动态`
- Example: `/163/music/user/events/585804522`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Master-Hash`
- Source Location: `music/userevents.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 uid, 可在用户主页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `music.163.com/user/event`
- `target`: `/music/user/events/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/163/music/user/events/585804522",
  "heat": 8,
  "location": "music/userevents.tsx",
  "maintainers": [
    "Master-Hash"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "用户 uid, 可在用户主页 URL 中找到"
  },
  "path": "/music/user/events/:id",
  "radar": [
    {
      "source": [
        "music.163.com/user/event"
      ],
      "target": "/music/user/events/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "网易云音乐用户动态 - 而我不再觉得 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149116147665490944",
      "image": "http://p1.music.126.net/j3JLGbJ3k7cV_k6fo9-zmg==/109951169986583600.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/user/event?id=398309610",
      "title": "番茄鱼鱼酱日记的云村动态",
      "type": "feed",
      "url": "rsshub://163/music/user/events/398309610"
    },
    {
      "description": "网易云音乐用户动态 - 清水如泉 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114722269609891849",
      "image": "http://p1.music.126.net/5LdymLqUBetGf6sdLJgmaw==/109951164484071083.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/user/event?id=96331715",
      "title": "某蓝姓潜水艇的云村动态",
      "type": "feed",
      "url": "rsshub://163/music/user/events/96331715"
    }
  ]
}
```
