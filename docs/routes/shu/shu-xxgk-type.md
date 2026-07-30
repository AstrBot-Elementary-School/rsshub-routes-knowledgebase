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
  "heat": 0,
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
  "topFeeds": [],
  "url": "xxgk.shu.edu.cn/"
}
```
