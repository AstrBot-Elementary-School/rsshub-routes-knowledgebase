# InfoQ 中文 - Presentations

## Coverage
`index-only`

## Route
- Namespace: `infoq`
- Namespace Name: `InfoQ 中文`
- Route Path: `/infoq/presentations/:conference?`
- Route Name: `Presentations`
- Example: `/infoq/presentations`
- URL: `www.infoq.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `presentations.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [InfoQ Live Jan 2024](https://www.infoq.com/infoq-live-jan-2024/presentations/)，where the URL is `https://www.infoq.com/infoq-live-jan-2024/presentations/`, extract the part `https://www.infoq.com/` to the end, which is `/presentations/`, and use it as the parameter to fill in. Therefore, the route will be [`/infoq/presentations/infoq-live-jan-2024`](https://rsshub.app/infoq/presentations/infoq-live-jan-2024).
:::

## Parameters
- `conference`: Conference, all by default, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.infoq.com/presentations`
  - `www.infoq.com/:conference/presentations`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\nIf you subscribe to [InfoQ Live Jan 2024](https://www.infoq.com/infoq-live-jan-2024/presentations/)，where the URL is `https://www.infoq.com/infoq-live-jan-2024/presentations/`, extract the part `https://www.infoq.com/` to the end, which is `/presentations/`, and use it as the parameter to fill in. Therefore, the route will be [`/infoq/presentations/infoq-live-jan-2024`](https://rsshub.app/infoq/presentations/infoq-live-jan-2024).\n:::",
  "example": "/infoq/presentations",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 184,
  "location": "presentations.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Presentations",
  "parameters": {
    "conference": "Conference, all by default, can be found in URL"
  },
  "path": "/presentations/:conference?",
  "radar": [
    {
      "source": [
        "www.infoq.com/presentations",
        "www.infoq.com/:conference/presentations"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Presentations from QCon London 2018, QCon New York 2018, SpringOne Platform 2018, and more - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70149738744378368",
      "image": "https://cdn.infoq.com/statics_s1_20260714062335/styles/static/images/logo/logo-big.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.infoq.com/presentations/",
      "title": "Presentations > Page #1 - InfoQ",
      "type": "feed",
      "url": "rsshub://infoq/presentations"
    },
    {
      "description": "Presentations from QCon London 2018, QCon New York 2018, SpringOne Platform 2018, and more - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70796779118347264",
      "image": "https://cdn.infoq.com/statics_s1_20260311083832-1/styles/static/images/logo/logo-big.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.infoq.com/:conference/presentations/",
      "title": "Presentations > Page #1 - InfoQ",
      "type": "feed",
      "url": "rsshub://infoq/presentations/:conference"
    }
  ],
  "url": "www.infoq.com"
}
```
