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
  "heat": 13029,
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
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "💌 협찬문의 👉DM 💋 @puremediakorea 💄 @x.level.kr ❣️ @artgravia_global 👇예하의 화보집 구매 링크👇 👉예하의 계정 대피소 : @yun_yeha 👈 🐥예하의 트위터 아이디 : @_yeha_y 🐥 - Powered by RSSHub",
      "errorAt": "2025-07-06T11:26:33.915Z",
      "errorMessage": "503 Service Unavailable\n",
      "id": "92979620002035712",
      "image": "https://sp1.pixnoy.com/a/a_51211216676_18553117281855_a5998e6b702849f9d18c467da9a109d1.jpg?o=aHR0cHM6Ly9pbnN0YWdyYW0uZmNwczItMS5mbmEuZmJjZG4ubmV0L3YvdDUxLjI4ODUtMTkvNDU3MTM4MDgzXzU1MTMzMjUxMDU1NTg1OV83MjM4OTg5OTIwMTAyODE1ODEyX24uanBnP3N0cD1kc3QtanBnX3MxNTB4MTUwX3R0NiZfbmNfaHQ9aW5zdGFncmFtLmZjcHMyLTEuZm5hLmZiY2RuLm5ldCZfbmNfY2F0PTExMSZfbmNfb2M9UTZjWjJRRTVDTm9SSkVuVW9FTzc3cEJWaGlUc2lfOTJPNFZUb1hTREZtZ2pwMmdDWDJWUzEzbWt4bW90c3pRVGVzRUZCMWVRYnpXOG1GOXVFYTJYcGllY1FRbHcmX25jX29oYz1RQ2kwRXRIMGJRZ1E3a052d0VWSkh4dyZfbmNfZ2lkPVZ0NS0wVXpMeGI2MENTd3VBVkluMmcmZWRtPUFMR2JKUE1CQUFBQSZjY2I9Ny01Jm9oPTAwX0FmUGljYW1QbmdCSExKRVpNRUZKZi04Q1MtU0dWWldWb2FoRlNYLWdYLVJkN2cmb2U9Njg2RDRGQ0ImX25jX3NpZD03ZDNhYzU=&h=796983201a948dbcc17414355729ec0d",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/_yeha_y/",
      "title": "윤예하 (@_yeha_y) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/_yeha_y"
    },
    {
      "description": "I’m a cosplayer from Japan! I also stream on Twitch, so come hang out with me there 💗 Feel free to call me Hanakon! 🌸 - Powered by RSSHub",
      "errorAt": "2026-05-02T21:07:06.117Z",
      "errorMessage": "Failed to fetch\n",
      "id": "70018609878004736",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/352214256_663676808924267_1478758354705943442_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby45ODMuYzIifQ&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=111&_nc_oc=Q6cZ2gH4qrclBOMQNnX-BaC__HZpem1uZ_Y3_oKcT9gh3FZ_CsWw3HBgpw20G_MHFeVjzqs&_nc_ohc=EnbLn7Yc2hgQ7kNvwHT_R7x&_nc_gid=2A60oEHT3y-f5WM2HLq1UA&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GPBc-hRrDHFMnFsCAJKL44jjmoUUbkULAAAB3203200j-ccb7-5&oh=00_Af1CtbiZpCU2-eCQ04lR5xrjXOJP-2U9ZRALO-KMSgdIUg&oe=69F0EF8B&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/875cos/",
      "title": "華子狐 (@875cos) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/875cos"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
