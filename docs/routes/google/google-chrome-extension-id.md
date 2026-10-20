# Google - Extension Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/chrome/extension/:id`
- Route Name: `Extension Update`
- Example: `/google/chrome/extension/kefjpfngnndepjbopdmoebkipbgkggaa`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `extension.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Extension id, can be found in extension url


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `chromewebstore.google.com/detail/:name/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/google/chrome/extension/kefjpfngnndepjbopdmoebkipbgkggaa",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "extension.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Extension Update",
  "parameters": {
    "id": "Extension id, can be found in extension url"
  },
  "path": "/chrome/extension/:id",
  "radar": [
    {
      "source": [
        "chromewebstore.google.com/detail/:name/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "UnTrap for YouTube - Google Chrome Extension - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "172551793166268429",
      "image": "https://lh3.googleusercontent.com/VMaJea6Qe9PoHsLF11LkF4iajuCiJu995dVI_ChRWgq-Co-mB241L_bVOaFRofDdJCODW9svxR74Kl3E5pAFBWjC=s60",
      "ownerUserId": null,
      "siteUrl": "https://chrome.google.com/webstore/detail/enboaomnljigfhfjfoalacienlhjlfil",
      "title": "UnTrap for YouTube - Google Chrome Extension",
      "type": "feed",
      "url": "rsshub://google/chrome/extension/enboaomnljigfhfjfoalacienlhjlfil"
    },
    {
      "description": "RSSHub Radar - Google Chrome Extension - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126248073223252992",
      "image": "https://lh3.googleusercontent.com/kub2caeSUBk0Al6xAj5zYgTYov49cU1I2FuwkoV031BKWD3g9Ynrj4ZofChlpf3Og4mCL3C8G3ahcdqq23mZMqbB3Q=s60",
      "ownerUserId": null,
      "siteUrl": "https://chrome.google.com/webstore/detail/kefjpfngnndepjbopdmoebkipbgkggaa",
      "title": "RSSHub Radar - Google Chrome Extension",
      "type": "feed",
      "url": "rsshub://google/chrome/extension/kefjpfngnndepjbopdmoebkipbgkggaa"
    }
  ]
}
```
