# PornHub - Video List

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornhub/category_url/:url?/:language?/:img?`
- Route Name: `Video List`
- Example: `/pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp`
- URL: `pornhub.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `category-url.ts`
- Source Module: `_None_`

## Description
**`language`**

Refer to [Pornhub F.A.Qs](https://help.pornhub.com/hc/en-us/articles/360044327034-How-do-I-change-the-language-), English by default. For example:

- `cn` (Chinese), for Pornhub in China <https://cn.pornhub.com>；

- `jp` (Japanese), for Pornhub in Japan <https://jp.pornhub.com> etc.

## Parameters
- `language`: language, see below. defaults to `www` (English)
- `url`: relative path after `pornhub.com/`, need to be URL encoded
- `img`: show images, set to `img=1` to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "**`language`**\n\nRefer to [Pornhub F.A.Qs](https://help.pornhub.com/hc/en-us/articles/360044327034-How-do-I-change-the-language-), English by default. For example:\n\n- `cn` (Chinese), for Pornhub in China <https://cn.pornhub.com>；\n\n- `jp` (Japanese), for Pornhub in Japan <https://jp.pornhub.com> etc.",
  "example": "/pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 132,
  "location": "category-url.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "name": "Video List",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to `www` (English)",
    "url": "relative path after `pornhub.com/`, need to be URL encoded"
  },
  "path": "/category_url/:url?/:language?/:img?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Watch the Hottest Pornstars And Porn Movies | PornHub - Powered by RSSHub",
      "errorAt": "2026-10-01T07:40:40.329Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "73689953585256448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/video?o=ht",
      "title": "Watch the Hottest Pornstars And Porn Movies | PornHub",
      "type": "feed",
      "url": "rsshub://pornhub/category_url/video%3Fo%3Dht"
    },
    {
      "description": "Anal Creampie: Free Teen Creampies Videos | Pornhub - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58588081077915648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/video?c=15&o=mv&t=w&cc=jp",
      "title": "Anal Creampie: Free Teen Creampies Videos | Pornhub",
      "type": "feed",
      "url": "rsshub://pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp"
    }
  ]
}
```
