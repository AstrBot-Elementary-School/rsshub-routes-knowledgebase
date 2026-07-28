# 快科技 - 分类

## Coverage
`index-only`

## Route
- Namespace: `mydrivers`
- Namespace Name: `快科技`
- Route Path: `/mydrivers/:category{.+}?`
- Route Name: `分类`
- Example: `/mydrivers/bcid/801`
- URL: `m.mydrivers.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `kt286, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
#### 板块

| 电脑     | 手机     | 汽车     | 业界     | 游戏     |
| -------- | -------- | -------- | -------- | -------- |
| bcid/801 | bcid/802 | bcid/807 | bcid/803 | bcid/806 |

#### 话题

| 科学     | 排行     | 评测     | 一图     |
| -------- | -------- | -------- | -------- |
| tid/1000 | tid/1001 | tid/1002 | tid/1003 |

#### 品牌

| 安卓     | 阿里     | 微软    | 百度    | PS5       | Xbox     | 华为     |
| -------- | -------- | ------- | ------- | --------- | -------- | -------- |
| icid/121 | icid/270 | icid/90 | icid/67 | icid/6950 | icid/194 | icid/136 |

| 小米      | VIVO     | 三星     | 魅族     | 一加     | 比亚迪   | 小鹏      |
| --------- | -------- | -------- | -------- | -------- | -------- | --------- |
| icid/9355 | icid/288 | icid/154 | icid/140 | icid/385 | icid/770 | icid/7259 |

| 蔚来      | 理想       | 奔驰     | 宝马     | 大众     |
| --------- | ---------- | -------- | -------- | -------- |
| icid/7318 | icid/12947 | icid/429 | icid/461 | icid/481 |

## Parameters
- `category`: 分类，见下表，默认为最新


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.mydrivers.com/`
- `target`: `/zhibo`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "#### 板块\n\n| 电脑     | 手机     | 汽车     | 业界     | 游戏     |\n| -------- | -------- | -------- | -------- | -------- |\n| bcid/801 | bcid/802 | bcid/807 | bcid/803 | bcid/806 |\n\n#### 话题\n\n| 科学     | 排行     | 评测     | 一图     |\n| -------- | -------- | -------- | -------- |\n| tid/1000 | tid/1001 | tid/1002 | tid/1003 |\n\n#### 品牌\n\n| 安卓     | 阿里     | 微软    | 百度    | PS5       | Xbox     | 华为     |\n| -------- | -------- | ------- | ------- | --------- | -------- | -------- |\n| icid/121 | icid/270 | icid/90 | icid/67 | icid/6950 | icid/194 | icid/136 |\n\n| 小米      | VIVO     | 三星     | 魅族     | 一加     | 比亚迪   | 小鹏      |\n| --------- | -------- | -------- | -------- | -------- | -------- | --------- |\n| icid/9355 | icid/288 | icid/154 | icid/140 | icid/385 | icid/770 | icid/7259 |\n\n| 蔚来      | 理想       | 奔驰     | 宝马     | 大众     |\n| --------- | ---------- | -------- | -------- | -------- |\n| icid/7318 | icid/12947 | icid/429 | icid/461 | icid/481 |",
  "example": "/mydrivers/bcid/801",
  "heat": 72,
  "location": "index.tsx",
  "maintainers": [
    "kt286",
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为最新"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "m.mydrivers.com/"
      ],
      "target": "/zhibo"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "手机驱动之家是驱动之家的手机门户网站，为亿万用户打造一个手机联通世界的超级平台，提供24小时全面及时的中文IT资讯。手机驱动之家触屏版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61784377765250050",
      "image": "https://11.mydrivers.com/m/images/v1/kkj_hearlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mydrivers.com/newsclass.aspx?ac=new",
      "title": "快科技 - 最新",
      "type": "feed",
      "url": "rsshub://mydrivers"
    },
    {
      "description": "手机驱动之家是驱动之家的手机门户网站，为亿万用户打造一个手机联通世界的超级平台，提供24小时全面及时的中文IT资讯。手机驱动之家触屏版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74113562646678532",
      "image": "https://11.mydrivers.com/m/images/v1/kkj_hearlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mydrivers.com/newsclass.aspx?ac=new",
      "title": "快科技 - 最新",
      "type": "feed",
      "url": "rsshub://mydrivers/new"
    }
  ]
}
```
