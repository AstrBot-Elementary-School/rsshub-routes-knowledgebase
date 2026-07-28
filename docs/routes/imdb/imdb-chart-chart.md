# IMDb - Charts

## Coverage
`index-only`

## Route
- Namespace: `imdb`
- Namespace Name: `IMDb`
- Route Path: `/imdb/chart/:chart?`
- Route Name: `Charts`
- Example: `/imdb/chart`
- URL: `www.imdb.com/chart/top/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `TonyRL`
- Source Location: `chart.tsx`
- Source Module: `_None_`

## Description
| Top 250 Movies | Most Popular Movies | Top 250 TV Shows | Most Popular TV Shows |
| -------------- | ------------------- | ---------------- | --------------------- |
| top            | moviemeter          | toptv            | tvmeter               |

## Parameters
- `chart`: {"default": "top", "description": "The chart to display, `top` by default", "options": [{"label": "Top 250 Movies", "value": "top"}, {"label": "Most Popular Movies", "value": "moviemeter"}, {"label": "Top 250 TV Shows", "value": "toptv"}, {"label": "Most Popular TV Shows", "value": "tvmeter"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.imdb.com/chart/:chart/`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "description": "| Top 250 Movies | Most Popular Movies | Top 250 TV Shows | Most Popular TV Shows |\n| -------------- | ------------------- | ---------------- | --------------------- |\n| top            | moviemeter          | toptv            | tvmeter               |",
  "example": "/imdb/chart",
  "heat": 1421,
  "location": "chart.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Charts",
  "parameters": {
    "chart": {
      "default": "top",
      "description": "The chart to display, `top` by default",
      "options": [
        {
          "label": "Top 250 Movies",
          "value": "top"
        },
        {
          "label": "Most Popular Movies",
          "value": "moviemeter"
        },
        {
          "label": "Top 250 TV Shows",
          "value": "toptv"
        },
        {
          "label": "Most Popular TV Shows",
          "value": "tvmeter"
        }
      ]
    }
  },
  "path": "/chart/:chart?",
  "radar": [
    {
      "source": [
        "www.imdb.com/chart/:chart/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "As rated by regular IMDb voters. - Powered by RSSHub",
      "errorAt": "2026-03-19T21:35:56.023Z",
      "errorMessage": "Unexpected end of JSON input\n502 \nUnexpected end of JSON input\nUnexpected end of JSON input\nUnexpected end of JSON input\n",
      "id": "69670759328198656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.imdb.com/chart/top/",
      "title": "IMDb Top 250 movies",
      "type": "feed",
      "url": "rsshub://imdb/chart/top"
    },
    {
      "description": "As determined by IMDb users - Powered by RSSHub",
      "errorAt": "2026-03-19T23:41:25.270Z",
      "errorMessage": "Unexpected end of JSON input\n502 \nUnexpected end of JSON input\nUnexpected end of JSON input\n",
      "id": "64117673690336339",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.imdb.com/chart/moviemeter/",
      "title": "Most popular movies",
      "type": "feed",
      "url": "rsshub://imdb/chart/moviemeter"
    }
  ],
  "url": "www.imdb.com/chart/top/",
  "view": 5
}
```
