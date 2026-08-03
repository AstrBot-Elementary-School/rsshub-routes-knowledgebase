# 中华人民共和国外交部 - 外交动态

## Coverage
`index-only`

## Route
- Namespace: `gov/mfa`
- Namespace Name: `中华人民共和国外交部`
- Route Path: `/gov/mfa/wjdt/:category?`
- Route Name: `外交动态`
- Example: `/gov/mfa/wjdt/fyrbt`
- URL: `www.mfa.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nicolaszf, nczitzk`
- Source Location: `wjdt.ts`
- Source Module: `_None_`

## Description
| 分类       | category |
| ---------- | -------- |
| 领导人活动 | gjldrhd  |
| 外事日程   | wsrc     |
| 部领导活动 | wjbxw    |
| 业务动态   | sjxw     |
| 发言人表态 | fyrbt    |
| 吹风会     | cfhsl    |
| 大使任免   | dsrm     |
| 驻外报道   | zwbd     |
| 政策解读   | zcjd     |

## Parameters
- `category`: 分类，见下表，默认为领导人活动


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 分类       | category |\n| ---------- | -------- |\n| 领导人活动 | gjldrhd  |\n| 外事日程   | wsrc     |\n| 部领导活动 | wjbxw    |\n| 业务动态   | sjxw     |\n| 发言人表态 | fyrbt    |\n| 吹风会     | cfhsl    |\n| 大使任免   | dsrm     |\n| 驻外报道   | zwbd     |\n| 政策解读   | zcjd     |",
  "example": "/gov/mfa/wjdt/fyrbt",
  "heat": 78,
  "location": "wjdt.ts",
  "maintainers": [
    "nicolaszf",
    "nczitzk"
  ],
  "name": "外交动态",
  "parameters": {
    "category": "分类，见下表，默认为领导人活动"
  },
  "path": "/wjdt/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "领导人活动_中华人民共和国外交部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58007926096163886",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mfa.gov.cn/web/wjdt_674879/gjldrhd_674881",
      "title": "领导人活动_中华人民共和国外交部",
      "type": "feed",
      "url": "rsshub://gov/mfa/wjdt/gjldrhd"
    },
    {
      "description": "外事日程_中华人民共和国外交部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58007926096163890",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mfa.gov.cn/web/wjdt_674879/wsrc_674883",
      "title": "外事日程_中华人民共和国外交部",
      "type": "feed",
      "url": "rsshub://gov/mfa/wjdt/wsrc"
    }
  ]
}
```
