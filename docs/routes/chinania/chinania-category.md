# 中国有色金属工业网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `chinania`
- Namespace Name: `中国有色金属工业网`
- Route Path: `/chinania/:category{.+}?`
- Route Name: `分类`
- Example: `/chinania/xiehuidongtai/xiehuitongzhi`
- URL: `www.chinania.org.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [协会通知](https://www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/)，网址为 `https://www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/`。截取 `https://www.chinania.org.cn/html` 到末尾 `/` 的部分 `xiehuidongtai/xiehuitongzhi` 作为参数填入，此时路由为 [`/chinania/xiehuidongtai/xiehuitongzhi`](https://rsshub.app/chinania/xiehuidongtai/xiehuitongzhi)。
:::

<details>
<summary>更多分类</summary>

#### [协会动态](https://www.chinania.org.cn/html/xiehuidongtai/)

| [协会动态](https://www.chinania.org.cn/html/xiehuidongtai/xiehuidongtai/)              | [协会通知](https://www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/)              | [有色企业 50 强](https://www.chinania.org.cn/html/xiehuidongtai/youseqiye50qiang/)           |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| [xiehuidongtai/xiehuidongtai](https://rsshub.app/chinania/xiehuidongtai/xiehuidongtai) | [xiehuidongtai/xiehuitongzhi](https://rsshub.app/chinania/xiehuidongtai/xiehuitongzhi) | [xiehuidongtai/youseqiye50qiang](https://rsshub.app/chinania/xiehuidongtai/youseqiye50qiang) |

#### [党建工作](https://www.chinania.org.cn/html/djgz/)

| [协会党建](https://www.chinania.org.cn/html/djgz/xiehuidangjian/)      | [行业党建](https://www.chinania.org.cn/html/djgz/hangyedangjian/)      |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [djgz/xiehuidangjian](https://rsshub.app/chinania/djgz/xiehuidangjian) | [djgz/hangyedangjian](https://rsshub.app/chinania/djgz/hangyedangjian) |

#### [行业新闻](https://www.chinania.org.cn/html/hangyexinwen/)

| [时政要闻](https://www.chinania.org.cn/html/hangyexinwen/shizhengyaowen/)              | [要闻](https://www.chinania.org.cn/html/hangyexinwen/yaowen/)          | [行业新闻](https://www.chinania.org.cn/html/hangyexinwen/guoneixinwen/)            | [资讯](https://www.chinania.org.cn/html/hangyexinwen/zixun/)         |
| -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [hangyexinwen/shizhengyaowen](https://rsshub.app/chinania/hangyexinwen/shizhengyaowen) | [hangyexinwen/yaowen](https://rsshub.app/chinania/hangyexinwen/yaowen) | [hangyexinwen/guoneixinwen](https://rsshub.app/chinania/hangyexinwen/guoneixinwen) | [hangyexinwen/zixun](https://rsshub.app/chinania/hangyexinwen/zixun) |

#### [人力资源](https://www.chinania.org.cn/html/renliziyuan/)

| [相关通知](https://www.chinania.org.cn/html/renliziyuan/xiangguantongzhi/)               | [人事招聘](https://www.chinania.org.cn/html/renliziyuan/renshizhaopin/)            |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| [renliziyuan/xiangguantongzhi](https://rsshub.app/chinania/renliziyuan/xiangguantongzhi) | [renliziyuan/renshizhaopin](https://rsshub.app/chinania/renliziyuan/renshizhaopin) |

#### [行业统计](https://www.chinania.org.cn/html/hangyetongji/jqzs/)

| [行业分析](https://www.chinania.org.cn/html/hangyetongji/tongji/)      | [数据统计](https://www.chinania.org.cn/html/hangyetongji/chanyeshuju/)           | [景气指数](https://www.chinania.org.cn/html/hangyetongji/jqzs/)    |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| [hangyetongji/tongji](https://rsshub.app/chinania/hangyetongji/tongji) | [hangyetongji/chanyeshuju](https://rsshub.app/chinania/hangyetongji/chanyeshuju) | [hangyetongji/jqzs](https://rsshub.app/chinania/hangyetongji/jqzs) |

#### [政策法规](https://www.chinania.org.cn/html/zcfg/zhengcefagui/)

| [政策法规](https://www.chinania.org.cn/html/zcfg/zhengcefagui/)    |
| ------------------------------------------------------------------ |
| [zcfg/zhengcefagui](https://rsshub.app/chinania/zcfg/zhengcefagui) |

#### [会议展览](https://www.chinania.org.cn/html/hyzl/huiyizhanlan/)

| [会展通知](https://www.chinania.org.cn/html/hyzl/huiyizhanlan/)    | [会展报道](https://www.chinania.org.cn/html/hyzl/huizhanbaodao/)     |
| ------------------------------------------------------------------ | -------------------------------------------------------------------- |
| [hyzl/huiyizhanlan](https://rsshub.app/chinania/hyzl/huiyizhanlan) | [hyzl/huizhanbaodao](https://rsshub.app/chinania/hyzl/huizhanbaodao) |

</details>

## Parameters
- `category`: 分类，默认为 `xiehuidongtai/xiehuitongzhi`，即协会通知，可在对应分类页 URL 中找到


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
  - `www.chinania.org.cn/html/:category`
### Rule 2
- `title`: `协会动态 - 协会动态`
- `source`:
  - `www.chinania.org.cn/html/xiehuidongtai/xiehuidongtai/`
- `target`: `/xiehuidongtai/xiehuidongtai`
### Rule 3
- `title`: `协会动态 - 协会通知`
- `source`:
  - `www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/`
- `target`: `/xiehuidongtai/xiehuitongzhi`
### Rule 4
- `title`: `协会动态 - 有色企业50强`
- `source`:
  - `www.chinania.org.cn/html/xiehuidongtai/youseqiye50qiang/`
- `target`: `/xiehuidongtai/youseqiye50qiang`
### Rule 5
- `title`: `党建工作 - 协会党建`
- `source`:
  - `www.chinania.org.cn/html/djgz/xiehuidangjian/`
- `target`: `/djgz/xiehuidangjian`
### Rule 6
- `title`: `党建工作 - 行业党建`
- `source`:
  - `www.chinania.org.cn/html/djgz/hangyedangjian/`
- `target`: `/djgz/hangyedangjian`
### Rule 7
- `title`: `会议展览 - 会展通知`
- `source`:
  - `www.chinania.org.cn/html/hyzl/huiyizhanlan/`
- `target`: `/hyzl/huiyizhanlan`
### Rule 8
- `title`: `会议展览 - 会展报道`
- `source`:
  - `www.chinania.org.cn/html/hyzl/huizhanbaodao/`
- `target`: `/hyzl/huizhanbaodao`
### Rule 9
- `title`: `行业新闻 - 时政要闻`
- `source`:
  - `www.chinania.org.cn/html/hangyexinwen/shizhengyaowen/`
- `target`: `/hangyexinwen/shizhengyaowen`
### Rule 10
- `title`: `行业新闻 - 要闻`
- `source`:
  - `www.chinania.org.cn/html/hangyexinwen/yaowen/`
- `target`: `/hangyexinwen/yaowen`
### Rule 11
- `title`: `行业新闻 - 行业新闻`
- `source`:
  - `www.chinania.org.cn/html/hangyexinwen/guoneixinwen/`
- `target`: `/hangyexinwen/guoneixinwen`
### Rule 12
- `title`: `行业新闻 - 资讯`
- `source`:
  - `www.chinania.org.cn/html/hangyexinwen/zixun/`
- `target`: `/hangyexinwen/zixun`
### Rule 13
- `title`: `行业统计 - 行业分析`
- `source`:
  - `www.chinania.org.cn/html/hangyetongji/tongji/`
- `target`: `/hangyetongji/tongji`
### Rule 14
- `title`: `行业统计 - 数据统计`
- `source`:
  - `www.chinania.org.cn/html/hangyetongji/chanyeshuju/`
- `target`: `/hangyetongji/chanyeshuju`
### Rule 15
- `title`: `行业统计 - 景气指数`
- `source`:
  - `www.chinania.org.cn/html/hangyetongji/jqzs/`
- `target`: `/hangyetongji/jqzs`
### Rule 16
- `title`: `人力资源 - 相关通知`
- `source`:
  - `www.chinania.org.cn/html/renliziyuan/xiangguantongzhi/`
- `target`: `/renliziyuan/xiangguantongzhi`
### Rule 17
- `title`: `人力资源 - 人事招聘`
- `source`:
  - `www.chinania.org.cn/html/renliziyuan/renshizhaopin/`
- `target`: `/renliziyuan/renshizhaopin`
### Rule 18
- `title`: `政策法规 - 政策法规`
- `source`:
  - `www.chinania.org.cn/html/zcfg/zhengcefagui/`
- `target`: `/zcfg/zhengcefagui`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [协会通知](https://www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/)，网址为 `https://www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/`。截取 `https://www.chinania.org.cn/html` 到末尾 `/` 的部分 `xiehuidongtai/xiehuitongzhi` 作为参数填入，此时路由为 [`/chinania/xiehuidongtai/xiehuitongzhi`](https://rsshub.app/chinania/xiehuidongtai/xiehuitongzhi)。\n:::\n\n<details>\n<summary>更多分类</summary>\n\n#### [协会动态](https://www.chinania.org.cn/html/xiehuidongtai/)\n\n| [协会动态](https://www.chinania.org.cn/html/xiehuidongtai/xiehuidongtai/)              | [协会通知](https://www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/)              | [有色企业 50 强](https://www.chinania.org.cn/html/xiehuidongtai/youseqiye50qiang/)           |\n| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |\n| [xiehuidongtai/xiehuidongtai](https://rsshub.app/chinania/xiehuidongtai/xiehuidongtai) | [xiehuidongtai/xiehuitongzhi](https://rsshub.app/chinania/xiehuidongtai/xiehuitongzhi) | [xiehuidongtai/youseqiye50qiang](https://rsshub.app/chinania/xiehuidongtai/youseqiye50qiang) |\n\n#### [党建工作](https://www.chinania.org.cn/html/djgz/)\n\n| [协会党建](https://www.chinania.org.cn/html/djgz/xiehuidangjian/)      | [行业党建](https://www.chinania.org.cn/html/djgz/hangyedangjian/)      |\n| ---------------------------------------------------------------------- | ---------------------------------------------------------------------- |\n| [djgz/xiehuidangjian](https://rsshub.app/chinania/djgz/xiehuidangjian) | [djgz/hangyedangjian](https://rsshub.app/chinania/djgz/hangyedangjian) |\n\n#### [行业新闻](https://www.chinania.org.cn/html/hangyexinwen/)\n\n| [时政要闻](https://www.chinania.org.cn/html/hangyexinwen/shizhengyaowen/)              | [要闻](https://www.chinania.org.cn/html/hangyexinwen/yaowen/)          | [行业新闻](https://www.chinania.org.cn/html/hangyexinwen/guoneixinwen/)            | [资讯](https://www.chinania.org.cn/html/hangyexinwen/zixun/)         |\n| -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------- |\n| [hangyexinwen/shizhengyaowen](https://rsshub.app/chinania/hangyexinwen/shizhengyaowen) | [hangyexinwen/yaowen](https://rsshub.app/chinania/hangyexinwen/yaowen) | [hangyexinwen/guoneixinwen](https://rsshub.app/chinania/hangyexinwen/guoneixinwen) | [hangyexinwen/zixun](https://rsshub.app/chinania/hangyexinwen/zixun) |\n\n#### [人力资源](https://www.chinania.org.cn/html/renliziyuan/)\n\n| [相关通知](https://www.chinania.org.cn/html/renliziyuan/xiangguantongzhi/)               | [人事招聘](https://www.chinania.org.cn/html/renliziyuan/renshizhaopin/)            |\n| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |\n| [renliziyuan/xiangguantongzhi](https://rsshub.app/chinania/renliziyuan/xiangguantongzhi) | [renliziyuan/renshizhaopin](https://rsshub.app/chinania/renliziyuan/renshizhaopin) |\n\n#### [行业统计](https://www.chinania.org.cn/html/hangyetongji/jqzs/)\n\n| [行业分析](https://www.chinania.org.cn/html/hangyetongji/tongji/)      | [数据统计](https://www.chinania.org.cn/html/hangyetongji/chanyeshuju/)           | [景气指数](https://www.chinania.org.cn/html/hangyetongji/jqzs/)    |\n| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------ |\n| [hangyetongji/tongji](https://rsshub.app/chinania/hangyetongji/tongji) | [hangyetongji/chanyeshuju](https://rsshub.app/chinania/hangyetongji/chanyeshuju) | [hangyetongji/jqzs](https://rsshub.app/chinania/hangyetongji/jqzs) |\n\n#### [政策法规](https://www.chinania.org.cn/html/zcfg/zhengcefagui/)\n\n| [政策法规](https://www.chinania.org.cn/html/zcfg/zhengcefagui/)    |\n| ------------------------------------------------------------------ |\n| [zcfg/zhengcefagui](https://rsshub.app/chinania/zcfg/zhengcefagui) |\n\n#### [会议展览](https://www.chinania.org.cn/html/hyzl/huiyizhanlan/)\n\n| [会展通知](https://www.chinania.org.cn/html/hyzl/huiyizhanlan/)    | [会展报道](https://www.chinania.org.cn/html/hyzl/huizhanbaodao/)     |\n| ------------------------------------------------------------------ | -------------------------------------------------------------------- |\n| [hyzl/huiyizhanlan](https://rsshub.app/chinania/hyzl/huiyizhanlan) | [hyzl/huizhanbaodao](https://rsshub.app/chinania/hyzl/huizhanbaodao) |\n\n</details>",
  "example": "/chinania/xiehuidongtai/xiehuitongzhi",
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
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，默认为 `xiehuidongtai/xiehuitongzhi`，即协会通知，可在对应分类页 URL 中找到"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.chinania.org.cn/html/:category"
      ]
    },
    {
      "source": [
        "www.chinania.org.cn/html/xiehuidongtai/xiehuidongtai/"
      ],
      "target": "/xiehuidongtai/xiehuidongtai",
      "title": "协会动态 - 协会动态"
    },
    {
      "source": [
        "www.chinania.org.cn/html/xiehuidongtai/xiehuitongzhi/"
      ],
      "target": "/xiehuidongtai/xiehuitongzhi",
      "title": "协会动态 - 协会通知"
    },
    {
      "source": [
        "www.chinania.org.cn/html/xiehuidongtai/youseqiye50qiang/"
      ],
      "target": "/xiehuidongtai/youseqiye50qiang",
      "title": "协会动态 - 有色企业50强"
    },
    {
      "source": [
        "www.chinania.org.cn/html/djgz/xiehuidangjian/"
      ],
      "target": "/djgz/xiehuidangjian",
      "title": "党建工作 - 协会党建"
    },
    {
      "source": [
        "www.chinania.org.cn/html/djgz/hangyedangjian/"
      ],
      "target": "/djgz/hangyedangjian",
      "title": "党建工作 - 行业党建"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hyzl/huiyizhanlan/"
      ],
      "target": "/hyzl/huiyizhanlan",
      "title": "会议展览 - 会展通知"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hyzl/huizhanbaodao/"
      ],
      "target": "/hyzl/huizhanbaodao",
      "title": "会议展览 - 会展报道"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyexinwen/shizhengyaowen/"
      ],
      "target": "/hangyexinwen/shizhengyaowen",
      "title": "行业新闻 - 时政要闻"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyexinwen/yaowen/"
      ],
      "target": "/hangyexinwen/yaowen",
      "title": "行业新闻 - 要闻"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyexinwen/guoneixinwen/"
      ],
      "target": "/hangyexinwen/guoneixinwen",
      "title": "行业新闻 - 行业新闻"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyexinwen/zixun/"
      ],
      "target": "/hangyexinwen/zixun",
      "title": "行业新闻 - 资讯"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyetongji/tongji/"
      ],
      "target": "/hangyetongji/tongji",
      "title": "行业统计 - 行业分析"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyetongji/chanyeshuju/"
      ],
      "target": "/hangyetongji/chanyeshuju",
      "title": "行业统计 - 数据统计"
    },
    {
      "source": [
        "www.chinania.org.cn/html/hangyetongji/jqzs/"
      ],
      "target": "/hangyetongji/jqzs",
      "title": "行业统计 - 景气指数"
    },
    {
      "source": [
        "www.chinania.org.cn/html/renliziyuan/xiangguantongzhi/"
      ],
      "target": "/renliziyuan/xiangguantongzhi",
      "title": "人力资源 - 相关通知"
    },
    {
      "source": [
        "www.chinania.org.cn/html/renliziyuan/renshizhaopin/"
      ],
      "target": "/renliziyuan/renshizhaopin",
      "title": "人力资源 - 人事招聘"
    },
    {
      "source": [
        "www.chinania.org.cn/html/zcfg/zhengcefagui/"
      ],
      "target": "/zcfg/zhengcefagui",
      "title": "政策法规 - 政策法规"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.chinania.org.cn"
}
```
