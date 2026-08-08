# Wikipedia - Current Events

## Coverage
`index-only`

## Route
- Namespace: `wikipedia`
- Namespace Name: `Wikipedia`
- Route Path: `/wikipedia/current-events/:includeToday?`
- Route Name: `Current Events`
- Example: `/wikipedia/current-events`
- URL: `en.wikipedia.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `aavanian`
- Source Location: `current-events.ts`
- Source Module: `_None_`

## Description
Wikipedia Portal: Current events - Latest news and events from the past 7 days

## Parameters
- `includeToday`: {"default": "auto", "description": "Include current day events (may be incomplete early in the day)", "options": [{"label": "Auto (include after 18:00 UTC)", "value": "auto"}, {"label": "Always include current day", "value": "always"}, {"label": "Never include current day", "value": "never"}, {"label": "Include after specific UTC hour (0-23)", "value": "0-23"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `en.wikipedia.org/wiki/Portal:Current_events`
- `target`: `/wikipedia/current-events`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Wikipedia Portal: Current events - Latest news and events from the past 7 days",
  "example": "/wikipedia/current-events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "current-events.ts",
  "maintainers": [
    "aavanian"
  ],
  "name": "Current Events",
  "parameters": {
    "includeToday": {
      "default": "auto",
      "description": "Include current day events (may be incomplete early in the day)",
      "options": [
        {
          "label": "Auto (include after 18:00 UTC)",
          "value": "auto"
        },
        {
          "label": "Always include current day",
          "value": "always"
        },
        {
          "label": "Never include current day",
          "value": "never"
        },
        {
          "label": "Include after specific UTC hour (0-23)",
          "value": "0-23"
        }
      ]
    }
  },
  "path": "/current-events/:includeToday?",
  "radar": [
    {
      "source": [
        "en.wikipedia.org/wiki/Portal:Current_events"
      ],
      "target": "/wikipedia/current-events"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Current events from Wikipedia - Latest news and events - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "192950772436249600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://en.wikipedia.org/wiki/Portal:Current_events",
      "title": "Wikipedia: Portal: Current events",
      "type": "feed",
      "url": "rsshub://wikipedia/current-events/auto"
    },
    {
      "description": "Current events from Wikipedia - Latest news and events - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "192777430745038848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://en.wikipedia.org/wiki/Portal:Current_events",
      "title": "Wikipedia: Portal: Current events",
      "type": "feed",
      "url": "rsshub://wikipedia/current-events"
    }
  ]
}
```
