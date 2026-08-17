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
  "heat": 14036,
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
      "description": "Photo tours and workshops - Powered by RSSHub",
      "errorAt": "2026-05-19T03:52:33.460Z",
      "errorMessage": "Failed to fetch\n",
      "id": "67415391929939968",
      "image": "https://media.picnob.info/get?url=https://scontent-bru2-1.cdninstagram.com/v/t51.2885-19/182609735_781545072499113_5766071618906021073_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby43NDguYzIifQ&_nc_ht=scontent-bru2-1.cdninstagram.com&_nc_cat=109&_nc_oc=Q6cZ2gEHbY7JzbMmqFW36BcWBEQAvkkF9v0H_kjE37b9C0dGtcJxT2MIsu5ArWmhh1hWuR0&_nc_ohc=_N5ZF-ltce8Q7kNvwHcLgyh&_nc_gid=HX6_6uLoKOlEdn1_4FxAtw&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GEdn4gqpGWykz8YCANHcWmKWMwVQbkULAAAB3203200j-ccb7-5&oh=00_Af7-8X3F4nXP3vRfbiB4G9R9onY0FSy0Kn8pObCA8OH1vw&oe=69FC77BB&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/maxrivephotography/",
      "title": "Max Rive (@maxrivephotography) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/maxrivephotography"
    },
    {
      "description": "不用找了！我把所有女神都放在這裡了❤️ 眼睛保養運動正式開啟👀 - 📩投稿請本人自行私訊小盒子 - Powered by RSSHub",
      "errorAt": "2026-04-01T11:55:44.661Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "70654798395602944",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/295820502_747405093032681_2662974620920347195_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby43NTAuYzIifQ&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=105&_nc_oc=Q6cZ2gHE6fiLaNXz-wbHZYKz0taeaih9jzdtmWpWVsF0r0-fvHcNnSqoaU6B8XkRe1A5kAY&_nc_ohc=_WLiNADpQMYQ7kNvwGkUQD9&_nc_gid=9Ugin7EAfPZ6JEF9z2_rDQ&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GNbcoRHp0hLPwqcCADt61gVPyfQkbkULAAAB3203200j-ccb7-5&oh=00_AfyFrjHsatt77fxherjIKU0tINYtYeb9y_5SBpfcANrS3g&oe=69CCBC88&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/beautygirl.search/",
      "title": "女神調查局 (@beautygirl.search) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/beautygirl.search"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
