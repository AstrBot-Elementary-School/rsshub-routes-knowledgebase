# 联合早报 - 其他栏目

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/zaobao/other/:type?/:section?`
- Route Name: `其他栏目`
- Example: `/zaobao/other/lifestyle/health`
- URL: `www.zaobao.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `shunf4`
- Source Location: `other.ts`
- Source Module: `_None_`

## Description
除了上面两个兼容规则之外，联合早报网站里所有页面形如 <https://www.zaobao.com/lifestyle/health> 这样的栏目都能被这个规则解析到，早报的大部分栏目都是这个样式的。你可以测试之后再订阅。

## Parameters
- `type`: https://www.zaobao.com/**lifestyle**/health 中的 **lifestyle**
- `section`: https://www.zaobao.com/lifestyle/**health** 中的 **health**


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "除了上面两个兼容规则之外，联合早报网站里所有页面形如 <https://www.zaobao.com/lifestyle/health> 这样的栏目都能被这个规则解析到，早报的大部分栏目都是这个样式的。你可以测试之后再订阅。",
  "example": "/zaobao/other/lifestyle/health",
  "heat": 144,
  "location": "other.ts",
  "maintainers": [
    "shunf4"
  ],
  "name": "其他栏目",
  "parameters": {
    "section": "https://www.zaobao.com/lifestyle/**health** 中的 **health**",
    "type": "https://www.zaobao.com/**lifestyle**/health 中的 **lifestyle**"
  },
  "path": "/other/:type?/:section?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149086131447585792",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/special/cnpol",
      "title": "《联合早报》中国政情 - 专题特稿 | 联合早报",
      "type": "feed",
      "url": "rsshub://zaobao/other/special/cnpol"
    },
    {
      "description": "新加坡、中国、亚洲和国际的即时、评论、商业、体育、生活、科技与多媒体新闻，尽在联合早报。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114855620432737280",
      "image": "https://www.zaobao.com.sg/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zaobao.com/forum/views",
      "title": "《联合早报》时事与新闻评论 | 联合早报",
      "type": "feed",
      "url": "rsshub://zaobao/other/forum/views"
    }
  ]
}
```
