# 中国农资流通协会 - 化肥价格指数与分析

## Coverage
`index-only`

## Route
- Namespace: `chinanzxh`
- Namespace Name: `中国农资流通协会`
- Route Path: `/chinanzxh/data/:category?`
- Route Name: `化肥价格指数与分析`
- Example: `/chinanzxh/data/price-indices`
- URL: `www.chinanzxh.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `data.ts`
- Source Module: `_None_`

## Description
收录各类化肥的价格指数周报与市场分析全文。指数分析文章来自微信公众号；若微信临时限制访问，订阅会报错，请稍后重试。

## Parameters
- `category`: {"default": "price-indices", "description": "数据中心栏目。", "options": [{"label": "价格指数", "value": "price-indices"}, {"label": "指数分析", "value": "index-analysis"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chinanzxh.com/data/price-indices/index.html`
- `target`: `/data/price-indices`
### Rule 2
- `source`:
  - `www.chinanzxh.com/data/index-analysis/index.html`
- `target`: `/data/index-analysis`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "收录各类化肥的价格指数周报与市场分析全文。指数分析文章来自微信公众号；若微信临时限制访问，订阅会报错，请稍后重试。",
  "example": "/chinanzxh/data/price-indices",
  "heat": 0,
  "location": "data.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "化肥价格指数与分析",
  "parameters": {
    "category": {
      "default": "price-indices",
      "description": "数据中心栏目。",
      "options": [
        {
          "label": "价格指数",
          "value": "price-indices"
        },
        {
          "label": "指数分析",
          "value": "index-analysis"
        }
      ]
    }
  },
  "path": "/data/:category?",
  "radar": [
    {
      "source": [
        "www.chinanzxh.com/data/price-indices/index.html"
      ],
      "target": "/data/price-indices"
    },
    {
      "source": [
        "www.chinanzxh.com/data/index-analysis/index.html"
      ],
      "target": "/data/index-analysis"
    }
  ],
  "topFeeds": []
}
```
