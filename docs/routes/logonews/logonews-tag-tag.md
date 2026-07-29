# LogoNews 标志情报局 - 文章标签

## Coverage
`index-only`

## Route
- Namespace: `logonews`
- Namespace Name: `LogoNews 标志情报局`
- Route Path: `/logonews/tag/:tag`
- Route Name: `文章标签`
- Example: `/logonews/tag/china`
- URL: `logonews.cn/`
- Language: `_None_`
- Categories: `design`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
如 [中国 - 标志情报局](https://www.logonews.cn/tag/china) 的 URL 为 `https://www.logonews.cn/tag/china`，可得路由为 [`/logonews/tag/china`](https://rsshub.app/logonews/tag/china)。

## Parameters
- `tag`: 标签，可在对应标签页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `logonews.cn/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "如 [中国 - 标志情报局](https://www.logonews.cn/tag/china) 的 URL 为 `https://www.logonews.cn/tag/china`，可得路由为 [`/logonews/tag/china`](https://rsshub.app/logonews/tag/china)。",
  "example": "/logonews/tag/china",
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章标签",
  "parameters": {
    "tag": "标签，可在对应标签页 URL 中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "logonews.cn/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "topFeeds": [],
  "url": "logonews.cn/"
}
```
