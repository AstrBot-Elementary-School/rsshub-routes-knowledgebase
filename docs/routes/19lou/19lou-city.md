# 19 楼 - 头条

## Coverage
`index-only`

## Route
- Namespace: `19lou`
- Namespace Name: `19 楼`
- Route Path: `/19lou/:city?`
- Route Name: `头条`
- Example: `/19lou/jiaxing`
- URL: `19lou.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 杭州 | 台州    | 嘉兴    | 宁波   | 湖州   |
| ---- | ------- | ------- | ------ | ------ |
| www  | taizhou | jiaxing | ningbo | huzhou |

| 绍兴     | 湖州   | 温州    | 金华   | 舟山     |
| -------- | ------ | ------- | ------ | -------- |
| shaoxing | huzhou | wenzhou | jinhua | zhoushan |

| 衢州   | 丽水   | 义乌 | 萧山     | 余杭   |
| ------ | ------ | ---- | -------- | ------ |
| quzhou | lishui | yiwu | xiaoshan | yuhang |

| 临安  | 富阳   | 桐庐   | 建德   | 淳安   |
| ----- | ------ | ------ | ------ | ------ |
| linan | fuyang | tonglu | jiande | chunan |

## Parameters
- `city`: 分类，见下表，默认为 www，即杭州


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 杭州 | 台州    | 嘉兴    | 宁波   | 湖州   |\n| ---- | ------- | ------- | ------ | ------ |\n| www  | taizhou | jiaxing | ningbo | huzhou |\n\n| 绍兴     | 湖州   | 温州    | 金华   | 舟山     |\n| -------- | ------ | ------- | ------ | -------- |\n| shaoxing | huzhou | wenzhou | jinhua | zhoushan |\n\n| 衢州   | 丽水   | 义乌 | 萧山     | 余杭   |\n| ------ | ------ | ---- | -------- | ------ |\n| quzhou | lishui | yiwu | xiaoshan | yuhang |\n\n| 临安  | 富阳   | 桐庐   | 建德   | 淳安   |\n| ----- | ------ | ------ | ------ | ------ |\n| linan | fuyang | tonglu | jiande | chunan |",
  "example": "/19lou/jiaxing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 55,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "头条",
  "parameters": {
    "city": "分类，见下表，默认为 www，即杭州"
  },
  "path": "/:city?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "嘉兴 19 楼 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59034349000577024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jiaxing.19lou.com/",
      "title": "嘉兴 19 楼",
      "type": "feed",
      "url": "rsshub://19lou/jiaxing"
    },
    {
      "description": "台州19楼 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71090917239899136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://taizhou.19lou.com/",
      "title": "台州19楼",
      "type": "feed",
      "url": "rsshub://19lou/taizhou"
    }
  ]
}
```
