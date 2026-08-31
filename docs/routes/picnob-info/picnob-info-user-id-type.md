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
  "heat": 13687,
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
      "description": "maddonna専属 ♡AV女優 ♡Twitterに作品情報載せています ♡リンクはファンサイト - Powered by RSSHub",
      "errorAt": "2026-03-22T00:28:48.100Z",
      "errorMessage": "Failed to fetch\n",
      "id": "70741282448498688",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/504102322_18076454998925423_5094171439121223523_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby41MzQuYzIifQ&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=111&_nc_oc=Q6cZ2gF2HDG65MJIUCEc6Y969dWbc_m9V8k_LPdMeWDQA7L1ElKEIvu11FeX7Q--sBbPElI&_nc_ohc=2V9TODDfvbIQ7kNvwEOF45f&_nc_gid=LlreyGJmCHFB2qljfWjsLg&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GLL9Cx5vYAKncDhAAGPPwg3vIbJGbvEnAQAB3203200j-ccb7-5&oh=00_Afy7zMOp-lqZAG1DclpVJTNqdKZJw8QWR38edfBNi_2bvg&oe=69C41165&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/ririko_kinosita/",
      "title": "木下 凛々子 ririko kinoshita (@ririko_kinosita) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/ririko_kinosita"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
