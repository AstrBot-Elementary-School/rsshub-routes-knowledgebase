# 麦当劳 - 麦当劳活动资讯

## Coverage
`index-only`

## Route
- Namespace: `mcdonalds`
- Namespace Name: `麦当劳`
- Route Path: `/mcdonalds/cn/:category`
- Route Name: `麦当劳活动资讯`
- Example: `/mcdonalds/cn/sales+event`
- URL: `www.mcdonalds.com.cn`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `huyyi`
- Source Location: `cn-news.ts`
- Source Module: `_None_`

## Description
| 全部分类   | 社会责任       | 人员品牌 | 产品故事 | 优惠  | 品牌文化 | 活动速报 |
| ---------- | -------------- | -------- | -------- | ----- | -------- | -------- |
| news\_list | responsibility | brand    | product  | sales | culture  | event    |

## Parameters
- `category`: 分类名（可用 + 连接多个分类）


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 全部分类   | 社会责任       | 人员品牌 | 产品故事 | 优惠  | 品牌文化 | 活动速报 |\n| ---------- | -------------- | -------- | -------- | ----- | -------- | -------- |\n| news\\_list | responsibility | brand    | product  | sales | culture  | event    |",
  "example": "/mcdonalds/cn/sales+event",
  "heat": 0,
  "location": "cn-news.ts",
  "maintainers": [
    "huyyi"
  ],
  "name": "麦当劳活动资讯",
  "parameters": {
    "category": "分类名（可用 + 连接多个分类）"
  },
  "path": "/cn/:category",
  "topFeeds": []
}
```
