# PlayZip (Koyso) - 游戏

## Coverage
`index-only`

## Route
- Namespace: `koyso`
- Namespace Name: `PlayZip (Koyso)`
- Route Path: `/koyso/:category?/:sort?`
- Route Name: `游戏`
- Example: `/koyso/0/latest`
- URL: `playzip.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
订阅 [最新动作游戏](https://playzip.com/category/action?sort=latest)，其源网址为 `https://playzip.com/category/action?sort=latest`，请参考该 URL 指定部分构成参数，此时路由为 [`/koyso/3/latest`](https://playzip.com/category/action?sort=latest)。
:::

#### 分类

| 分类                                                   | ID                                |
| ------------------------------------------------------ | --------------------------------- |
| [全部游戏](https://playzip.com/)                       | [0](https://rsshub.app/koyso/0)   |
| [动作游戏](https://playzip.com/category/action)        | [3](https://rsshub.app/koyso/3)   |
| [冒险游戏](https://playzip.com/category/adventure)     | [5](https://rsshub.app/koyso/5)   |
| [绅士游戏](https://playzip.com/category/r18)           | [7](https://rsshub.app/koyso/7)   |
| [射击游戏](https://playzip.com/category/shooting)      | [1](https://rsshub.app/koyso/1)   |
| [休闲游戏](https://playzip.com/category/casual)        | [2](https://rsshub.app/koyso/2)   |
| [体育竞速](https://playzip.com/category/sports_racing) | [4](https://rsshub.app/koyso/4)   |
| [模拟经营](https://playzip.com/category/simulation)    | [6](https://rsshub.app/koyso/6)   |
| [角色扮演](https://playzip.com/category/rpg)           | [8](https://rsshub.app/koyso/8)   |
| [策略游戏](https://playzip.com/category/strategy)      | [9](https://rsshub.app/koyso/9)   |
| [格斗游戏](https://playzip.com/category/fighting)      | [10](https://rsshub.app/koyso/10) |
| [恐怖游戏](https://playzip.com/category/horror)        | [11](https://rsshub.app/koyso/11) |
| [即时战略](https://playzip.com/category/rts)           | [12](https://rsshub.app/koyso/12) |
| [卡牌游戏](https://playzip.com/category/card)          | [13](https://rsshub.app/koyso/13) |
| [独立游戏](https://playzip.com/category/indie)         | [14](https://rsshub.app/koyso/14) |
| [局域网联机](https://playzip.com/category/lan)         | [15](https://rsshub.app/koyso/15) |

#### 排序

| 排序                                     | ID                                          |
| ---------------------------------------- | ------------------------------------------- |
| [热度](https://playzip.com/?sort=views)  | [views](https://rsshub.app/koyso/0/views)   |
| [最新](https://playzip.com/?sort=latest) | [latest](https://rsshub.app/koyso/0/latest) |

## Parameters
- `category`: {"description": "分类，默认为 `0`，即全部，ID 对应下表分类", "options": [{"label": "全部游戏", "value": "0"}, {"label": "动作游戏", "value": "3"}, {"label": "冒险游戏", "value": "5"}, {"label": "绅士游戏", "value": "7"}, {"label": "射击游戏", "value": "1"}, {"label": "休闲游戏", "value": "2"}, {"label": "体育竞速", "value": "4"}, {"label": "模拟经营", "value": "6"}, {"label": "角色扮演", "value": "8"}, {"label": "策略游戏", "value": "9"}, {"label": "格斗游戏", "value": "10"}, {"label": "恐怖游戏", "value": "11"}, {"label": "即时战略", "value": "12"}, {"label": "卡牌游戏", "value": "13"}, {"label": "独立游戏", "value": "14"}, {"label": "局域网联机", "value": "15"}]}
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
- `title`: `全部游戏`
- `source`:
  - `koyso.to`
- `target`: `/0`
### Rule 2
- `source`:
  - `playzip.com/`
- `target`: `/0`
### Rule 3
- `title`: `动作游戏`
- `source`:
  - `koyso.to`
- `target`: `/3`
### Rule 4
- `source`:
  - `playzip.com/category/action`
- `target`: `/3`
### Rule 5
- `title`: `冒险游戏`
- `source`:
  - `koyso.to`
- `target`: `/5`
### Rule 6
- `source`:
  - `playzip.com/category/adventure`
- `target`: `/5`
### Rule 7
- `title`: `绅士游戏`
- `source`:
  - `koyso.to`
- `target`: `/7`
### Rule 8
- `source`:
  - `playzip.com/category/r18`
- `target`: `/7`
### Rule 9
- `title`: `射击游戏`
- `source`:
  - `koyso.to`
- `target`: `/1`
### Rule 10
- `source`:
  - `playzip.com/category/shooting`
- `target`: `/1`
### Rule 11
- `title`: `休闲游戏`
- `source`:
  - `koyso.to`
- `target`: `/2`
### Rule 12
- `source`:
  - `playzip.com/category/casual`
- `target`: `/2`
### Rule 13
- `title`: `体育竞速`
- `source`:
  - `koyso.to`
- `target`: `/4`
### Rule 14
- `source`:
  - `playzip.com/category/sports_racing`
- `target`: `/4`
### Rule 15
- `title`: `模拟经营`
- `source`:
  - `koyso.to`
- `target`: `/6`
### Rule 16
- `source`:
  - `playzip.com/category/simulation`
- `target`: `/6`
### Rule 17
- `title`: `角色扮演`
- `source`:
  - `koyso.to`
- `target`: `/8`
### Rule 18
- `source`:
  - `playzip.com/category/rpg`
- `target`: `/8`
### Rule 19
- `title`: `策略游戏`
- `source`:
  - `koyso.to`
- `target`: `/9`
### Rule 20
- `source`:
  - `playzip.com/category/strategy`
- `target`: `/9`
### Rule 21
- `title`: `格斗游戏`
- `source`:
  - `koyso.to`
- `target`: `/10`
### Rule 22
- `source`:
  - `playzip.com/category/fighting`
- `target`: `/10`
### Rule 23
- `title`: `恐怖游戏`
- `source`:
  - `koyso.to`
- `target`: `/11`
### Rule 24
- `source`:
  - `playzip.com/category/horror`
- `target`: `/11`
### Rule 25
- `title`: `即时战略`
- `source`:
  - `koyso.to`
- `target`: `/12`
### Rule 26
- `source`:
  - `playzip.com/category/rts`
- `target`: `/12`
### Rule 27
- `title`: `卡牌游戏`
- `source`:
  - `koyso.to`
- `target`: `/13`
### Rule 28
- `source`:
  - `playzip.com/category/card`
- `target`: `/13`
### Rule 29
- `title`: `独立游戏`
- `source`:
  - `koyso.to`
- `target`: `/14`
### Rule 30
- `source`:
  - `playzip.com/category/indie`
- `target`: `/14`
### Rule 31
- `title`: `局域网联机`
- `source`:
  - `koyso.to`
- `target`: `/15`
### Rule 32
- `source`:
  - `playzip.com/category/lan`
- `target`: `/15`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n订阅 [最新动作游戏](https://playzip.com/category/action?sort=latest)，其源网址为 `https://playzip.com/category/action?sort=latest`，请参考该 URL 指定部分构成参数，此时路由为 [`/koyso/3/latest`](https://playzip.com/category/action?sort=latest)。\n:::\n\n#### 分类\n\n| 分类                                                   | ID                                |\n| ------------------------------------------------------ | --------------------------------- |\n| [全部游戏](https://playzip.com/)                       | [0](https://rsshub.app/koyso/0)   |\n| [动作游戏](https://playzip.com/category/action)        | [3](https://rsshub.app/koyso/3)   |\n| [冒险游戏](https://playzip.com/category/adventure)     | [5](https://rsshub.app/koyso/5)   |\n| [绅士游戏](https://playzip.com/category/r18)           | [7](https://rsshub.app/koyso/7)   |\n| [射击游戏](https://playzip.com/category/shooting)      | [1](https://rsshub.app/koyso/1)   |\n| [休闲游戏](https://playzip.com/category/casual)        | [2](https://rsshub.app/koyso/2)   |\n| [体育竞速](https://playzip.com/category/sports_racing) | [4](https://rsshub.app/koyso/4)   |\n| [模拟经营](https://playzip.com/category/simulation)    | [6](https://rsshub.app/koyso/6)   |\n| [角色扮演](https://playzip.com/category/rpg)           | [8](https://rsshub.app/koyso/8)   |\n| [策略游戏](https://playzip.com/category/strategy)      | [9](https://rsshub.app/koyso/9)   |\n| [格斗游戏](https://playzip.com/category/fighting)      | [10](https://rsshub.app/koyso/10) |\n| [恐怖游戏](https://playzip.com/category/horror)        | [11](https://rsshub.app/koyso/11) |\n| [即时战略](https://playzip.com/category/rts)           | [12](https://rsshub.app/koyso/12) |\n| [卡牌游戏](https://playzip.com/category/card)          | [13](https://rsshub.app/koyso/13) |\n| [独立游戏](https://playzip.com/category/indie)         | [14](https://rsshub.app/koyso/14) |\n| [局域网联机](https://playzip.com/category/lan)         | [15](https://rsshub.app/koyso/15) |\n\n#### 排序\n\n| 排序                                     | ID                                          |\n| ---------------------------------------- | ------------------------------------------- |\n| [热度](https://playzip.com/?sort=views)  | [views](https://rsshub.app/koyso/0/views)   |\n| [最新](https://playzip.com/?sort=latest) | [latest](https://rsshub.app/koyso/0/latest) |",
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
      "description": "分类，默认为 `0`，即全部，ID 对应下表分类",
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
      ],
      "target": "/0",
      "title": "全部游戏"
    },
    {
      "source": [
        "playzip.com/"
      ],
      "target": "/0"
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
        "playzip.com/category/action"
      ],
      "target": "/3"
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
        "playzip.com/category/adventure"
      ],
      "target": "/5"
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
        "playzip.com/category/r18"
      ],
      "target": "/7"
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
        "playzip.com/category/shooting"
      ],
      "target": "/1"
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
        "playzip.com/category/casual"
      ],
      "target": "/2"
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
        "playzip.com/category/sports_racing"
      ],
      "target": "/4"
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
        "playzip.com/category/simulation"
      ],
      "target": "/6"
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
        "playzip.com/category/rpg"
      ],
      "target": "/8"
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
        "playzip.com/category/strategy"
      ],
      "target": "/9"
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
        "playzip.com/category/fighting"
      ],
      "target": "/10"
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
        "playzip.com/category/horror"
      ],
      "target": "/11"
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
        "playzip.com/category/rts"
      ],
      "target": "/12"
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
        "playzip.com/category/card"
      ],
      "target": "/13"
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
        "playzip.com/category/indie"
      ],
      "target": "/14"
    },
    {
      "source": [
        "koyso.to"
      ],
      "target": "/15",
      "title": "局域网联机"
    },
    {
      "source": [
        "playzip.com/category/lan"
      ],
      "target": "/15"
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
      "siteUrl": "https://playzip.com/?sort=latest",
      "title": "PlayZip - PC Games Free Download - All - Latest",
      "type": "feed",
      "url": "rsshub://koyso"
    },
    {
      "description": "Free pre-installed PC games download. No speed limits, no installation required. - Powered by RSSHub",
      "errorAt": "2026-10-19T08:30:47.752Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "185221927541489664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://playzip.com/?sort=latest",
      "title": "PlayZip - PC Games Free Download - All - Latest",
      "type": "feed",
      "url": "rsshub://koyso/0/latest"
    }
  ],
  "url": "playzip.com",
  "view": 0
}
```
