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
  "heat": 14280,
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
      "description": "🍊 unofficial fanpage of @jujingyi_kikuuu 🐷 ‘’not impersonating anyone,, - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68610825570148352",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/271956448_4733843110002864_7313793041524414966_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby45NjIuYzIifQ&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=100&_nc_oc=Q6cZ2gGlHWI9ie6GSVnHKJO-YBIAFI-vGhaq4Ps3ZNYFZJ9QO0XG_PEK5KMiCbMucWaGqAM&_nc_ohc=JU6Ya-spgA4Q7kNvwHVOqLu&_nc_gid=s2dWr9eiBrhQoEZv8uOxVQ&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GOC5NRCwgP68Z9EQAPZZyWgF0H9lbkULAAAB3203200j-ccb7-5&oh=00_Af6ogzV1h82bf2PC-Zt3NWnEH6JctMI5fvP2zl7e8Wc_yg&oe=69FC6FF8&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/jujingyii_/",
      "title": "鞠婧祎 𝗝𝗨𝗝𝗜𝗡𝗚𝗬𝗜 || 𝗨𝗡𝗢𝗙𝗙𝗜𝗖𝗜𝗔𝗟 𝗙𝗔𝗡𝗣𝗔𝗚𝗘 (@jujingyii_) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/jujingyii_"
    },
    {
      "description": "Welcome to The Mood Room Street | Urban | Cinematic Scenes Freelance @moodroomframes 🎬 Please email for inquires! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64209485549102080",
      "image": "https://media.picnob.info/get?url=https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/457660786_1725355404960768_3285457465846608537_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=100&_nc_oc=Q6cZ2gHxZju3lk72w9osyADdCn25emSN8l_a0nS9eNB9iR5j6z_JfK7d3wIMDTcw3gb_3a0&_nc_ohc=85aJ9Orawp4Q7kNvwGVdiDk&_nc_gid=98DYNqaxwl81T1x2N1bKTA&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GHJZRxsAJAacMyEGAJkycXgoSpgtbkULAAAB3203200j-ccb7-5&oh=00_Af2mthntYes6gFxIzDxJkPO8eF38WqKWSd2W-uzx3zEUFQ&oe=69F0DC21&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/moumarion/",
      "title": "Marion Mou (@moumarion) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/moumarion"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
