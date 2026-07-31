# 北京航空航天大学 - 图书馆 - 新书速递

## Coverage
`index-only`

## Route
- Namespace: `buaa`
- Namespace Name: `北京航空航天大学`
- Route Path: `/buaa/lib/space/:path{newbook.*}`
- Route Name: `图书馆 - 新书速递`
- Example: `/buaa/lib/space/newbook/`
- URL: `space.lib.buaa.edu.cn/mspace/newBook`
- Language: `_None_`
- Categories: `university`
- Maintainers: `OverflowCat`
- Source Location: `lib/space/newbook.tsx`
- Source Module: `_None_`

## Description
可通过参数进行筛选：`/buaa/lib/space/newbook/key1=value1&key2=value2...`

- `dcpCode`：学科分类代码
  - 例：
    - 工学：`08`
    - 工学 > 计算机 > 计算机科学与技术：`080901`
  - 默认值：`nolimit`
  - 注意事项：不可与 `clsNo` 同时使用。
- `clsNo`：中图分类号
  - 例：
    - 计算机科学：`TP3`
  - 默认值：无
  - 注意事项
    - 不可与 `dcpCode` 同时使用。
    - 此模式下获取不到上架日期。
- `libCode`：图书馆代码
  - 例：
    - 本馆：`00000`
  - 默认值：无
  - 注意事项：只有本馆一个可选值。
- `locaCode`：馆藏地代码
  - 例：
    - 五层西 - 中文新书借阅室 (A-Z 类)：`02503`
  - 默认值：无
  - 注意事项：必须与 `libCode` 同时使用。

示例：

- `buaa/lib/space/newbook` 为所有新书
- `buaa/lib/space/newbook/clsNo=U&libCode=00000&locaCode=60001` 为沙河教 2 图书馆所有中图分类号为 U（交通运输）的书籍

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "可通过参数进行筛选：`/buaa/lib/space/newbook/key1=value1&key2=value2...`\n\n- `dcpCode`：学科分类代码\n  - 例：\n    - 工学：`08`\n    - 工学 > 计算机 > 计算机科学与技术：`080901`\n  - 默认值：`nolimit`\n  - 注意事项：不可与 `clsNo` 同时使用。\n- `clsNo`：中图分类号\n  - 例：\n    - 计算机科学：`TP3`\n  - 默认值：无\n  - 注意事项\n    - 不可与 `dcpCode` 同时使用。\n    - 此模式下获取不到上架日期。\n- `libCode`：图书馆代码\n  - 例：\n    - 本馆：`00000`\n  - 默认值：无\n  - 注意事项：只有本馆一个可选值。\n- `locaCode`：馆藏地代码\n  - 例：\n    - 五层西 - 中文新书借阅室 (A-Z 类)：`02503`\n  - 默认值：无\n  - 注意事项：必须与 `libCode` 同时使用。\n\n示例：\n\n- `buaa/lib/space/newbook` 为所有新书\n- `buaa/lib/space/newbook/clsNo=U&libCode=00000&locaCode=60001` 为沙河教 2 图书馆所有中图分类号为 U（交通运输）的书籍",
  "example": "/buaa/lib/space/newbook/",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "lib/space/newbook.tsx",
  "maintainers": [
    "OverflowCat"
  ],
  "name": "图书馆 - 新书速递",
  "path": "/lib/space/:path{newbook.*}",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北京航空航天大学图书馆新书速递 - Powered by RSSHub",
      "errorAt": "2026-01-30T23:58:57.626Z",
      "errorMessage": "[GET] \"https://space.lib.buaa.edu.cn/meta-local/opac/new/100/bysubject?pageSize=100&page=1&dcpCode=nolimit\": <no response> fetch failed (unable to verify the first certificate; if the root CA is installed locally, try running Node.js with --use-system-ca)\n",
      "id": "62129102955320320",
      "image": "https://lib.buaa.edu.cn/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://space.lib.buaa.edu.cn/space/newBook",
      "title": "北航图书馆 - 新书速递",
      "type": "feed",
      "url": "rsshub://buaa/lib/space/newbook/"
    }
  ],
  "url": "space.lib.buaa.edu.cn/mspace/newBook"
}
```
