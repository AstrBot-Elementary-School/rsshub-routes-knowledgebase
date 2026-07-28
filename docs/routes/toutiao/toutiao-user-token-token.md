# 今日头条 - 头条主页

## Coverage
`index-only`

## Route
- Namespace: `toutiao`
- Namespace Name: `今日头条`
- Route Path: `/toutiao/user/token/:token`
- Route Name: `头条主页`
- Example: `/toutiao/user/token/MS4wLjABAAAAEmbqJP2CmC8XXv1BpMvQ3sQHKAxFsq8wHxj8XVIQWja6tMcB-QEbFkzkRNgMl12M`
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
  "example": "/toutiao/user/token/MS4wLjABAAAAEmbqJP2CmC8XXv1BpMvQ3sQHKAxFsq8wHxj8XVIQWja6tMcB-QEbFkzkRNgMl12M",
  "features": {
    "antiCrawler": true
  },
  "heat": 379,
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
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
      "image": "https://p3-sign.toutiaoimg.com/user-avatar/574d56bc5fcc3e3dd56bf1d0989e7c2e~300x300.image?_iz=112761&from=tt_user.profile_all_shortvideo&lk3s=06827d14&x-expires=1785801600&x-signature=4jq1NyhATchwy1MdnJhh8uy1mKM%3D",
      "ownerUserId": null,
      "siteUrl": "https://www.toutiao.com/c/user/token/MS4wLjABAAAA1q3h6c_FuudwZwYJBcGMC4LjJwrnBkzE6tkRu2pVPOg/",
      "title": "听风的蚕的头条主页 - 今日头条(www.toutiao.com)",
      "type": "feed",
      "url": "rsshub://toutiao/user/token/MS4wLjABAAAA1q3h6c_FuudwZwYJBcGMC4LjJwrnBkzE6tkRu2pVPOg"
    }
  ]
}
```
