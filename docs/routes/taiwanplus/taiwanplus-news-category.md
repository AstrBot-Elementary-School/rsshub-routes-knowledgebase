# TaiwanPlus - News

## Coverage
`index-only`

## Route
- Namespace: `taiwanplus`
- Namespace Name: `TaiwanPlus`
- Route Path: `/taiwanplus/news/:category{.+}?`
- Route Name: `News`
- Example: `/taiwanplus/news/taiwan-news`
- URL: `www.taiwanplus.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `DIYgod`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: News category path from the website URL, defaults to taiwan-news.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.taiwanplus.com/news/:category*`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/taiwanplus/news/taiwan-news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "News",
  "parameters": {
    "category": "News category path from the website URL, defaults to taiwan-news."
  },
  "path": "/news/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.taiwanplus.com/news/:category*"
      ],
      "target": "/news/:category"
    }
  ],
  "topFeeds": []
}
```
