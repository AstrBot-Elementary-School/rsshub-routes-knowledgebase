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
  "heat": 0,
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
  "topFeeds": [],
  "url": "vice.com/"
}
```
