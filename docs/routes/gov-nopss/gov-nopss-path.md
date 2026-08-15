# 全国哲学社会科学工作办公室 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/nopss`
- Namespace Name: `全国哲学社会科学工作办公室`
- Route Path: `/gov/nopss/:path{.+}?`
- Route Name: `通用`
- Example: `/gov/nopss/GB/219469`
- URL: `www.nopss.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `http://www.nopss.gov.cn/` 后的字段。下面是一个例子。

若订阅 [年度项目、青年项目和西部项目](http://www.nopss.gov.cn/GB/219469/431027) 则将对应页面 URL <http://www.nopss.gov.cn/GB/219469/431027> 中 `http://www.nopss.gov.cn/` 后的字段 `GB/219469/431027` 作为路径填入。此时路由为 [`/gov/nopss/GB/219469/431027`](https://rsshub.app/gov/nopss/GB/219469/431027)

:::

## Parameters
- `path`: 路径，默认为通知公告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nopss.gov.cn/*path/index.html`
  - `www.nopss.gov.cn/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `http://www.nopss.gov.cn/` 后的字段。下面是一个例子。\n\n若订阅 [年度项目、青年项目和西部项目](http://www.nopss.gov.cn/GB/219469/431027) 则将对应页面 URL <http://www.nopss.gov.cn/GB/219469/431027> 中 `http://www.nopss.gov.cn/` 后的字段 `GB/219469/431027` 作为路径填入。此时路由为 [`/gov/nopss/GB/219469/431027`](https://rsshub.app/gov/nopss/GB/219469/431027)\n\n:::",
  "example": "/gov/nopss/GB/219469",
  "heat": 3,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，默认为通知公告"
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.nopss.gov.cn/*path/index.html",
        "www.nopss.gov.cn/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "重大项目- 全国哲学社会科学工作办公室 - Powered by RSSHub",
      "errorAt": "2026-06-15T11:29:45.771Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "68892056440478838",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nopss.gov.cn/GB/219469/431028",
      "title": "重大项目- 全国哲学社会科学工作办公室",
      "type": "feed",
      "url": "rsshub://gov/nopss/GB/219469/431028"
    },
    {
      "description": "年度项目- 全国哲学社会科学工作办公室 - Powered by RSSHub",
      "errorAt": "2026-06-15T12:07:28.389Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "68892056440478839",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nopss.gov.cn/GB/219469/431027",
      "title": "年度项目- 全国哲学社会科学工作办公室",
      "type": "feed",
      "url": "rsshub://gov/nopss/GB/219469/431027"
    }
  ]
}
```
