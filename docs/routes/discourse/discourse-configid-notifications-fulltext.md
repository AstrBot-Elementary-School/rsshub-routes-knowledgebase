# Discourse - Notifications

## Coverage
`index-only`

## Route
- Namespace: `discourse`
- Namespace Name: `Discourse`
- Route Path: `/discourse/:configId/notifications/:fulltext?`
- Route Name: `Notifications`
- Example: `/discourse/0/notifications`
- URL: `_None_`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `dzx-dzx`
- Source Location: `notifications.ts`
- Source Module: `_None_`

## Description
::: warning
If you opt to enable `fulltext` feature, consider adding `limit` parameter to your query to avoid sending too many request.
:::

## Parameters
- `configId`: Environment variable configuration id, see above
- `fulltext`: Fetch the content if the notification points to a post. This is disabled by default, set it to `1` to enable it.


## Features
- `requireConfig`: [{"description": "", "name": "DISCOURSE_CONFIG_*"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: warning\nIf you opt to enable `fulltext` feature, consider adding `limit` parameter to your query to avoid sending too many request.\n:::",
  "example": "/discourse/0/notifications",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "DISCOURSE_CONFIG_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "notifications.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "Notifications",
  "parameters": {
    "configId": "Environment variable configuration id, see above",
    "fulltext": "Fetch the content if the notification points to a post. This is disabled by default, set it to `1` to enable it."
  },
  "path": "/:configId/notifications/:fulltext?",
  "topFeeds": []
}
```
