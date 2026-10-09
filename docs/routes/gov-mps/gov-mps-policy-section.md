# 中华人民共和国公安部 - 政策文件与解读

## Coverage
`index-only`

## Route
- Namespace: `gov/mps`
- Namespace Name: `中华人民共和国公安部`
- Route Path: `/gov/mps/policy/:section?`
- Route Name: `政策文件与解读`
- Example: `/gov/mps/policy/documents`
- URL: `www.mps.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `DIYgod`
- Source Location: `policy.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: documents（政策文件，默认）或 interpretations（政策解读）


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `www.mps.gov.cn/n6557558/index.html`
- `target`: `/policy/documents`
### Rule 2
- `source`:
  - `www.mps.gov.cn/n6557563/index.html`
- `target`: `/policy/interpretations`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/mps/policy/documents",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "policy.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "政策文件与解读",
  "parameters": {
    "section": "documents（政策文件，默认）或 interpretations（政策解读）"
  },
  "path": "/policy/:section?",
  "radar": [
    {
      "source": [
        "www.mps.gov.cn/n6557558/index.html"
      ],
      "target": "/policy/documents"
    },
    {
      "source": [
        "www.mps.gov.cn/n6557563/index.html"
      ],
      "target": "/policy/interpretations"
    }
  ],
  "topFeeds": []
}
```
