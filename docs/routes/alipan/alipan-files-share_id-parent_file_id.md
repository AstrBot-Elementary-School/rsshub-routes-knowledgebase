# 阿里云盘 - 文件列表

## Coverage
`index-only`

## Route
- Namespace: `alipan`
- Namespace Name: `阿里云盘`
- Route Path: `/alipan/files/:share_id/:parent_file_id?`
- Route Name: `文件列表`
- Example: `/alipan/files/jjtKEgXJAtC/64a957744876479ab17941b29d1289c6ebdd71ef`
- URL: `www.alipan.com/s`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `files.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `share_id`: 分享 id，可以从分享页面 URL 中找到
- `parent_file_id`: 文件夹 id，可以从文件夹页面 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.alipan.com/s/:share_id/folder/:parent_file_id`
  - `www.alipan.com/s/:share_id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/alipan/files/jjtKEgXJAtC/64a957744876479ab17941b29d1289c6ebdd71ef",
  "heat": 7,
  "location": "files.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "文件列表",
  "parameters": {
    "parent_file_id": "文件夹 id，可以从文件夹页面 URL 中找到",
    "share_id": "分享 id，可以从分享页面 URL 中找到"
  },
  "path": "/files/:share_id/:parent_file_id?",
  "radar": [
    {
      "source": [
        "www.alipan.com/s/:share_id/folder/:parent_file_id",
        "www.alipan.com/s/:share_id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "A 国漫-阿里云盘 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "158350876831333376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.aliyundrive.com/s/jcuRG1PKsTn/folder/678b1f0e38bfbaa0650a49049919f34ce7e2678e",
      "title": "A 国漫-阿里云盘",
      "type": "feed",
      "url": "rsshub://alipan/files/jcuRG1PKsTn/678b1f0e38bfbaa0650a49049919f34ce7e2678e"
    },
    {
      "description": "【微博@tv综合吧】善意的竞争-阿里云盘 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114980282029010944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.aliyundrive.com/s/Dhvm99rqDLU/folder/679f0e41465632058c0749f6aaeb75c874c95bec",
      "title": "【微博@tv综合吧】善意的竞争-阿里云盘",
      "type": "feed",
      "url": "rsshub://alipan/files/Dhvm99rqDLU/679f0e41465632058c0749f6aaeb75c874c95bec"
    }
  ],
  "url": "www.alipan.com/s"
}
```
