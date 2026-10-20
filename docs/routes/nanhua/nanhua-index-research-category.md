# 南华期货 - 南华指数研究

## Coverage
`index-only`

## Route
- Namespace: `nanhua`
- Namespace Name: `南华期货`
- Route Path: `/nanhua/index-research/:category?`
- Route Name: `南华指数研究`
- Example: `/nanhua/index-research/daily`
- URL: `www.nanhua.net/subpage/research/nawaaindex/indexresearch/index-daily.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index-research.ts`
- Source Module: `_None_`

## Description
报告正文为 PDF，条目链接直接指向 PDF 文件。

## Parameters
- `category`: {"default": "daily", "description": "报告类型", "options": [{"label": "指数日报", "value": "daily"}, {"label": "指数周报", "value": "weekly"}, {"label": "指数季报", "value": "quarterly"}]}


## Features
_None_

## Radar
### Rule 1
- `title`: `指数日报`
- `source`:
  - `www.nanhua.net/subpage/research/nawaaindex/indexresearch/index-daily.html`
- `target`: `/index-research/daily`
### Rule 2
- `title`: `指数周报`
- `source`:
  - `www.nanhua.net/subpage/research/nawaaindex/indexresearch/index-weekly.html`
- `target`: `/index-research/weekly`
### Rule 3
- `title`: `指数季报`
- `source`:
  - `www.nanhua.net/subpage/research/nawaaindex/indexresearch/seminar.html`
- `target`: `/index-research/quarterly`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "报告正文为 PDF，条目链接直接指向 PDF 文件。",
  "example": "/nanhua/index-research/daily",
  "heat": 0,
  "location": "index-research.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "南华指数研究",
  "parameters": {
    "category": {
      "default": "daily",
      "description": "报告类型",
      "options": [
        {
          "label": "指数日报",
          "value": "daily"
        },
        {
          "label": "指数周报",
          "value": "weekly"
        },
        {
          "label": "指数季报",
          "value": "quarterly"
        }
      ]
    }
  },
  "path": "/index-research/:category?",
  "radar": [
    {
      "source": [
        "www.nanhua.net/subpage/research/nawaaindex/indexresearch/index-daily.html"
      ],
      "target": "/index-research/daily",
      "title": "指数日报"
    },
    {
      "source": [
        "www.nanhua.net/subpage/research/nawaaindex/indexresearch/index-weekly.html"
      ],
      "target": "/index-research/weekly",
      "title": "指数周报"
    },
    {
      "source": [
        "www.nanhua.net/subpage/research/nawaaindex/indexresearch/seminar.html"
      ],
      "target": "/index-research/quarterly",
      "title": "指数季报"
    }
  ],
  "topFeeds": [],
  "url": "www.nanhua.net/subpage/research/nawaaindex/indexresearch/index-daily.html"
}
```
