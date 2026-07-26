# Daily.dev - Popular

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/popular/:dateSort?`
- Route Name: `Popular`
- Example: `/daily/popular`
- URL: `app.daily.dev/popular`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `dateSort`: {"default": "true", "description": "Sort posts by publication date instead of popularity", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/popular`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/popular",
  "heat": 10,
  "location": "popular.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Popular",
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
    }
  },
  "path": "/popular/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/popular"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "daily.dev is the easiest way to stay updated on the latest programming news. Get the best content from the top tech publications on any topic you want. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98839639566962688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.daily.dev/posts",
      "title": "Popular posts on daily.dev",
      "type": "feed",
      "url": "rsshub://daily/popular"
    }
  ],
  "url": "app.daily.dev/popular",
  "view": 0
}
```
