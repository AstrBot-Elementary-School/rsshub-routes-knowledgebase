# Reuters - My News

## Coverage
`index-only`

## Route
- Namespace: `reuters`
- Namespace Name: `Reuters`
- Route Path: `/reuters/my-news`
- Route Name: `My News`
- Example: `/reuters/my-news`
- URL: `reuters.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `my-news.ts`
- Source Module: `_None_`

## Description
The first page of the configured Reuters account's personalized My News feed. Requires a self-hosted instance with `REUTERS_AUTH_TOKEN` configured.

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "Sign in to Reuters and open Browser Devtools to find `rt_token` from Local Storage.", "name": "REUTERS_AUTH_TOKEN", "optional": false}]
- `requirePuppeteer`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "The first page of the configured Reuters account's personalized My News feed. Requires a self-hosted instance with `REUTERS_AUTH_TOKEN` configured.",
  "example": "/reuters/my-news",
  "features": {
    "requireConfig": [
      {
        "description": "Sign in to Reuters and open Browser Devtools to find `rt_token` from Local Storage.",
        "name": "REUTERS_AUTH_TOKEN",
        "optional": false
      }
    ],
    "requirePuppeteer": false
  },
  "heat": 0,
  "location": "my-news.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "My News",
  "path": "/my-news",
  "topFeeds": [],
  "view": 0
}
```
