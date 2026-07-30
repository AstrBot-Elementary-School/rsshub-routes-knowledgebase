# 哈尔滨工业大学（深圳） - 教务部教务学务与学位管理所有栏目

## Coverage
`index-only`

## Route
- Namespace: `hitsz`
- Namespace Name: `哈尔滨工业大学（深圳）`
- Route Path: `/hitsz/due/general/:type?`
- Route Name: `教务部教务学务与学位管理所有栏目`
- Example: `/hitsz/due/general`
- URL: `due.hitsz.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `guohuiyuan`
- Source Location: `due.ts`
- Source Module: `_None_`

## Description
哈尔滨工业大学（深圳）教务部中教务学务和学位管理所有栏目的最新新闻汇总。

#### 栏目分组说明

支持按业务类型筛选，使用路径参数指定分组：

- `type=teaching` - 教务核心业务：教务管理、考务管理、注册管理、选课管理、成绩管理
- `type=studentStatus` - 学籍相关：本科生学籍管理、研究生学籍管理
- `type=teachingSupport` - 教学支持：教学信息化、奖助学金
- `type=education` - 学生培养：本科生新闻、硕士学位培养、博士学位培养
- `type=all` 或省略 - 所有栏目（默认）

#### 包含栏目：

- [教务管理](http://due.hitsz.edu.cn/jwxw/jwgl.htm)
- [考务管理](http://due.hitsz.edu.cn/jwxw/kwgl.htm)
- [注册管理](http://due.hitsz.edu.cn/jwxw/zcgl.htm)
- [选课管理](http://due.hitsz.edu.cn/jwxw/xkgl.htm)
- [成绩管理](http://due.hitsz.edu.cn/jwxw/cjgl.htm)
- [学籍管理（本）](http://due.hitsz.edu.cn/jwxw/xjgl_b_.htm)
- [学籍管理（研）](http://due.hitsz.edu.cn/jwxw/xjgl_y_.htm)
- [教学信息化](http://due.hitsz.edu.cn/jwxw/jxxxh.htm)
- [奖助学金](http://due.hitsz.edu.cn/jwxw/jzxj.htm)
- [本科生新闻](http://due.hitsz.edu.cn/xwgl/bksxw.htm)
- [硕士学位培养](http://due.hitsz.edu.cn/xwgl/ssxwpy/ktyzj.htm)
- [博士学位培养](http://due.hitsz.edu.cn/xwgl/bsxwpy/qqhj1.htm)

## Parameters
- `type`: {"default": "all", "description": "栏目类型筛选，默认all（所有栏目）", "options": [{"label": "所有栏目", "value": "all"}, {"label": "教务核心业务", "value": "teaching"}, {"label": "学籍相关", "value": "studentStatus"}, {"label": "教学支持", "value": "teachingSupport"}, {"label": "学生培养", "value": "education"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `due.hitsz.edu.cn/jwxw/jwgl.htm`
- `target`: `/hitsz/due/general`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "哈尔滨工业大学（深圳）教务部中教务学务和学位管理所有栏目的最新新闻汇总。\n\n#### 栏目分组说明\n\n支持按业务类型筛选，使用路径参数指定分组：\n\n- `type=teaching` - 教务核心业务：教务管理、考务管理、注册管理、选课管理、成绩管理\n- `type=studentStatus` - 学籍相关：本科生学籍管理、研究生学籍管理\n- `type=teachingSupport` - 教学支持：教学信息化、奖助学金\n- `type=education` - 学生培养：本科生新闻、硕士学位培养、博士学位培养\n- `type=all` 或省略 - 所有栏目（默认）\n\n#### 包含栏目：\n\n- [教务管理](http://due.hitsz.edu.cn/jwxw/jwgl.htm)\n- [考务管理](http://due.hitsz.edu.cn/jwxw/kwgl.htm)\n- [注册管理](http://due.hitsz.edu.cn/jwxw/zcgl.htm)\n- [选课管理](http://due.hitsz.edu.cn/jwxw/xkgl.htm)\n- [成绩管理](http://due.hitsz.edu.cn/jwxw/cjgl.htm)\n- [学籍管理（本）](http://due.hitsz.edu.cn/jwxw/xjgl_b_.htm)\n- [学籍管理（研）](http://due.hitsz.edu.cn/jwxw/xjgl_y_.htm)\n- [教学信息化](http://due.hitsz.edu.cn/jwxw/jxxxh.htm)\n- [奖助学金](http://due.hitsz.edu.cn/jwxw/jzxj.htm)\n- [本科生新闻](http://due.hitsz.edu.cn/xwgl/bksxw.htm)\n- [硕士学位培养](http://due.hitsz.edu.cn/xwgl/ssxwpy/ktyzj.htm)\n- [博士学位培养](http://due.hitsz.edu.cn/xwgl/bsxwpy/qqhj1.htm)",
  "example": "/hitsz/due/general",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "due.ts",
  "maintainers": [
    "guohuiyuan"
  ],
  "name": "教务部教务学务与学位管理所有栏目",
  "parameters": {
    "type": {
      "default": "all",
      "description": "栏目类型筛选，默认all（所有栏目）",
      "options": [
        {
          "label": "所有栏目",
          "value": "all"
        },
        {
          "label": "教务核心业务",
          "value": "teaching"
        },
        {
          "label": "学籍相关",
          "value": "studentStatus"
        },
        {
          "label": "教学支持",
          "value": "teachingSupport"
        },
        {
          "label": "学生培养",
          "value": "education"
        }
      ]
    }
  },
  "path": "/due/general/:type?",
  "radar": [
    {
      "source": [
        "due.hitsz.edu.cn/jwxw/jwgl.htm"
      ],
      "target": "/hitsz/due/general"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "due.hitsz.edu.cn"
}
```
