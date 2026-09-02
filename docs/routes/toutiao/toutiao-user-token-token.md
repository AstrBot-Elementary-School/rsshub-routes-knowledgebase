# 今日头条 - 头条主页

## Coverage
`index-only`

## Route
- Namespace: `toutiao`
- Namespace Name: `今日头条`
- Route Path: `/toutiao/user/token/:token`
- Route Name: `头条主页`
- Example: `/toutiao/user/token/MS4wLjABAAAApOspM7AnWqplD9FIBGnhJRfUjFT_msD1KZMfNPBZa-c`
- URL: `www.toutiao.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `token`: 用户 token，可在用户主页 URL 找到


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.toutiao.com/c/user/token/:token`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/toutiao/user/token/MS4wLjABAAAApOspM7AnWqplD9FIBGnhJRfUjFT_msD1KZMfNPBZa-c",
  "features": {
    "antiCrawler": true
  },
  "heat": 381,
  "location": "user.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "头条主页",
  "parameters": {
    "token": "用户 token，可在用户主页 URL 找到"
  },
  "path": "/user/token/:token",
  "radar": [
    {
      "source": [
        "www.toutiao.com/c/user/token/:token"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "🌈资深程序猿一名 🏠分享AI知识，以及好用的软件推荐 🙊一个说真话的培训师 软件都在 抖音粉丝群 承接各类培训服务 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84064321853358080",
      "image": "https://sf6-cdn-tos.bdxiguastatic.com/img/user-avatar/b8b6c80c419c2743cabb64c20b65271b~300x300.image",
      "ownerUserId": null,
      "siteUrl": "https://www.toutiao.com/c/user/token/MS4wLjABAAAAuaHJxshSggAbn-LFL6O0BjzOrTlpHxUDLxcvCP73__GXaavP1FTSVX87jpouwAG2/",
      "title": "程序员老张（AI教学）的头条主页 - 今日头条(www.toutiao.com)",
      "type": "feed",
      "url": "rsshub://toutiao/user/token/MS4wLjABAAAAuaHJxshSggAbn-LFL6O0BjzOrTlpHxUDLxcvCP73__GXaavP1FTSVX87jpouwAG2"
    },
    {
      "description": "关注不迷路🤙🏻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84412058211393536",
      "image": "https://p3-sign.toutiaoimg.com/user-avatar/574d56bc5fcc3e3dd56bf1d0989e7c2e~300x300.image?_iz=112761&from=tt_user.profile_all_shortvideo&lk3s=06827d14&x-expires=1788912000&x-signature=2zZ5THqFRMIivWNB3vA%2BM50LSL4%3D",
      "ownerUserId": null,
      "siteUrl": "https://www.toutiao.com/c/user/token/MS4wLjABAAAA1q3h6c_FuudwZwYJBcGMC4LjJwrnBkzE6tkRu2pVPOg/",
      "title": "听风的蚕工作室的头条主页 - 今日头条(www.toutiao.com)",
      "type": "feed",
      "url": "rsshub://toutiao/user/token/MS4wLjABAAAA1q3h6c_FuudwZwYJBcGMC4LjJwrnBkzE6tkRu2pVPOg"
    }
  ]
}
```
