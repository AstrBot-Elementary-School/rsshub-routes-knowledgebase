# 百度 - 贴吧搜索

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/search/:qw/:routeParams?`
- Route Name: `贴吧搜索`
- Example: `/baidu/tieba/search/neuro`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `JimenezLi, FlanChanXwO`
- Source Location: `tieba/search.ts`
- Source Module: `_None_`

## Description
| 键           | 含义                                                       | 接受的值      | 默认值 |
| ------------ | ---------------------------------------------------------- | ------------- | ------ |
| kw           | 在名为 kw 的贴吧中搜索                                     | 任意名称 / 无 | 无     |
| only\_thread | 只看主题帖，默认为 0 关闭                                  | 0/1           | 0      |
| rn           | 返回条目的数量                                             | 1-20          | 20     |
| sm           | 排序方式，0 为按时间顺序，1 为按时间倒序，2 为按相关性顺序 | 0/1/2         | 1      |

用例：`/baidu/tieba/search/neuro/kw=neurosama&only_thread=1&sm=2`

## Parameters
- `qw`: 搜索关键词
- `routeParams`: 额外参数；请参阅以下说明和表格


## Features
- `requireConfig`: [{"description": "百度 cookie 值，用于需要登录的贴吧页面", "name": "BAIDU_COOKIE", "optional": true}]
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 键           | 含义                                                       | 接受的值      | 默认值 |\n| ------------ | ---------------------------------------------------------- | ------------- | ------ |\n| kw           | 在名为 kw 的贴吧中搜索                                     | 任意名称 / 无 | 无     |\n| only\\_thread | 只看主题帖，默认为 0 关闭                                  | 0/1           | 0      |\n| rn           | 返回条目的数量                                             | 1-20          | 20     |\n| sm           | 排序方式，0 为按时间顺序，1 为按时间倒序，2 为按相关性顺序 | 0/1/2         | 1      |\n\n用例：`/baidu/tieba/search/neuro/kw=neurosama&only_thread=1&sm=2`",
  "example": "/baidu/tieba/search/neuro",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "百度 cookie 值，用于需要登录的贴吧页面",
        "name": "BAIDU_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 37,
  "location": "tieba/search.ts",
  "maintainers": [
    "JimenezLi",
    "FlanChanXwO"
  ],
  "name": "贴吧搜索",
  "parameters": {
    "qw": "搜索关键词",
    "routeParams": "额外参数；请参阅以下说明和表格"
  },
  "path": "/tieba/search/:qw/:routeParams?",
  "topFeeds": [
    {
      "description": "孙笑川吧 - 百度贴吧搜索 - Powered by RSSHub",
      "errorAt": "2025-11-28T22:53:21.188Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
      "id": "86933542129623040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/f/search/res?ie=utf-8&qw=%E5%AD%99%E7%AC%91%E5%B7%9D%E5%90%A7&rn=20",
      "title": "孙笑川吧 - 百度贴吧搜索",
      "type": "feed",
      "url": "rsshub://baidu/tieba/search/%E5%AD%99%E7%AC%91%E5%B7%9D%E5%90%A7"
    },
    {
      "description": "生存狂 - 百度贴吧搜索 - Powered by RSSHub",
      "errorAt": "2026-03-13T01:37:42.182Z",
      "errorMessage": "Baidu Tieba RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#baidu\">BAIDU_COOKIE</a>\n",
      "id": "82761206638000128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/f/search/res?ie=utf-8&qw=%E7%94%9F%E5%AD%98%E7%8B%82&rn=20",
      "title": "生存狂 - 百度贴吧搜索",
      "type": "feed",
      "url": "rsshub://baidu/tieba/search/%E7%94%9F%E5%AD%98%E7%8B%82"
    }
  ]
}
```
