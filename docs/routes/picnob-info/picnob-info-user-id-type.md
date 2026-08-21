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
  "heat": 13849,
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
      "description": "Street portraits . Travel . Stories Contact | filipe.o.pinhas@gmail.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64208632419650560",
      "image": "https://media.picnob.info/get?url=https://scontent-cph2-1.cdninstagram.com/v/t51.2885-19/93142683_1345688262283077_6234904053944418304_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-cph2-1.cdninstagram.com&_nc_cat=109&_nc_oc=Q6cZ2gGAYbpYQAVQvN8MY6AAmeqJ_nHmvKduHtAEqiuV5DpWERucLa-qkG48MneR31-GrO4&_nc_ohc=5log6Ge2woUQ7kNvwFRLxw0&_nc_gid=Tq3KcUbn9oTOQBLtsfVo3Q&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GJs_jQVFD9p25ccEAAAAAAA01IZWbkULAAAB3203200j-ccb7-5&oh=00_Af0guCSRSRgtY64SkRgsnW4Q5NNx3Kb88lfdIBqBywQlrw&oe=69F0F963&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/filipepinhas/",
      "title": "Filipe Pinhas (@filipepinhas) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/filipepinhas"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
