# LogoNews 标志情报局 - 作品标签

## Coverage
`index-only`

## Route
- Namespace: `logonews`
- Namespace Name: `LogoNews 标志情报局`
- Route Path: `/logonews/work/tags/:tag?`
- Route Name: `作品标签`
- Example: `/logonews/work/tags/旅游`
- URL: `logonews.cn/`
- Language: `_None_`
- Categories: `design`
- Maintainers: `nczitzk`
- Source Location: `work-tag.ts`
- Source Module: `_None_`

## Description
如 [LOGO 标签：旅游 - 标志情报局](https://www.logonews.cn/work/tags/旅游) 的 URL 为 [https://www.logonews.cn/work/tags/ 旅游](https://www.logonews.cn/work/tags/旅游)，可得路由为 [`/logonews/work/tags/旅游`](https://rsshub.app/logonews/work/tags/旅游)。

## Parameters
- `tag`: 标签，可在对应标签页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `logonews.cn/work/tags/:tag`
- `target`: `/work/tags/:tag`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "如 [LOGO 标签：旅游 - 标志情报局](https://www.logonews.cn/work/tags/旅游) 的 URL 为 [https://www.logonews.cn/work/tags/ 旅游](https://www.logonews.cn/work/tags/旅游)，可得路由为 [`/logonews/work/tags/旅游`](https://rsshub.app/logonews/work/tags/旅游)。",
  "example": "/logonews/work/tags/旅游",
  "heat": 0,
  "location": "work-tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "作品标签",
  "parameters": {
    "tag": "标签，可在对应标签页 URL 中找到"
  },
  "path": "/work/tags/:tag?",
  "radar": [
    {
      "source": [
        "logonews.cn/work/tags/:tag"
      ],
      "target": "/work/tags/:tag"
    }
  ],
  "topFeeds": [],
  "url": "logonews.cn/"
}
```
