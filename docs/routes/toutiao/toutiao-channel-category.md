# 今日头条 - 频道

## Coverage
`index-only`

## Route
- Namespace: `toutiao`
- Namespace Name: `今日头条`
- Route Path: `/toutiao/channel/:category`
- Route Name: `频道`
- Example: `/toutiao/channel/news_tech`
- URL: `www.toutiao.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "频道", "options": [{"label": "推荐", "value": "recommend"}, {"label": "热点", "value": "news_hot"}, {"label": "科技", "value": "news_tech"}, {"label": "财经", "value": "news_finance"}, {"label": "娱乐", "value": "news_entertainment"}, {"label": "体育", "value": "news_sports"}, {"label": "国际", "value": "news_world"}, {"label": "军事", "value": "news_military"}, {"label": "历史", "value": "news_history"}, {"label": "美文", "value": "news_essay"}, {"label": "美食", "value": "news_food"}, {"label": "旅游", "value": "news_travel"}, {"label": "时尚", "value": "news_fashion"}, {"label": "游戏", "value": "news_game"}, {"label": "育儿", "value": "news_baby"}, {"label": "养生", "value": "news_regimen"}, {"label": "数码", "value": "digital"}, {"label": "视频", "value": "video"}]}


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.toutiao.com/ch/:category`
### Rule 2
- `title`: `推荐`
- `source`:
  - `www.toutiao.com/`
- `target`: `/channel/recommend`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/toutiao/channel/news_tech",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "channel.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "频道",
  "parameters": {
    "category": {
      "description": "频道",
      "options": [
        {
          "label": "推荐",
          "value": "recommend"
        },
        {
          "label": "热点",
          "value": "news_hot"
        },
        {
          "label": "科技",
          "value": "news_tech"
        },
        {
          "label": "财经",
          "value": "news_finance"
        },
        {
          "label": "娱乐",
          "value": "news_entertainment"
        },
        {
          "label": "体育",
          "value": "news_sports"
        },
        {
          "label": "国际",
          "value": "news_world"
        },
        {
          "label": "军事",
          "value": "news_military"
        },
        {
          "label": "历史",
          "value": "news_history"
        },
        {
          "label": "美文",
          "value": "news_essay"
        },
        {
          "label": "美食",
          "value": "news_food"
        },
        {
          "label": "旅游",
          "value": "news_travel"
        },
        {
          "label": "时尚",
          "value": "news_fashion"
        },
        {
          "label": "游戏",
          "value": "news_game"
        },
        {
          "label": "育儿",
          "value": "news_baby"
        },
        {
          "label": "养生",
          "value": "news_regimen"
        },
        {
          "label": "数码",
          "value": "digital"
        },
        {
          "label": "视频",
          "value": "video"
        }
      ]
    }
  },
  "path": "/channel/:category",
  "radar": [
    {
      "source": [
        "www.toutiao.com/ch/:category"
      ]
    },
    {
      "source": [
        "www.toutiao.com/"
      ],
      "target": "/channel/recommend",
      "title": "推荐"
    }
  ],
  "topFeeds": []
}
```
