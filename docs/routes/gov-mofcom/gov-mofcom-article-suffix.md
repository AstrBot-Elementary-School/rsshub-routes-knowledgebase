# 中华人民共和国商务部 - 政务公开

## Coverage
`index-only`

## Route
- Namespace: `gov/mofcom`
- Namespace Name: `中华人民共和国商务部`
- Route Path: `/gov/mofcom/article/:suffix{.+}`
- Route Name: `政务公开`
- Example: `/gov/mofcom/article/b`
- URL: `www.mofcom.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `LogicJake`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `suffix`: 支持形如 `http://www.mofcom.gov.cn/article/*` 的网站，传入 article 之后的后缀


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/mofcom/article/b",
  "heat": 1,
  "location": "article.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "政务公开",
  "parameters": {
    "suffix": "支持形如 `http://www.mofcom.gov.cn/article/*` 的网站，传入 article 之后的后缀"
  },
  "path": "/article/:suffix{.+}",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-10-07T13:07:55.026Z",
      "errorMessage": "[GET] \"http://www.mofcom.gov.cn/article/xwfb/\": 530 \n",
      "id": "198372079645781010",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gov/mofcom/article/xwfb"
    }
  ]
}
```
