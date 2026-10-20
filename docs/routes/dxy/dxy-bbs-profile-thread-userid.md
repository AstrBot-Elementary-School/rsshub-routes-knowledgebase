# 丁香园 - 个人帖子

## Coverage
`index-only`

## Route
- Namespace: `dxy`
- Namespace Name: `丁香园`
- Route Path: `/dxy/bbs/profile/thread/:userId`
- Route Name: `个人帖子`
- Example: `/dxy/bbs/profile/thread/8335054`
- URL: `dxy.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `profile/thread.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `userId`: 个人 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.dxy.cn/bbs/newweb/pc/profile/:userId/threads`
  - `www.dxy.cn/bbs/newweb/pc/profile/:userId`
- `target`: `/bbs/profile/thread/:userId`
### Rule 2
- `source`:
  - `dxy.cn/bbs/newweb/pc/profile/:userId/threads`
  - `dxy.cn/bbs/newweb/pc/profile/:userId`
- `target`: `/bbs/profile/thread/:userId`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/dxy/bbs/profile/thread/8335054",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "profile/thread.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "个人帖子",
  "parameters": {
    "userId": "个人 ID，可在 URL 中找到"
  },
  "path": "/bbs/profile/thread/:userId",
  "radar": [
    {
      "source": [
        "www.dxy.cn/bbs/newweb/pc/profile/:userId/threads",
        "www.dxy.cn/bbs/newweb/pc/profile/:userId"
      ],
      "target": "/bbs/profile/thread/:userId"
    },
    {
      "source": [
        "dxy.cn/bbs/newweb/pc/profile/:userId/threads",
        "dxy.cn/bbs/newweb/pc/profile/:userId"
      ],
      "target": "/bbs/profile/thread/:userId"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "心血管内科医师 路漫漫其修远兮，吾将上下前后左右而求索。 - Powered by RSSHub",
      "errorAt": "2025-08-12T08:05:10.572Z",
      "errorMessage": "请求异常，请通过验证\n",
      "id": "59116838117216256",
      "image": "https://img.dxycdn.com/avatars/120/7f/2e/ce/8335054/1.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.dxy.cn/bbs/newweb/pc/profile/8335054/threads",
      "title": "达摩 的个人主页 - 丁香园论坛 - 专业医生社区，医学、药学、生命科学、科研学术交流",
      "type": "feed",
      "url": "rsshub://dxy/bbs/profile/thread/8335054"
    }
  ]
}
```
