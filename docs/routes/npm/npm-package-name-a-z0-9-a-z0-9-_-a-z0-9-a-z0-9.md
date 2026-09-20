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
      "description": "@vue/language-server - npm - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "175923362558744576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npmjs.com/package/@vue/language-server",
      "title": "@vue/language-server - npm",
      "type": "feed",
      "url": "rsshub://npm/package/@vue/language-server"
    },
    {
      "description": "nocodb - npm - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197390555900909568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npmjs.com/package/nocodb",
      "title": "nocodb - npm",
      "type": "feed",
      "url": "rsshub://npm/package/nocodb"
    }
  ]
}
```
