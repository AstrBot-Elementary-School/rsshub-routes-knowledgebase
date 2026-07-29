# RSSHub - Transformation - Sitemap

## Coverage
`index-only`

## Route
- Namespace: `rsshub`
- Namespace Name: `RSSHub`
- Route Path: `/rsshub/transform/sitemap/:url/:routeParams?`
- Route Name: `Transformation - Sitemap`
- Example: `/rsshub/transform/sitemap/https%3A%2F%2Fwww.sitemaps.org%2Fsitemap.xml`
- URL: `docs.rsshub.app`
- Language: `_None_`
- Categories: `other`
- Maintainers: `flrngel`
- Source Location: `transform/sitemap.ts`
- Source Module: `_None_`

## Description
Specify options (in the format of query string) in parameter `routeParams` parameter to extract data from Sitemap. (Follows Sitemap Protocol 0.9)

| Key     | Meaning              | Accepted Values | Default                          |
| ------- | -------------------- | --------------- | -------------------------------- |
| `title` | The title of the RSS | `string`        | The first `<loc>` in the sitemap |

## Parameters
- `url`: `encodeURIComponent`ed URL address
- `routeParams`: Transformation rules, requires URL encode


## Features
- `requireConfig`: [{"description": "", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]
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
    "other"
  ],
  "description": "Specify options (in the format of query string) in parameter `routeParams` parameter to extract data from Sitemap. (Follows Sitemap Protocol 0.9)\n\n| Key     | Meaning              | Accepted Values | Default                          |\n| ------- | -------------------- | --------------- | -------------------------------- |\n| `title` | The title of the RSS | `string`        | The first `<loc>` in the sitemap |",
  "example": "/rsshub/transform/sitemap/https%3A%2F%2Fwww.sitemaps.org%2Fsitemap.xml",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "transform/sitemap.ts",
  "maintainers": [
    "flrngel"
  ],
  "name": "Transformation - Sitemap",
  "parameters": {
    "routeParams": "Transformation rules, requires URL encode",
    "url": "`encodeURIComponent`ed URL address"
  },
  "path": "/transform/sitemap/:url/:routeParams?",
  "topFeeds": []
}
```
