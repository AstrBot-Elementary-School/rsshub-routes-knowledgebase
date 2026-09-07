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
  "heat": 13036,
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
      "description": "45th & 47th President of the United States - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67508720925455360",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/343276689_801823474149940_2996871766977206771_n.jpg?stp=dst-jpg_s320x320_tt6&cb=8438d1d6-eb76aa66&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4zOTUuYzIifQ&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_oc=Q6cZ2gHwE0zQ9UC0xqvTYxWLAbZVO39DDSjbUGjAvzrrR1471uIT7iETR4-rGBGXovXna3k&_nc_ohc=yHde1BHyyWsQ7kNvwE2TCMK&_nc_gid=M_Jbd2uBuqRp-WTaW3RYLA&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GJH8dRQ0alkTQdkCAPPZEnT_BpcpbkULAAAB3203200j-ccb7-5-cb8438d1d6-eb76aa66&oh=00_Af2NLrkMAUPZ6EahiByCJPS9Xsg23Bjsd_QeGl5VgR_Q4Q&oe=69F11BD1&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/realdonaldtrump/",
      "title": "President Donald J. Trump (@realdonaldtrump) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/realdonaldtrump"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
