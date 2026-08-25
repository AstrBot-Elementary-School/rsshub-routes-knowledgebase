# WeGene - 微解读栏目

## Coverage
`index-only`

## Route
- Namespace: `wegene`
- Namespace Name: `WeGene`
- Route Path: `/wegene/column/:type/:category`
- Route Name: `微解读栏目`
- Example: `/wegene/column/all/all`
- URL: `www.wegene.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `LogicJake`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
::: tip
type 为 all 时，category 参数不支持 cost 和 free
:::

| 全部 | 祖源分析 | 付费 | 遗传性疾病 | 药物指南 | 免费 | 运动基因 | 营养代谢   | 心理特质   | 健康风险 | 皮肤特性 | 遗传特征 |
| ---- | -------- | ---- | ---------- | -------- | ---- | -------- | ---------- | ---------- | -------- | -------- | -------- |
| all  | ancestry | cost | disease    | drug     | free | genefit  | metabolism | psychology | risk     | skin     | traits   |

## Parameters
- `type`: 栏目类型，all（全部项目） 或 weapp（专业版）
- `category`: 栏目分类


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wegene.com/crowdsourcing`
- `target`: `/column/all/all`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\ntype 为 all 时，category 参数不支持 cost 和 free\n:::\n\n| 全部 | 祖源分析 | 付费 | 遗传性疾病 | 药物指南 | 免费 | 运动基因 | 营养代谢   | 心理特质   | 健康风险 | 皮肤特性 | 遗传特征 |\n| ---- | -------- | ---- | ---------- | -------- | ---- | -------- | ---------- | ---------- | -------- | -------- | -------- |\n| all  | ancestry | cost | disease    | drug     | free | genefit  | metabolism | psychology | risk     | skin     | traits   |",
  "example": "/wegene/column/all/all",
  "heat": 0,
  "location": "column.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "微解读栏目",
  "parameters": {
    "category": "栏目分类",
    "type": "栏目类型，all（全部项目） 或 weapp（专业版）"
  },
  "path": "/column/:type/:category",
  "radar": [
    {
      "source": [
        "www.wegene.com/crowdsourcing"
      ],
      "target": "/column/all/all"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
