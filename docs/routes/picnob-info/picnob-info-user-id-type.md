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
  "heat": 13032,
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
      "description": "Musician, Singer and Dad - Powered by RSSHub",
      "errorAt": "2026-05-02T22:37:03.561Z",
      "errorMessage": "Failed to fetch\n",
      "id": "83864858777430016",
      "image": "https://media.picnob.info/get?url=https://scontent-bru2-1.cdninstagram.com/v/t51.2885-19/450602929_809768534593876_7226006656844569067_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-bru2-1.cdninstagram.com&_nc_cat=104&_nc_oc=Q6cZ2gH6W0nAwiLEyTrfH_Su9nTyyif3NJ19SYgvnqbpYU9wwTEeQJyu0VMF0SRoLLp3aec&_nc_ohc=7viiabskgHUQ7kNvwFRzRUy&_nc_gid=3sZYt-GEfBK-8fNXkpOsHw&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GLGn2xpU0drteuACAOsZ1PXE7kdkbkULAAAB3203200j-ccb7-5&oh=00_Af2rGcWUNmj3cRrJ2TPs_KDB61BzBUghBoZr10E58I8imQ&oe=69F12633&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/davidztao/",
      "title": "David Tao 陶喆 (@davidztao) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/davidztao"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
