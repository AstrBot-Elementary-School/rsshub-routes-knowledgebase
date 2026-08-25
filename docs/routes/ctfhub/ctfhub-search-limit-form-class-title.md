# CTFHub - 查询国内外 CTF 赛事信息

## Coverage
`index-only`

## Route
- Namespace: `ctfhub`
- Namespace Name: `CTFHub`
- Route Path: `/ctfhub/search/:limit?/:form?/:class?/:title?`
- Route Name: `查询国内外 CTF 赛事信息`
- Example: `/ctfhub/search`
- URL: `www.ctfhub.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `frankli0324`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
| `:class` | 类型                               |
| :------: | ---------------------------------- |
|     0    | Jeopardy \[解题]                   |
|     1    | Attack with Defense \[AwD 攻防]    |
|     2    | Robo Hacking Game \[RHG AI 自动化] |
|     3    | Real World \[RW 真实世界]          |
|     4    | King of The Hill \[KoH 抢占山头]   |
|     5    | Mix \[混合]                        |

> class 以 <https://api.ctfhub.com/User_API/Event/getType> 的返回结果为准

| `:form` | 形式   |
| :-----: | ------ |
|    0    | 线上赛 |
|    1    | 线下赛 |

## Parameters
- `limit`: 一个整数，筛选最新的 limit 场比赛，默认为 10
- `form`: 比赛形式
- `class`: 比赛类型
- `title`: 通过 CTF 赛事名称过滤


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| `:class` | 类型                               |\n| :------: | ---------------------------------- |\n|     0    | Jeopardy \\[解题]                   |\n|     1    | Attack with Defense \\[AwD 攻防]    |\n|     2    | Robo Hacking Game \\[RHG AI 自动化] |\n|     3    | Real World \\[RW 真实世界]          |\n|     4    | King of The Hill \\[KoH 抢占山头]   |\n|     5    | Mix \\[混合]                        |\n\n> class 以 <https://api.ctfhub.com/User_API/Event/getType> 的返回结果为准\n\n| `:form` | 形式   |\n| :-----: | ------ |\n|    0    | 线上赛 |\n|    1    | 线下赛 |",
  "example": "/ctfhub/search",
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "frankli0324"
  ],
  "name": "查询国内外 CTF 赛事信息",
  "parameters": {
    "class": "比赛类型",
    "form": "比赛形式",
    "limit": "一个整数，筛选最新的 limit 场比赛，默认为 10",
    "title": "通过 CTF 赛事名称过滤"
  },
  "path": "/search/:limit?/:form?/:class?/:title?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected -7166034692 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
