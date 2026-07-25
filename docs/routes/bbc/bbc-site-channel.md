# BBC - News

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/bbc/:site?/:channel?`
- Route Name: `News`
- Example: `/bbc/world-asia`
- URL: `bbc.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `HenryQW, DIYgod, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Provides a better reading experience (full text articles) over the official ones.

Support major channels, refer to [BBC RSS feeds](https://www.bbc.co.uk/news/10628494). Eg, `business` for `https://feeds.bbci.co.uk/news/business/rss.xml`.

- Channel contains sub-directories, such as `https://feeds.bbci.co.uk/news/world/asia/rss.xml`, replace `/` with `-`, `/bbc/world-asia`.

## Parameters
- `site`: 语言，简体或繁体中文
- `channel`: channel, default to `top stories`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "Provides a better reading experience (full text articles) over the official ones.\n\nSupport major channels, refer to [BBC RSS feeds](https://www.bbc.co.uk/news/10628494). Eg, `business` for `https://feeds.bbci.co.uk/news/business/rss.xml`.\n\n- Channel contains sub-directories, such as `https://feeds.bbci.co.uk/news/world/asia/rss.xml`, replace `/` with `-`, `/bbc/world-asia`.",
  "example": "/bbc/world-asia",
  "heat": 2428,
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "DIYgod",
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {
    "channel": "channel, default to `top stories`",
    "site": "语言，简体或繁体中文"
  },
  "path": "/:site?/:channel?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "BBC News 中文网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41965184796581990",
      "image": "https://www.bbc.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "BBC News 中文网",
      "type": "feed",
      "url": "rsshub://bbc/chinese"
    },
    {
      "description": "BBC News Top Stories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55115129833870338",
      "image": "https://www.bbc.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.bbc.co.uk/news",
      "title": "BBC News Top Stories",
      "type": "feed",
      "url": "rsshub://bbc"
    }
  ]
}
```
