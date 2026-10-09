# El País - News

## Coverage
`index-only`

## Route
- Namespace: `elpais`
- Namespace Name: `El País`
- Route Path: `/elpais/news`
- Route Name: `News`
- Example: `/elpais/news`
- URL: `elpais.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DIYgod`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Includes full text for articles marked publicly accessible by El País. Subscription articles retain their official RSS summary.

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `elpais.com`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Includes full text for articles marked publicly accessible by El País. Subscription articles retain their official RSS summary.",
  "example": "/elpais/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "elpais.com"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": []
}
```
