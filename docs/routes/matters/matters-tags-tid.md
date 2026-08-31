# Matters - Tags

## Coverage
`index-only`

## Route
- Namespace: `matters`
- Namespace Name: `Matters`
- Route Path: `/matters/tags/:tid`
- Route Name: `Tags`
- Example: `/matters/tags/972-哲學`
- URL: `matters.town`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Cerebrater`
- Source Location: `tags.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tid`: Tag id, can be found in the url of the tag page


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `matters.town/tags/:tid`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/matters/tags/972-哲學",
  "heat": 1,
  "location": "tags.ts",
  "maintainers": [
    "Cerebrater"
  ],
  "name": "Tags",
  "parameters": {
    "tid": "Tag id, can be found in the url of the tag page"
  },
  "path": "/tags/:tid",
  "radar": [
    {
      "source": [
        "matters.town/tags/:tid"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-15T04:33:59.169Z",
      "errorMessage": "Cannot read properties of undefined (reading 'ROOT_QUERY')\n",
      "id": "156923764513225731",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://matters/tags/VGFnOjk3Mg"
    }
  ]
}
```
