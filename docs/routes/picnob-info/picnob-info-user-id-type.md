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
  "heat": 12907,
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
      "description": "@hadabin_ lovebinofficial@gmail.com - Powered by RSSHub",
      "errorAt": "2026-03-11T13:12:40.758Z",
      "errorMessage": "Failed to fetch\n503 Service Unavailable\n",
      "id": "58527216453026816",
      "image": "https://sp1.pixnoy.com/a/a_1383501409_50286038151853_b413a89eff4e3ed404fa2e9045a227cc.jpg?o=aHR0cHM6Ly9zY29udGVudC1pYWQzLTEuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS44Mjc4Ny0xOS82NDIzMzg4MjJfMTg1NzI5MDkxNDAwMTM0MTBfMTQ2MTM4Mjc3MTQzMjU5OTU3X24uanBnP3N0cD1kc3QtanBnX3MxNTB4MTUwX3R0NiZlZmc9ZXlKMlpXNWpiMlJsWDNSaFp5STZJbkJ5YjJacGJHVmZjR2xqTG1ScVlXNW5ieTR4TURnd0xtTXlJbjAmX25jX2h0PXNjb250ZW50LWlhZDMtMS5jZG5pbnN0YWdyYW0uY29tJl9uY19jYXQ9MTEwJl9uY19vYz1RNmNaMlFHQkNXLW1CNHplWXhxWnJrS2tDLUFoSWVsNjd0U1hBOFUyMFVBeEhnOTFDcVBDZEwyZHJtOGNMSU9JRlVVTkUwNDRMWW9GcDJWaWVBVEJaUHNOSy1UeiZfbmNfb2hjPUlkU3d5by1jQmhBUTdrTnZ3RzdFUFg5Jl9uY19naWQ9WGxEcXNRSVhpVGRfNk44VFJ6MEZtZyZlZG09QUxHYkpQTUJBQUFBJmNjYj03LTUmb2g9MDBfQWZ5LWZBTkVYNWs1cGlXbGlZdklYWV9weEhLUzBjaTdFMk81VGJKcTEzMEY2ZyZvZT02OUI0RUZDQSZfbmNfc2lkPTdkM2FjNQ==&h=123acb6fd777efbd97001717d128b240",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/dabin_v/",
      "title": "다빈 (@dabin_v) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/dabin_v"
    },
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
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
