# Nature Journal - Unknown

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/news-and-comment/:journal?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `nature.com/latest-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `news-and-comment.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "heat": 50,
  "location": "news-and-comment.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Unknown",
  "path": "/news-and-comment/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": [
    {
      "description": "Read the latest News & Comment articles from Nature Energy - Powered by RSSHub",
      "errorAt": "2026-06-27T11:13:28.185Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "160596099235667968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nenergy/news-and-comment",
      "title": "News & Comment | Nature Energy",
      "type": "feed",
      "url": "rsshub://nature/news-and-comment/nenergy"
    },
    {
      "description": "Read the latest News & Comment articles from Nature Geoscience - Powered by RSSHub",
      "errorAt": "2026-06-19T17:23:36.879Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "160604172723269632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/ngeo/news-and-comment",
      "title": "News & Comment | Nature Geoscience",
      "type": "feed",
      "url": "rsshub://nature/news-and-comment/ngeo"
    }
  ],
  "url": "nature.com/latest-news"
}
```
