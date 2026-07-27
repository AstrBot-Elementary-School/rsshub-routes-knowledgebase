# Daily.dev - Most Discussed

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/discussed/:period?/:dateSort?`
- Route Name: `Most Discussed`
- Example: `/daily/discussed/30`
- URL: `app.daily.dev/discussed`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `discussed.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `dateSort`: {"default": "true", "description": "Sort posts by publication date instead of popularity", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}
- `period`: {"default": "7", "description": "Period of Lookup", "options": [{"label": "Last Week", "value": "7"}, {"label": "Last Month", "value": "30"}, {"label": "Last Year", "value": "365"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/discussed`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/discussed/30",
  "heat": 5,
  "location": "discussed.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Most Discussed",
  "parameters": {
    "dateSort": {
      "default": "true",
      "description": "Sort posts by publication date instead of popularity",
      "options": [
        {
          "label": "False",
          "value": "false"
        },
        {
          "label": "True",
          "value": "true"
        }
      ]
    },
    "period": {
      "default": "7",
      "description": "Period of Lookup",
      "options": [
        {
          "label": "Last Week",
          "value": "7"
        },
        {
          "label": "Last Month",
          "value": "30"
        },
        {
          "label": "Last Year",
          "value": "365"
        }
      ]
    }
  },
  "path": "/discussed/:period?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/discussed"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Stay on top of real-time developer discussions on daily.dev. Join conversations happening now and engage with the most active community members. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83025199966683136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.daily.dev/posts/discussed",
      "title": "Real-time discussions in the developer community | daily.dev",
      "type": "feed",
      "url": "rsshub://daily/discussed"
    }
  ],
  "url": "app.daily.dev/discussed",
  "view": 0
}
```
