# 武汉大学 - 武汉大学遥感信息工程学院

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/rsgis/:type/:sub?`
- Route Name: `武汉大学遥感信息工程学院`
- Example: `/whu/rsgis/index`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `HPDell`
- Source Location: `rsgis.ts`
- Source Module: `_None_`

## Description
|  分类名  | `type` 值 |  子类名  | `sub` 值 |
| :------: | :-------- | :------: | :------- |
|   首页   | `index`   |          |          |
| 学院新闻 | `xyxw`    |   全部   | `all`    |
|          |           | 学院要闻 | `xyyw`   |
|          |           | 合作交流 | `hzjl`   |
|          |           | 媒体聚焦 | `mtjj`   |
|          |           | 学工要闻 | `xgyw`   |
| 科学研究 | `kxyj`    |   全部   | `all`    |
|          |           | 学术报告 | `xsbg`   |
|          |           | 学术交流 | `xsjl`   |
|          |           | 学术成果 | `kycg`   |
|          |           | 申报信息 | `sbxx`   |
| 通知公告 | `tzgg`    |   全部   | `all`    |
|          |           | 学院通知 | `xytz`   |
|          |           | 教学动态 | `jxdt`   |
|          |           | 学术动态 | `xsdt`   |
|          |           | 人才引进 | `rcyj`   |

## Parameters
- `type`: 栏目，详见表格
- `sub`: 子栏目。当 `type` 为 `index` 的时候不起效；当 `type` 为其他合法值时，默认为 `all` 表示所有子类，其他可选项见下表。


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rsgis.whu.edu.cn/index.htm`
- `target`: `/rsgis/index`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "|  分类名  | `type` 值 |  子类名  | `sub` 值 |\n| :------: | :-------- | :------: | :------- |\n|   首页   | `index`   |          |          |\n| 学院新闻 | `xyxw`    |   全部   | `all`    |\n|          |           | 学院要闻 | `xyyw`   |\n|          |           | 合作交流 | `hzjl`   |\n|          |           | 媒体聚焦 | `mtjj`   |\n|          |           | 学工要闻 | `xgyw`   |\n| 科学研究 | `kxyj`    |   全部   | `all`    |\n|          |           | 学术报告 | `xsbg`   |\n|          |           | 学术交流 | `xsjl`   |\n|          |           | 学术成果 | `kycg`   |\n|          |           | 申报信息 | `sbxx`   |\n| 通知公告 | `tzgg`    |   全部   | `all`    |\n|          |           | 学院通知 | `xytz`   |\n|          |           | 教学动态 | `jxdt`   |\n|          |           | 学术动态 | `xsdt`   |\n|          |           | 人才引进 | `rcyj`   |",
  "example": "/whu/rsgis/index",
  "heat": 3,
  "location": "rsgis.ts",
  "maintainers": [
    "HPDell"
  ],
  "name": "武汉大学遥感信息工程学院",
  "parameters": {
    "sub": "子栏目。当 `type` 为 `index` 的时候不起效；当 `type` 为其他合法值时，默认为 `all` 表示所有子类，其他可选项见下表。",
    "type": "栏目，详见表格"
  },
  "path": "/rsgis/:type/:sub?",
  "radar": [
    {
      "source": [
        "rsgis.whu.edu.cn/index.htm"
      ],
      "target": "/rsgis/index"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "通知公告 - 武汉大学遥感信息工程学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59180619931460608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rsgis.whu.edu.cn/",
      "title": "通知公告 - 武汉大学遥感信息工程学院",
      "type": "feed",
      "url": "rsshub://whu/rsgis/tzgg/rcyj"
    },
    {
      "description": "首页 - 武汉大学遥感信息工程学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59180420116893696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rsgis.whu.edu.cn/",
      "title": "首页 - 武汉大学遥感信息工程学院",
      "type": "feed",
      "url": "rsshub://whu/rsgis/index"
    }
  ]
}
```
