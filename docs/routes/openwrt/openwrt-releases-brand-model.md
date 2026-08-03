# OpenWrt - Releases

## Coverage
`index-only`

## Route
- Namespace: `openwrt`
- Namespace Name: `OpenWrt`
- Route Path: `/openwrt/releases/:brand/:model`
- Route Name: `Releases`
- Example: `/openwrt/releases/xiaomi/xiaomi_redmi_router_ac2100`
- URL: `openwrt.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `releases.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `brand`: Device Model, can be found in url of `Table of Hardware` -> `Device Page`
- `model`: Same as above


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `openwrt.org/toh/:band/:model`
- `target`: `/releases/:model`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/openwrt/releases/xiaomi/xiaomi_redmi_router_ac2100",
  "heat": 0,
  "location": "releases.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Releases",
  "parameters": {
    "brand": "Device Model, can be found in url of `Table of Hardware` -> `Device Page`",
    "model": "Same as above"
  },
  "path": "/releases/:brand/:model",
  "radar": [
    {
      "source": [
        "openwrt.org/toh/:band/:model"
      ],
      "target": "/releases/:model"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
