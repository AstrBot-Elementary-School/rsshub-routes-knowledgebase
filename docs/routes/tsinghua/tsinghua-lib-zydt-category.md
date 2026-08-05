# 清华大学 - 图书馆资源动态

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/lib/zydt/:category?`
- Route Name: `图书馆资源动态`
- Example: `/tsinghua/lib/zydt`
- URL: `lib.tsinghua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `lib/zydt.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [清华大学图书馆已购资源动态](https://lib.tsinghua.edu.cn/zydt/yg.htm)，网址为 `https://lib.tsinghua.edu.cn/zydt/yg.htm`。截取 `https://lib.tsinghua.edu.cn/zydt` 到末尾 `.htm` 的部分 `yg` 作为参数填入，此时路由为 [`/tsinghua/lib/zydt/yg`](https://rsshub.app/tsinghua/lib/zydt/yg)。
:::

| 已购 | 试用 |
| ---- | ---- |
| yg   | sy   |

## Parameters
- `category`: 分类，默认为空，即全部，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lib.tsinghua.edu.cn/zydt/:category?`
### Rule 2
- `title`: `图书馆资源动态`
- `source`:
  - `lib.tsinghua.edu.cn/zydt`
- `target`: `/lib/zydt`
### Rule 3
- `title`: `图书馆已购资源动态`
- `source`:
  - `lib.tsinghua.edu.cn/zydt/yg`
- `target`: `/lib/zydt/yg`
### Rule 4
- `title`: `图书馆试用资源动态`
- `source`:
  - `lib.tsinghua.edu.cn/zydt/sy`
- `target`: `/lib/zydt/sy`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n若订阅 [清华大学图书馆已购资源动态](https://lib.tsinghua.edu.cn/zydt/yg.htm)，网址为 `https://lib.tsinghua.edu.cn/zydt/yg.htm`。截取 `https://lib.tsinghua.edu.cn/zydt` 到末尾 `.htm` 的部分 `yg` 作为参数填入，此时路由为 [`/tsinghua/lib/zydt/yg`](https://rsshub.app/tsinghua/lib/zydt/yg)。\n:::\n\n| 已购 | 试用 |\n| ---- | ---- |\n| yg   | sy   |",
  "example": "/tsinghua/lib/zydt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "lib/zydt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "图书馆资源动态",
  "parameters": {
    "category": "分类，默认为空，即全部，可在对应分类页 URL 中找到"
  },
  "path": "/lib/zydt/:category?",
  "radar": [
    {
      "source": [
        "lib.tsinghua.edu.cn/zydt/:category?"
      ]
    },
    {
      "source": [
        "lib.tsinghua.edu.cn/zydt"
      ],
      "target": "/lib/zydt",
      "title": "图书馆资源动态"
    },
    {
      "source": [
        "lib.tsinghua.edu.cn/zydt/yg"
      ],
      "target": "/lib/zydt/yg",
      "title": "图书馆已购资源动态"
    },
    {
      "source": [
        "lib.tsinghua.edu.cn/zydt/sy"
      ],
      "target": "/lib/zydt/sy",
      "title": "图书馆试用资源动态"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "资源动态-清华大学图书馆 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55800849364779008",
      "image": "https://lib.tsinghua.edu.cn/undefined",
      "ownerUserId": null,
      "siteUrl": "https://lib.tsinghua.edu.cn/zydt.htm",
      "title": "资源动态-清华大学图书馆",
      "type": "feed",
      "url": "rsshub://tsinghua/lib/zydt"
    }
  ],
  "url": "lib.tsinghua.edu.cn"
}
```
