# TikTok - Live

## Coverage
`index-only`

## Route
- Namespace: `tiktok`
- Namespace Name: `TikTok`
- Route Path: `/tiktok/live/:user`
- Route Name: `Live`
- Example: `/tiktok/live/@shinichifuku`
- URL: `tiktok.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User ID, including @


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.tiktok.com/:user/live`
- `target`: `/live/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/tiktok/live/@shinichifuku",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "live.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Live",
  "parameters": {
    "user": "User ID, including @"
  },
  "path": "/live/:user",
  "radar": [
    {
      "source": [
        "www.tiktok.com/:user/live"
      ],
      "target": "/live/:user"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Se vuoi ridere sei nel posto giusto😎 If u wanna laugh u r in the right place😎 - Powered by RSSHub",
      "errorAt": "2026-08-17T07:27:58.131Z",
      "errorMessage": "Unexpected end of JSON input\n",
      "id": "242665903234866176",
      "image": "https://p19-common-sign.tiktokcdn.com/tos-maliva-avt-0068/08987e23b94057953fd4f1738694bf5f~tplv-tiktokx-cropcenter:1080:1080.webp?dr=14579&refresh_token=4134b430&x-expires=1787090400&x-signature=k%2F%2BgIyQs%2Brcb7lWSCJsE9WfVD2A%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=fdd36af4&idc=my",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@khaby.lame/live",
      "title": "Khabane lame (@khaby.lame)'s Live Stream - TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/live/%40khaby.lame"
    }
  ]
}
```
