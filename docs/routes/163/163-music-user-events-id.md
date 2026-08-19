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
  "heat": 9,
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
      "description": "网易云音乐用户动态 - 不想温柔，也不想坚定 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66801413814601728",
      "image": "http://p1.music.126.net/QEs-7T3hM-uQNKUrlY2l6A==/109951167949881205.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/user/event?id=395678483",
      "title": "夏天-summer-5的云村动态",
      "type": "feed",
      "url": "rsshub://163/music/user/events/395678483"
    },
    {
      "description": "网易云音乐用户动态 - 知名女星的粉丝 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "241796608046652416",
      "image": "http://p1.music.126.net/SiDxCskD6Hm4kRZKzDbQcQ==/109951170026575192.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/#/user/event?id=134073344",
      "title": "东狸山大猫的云村动态",
      "type": "feed",
      "url": "rsshub://163/music/user/events/134073344"
    }
  ]
}
```
