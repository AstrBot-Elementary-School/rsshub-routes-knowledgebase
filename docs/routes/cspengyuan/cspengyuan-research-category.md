# 中证鹏元 - 信用研究

## Coverage
`index-only`

## Route
- Namespace: `cspengyuan`
- Namespace Name: `中证鹏元`
- Route Path: `/cspengyuan/research/:category?`
- Route Name: `信用研究`
- Example: `/cspengyuan/research/macroSpecialResearch`
- URL: `www.cspengyuan.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
| 栏目         | 编码                    |
| ------------ | ----------------------- |
| 宏观专题     | macroSpecialResearch    |
| 政策解读     | macroPolicyResearch     |
| 经济观察     | macroEconomiesResearch  |
| 大类资产     | macroAssetClassResearch |
| 宏观周报     | macroWeeklyResearch     |
| 债市专题研究 | bondSpecial             |
| 热点分析     | bondHotspot             |
| 债市周报     | bondWeekly              |
| 债市观察     | bondMonthly             |
| 债市年报     | bondYearly              |
| 行业评论     | industryComment         |
| 行业展望     | industryOutlook         |
| 行业专题     | industrySpecial         |

## Parameters
- `category`: 官网信用研究栏目编码，默认 macroSpecialResearch。


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `www.cspengyuan.com/credit-research/:category`
- `target`: `/research/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 栏目         | 编码                    |\n| ------------ | ----------------------- |\n| 宏观专题     | macroSpecialResearch    |\n| 政策解读     | macroPolicyResearch     |\n| 经济观察     | macroEconomiesResearch  |\n| 大类资产     | macroAssetClassResearch |\n| 宏观周报     | macroWeeklyResearch     |\n| 债市专题研究 | bondSpecial             |\n| 热点分析     | bondHotspot             |\n| 债市周报     | bondWeekly              |\n| 债市观察     | bondMonthly             |\n| 债市年报     | bondYearly              |\n| 行业评论     | industryComment         |\n| 行业展望     | industryOutlook         |\n| 行业专题     | industrySpecial         |",
  "example": "/cspengyuan/research/macroSpecialResearch",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "信用研究",
  "parameters": {
    "category": "官网信用研究栏目编码，默认 macroSpecialResearch。"
  },
  "path": "/research/:category?",
  "radar": [
    {
      "source": [
        "www.cspengyuan.com/credit-research/:category"
      ],
      "target": "/research/:category"
    }
  ],
  "topFeeds": []
}
```
