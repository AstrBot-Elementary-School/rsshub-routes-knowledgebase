# Tumblr - Tagged Posts

## Coverage
`index-only`

## Route
- Namespace: `tumblr`
- Namespace Name: `Tumblr`
- Route Path: `/tumblr/tagged/:tag`
- Route Name: `Tagged Posts`
- Example: `/tumblr/tagged/nature`
- URL: `tumblr.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `PolarisStarnor`
- Source Location: `tagged.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag name (see `https://www.tumblr.com/docs/en/api/v2#tagged--get-posts-with-tag`)


## Features
- `requireConfig`: [{"description": "Please see above for details.", "name": "TUMBLR_CLIENT_ID"}, {"description": "Please see above for details.", "name": "TUMBLR_CLIENT_SECRET", "optional": true}, {"description": "Please see above for details.", "name": "TUMBLR_REFRESH_TOKEN", "optional": true}]
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
  "example": "/tumblr/tagged/nature",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_CLIENT_ID"
      },
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_CLIENT_SECRET",
        "optional": true
      },
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_REFRESH_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tagged.ts",
  "maintainers": [
    "PolarisStarnor"
  ],
  "name": "Tagged Posts",
  "parameters": {
    "tag": "Tag name (see `https://www.tumblr.com/docs/en/api/v2#tagged--get-posts-with-tag`)"
  },
  "path": "/tagged/:tag",
  "radar": [],
  "topFeeds": []
}
```
