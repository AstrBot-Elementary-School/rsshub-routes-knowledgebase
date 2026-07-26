# 摩点 - 众筹

## Coverage
`index-only`

## Route
- Namespace: `modian`
- Namespace Name: `摩点`
- Route Path: `/modian/zhongchou/:category?/:sort?/:status?`
- Route Name: `众筹`
- Example: `/modian/zhongchou`
- URL: `modian.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `zhongchou.ts`
- Source Module: `_None_`

## Description
分类

| 全部 | 游戏  | 动漫   | 出版       | 桌游       |
| ---- | ----- | ------ | ---------- | ---------- |
| all  | games | comics | publishing | tablegames |

| 卡牌  | 潮玩模型 | 影视       | 音乐  | 活动       |
| ----- | -------- | ---------- | ----- | ---------- |
| cards | toys     | film-video | music | activities |

| 设计   | 科技       | 食品 | 爱心通道 | 动物救助 |
| ------ | ---------- | ---- | -------- | -------- |
| design | technology | food | charity  | animals  |

| 个人愿望 | 其他   |
| -------- | ------ |
| wishes   | others |

排序

| 最新上线  | 金额最高   | 评论最多     |
| --------- | ---------- | ------------ |
| top\_time | top\_money | top\_comment |

状态

| 全部 | 创意 | 预热    | 众筹中 | 众筹成功 |
| ---- | ---- | ------- | ------ | -------- |
| all  | idea | preheat | going  | success  |

## Parameters
- `category`: 分类，见下表，默认为全部
- `sort`: 排序，见下表，默认为最新上线
- `status`: 状态，见下表，默认为全部


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `zhongchou.modian.com/:category/:sort/:status`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "分类\n\n| 全部 | 游戏  | 动漫   | 出版       | 桌游       |\n| ---- | ----- | ------ | ---------- | ---------- |\n| all  | games | comics | publishing | tablegames |\n\n| 卡牌  | 潮玩模型 | 影视       | 音乐  | 活动       |\n| ----- | -------- | ---------- | ----- | ---------- |\n| cards | toys     | film-video | music | activities |\n\n| 设计   | 科技       | 食品 | 爱心通道 | 动物救助 |\n| ------ | ---------- | ---- | -------- | -------- |\n| design | technology | food | charity  | animals  |\n\n| 个人愿望 | 其他   |\n| -------- | ------ |\n| wishes   | others |\n\n排序\n\n| 最新上线  | 金额最高   | 评论最多     |\n| --------- | ---------- | ------------ |\n| top\\_time | top\\_money | top\\_comment |\n\n状态\n\n| 全部 | 创意 | 预热    | 众筹中 | 众筹成功 |\n| ---- | ---- | ------- | ------ | -------- |\n| all  | idea | preheat | going  | success  |",
  "example": "/modian/zhongchou",
  "heat": 54,
  "location": "zhongchou.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "众筹",
  "parameters": {
    "category": "分类，见下表，默认为全部",
    "sort": "排序，见下表，默认为最新上线",
    "status": "状态，见下表，默认为全部"
  },
  "path": "/zhongchou/:category?/:sort?/:status?",
  "radar": [
    {
      "source": [
        "zhongchou.modian.com/:category/:sort/:status"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -1275875263 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "全部 - 全部状态 - 最新上线 - 摩点众筹 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59241270393578496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhongchou.modian.com/all/top_time/all",
      "title": "全部 - 全部状态 - 最新上线 - 摩点众筹",
      "type": "feed",
      "url": "rsshub://modian/zhongchou"
    },
    {
      "description": "桌游 - 众筹中 - 最新上线 - 摩点众筹 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82230096897464320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zhongchou.modian.com/tablegames/top_time/going",
      "title": "桌游 - 众筹中 - 最新上线 - 摩点众筹",
      "type": "feed",
      "url": "rsshub://modian/zhongchou/tablegames/top_time/going"
    }
  ]
}
```
