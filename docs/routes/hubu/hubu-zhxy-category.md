# 湖北大学 - 资源环境学院

## Coverage
`index-only`

## Route
- Namespace: `hubu`
- Namespace Name: `湖北大学`
- Route Path: `/hubu/zhxy/:category{.+}?`
- Route Name: `资源环境学院`
- Example: `/hubu/zhxy/index/tzgg`
- URL: `zhxy.hubu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `zhxy.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [通知公告](https://zhxy.hubu.edu.cn/index/tzgg.htm)，网址为 `https://zhxy.hubu.edu.cn/index/tzgg.htm`。截取 `https://zhxy.hubu.edu.cn/` 到末尾 `.htm` 的部分 `index/tzgg` 作为参数填入，此时路由为 [`/hubu/zhxy/index/tzgg`](https://rsshub.app/hubu/zhxy/index/tzgg)。
:::

| [通知公告](https://zhxy.hubu.edu.cn/index/tzgg.htm) | [新闻动态](https://zhxy.hubu.edu.cn/index/xwdt.htm) |
| --------------------------------------------------- | --------------------------------------------------- |
| index/tzgg                                          | index/xwdt                                          |

#### [人才培养](https://zhxy.hubu.edu.cn/rcpy.htm)

| [人才培养](https://zhxy.hubu.edu.cn/rcpy.htm) | [本科生教育](https://zhxy.hubu.edu.cn/rcpy/bksjy.htm) | [研究生教育](https://zhxy.hubu.edu.cn/rcpy/yjsjy.htm) | [招生与就业](https://zhxy.hubu.edu.cn/rcpy/zsyjy/zsxx.htm) |
| --------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------- | ---------------------------------------------------------- |
| rcpy                                          | rcpy/bksjy                                            | rcpy/yjsjy                                            | rcpy/zsyjy/zsxx                                            |

#### [学科建设](https://zhxy.hubu.edu.cn/xkjianshe/zdxk.htm)

| [学科建设](https://zhxy.hubu.edu.cn/xkjianshe/zdxk.htm) | [重点学科](https://zhxy.hubu.edu.cn/xkjianshe/zdxk.htm) | [硕士点](https://zhxy.hubu.edu.cn/xkjianshe/ssd.htm) | [博士点](https://zhxy.hubu.edu.cn/xkjianshe/bsd.htm) |
| ------------------------------------------------------- | ------------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| xkjianshe/zdxk                                          | xkjianshe/zdxk                                          | xkjianshe/ssd                                        | xkjianshe/bsd                                        |

#### [科研服务](https://zhxy.hubu.edu.cn/kyfw.htm)

| [科研服务](https://zhxy.hubu.edu.cn/kyfw.htm) | [科研动态](https://zhxy.hubu.edu.cn/kyfw/kydongt.htm) | [学术交流](https://zhxy.hubu.edu.cn/kyfw/xsjl.htm) | [科研平台](https://zhxy.hubu.edu.cn/kyfw/keyapt.htm) | [社会服务](https://zhxy.hubu.edu.cn/kyfw/shfuw.htm) |
| --------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------- | --------------------------------------------------- |
| kyfw                                          | kyfw/kydongt                                          | kyfw/xsjl                                          | kyfw/keyapt                                          | kyfw/shfuw                                          |

#### [党群工作](https://zhxy.hubu.edu.cn/dqgz.htm)

| [党群工作](https://zhxy.hubu.edu.cn/dqgz.htm) | [党建工作](https://zhxy.hubu.edu.cn/dqgz/djgz/jgdj.htm) | [工会工作](https://zhxy.hubu.edu.cn/dqgz/ghgon.htm) |
| --------------------------------------------- | ------------------------------------------------------- | --------------------------------------------------- |
| dqgz                                          | dqgz/djgz/jgdj                                          | dqgz/ghgon                                          |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，默认为[通知公告](https://zhxy.hubu.edu.cn/index/tzgg.htm)


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
- `title`: `通知公告`
- `source`:
  - `zhxy.hubu.edu.cn/index/tzgg.htm`
- `target`: `/zhxy/index/tzgg`
### Rule 2
- `title`: `新闻动态`
- `source`:
  - `zhxy.hubu.edu.cn/index/xwdt.htm`
- `target`: `/zhxy/index/xwdt`
### Rule 3
- `title`: `人才培养`
- `source`:
  - `zhxy.hubu.edu.cn/rcpy.htm`
- `target`: `/zhxy/rcpy`
### Rule 4
- `title`: `人才培养 - 本科生教育`
- `source`:
  - `zhxy.hubu.edu.cn/rcpy/bksjy.htm`
- `target`: `/zhxy/rcpy/bksjy`
### Rule 5
- `title`: `人才培养 - 研究生教育`
- `source`:
  - `zhxy.hubu.edu.cn/rcpy/yjsjy.htm`
- `target`: `/zhxy/rcpy/yjsjy`
### Rule 6
- `title`: `人才培养 - 招生与就业`
- `source`:
  - `zhxy.hubu.edu.cn/rcpy/zsyjy/zsxx.htm`
- `target`: `/zhxy/rcpy/zsyjy/zsxx`
### Rule 7
- `title`: `学科建设`
- `source`:
  - `zhxy.hubu.edu.cn/xkjianshe/zdxk.htm`
- `target`: `/zhxy/xkjianshe/zdxk`
### Rule 8
- `title`: `学科建设 - 重点学科`
- `source`:
  - `zhxy.hubu.edu.cn/xkjianshe/zdxk.htm`
- `target`: `/zhxy/xkjianshe/zdxk`
### Rule 9
- `title`: `学科建设 - 硕士点`
- `source`:
  - `zhxy.hubu.edu.cn/xkjianshe/ssd.htm`
- `target`: `/zhxy/xkjianshe/ssd`
### Rule 10
- `title`: `学科建设 - 博士点`
- `source`:
  - `zhxy.hubu.edu.cn/xkjianshe/bsd.htm`
- `target`: `/zhxy/xkjianshe/bsd`
### Rule 11
- `title`: `科研服务`
- `source`:
  - `zhxy.hubu.edu.cn/kyfw.htm`
- `target`: `/zhxy/kyfw`
### Rule 12
- `title`: `科研服务 - 科研动态`
- `source`:
  - `zhxy.hubu.edu.cn/kyfw/kydongt.htm`
- `target`: `/zhxy/kyfw/kydongt`
### Rule 13
- `title`: `科研服务 - 学术交流`
- `source`:
  - `zhxy.hubu.edu.cn/kyfw/xsjl.htm`
- `target`: `/zhxy/kyfw/xsjl`
### Rule 14
- `title`: `科研服务 - 科研平台`
- `source`:
  - `zhxy.hubu.edu.cn/kyfw/keyapt.htm`
- `target`: `/zhxy/kyfw/keyapt`
### Rule 15
- `title`: `科研服务 - 社会服务`
- `source`:
  - `zhxy.hubu.edu.cn/kyfw/shfuw.htm`
- `target`: `/zhxy/kyfw/shfuw`
### Rule 16
- `title`: `党群工作`
- `source`:
  - `zhxy.hubu.edu.cn/dqgz.htm`
- `target`: `/zhxy/dqgz`
### Rule 17
- `title`: `党群工作 - 党建工作`
- `source`:
  - `zhxy.hubu.edu.cn/dqgz/djgz/jgdj.htm`
- `target`: `/zhxy/dqgz/djgz/jgdj`
### Rule 18
- `title`: `党群工作 - 工会工作`
- `source`:
  - `zhxy.hubu.edu.cn/dqgz/ghgon.htm`
- `target`: `/zhxy/dqgz/ghgon`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n若订阅 [通知公告](https://zhxy.hubu.edu.cn/index/tzgg.htm)，网址为 `https://zhxy.hubu.edu.cn/index/tzgg.htm`。截取 `https://zhxy.hubu.edu.cn/` 到末尾 `.htm` 的部分 `index/tzgg` 作为参数填入，此时路由为 [`/hubu/zhxy/index/tzgg`](https://rsshub.app/hubu/zhxy/index/tzgg)。\n:::\n\n| [通知公告](https://zhxy.hubu.edu.cn/index/tzgg.htm) | [新闻动态](https://zhxy.hubu.edu.cn/index/xwdt.htm) |\n| --------------------------------------------------- | --------------------------------------------------- |\n| index/tzgg                                          | index/xwdt                                          |\n\n#### [人才培养](https://zhxy.hubu.edu.cn/rcpy.htm)\n\n| [人才培养](https://zhxy.hubu.edu.cn/rcpy.htm) | [本科生教育](https://zhxy.hubu.edu.cn/rcpy/bksjy.htm) | [研究生教育](https://zhxy.hubu.edu.cn/rcpy/yjsjy.htm) | [招生与就业](https://zhxy.hubu.edu.cn/rcpy/zsyjy/zsxx.htm) |\n| --------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------- | ---------------------------------------------------------- |\n| rcpy                                          | rcpy/bksjy                                            | rcpy/yjsjy                                            | rcpy/zsyjy/zsxx                                            |\n\n#### [学科建设](https://zhxy.hubu.edu.cn/xkjianshe/zdxk.htm)\n\n| [学科建设](https://zhxy.hubu.edu.cn/xkjianshe/zdxk.htm) | [重点学科](https://zhxy.hubu.edu.cn/xkjianshe/zdxk.htm) | [硕士点](https://zhxy.hubu.edu.cn/xkjianshe/ssd.htm) | [博士点](https://zhxy.hubu.edu.cn/xkjianshe/bsd.htm) |\n| ------------------------------------------------------- | ------------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |\n| xkjianshe/zdxk                                          | xkjianshe/zdxk                                          | xkjianshe/ssd                                        | xkjianshe/bsd                                        |\n\n#### [科研服务](https://zhxy.hubu.edu.cn/kyfw.htm)\n\n| [科研服务](https://zhxy.hubu.edu.cn/kyfw.htm) | [科研动态](https://zhxy.hubu.edu.cn/kyfw/kydongt.htm) | [学术交流](https://zhxy.hubu.edu.cn/kyfw/xsjl.htm) | [科研平台](https://zhxy.hubu.edu.cn/kyfw/keyapt.htm) | [社会服务](https://zhxy.hubu.edu.cn/kyfw/shfuw.htm) |\n| --------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------- | --------------------------------------------------- |\n| kyfw                                          | kyfw/kydongt                                          | kyfw/xsjl                                          | kyfw/keyapt                                          | kyfw/shfuw                                          |\n\n#### [党群工作](https://zhxy.hubu.edu.cn/dqgz.htm)\n\n| [党群工作](https://zhxy.hubu.edu.cn/dqgz.htm) | [党建工作](https://zhxy.hubu.edu.cn/dqgz/djgz/jgdj.htm) | [工会工作](https://zhxy.hubu.edu.cn/dqgz/ghgon.htm) |\n| --------------------------------------------- | ------------------------------------------------------- | --------------------------------------------------- |\n| dqgz                                          | dqgz/djgz/jgdj                                          | dqgz/ghgon                                          |",
  "example": "/hubu/zhxy/index/tzgg",
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
  "location": "zhxy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资源环境学院",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，默认为[通知公告](https://zhxy.hubu.edu.cn/index/tzgg.htm)"
  },
  "path": "/zhxy/:category{.+}?",
  "radar": [
    {
      "source": [
        "zhxy.hubu.edu.cn/index/tzgg.htm"
      ],
      "target": "/zhxy/index/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/index/xwdt.htm"
      ],
      "target": "/zhxy/index/xwdt",
      "title": "新闻动态"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/rcpy.htm"
      ],
      "target": "/zhxy/rcpy",
      "title": "人才培养"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/rcpy/bksjy.htm"
      ],
      "target": "/zhxy/rcpy/bksjy",
      "title": "人才培养 - 本科生教育"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/rcpy/yjsjy.htm"
      ],
      "target": "/zhxy/rcpy/yjsjy",
      "title": "人才培养 - 研究生教育"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/rcpy/zsyjy/zsxx.htm"
      ],
      "target": "/zhxy/rcpy/zsyjy/zsxx",
      "title": "人才培养 - 招生与就业"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/xkjianshe/zdxk.htm"
      ],
      "target": "/zhxy/xkjianshe/zdxk",
      "title": "学科建设"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/xkjianshe/zdxk.htm"
      ],
      "target": "/zhxy/xkjianshe/zdxk",
      "title": "学科建设 - 重点学科"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/xkjianshe/ssd.htm"
      ],
      "target": "/zhxy/xkjianshe/ssd",
      "title": "学科建设 - 硕士点"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/xkjianshe/bsd.htm"
      ],
      "target": "/zhxy/xkjianshe/bsd",
      "title": "学科建设 - 博士点"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/kyfw.htm"
      ],
      "target": "/zhxy/kyfw",
      "title": "科研服务"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/kyfw/kydongt.htm"
      ],
      "target": "/zhxy/kyfw/kydongt",
      "title": "科研服务 - 科研动态"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/kyfw/xsjl.htm"
      ],
      "target": "/zhxy/kyfw/xsjl",
      "title": "科研服务 - 学术交流"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/kyfw/keyapt.htm"
      ],
      "target": "/zhxy/kyfw/keyapt",
      "title": "科研服务 - 科研平台"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/kyfw/shfuw.htm"
      ],
      "target": "/zhxy/kyfw/shfuw",
      "title": "科研服务 - 社会服务"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/dqgz.htm"
      ],
      "target": "/zhxy/dqgz",
      "title": "党群工作"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/dqgz/djgz/jgdj.htm"
      ],
      "target": "/zhxy/dqgz/djgz/jgdj",
      "title": "党群工作 - 党建工作"
    },
    {
      "source": [
        "zhxy.hubu.edu.cn/dqgz/ghgon.htm"
      ],
      "target": "/zhxy/dqgz/ghgon",
      "title": "党群工作 - 工会工作"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "zhxy.hubu.edu.cn"
}
```
