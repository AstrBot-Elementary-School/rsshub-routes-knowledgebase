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
  "heat": 13689,
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
      "description": "Photographing every county in England from my self built campervan Currently back home - Powered by RSSHub",
      "errorAt": "2026-05-18T21:18:29.026Z",
      "errorMessage": "Failed to fetch\n",
      "id": "70806173033907200",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/350875613_3468477706771628_8148305046493801488_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=108&_nc_oc=Q6cZ2gFRo31fRwjWSTT-hjwhm8U7p7QMdSCaWt5zqRMQ0fG6pe7OPBe5wLHnXE2uVO62qm8&_nc_ohc=4oYq7f_etZUQ7kNvwFrJt-r&_nc_gid=dGBcGMhaIxfi3ziNCxseWA&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GN3v6RSsnJ-lj1IMABAsyalEmBRxbkULAAAB3203200j-ccb7-5&oh=00_Af1W-AmD0PtTT_PVnwFZqTBknzR52LvZlh6bjccHa-V54w&oe=69F138A6&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/nigel.danson/",
      "title": "Nigel Danson (@nigel.danson) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/nigel.danson"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
