# 北京邮电大学 - 校园新闻

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/bupt/news`
- Route Name: `校园新闻`
- Example: `/bupt/news`
- URL: `bupt.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `wzekin`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
由于需要登陆 `https://webapp.bupt.edu.cn/wap/login.html?redirect=http://` 后的 Cookie 值，所以只能自建，详情见部署页面的配置模块

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "登陆 `https://webapp.bupt.edu.cn/wap/login.html?redirect=http://` 后的 Cookie 值", "name": "BUPT_PORTAL_COOKIE"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "由于需要登陆 `https://webapp.bupt.edu.cn/wap/login.html?redirect=http://` 后的 Cookie 值，所以只能自建，详情见部署页面的配置模块",
  "example": "/bupt/news",
  "features": {
    "requireConfig": [
      {
        "description": "登陆 `https://webapp.bupt.edu.cn/wap/login.html?redirect=http://` 后的 Cookie 值",
        "name": "BUPT_PORTAL_COOKIE"
      }
    ]
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "wzekin"
  ],
  "name": "校园新闻",
  "path": "/news",
  "topFeeds": []
}
```
