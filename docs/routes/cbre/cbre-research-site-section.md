# 世邦魏理仕 CBRE - 洞见和市场报告

## Coverage
`index-only`

## Route
- Namespace: `cbre`
- Namespace Name: `世邦魏理仕 CBRE`
- Route Path: `/cbre/research/:site?/:section?`
- Route Name: `洞见和市场报告`
- Example: `/cbre/research/cn/insights`
- URL: `www.cbre.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
按官网发布时间返回最新报告摘要及公开 PDF 附件。香港繁体站的市场报告栏目目前提供英文报告，保留官网实际内容。

## Parameters
- `site`: cn：中国简体（默认）；cn-en：中国英文；hk：香港英文；hk-tc：香港繁体。
- `section`: insights：洞见（默认）；markets：市场报告。


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `www.cbre.com.cn/insights`
- `target`: `/research/cn`
### Rule 2
- `source`:
  - `www.cbre.com.cn/en/insights`
- `target`: `/research/cn-en`
### Rule 3
- `source`:
  - `www.cbre.com.hk/insights`
- `target`: `/research/hk`
### Rule 4
- `source`:
  - `www.cbre.com.hk/zh-hk/insights`
- `target`: `/research/hk-tc`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "按官网发布时间返回最新报告摘要及公开 PDF 附件。香港繁体站的市场报告栏目目前提供英文报告，保留官网实际内容。",
  "example": "/cbre/research/cn/insights",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "洞见和市场报告",
  "parameters": {
    "section": "insights：洞见（默认）；markets：市场报告。",
    "site": "cn：中国简体（默认）；cn-en：中国英文；hk：香港英文；hk-tc：香港繁体。"
  },
  "path": "/research/:site?/:section?",
  "radar": [
    {
      "source": [
        "www.cbre.com.cn/insights"
      ],
      "target": "/research/cn"
    },
    {
      "source": [
        "www.cbre.com.cn/en/insights"
      ],
      "target": "/research/cn-en"
    },
    {
      "source": [
        "www.cbre.com.hk/insights"
      ],
      "target": "/research/hk"
    },
    {
      "source": [
        "www.cbre.com.hk/zh-hk/insights"
      ],
      "target": "/research/hk-tc"
    }
  ],
  "topFeeds": []
}
```
