# 人人影视 - 影视资讯

## Coverage
`index-only`

## Route
- Namespace: `yyets`
- Namespace Name: `人人影视`
- Route Path: `/yyets/article/:type?`
- Route Name: `影视资讯`
- Example: `/yyets/article`
- URL: `yysub.net`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `wb121017405`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 全部 | 影视资讯 | 收视快报 | 人人影评  | 人人剧评  | 新剧评测    | 片单推荐 |
| ---- | -------- | -------- | --------- | --------- | ----------- | -------- |
|      | news     | report   | m\_review | t\_review | new\_review | recom    |

## Parameters
- `type`: {"default": "all", "description": "类型", "options": [{"label": "全部", "value": "all"}, {"label": "影视资讯", "value": "news"}, {"label": "收视快报", "value": "report"}, {"label": "人人影评", "value": "m_review"}, {"label": "人人剧评", "value": "t_review"}, {"label": "新剧评测", "value": "new_review"}, {"label": "片单推荐", "value": "recom"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "description": "| 全部 | 影视资讯 | 收视快报 | 人人影评  | 人人剧评  | 新剧评测    | 片单推荐 |\n| ---- | -------- | -------- | --------- | --------- | ----------- | -------- |\n|      | news     | report   | m\\_review | t\\_review | new\\_review | recom    |",
  "example": "/yyets/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2685,
  "location": "article.ts",
  "maintainers": [
    "wb121017405"
  ],
  "name": "影视资讯",
  "parameters": {
    "type": {
      "default": "all",
      "description": "类型",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "影视资讯",
          "value": "news"
        },
        {
          "label": "收视快报",
          "value": "report"
        },
        {
          "label": "人人影评",
          "value": "m_review"
        },
        {
          "label": "人人剧评",
          "value": "t_review"
        },
        {
          "label": "新剧评测",
          "value": "new_review"
        },
        {
          "label": "片单推荐",
          "value": "recom"
        }
      ]
    }
  },
  "path": "/article/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "ZiMuZu字幕组网站,www.zimuzu.tv是一群由海外留学生于2015年1月1号组建的字幕组分享网站,以翻译最新最快影 视剧为兴趣爱好,并且免费分享给广大网友和爱好者，欢迎大家的加入 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72485769266542592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yysub.net/article?type=all",
      "title": "资讯列表 - 人人影视",
      "type": "feed",
      "url": "rsshub://yyets/article/all"
    },
    {
      "description": "ZiMuZu字幕组网站,www.zimuzu.tv是一群由海外留学生于2015年1月1号组建的字幕组分享网站,以翻译最新最快影 视剧为兴趣爱好,并且免费分享给广大网友和爱好者，欢迎大家的加入 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72568323043948544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yysub.net/article?type=recom",
      "title": "片单推荐 - 人人影视",
      "type": "feed",
      "url": "rsshub://yyets/article/recom"
    }
  ],
  "view": 0
}
```
