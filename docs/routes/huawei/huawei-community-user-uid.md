# 华为 - 花粉俱乐部用户帖子

## Coverage
`index-only`

## Route
- Namespace: `huawei`
- Namespace Name: `华为`
- Route Path: `/huawei/community/user/:uid?`
- Route Name: `花粉俱乐部用户帖子`
- Example: `/huawei/community/user/1000014645695`
- URL: `developer.huawei.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `community/user.ts`
- Source Module: `_None_`

## Description
Includes public posts and their complete update notes. The default official account publishes device models, software versions, and release details.

## Parameters
- `uid`: User ID from the public profile URL. Defaults to the official Mate/P software maintenance account (1000014645695).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cn.club.vmall.com/mhw/consumer/cn/community/mhwnews/bluevstore/id_:uid`
- `target`: `/community/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Includes public posts and their complete update notes. The default official account publishes device models, software versions, and release details.",
  "example": "/huawei/community/user/1000014645695",
  "heat": 0,
  "location": "community/user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "花粉俱乐部用户帖子",
  "parameters": {
    "uid": "User ID from the public profile URL. Defaults to the official Mate/P software maintenance account (1000014645695)."
  },
  "path": "/community/user/:uid?",
  "radar": [
    {
      "source": [
        "cn.club.vmall.com/mhw/consumer/cn/community/mhwnews/bluevstore/id_:uid"
      ],
      "target": "/community/user/:uid"
    }
  ],
  "topFeeds": []
}
```
