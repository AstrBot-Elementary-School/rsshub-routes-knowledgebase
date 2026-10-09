# 豆瓣 - 小组帖子更新

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/group/topic/:id/:author?`
- Route Name: `小组帖子更新`
- Example: `/douban/group/topic/309838592`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `other/group-topic.ts`
- Source Module: `_None_`

## Description
订阅主帖正文和源页面首屏回帖。主帖标题或正文改变时产生新 GUID，以供阅读器识别更新。只看楼主使用源站的 author=1 页面。源站回帖按从早到晚排序，因此长帖尾页的新回复尚不在本路由范围内。日期保留源站创建时间，不冒充最后更新时间。

## Parameters
- `id`: 小组帖子 URL 中的数字 ID。
- `author`: {"default": "all", "description": "回帖范围。", "options": [{"label": "全部", "value": "all"}, {"label": "只看楼主", "value": "author"}]}


## Features
- `antiCrawler`: true
- `requireConfig`: [{"description": "需要登录才能查看的帖子请配置本人豆瓣 Cookie。", "name": "DOUBAN_COOKIE", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `www.douban.com/group/topic/:id`
- `target`: `/group/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "订阅主帖正文和源页面首屏回帖。主帖标题或正文改变时产生新 GUID，以供阅读器识别更新。只看楼主使用源站的 author=1 页面。源站回帖按从早到晚排序，因此长帖尾页的新回复尚不在本路由范围内。日期保留源站创建时间，不冒充最后更新时间。",
  "example": "/douban/group/topic/309838592",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "需要登录才能查看的帖子请配置本人豆瓣 Cookie。",
        "name": "DOUBAN_COOKIE",
        "optional": true
      }
    ]
  },
  "heat": 0,
  "location": "other/group-topic.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "小组帖子更新",
  "parameters": {
    "author": {
      "default": "all",
      "description": "回帖范围。",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "只看楼主",
          "value": "author"
        }
      ]
    },
    "id": "小组帖子 URL 中的数字 ID。"
  },
  "path": "/group/topic/:id/:author?",
  "radar": [
    {
      "source": [
        "www.douban.com/group/topic/:id"
      ],
      "target": "/group/topic/:id"
    }
  ],
  "topFeeds": []
}
```
