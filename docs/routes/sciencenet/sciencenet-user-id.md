# 科学网 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `sciencenet`
- Namespace Name: `科学网`
- Route Path: `/sciencenet/user/:id`
- Route Name: `用户博客`
- Example: `/sciencenet/user/tony8310`
- URL: `blog.sciencenet.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id，可在对用户博客页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `blog.sciencenet.cn/u/:id`
  - `blog.sciencenet.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sciencenet/user/tony8310",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 37,
  "location": "user.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户博客",
  "parameters": {
    "id": "用户 id，可在对用户博客页 URL 中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "blog.sciencenet.cn/u/:id",
        "blog.sciencenet.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "科学网 - 王树义的博文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66855175407694848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.sciencenet.cn/u/wshuyi",
      "title": "科学网 - 王树义的博文",
      "type": "feed",
      "url": "rsshub://sciencenet/user/wshuyi"
    },
    {
      "description": "科学网 - 朱豫才的博文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66637908923103232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.sciencenet.cn/u/zhuyucai1",
      "title": "科学网 - 朱豫才的博文",
      "type": "feed",
      "url": "rsshub://sciencenet/user/zhuyucai1"
    }
  ]
}
```
