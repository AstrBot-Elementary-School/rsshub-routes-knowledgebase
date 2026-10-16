# 司机社 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `xsijishe`
- Namespace Name: `司机社`
- Route Path: `/xsijishe/rank/:type`
- Route Name: `排行榜`
- Example: `/xsijishe/rank/weekly`
- URL: `xsijishe.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `akynazh, AiraNadih`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "排行榜类型", "options": [{"label": "周榜", "value": "weekly"}, {"label": "月榜", "value": "monthly"}]}


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
    "bbs",
    "popular"
  ],
  "example": "/xsijishe/rank/weekly",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4893,
  "location": "rank.ts",
  "maintainers": [
    "akynazh",
    "AiraNadih"
  ],
  "name": "排行榜",
  "parameters": {
    "type": {
      "description": "排行榜类型",
      "options": [
        {
          "label": "周榜",
          "value": "weekly"
        },
        {
          "label": "月榜",
          "value": "monthly"
        }
      ]
    }
  },
  "path": "/rank/:type",
  "topFeeds": [
    {
      "description": "司机社综合月排行榜 - Powered by RSSHub",
      "errorAt": "2026-10-15T03:14:46.904Z",
      "errorMessage": "[GET] \"https://xsijishe.com/portal.php\": 403 \n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /home/sbx_user1051/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\n500 \nFailed to fetch\n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\n",
      "id": "41511702474276884",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/portal.php",
      "title": "司机社综合月排行榜",
      "type": "feed",
      "url": "rsshub://xsijishe/rank/monthly"
    },
    {
      "description": "司机社综合周排行榜 - Powered by RSSHub",
      "errorAt": "2026-10-15T02:37:18.416Z",
      "errorMessage": "[GET] \"https://xsijishe.com/portal.php\": 403 \n[GET] \"https://xsijishe.com/portal.php\": 403 \n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\n[GET] \"https://xsijishe.com/portal.php\": 403 \nCould not find Chrome (ver. 123.0.6312.86). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\n",
      "id": "41707595233790976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/portal.php",
      "title": "司机社综合周排行榜",
      "type": "feed",
      "url": "rsshub://xsijishe/rank/weekly"
    }
  ]
}
```
