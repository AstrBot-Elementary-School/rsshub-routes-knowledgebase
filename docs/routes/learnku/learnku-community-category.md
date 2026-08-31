# LearnKu - 社区

## Coverage
`index-only`

## Route
- Namespace: `learnku`
- Namespace Name: `LearnKu`
- Route Path: `/learnku/:community/:category?`
- Route Name: `社区`
- Example: `/learnku/laravel/qa`
- URL: `learnku.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `kayw-geek`
- Source Location: `topic.tsx`
- Source Module: `_None_`

## Description
| 招聘 | 翻译         | 问答 | 链接  |
| ---- | ------------ | ---- | ----- |
| jobs | translations | qa   | links |

## Parameters
- `community`: 社区 标识，可在 <https://learnku.com/communities> 找到
- `category`: 分类，如果不传 `category` 则获取全部分类


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `learnku.com/:community`
- `target`: `/:community`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 招聘 | 翻译         | 问答 | 链接  |\n| ---- | ------------ | ---- | ----- |\n| jobs | translations | qa   | links |",
  "example": "/learnku/laravel/qa",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 168,
  "location": "topic.tsx",
  "maintainers": [
    "kayw-geek"
  ],
  "name": "社区",
  "parameters": {
    "category": "分类，如果不传 `category` 则获取全部分类",
    "community": "社区 标识，可在 <https://learnku.com/communities> 找到"
  },
  "path": "/:community/:category?",
  "radar": [
    {
      "source": [
        "learnku.com/:community"
      ],
      "target": "/:community"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "讨论话题包括编辑器、终端、Git、VSCode、PHPStorm、VIM 等开发者工具相关话题。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58746729811026944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://learnku.com/devtools",
      "title": "LearnKu - 开发者工具论坛 - 最新",
      "type": "feed",
      "url": "rsshub://learnku/devtools"
    },
    {
      "description": "Go（又称 Golang）是 Google 开发的一种静态强类型、编译型、并发型，并具有垃圾回收功能的编程语言。Go 被誉为是未来的服务器端编程语言。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60868955443264512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://learnku.com/go",
      "title": "LearnKu - Go 技术论坛 - 最新",
      "type": "feed",
      "url": "rsshub://learnku/go"
    }
  ]
}
```
