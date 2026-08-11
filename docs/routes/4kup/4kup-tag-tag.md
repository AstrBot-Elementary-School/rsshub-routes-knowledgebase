# 4KUP - Tag

## Coverage
`index-only`

## Route
- Namespace: `4kup`
- Namespace Name: `4KUP`
- Route Path: `/4kup/tag/:tag`
- Route Name: `Tag`
- Example: `/4kup/tag/asian`
- URL: `4kup.net/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag


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
  - `4kup.net/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4kup/tag/asian",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 111,
  "location": "tag.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Tag",
  "parameters": {
    "tag": "Tag"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "4kup.net/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "4KUP - Tag: adult - Powered by RSSHub",
      "errorAt": "2025-07-16T06:57:47.435Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "146184443590645760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://4kup.net/tag/adult/",
      "title": "4KUP - Tag: adult",
      "type": "feed",
      "url": "rsshub://4kup/tag/adult"
    },
    {
      "description": "4KUP - Tag: asian - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "106603704433946624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://4kup.net/tag/asian/",
      "title": "4KUP - Tag: asian",
      "type": "feed",
      "url": "rsshub://4kup/tag/asian"
    }
  ],
  "url": "4kup.net/"
}
```
