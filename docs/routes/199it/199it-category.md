# 199it - 资讯

## Coverage
`index-only`

## Route
- Namespace: `199it`
- Namespace Name: `199it`
- Route Path: `/199it/:category{.+}?`
- Route Name: `资讯`
- Example: `/199it/newly`
- URL: `199it.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `salviox, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
若订阅 [研究报告](https://www.199it.com/archives/category/report)，网址为 `https://www.199it.com/archives/category/report`，请截取 `https://www.199it.com/archives/category/report` 到末尾的部分 `archives/category/report` 作为 `category` 参数填入，此时目标路由为 [`/199it/archives/category/report`](https://rsshub.app/199it/archives/category/report)。
:::

<details>
  <summary>更多分类</summary>

| 分类                                                                            | ID                                                                                                      |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| [报告](http://www.199it.com/archives/category/report)                           | [archives/category/report](https://rsshub.app/199it/archives/category/report)                           |
| [新兴产业](http://www.199it.com/archives/category/emerging)                     | [archives/category/emerging](https://rsshub.app/199it/archives/category/emerging)                       |
| [金融科技](http://www.199it.com/archives/category/fintech)                      | [archives/category/fintech](https://rsshub.app/199it/archives/category/fintech)                         |
| [共享经济](http://www.199it.com/archives/category/sharingeconomy)               | [archives/category/sharingeconomy](https://rsshub.app/199it/archives/category/sharingeconomy)           |
| [移动互联网](http://www.199it.com/archives/category/mobile-internet)            | [archives/category/mobile-internet](https://rsshub.app/199it/archives/category/mobile-internet)         |
| [电子商务](http://www.199it.com/archives/category/electronic-commerce)          | [archives/category/electronic-commerce](https://rsshub.app/199it/archives/category/electronic-commerce) |
| [社交网络](http://www.199it.com/archives/category/social-network)               | [archives/category/social-network](https://rsshub.app/199it/archives/category/social-network)           |
| [网络广告](http://www.199it.com/archives/category/advertising)                  | [archives/category/advertising](https://rsshub.app/199it/archives/category/advertising)                 |
| [投资 & 经济，互联网金融](http://www.199it.com/archives/category/economic-data) | [archives/category/economic-data](https://rsshub.app/199it/archives/category/economic-data)             |
| [服务](http://www.199it.com/archives/category/service)                          | [archives/category/service](https://rsshub.app/199it/archives/category/service)                         |
| [网络服务行业](http://www.199it.com/archives/category/dataindustry)             | [archives/category/dataindustry](https://rsshub.app/199it/archives/category/dataindustry)               |
| [用户研究](http://www.199it.com/archives/category/internet-users)               | [archives/category/internet-users](https://rsshub.app/199it/archives/category/internet-users)           |

</details>

## Parameters
- `category`: {"description": "分类，默认为 `newly`，即最新，可在对应分类页 URL 中找到", "options": [{"label": "最新", "value": "newly"}, {"label": "报告", "value": "archives/category/report"}, {"label": "新兴产业", "value": "archives/category/emerging"}, {"label": "金融科技", "value": "archives/category/fintech"}, {"label": "共享经济", "value": "archives/category/sharingeconomy"}, {"label": "移动互联网", "value": "archives/category/mobile-internet"}, {"label": "电子商务", "value": "archives/category/electronic-commerce"}, {"label": "社交网络", "value": "archives/category/social-network"}, {"label": "网络广告", "value": "archives/category/advertising"}, {"label": "投资&amp;经济，互联网金融", "value": "archives/category/economic-data"}, {"label": "服务", "value": "archives/category/service"}, {"label": "网络服务行业", "value": "archives/category/dataindustry"}, {"label": "用户研究", "value": "archives/category/internet-users"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.199it.com/:category`
### Rule 2
- `title`: `最新`
- `source`:
  - `www.199it.com/newly`
- `target`: `/newly`
### Rule 3
- `title`: `报告`
- `source`:
  - `www.199it.com/archives/category/report`
- `target`: `/archives/category/report`
### Rule 4
- `title`: `新兴产业`
- `source`:
  - `www.199it.com/archives/category/emerging`
- `target`: `/archives/category/emerging`
### Rule 5
- `title`: `金融科技`
- `source`:
  - `www.199it.com/archives/category/fintech`
- `target`: `/archives/category/fintech`
### Rule 6
- `title`: `共享经济`
- `source`:
  - `www.199it.com/archives/category/sharingeconomy`
- `target`: `/archives/category/sharingeconomy`
### Rule 7
- `title`: `移动互联网`
- `source`:
  - `www.199it.com/archives/category/mobile-internet`
- `target`: `/archives/category/mobile-internet`
### Rule 8
- `title`: `电子商务`
- `source`:
  - `www.199it.com/archives/category/electronic-commerce`
- `target`: `/archives/category/electronic-commerce`
### Rule 9
- `title`: `社交网络`
- `source`:
  - `www.199it.com/archives/category/social-network`
- `target`: `/archives/category/social-network`
### Rule 10
- `title`: `网络广告`
- `source`:
  - `www.199it.com/archives/category/advertising`
- `target`: `/archives/category/advertising`
### Rule 11
- `title`: `投资&amp;经济，互联网金融`
- `source`:
  - `www.199it.com/archives/category/economic-data`
- `target`: `/archives/category/economic-data`
### Rule 12
- `title`: `服务`
- `source`:
  - `www.199it.com/archives/category/service`
- `target`: `/archives/category/service`
### Rule 13
- `title`: `网络服务行业`
- `source`:
  - `www.199it.com/archives/category/dataindustry`
- `target`: `/archives/category/dataindustry`
### Rule 14
- `title`: `用户研究`
- `source`:
  - `www.199it.com/archives/category/internet-users`
- `target`: `/archives/category/internet-users`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [研究报告](https://www.199it.com/archives/category/report)，网址为 `https://www.199it.com/archives/category/report`，请截取 `https://www.199it.com/archives/category/report` 到末尾的部分 `archives/category/report` 作为 `category` 参数填入，此时目标路由为 [`/199it/archives/category/report`](https://rsshub.app/199it/archives/category/report)。\n:::\n\n<details>\n  <summary>更多分类</summary>\n\n| 分类                                                                            | ID                                                                                                      |\n| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |\n| [报告](http://www.199it.com/archives/category/report)                           | [archives/category/report](https://rsshub.app/199it/archives/category/report)                           |\n| [新兴产业](http://www.199it.com/archives/category/emerging)                     | [archives/category/emerging](https://rsshub.app/199it/archives/category/emerging)                       |\n| [金融科技](http://www.199it.com/archives/category/fintech)                      | [archives/category/fintech](https://rsshub.app/199it/archives/category/fintech)                         |\n| [共享经济](http://www.199it.com/archives/category/sharingeconomy)               | [archives/category/sharingeconomy](https://rsshub.app/199it/archives/category/sharingeconomy)           |\n| [移动互联网](http://www.199it.com/archives/category/mobile-internet)            | [archives/category/mobile-internet](https://rsshub.app/199it/archives/category/mobile-internet)         |\n| [电子商务](http://www.199it.com/archives/category/electronic-commerce)          | [archives/category/electronic-commerce](https://rsshub.app/199it/archives/category/electronic-commerce) |\n| [社交网络](http://www.199it.com/archives/category/social-network)               | [archives/category/social-network](https://rsshub.app/199it/archives/category/social-network)           |\n| [网络广告](http://www.199it.com/archives/category/advertising)                  | [archives/category/advertising](https://rsshub.app/199it/archives/category/advertising)                 |\n| [投资 & 经济，互联网金融](http://www.199it.com/archives/category/economic-data) | [archives/category/economic-data](https://rsshub.app/199it/archives/category/economic-data)             |\n| [服务](http://www.199it.com/archives/category/service)                          | [archives/category/service](https://rsshub.app/199it/archives/category/service)                         |\n| [网络服务行业](http://www.199it.com/archives/category/dataindustry)             | [archives/category/dataindustry](https://rsshub.app/199it/archives/category/dataindustry)               |\n| [用户研究](http://www.199it.com/archives/category/internet-users)               | [archives/category/internet-users](https://rsshub.app/199it/archives/category/internet-users)           |\n\n</details>",
  "example": "/199it/newly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 38,
  "location": "index.tsx",
  "maintainers": [
    "salviox",
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "category": {
      "description": "分类，默认为 `newly`，即最新，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "最新",
          "value": "newly"
        },
        {
          "label": "报告",
          "value": "archives/category/report"
        },
        {
          "label": "新兴产业",
          "value": "archives/category/emerging"
        },
        {
          "label": "金融科技",
          "value": "archives/category/fintech"
        },
        {
          "label": "共享经济",
          "value": "archives/category/sharingeconomy"
        },
        {
          "label": "移动互联网",
          "value": "archives/category/mobile-internet"
        },
        {
          "label": "电子商务",
          "value": "archives/category/electronic-commerce"
        },
        {
          "label": "社交网络",
          "value": "archives/category/social-network"
        },
        {
          "label": "网络广告",
          "value": "archives/category/advertising"
        },
        {
          "label": "投资&amp;经济，互联网金融",
          "value": "archives/category/economic-data"
        },
        {
          "label": "服务",
          "value": "archives/category/service"
        },
        {
          "label": "网络服务行业",
          "value": "archives/category/dataindustry"
        },
        {
          "label": "用户研究",
          "value": "archives/category/internet-users"
        }
      ]
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.199it.com/:category"
      ]
    },
    {
      "source": [
        "www.199it.com/newly"
      ],
      "target": "/newly",
      "title": "最新"
    },
    {
      "source": [
        "www.199it.com/archives/category/report"
      ],
      "target": "/archives/category/report",
      "title": "报告"
    },
    {
      "source": [
        "www.199it.com/archives/category/emerging"
      ],
      "target": "/archives/category/emerging",
      "title": "新兴产业"
    },
    {
      "source": [
        "www.199it.com/archives/category/fintech"
      ],
      "target": "/archives/category/fintech",
      "title": "金融科技"
    },
    {
      "source": [
        "www.199it.com/archives/category/sharingeconomy"
      ],
      "target": "/archives/category/sharingeconomy",
      "title": "共享经济"
    },
    {
      "source": [
        "www.199it.com/archives/category/mobile-internet"
      ],
      "target": "/archives/category/mobile-internet",
      "title": "移动互联网"
    },
    {
      "source": [
        "www.199it.com/archives/category/electronic-commerce"
      ],
      "target": "/archives/category/electronic-commerce",
      "title": "电子商务"
    },
    {
      "source": [
        "www.199it.com/archives/category/social-network"
      ],
      "target": "/archives/category/social-network",
      "title": "社交网络"
    },
    {
      "source": [
        "www.199it.com/archives/category/advertising"
      ],
      "target": "/archives/category/advertising",
      "title": "网络广告"
    },
    {
      "source": [
        "www.199it.com/archives/category/economic-data"
      ],
      "target": "/archives/category/economic-data",
      "title": "投资&amp;经济，互联网金融"
    },
    {
      "source": [
        "www.199it.com/archives/category/service"
      ],
      "target": "/archives/category/service",
      "title": "服务"
    },
    {
      "source": [
        "www.199it.com/archives/category/dataindustry"
      ],
      "target": "/archives/category/dataindustry",
      "title": "网络服务行业"
    },
    {
      "source": [
        "www.199it.com/archives/category/internet-users"
      ],
      "target": "/archives/category/internet-users",
      "title": "用户研究"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中文互联网数据研究资讯中心是一个专注于互联网数据研究、互联网数据调研、IT数据分析、互联网咨询机构数据、互联网权威机构，并致力为中国互联网研究和咨询及IT行业数据专业人员和决策者提供一个数据共享平台。这里是最新 | - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "109510016354217993",
      "image": "//www.199it.com/199itlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.199it.com/newly",
      "title": "最新 | 互联网数据资讯网-199IT | 中文互联网数据研究资讯中心-199IT",
      "type": "feed",
      "url": "rsshub://199it"
    },
    {
      "description": "中文互联网数据研究资讯中心是一个专注于互联网数据研究、互联网数据调研、IT数据分析、互联网咨询机构数据、互联网权威机构，并致力为中国互联网研究和咨询及IT行业数据专业人员和决策者提供一个数据共享平台。这里是最新 | - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "132133310851759104",
      "image": "//www.199it.com/199itlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.199it.com/newly",
      "title": "最新 | 互联网数据资讯网-199IT | 中文互联网数据研究资讯中心-199IT",
      "type": "feed",
      "url": "rsshub://199it/newly"
    }
  ],
  "url": "199it.com",
  "view": 0
}
```
