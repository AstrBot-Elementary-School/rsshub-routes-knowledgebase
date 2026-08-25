# 中国纺织经济信息网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `ctei`
- Namespace Name: `中国纺织经济信息网`
- Route Path: `/ctei/news/:id?`
- Route Name: `资讯`
- Example: `/ctei/news/bwzq`
- URL: `news.ctei.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 要闻   | 国内     | 国际     | 企业    | 品牌  | 外贸  | 政策   | 科技       | 流行    | 服装    | 家纺    |
| ------ | -------- | -------- | ------- | ----- | ----- | ------ | ---------- | ------- | ------- | ------- |
| newsyw | domestic | internal | company | brand | trade | policy | Technology | fashion | apparel | hometex |

## Parameters
- `id`: 分类 id，可在分类页的 URL 中找到，默认为本网专区


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 要闻   | 国内     | 国际     | 企业    | 品牌  | 外贸  | 政策   | 科技       | 流行    | 服装    | 家纺    |\n| ------ | -------- | -------- | ------- | ----- | ----- | ------ | ---------- | ------- | ------- | ------- |\n| newsyw | domestic | internal | company | brand | trade | policy | Technology | fashion | apparel | hometex |",
  "example": "/ctei/news/bwzq",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "id": "分类 id，可在分类页的 URL 中找到，默认为本网专区"
  },
  "path": "/news/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
