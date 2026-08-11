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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Current events from Wikipedia - Latest news and events - Powered by RSSHub",
      "errorAt": "2026-08-09T07:51:44.557Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
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
      "errorAt": "2026-08-09T03:16:10.806Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
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
