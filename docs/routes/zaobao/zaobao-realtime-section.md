# 联合早报 - 即时新闻

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/zaobao/realtime/:section?`
- Route Name: `即时新闻`
- Example: `/zaobao/realtime/china`
- URL: `www.zaobao.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `shunf4`
- Source Location: `realtime.ts`
- Source Module: `_None_`

## Description
| 中国  | 新加坡    | 国际  | 财经     |
| ----- | --------- | ----- | -------- |
| china | singapore | world | zfinance |

## Parameters
- `section`: 分类，缺省为 china


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "| 中国  | 新加坡    | 国际  | 财经     |\n| ----- | --------- | ----- | -------- |\n| china | singapore | world | zfinance |",
  "example": "/zaobao/realtime/china",
  "heat": 8943,
  "location": "realtime.ts",
  "maintainers": [
    "shunf4"
  ],
  "name": "即时新闻",
  "parameters": {
    "section": "分类，缺省为 china"
  },
  "path": "/realtime/:section?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67490527781761028",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/realtime/china",
      "title": "《联合早报》-中港台-即时",
      "type": "feed",
      "url": "rsshub://zaobao/realtime"
    },
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": "2026-07-29T06:12:28.593Z",
      "errorMessage": "Unexpected non-whitespace character after JSON at position 870 (line 1 column 871)\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\n502 \nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\n[GET] \"https://www.zaobao.com/realtime/world\": <no response> fetch failed\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\nUnexpected non-whitespace character after JSON at position 870 (line 1 column 871)\n",
      "id": "41461870201364483",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/realtime/world",
      "title": "《联合早报》-国际-即时",
      "type": "feed",
      "url": "rsshub://zaobao/realtime/world"
    }
  ]
}
```
