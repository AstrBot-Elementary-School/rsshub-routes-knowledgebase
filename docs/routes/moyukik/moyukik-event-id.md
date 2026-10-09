# 摸鱼 kik - 事件追踪

## Coverage
`index-only`

## Route
- Namespace: `moyukik`
- Namespace Name: `摸鱼 kik`
- Route Path: `/moyukik/event/:id`
- Route Name: `事件追踪`
- Example: `/moyukik/event/65512562447749138`
- URL: `h5-ol.sns.sohu.com/hy-moyukik-h5`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DIYgod`
- Source Location: `event.ts`
- Source Module: `_None_`

## Description
Includes the latest entries on the public share page and their complete public article content.

## Parameters
- `id`: Event ID from the share URL.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `h5-ol.sns.sohu.com/hy-moyukik-h5/share/event/:id`
- `target`: `/event/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Includes the latest entries on the public share page and their complete public article content.",
  "example": "/moyukik/event/65512562447749138",
  "heat": 0,
  "location": "event.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "事件追踪",
  "parameters": {
    "id": "Event ID from the share URL."
  },
  "path": "/event/:id",
  "radar": [
    {
      "source": [
        "h5-ol.sns.sohu.com/hy-moyukik-h5/share/event/:id"
      ],
      "target": "/event/:id"
    }
  ],
  "topFeeds": []
}
```
