# U.S. Food and Drug Administration - CDRHNew

## Coverage
`index-only`

## Route
- Namespace: `fda`
- Namespace Name: `U.S. Food and Drug Administration`
- Route Path: `/fda/cdrh/:titleOnly?`
- Route Name: `CDRHNew`
- Example: `/fda/cdrh`
- URL: `fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `cdrh.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `titleOnly`: Title only, empty by default which includes the full text, any other value shows the title only


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates`
  - `fda.gov/`
- `target`: `/cdrh/:titleOnly`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/fda/cdrh",
  "heat": 1,
  "location": "cdrh.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "CDRHNew",
  "parameters": {
    "titleOnly": "Title only, empty by default which includes the full text, any other value shows the title only"
  },
  "path": "/cdrh/:titleOnly?",
  "radar": [
    {
      "source": [
        "fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates",
        "fda.gov/"
      ],
      "target": "/cdrh/:titleOnly"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(6) ] to not include 'https://www.fda.gov/medical-devices/d…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates"
}
```
