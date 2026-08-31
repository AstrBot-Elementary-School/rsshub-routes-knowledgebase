# 四川农业大学 - 二课活动

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/sicau/jk/:gid/:typeId/:sortType/:token`
- Route Name: `二课活动`
- Example: `/sicau/jk/0/0/2/8d95466cf63e537292b303cb92b5958c`
- URL: `jk.sicau.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hualiong`
- Source Location: `jk.ts`
- Source Module: `_None_`

## Description
::: tip
**本校学生**可以直接 POST `https://jk.sicau.edu.cn/user/login/v1.0.0/snoLogin` 从返回结果中的 `token` 字段拿到个人令牌，记得在 url 后添加以下**查询参数**：

- sid: `f1c97a0e81c24e98adb1ebdadca0699b`
- loginName: `你的学号`
- password: `你的i川农密码`

:::

::: warning
由于 i 川农后台有请求限制，为避免一次性大量请求而被限流，每次只请求结果的第一页数据，即前 20 条
:::

**活动所属组织 ID：**

| ID | 组织                 | ID | 组织               | ID | 组织                   | ID | 组织                   |
| -- | -------------------- | -- | ------------------ | -- | ---------------------- | -- | ---------------------- |
| 0  | 全部组织             | 14 | 校纪委             | 28 | 食品学院               | 42 | 经济学院               |
| 1  | 管理学院             | 15 | 生命科学学院       | 29 | 环境学院               | 43 | 机电学院               |
| 2  | 学生心理健康服务中心 | 16 | 水利水电学院       | 30 | 国家重点实验室         | 44 | 都江堰校区综合办后管科 |
| 3  | 档案馆               | 17 | 国合处             | 31 | 党委统战部             | 45 | 园艺学院               |
| 4  | 马克思主义学院       | 18 | 商旅学院           | 32 | 草业科技学院           | 46 | 资源学院               |
| 5  | 都江堰校区党政办     | 19 | 风景园林学院       | 33 | 商学院                 | 47 | 学生处                 |
| 6  | 土木工程学院         | 20 | 建筑与城乡规划学院 | 34 | 党委组织部             | 48 | 农学院                 |
| 7  | 林学院               | 21 | 体育学院           | 35 | 校团委                 | 49 | 公共管理学院           |
| 8  | 动物医学院           | 22 | 校体委             | 36 | 法学院                 | 50 | 图书馆                 |
| 9  | 保卫处               | 23 | 校区团委           | 37 | 水稻研究所             | 51 | 校学生会               |
| 10 | 理学院               | 24 | 后勤管理处         | 38 | 研究生院               | 52 | 动物科技学院           |
| 11 | 艺术与传媒学院       | 25 | 教务处             | 39 | 后勤服务总公司         | 53 | 信息工程学院           |
| 12 | 大学生艺术团         | 26 | 人文学院           | 40 | 招生就业处             |    |                        |
| 13 | 都江堰校区基础教学部 | 27 | 党委宣传部         | 41 | 学生社团管理与服务中心 |    |                        |

**活动类别 ID：**

| ID | 组织             | ID | 组织                 | ID | 组织           |
| -- | ---------------- | -- | -------------------- | -- | -------------- |
| 0  | 所有类别         | 5  | 校本文化（校规校纪） | 10 | 体质测试       |
| 1  | 党团学习         | 6  | 德育 — 社会实践      | 11 | 文化艺术活动   |
| 2  | 学生干部社会工作 | 7  | 创新创业类           | 12 | 文艺演出或讲座 |
| 3  | 校院班任务       | 8  | 科技学术讲座         | 13 | 劳动教育       |
| 4  | 德育（志愿公益） | 9  | 体育活动（新）       |    |                |

**排序方式：**

| 即将开始 | 最新活动 | 可参与 |
| -------- | -------- | ------ |
| 1        | 2        | 4      |

## Parameters
- `gid`: 活动所属组织ID，见下表
- `typeId`: 活动类别ID，见下表
- `sortType`: 排序方式，见下表
- `token`: 访问令牌，可通过示例中的令牌直接访问（会过期）


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
    "university"
  ],
  "description": "::: tip\n**本校学生**可以直接 POST `https://jk.sicau.edu.cn/user/login/v1.0.0/snoLogin` 从返回结果中的 `token` 字段拿到个人令牌，记得在 url 后添加以下**查询参数**：\n\n- sid: `f1c97a0e81c24e98adb1ebdadca0699b`\n- loginName: `你的学号`\n- password: `你的i川农密码`\n\n:::\n\n::: warning\n由于 i 川农后台有请求限制，为避免一次性大量请求而被限流，每次只请求结果的第一页数据，即前 20 条\n:::\n\n**活动所属组织 ID：**\n\n| ID | 组织                 | ID | 组织               | ID | 组织                   | ID | 组织                   |\n| -- | -------------------- | -- | ------------------ | -- | ---------------------- | -- | ---------------------- |\n| 0  | 全部组织             | 14 | 校纪委             | 28 | 食品学院               | 42 | 经济学院               |\n| 1  | 管理学院             | 15 | 生命科学学院       | 29 | 环境学院               | 43 | 机电学院               |\n| 2  | 学生心理健康服务中心 | 16 | 水利水电学院       | 30 | 国家重点实验室         | 44 | 都江堰校区综合办后管科 |\n| 3  | 档案馆               | 17 | 国合处             | 31 | 党委统战部             | 45 | 园艺学院               |\n| 4  | 马克思主义学院       | 18 | 商旅学院           | 32 | 草业科技学院           | 46 | 资源学院               |\n| 5  | 都江堰校区党政办     | 19 | 风景园林学院       | 33 | 商学院                 | 47 | 学生处                 |\n| 6  | 土木工程学院         | 20 | 建筑与城乡规划学院 | 34 | 党委组织部             | 48 | 农学院                 |\n| 7  | 林学院               | 21 | 体育学院           | 35 | 校团委                 | 49 | 公共管理学院           |\n| 8  | 动物医学院           | 22 | 校体委             | 36 | 法学院                 | 50 | 图书馆                 |\n| 9  | 保卫处               | 23 | 校区团委           | 37 | 水稻研究所             | 51 | 校学生会               |\n| 10 | 理学院               | 24 | 后勤管理处         | 38 | 研究生院               | 52 | 动物科技学院           |\n| 11 | 艺术与传媒学院       | 25 | 教务处             | 39 | 后勤服务总公司         | 53 | 信息工程学院           |\n| 12 | 大学生艺术团         | 26 | 人文学院           | 40 | 招生就业处             |    |                        |\n| 13 | 都江堰校区基础教学部 | 27 | 党委宣传部         | 41 | 学生社团管理与服务中心 |    |                        |\n\n**活动类别 ID：**\n\n| ID | 组织             | ID | 组织                 | ID | 组织           |\n| -- | ---------------- | -- | -------------------- | -- | -------------- |\n| 0  | 所有类别         | 5  | 校本文化（校规校纪） | 10 | 体质测试       |\n| 1  | 党团学习         | 6  | 德育 — 社会实践      | 11 | 文化艺术活动   |\n| 2  | 学生干部社会工作 | 7  | 创新创业类           | 12 | 文艺演出或讲座 |\n| 3  | 校院班任务       | 8  | 科技学术讲座         | 13 | 劳动教育       |\n| 4  | 德育（志愿公益） | 9  | 体育活动（新）       |    |                |\n\n**排序方式：**\n\n| 即将开始 | 最新活动 | 可参与 |\n| -------- | -------- | ------ |\n| 1        | 2        | 4      |",
  "example": "/sicau/jk/0/0/2/8d95466cf63e537292b303cb92b5958c",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jk.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "二课活动",
  "parameters": {
    "gid": "活动所属组织ID，见下表",
    "sortType": "排序方式，见下表",
    "token": "访问令牌，可通过示例中的令牌直接访问（会过期）",
    "typeId": "活动类别ID，见下表"
  },
  "path": "/jk/:gid/:typeId/:sortType/:token",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jk.sicau.edu.cn"
}
```
