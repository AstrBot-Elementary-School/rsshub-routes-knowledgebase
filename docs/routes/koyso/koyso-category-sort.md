# Koyso - 游戏

## Coverage
`index-only`

## Route
- Namespace: `koyso`
- Namespace Name: `Koyso`
- Route Path: `/koyso/:category?/:sort?`
- Route Name: `游戏`
- Example: `/koyso/0/latest`
- URL: `koyso.to`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
订阅 [最新动作游戏](https://koyso.to/?category=3\&sort=latest)，其源网址为 `https://koyso.to/?category=3&sort=latest`，请参考该 URL 指定部分构成参数，此时路由为 [`/koyso/3/latest`](https://koyso.to/?category=3\&sort=latest)。
:::

#### 分类

| 分类                                        | ID                                |
| ------------------------------------------- | --------------------------------- |
| [全部游戏](https://koyso.to/)               | [0](https://rsshub.app/koyso/0)   |
| [动作游戏](https://koyso.to/?category=3)    | [3](https://rsshub.app/koyso/3)   |
| [冒险游戏](https://koyso.to/?category=5)    | [5](https://rsshub.app/koyso/5)   |
| [绅士游戏](https://koyso.to/?category=7)    | [7](https://rsshub.app/koyso/7)   |
| [射击游戏](https://koyso.to/?category=1)    | [1](https://rsshub.app/koyso/1)   |
| [休闲游戏](https://koyso.to/?category=2)    | [2](https://rsshub.app/koyso/2)   |
| [体育竞速](https://koyso.to/?category=4)    | [4](https://rsshub.app/koyso/4)   |
| [模拟经营](https://koyso.to/?category=6)    | [6](https://rsshub.app/koyso/6)   |
| [角色扮演](https://koyso.to/?category=8)    | [8](https://rsshub.app/koyso/8)   |
| [策略游戏](https://koyso.to/?category=9)    | [9](https://rsshub.app/koyso/9)   |
| [格斗游戏](https://koyso.to/?category=10)   | [10](https://rsshub.app/koyso/10) |
| [恐怖游戏](https://koyso.to/?category=11)   | [11](https://rsshub.app/koyso/11) |
| [即时战略](https://koyso.to/?category=12)   | [12](https://rsshub.app/koyso/12) |
| [卡牌游戏](https://koyso.to/?category=13)   | [13](https://rsshub.app/koyso/13) |
| [独立游戏](https://koyso.to/?category=14)   | [14](https://rsshub.app/koyso/14) |
| [局域网联机](https://koyso.to/?category=15) | [15](https://rsshub.app/koyso/15) |

#### 排序

| 排序                                  | ID                                          |
| ------------------------------------- | ------------------------------------------- |
| [热度](https://koyso.to/?sort=views)  | [views](https://rsshub.app/koyso/0/views)   |
| [最新](https://koyso.to/?sort=latest) | [latest](https://rsshub.app/koyso/0/latest) |

## Parameters
- `category`: {"description": "排序，默认为 `0`，即全部，可在对应分类页 URL 中找到", "options": [{"label": "全部游戏", "value": "0"}, {"label": "动作游戏", "value": "3"}, {"label": "冒险游戏", "value": "5"}, {"label": "绅士游戏", "value": "7"}, {"label": "射击游戏", "value": "1"}, {"label": "休闲游戏", "value": "2"}, {"label": "体育竞速", "value": "4"}, {"label": "模拟经营", "value": "6"}, {"label": "角色扮演", "value": "8"}, {"label": "策略游戏", "value": "9"}, {"label": "格斗游戏", "value": "10"}, {"label": "恐怖游戏", "value": "11"}, {"label": "即时战略", "value": "12"}, {"label": "卡牌游戏", "value": "13"}, {"label": "独立游戏", "value": "14"}, {"label": "局域网联机", "value": "15"}]}
- `sort`: {"description": "排序，默认为 `latest`，即最新，可在对应页 URL 中找到", "options": [{"label": "热度", "value": "views"}, {"label": "最新", "value": "latest"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `koyso.to`
### Rule 2
- `title`: `全部游戏`
- `source`:
  - `koyso.to`
- `target`: `/0`
### Rule 3
- `title`: `动作游戏`
- `source`:
  - `koyso.to`
- `target`: `/3`
### Rule 4
- `title`: `冒险游戏`
- `source`:
  - `koyso.to`
- `target`: `/5`
### Rule 5
- `title`: `绅士游戏`
- `source`:
  - `koyso.to`
- `target`: `/7`
### Rule 6
- `title`: `射击游戏`
- `source`:
  - `koyso.to`
- `target`: `/1`
### Rule 7
- `title`: `休闲游戏`
- `source`:
  - `koyso.to`
- `target`: `/2`
### Rule 8
- `title`: `体育竞速`
- `source`:
  - `koyso.to`
- `target`: `/4`
### Rule 9
- `title`: `模拟经营`
- `source`:
  - `koyso.to`
- `target`: `/6`
### Rule 10
- `title`: `角色扮演`
- `source`:
  - `koyso.to`
- `target`: `/8`
### Rule 11
- `title`: `策略游戏`
- `source`:
  - `koyso.to`
- `target`: `/9`
### Rule 12
- `title`: `格斗游戏`
- `source`:
  - `koyso.to`
- `target`: `/10`
### Rule 13
- `title`: `恐怖游戏`
- `source`:
  - `koyso.to`
- `target`: `/11`
### Rule 14
- `title`: `即时战略`
- `source`:
  - `koyso.to`
- `target`: `/12`
### Rule 15
- `title`: `卡牌游戏`
- `source`:
  - `koyso.to`
- `target`: `/13`
### Rule 16
- `title`: `独立游戏`
- `source`:
  - `koyso.to`
- `target`: `/14`
### Rule 17
- `title`: `局域网联机`
- `source`:
  - `koyso.to`
- `target`: `/15`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n订阅 [最新动作游戏](https://koyso.to/?category=3\\&sort=latest)，其源网址为 `https://koyso.to/?category=3&sort=latest`，请参考该 URL 指定部分构成参数，此时路由为 [`/koyso/3/latest`](https://koyso.to/?category=3\\&sort=latest)。\n:::\n\n#### 分类\n\n| 分类                                        | ID                                |\n| ------------------------------------------- | --------------------------------- |\n| [全部游戏](https://koyso.to/)               | [0](https://rsshub.app/koyso/0)   |\n| [动作游戏](https://koyso.to/?category=3)    | [3](https://rsshub.app/koyso/3)   |\n| [冒险游戏](https://koyso.to/?category=5)    | [5](https://rsshub.app/koyso/5)   |\n| [绅士游戏](https://koyso.to/?category=7)    | [7](https://rsshub.app/koyso/7)   |\n| [射击游戏](https://koyso.to/?category=1)    | [1](https://rsshub.app/koyso/1)   |\n| [休闲游戏](https://koyso.to/?category=2)    | [2](https://rsshub.app/koyso/2)   |\n| [体育竞速](https://koyso.to/?category=4)    | [4](https://rsshub.app/koyso/4)   |\n| [模拟经营](https://koyso.to/?category=6)    | [6](https://rsshub.app/koyso/6)   |\n| [角色扮演](https://koyso.to/?category=8)    | [8](https://rsshub.app/koyso/8)   |\n| [策略游戏](https://koyso.to/?category=9)    | [9](https://rsshub.app/koyso/9)   |\n| [格斗游戏](https://koyso.to/?category=10)   | [10](https://rsshub.app/koyso/10) |\n| [恐怖游戏](https://koyso.to/?category=11)   | [11](https://rsshub.app/koyso/11) |\n| [即时战略](https://koyso.to/?category=12)   | [12](https://rsshub.app/koyso/12) |\n| [卡牌游戏](https://koyso.to/?category=13)   | [13](https://rsshub.app/koyso/13) |\n| [独立游戏](https://koyso.to/?category=14)   | [14](https://rsshub.app/koyso/14) |\n| [局域网联机](https://koyso.to/?category=15) | [15](https://rsshub.app/koyso/15) |\n\n#### 排序\n\n| 排序                                  | ID                                          |\n| ------------------------------------- | ------------------------------------------- |\n| [热度](https://koyso.to/?sort=views)  | [views](https://rsshub.app/koyso/0/views)   |\n| [最新](https://koyso.to/?sort=latest) | [latest](https://rsshub.app/koyso/0/latest) |",
  "example": "/koyso/0/latest",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 10,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "游戏",
  "parameters": {
    "category": {
      "description": "排序，默认为 `0`，即全部，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部游戏",
          "value": "0"
        },
        {
          "label": "动作游戏",
          "value": "3"
        },
        {
          "label": "冒险游戏",
          "value": "5"
        },
        {
          "label": "绅士游戏",
          "value": "7"
        },
        {
          "label": "射击游戏",
          "value": "1"
        },
        {
          "label": "休闲游戏",
          "value": "2"
        },
        {
          "label": "体育竞速",
          "value": "4"
        },
        {
          "label": "模拟经营",
          "value": "6"
        },
        {
          "label": "角色扮演",
          "value": "8"
        },
        {
          "label": "策略游戏",
          "value": "9"
        },
        {
          "label": "格斗游戏",
          "value": "10"
        },
        {
          "label": "恐怖游戏",
          "value": "11"
        },
        {
          "label": "即时战略",
          "value": "12"
        },
        {
          "label": "卡牌游戏",
          "value": "13"
        },
        {
          "label": "独立游戏",
          "value": "14"
        },
        {
          "label": "局域网联机",
          "value": "15"
        }
      ]
    },
    "sort": {
      "description": "排序，默认为 `latest`，即最新，可在对应页 URL 中找到",
      "options": [
        {
          "label": "热度",
          "value": "views"
        },
        {
          "label": "最新",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/:category?/:sort?",
  "radar": [
    {
      "source": [
        "koyso.to"
      ]
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/0",
      "title": "全部游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/3",
      "title": "动作游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/5",
      "title": "冒险游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/7",
      "title": "绅士游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/1",
      "title": "射击游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/2",
      "title": "休闲游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/4",
      "title": "体育竞速"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/6",
      "title": "模拟经营"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/8",
      "title": "角色扮演"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/9",
      "title": "策略游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/10",
      "title": "格斗游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/11",
      "title": "恐怖游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/12",
      "title": "即时战略"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/13",
      "title": "卡牌游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/14",
      "title": "独立游戏"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/15",
      "title": "局域网联机"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Free pre-installed PC games download. No speed limits, no installation required. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "186257019396793344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://koyso.to/?sort=latest",
      "title": "PlayZip - PC Games Free Download - All - Latest",
      "type": "feed",
      "url": "rsshub://koyso"
    },
    {
      "description": "Free pre-installed PC games download. No speed limits, no installation required. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "185221927541489664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://koyso.to/?sort=latest",
      "title": "PlayZip - PC Games Free Download - All - Latest",
      "type": "feed",
      "url": "rsshub://koyso/0/latest"
    }
  ],
  "url": "koyso.to",
  "view": 0
}
```
