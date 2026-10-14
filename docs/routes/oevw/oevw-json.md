# ÖVW - Suche

## Coverage
`index-only`

## Route
- Namespace: `oevw`
- Namespace Name: `ÖVW`
- Route Path: `/oevw/:json?`
- Route Name: `Suche`
- Example: `/oevw/%7B%22rooms%22%3A%5B%222%22%2C%223%22%5D%7D`
- URL: `oevw.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
When applying a filter on <https://www.oevw.at/suche>, a POST request is sent
to <https://www.oevw.at/suche/filter>. You can take its JSON body, URL-encode it
(`encodeURIComponent('{...}')`) and append it to the URL, see example URL.
for this route.

## Parameters
- `json`: JSON request body, as sent to oevw.at/suche


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "When applying a filter on <https://www.oevw.at/suche>, a POST request is sent\nto <https://www.oevw.at/suche/filter>. You can take its JSON body, URL-encode it\n(`encodeURIComponent('{...}')`) and append it to the URL, see example URL.\nfor this route.",
  "example": "/oevw/%7B%22rooms%22%3A%5B%222%22%2C%223%22%5D%7D",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Suche",
  "parameters": {
    "json": "JSON request body, as sent to oevw.at/suche"
  },
  "path": "/:json?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
