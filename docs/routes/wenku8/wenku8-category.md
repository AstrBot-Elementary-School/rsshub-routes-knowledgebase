# 轻小说文库 - 首页分类

## Coverage
`index-only`

## Route
- Namespace: `wenku8`
- Namespace Name: `轻小说文库`
- Route Path: `/wenku8/:category?`
- Route Name: `首页分类`
- Example: `/wenku8/lastupdate`
- URL: `www.wenku8.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
|  今日更新  | 完结全本 | 新书一览 | 动画化作品 | 热门轻小说 |  轻小说列表 |
| :--------: | :------: | :------: | :--------: | :--------: | :---------: |
| lastupdate | fullflag | postdate |    anime   |  allvisit  | articlelist |

## Parameters
- `category`: 首页分类，见下表，默认为今日更新


## Features
- `requireConfig`: [{"description": "登陆轻小说文库后的 cookie", "name": "WENKU8_COOKIE"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "|  今日更新  | 完结全本 | 新书一览 | 动画化作品 | 热门轻小说 |  轻小说列表 |\n| :--------: | :------: | :------: | :--------: | :--------: | :---------: |\n| lastupdate | fullflag | postdate |    anime   |  allvisit  | articlelist |",
  "example": "/wenku8/lastupdate",
  "features": {
    "requireConfig": [
      {
        "description": "登陆轻小说文库后的 cookie",
        "name": "WENKU8_COOKIE"
      }
    ]
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "首页分类",
  "parameters": {
    "category": "首页分类，见下表，默认为今日更新"
  },
  "path": "/:category?",
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-25T07:36:49.698Z",
      "errorMessage": "[GET] \"https://www.wenku8.net/modules/article/articlelist.php?fullflag=1\": 403 Forbidden\n",
      "id": "182658801734908930",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://wenku8/fullflag"
    },
    {
      "description": null,
      "errorAt": "2025-08-25T07:36:59.386Z",
      "errorMessage": "[GET] \"https://www.wenku8.net/modules/article/toplist.php?sort=postdate\": 403 Forbidden\n",
      "id": "182658801734908931",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://wenku8/postdate"
    }
  ]
}
```
