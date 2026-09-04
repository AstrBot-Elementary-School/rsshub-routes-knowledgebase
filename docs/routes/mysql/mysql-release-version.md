# MySQL - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `mysql`
- Namespace Name: `MySQL`
- Route Path: `/mysql/release/:version?`
- Route Name: `Release Notes`
- Example: `/mysql/release/8.0`
- URL: `dev.mysql.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `release.ts`
- Source Module: `_None_`

## Description
| 8.0 | 5.7 | 5.6 |
| --- | --- | --- |

## Parameters
- `version`: Version, see below, 8.0 by default


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
    "programming"
  ],
  "description": "| 8.0 | 5.7 | 5.6 |\n| --- | --- | --- |",
  "example": "/mysql/release/8.0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "release.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Release Notes",
  "parameters": {
    "version": "Version, see below, 8.0 by default"
  },
  "path": "/release/:version?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "MySQL :: MySQL 8.0 Release Notes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62150011386109952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dev.mysql.com/doc/relnotes/mysql/8.0/en/",
      "title": "MySQL :: MySQL 8.0 Release Notes",
      "type": "feed",
      "url": "rsshub://mysql/release"
    },
    {
      "description": "MySQL :: MySQL 8.0 Release Notes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68567265391075328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dev.mysql.com/doc/relnotes/mysql/8.0/en/",
      "title": "MySQL :: MySQL 8.0 Release Notes",
      "type": "feed",
      "url": "rsshub://mysql/release/8.0"
    }
  ]
}
```
