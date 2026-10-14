# Daily.dev - Most upvoted

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/upvoted/:period?/:dateSort?`
- Route Name: `Most upvoted`
- Example: `/daily/upvoted/7`
- URL: `app.daily.dev/upvoted`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `upvoted.ts`
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
  - `daily.dev/posts/upvoted`
  - `daily.dev/upvoted`
- `target`: `/upvoted`
### Rule 2
- `source`:
  - `app.daily.dev/posts/upvoted`
  - `app.daily.dev/upvoted`
- `target`: `/upvoted`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/upvoted/7",
  "heat": 1,
  "location": "upvoted.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Most upvoted",
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
  "path": "/upvoted/:period?/:dateSort?",
  "radar": [
    {
      "source": [
        "daily.dev/posts/upvoted",
        "daily.dev/upvoted"
      ],
      "target": "/upvoted"
    },
    {
      "source": [
        "app.daily.dev/posts/upvoted",
        "app.daily.dev/upvoted"
      ],
      "target": "/upvoted"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Find the most upvoted developer posts on daily.dev. Explore top-rated content in coding, tutorials, and tech news from the largest developer network in the world. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "112689652596865024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.daily.dev/posts/upvoted",
      "title": "Most upvoted posts for developers | daily.dev",
      "type": "feed",
      "url": "rsshub://daily/upvoted/:period"
    }
  ],
  "url": "app.daily.dev/upvoted",
  "view": 0
}
```
