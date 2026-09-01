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
  "heat": 13677,
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
