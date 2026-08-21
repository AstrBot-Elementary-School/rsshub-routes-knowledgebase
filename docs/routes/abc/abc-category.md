# ABC News (Australian Broadcasting Corporation) - Channel & Topic

## Coverage
`index-only`

## Route
- Namespace: `abc`
- Namespace Name: `ABC News (Australian Broadcasting Corporation)`
- Route Path: `/abc/:category{.+}?`
- Route Name: `Channel & Topic`
- Example: `/abc/wa`
- URL: `abc.net.au`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
All Topics in [Topic Library](https://abc.net.au/news/topics) are supported, you can fill in the field after `topic` in its URL, or fill in the `documentId`.

For example, the URL for [Computer Science](https://www.abc.net.au/news/topic/computer-science) is `https://www.abc.net.au/news/topic/computer-science`, the `category` is `news/topic/computer-science`, and the `documentId` of the Topic is `2302`, so the route is [/abc/news/topic/computer-science](https://rsshub.app/abc/news/topic/computer-science) and [/abc/2302](https://rsshub.app/abc/2302).

The supported channels are all listed in the table below. For other channels, please find the `documentId` in the source code of the channel page and fill it in as above.
:::

## Parameters
- `category`: Category, can be found in the URL, can also be filled in with the `documentId` in the source code of the page, `news/justin` as **Just In** by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `abc.net.au/:category*`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\nAll Topics in [Topic Library](https://abc.net.au/news/topics) are supported, you can fill in the field after `topic` in its URL, or fill in the `documentId`.\n\nFor example, the URL for [Computer Science](https://www.abc.net.au/news/topic/computer-science) is `https://www.abc.net.au/news/topic/computer-science`, the `category` is `news/topic/computer-science`, and the `documentId` of the Topic is `2302`, so the route is [/abc/news/topic/computer-science](https://rsshub.app/abc/news/topic/computer-science) and [/abc/2302](https://rsshub.app/abc/2302).\n\nThe supported channels are all listed in the table below. For other channels, please find the `documentId` in the source code of the channel page and fill it in as above.\n:::",
  "example": "/abc/wa",
  "heat": 102,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Channel & Topic",
  "parameters": {
    "category": "Category, can be found in the URL, can also be filled in with the `documentId` in the source code of the page, `news/justin` as **Just In** by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "abc.net.au/:category*"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Live breaking news stories from across Australia & around the world. In-depth coverage from Australia's most trusted source. Includes business, sport, weather. - Powered by RSSHub",
      "errorAt": "2025-04-28T19:57:53.044Z",
      "errorMessage": "[GET] \"https://www.abc.net.au/news/feed/news/justin/rss.xml\": <no response> fetch failed\n[GET] \"https://www.abc.net.au/news/feed/news/justin/rss.xml\": 404 Not Found\n",
      "id": "82619977766945792",
      "image": "https://live-production.wcms.abc-cdn.net.au/7ee6f190de6d7dbb04203e514bfae9ec",
      "ownerUserId": null,
      "siteUrl": "https://www.abc.net.au/news/justin",
      "title": "Just In - ABC News",
      "type": "feed",
      "url": "rsshub://abc"
    },
    {
      "description": "澳大利亚广播公司ABC独立于政府、政治团体，商业或其他行业机构，不涉及任何利益关系，编辑自主，提供客观和公正的新闻报道，是澳大利亚全国公共广播机构。ABC中文遵循ABC编辑方针，以澳大利亚视角，报道国内外重大新闻事件、深度分析时事要闻、多方展现观点碰撞。 - Powered by RSSHub",
      "errorAt": "2025-04-28T18:36:45.726Z",
      "errorMessage": "[GET] \"https://www.abc.net.au/news/feed/chinese/rss.xml\": 404 Not Found\n",
      "id": "59961396218494976",
      "image": "https://live-production.wcms.abc-cdn.net.au/7ee6f190de6d7dbb04203e514bfae9ec",
      "ownerUserId": null,
      "siteUrl": "https://www.abc.net.au/chinese",
      "title": "ABC中文 - ABC News",
      "type": "feed",
      "url": "rsshub://abc/chinese"
    }
  ]
}
```
