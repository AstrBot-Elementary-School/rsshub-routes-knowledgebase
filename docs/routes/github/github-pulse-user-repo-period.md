# GitHub - Repo Pulse

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/pulse/:user/:repo/:period?`
- Route Name: `Repo Pulse`
- Example: `/github/pulse/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `jameschensmith`
- Source Location: `pulse.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name
- `period`: Time frame, selected from a repository's Pulse/Insights page. Possible values are: `daily`, `halfweekly`, `weekly`, or `monthly`. Default: `weekly`. If your RSS client supports it, consider aligning the polling frequency of the feed to the period.


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
  - `github.com/:user/:repo/pulse`
  - `github.com/:user/:repo/pulse/:period`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/pulse/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "pulse.tsx",
  "maintainers": [
    "jameschensmith"
  ],
  "name": "Repo Pulse",
  "parameters": {
    "period": "Time frame, selected from a repository's Pulse/Insights page. Possible values are: `daily`, `halfweekly`, `weekly`, or `monthly`. Default: `weekly`. If your RSS client supports it, consider aligning the polling frequency of the feed to the period.",
    "repo": "Repo name",
    "user": "User name"
  },
  "path": "/pulse/:user/:repo/:period?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/pulse",
        "github.com/:user/:repo/pulse/:period"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "datawhalechina/llm-universe weekly Pulse - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "137417584044606464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/datawhalechina/llm-universe/pulse/weekly",
      "title": "datawhalechina/llm-universe weekly Pulse",
      "type": "feed",
      "url": "rsshub://github/pulse/datawhalechina/llm-universe"
    },
    {
      "description": "RVC-Project/Retrieval-based-Voice-Conversion-WebUI weekly Pulse - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "220767323256864795",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI/pulse/weekly",
      "title": "RVC-Project/Retrieval-based-Voice-Conversion-WebUI weekly Pulse",
      "type": "feed",
      "url": "rsshub://github/pulse/RVC-Project/Retrieval-based-Voice-Conversion-WebUI/weekly"
    }
  ]
}
```
