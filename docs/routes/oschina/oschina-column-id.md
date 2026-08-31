# 开源中国 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `oschina`
- Namespace Name: `开源中国`
- Route Path: `/oschina/column/:id`
- Route Name: `专栏`
- Example: `/oschina/column/14`
- URL: `www.oschina.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [开源安全专栏](https://www.oschina.net/news/column?columnId=14)，网址为 `https://www.oschina.net/news/column?columnId=14`，请截取 `https://www.oschina.net/news/column?columnId=` 到末尾的部分 `14` 作为 `id` 参数填入，此时目标路由为 [`/oschina/column/14`](https://rsshub.app/oschina/column/14)。
:::

<details>
<summary>更多专栏</summary>

| 名称            | ID |
| --------------- | -- |
| 古典主义 Debian | 4  |
| 自由 & 开源     | 5  |
| 溯源            | 6  |
| 开源先懂协议    | 7  |
| 开源变局        | 8  |
| 创造者说        | 9  |
| 精英主义 BSD    | 10 |
| 苹果有开源      | 11 |
| 开源访谈        | 12 |
| 抱团找组织      | 13 |
| 开源安全        | 14 |
| OSPO            | 15 |
| 创业小辑        | 16 |
| 星推荐          | 17 |
| 单口开源        | 18 |
| 编辑部观察直播  | 19 |
| 开源商业化      | 20 |
| ChatGPT 专题    | 21 |
| 开源新思        | 24 |
| 开源日报        | 25 |
| 大模型思辨      | 26 |
| 家里有个程序员  | 27 |
| 开源漫谈        | 23 |

</details>

## Parameters
- `id`: 专栏 id，可在对应专栏页 URL 中找到


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
  - `www.oschina.net`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\n若订阅 [开源安全专栏](https://www.oschina.net/news/column?columnId=14)，网址为 `https://www.oschina.net/news/column?columnId=14`，请截取 `https://www.oschina.net/news/column?columnId=` 到末尾的部分 `14` 作为 `id` 参数填入，此时目标路由为 [`/oschina/column/14`](https://rsshub.app/oschina/column/14)。\n:::\n\n<details>\n<summary>更多专栏</summary>\n\n| 名称            | ID |\n| --------------- | -- |\n| 古典主义 Debian | 4  |\n| 自由 & 开源     | 5  |\n| 溯源            | 6  |\n| 开源先懂协议    | 7  |\n| 开源变局        | 8  |\n| 创造者说        | 9  |\n| 精英主义 BSD    | 10 |\n| 苹果有开源      | 11 |\n| 开源访谈        | 12 |\n| 抱团找组织      | 13 |\n| 开源安全        | 14 |\n| OSPO            | 15 |\n| 创业小辑        | 16 |\n| 星推荐          | 17 |\n| 单口开源        | 18 |\n| 编辑部观察直播  | 19 |\n| 开源商业化      | 20 |\n| ChatGPT 专题    | 21 |\n| 开源新思        | 24 |\n| 开源日报        | 25 |\n| 大模型思辨      | 26 |\n| 家里有个程序员  | 27 |\n| 开源漫谈        | 23 |\n\n</details>",
  "example": "/oschina/column/14",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "column.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id，可在对应专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "www.oschina.net"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'oschina-undefined' ] to not include 'oschina-undefined'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.oschina.net",
  "view": 0
}
```
