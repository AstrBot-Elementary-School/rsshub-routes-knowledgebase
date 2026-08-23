# Soul - 话题瞬间

## Coverage
`index-only`

## Route
- Namespace: `soulapp`
- Namespace Name: `Soul`
- Route Path: `/soulapp/posts/tag/:tid{.+}`
- Route Name: `话题瞬间`
- Example: `/soulapp/posts/tag/VHdZN0ZpVUp4M2s9`
- URL: `soulapp.cn`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `BugWriter2`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
提供不同内容的 `tid`, 可以得到不同的话题瞬间推荐，如果想看多个话题可以用 `/` 把不同的 `tid` 连起来，例如: `VHdZN0ZpVUp4M2s9/d1k5VEt2d0tkcW89`

## Parameters
- `tid`: 话题 id, 分享话题时的 URL 的 tagIdEcpt 参数


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "提供不同内容的 `tid`, 可以得到不同的话题瞬间推荐，如果想看多个话题可以用 `/` 把不同的 `tid` 连起来，例如: `VHdZN0ZpVUp4M2s9/d1k5VEt2d0tkcW89`",
  "example": "/soulapp/posts/tag/VHdZN0ZpVUp4M2s9",
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "BugWriter2"
  ],
  "name": "话题瞬间",
  "parameters": {
    "tid": "话题 id, 分享话题时的 URL 的 tagIdEcpt 参数"
  },
  "path": "/posts/tag/:tid{.+}",
  "topFeeds": []
}
```
