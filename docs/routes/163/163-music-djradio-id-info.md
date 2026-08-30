# 网易公开课 - 电台节目

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/djradio/:id/:info?`
- Route Name: `电台节目`
- Example: `/163/music/djradio/347317067`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `magic-akari`
- Source Location: `music/djradio.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 节目 id, 可在电台节目页 URL 中找到
- `info`: 默认在正文尾部显示节目相关信息，任意值为不显示


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `music.163.com/djradio`
- `target`: `/music/djradio/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/163/music/djradio/347317067",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2476,
  "location": "music/djradio.tsx",
  "maintainers": [
    "magic-akari"
  ],
  "name": "电台节目",
  "parameters": {
    "id": "节目 id, 可在电台节目页 URL 中找到",
    "info": "默认在正文尾部显示节目相关信息，任意值为不显示"
  },
  "path": "/music/djradio/:id/:info?",
  "radar": [
    {
      "source": [
        "music.163.com/djradio"
      ],
      "target": "/music/djradio/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "华尔街日报、纽约时报、经济学人、卫报、华盛顿邮报...每日精选外刊新闻，有趣、有料的双语新闻等你来听哦！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86942680091975680",
      "image": "https://p1.music.126.net/FEr0yi7hy9AA2Fnyksox-w==/109951168094109440.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/djradio?id=792645464",
      "title": "每日双语新闻 | 快乐学英语",
      "type": "feed",
      "url": "rsshub://163/music/djradio/792645464"
    },
    {
      "description": "无时差研究所\"Time Travel Institution\"，诞生于纽约中城的一间会议室，现在辗转落地到了北京，是一档连续更新超过四年的播客节目。 节目以访谈的形式进行，每期都会邀请不同的嘉宾，来分享自己的知识、经验或者见解。我们不追求与社会热点无时差，但求对人类生存空间的持续关注。希望陪伴你上下班，陪你等地铁、公交，刷手机，成为你日常碎片化时间的一部分。 两位主播珂珂和王妈妈虽然每天讲烂梗，不做正经事，但是每一次准备播客的过程，都带我们走到了某一个小小议题的门口，而每个嘉宾都是一把钥匙，ta 领着我们看到了全新的、更大的世界，ta 让我对世界多了一些了解，即便每次都有一点点，它都成为了我们生命里的一个小小刻度，也希望它也能帮助到你~ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86348092512122880",
      "image": "https://p1.music.126.net/pDwIwKwFhduBjkYEfRnFVg==/109951164453536558.jpg",
      "ownerUserId": null,
      "siteUrl": "https://music.163.com/djradio?id=794193438",
      "title": "无时差研究所",
      "type": "feed",
      "url": "rsshub://163/music/djradio/794193438"
    }
  ]
}
```
