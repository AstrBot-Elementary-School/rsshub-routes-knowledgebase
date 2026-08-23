# 快媒体 - 首页更新 / 具体栏目更新

## Coverage
`index-only`

## Route
- Namespace: `kuai`
- Namespace Name: `快媒体`
- Route Path: `/kuai/:category?`
- Route Name: `首页更新 / 具体栏目更新`
- Example: `/kuai/stock_us`
- URL: `www.kuai.media`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `salviox`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "栏目，留空为首页", "options": [{"label": "星相", "value": "astrology"}, {"label": "加国", "value": "canada"}, {"label": "育儿", "value": "children"}, {"label": "大陆", "value": "china"}, {"label": "华人", "value": "chinese"}, {"label": "教育", "value": "edu"}, {"label": "娱乐", "value": "ent"}, {"label": "时尚", "value": "fashion"}, {"label": "财经", "value": "finance"}, {"label": "美食", "value": "food"}, {"label": "搞笑", "value": "funny"}, {"label": "养生", "value": "health"}, {"label": "历史", "value": "history"}, {"label": "港澳", "value": "hk_macau"}, {"label": "移民", "value": "immigration"}, {"label": "国际", "value": "in"}, {"label": "科技", "value": "it"}, {"label": "情感", "value": "love"}, {"label": "军事", "value": "mil"}, {"label": "杂闻", "value": "misc"}, {"label": "宠物", "value": "pet"}, {"label": "摄影", "value": "photo"}, {"label": "政坛", "value": "politics"}, {"label": "体育", "value": "sport"}, {"label": "美股", "value": "stock_us"}, {"label": "台湾", "value": "taiwan"}, {"label": "旅游", "value": "travel"}, {"label": "美国", "value": "usa"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.kuai.media/news/:category/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/kuai/stock_us",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "salviox"
  ],
  "name": "首页更新 / 具体栏目更新",
  "parameters": {
    "category": {
      "description": "栏目，留空为首页",
      "options": [
        {
          "label": "星相",
          "value": "astrology"
        },
        {
          "label": "加国",
          "value": "canada"
        },
        {
          "label": "育儿",
          "value": "children"
        },
        {
          "label": "大陆",
          "value": "china"
        },
        {
          "label": "华人",
          "value": "chinese"
        },
        {
          "label": "教育",
          "value": "edu"
        },
        {
          "label": "娱乐",
          "value": "ent"
        },
        {
          "label": "时尚",
          "value": "fashion"
        },
        {
          "label": "财经",
          "value": "finance"
        },
        {
          "label": "美食",
          "value": "food"
        },
        {
          "label": "搞笑",
          "value": "funny"
        },
        {
          "label": "养生",
          "value": "health"
        },
        {
          "label": "历史",
          "value": "history"
        },
        {
          "label": "港澳",
          "value": "hk_macau"
        },
        {
          "label": "移民",
          "value": "immigration"
        },
        {
          "label": "国际",
          "value": "in"
        },
        {
          "label": "科技",
          "value": "it"
        },
        {
          "label": "情感",
          "value": "love"
        },
        {
          "label": "军事",
          "value": "mil"
        },
        {
          "label": "杂闻",
          "value": "misc"
        },
        {
          "label": "宠物",
          "value": "pet"
        },
        {
          "label": "摄影",
          "value": "photo"
        },
        {
          "label": "政坛",
          "value": "politics"
        },
        {
          "label": "体育",
          "value": "sport"
        },
        {
          "label": "美股",
          "value": "stock_us"
        },
        {
          "label": "台湾",
          "value": "taiwan"
        },
        {
          "label": "旅游",
          "value": "travel"
        },
        {
          "label": "美国",
          "value": "usa"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.kuai.media/news/:category/"
      ],
      "target": "/:category"
    }
  ],
  "topFeeds": [],
  "url": "www.kuai.media"
}
```
