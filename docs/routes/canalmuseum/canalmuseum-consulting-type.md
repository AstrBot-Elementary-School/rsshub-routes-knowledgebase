# The Grand Canal Museum of Beijing - NEWS

## Coverage
`index-only`

## Route
- Namespace: `canalmuseum`
- Namespace Name: `The Grand Canal Museum of Beijing`
- Route Path: `/canalmuseum/consulting/:type`
- Route Name: `NEWS`
- Example: `/canalmuseum/consulting/tzgg`
- URL: `www.canalmuseum.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `consulting.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: News type, supported values: tzgg（通知公告）, xwdt（新闻动态）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.canalmuseum.org.cn/consulting.html`
- `target`: `/consulting/tzgg`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/canalmuseum/consulting/tzgg",
  "heat": 0,
  "location": "consulting.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "NEWS",
  "parameters": {
    "type": "News type, supported values: tzgg（通知公告）, xwdt（新闻动态）"
  },
  "path": "/consulting/:type",
  "radar": [
    {
      "source": [
        "www.canalmuseum.org.cn/consulting.html"
      ],
      "target": "/consulting/tzgg"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
