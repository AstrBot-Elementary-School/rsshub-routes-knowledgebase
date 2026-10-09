# 国家卫星气象中心 - 卫星云图视频

## Coverage
`index-only`

## Route
- Namespace: `nsmc`
- Namespace Name: `国家卫星气象中心`
- Route Path: `/nsmc/cloud/:product?/:hours?`
- Route Name: `卫星云图视频`
- Example: `/nsmc/cloud/geos-col-irx/24`
- URL: `www.nsmc.org.cn`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `DIYgod`
- Source Location: `cloud.ts`
- Source Module: `_None_`

## Description
订阅卫星云图视频更新。发布时间来自官方 XML 云图列表；视频文件由源站持续更新，条目标识包含观测时间。

## Parameters
- `product`: 产品：geos-col-irx、geos-mos-irx、fy4b-gclr 或 fy4b-swci，默认 geos-col-irx
- `hours`: 视频覆盖的小时数：24、48、72 或 168，默认 24


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nsmc.org.cn/nsmc/cn/image/video.html`
  - `www.nsmc.org.cn/nsmc/cn/image/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "订阅卫星云图视频更新。发布时间来自官方 XML 云图列表；视频文件由源站持续更新，条目标识包含观测时间。",
  "example": "/nsmc/cloud/geos-col-irx/24",
  "heat": 0,
  "location": "cloud.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "卫星云图视频",
  "parameters": {
    "hours": "视频覆盖的小时数：24、48、72 或 168，默认 24",
    "product": "产品：geos-col-irx、geos-mos-irx、fy4b-gclr 或 fy4b-swci，默认 geos-col-irx"
  },
  "path": "/cloud/:product?/:hours?",
  "radar": [
    {
      "source": [
        "www.nsmc.org.cn/nsmc/cn/image/video.html",
        "www.nsmc.org.cn/nsmc/cn/image/"
      ]
    }
  ],
  "topFeeds": []
}
```
