# VICE - Topic

## Coverage
`index-only`

## Route
- Namespace: `vice`
- Namespace Name: `VICE`
- Route Path: `/vice/topic/:topic/:language?`
- Route Name: `Topic`
- Example: `/vice/topic/politics/en`
- URL: `vice.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `K33k0`
- Source Location: `topic.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Can be found in the URL
- `language`: defaults to `en`, use the website to discover other codes


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.vice.com/:language/topic/:topic`
  - `www.vice.com/:language/tag/:topic`
- `target`: `/topic/:topic/:language`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/vice/topic/politics/en",
  "heat": 1,
  "location": "topic.tsx",
  "maintainers": [
    "K33k0"
  ],
  "name": "Topic",
  "parameters": {
    "language": "defaults to `en`, use the website to discover other codes",
    "topic": "Can be found in the URL"
  },
  "path": "/topic/:topic/:language?",
  "radar": [
    {
      "source": [
        "www.vice.com/:language/topic/:topic",
        "www.vice.com/:language/tag/:topic"
      ],
      "target": "/topic/:topic/:language"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "VICE | 123 articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1333814591167004672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.vice.com/en/tag/123/",
      "title": "VICE | 123 articles",
      "type": "feed",
      "url": "rsshub://vice/topic/123"
    }
  ],
  "url": "vice.com/"
}
```
