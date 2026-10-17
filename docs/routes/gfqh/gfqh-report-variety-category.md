# 广发期货 - 研究报告

## Coverage
`index-only`

## Route
- Namespace: `gfqh`
- Namespace Name: `广发期货`
- Route Path: `/gfqh/report/:variety?/:category?`
- Route Name: `研究报告`
- Example: `/gfqh/report/100005`
- URL: `rd.gfqh.cn/RDInformation/menu/235`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `report.tsx`
- Source Module: `_None_`

## Description
例如农产品常规报告使用 `/gfqh/report/100005/100001`。报告正文多为 PDF 附件，附件链接列在条目内容末尾。只读取第一页。

## Parameters
- `variety`: {"default": "0", "description": "交易品种", "options": [{"label": "全部", "value": "0"}, {"label": "能源化工", "value": "100002"}, {"label": "金融", "value": "100004"}, {"label": "农产品", "value": "100005"}, {"label": "综合", "value": "100009"}, {"label": "黑色金属", "value": "100010"}, {"label": "有色金属", "value": "100011"}]}
- `category`: {"default": "0", "description": "报告类型", "options": [{"label": "全部", "value": "0"}, {"label": "常规报告", "value": "100001"}, {"label": "专题报告", "value": "100003"}, {"label": "其他报告", "value": "100004"}, {"label": "调研报告", "value": "100005"}, {"label": "热点点评", "value": "100006"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rd.gfqh.cn/RDInformation/menu/235`
- `target`: `/report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "例如农产品常规报告使用 `/gfqh/report/100005/100001`。报告正文多为 PDF 附件，附件链接列在条目内容末尾。只读取第一页。",
  "example": "/gfqh/report/100005",
  "heat": 0,
  "location": "report.tsx",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "研究报告",
  "parameters": {
    "category": {
      "default": "0",
      "description": "报告类型",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "常规报告",
          "value": "100001"
        },
        {
          "label": "专题报告",
          "value": "100003"
        },
        {
          "label": "其他报告",
          "value": "100004"
        },
        {
          "label": "调研报告",
          "value": "100005"
        },
        {
          "label": "热点点评",
          "value": "100006"
        }
      ]
    },
    "variety": {
      "default": "0",
      "description": "交易品种",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "能源化工",
          "value": "100002"
        },
        {
          "label": "金融",
          "value": "100004"
        },
        {
          "label": "农产品",
          "value": "100005"
        },
        {
          "label": "综合",
          "value": "100009"
        },
        {
          "label": "黑色金属",
          "value": "100010"
        },
        {
          "label": "有色金属",
          "value": "100011"
        }
      ]
    }
  },
  "path": "/report/:variety?/:category?",
  "radar": [
    {
      "source": [
        "rd.gfqh.cn/RDInformation/menu/235"
      ],
      "target": "/report"
    }
  ],
  "topFeeds": [],
  "url": "rd.gfqh.cn/RDInformation/menu/235"
}
```
