# ResetEra - Thread latest posts (text & images)

## Coverage
`index-only`

## Route
- Namespace: `resetera`
- Namespace Name: `ResetEra`
- Route Path: `/resetera/thread/:id`
- Route Name: `Thread latest posts (text & images)`
- Example: `/resetera/thread/1076160`
- URL: `resetera.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `ZEN-GUO`
- Source Location: `thread.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Numeric thread ID at the end of the URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `resetera.com/threads/:slug.:id/`
- `target`: `/thread/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/resetera/thread/1076160",
  "heat": 2,
  "location": "thread.ts",
  "maintainers": [
    "ZEN-GUO"
  ],
  "name": "Thread latest posts (text & images)",
  "parameters": {
    "id": "Numeric thread ID at the end of the URL"
  },
  "path": "/thread/:id",
  "radar": [
    {
      "source": [
        "resetera.com/threads/:slug.:id/"
      ],
      "target": "/thread/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The 2025 Console & PC Virtual Photography Thread | IMG_01_12_2025.png - Powered by RSSHub",
      "errorAt": "2026-01-20T10:19:48.761Z",
      "errorMessage": "[GET] \"https://www.resetera.com/threads/1076160/\": 403 Forbidden\n",
      "id": "205712835507102720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.resetera.com/threads/1076160/page-38",
      "title": "The 2025 Console & PC Virtual Photography Thread | IMG_01_12_2025.png",
      "type": "feed",
      "url": "rsshub://resetera/thread/1076160"
    }
  ],
  "url": "resetera.com"
}
```
