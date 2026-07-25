# Instagram - User Profile - Picnob.info

## Coverage
`index-only`

## Route
- Namespace: `picnob.info`
- Namespace Name: `Instagram`
- Route Path: `/picnob.info/user/:id/:type?`
- Route Name: `User Profile - Picnob.info`
- Example: `/picnob.info/user/xlisa_olivex`
- URL: `picnob.info`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: {"default": "posts", "description": "Type of profile page", "options": [{"label": "Posts", "value": "posts"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/picnob.info/user/xlisa_olivex",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14406,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Profile - Picnob.info",
  "parameters": {
    "id": "Instagram id",
    "type": {
      "default": "posts",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Posts",
          "value": "posts"
        }
      ]
    }
  },
  "path": "/user/:id/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "谢谢你的关注 - Powered by RSSHub",
      "errorAt": "2024-12-12T00:24:16.873Z",
      "errorMessage": "503 Service Unavailable\n",
      "id": "60491404833914880",
      "image": "https://sp1.piokok.com/a/a_44102649694_28441710182871616169_e322c99cf726f66957cffc3fbc34e99c.jpg?v/t51.2885-19/123266262_3067125136865188_9063518416041685664_n.jpg?stp=dst-jpg_e0_s150x150_tt6&_nc_ht=scontent-mad2-1.cdninstagram.com&_nc_cat=104&_nc_ohc=ls01UnhNlAsQ7kNvgHGhRik&_nc_gid=ac3e89eb9bcf441d8fa35e01494a1dcc&edm=AOQ1c0wBAAAA&ccb=7-5&oh=00_AYC-P4Uvy4czlrklmfyZy5avLFEvV_EIc64uwpwcRTlGrQ&oe=674C0FB5&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.piokok.com/profile/azhu_a1997/",
      "title": "阿朱啊 (@azhu_a1997) - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/azhu_a1997"
    },
    {
      "description": "🇺🇸美高🇺🇸美本Math🇭🇰港硕AI🇨🇳🐧 🌍旅游攻略分享👉🏻Red Note&抖音ID: Riyaaa171 没有小号❗️不用X和任何交友软件❗️ 没有🚪没有群❗️有发这些的全是骗子❗️看到盗图假号请举报❗️勿信网上虚假信息以免上当受骗❗️ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61019054805448704",
      "image": "https://media.picnob.info/get?url=https://scontent-bru2-1.cdninstagram.com/v/t51.82787-19/568464527_18539365957027402_1084857286998025840_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby44NjQuYzIifQ&_nc_ht=scontent-bru2-1.cdninstagram.com&_nc_cat=110&_nc_oc=Q6cZ2gG4Kj6lALwIiOBE47mJqLETVns-8K6aCp6x4naFSkrjjSH0lKfCLm1u3OJukcWHMr6IktqO11psE8V1g02ZCst3&_nc_ohc=zNtLFZcfjt0Q7kNvwHjAyZN&_nc_gid=BVjB7Ob6jR9SkaKaYZT84w&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GI8U4iFKxjqCdN1BAHDmgmf0Lw4PbmNDAQAB3203200j-ccb7-5&oh=00_Af5MZWxDr5PaVB-VKtfcWoNngzlJbShWaYJUnP9TrttR8w&oe=6A18F15B&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/riya_yu/",
      "title": "Riyaaa🎀 (@riya_yu) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/riya_yu"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
