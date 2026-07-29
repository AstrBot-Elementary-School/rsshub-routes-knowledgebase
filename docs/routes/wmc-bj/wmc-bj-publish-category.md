# World Meteorological Centre Beijing - Publish

## Coverage
`index-only`

## Route
- Namespace: `wmc-bj`
- Namespace Name: `World Meteorological Centre Beijing`
- Route Path: `/wmc-bj/publish/:category{.+}?`
- Route Name: `Publish`
- Example: `/wmc-bj/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html`
- URL: `wmc-bj.net`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `publish.tsx`
- Source Module: `_None_`

## Description
::: tip
`category` is the text after `publish/` in the URL.

eg. The URL for [Monitoring\_CMA-RA\_2m-Temperature\_6-hour](http://www.wmc-bj.net/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html) is <http://www.wmc-bj.net/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html>. The `category` for route can be represented as [`/wmc-bj/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html`](https://rsshub.app/wmc-bj/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html).
:::

## Parameters
- `category`: Category, can be found in URL, `CRA-Reanalysis/2m-Temperature/6-hour/index.html` by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n`category` is the text after `publish/` in the URL.\n\neg. The URL for [Monitoring\\_CMA-RA\\_2m-Temperature\\_6-hour](http://www.wmc-bj.net/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html) is <http://www.wmc-bj.net/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html>. The `category` for route can be represented as [`/wmc-bj/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html`](https://rsshub.app/wmc-bj/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html).\n:::",
  "example": "/wmc-bj/publish/CRA-Reanalysis/2m-Temperature/6-hour/index.html",
  "heat": 0,
  "location": "publish.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Publish",
  "parameters": {
    "category": "Category, can be found in URL, `CRA-Reanalysis/2m-Temperature/6-hour/index.html` by default"
  },
  "path": "/publish/:category{.+}?",
  "topFeeds": []
}
```
