# Mastodon - User timeline (by account ID)

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/mastodon/account_id/:site/:account_id/statuses/:only_media?`
- Route Name: `User timeline (by account ID)`
- Example: `/mastodon/account_id/mas.to/109300507275095341/statuses/false`
- URL: `mastodon.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `notofoe, pseudoyu`
- Source Location: `account-id.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `site`: instance address, only domain, no `http://` or `https://` protocol header
- `account_id`: account ID, you can get it from `https://INSTANCE/api/v1/accounts/lookup?acct=USERNAME` api
- `only_media`: {"default": "false", "description": "whether only display media content, default to false, any value to true", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
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
    "social-media"
  ],
  "example": "/mastodon/account_id/mas.to/109300507275095341/statuses/false",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 55,
  "location": "account-id.ts",
  "maintainers": [
    "notofoe",
    "pseudoyu"
  ],
  "name": "User timeline (by account ID)",
  "parameters": {
    "account_id": "account ID, you can get it from `https://INSTANCE/api/v1/accounts/lookup?acct=USERNAME` api",
    "only_media": {
      "default": "false",
      "description": "whether only display media content, default to false, any value to true",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    },
    "site": "instance address, only domain, no `http://` or `https://` protocol header"
  },
  "path": "/account_id/:site/:account_id/statuses/:only_media?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "<p>We are one of the largest online libraries in the world. We aim to make literature and knowledge accessible to everyone 🕊️📚</p><p>📧 support@z-lib.fm</p> - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72480233900826624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mastodon.social/@Z_Lib_official",
      "title": "Z-Library Official (@Z_Lib_official)",
      "type": "feed",
      "url": "rsshub://mastodon/account_id/mastodon.social/110560361984531227/statuses/false"
    },
    {
      "description": "<p>社会学的门徒 / 确诊了ADHD / 半吊子程序员</p> - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67090775398070272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://expressional.social/@AHpx",
      "title": "破晓 (@AHpx)",
      "type": "feed",
      "url": "rsshub://mastodon/account_id/expressional.social/109640365871887551/statuses/false"
    }
  ],
  "view": 1
}
```
