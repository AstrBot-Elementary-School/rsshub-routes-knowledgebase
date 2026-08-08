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
  "test": {
    "code": 0
  },
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
      "description": "网易云音乐用户动态 - I love you three thousand times - Powered by RSSHub",
      "errorAt": "2025-11-04T02:37:40.370Z",
      "errorMessage": "Failed to fetch\n",
      "id": "186422945668491340",
      "image": "http://p1.music.126.net/QM5zjqPI2NGLGF2O-LcFvw==/109951164221621943.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/user/event?id=253142666",
      "title": "我在那一角落患过伤风啊的云村动态",
      "type": "feed",
      "url": "rsshub://163/music/user/events/253142666"
    }
  ]
}
```
