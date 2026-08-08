# 色花堂 - Forum

## Coverage
`index-only`

## Route
- Namespace: `sehuatang`
- Namespace Name: `色花堂`
- Route Path: `/sehuatang/bt/:subforumid?`
- Route Name: `Forum`
- Example: `/sehuatang/36/368`
- URL: `sehuatang.net`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `qiwihui, junfengP, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
**原创 BT 电影**

| 国产原创 | 亚洲无码原创 | 亚洲有码原创 | 高清中文字幕 | 三级写真 | VR 视频 | 素人有码 | 欧美无码 | 韩国主播 | 动漫原创 | 综合讨论 |
| -------- | ------------ | ------------ | ------------ | -------- | ------- | -------- | -------- | -------- | -------- | -------- |
| gcyc     | yzwmyc       | yzymyc       | gqzwzm       | sjxz     | vr      | srym     | omwm     | hgzb     | dmyc     | zhtl     |

**色花图片**

| 原创自拍 | 转贴自拍 | 华人街拍 | 亚洲性爱 | 欧美性爱 | 卡通动漫 | 套图下载 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| yczp     | ztzp     | hrjp     | yzxa     | omxa     | ktdm     | ttxz     |

## Parameters
- `subforumid`: 版块 id 或板块名称（见下表）, 为空默认高清中文字幕
- `type`: 类型 id, 可在分区类型过滤后的 URL 中找到


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "**原创 BT 电影**\n\n| 国产原创 | 亚洲无码原创 | 亚洲有码原创 | 高清中文字幕 | 三级写真 | VR 视频 | 素人有码 | 欧美无码 | 韩国主播 | 动漫原创 | 综合讨论 |\n| -------- | ------------ | ------------ | ------------ | -------- | ------- | -------- | -------- | -------- | -------- | -------- |\n| gcyc     | yzwmyc       | yzymyc       | gqzwzm       | sjxz     | vr      | srym     | omwm     | hgzb     | dmyc     | zhtl     |\n\n**色花图片**\n\n| 原创自拍 | 转贴自拍 | 华人街拍 | 亚洲性爱 | 欧美性爱 | 卡通动漫 | 套图下载 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| yczp     | ztzp     | hrjp     | yzxa     | omxa     | ktdm     | ttxz     |",
  "example": "/sehuatang/36/368",
  "features": {
    "nsfw": true
  },
  "heat": 306,
  "location": "index.ts",
  "maintainers": [
    "qiwihui",
    "junfengP",
    "nczitzk"
  ],
  "name": "Forum",
  "parameters": {
    "subforumid": "版块 id 或板块名称（见下表）, 为空默认高清中文字幕",
    "type": "类型 id, 可在分区类型过滤后的 URL 中找到"
  },
  "path": [
    "/bt/:subforumid?",
    "/picture/:subforumid",
    "/:subforumid?/:type?",
    "/:subforumid?",
    ""
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "色花堂 - 高清中文字幕 - Powered by RSSHub",
      "errorAt": "2026-07-27T13:52:56.392Z",
      "errorMessage": "[GET] \"https://www.sehuatang.net/\": 403 Forbidden\n",
      "id": "65327819580054528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sehuatang.net/forum.php?mod=forumdisplay&orderby=dateline&fid=103",
      "title": "色花堂 - 高清中文字幕",
      "type": "feed",
      "url": "rsshub://sehuatang/bt/gqzwzm"
    },
    {
      "description": "色花堂 - 国产原创 - Powered by RSSHub",
      "errorAt": "2026-07-31T11:07:31.532Z",
      "errorMessage": "[GET] \"https://www.sehuatang.net/\": 403 Forbidden\n[GET] \"https://www.sehuatang.net/\": 403 Forbidden\n",
      "id": "75483915450641408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sehuatang.net/forum.php?mod=forumdisplay&orderby=dateline&fid=2",
      "title": "色花堂 - 国产原创",
      "type": "feed",
      "url": "rsshub://sehuatang/bt/2"
    }
  ]
}
```
