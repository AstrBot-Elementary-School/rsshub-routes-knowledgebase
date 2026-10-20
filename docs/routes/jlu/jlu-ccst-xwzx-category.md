# 吉林大学 - 计算机科学与技术学院 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `jlu`
- Namespace Name: `吉林大学`
- Route Path: `/jlu/ccst/xwzx/:category`
- Route Name: `计算机科学与技术学院 - 新闻中心`
- Example: `/jlu/ccst/xwzx/gsl`
- URL: `ccst.jlu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mayouxi`
- Source Location: `ccst/xwzx/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 栏目，可用 gsl（公示栏）、xstd（学生天地）、xytz（学院通知）、xyxw（学院新闻）、zsjy（招生就业）等对应列表文件名，不含 .htm。


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `ccst.jlu.edu.cn/xwzx/gsl.htm`
- `target`: `/ccst/xwzx/gsl`
### Rule 2
- `source`:
  - `ccst.jlu.edu.cn/xwzx/xstd.htm`
- `target`: `/ccst/xwzx/xstd`
### Rule 3
- `source`:
  - `ccst.jlu.edu.cn/xwzx/xytz.htm`
- `target`: `/ccst/xwzx/xytz`
### Rule 4
- `source`:
  - `ccst.jlu.edu.cn/xwzx/xyxw.htm`
- `target`: `/ccst/xwzx/xyxw`
### Rule 5
- `source`:
  - `ccst.jlu.edu.cn/xwzx/zsjy.htm`
- `target`: `/ccst/xwzx/zsjy`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/jlu/ccst/xwzx/gsl",
  "heat": 10,
  "location": "ccst/xwzx/index.ts",
  "maintainers": [
    "mayouxi"
  ],
  "name": "计算机科学与技术学院 - 新闻中心",
  "parameters": {
    "category": "栏目，可用 gsl（公示栏）、xstd（学生天地）、xytz（学院通知）、xyxw（学院新闻）、zsjy（招生就业）等对应列表文件名，不含 .htm。"
  },
  "path": "/ccst/xwzx/:category",
  "radar": [
    {
      "source": [
        "ccst.jlu.edu.cn/xwzx/gsl.htm"
      ],
      "target": "/ccst/xwzx/gsl"
    },
    {
      "source": [
        "ccst.jlu.edu.cn/xwzx/xstd.htm"
      ],
      "target": "/ccst/xwzx/xstd"
    },
    {
      "source": [
        "ccst.jlu.edu.cn/xwzx/xytz.htm"
      ],
      "target": "/ccst/xwzx/xytz"
    },
    {
      "source": [
        "ccst.jlu.edu.cn/xwzx/xyxw.htm"
      ],
      "target": "/ccst/xwzx/xyxw"
    },
    {
      "source": [
        "ccst.jlu.edu.cn/xwzx/zsjy.htm"
      ],
      "target": "/ccst/xwzx/zsjy"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "吉林大学计算机科学与技术学院 - 新闻中心新闻中心 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1217983246378074112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ccst.jlu.edu.cn/",
      "title": "吉林大学计算机科学与技术学院 - 新闻中心新闻中心",
      "type": "feed",
      "url": "rsshub://jlu/ccst/xwzx/..%2Frcpy%2Fbksjy%2Fjxtz"
    },
    {
      "description": "吉林大学计算机科学与技术学院 - 新闻中心新闻中心 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1217985769201598464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ccst.jlu.edu.cn/",
      "title": "吉林大学计算机科学与技术学院 - 新闻中心新闻中心",
      "type": "feed",
      "url": "rsshub://jlu/ccst/xwzx/..%2Fxwzx%2Fxytz"
    }
  ],
  "url": "ccst.jlu.edu.cn"
}
```
