# NGA - 分区帖子

## Coverage
`index-only`

## Route
- Namespace: `nga`
- Namespace Name: `NGA`
- Route Path: `/nga/forum/:fid/:recommend?`
- Route Name: `分区帖子`
- Example: `/nga/forum/489`
- URL: `bbs.nga.cn`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `xyqfer`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `fid`: 分区 id, 可在分区主页 URL 找到, 没有 fid 时 stid 同样适用
- `recommend`: 是否只显示精华主题, 留空为否, 任意值为是


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
    "bbs",
    "popular"
  ],
  "example": "/nga/forum/489",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3195,
  "location": "forum.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "分区帖子",
  "parameters": {
    "fid": "分区 id, 可在分区主页 URL 找到, 没有 fid 时 stid 同样适用",
    "recommend": "是否只显示精华主题, 留空为否, 任意值为是"
  },
  "path": "/forum/:fid/:recommend?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NGA是国内专业的游戏玩家社区,魔兽世界,英雄联盟,炉石传说,风暴英雄,暗黑破坏神3(D3)游戏攻略讨论,以及其他热门游戏玩家社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42244008445359104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nga.178.com/thread.php?fid=-7955747",
      "title": "NGA-晴风村",
      "type": "feed",
      "url": "rsshub://nga/forum/-7955747"
    },
    {
      "description": "NGA是国内专业的游戏玩家社区,魔兽世界,英雄联盟,炉石传说,风暴英雄,暗黑破坏神3(D3)游戏攻略讨论,以及其他热门游戏玩家社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78735948081081344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nga.178.com/thread.php?fid=-7",
      "title": "NGA-网事杂谈",
      "type": "feed",
      "url": "rsshub://nga/forum/-7"
    }
  ],
  "view": 0
}
```
