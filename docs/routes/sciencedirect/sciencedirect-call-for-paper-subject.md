# ScienceDirect - Call for Papers

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/sciencedirect/call-for-paper/:subject`
- Route Name: `Call for Papers`
- Example: `/sciencedirect/call-for-paper/education`
- URL: `sciencedirect.com/browse/calls-for-papers`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `etShaw-zh`
- Source Location: `call-for-paper.tsx`
- Source Module: `_None_`

## Description
`sciencedirect.com/browse/calls-for-papers?subject=education` -> `/sciencedirect/call-for-paper/education`

## Parameters
- `subject`: 学科分类，例如“education”


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `sciencedirect.com`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "`sciencedirect.com/browse/calls-for-papers?subject=education` -> `/sciencedirect/call-for-paper/education`",
  "example": "/sciencedirect/call-for-paper/education",
  "heat": 37,
  "location": "call-for-paper.tsx",
  "maintainers": [
    "etShaw-zh"
  ],
  "name": "Call for Papers",
  "parameters": {
    "subject": "学科分类，例如“education”"
  },
  "path": "/call-for-paper/:subject",
  "radar": [
    {
      "source": [
        "sciencedirect.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Calls for Papers on ScienceDirect for subject: computer-science - Powered by RSSHub",
      "errorAt": "2025-11-06T10:27:52.276Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/browse/calls-for-papers?subject=computer-science\": 403 Forbidden\n",
      "id": "137424111559118848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sciencedirect.com/browse/calls-for-papers?subject=computer-science",
      "title": "ScienceDirect Calls for Papers - computer-science",
      "type": "feed",
      "url": "rsshub://sciencedirect/call-for-paper/computer-science"
    },
    {
      "description": "Calls for Papers on ScienceDirect for subject: education - Powered by RSSHub",
      "errorAt": "2025-11-06T10:11:13.592Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/browse/calls-for-papers?subject=education\": 403 Forbidden\n",
      "id": "150383744963434496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sciencedirect.com/browse/calls-for-papers?subject=education",
      "title": "ScienceDirect Calls for Papers - education",
      "type": "feed",
      "url": "rsshub://sciencedirect/call-for-paper/education"
    }
  ],
  "url": "sciencedirect.com/browse/calls-for-papers"
}
```
