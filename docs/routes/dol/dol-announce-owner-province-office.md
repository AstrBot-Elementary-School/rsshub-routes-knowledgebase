# Thailand Department of Lands - e-LandsAnnouncement

## Coverage
`index-only`

## Route
- Namespace: `dol`
- Namespace Name: `Thailand Department of Lands`
- Route Path: `/dol/announce/:owner?/:province?/:office?`
- Route Name: `e-LandsAnnouncement`
- Example: `/dol/announce`
- URL: `announce.dol.go.th`
- Language: `_None_`
- Categories: `government`
- Maintainers: `itpcc`
- Source Location: `announce.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `owner`: Requester/former land owner. Use _ to omit it when selecting a province or office.
- `province`: Province which the land belongs to. Use _ to omit it when selecting an office.
- `office`: DOL office name which the land belongs to (สำนักงานที่ดิน(กรุงเทพมหานคร|จังหวัด*) [สาขา*])


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/dol/announce",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "announce.ts",
  "maintainers": [
    "itpcc"
  ],
  "name": "e-LandsAnnouncement",
  "parameters": {
    "office": "DOL office name which the land belongs to (สำนักงานที่ดิน(กรุงเทพมหานคร|จังหวัด*) [สาขา*])",
    "owner": "Requester/former land owner. Use _ to omit it when selecting a province or office.",
    "province": "Province which the land belongs to. Use _ to omit it when selecting an office."
  },
  "path": "/announce/:owner?/:province?/:office?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
