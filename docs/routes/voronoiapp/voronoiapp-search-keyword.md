# Voronoi - Search Keyword Posts

## Coverage
`index-only`

## Route
- Namespace: `voronoiapp`
- Namespace Name: `Voronoi`
- Route Path: `/voronoiapp/search/:keyword`
- Route Name: `Search Keyword Posts`
- Example: `/voronoiapp/search/china`
- URL: `voronoiapp.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `Cesaryuan`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: The keyword to search for


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.voronoiapp.com/explore`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/voronoiapp/search/china",
  "heat": 5,
  "location": "search.ts",
  "maintainers": [
    "Cesaryuan"
  ],
  "name": "Search Keyword Posts",
  "parameters": {
    "keyword": "The keyword to search for"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "www.voronoiapp.com/explore"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Voronoi Posts for \"china\" - Powered by RSSHub",
      "errorAt": "2024-10-25T10:39:27.750Z",
      "errorMessage": "[GET] \"https://9oyi4rk426.execute-api.ca-central-1.amazonaws.com/production/post?limit=20&offset=0&search=china\": <no response> fetch failed (getaddrinfo ENOTFOUND 9oyi4rk426.execute-api.ca-central-1.amazonaws.com)\n",
      "id": "70012973610700800",
      "image": "https://about.voronoiapp.com/wp-content/uploads/2023/07/voronoi-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.voronoiapp.com/explore?search=china",
      "title": "Voronoi Posts for \"china\"",
      "type": "feed",
      "url": "rsshub://voronoiapp/search/china"
    }
  ],
  "url": "voronoiapp.com",
  "view": 2
}
```
