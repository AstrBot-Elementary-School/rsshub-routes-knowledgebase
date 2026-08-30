# AcFun - 用户投稿

## Coverage
`index-only`

## Route
- Namespace: `acfun`
- Namespace Name: `AcFun`
- Route Path: `/acfun/user/video/:uid/:embed?`
- Route Name: `用户投稿`
- Example: `/acfun/user/video/6102`
- URL: `www.acfun.cn`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `wdssmq`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 UID
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.acfun.cn/u/:id`
- `target`: `/user/video/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/acfun/user/video/6102",
  "heat": 40,
  "location": "video.ts",
  "maintainers": [
    "wdssmq"
  ],
  "name": "用户投稿",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 UID"
  },
  "path": "/user/video/:uid/:embed?",
  "radar": [
    {
      "source": [
        "www.acfun.cn/u/:id"
      ],
      "target": "/user/video/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "每天最新的国内车祸实例，助你提高安全意识，生命冇take two，请小心演绎！欢迎投稿：UploadAccident@qq.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74054665945348096",
      "image": "https://imgs.aixifan.com/style/image/201907/zjC8tBrviYU9WXilU5iSWE21qpmXIk2l.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.acfun.cn/u/4075269",
      "title": "交通事故video的个人空间 -AcFun弹幕视频网 - 认真你就输啦 (?ω?)ノ- ( ゜- ゜)つロ",
      "type": "feed",
      "url": "rsshub://acfun/user/video/4075269"
    },
    {
      "description": "感谢大家的关注和投蕉，谢谢！！！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72885134656350208",
      "image": "https://imgs.aixifan.com/style/image/201907/Pt1GipJtiUHE0rnGckcm5gHzJeTRxjJh.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.acfun.cn/u/2176158",
      "title": "九星之歌的个人空间 -AcFun弹幕视频网 - 认真你就输啦 (?ω?)ノ- ( ゜- ゜)つロ",
      "type": "feed",
      "url": "rsshub://acfun/user/video/2176158"
    }
  ],
  "view": 3
}
```
