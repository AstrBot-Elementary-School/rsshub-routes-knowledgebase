# 哈尔滨工程大学 - 就业服务平台

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/job/calendar`
- Route Name: `就业服务平台`
- Example: `/hrbeu/job/calendar`
- URL: `job.hrbeu.edu.cn/*`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `job/calendar.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 热点新闻 |
| :------: | :------: |
|   tzgg   |   rdxw   |

#### 大型招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-da-xing-zhao-pin-hui}

#### 今日招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-jin-ri-zhao-pin-hui}

## Parameters
_None_


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
  - `job.hrbeu.edu.cn/*`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 热点新闻 |\n| :------: | :------: |\n|   tzgg   |   rdxw   |\n\n#### 大型招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-da-xing-zhao-pin-hui}\n\n#### 今日招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-jin-ri-zhao-pin-hui}",
  "example": "/hrbeu/job/calendar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "job/calendar.ts",
  "maintainers": [
    "Derekmini"
  ],
  "name": "就业服务平台",
  "parameters": {},
  "path": "/job/calendar",
  "radar": [
    {
      "source": [
        "job.hrbeu.edu.cn/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "job.hrbeu.edu.cn/*"
}
```
