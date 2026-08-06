# NPM - Package

## Coverage
`index-only`

## Route
- Namespace: `npm`
- Namespace Name: `NPM`
- Route Path: `/npm/package/:name{(@[a-z0-9-~][a-z0-9-._~]*/)?[a-z0-9-~][a-z0-9-._~]*}`
- Route Name: `Package`
- Example: `/npm/package/rsshub`
- URL: `npmjs.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Fatpandac`
- Source Location: `package.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.npmjs.com/package/:name`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/npm/package/rsshub",
  "heat": 10,
  "location": "package.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Package",
  "path": "/package/:name{(@[a-z0-9-~][a-z0-9-._~]*/)?[a-z0-9-~][a-z0-9-._~]*}",
  "radar": [
    {
      "source": [
        "www.npmjs.com/package/:name"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "vite - npm - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "175925939002251264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npmjs.com/package/vite",
      "title": "vite - npm",
      "type": "feed",
      "url": "rsshub://npm/package/vite"
    },
    {
      "description": "@antfu/eslint-config - npm - Powered by RSSHub",
      "errorAt": "2026-08-05T04:56:05.232Z",
      "errorMessage": "Failed to fetch\n",
      "id": "175925709458059264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npmjs.com/package/@antfu/eslint-config",
      "title": "@antfu/eslint-config - npm",
      "type": "feed",
      "url": "rsshub://npm/package/@antfu/eslint-config"
    }
  ]
}
```
