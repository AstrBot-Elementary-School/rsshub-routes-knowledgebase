# Bing - 每日壁纸

## Coverage
`index-only`

## Route
- Namespace: `bing`
- Namespace Name: `Bing`
- Route Path: `/bing/:routeParams?`
- Route Name: `每日壁纸`
- Example: `/bing/type=UHD&story=1&lang=zh-CN`
- URL: `www.bing.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `FHYunCai, LLLLLFish`
- Source Location: `daily-wallpaper.ts`
- Source Module: `_None_`

## Description
| 参数  | 含义                                | 接受的值                                                   | 默认值    | 备注                                                                              |
| ----- | ----------------------------------- | ---------------------------------------------------------- | --------- | --------------------------------------------------------------------------------- |
| type  | 输出壁纸的像素类型                  | UHD/1920x1080/1920x1200/768x1366/1080x1920/1080x1920\_logo | 1920x1080 | 1920x1200 与 1080x1920\_logo 带有水印，输入的值不在接受范围内都会输出成 1920x1080 |
| story | 是否输出壁纸的故事                  | 1/0                                                        | 0         | 输入的值不为 1 都不会输出故事                                                     |
| lang  | 输出壁纸图文的地区 (中文或者是英文) | zh/en                                                      | zh        | zh/en 输出的壁纸图文不一定是一样的；如果 en 不生效，试着部署到其他地方            |

## Parameters
- `routeParams`: 额外参数type,story和lang:请参阅以下说明和表格


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bing.com/`
- `target`: ``
### Rule 2
- `source`:
  - `cn.bing.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 参数  | 含义                                | 接受的值                                                   | 默认值    | 备注                                                                              |\n| ----- | ----------------------------------- | ---------------------------------------------------------- | --------- | --------------------------------------------------------------------------------- |\n| type  | 输出壁纸的像素类型                  | UHD/1920x1080/1920x1200/768x1366/1080x1920/1080x1920\\_logo | 1920x1080 | 1920x1200 与 1080x1920\\_logo 带有水印，输入的值不在接受范围内都会输出成 1920x1080 |\n| story | 是否输出壁纸的故事                  | 1/0                                                        | 0         | 输入的值不为 1 都不会输出故事                                                     |\n| lang  | 输出壁纸图文的地区 (中文或者是英文) | zh/en                                                      | zh        | zh/en 输出的壁纸图文不一定是一样的；如果 en 不生效，试着部署到其他地方            |",
  "example": "/bing/type=UHD&story=1&lang=zh-CN",
  "heat": 1124,
  "location": "daily-wallpaper.ts",
  "maintainers": [
    "FHYunCai",
    "LLLLLFish"
  ],
  "name": "每日壁纸",
  "parameters": {
    "routeParams": "额外参数type,story和lang:请参阅以下说明和表格"
  },
  "path": "/:routeParams?",
  "radar": [
    {
      "source": [
        "www.bing.com/"
      ],
      "target": ""
    },
    {
      "source": [
        "cn.bing.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Bing每日壁纸 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42109271607731200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.bing.com/",
      "title": "Bing每日壁纸",
      "type": "feed",
      "url": "rsshub://bing"
    },
    {
      "description": "Bing每日壁纸 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42501169300235264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.bing.com/",
      "title": "Bing每日壁纸",
      "type": "feed",
      "url": "rsshub://bing/type=UHD&story=1&lang=zh-CN"
    }
  ],
  "url": "www.bing.com/"
}
```
