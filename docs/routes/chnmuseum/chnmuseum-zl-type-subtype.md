# National Museum Of China - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `chnmuseum`
- Namespace Name: `National Museum Of China`
- Route Path: `/chnmuseum/zl/:type?/:subType?`
- Route Name: `Exhibitions`
- Example: `/chnmuseum/zl/lszl/zdzt`
- URL: `www.chnmuseum.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `zl.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: zhanlanyugao（正在展出）、jbcl（基本陈列）、ztcl（专题展览）、lszl（临时展览）、gjzl（国家展览）、gbxz（国博巡展）. Default: All exhibitions.
- `subType`: subtype only works under type lszl（临时展览）, supported values: zdzt（重大主题）、lswh（历史文化）、yscx（艺术创新）、gjjl（国际交流）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chnmuseum.cn/zl/`
- `target`: `/zl`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/chnmuseum/zl/lszl/zdzt",
  "heat": 1,
  "location": "zl.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibitions",
  "parameters": {
    "subType": "subtype only works under type lszl（临时展览）, supported values: zdzt（重大主题）、lswh（历史文化）、yscx（艺术创新）、gjjl（国际交流）",
    "type": "Exhibition type, supported values: zhanlanyugao（正在展出）、jbcl（基本陈列）、ztcl（专题展览）、lszl（临时展览）、gjzl（国家展览）、gbxz（国博巡展）. Default: All exhibitions."
  },
  "path": "/zl/:type?/:subType?",
  "radar": [
    {
      "source": [
        "www.chnmuseum.cn/zl/"
      ],
      "target": "/zl"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国国家博物馆 - 临时展览 - 历史文化 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1268365424953524225",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chnmuseum.cn/zl/lszl/lswh/",
      "title": "中国国家博物馆 - 临时展览 - 历史文化",
      "type": "feed",
      "url": "rsshub://chnmuseum/zl/lszl/lswh"
    }
  ]
}
```
