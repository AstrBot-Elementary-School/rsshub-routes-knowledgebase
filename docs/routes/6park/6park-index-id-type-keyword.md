# 留园网 - 首页

## Coverage
`index-only`

## Route
- Namespace: `6park`
- Namespace Name: `留园网`
- Route Path: `/6park/index/:id?/:type?/:keyword?`
- Route Name: `首页`
- Example: `/6park/index`
- URL: `club.6parkbbs.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, cscnk52`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 婚姻家庭 | 魅力时尚 | 女性频道 | 生活百态 | 美食厨房 | 非常影音 | 车迷沙龙 | 游戏天地 | 卡通漫画 | 体坛纵横 | 运动健身 | 电脑前线 | 数码家电 | 旅游风向 | 摄影部落 | 奇珍异宝 | 笑口常开 | 娱乐八卦 | 吃喝玩乐 | 文化长廊 | 军事纵横 | 百家论坛 | 科技频道 | 爱子情怀 | 健康人生 | 博论天下 | 史海钩沉 | 网际谈兵 | 经济观察 | 谈股论金 | 杂论闲侃 | 唯美乐园 | 学习园地 | 命理玄机 | 宠物情缘 | 网络歌坛 | 音乐殿堂 | 情感世界 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| life9    | life1    | chan10   | life2    | life6    | fr       | enter7   | enter3   | enter6   | enter5   | sport    | know1    | chan6    | life7    | chan8    | page     | enter1   | enter8   | netstar  | life10   | nz       | other    | chan2    | chan5    | life5    | bolun    | chan1    | military | finance  | chan4    | pk       | gz1      | gz2      | gz3      | life8    | chan7    | enter4   | life3    |

## Parameters
- `id`: 分站，见下表，默认为史海钩沉
- `type`: 类型，可选值为 gold、type，默认为空
- `keyword`: 关键词，可选，默认为空


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `club.6parkbbs.com/:id/index.php`
  - `club.6parkbbs.com/`
- `target`: `/:id?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 婚姻家庭 | 魅力时尚 | 女性频道 | 生活百态 | 美食厨房 | 非常影音 | 车迷沙龙 | 游戏天地 | 卡通漫画 | 体坛纵横 | 运动健身 | 电脑前线 | 数码家电 | 旅游风向 | 摄影部落 | 奇珍异宝 | 笑口常开 | 娱乐八卦 | 吃喝玩乐 | 文化长廊 | 军事纵横 | 百家论坛 | 科技频道 | 爱子情怀 | 健康人生 | 博论天下 | 史海钩沉 | 网际谈兵 | 经济观察 | 谈股论金 | 杂论闲侃 | 唯美乐园 | 学习园地 | 命理玄机 | 宠物情缘 | 网络歌坛 | 音乐殿堂 | 情感世界 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| life9    | life1    | chan10   | life2    | life6    | fr       | enter7   | enter3   | enter6   | enter5   | sport    | know1    | chan6    | life7    | chan8    | page     | enter1   | enter8   | netstar  | life10   | nz       | other    | chan2    | chan5    | life5    | bolun    | chan1    | military | finance  | chan4    | pk       | gz1      | gz2      | gz3      | life8    | chan7    | enter4   | life3    |",
  "example": "/6park/index",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "cscnk52"
  ],
  "name": "首页",
  "parameters": {
    "id": "分站，见下表，默认为史海钩沉",
    "keyword": "关键词，可选，默认为空",
    "type": "类型，可选值为 gold、type，默认为空"
  },
  "path": "/index/:id?/:type?/:keyword?",
  "radar": [
    {
      "source": [
        "club.6parkbbs.com/:id/index.php",
        "club.6parkbbs.com/"
      ],
      "target": "/:id?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
