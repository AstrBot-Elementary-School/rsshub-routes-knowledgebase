# 哔嘀影视 - 首页

## Coverage
`index-only`

## Route
- Namespace: `bdys`
- Namespace Name: `哔嘀影视`
- Route Path: `/bdys/:caty?/:type?/:area?/:year?/:order?`
- Route Name: `首页`
- Example: `/bdys`
- URL: `52bdys.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
#### 资源分类

| 不限 | 电影 | 电视剧 |
| ---- | ---- | ------ |
| all  | 0    | 1      |

#### 影视类型

| 不限 | 动作    | 爱情   | 喜剧 | 科幻   | 恐怖   |
| ---- | ------- | ------ | ---- | ------ | ------ |
| all  | dongzuo | aiqing | xiju | kehuan | kongbu |

| 战争      | 武侠  | 魔幻   | 剧情   | 动画    | 惊悚     |
| --------- | ----- | ------ | ------ | ------- | -------- |
| zhanzheng | wuxia | mohuan | juqing | donghua | jingsong |

| 3D | 灾难   | 悬疑   | 警匪    | 文艺  | 青春     |
| -- | ------ | ------ | ------- | ----- | -------- |
| 3D | zainan | xuanyi | jingfei | wenyi | qingchun |

| 冒险    | 犯罪   | 纪录 | 古装     | 奇幻   | 国语  |
| ------- | ------ | ---- | -------- | ------ | ----- |
| maoxian | fanzui | jilu | guzhuang | qihuan | guoyu |

| 综艺   | 历史  | 运动    | 原创压制   |
| ------ | ----- | ------- | ---------- |
| zongyi | lishi | yundong | yuanchuang |

| 美剧  | 韩剧  | 国产电视剧 | 日剧 | 英剧   | 德剧 |
| ----- | ----- | ---------- | ---- | ------ | ---- |
| meiju | hanju | guoju      | riju | yingju | deju |

| 俄剧 | 巴剧 | 加剧  | 西剧    | 意大利剧 | 泰剧  |
| ---- | ---- | ----- | ------- | -------- | ----- |
| eju  | baju | jiaju | spanish | yidaliju | taiju |

| 港台剧    | 法剧 | 澳剧 |
| --------- | ---- | ---- |
| gangtaiju | faju | aoju |

#### 制片地区

| 大陆 | 中国香港 | 中国台湾 |
| ---- | -------- | -------- |

| 美国 | 英国 | 日本 | 韩国 | 法国 |
| ---- | ---- | ---- | ---- | ---- |

| 印度 | 德国 | 西班牙 | 意大利 | 澳大利亚 |
| ---- | ---- | ------ | ------ | -------- |

| 比利时 | 瑞典 | 荷兰 | 丹麦 | 加拿大 | 俄罗斯 |
| ------ | ---- | ---- | ---- | ------ | ------ |

#### 影视排序

| 更新时间 | 豆瓣评分 |
| -------- | -------- |
| 0        | 1        |

## Parameters
- `caty`: 影视类型，见下表，默认为 `all` 即不限
- `type`: 资源分类，见下表，默认为 `all` 即不限
- `area`: 制片地区，见下表，默认为 `all` 即不限
- `year`: 上映时间，此处填写年份不小于2000，默认为 `all` 即不限
- `order`: 影视排序，见下表，默认为更新时间


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "#### 资源分类\n\n| 不限 | 电影 | 电视剧 |\n| ---- | ---- | ------ |\n| all  | 0    | 1      |\n\n#### 影视类型\n\n| 不限 | 动作    | 爱情   | 喜剧 | 科幻   | 恐怖   |\n| ---- | ------- | ------ | ---- | ------ | ------ |\n| all  | dongzuo | aiqing | xiju | kehuan | kongbu |\n\n| 战争      | 武侠  | 魔幻   | 剧情   | 动画    | 惊悚     |\n| --------- | ----- | ------ | ------ | ------- | -------- |\n| zhanzheng | wuxia | mohuan | juqing | donghua | jingsong |\n\n| 3D | 灾难   | 悬疑   | 警匪    | 文艺  | 青春     |\n| -- | ------ | ------ | ------- | ----- | -------- |\n| 3D | zainan | xuanyi | jingfei | wenyi | qingchun |\n\n| 冒险    | 犯罪   | 纪录 | 古装     | 奇幻   | 国语  |\n| ------- | ------ | ---- | -------- | ------ | ----- |\n| maoxian | fanzui | jilu | guzhuang | qihuan | guoyu |\n\n| 综艺   | 历史  | 运动    | 原创压制   |\n| ------ | ----- | ------- | ---------- |\n| zongyi | lishi | yundong | yuanchuang |\n\n| 美剧  | 韩剧  | 国产电视剧 | 日剧 | 英剧   | 德剧 |\n| ----- | ----- | ---------- | ---- | ------ | ---- |\n| meiju | hanju | guoju      | riju | yingju | deju |\n\n| 俄剧 | 巴剧 | 加剧  | 西剧    | 意大利剧 | 泰剧  |\n| ---- | ---- | ----- | ------- | -------- | ----- |\n| eju  | baju | jiaju | spanish | yidaliju | taiju |\n\n| 港台剧    | 法剧 | 澳剧 |\n| --------- | ---- | ---- |\n| gangtaiju | faju | aoju |\n\n#### 制片地区\n\n| 大陆 | 中国香港 | 中国台湾 |\n| ---- | -------- | -------- |\n\n| 美国 | 英国 | 日本 | 韩国 | 法国 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 印度 | 德国 | 西班牙 | 意大利 | 澳大利亚 |\n| ---- | ---- | ------ | ------ | -------- |\n\n| 比利时 | 瑞典 | 荷兰 | 丹麦 | 加拿大 | 俄罗斯 |\n| ------ | ---- | ---- | ---- | ------ | ------ |\n\n#### 影视排序\n\n| 更新时间 | 豆瓣评分 |\n| -------- | -------- |\n| 0        | 1        |",
  "example": "/bdys",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 27,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "首页",
  "parameters": {
    "area": "制片地区，见下表，默认为 `all` 即不限",
    "caty": "影视类型，见下表，默认为 `all` 即不限",
    "order": "影视排序，见下表，默认为更新时间",
    "type": "资源分类，见下表，默认为 `all` 即不限",
    "year": "上映时间，此处填写年份不小于2000，默认为 `all` 即不限"
  },
  "path": "/:caty?/:type?/:area?/:year?/:order?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "哔嘀影视 - Powered by RSSHub",
      "errorAt": "2025-02-20T13:50:10.262Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "112474437722406912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bdys01.com/s/all?&order=0",
      "title": "哔嘀影视",
      "type": "feed",
      "url": "rsshub://bdys"
    }
  ]
}
```
