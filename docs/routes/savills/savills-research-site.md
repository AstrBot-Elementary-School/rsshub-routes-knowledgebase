# 第一太平戴维斯 Savills - 市场研究

## Coverage
`index-only`

## Route
- Namespace: `savills`
- Namespace Name: `第一太平戴维斯 Savills`
- Route Path: `/savills/research/:site?`
- Route Name: `市场研究`
- Example: `/savills/research/cn`
- URL: `www.savills.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
返回官网最新研究报告的摘要，以及源站提供的 PDF 附件。英文中国站目前返回错误页面；香港英文站也会发布亚太区域研究。

## Parameters
- `site`: cn：中国简体中文（默认）；hk：香港英文；hk-tc：香港繁体中文。


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `www.savills.com.cn/insight-and-opinion/research.aspx`
- `target`: `/research/cn`
### Rule 2
- `source`:
  - `www.savills.com.hk/insight-and-opinion/research.aspx`
- `target`: `/research/hk`
### Rule 3
- `source`:
  - `tc.savills.com.hk/insight-and-opinion/research.aspx`
- `target`: `/research/hk-tc`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "返回官网最新研究报告的摘要，以及源站提供的 PDF 附件。英文中国站目前返回错误页面；香港英文站也会发布亚太区域研究。",
  "example": "/savills/research/cn",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "市场研究",
  "parameters": {
    "site": "cn：中国简体中文（默认）；hk：香港英文；hk-tc：香港繁体中文。"
  },
  "path": "/research/:site?",
  "radar": [
    {
      "source": [
        "www.savills.com.cn/insight-and-opinion/research.aspx"
      ],
      "target": "/research/cn"
    },
    {
      "source": [
        "www.savills.com.hk/insight-and-opinion/research.aspx"
      ],
      "target": "/research/hk"
    },
    {
      "source": [
        "tc.savills.com.hk/insight-and-opinion/research.aspx"
      ],
      "target": "/research/hk-tc"
    }
  ],
  "topFeeds": []
}
```
