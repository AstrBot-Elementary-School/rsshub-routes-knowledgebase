# 联合早报 - 热门新闻

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/zaobao/popular/:period?`
- Route Name: `热门新闻`
- Example: `/zaobao/popular/daily`
- URL: `www.zaobao.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `DIYgod`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
Includes the source’s ranked headlines, summaries, and images. Complete articles may require a Zaobao subscription.

## Parameters
- `period`: daily（单日，默认）或 weekly（一周）。


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `zaobao.com.sg/news`
- `target`: `/popular/daily`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Includes the source’s ranked headlines, summaries, and images. Complete articles may require a Zaobao subscription.",
  "example": "/zaobao/popular/daily",
  "heat": 0,
  "location": "popular.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "热门新闻",
  "parameters": {
    "period": "daily（单日，默认）或 weekly（一周）。"
  },
  "path": "/popular/:period?",
  "radar": [
    {
      "source": [
        "zaobao.com.sg/news"
      ],
      "target": "/popular/daily"
    }
  ],
  "topFeeds": []
}
```
