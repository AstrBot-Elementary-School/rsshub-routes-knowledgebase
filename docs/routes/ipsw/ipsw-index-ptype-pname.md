# IPSW.me - Apple Firmware Update-IPSWs/OTAs version

## Coverage
`index-only`

## Route
- Namespace: `ipsw`
- Namespace Name: `IPSW.me`
- Route Path: `/ipsw/index/:ptype/:pname`
- Route Name: `Apple Firmware Update-IPSWs/OTAs version`
- Example: `/ipsw/index/ipsws/iPad8,11`
- URL: `ipsw.me`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Jeason0228`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `ptype`: Fill in ipsws or otas to get different versions of firmware
- `pname`: Product name, `http://rsshub.app/ipsw/index/ipsws/iPod`, if you fill in the iPad, follow the entire iPad series(ptype default to ipsws).`http://rsshub.app/ipsw/index/ipsws/iPhone11,8`, if you fill in the specific iPhone11,8, submit to the ipsws firmware information of this model


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
  "example": "/ipsw/index/ipsws/iPad8,11",
  "heat": 3,
  "location": "index.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "name": "Apple Firmware Update-IPSWs/OTAs version",
  "parameters": {
    "pname": "Product name, `http://rsshub.app/ipsw/index/ipsws/iPod`, if you fill in the iPad, follow the entire iPad series(ptype default to ipsws).`http://rsshub.app/ipsw/index/ipsws/iPhone11,8`, if you fill in the specific iPhone11,8, submit to the ipsws firmware information of this model",
    "ptype": "Fill in ipsws or otas to get different versions of firmware"
  },
  "path": "/index/:ptype/:pname",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "查看Apple-iPhone16,1- ipsws 固件-是否关闭验证 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52597163962893312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ipsw.me/iPhone16,1",
      "title": "iPhone16,1 - ipsws Released",
      "type": "feed",
      "url": "rsshub://ipsw/index/ipsws/iPhone16,1"
    },
    {
      "description": "查看Apple-iPhone15,2- ipsws 固件-是否关闭验证 - Powered by RSSHub",
      "errorAt": "2026-07-04T10:38:09.962Z",
      "errorMessage": "[GET] \"https://ipsw.me/window.location=%22/download/iPhone15,2/23E254%22\": 404 Not Found\n",
      "id": "156857634902037504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ipsw.me/iPhone15,2",
      "title": "iPhone15,2 - ipsws Released",
      "type": "feed",
      "url": "rsshub://ipsw/index/ipsws/iPhone15%2C2"
    }
  ]
}
```
