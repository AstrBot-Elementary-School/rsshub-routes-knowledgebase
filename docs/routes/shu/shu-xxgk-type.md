# 上海大学 - 信息公开网

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/shu/xxgk/:type?`
- Route Name: `信息公开网`
- Example: `/shu/xxgk/dwjlxm`
- URL: `xxgk.shu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `xxgk.ts`
- Source Module: `_None_`

## Description
| 对外交流项目 | 合作交流 |
| ------------ | -------- |
| dwjlxm       | hzjl     |

## Parameters
- `type`: 分类，默认为对外交流项目


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
  - `xxgk.shu.edu.cn/`
- `target`: `/xxgk`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 对外交流项目 | 合作交流 |\n| ------------ | -------- |\n| dwjlxm       | hzjl     |",
  "example": "/shu/xxgk/dwjlxm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "xxgk.ts",
  "maintainers": [
    "GhhG123"
  ],
  "name": "信息公开网",
  "parameters": {
    "type": "分类，默认为对外交流项目"
  },
  "path": "/xxgk/:type?",
  "radar": [
    {
      "source": [
        "xxgk.shu.edu.cn/"
      ],
      "target": "/xxgk"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海大学信息公开网-信息公开栏目-国际合作与交流-对外交流项目 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1238799867828895744",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://xxgk.shu.edu.cn/xxgklm/gjhzyjl1/dwjlxm.htm",
      "title": "上海大学信息公开网-信息公开栏目-国际合作与交流-对外交流项目",
      "type": "feed",
      "url": "rsshub://shu/xxgk/dwjlxm"
    }
  ],
  "url": "xxgk.shu.edu.cn/"
}
```
