# DLsite - Ci-en Creators' Article

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/dlsite/ci-en/:id/article`
- Route Name: `Ci-en Creators' Article`
- Example: `/dlsite/ci-en/7400/article`
- URL: `dlsite.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `ci-en/article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Creator id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `ci-en.dlsite.com/creator/:id/article/843558`
  - `ci-en.dlsite.com/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/dlsite/ci-en/7400/article",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "ci-en/article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Ci-en Creators' Article",
  "parameters": {
    "id": "Creator id, can be found in URL"
  },
  "path": "/ci-en/:id/article",
  "radar": [
    {
      "source": [
        "ci-en.dlsite.com/creator/:id/article/843558",
        "ci-en.dlsite.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "BBQ大好きの記事一覧 - Ci-en（シエン） - Powered by RSSHub",
      "errorAt": "2025-11-06T04:45:37.496Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "72513717942538240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ci-en.dlsite.com/creator/7400/article?mode=list",
      "title": "BBQ大好きの記事一覧 - Ci-en（シエン）",
      "type": "feed",
      "url": "rsshub://dlsite/ci-en/7400/article"
    },
    {
      "description": "しもばしら工房の記事一覧 - Ci-en（シエン） - Powered by RSSHub",
      "errorAt": "2025-11-06T04:28:44.197Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "71888583981323264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ci-en.dlsite.com/creator/4551/article?mode=list",
      "title": "しもばしら工房の記事一覧 - Ci-en（シエン）",
      "type": "feed",
      "url": "rsshub://dlsite/ci-en/4551/article"
    }
  ],
  "view": 0
}
```
