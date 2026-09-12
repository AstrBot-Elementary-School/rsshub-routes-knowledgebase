# 线报酷 - 线板酷

## Coverage
`index-only`

## Route
- Namespace: `xianbao`
- Namespace Name: `线报酷`
- Route Path: `/xianbao/:category?`
- Route Name: `线板酷`
- Example: `/xianbao`
- URL: `new.xianbao.fun`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `nashi23`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类         | id             |
| ------------ | -------------- |
| 最新         | latest         |
| 赚客吧       | zuankeba       |
| 赚客吧热帖   | zuankeba-hot   |
| 新赚吧       | xinzuanba      |
| 新赚吧热帖   | xinzuanba-hot  |
| 微博         | weibo          |
| 微博热帖     | weibo-hot      |
| 豆瓣线报     | douban         |
| 豆瓣热帖     | douban-hot     |
| 酷安         | kuan           |
| 小嘀咕       | xiaodigu       |
| 葫芦侠       | huluxia        |
| 小刀娱乐网   | xiadao         |
| 技术 QQ 网   | qqjishu        |
| YYOK 大全    | yyok           |
| 活动资讯网   | huodong        |
| 免费赚钱中心 | mianfei        |
| 一小时       | yixiaoshi      |
| 三小时       | sanxiaoshi     |
| 六小时       | liuxiaoshi     |
| 十二小时     | shierxiaoshi   |
| 二十四小时   | ershisixiaoshi |
| 四十八小时   | sishibaxiaoshi |
| 今天         | jintian        |
| 昨天         | zuotian        |
| 前天         | qiantian       |
| 三天         | santian        |
| 五天         | wutian         |
| 七天         | qitian         |
| 十五天       | shiwutian      |

## Parameters
- `category`: 类别id，默认为：latest


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
  - `new.xianbao.fun`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 分类         | id             |\n| ------------ | -------------- |\n| 最新         | latest         |\n| 赚客吧       | zuankeba       |\n| 赚客吧热帖   | zuankeba-hot   |\n| 新赚吧       | xinzuanba      |\n| 新赚吧热帖   | xinzuanba-hot  |\n| 微博         | weibo          |\n| 微博热帖     | weibo-hot      |\n| 豆瓣线报     | douban         |\n| 豆瓣热帖     | douban-hot     |\n| 酷安         | kuan           |\n| 小嘀咕       | xiaodigu       |\n| 葫芦侠       | huluxia        |\n| 小刀娱乐网   | xiadao         |\n| 技术 QQ 网   | qqjishu        |\n| YYOK 大全    | yyok           |\n| 活动资讯网   | huodong        |\n| 免费赚钱中心 | mianfei        |\n| 一小时       | yixiaoshi      |\n| 三小时       | sanxiaoshi     |\n| 六小时       | liuxiaoshi     |\n| 十二小时     | shierxiaoshi   |\n| 二十四小时   | ershisixiaoshi |\n| 四十八小时   | sishibaxiaoshi |\n| 今天         | jintian        |\n| 昨天         | zuotian        |\n| 前天         | qiantian       |\n| 三天         | santian        |\n| 五天         | wutian         |\n| 七天         | qitian         |\n| 十五天       | shiwutian      |",
  "example": "/xianbao",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 435,
  "location": "index.ts",
  "maintainers": [
    "nashi23"
  ],
  "name": "线板酷",
  "parameters": {
    "category": "类别id，默认为：latest"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "new.xianbao.fun"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "线板酷-最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57341806801267712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://new.xianbao.fun/",
      "title": "线板酷-最新",
      "type": "feed",
      "url": "rsshub://xianbao"
    },
    {
      "description": "线板酷-赚客吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67550789955228672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://new.xianbao.fun/category-zuankeba",
      "title": "线板酷-赚客吧",
      "type": "feed",
      "url": "rsshub://xianbao/zuankeba"
    }
  ],
  "url": "new.xianbao.fun"
}
```
