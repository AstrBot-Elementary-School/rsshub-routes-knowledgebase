# 站酷 - 作品总榜单

## Coverage
`index-only`

## Route
- Namespace: `zcool`
- Namespace Name: `站酷`
- Route Path: `/zcool/top/:type`
- Route Name: `作品总榜单`
- Example: `/zcool/top/design`
- URL: `www.zcool.com.cn`
- Language: `_None_`
- Categories: `design, popular`
- Maintainers: `yuuow`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "推荐类型", "options": [{"label": "作品榜单", "value": "design"}, {"label": "文章榜单", "value": "article"}]}


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
    "design",
    "popular"
  ],
  "example": "/zcool/top/design",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1928,
  "location": "top.ts",
  "maintainers": [
    "yuuow"
  ],
  "name": "作品总榜单",
  "parameters": {
    "type": {
      "description": "推荐类型",
      "options": [
        {
          "label": "作品榜单",
          "value": "design"
        },
        {
          "label": "文章榜单",
          "value": "article"
        }
      ]
    }
  },
  "path": "/top/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "站酷总榜设计_创意作品榜_站酷ZCOOL,中国设计师互动平台.深耕设计领域十八年,站酷聚集了1800万设计师_摄影师_插画师_艺术家_创意人_设计创意群体中具有较高的影响力与号召力. - Powered by RSSHub",
      "errorAt": "2026-06-15T20:02:12.999Z",
      "errorMessage": "Unexpected end of JSON input\nUnexpected end of JSON input\nAuthentication failed. Access denied.\n/zcool/top/design\n502 \nUnexpected end of JSON input\nMISCONF Redis is configured to save RDB snapshots, but it's currently unable to persist to disk. Commands that may modify the data set are disabled, because this instance is configured to report errors during writes if RDB snapshotting fails (stop-writes-on-bgsave-error option). Please check the Redis logs for details about the RDB error.\nUnexpected end of JSON input\nUnexpected end of JSON input\nUnexpected end of JSON input\nUnexpected end of JSON input\nUnexpected end of JSON input\nUnexpected end of JSON input\nAuthentication failed. Access denied.\n/zcool/top/design\n503 \nUnexpected end of JSON input\n",
      "id": "43301307059705856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zcool.com.cn/top/index.do",
      "title": "站酷总榜设计_创意作品榜_第476期-站酷ZCOOL",
      "type": "feed",
      "url": "rsshub://zcool/top/design"
    },
    {
      "description": "站酷总榜设计_创意文章榜_站酷ZCOOL,中国设计师互动平台.耕设计领域十八年,站酷聚集了1800万设计师_摄影师_插画师_艺术家_创意人_设计创意群体中具有较高的影响力与号召力. - Powered by RSSHub",
      "errorAt": "2026-06-15T21:46:33.957Z",
      "errorMessage": "Unexpected end of JSON input\nUnexpected end of JSON input\nAuthentication failed. Access denied.\n/zcool/top/article\nUnexpected end of JSON input\nUnexpected end of JSON input\nAuthentication failed. Access denied.\n/zcool/top/article\nUnexpected end of JSON input\n",
      "id": "45447315970816000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zcool.com.cn/top/article.do?rankType=8",
      "title": "站酷总榜设计_创意文章榜_第476期-站酷ZCOOL",
      "type": "feed",
      "url": "rsshub://zcool/top/article"
    }
  ],
  "view": 2
}
```
