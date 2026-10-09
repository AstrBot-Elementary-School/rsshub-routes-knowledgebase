# Yahoo - Publisher profiles

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/news/publisher/:publisher`
- Route Name: `Publisher profiles`
- Example: `/yahoo/news/publisher/reuters`
- URL: `news.yahoo.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DIYgod`
- Source Location: `news/publisher.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `publisher`: Publisher slug from profiles.yahoo.com/brands/:publisher/ (for example reuters, cnn or afp).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `profiles.yahoo.com/brands/:publisher`
- `target`: `/news/publisher/:publisher`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/yahoo/news/publisher/reuters",
  "heat": 0,
  "location": "news/publisher.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Publisher profiles",
  "parameters": {
    "publisher": "Publisher slug from profiles.yahoo.com/brands/:publisher/ (for example reuters, cnn or afp)."
  },
  "path": "/news/publisher/:publisher",
  "radar": [
    {
      "source": [
        "profiles.yahoo.com/brands/:publisher"
      ],
      "target": "/news/publisher/:publisher"
    }
  ],
  "topFeeds": []
}
```
