# Voronoi - Author Posts

## Coverage
`index-only`

## Route
- Namespace: `voronoiapp`
- Namespace Name: `Voronoi`
- Route Path: `/voronoiapp/author/:username`
- Route Name: `Author Posts`
- Example: `/voronoiapp/author/visualcapitalist`
- URL: `voronoiapp.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `Cesaryuan`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: The username of the author


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.voronoiapp.com/author/:username`
- `target`: `/author/:username`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/voronoiapp/author/visualcapitalist",
  "heat": 0,
  "location": "author.ts",
  "maintainers": [
    "Cesaryuan"
  ],
  "name": "Author Posts",
  "parameters": {
    "username": "The username of the author"
  },
  "path": "/author/:username",
  "radar": [
    {
      "source": [
        "www.voronoiapp.com/author/:username"
      ],
      "target": "/author/:username"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "voronoiapp.com",
  "view": 2
}
```
