# 上海大学 - 教务部

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/shu/jwb/:type?`
- Route Name: `教务部`
- Example: `/shu/jwb/notice`
- URL: `www.shu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `tuxinghuan, GhhG123`
- Source Location: `jwb.ts`
- Source Module: `_None_`

## Description
| 通知通告 | 新闻 | 政策文件 (bug) |
| -------- | ---- | -------------- |
| notice   | news | policy         |

## Parameters
- `type`: 消息类型,默认为`notice`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.shu.edu.cn/index`
- `target`: `/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知通告 | 新闻 | 政策文件 (bug) |\n| -------- | ---- | -------------- |\n| notice   | news | policy         |",
  "example": "/shu/jwb/notice",
  "heat": 3,
  "location": "jwb.ts",
  "maintainers": [
    "tuxinghuan",
    "GhhG123"
  ],
  "name": "教务部",
  "parameters": {
    "type": "消息类型,默认为`notice`"
  },
  "path": "/jwb/:type?",
  "radar": [
    {
      "source": [
        "www.shu.edu.cn/index"
      ],
      "target": "/:type?"
    }
  ],
  "topFeeds": [
    {
      "description": "通知公告-上海大学本科生院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84818651163788288",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://jwb.shu.edu.cn/index/tzgg.htm",
      "title": "通知公告-上海大学本科生院",
      "type": "feed",
      "url": "rsshub://shu/jwb/tzgg"
    },
    {
      "description": "新闻-上海大学教务部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84819628572333056",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://jwb.shu.edu.cn/index/xw.htm",
      "title": "新闻-上海大学教务部",
      "type": "feed",
      "url": "rsshub://shu/jwb/xw"
    }
  ]
}
```
