# Mozilla - New Release

## Coverage
`index-only`

## Route
- Namespace: `firefox`
- Namespace Name: `Mozilla`
- Route Path: `/firefox/release/:platform?`
- Route Name: `New Release`
- Example: `/firefox/release/desktop`
- URL: `monitor.firefox.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `fengkx`
- Source Location: `release.ts`
- Source Module: `_None_`

## Description
| Desktop | Android | Beta | Nightly | iOS |
| ------- | ------- | ---- | ------- | --- |
| desktop | android | beta | nightly | ios |

## Parameters
- `platform`: the platform


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| Desktop | Android | Beta | Nightly | iOS |\n| ------- | ------- | ---- | ------- | --- |\n| desktop | android | beta | nightly | ios |",
  "example": "/firefox/release/desktop",
  "heat": 3,
  "location": "release.ts",
  "maintainers": [
    "fengkx"
  ],
  "name": "New Release",
  "parameters": {
    "platform": "the platform"
  },
  "path": "/release/:platform?",
  "topFeeds": [
    {
      "description": "Firefox beta release notes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72287537564742660",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mozilla.org/en-US/firefox/beta/notes",
      "title": "Firefox beta release notes",
      "type": "feed",
      "url": "rsshub://firefox/release/beta"
    },
    {
      "description": "Firefox desktop release notes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "134365629543286784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mozilla.org/en-US/firefox/releasenotes",
      "title": "Firefox desktop release notes",
      "type": "feed",
      "url": "rsshub://firefox/release"
    }
  ]
}
```
