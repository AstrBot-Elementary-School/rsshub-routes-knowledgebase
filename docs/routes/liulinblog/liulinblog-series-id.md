# 木木博客 - 专题

## Coverage
`index-only`

## Route
- Namespace: `liulinblog`
- Namespace Name: `木木博客`
- Route Path: `/liulinblog/series/:id`
- Route Name: `专题`
- Example: `/liulinblog/series/xunlei`
- URL: `liulinblog.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
| 【免费速存】迅雷资源合集 | 直播带货教程 | 电商培训课程    | 拼多多运营培训 | 小红书运营  | 抖音运营      | 闲鱼运营      | 短视频运营        |
| ------------------------ | ------------ | --------------- | -------------- | ----------- | ------------- | ------------- | ----------------- |
| xunlei                   | zhibodaihuo  | dianshangpeixun | pinduoduo      | xiaohongshu | douyinyunying | xianyuyunying | duanshipinyunying |

## Parameters
- `id`: 专题 id，可在对应标签页 URL 中找到，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `liulinblog.com/series/:id`
  - `liulinblog.com/`
- `target`: `/series/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 【免费速存】迅雷资源合集 | 直播带货教程 | 电商培训课程    | 拼多多运营培训 | 小红书运营  | 抖音运营      | 闲鱼运营      | 短视频运营        |\n| ------------------------ | ------------ | --------------- | -------------- | ----------- | ------------- | ------------- | ----------------- |\n| xunlei                   | zhibodaihuo  | dianshangpeixun | pinduoduo      | xiaohongshu | douyinyunying | xianyuyunying | duanshipinyunying |",
  "example": "/liulinblog/series/xunlei",
  "heat": 0,
  "location": "series.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专题",
  "parameters": {
    "id": "专题 id，可在对应标签页 URL 中找到，见下表"
  },
  "path": "/series/:id",
  "radar": [
    {
      "source": [
        "liulinblog.com/series/:id",
        "liulinblog.com/"
      ],
      "target": "/series/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
