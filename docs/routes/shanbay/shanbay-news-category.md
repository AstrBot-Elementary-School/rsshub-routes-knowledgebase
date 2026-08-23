# 扇贝 - 今日短文

## Coverage
`index-only`

## Route
- Namespace: `shanbay`
- Namespace Name: `扇贝`
- Route Path: `/shanbay/news/:category?`
- Route Name: `今日短文`
- Example: `/shanbay/news`
- URL: `web.shanbay.com/reading/web-news`
- Language: `_None_`
- Categories: `study`
- Maintainers: `qiwihui`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "aaaaa", "description": "分类 id", "options": [{"label": "全部", "value": "aaaaa"}, {"label": "时文", "value": "aphen"}, {"label": "生活", "value": "brfpia"}, {"label": "商业", "value": "qvyrg"}, {"label": "科技", "value": "exicx"}, {"label": "科普", "value": "phena"}, {"label": "趣闻", "value": "iycfg"}, {"label": "成长", "value": "ytmwg"}, {"label": "科学", "value": "kdpkg"}, {"label": "心理", "value": "zisju"}, {"label": "经济", "value": "hooui"}, {"label": "美文", "value": "ucbyq"}, {"label": "自然", "value": "bvfjmu"}, {"label": "人文", "value": "wnzun"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `web.shanbay.com/reading/web-news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/shanbay/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "qiwihui"
  ],
  "name": "今日短文",
  "parameters": {
    "category": {
      "default": "aaaaa",
      "description": "分类 id",
      "options": [
        {
          "label": "全部",
          "value": "aaaaa"
        },
        {
          "label": "时文",
          "value": "aphen"
        },
        {
          "label": "生活",
          "value": "brfpia"
        },
        {
          "label": "商业",
          "value": "qvyrg"
        },
        {
          "label": "科技",
          "value": "exicx"
        },
        {
          "label": "科普",
          "value": "phena"
        },
        {
          "label": "趣闻",
          "value": "iycfg"
        },
        {
          "label": "成长",
          "value": "ytmwg"
        },
        {
          "label": "科学",
          "value": "kdpkg"
        },
        {
          "label": "心理",
          "value": "zisju"
        },
        {
          "label": "经济",
          "value": "hooui"
        },
        {
          "label": "美文",
          "value": "ucbyq"
        },
        {
          "label": "自然",
          "value": "bvfjmu"
        },
        {
          "label": "人文",
          "value": "wnzun"
        }
      ]
    }
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "web.shanbay.com/reading/web-news"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": [],
  "url": "web.shanbay.com/reading/web-news"
}
```
