# Google - Fonts

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/fonts/:sort?`
- Route Name: `Fonts`
- Example: `/google/fonts/date`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `Fatpandac`
- Source Location: `fonts.tsx`
- Source Module: `_None_`

## Description
| Newest | Trending | Most popular |  Name | Number of styles |
| :----: | :------: | :----------: | :---: | :--------------: |
|  date  | trending |  popularity  | alpha |       style      |

::: warning
This route requires API key, therefore it's only available when self-hosting, refer to the [Deploy Guide](https://docs.rsshub.app/deploy/config#route-specific-configurations) for route-specific configurations.
:::

## Parameters
- `sort`: Sorting type, see below, default to `date`


## Features
- `requireConfig`: [{"description": "", "name": "GOOGLE_FONTS_API_KEY"}]
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
    "design"
  ],
  "description": "| Newest | Trending | Most popular |  Name | Number of styles |\n| :----: | :------: | :----------: | :---: | :--------------: |\n|  date  | trending |  popularity  | alpha |       style      |\n\n::: warning\nThis route requires API key, therefore it's only available when self-hosting, refer to the [Deploy Guide](https://docs.rsshub.app/deploy/config#route-specific-configurations) for route-specific configurations.\n:::",
  "example": "/google/fonts/date",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "GOOGLE_FONTS_API_KEY"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "fonts.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Fonts",
  "parameters": {
    "sort": "Sorting type, see below, default to `date`"
  },
  "path": "/fonts/:sort?",
  "topFeeds": []
}
```
