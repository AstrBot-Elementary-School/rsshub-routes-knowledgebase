# 哈尔滨工程大学 - 本科生院工作通知

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/ugs/news/:author?/:category?`
- Route Name: `本科生院工作通知`
- Example: `/hrbeu/ugs/news/jwc/jxap`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `XYenon`
- Source Location: `ugs/news.ts`
- Source Module: `_None_`

## Description
author 列表：

| 教务处 | 实践教学与交流处 | 教育评估处 | 专业建设处 | 国家大学生文化素质基地 | 教师教学发展中心 | 综合办公室 | 工作通知 |
| ------ | ---------------- | ---------- | ---------- | ---------------------- | ---------------- | ---------- | -------- |
| jwc    | sjjxyjlzx        | jypgc      | zyjsc      | gjdxswhszjd            | jsjxfzzx         | zhbgs      | gztz     |

category 列表：

`all` 为全部

教务处：

| 教学安排 | 考试管理 | 学籍管理 | 外语统考 | 成绩管理 |
| -------- | -------- | -------- | -------- | -------- |
| jxap     | ksgl     | xjgl     | wytk     | cjgl     |

实践教学与交流处：

| 实验教学 | 实验室建设 | 校外实习 | 学位论文 | 课程设计 | 创新创业 | 校际交流 |
| -------- | ---------- | -------- | -------- | -------- | -------- | -------- |
| syjx     | sysjs      | xwsx     | xwlw     | kcsj     | cxcy     | xjjl     |

教育评估处：

| 教学研究与教学成果 | 质量监控 |
| ------------------ | -------- |
| jxyjyjxcg          | zljk     |

专业建设处：

| 专业与教材建设 | 陈赓实验班 | 教学名师与优秀主讲教师 | 课程建设 | 双语教学 |
| -------------- | ---------- | ---------------------- | -------- | -------- |
| zyyjcjs        | cgsyb      | jxmsyyxzjjs            | kcjs     | syjx     |

国家大学生文化素质基地：无

教师教学发展中心：

| 教师培训 |
| -------- |
| jspx     |

综合办公室：

| 联系课程 |
| -------- |
| lxkc     |

工作通知：无

## Parameters
- `author`: 发布部门，默认为 `gztz`
- `category`: 分类，默认为 `all`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ugs.hrbeu.edu.cn/2821/list.htm`
- `target`: `/ugs/news/gztz/all`
### Rule 2
- `source`:
  - `ugs.hrbeu.edu.cn/jwc/list.htm`
- `target`: `/ugs/news/jwc/all`
### Rule 3
- `source`:
  - `ugs.hrbeu.edu.cn/2847/list.htm`
- `target`: `/ugs/news/jwc/jxap`
### Rule 4
- `source`:
  - `ugs.hrbeu.edu.cn/2895/list.htm`
- `target`: `/ugs/news/jwc/ksgl`
### Rule 5
- `source`:
  - `ugs.hrbeu.edu.cn/2902/list.htm`
- `target`: `/ugs/news/jwc/xjgl`
### Rule 6
- `source`:
  - `ugs.hrbeu.edu.cn/2897/list.htm`
- `target`: `/ugs/news/jwc/wytk`
### Rule 7
- `source`:
  - `ugs.hrbeu.edu.cn/2901/list.htm`
- `target`: `/ugs/news/jwc/cjgl`
### Rule 8
- `source`:
  - `ugs.hrbeu.edu.cn/3206/list.htm`
- `target`: `/ugs/news/sjjxyjlc/all`
### Rule 9
- `source`:
  - `ugs.hrbeu.edu.cn/2847/list.htm`
- `target`: `/ugs/news/sjjxyjlc/syjx`
### Rule 10
- `source`:
  - `ugs.hrbeu.edu.cn/sysjs/list.htm`
- `target`: `/ugs/news/sjjxyjlc/sysjs`
### Rule 11
- `source`:
  - `ugs.hrbeu.edu.cn/2909/list.htm`
- `target`: `/ugs/news/sjjxyjlc/xwsx`
### Rule 12
- `source`:
  - `ugs.hrbeu.edu.cn/2910/list.htm`
- `target`: `/ugs/news/sjjxyjlc/xwlw`
### Rule 13
- `source`:
  - `ugs.hrbeu.edu.cn/2911/list.htm`
- `target`: `/ugs/news/sjjxyjlc/kcsj`
### Rule 14
- `source`:
  - `ugs.hrbeu.edu.cn/2913/list.htm`
- `target`: `/ugs/news/sjjxyjlc/cxcy`
### Rule 15
- `source`:
  - `ugs.hrbeu.edu.cn/xjjl/list.htm`
- `target`: `/ugs/news/sjjxyjlc/xjjl`
### Rule 16
- `source`:
  - `ugs.hrbeu.edu.cn/3207/list.htm`
- `target`: `/ugs/news/jypgc/all`
### Rule 17
- `source`:
  - `ugs.hrbeu.edu.cn/2916/list.htm`
- `target`: `/ugs/news/jypgc/jxyjyjxcg`
### Rule 18
- `source`:
  - `ugs.hrbeu.edu.cn/2917/list.htm`
- `target`: `/ugs/news/jypgc/zljk`
### Rule 19
- `source`:
  - `ugs.hrbeu.edu.cn/3208/list.htm`
- `target`: `/ugs/news/zyjsc/all`
### Rule 20
- `source`:
  - `ugs.hrbeu.edu.cn/2914/list.htm`
- `target`: `/ugs/news/zyjsc/zyyjcjs`
### Rule 21
- `source`:
  - `ugs.hrbeu.edu.cn/2925/list.htm`
- `target`: `/ugs/news/zyjsc/cgsyb`
### Rule 22
- `source`:
  - `ugs.hrbeu.edu.cn/2918/list.htm`
- `target`: `/ugs/news/zyjsc/jxmsyyxzjjs`
### Rule 23
- `source`:
  - `ugs.hrbeu.edu.cn/2919/list.htm`
- `target`: `/ugs/news/zyjsc/ktjs`
### Rule 24
- `source`:
  - `ugs.hrbeu.edu.cn/2920/list.htm`
- `target`: `/ugs/news/zyjsc/syjx`
### Rule 25
- `source`:
  - `ugs.hrbeu.edu.cn/3209/list.htm`
- `target`: `/ugs/news/gjdxswhszjd/all`
### Rule 26
- `source`:
  - `ugs.hrbeu.edu.cn/3210/list.htm`
- `target`: `/ugs/news/jsjxfzzx/all`
### Rule 27
- `source`:
  - `ugs.hrbeu.edu.cn/2915/list.htm`
- `target`: `/ugs/news/jsjxfzzx/jspx`
### Rule 28
- `source`:
  - `ugs.hrbeu.edu.cn/3211/list.htm`
- `target`: `/ugs/news/zhbgs/all`
### Rule 29
- `source`:
  - `ugs.hrbeu.edu.cn/lxkc/list.htm`
- `target`: `/ugs/news/zhbgs/lxkc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "author 列表：\n\n| 教务处 | 实践教学与交流处 | 教育评估处 | 专业建设处 | 国家大学生文化素质基地 | 教师教学发展中心 | 综合办公室 | 工作通知 |\n| ------ | ---------------- | ---------- | ---------- | ---------------------- | ---------------- | ---------- | -------- |\n| jwc    | sjjxyjlzx        | jypgc      | zyjsc      | gjdxswhszjd            | jsjxfzzx         | zhbgs      | gztz     |\n\ncategory 列表：\n\n`all` 为全部\n\n教务处：\n\n| 教学安排 | 考试管理 | 学籍管理 | 外语统考 | 成绩管理 |\n| -------- | -------- | -------- | -------- | -------- |\n| jxap     | ksgl     | xjgl     | wytk     | cjgl     |\n\n实践教学与交流处：\n\n| 实验教学 | 实验室建设 | 校外实习 | 学位论文 | 课程设计 | 创新创业 | 校际交流 |\n| -------- | ---------- | -------- | -------- | -------- | -------- | -------- |\n| syjx     | sysjs      | xwsx     | xwlw     | kcsj     | cxcy     | xjjl     |\n\n教育评估处：\n\n| 教学研究与教学成果 | 质量监控 |\n| ------------------ | -------- |\n| jxyjyjxcg          | zljk     |\n\n专业建设处：\n\n| 专业与教材建设 | 陈赓实验班 | 教学名师与优秀主讲教师 | 课程建设 | 双语教学 |\n| -------------- | ---------- | ---------------------- | -------- | -------- |\n| zyyjcjs        | cgsyb      | jxmsyyxzjjs            | kcjs     | syjx     |\n\n国家大学生文化素质基地：无\n\n教师教学发展中心：\n\n| 教师培训 |\n| -------- |\n| jspx     |\n\n综合办公室：\n\n| 联系课程 |\n| -------- |\n| lxkc     |\n\n工作通知：无",
  "example": "/hrbeu/ugs/news/jwc/jxap",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "ugs/news.ts",
  "maintainers": [
    "XYenon"
  ],
  "name": "本科生院工作通知",
  "parameters": {
    "author": "发布部门，默认为 `gztz`",
    "category": "分类，默认为 `all`"
  },
  "path": "/ugs/news/:author?/:category?",
  "radar": [
    {
      "source": [
        "ugs.hrbeu.edu.cn/2821/list.htm"
      ],
      "target": "/ugs/news/gztz/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/jwc/list.htm"
      ],
      "target": "/ugs/news/jwc/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2847/list.htm"
      ],
      "target": "/ugs/news/jwc/jxap"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2895/list.htm"
      ],
      "target": "/ugs/news/jwc/ksgl"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2902/list.htm"
      ],
      "target": "/ugs/news/jwc/xjgl"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2897/list.htm"
      ],
      "target": "/ugs/news/jwc/wytk"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2901/list.htm"
      ],
      "target": "/ugs/news/jwc/cjgl"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/3206/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2847/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/syjx"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/sysjs/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/sysjs"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2909/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/xwsx"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2910/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/xwlw"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2911/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/kcsj"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2913/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/cxcy"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/xjjl/list.htm"
      ],
      "target": "/ugs/news/sjjxyjlc/xjjl"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/3207/list.htm"
      ],
      "target": "/ugs/news/jypgc/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2916/list.htm"
      ],
      "target": "/ugs/news/jypgc/jxyjyjxcg"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2917/list.htm"
      ],
      "target": "/ugs/news/jypgc/zljk"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/3208/list.htm"
      ],
      "target": "/ugs/news/zyjsc/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2914/list.htm"
      ],
      "target": "/ugs/news/zyjsc/zyyjcjs"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2925/list.htm"
      ],
      "target": "/ugs/news/zyjsc/cgsyb"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2918/list.htm"
      ],
      "target": "/ugs/news/zyjsc/jxmsyyxzjjs"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2919/list.htm"
      ],
      "target": "/ugs/news/zyjsc/ktjs"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2920/list.htm"
      ],
      "target": "/ugs/news/zyjsc/syjx"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/3209/list.htm"
      ],
      "target": "/ugs/news/gjdxswhszjd/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/3210/list.htm"
      ],
      "target": "/ugs/news/jsjxfzzx/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/2915/list.htm"
      ],
      "target": "/ugs/news/jsjxfzzx/jspx"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/3211/list.htm"
      ],
      "target": "/ugs/news/zhbgs/all"
    },
    {
      "source": [
        "ugs.hrbeu.edu.cn/lxkc/list.htm"
      ],
      "target": "/ugs/news/zhbgs/lxkc"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "哈尔滨工程大学本科生院工作通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82712133983555608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://ugs.hrbeu.edu.cn/jwc/list.htm",
      "title": "哈尔滨工程大学本科生院工作通知",
      "type": "feed",
      "url": "rsshub://hrbeu/ugs/news/jwc/all"
    }
  ]
}
```
