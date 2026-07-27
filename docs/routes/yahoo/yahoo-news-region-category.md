# Yahoo - News

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/news/:region/:category?`
- Route Name: `News`
- Example: `/yahoo/news/hk/world`
- URL: `news.yahoo.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `KeiLongW, williamgateszhao`
- Source Location: `news/index.ts`
- Source Module: `_None_`

## Description
`Region`

Support all regions represented by the asterisk (\*) in \*.news.yahoo.com, such as hk/tw/au/ca/fr/malaysia/nz/sg/uk/en(us). For [www.yahoo.com](http://www.yahoo.com), use en or us. Sites with news domains other than \*.news.yahoo.com, such as de.nachrichten.yahoo.com or news.yahoo.co.jp, are not supported.

`Category`

The parsing method for Yahoo Hong Kong and Taiwan is quite unique. All supported categories are as follows

Category for hk.news.yahoo.com (hongkong)

| 全部    | 港聞      | 兩岸國際 | 財經     | 娛樂          | 體育   | 健康   | 親子      | 副刊       |
| ------- | --------- | -------- | -------- | ------------- | ------ | ------ | --------- | ---------- |
| (empty) | hong-kong | world    | business | entertainment | sports | health | parenting | supplement |

Category for tw\.news.yahoo.com (taiwan)

| 全部    | 政治     | 財經    | 娛樂          | 運動   | 社會地方 | 國際  | 生活      | 健康   | 科技       |
| ------- | -------- | ------- | ------------- | ------ | -------- | ----- | --------- | ------ | ---------- |
| (empty) | politics | finance | entertainment | sports | society  | world | lifestyle | health | technology |

Other Yahoo news is fetched from the RSS provided by Yahoo. Please refer to the categories displayed on the pages of \*.news.yahoo.com (for example, "world"), and try to access \*.news.yahoo.com/rss/world to see if it is accessible and contains recent news (some categories exist but are not updated). If it is accessible and has recent news, then that category can be used on the corresponding site. For example, the available categories for news.yahoo.com are as follows

Category for news.yahoo.com (US)

| All     | US | Politics | World | Science | Tech |
| ------- | -- | -------- | ----- | ------- | ---- |
| (empty) | us | politics | world | science | tech |

To give another example, since uk.news.yahoo.com/rss/ukoriginal is accessible and has recent news, /yahoo/news/uk/ukoriginal is a valid RSSHub route.

`author`

For Yahoo Hong Kong and Yahoo Taiwan, please use another "news source" route.

For other Yahoo News, this route's RSS provides the author field. You can use RSSHub's built-in "content filtering" feature. For example, /yahoo-wg/news/tw/technology?filter\_author=Yahoo%20Tech|Engadget can filter out news with authors containing Yahoo Tech or Engadget from Yahoo Taiwan's technology news, which is the Chinese version of Engadget.

## Parameters
- `region`: Region, `hk/tw/au/ca/fr/malaysia/nz/sg/uk/en(us)`, the part represented by the asterisk (*) in *.news.yahoo.com
- `category`: Category, The part represented by the asterisk (*) in .news.yahoo.com/rss/*, region "hk/tw" differs, see the description below


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
  - `news.yahoo.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "`Region`\n\nSupport all regions represented by the asterisk (\\*) in \\*.news.yahoo.com, such as hk/tw/au/ca/fr/malaysia/nz/sg/uk/en(us). For [www.yahoo.com](http://www.yahoo.com), use en or us. Sites with news domains other than \\*.news.yahoo.com, such as de.nachrichten.yahoo.com or news.yahoo.co.jp, are not supported.\n\n`Category`\n\nThe parsing method for Yahoo Hong Kong and Taiwan is quite unique. All supported categories are as follows\n\nCategory for hk.news.yahoo.com (hongkong)\n\n| 全部    | 港聞      | 兩岸國際 | 財經     | 娛樂          | 體育   | 健康   | 親子      | 副刊       |\n| ------- | --------- | -------- | -------- | ------------- | ------ | ------ | --------- | ---------- |\n| (empty) | hong-kong | world    | business | entertainment | sports | health | parenting | supplement |\n\nCategory for tw\\.news.yahoo.com (taiwan)\n\n| 全部    | 政治     | 財經    | 娛樂          | 運動   | 社會地方 | 國際  | 生活      | 健康   | 科技       |\n| ------- | -------- | ------- | ------------- | ------ | -------- | ----- | --------- | ------ | ---------- |\n| (empty) | politics | finance | entertainment | sports | society  | world | lifestyle | health | technology |\n\nOther Yahoo news is fetched from the RSS provided by Yahoo. Please refer to the categories displayed on the pages of \\*.news.yahoo.com (for example, \"world\"), and try to access \\*.news.yahoo.com/rss/world to see if it is accessible and contains recent news (some categories exist but are not updated). If it is accessible and has recent news, then that category can be used on the corresponding site. For example, the available categories for news.yahoo.com are as follows\n\nCategory for news.yahoo.com (US)\n\n| All     | US | Politics | World | Science | Tech |\n| ------- | -- | -------- | ----- | ------- | ---- |\n| (empty) | us | politics | world | science | tech |\n\nTo give another example, since uk.news.yahoo.com/rss/ukoriginal is accessible and has recent news, /yahoo/news/uk/ukoriginal is a valid RSSHub route.\n\n`author`\n\nFor Yahoo Hong Kong and Yahoo Taiwan, please use another \"news source\" route.\n\nFor other Yahoo News, this route's RSS provides the author field. You can use RSSHub's built-in \"content filtering\" feature. For example, /yahoo-wg/news/tw/technology?filter\\_author=Yahoo%20Tech|Engadget can filter out news with authors containing Yahoo Tech or Engadget from Yahoo Taiwan's technology news, which is the Chinese version of Engadget.",
  "example": "/yahoo/news/hk/world",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 317,
  "location": "news/index.ts",
  "maintainers": [
    "KeiLongW",
    "williamgateszhao"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, The part represented by the asterisk (*) in .news.yahoo.com/rss/*, region \"hk/tw\" differs, see the description below",
    "region": "Region, `hk/tw/au/ca/fr/malaysia/nz/sg/uk/en(us)`, the part represented by the asterisk (*) in *.news.yahoo.com"
  },
  "path": "/news/:region/:category?",
  "radar": [
    {
      "source": [
        "news.yahoo.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Yahoo 新聞 HK - 所有類別 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58739494825370652",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://hk.news.yahoo.com/archive",
      "title": "Yahoo 新聞 HK - 所有類別",
      "type": "feed",
      "url": "rsshub://yahoo/news/hk"
    },
    {
      "description": "Yahoo 新聞 TW - 所有類別 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58739494825370651",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://tw.news.yahoo.com/archive",
      "title": "Yahoo 新聞 TW - 所有類別",
      "type": "feed",
      "url": "rsshub://yahoo/news/tw"
    }
  ],
  "url": "news.yahoo.com/",
  "zh": {
    "description": "`区域 Region`\n\n支持所有 *.news.yahoo.com 中*号所代表的区域，例如`hk/tw/au/ca/fr/malaysia/nz/sg/uk/en(us)`, 其中 [www.yahoo.com](http://www.yahoo.com) 用 en 或 us 来表示。不支持新闻域名不为 \\*.news.yahoo.com 的站点如 de.nachrichten.yahoo.com 或 news.yahoo.co.jp。\n\n`分类 Category`\n\n香港和台湾雅虎的读取方式比较特别，所有支持的 category 如下\n\nhk.news.yahoo.com (香港) 所支持的分类\n\n| 全部     | 港聞      | 兩岸國際 | 財經     | 娛樂          | 體育   | 健康   | 親子      | 副刊       |\n| -------- | --------- | -------- | -------- | ------------- | ------ | ------ | --------- | ---------- |\n| （留空） | hong-kong | world    | business | entertainment | sports | health | parenting | supplement |\n\ntw\\.news.yahoo.com (台湾) 所支持的分类\n\n| 全部     | 政治     | 財經    | 娛樂          | 運動   | 社會地方 | 國際  | 生活      | 健康   | 科技       |\n| -------- | -------- | ------- | ------------- | ------ | -------- | ----- | --------- | ------ | ---------- |\n| （留空） | politics | finance | entertainment | sports | society  | world | lifestyle | health | technology |\n\n其他雅虎新闻读取自 yahoo 提供的 RSS, 请根据 \\*.news.yahoo.com 的页面上展示的分类 (例如 world), 尝试 \\*.news.yahoo.com/rss/world 能否访问并且有近期的新闻 (有些分类存在但未更新), 如果可以的话则该分类可以用在相应站点，例如 news.yahoo.com 可用的分类如下\n\nnews.yahoo.com (美国) 所支持的分类\n\n| All    | US | Politics | World | Science | Tech |\n| ------ | -- | -------- | ----- | ------- | ---- |\n| (留空) | us | politics | world | science | tech |\n\n再举例，由于 uk.news.yahoo.com/rss/ukoriginal 可以访问并且有较新的新闻，所以 /yahoo/news/uk/ukoriginal 是一个有效的 RSSHub 路由。\n\n`作者 author`\n\n对于香港和台湾雅虎，请使用另一个 \"新聞來源\" 路由。\n\n对于其他雅虎新闻，本路由的 RSS 中提供了 author 字段，可使用 RSSHub 的内置 \"内容过滤\" 功能，例如 /yahoo-wg/news/tw/technology?filter\\_author=Yahoo%20Tech|Engadget 可从台湾雅虎的科技新闻中过滤出作者名称中包含 Yahoo Tech 或者 Engadget 的新闻，即瘾科技中文版。",
    "name": "新闻"
  }
}
```
