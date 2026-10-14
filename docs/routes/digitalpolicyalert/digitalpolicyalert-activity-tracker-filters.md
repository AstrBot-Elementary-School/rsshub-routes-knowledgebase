# Digital Policy Alert - Activity Tracker

## Coverage
`index-only`

## Route
- Namespace: `digitalpolicyalert`
- Namespace Name: `Digital Policy Alert`
- Route Path: `/digitalpolicyalert/activity-tracker/:filters?`
- Route Name: `Activity Tracker`
- Example: `/digitalpolicyalert/activity-tracker`
- URL: `digitalpolicyalert.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `activity-tracker.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Activity Tracker - International trade](https://digitalpolicyalert.org/activity-tracker?policy=1), where the source URL is `https://digitalpolicyalert.org/activity-tracker?policy=1`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/digitalpolicyalert/activity-tracker/policy=1`](https://rsshub.app/digitalpolicyalert/activity-tracker/policy=1).
:::

## Parameters
- `filters`: {"description": "Filter, all by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `digitalpolicyalert.org`
  - `digitalpolicyalert.org/activity-tracker`
  - `digitalpolicyalert.org/change/:slug`
- `target`: `/activity-tracker`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\nTo subscribe to [Activity Tracker - International trade](https://digitalpolicyalert.org/activity-tracker?policy=1), where the source URL is `https://digitalpolicyalert.org/activity-tracker?policy=1`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/digitalpolicyalert/activity-tracker/policy=1`](https://rsshub.app/digitalpolicyalert/activity-tracker/policy=1).\n:::",
  "example": "/digitalpolicyalert/activity-tracker",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "activity-tracker.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Activity Tracker",
  "parameters": {
    "filters": {
      "description": "Filter, all by default"
    }
  },
  "path": "/activity-tracker/:filters?",
  "radar": [
    {
      "source": [
        "digitalpolicyalert.org",
        "digitalpolicyalert.org/activity-tracker",
        "digitalpolicyalert.org/change/:slug"
      ],
      "target": "/activity-tracker"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "An independent, timely and accessible record of policy and regulatory changes affecting the digital economy. - Powered by RSSHub",
      "errorAt": "2025-11-13T18:01:23.942Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slice')\n",
      "id": "177934592594010112",
      "image": "https://digitalpolicyalert.org/img/main_image.png",
      "ownerUserId": null,
      "siteUrl": "https://digitalpolicyalert.org/activity-tracker?offset=0&limit=30",
      "title": "Activity Tracker - Digital Policy Alert",
      "type": "feed",
      "url": "rsshub://digitalpolicyalert/activity-tracker"
    }
  ],
  "url": "digitalpolicyalert.org",
  "view": 0
}
```
