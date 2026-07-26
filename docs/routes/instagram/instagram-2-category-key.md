# Instagram - User Profile / Hashtag

## Coverage
`index-only`

## Route
- Namespace: `instagram`
- Namespace Name: `Instagram`
- Route Path: `/instagram/2/:category/:key`
- Route Name: `User Profile / Hashtag`
- Example: `/instagram/2/user/stefaniejoosten`
- URL: `www.instagram.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `web-api/index.ts`
- Source Module: `_None_`

## Description
::: tip
You may need to setup cookie for a less restrictive rate limit and private profiles.
:::

| User timeline | Hashtag |
| ------------- | ------- |
| user          | tags    |

## Parameters
- `category`: Feed category, see table below
- `key`: Username / Hashtag name


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: tip\nYou may need to setup cookie for a less restrictive rate limit and private profiles.\n:::\n\n| User timeline | Hashtag |\n| ------------- | ------- |\n| user          | tags    |",
  "example": "/instagram/2/user/stefaniejoosten",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 364,
  "location": "web-api/index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Profile / Hashtag",
  "parameters": {
    "category": "Feed category, see table below",
    "key": "Username / Hashtag name"
  },
  "path": "/2/:category/:key",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Madonna actress 📩 Business inquiries only DMはお仕事のご依頼のみ承ります - Powered by RSSHub",
      "errorAt": "2026-02-06T17:14:42.699Z",
      "errorMessage": "[GET] \"https://www.instagram.com/api/v1/users/web_profile_info/?username=niizuma_cmore\": <no response> fetch failed (Connect Timeout Error (attempted address: www.instagram.com:443, timeout: 10000ms))\nAuthentication failed. Access denied.\n/instagram/2/user/niizuma_cmore\n[GET] \"https://www.instagram.com/api/v1/users/web_profile_info/?username=niizuma_cmore\": 429 Too Many Requests\n",
      "id": "168564693075937280",
      "image": "https://scontent-bom2-3.cdninstagram.com/v/t51.2885-19/537813338_17874088467407269_4465696083181389766_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-bom2-3.cdninstagram.com&_nc_cat=101&_nc_oc=Q6cZ2QGS5cpAIuKyPHoKR-J0SVEMJTZmWm9mwXe7T1iYQvvvNG6tcnZq44q3uY5j1UHQ9Hg&_nc_ohc=Rzm3HvhVuhYQ7kNvwGsHC6Q&_nc_gid=tJtg6-BmPewFhE1crgz90g&edm=AOQ1c0wBAAAA&ccb=7-5&oh=00_Afs-EmeyrJ3DGHBUuDIKh2fQ52vHr6jp1un1phG_DP9e6A&oe=698B7C78&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/niizuma_cmore",
      "title": "新妻ゆうか｜Yuuka Niizuma (@niizuma_cmore) - Instagram",
      "type": "feed",
      "url": "rsshub://instagram/2/user/niizuma_cmore"
    },
    {
      "description": "リスタープロ所属。子役→塾講師→グラビアアイドル→MUTEKI ちいかわ好きです お仕事の依頼について→info@listarpro.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168841072365077504",
      "image": "https://scontent-sin6-3.cdninstagram.com/v/t51.2885-19/365432985_1321784328764826_5416763734837577804_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-sin6-3.cdninstagram.com&_nc_cat=106&_nc_oc=Q6cZ2gEWqKZr5C4MKZuGyKQihCyxSvdPohobzKnMBMHxlornaYex6tCf-IiXSpOiTiSwy6I&_nc_ohc=SM2It1L4BZsQ7kNvwE3SK61&_nc_gid=oxXvVOYgUQr247L6_9rbbw&edm=AOQ1c0wBAAAA&ccb=7-5&oh=00_Af2a90cpN5jZRT_BEDh8xpuWkHQW0o1msJ7wQ0inQeI77w&oe=69F42FAE&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/rui_shido",
      "title": "紫堂るい (@rui_shido) - Instagram",
      "type": "feed",
      "url": "rsshub://instagram/2/user/rui_shido"
    }
  ]
}
```
