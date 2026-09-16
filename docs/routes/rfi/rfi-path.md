# Radio France Internationale - Generic News

## Coverage
`index-only`

## Route
- Namespace: `rfi`
- Namespace Name: `Radio France Internationale`
- Route Path: `/rfi/:path{.+}?`
- Route Name: `Generic News`
- Example: `/rfi`
- URL: `rfi.fr`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip

- To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).
- To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).
- To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).

:::

::: warning
This route does not support podcasts, please use the Offical RSS feed instead.
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rfi.fr/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n\n- To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).\n- To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).\n- To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).\n\n:::\n\n::: warning\nThis route does not support podcasts, please use the Offical RSS feed instead.\n:::",
  "example": "/rfi",
  "heat": 73,
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Generic News",
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "rfi.fr/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "同步、随时跟踪法广政治、文化、体育新闻，了解法国、中国与世界各地大事 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58701529235465216",
      "image": "https://s.rfi.fr/media/display/020b8dae-e6c1-11ee-a196-005056bfb2b6/w:1280/p:16x9/img-default-RFI.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.rfi.fr/cn/",
      "title": "法广 - 时事与新闻直播 - RFI - 法国国际广播电台",
      "type": "feed",
      "url": "rsshub://rfi/cn"
    },
    {
      "description": "同步、随时跟踪中国时事：采访、报道、特别专题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75444883463138304",
      "image": "https://s.rfi.fr/media/display/020b8dae-e6c1-11ee-a196-005056bfb2b6/w:1280/p:16x9/img-default-RFI.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.rfi.fr/cn/%E4%B8%AD%E5%9B%BD/",
      "title": "中国时事 - 法广 - RFI",
      "type": "feed",
      "url": "rsshub://rfi/cn/%E4%B8%AD%E5%9B%BD"
    }
  ],
  "url": "rfi.fr"
}
```
