# M+博物館 - 雜誌、展覽與今日呈獻

## Coverage
`index-only`

## Route
- Namespace: `mplus`
- Namespace Name: `M+博物館`
- Route Path: `/mplus/content/:section?`
- Route Name: `雜誌、展覽與今日呈獻`
- Example: `/mplus/content/magazine`
- URL: `www.mplus.org.hk`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `DIYgod`
- Source Location: `content.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: magazine（雜誌，預設）、exhibitions（展覽）或 today（今日呈獻）。


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.mplus.org.hk/tc/:section`
- `target`: `/content/:section`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/mplus/content/magazine",
  "heat": 0,
  "location": "content.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "雜誌、展覽與今日呈獻",
  "parameters": {
    "section": "magazine（雜誌，預設）、exhibitions（展覽）或 today（今日呈獻）。"
  },
  "path": "/content/:section?",
  "radar": [
    {
      "source": [
        "www.mplus.org.hk/tc/:section"
      ],
      "target": "/content/:section"
    }
  ],
  "topFeeds": []
}
```
