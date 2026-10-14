# 赣南医科大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `gmu`
- Namespace Name: `赣南医科大学`
- Route Path: `/gmu/yjs/:type/:subtype`
- Route Name: `研究生院`
- Example: `/gmu/yjs/zsgz/tzgg`
- URL: `gmu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrankFahey`
- Source Location: `yjs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "分类，见下表", "options": [{"label": "招生工作", "value": "zsgz"}, {"label": "培养工作", "value": "pygz"}, {"label": "学位工作", "value": "xwgz"}, {"label": "学生工作", "value": "xsgz"}, {"label": "下载中心", "value": "xzzx"}]}
- `subtype`: {"description": "子分类，见下表", "options": [{"label": "通知公告", "value": "tzgg"}, {"label": "新闻速递", "value": "xwsd"}, {"label": "规章制度", "value": "gzzd"}, {"label": "导师管理", "value": "dsgl"}, {"label": "学位管理", "value": "xwgl"}, {"label": "评估工作", "value": "pggz"}, {"label": "学生活动", "value": "xshd"}, {"label": "奖助工作", "value": "jzgz"}, {"label": "招生下载", "value": "zsxz"}, {"label": "培养下载", "value": "pyxz"}, {"label": "学位下载", "value": "xwxz"}]}


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
  - `yjs.gmu.cn/`
  - `yjs.gmu.cn/tzgg/zsgz.htm`
- `target`: `/yjs/zsgz/tzgg`
### Rule 2
- `title`: `培养工作 - 通知公告`
- `source`:
  - `yjs.gmu.cn/pygz/tzgg.htm`
- `target`: `/yjs/pygz/tzgg`
### Rule 3
- `title`: `培养工作 - 规章制度`
- `source`:
  - `yjs.gmu.cn/pygz/gzzd.htm`
- `target`: `/yjs/pygz/gzzd`
### Rule 4
- `title`: `学位工作 - 通知公告`
- `source`:
  - `yjs.gmu.cn/xwgz/tzgg.htm`
- `target`: `/yjs/xwgz/tzgg`
### Rule 5
- `title`: `学位工作 - 导师管理`
- `source`:
  - `yjs.gmu.cn/xwgz/dsgl.htm`
- `target`: `/yjs/xwgz/dsgl`
### Rule 6
- `title`: `学位工作 - 学位管理`
- `source`:
  - `yjs.gmu.cn/xwgz/xwgl.htm`
- `target`: `/yjs/xwgz/xwgl`
### Rule 7
- `title`: `学位工作 - 评估工作`
- `source`:
  - `yjs.gmu.cn/xwgz/pggz.htm`
- `target`: `/yjs/xwgz/pggz`
### Rule 8
- `title`: `学生工作 - 通知公告`
- `source`:
  - `yjs.gmu.cn/tzgg/xsgz.htm`
- `target`: `/yjs/xsgz/tzgg`
### Rule 9
- `title`: `学生工作 - 学生活动`
- `source`:
  - `yjs.gmu.cn/xsgz/xshd.htm`
- `target`: `/yjs/xsgz/xshd`
### Rule 10
- `title`: `学生工作 - 奖助工作`
- `source`:
  - `yjs.gmu.cn/xsgz/jzgz.htm`
- `target`: `/yjs/xsgz/jzgz`
### Rule 11
- `title`: `下载中心 - 招生下载`
- `source`:
  - `yjs.gmu.cn/xzzx/zsxz.htm`
- `target`: `/yjs/xzzx/zsxz`
### Rule 12
- `title`: `下载中心 - 培养下载`
- `source`:
  - `yjs.gmu.cn/xzzx/pyxz.htm`
- `target`: `/yjs/xzzx/pyxz`
### Rule 13
- `title`: `下载中心 - 学位下载`
- `source`:
  - `yjs.gmu.cn/xzzx/xwxz.htm`
- `target`: `/yjs/xzzx/xwxz`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gmu/yjs/zsgz/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yjs.ts",
  "maintainers": [
    "FrankFahey"
  ],
  "name": "研究生院",
  "parameters": {
    "subtype": {
      "description": "子分类，见下表",
      "options": [
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "新闻速递",
          "value": "xwsd"
        },
        {
          "label": "规章制度",
          "value": "gzzd"
        },
        {
          "label": "导师管理",
          "value": "dsgl"
        },
        {
          "label": "学位管理",
          "value": "xwgl"
        },
        {
          "label": "评估工作",
          "value": "pggz"
        },
        {
          "label": "学生活动",
          "value": "xshd"
        },
        {
          "label": "奖助工作",
          "value": "jzgz"
        },
        {
          "label": "招生下载",
          "value": "zsxz"
        },
        {
          "label": "培养下载",
          "value": "pyxz"
        },
        {
          "label": "学位下载",
          "value": "xwxz"
        }
      ]
    },
    "type": {
      "description": "分类，见下表",
      "options": [
        {
          "label": "招生工作",
          "value": "zsgz"
        },
        {
          "label": "培养工作",
          "value": "pygz"
        },
        {
          "label": "学位工作",
          "value": "xwgz"
        },
        {
          "label": "学生工作",
          "value": "xsgz"
        },
        {
          "label": "下载中心",
          "value": "xzzx"
        }
      ]
    }
  },
  "path": "/yjs/:type/:subtype",
  "radar": [
    {
      "source": [
        "yjs.gmu.cn/",
        "yjs.gmu.cn/tzgg/zsgz.htm"
      ],
      "target": "/yjs/zsgz/tzgg"
    },
    {
      "source": [
        "yjs.gmu.cn/pygz/tzgg.htm"
      ],
      "target": "/yjs/pygz/tzgg",
      "title": "培养工作 - 通知公告"
    },
    {
      "source": [
        "yjs.gmu.cn/pygz/gzzd.htm"
      ],
      "target": "/yjs/pygz/gzzd",
      "title": "培养工作 - 规章制度"
    },
    {
      "source": [
        "yjs.gmu.cn/xwgz/tzgg.htm"
      ],
      "target": "/yjs/xwgz/tzgg",
      "title": "学位工作 - 通知公告"
    },
    {
      "source": [
        "yjs.gmu.cn/xwgz/dsgl.htm"
      ],
      "target": "/yjs/xwgz/dsgl",
      "title": "学位工作 - 导师管理"
    },
    {
      "source": [
        "yjs.gmu.cn/xwgz/xwgl.htm"
      ],
      "target": "/yjs/xwgz/xwgl",
      "title": "学位工作 - 学位管理"
    },
    {
      "source": [
        "yjs.gmu.cn/xwgz/pggz.htm"
      ],
      "target": "/yjs/xwgz/pggz",
      "title": "学位工作 - 评估工作"
    },
    {
      "source": [
        "yjs.gmu.cn/tzgg/xsgz.htm"
      ],
      "target": "/yjs/xsgz/tzgg",
      "title": "学生工作 - 通知公告"
    },
    {
      "source": [
        "yjs.gmu.cn/xsgz/xshd.htm"
      ],
      "target": "/yjs/xsgz/xshd",
      "title": "学生工作 - 学生活动"
    },
    {
      "source": [
        "yjs.gmu.cn/xsgz/jzgz.htm"
      ],
      "target": "/yjs/xsgz/jzgz",
      "title": "学生工作 - 奖助工作"
    },
    {
      "source": [
        "yjs.gmu.cn/xzzx/zsxz.htm"
      ],
      "target": "/yjs/xzzx/zsxz",
      "title": "下载中心 - 招生下载"
    },
    {
      "source": [
        "yjs.gmu.cn/xzzx/pyxz.htm"
      ],
      "target": "/yjs/xzzx/pyxz",
      "title": "下载中心 - 培养下载"
    },
    {
      "source": [
        "yjs.gmu.cn/xzzx/xwxz.htm"
      ],
      "target": "/yjs/xzzx/xwxz",
      "title": "下载中心 - 学位下载"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
