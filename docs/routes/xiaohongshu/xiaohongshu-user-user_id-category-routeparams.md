# 小红书 - 用户笔记/收藏

## Coverage
`index-only`

## Route
- Namespace: `xiaohongshu`
- Namespace Name: `小红书`
- Route Path: `/xiaohongshu/user/:user_id/:category/:routeParams?`
- Route Name: `用户笔记/收藏`
- Example: `/xiaohongshu/user/593032945e87e77791e03696/notes`
- URL: `xiaohongshu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `lotosbin, howerhe, rien7, dddaniel1, pseudoyu`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user_id`: user id, length 24 characters
- `category`: {"default": "notes", "description": "category, notes or collect", "options": [{"label": "notes", "value": "notes"}, {"label": "collect", "value": "collect"}]}
- `routeParams`: {"default": "0", "description": "displayLivePhoto,`/user/:user_id/notes/displayLivePhoto=0`,不限时LivePhoto显示为图片,`/user/:user_id/notes/displayLivePhoto=1`,取值不为0时LivePhoto显示为视频"}


## Features
- `antiCrawler`: true
- `requirePuppeteer`: true
- `requireConfig`: [{"description": "小红书 cookie 值，可在网络里面看到。", "name": "XIAOHONGSHU_COOKIE", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `xiaohongshu.com/user/profile/:user_id`
- `target`: `/user/:user_id/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/xiaohongshu/user/593032945e87e77791e03696/notes",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "小红书 cookie 值，可在网络里面看到。",
        "name": "XIAOHONGSHU_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": true
  },
  "heat": 1394260,
  "location": "user.ts",
  "maintainers": [
    "lotosbin",
    "howerhe",
    "rien7",
    "dddaniel1",
    "pseudoyu"
  ],
  "name": "用户笔记/收藏",
  "parameters": {
    "category": {
      "default": "notes",
      "description": "category, notes or collect",
      "options": [
        {
          "label": "notes",
          "value": "notes"
        },
        {
          "label": "collect",
          "value": "collect"
        }
      ]
    },
    "routeParams": {
      "default": "0",
      "description": "displayLivePhoto,`/user/:user_id/notes/displayLivePhoto=0`,不限时LivePhoto显示为图片,`/user/:user_id/notes/displayLivePhoto=1`,取值不为0时LivePhoto显示为视频"
    },
    "user_id": "user id, length 24 characters"
  },
  "path": "/user/:user_id/:category/:routeParams?",
  "radar": [
    {
      "source": [
        "xiaohongshu.com/user/profile/:user_id"
      ],
      "target": "/user/:user_id/notes"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "喜欢穿搭👗 随意分享🩰 📮3790381790@qq.com 白羊座 重庆南岸 3 关注 1万+ 粉丝 1万+ 获赞与收藏 - Powered by RSSHub",
      "errorAt": "2026-07-13T17:19:40.144Z",
      "errorMessage": "Failed to fetch\nAuthentication failed. Access denied.\n/xiaohongshu/user/5db011250000000001002502/notes\nFailed to fetch\nWaiting for selector `div.reds-tab-item:nth-child(2), #red-captcha` failed: waitForFunction failed: frame got detached.\nFailed to fetch\n",
      "id": "67448641547187200",
      "image": "https://sns-avatar-qc.xhscdn.com/avatar/1040g2jo319cmu4i06c005ndg24ig8982rj4drug?imageView2/2/w/540/format/webp",
      "ownerUserId": null,
      "siteUrl": "https://www.xiaohongshu.com/user/profile/5db011250000000001002502",
      "title": "shirley - 小红书笔记",
      "type": "feed",
      "url": "rsshub://xiaohongshu/user/5db011250000000001002502/notes"
    },
    {
      "description": "女摄/杭州 10+ 关注 1万+ 粉丝 1万+ 获赞与收藏 - Powered by RSSHub",
      "errorAt": "2025-12-09T12:40:34.349Z",
      "errorMessage": "Failed to fetch\n522 \nFailed to fetch\nFailed to fetch\n",
      "id": "68661468126774272",
      "image": "https://sns-avatar-qc.xhscdn.com/avatar/1040g2jo30q8atfr8n6005p9bl8hqmi9p1q1h18o?imageView2/2/w/540/format/webp",
      "ownerUserId": null,
      "siteUrl": "https://www.xiaohongshu.com/user/profile/652baa23000000002a034939",
      "title": "馒头豹饱 - 小红书笔记",
      "type": "feed",
      "url": "rsshub://xiaohongshu/user/652baa23000000002a034939/notes"
    }
  ],
  "view": 0
}
```
