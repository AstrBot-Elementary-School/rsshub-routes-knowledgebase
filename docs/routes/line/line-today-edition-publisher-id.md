# LINE - TODAY - Channel

## Coverage
`index-only`

## Route
- Namespace: `line`
- Namespace Name: `LINE`
- Route Path: `/line/today/:edition/publisher/:id`
- Route Name: `TODAY - Channel`
- Example: `/line/today/th/publisher/101048`
- URL: `today.line.me`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `publisher.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `edition`: Edition, see table above
- `id`: Channel ID, can be found in URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `today.line.me/:edition/v2/publisher/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/line/today/th/publisher/101048",
  "heat": 10,
  "location": "publisher.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "TODAY - Channel",
  "parameters": {
    "edition": "Edition, see table above",
    "id": "Channel ID, can be found in URL"
  },
  "path": "/today/:edition/publisher/:id",
  "radar": [
    {
      "source": [
        "today.line.me/:edition/v2/publisher/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "科技紫微網每日星座 - Line Today - Powered by RSSHub",
      "errorAt": "2026-05-03T00:47:45.789Z",
      "errorMessage": "Failed to fetch\n",
      "id": "92072410794728448",
      "image": "https://obs.line-scdn.net/0hwVRuQzivKHlvDAFT0BtXLlVaKxZcYDt6Czp5eixidk0VOTp8UG9mSE1edBoWNW8nB2xgGE8LM0gQNWd6W2hm",
      "ownerUserId": null,
      "siteUrl": "https://today.line.me/tw/v2/publisher/101266",
      "title": "科技紫微網每日星座 - Line Today",
      "type": "feed",
      "url": "rsshub://line/today/tw/publisher/101266"
    },
    {
      "description": "國際 on LINE - Line Today - Powered by RSSHub",
      "errorAt": "2026-08-18T06:51:00.116Z",
      "errorMessage": "Failed to fetch\n",
      "id": "79814217269594112",
      "image": "https://obs.line-scdn.net/0hRVlHgnY2DXlRMR9CkgdyLgVnDhZiXR56NQdcZg5fWx1-B0IuZAJeHSA4UVV5UksucV8SGXMtVxp0Ahp7bFcWH3EyUEopVk8mKFdCF31mV018",
      "ownerUserId": null,
      "siteUrl": "https://today.line.me/hk/v2/publisher/103238",
      "title": "國際 on LINE - Line Today",
      "type": "feed",
      "url": "rsshub://line/today/hk/publisher/103238"
    }
  ]
}
```
