# 西安电子科技大学 - 研究生院/卓越工程师学院

## Coverage
`index-only`

## Route
- Namespace: `xidian`
- Namespace Name: `西安电子科技大学`
- Route Path: `/xidian/gr/:category?`
- Route Name: `研究生院/卓越工程师学院`
- Example: `/xidian/gr/home_tzgg1`
- URL: `gr.xidian.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ZiHao256`
- Source Location: `gr.ts`
- Source Module: `_None_`

## Description
| 文章来源                    | 参数          |
| --------------------------- | ------------- |
| ✅主页 - 最新动态           | home\_zxdt    |
| ✅主页 - 通知公告           | home\_tzgg1   |
| ✅主页 - 讲座报告           | home\_jzbg    |
| ✅研院介绍 - 基本情况       | yyjs\_jbqk    |
| ✅研院介绍 - 机构设置       | yyjs\_jbqk1   |
| ✅研院介绍 - 部门领导       | yyjs\_jbqk2   |
| ✅研院介绍 - 服务指南       | yyjs\_jbqk3   |
| ✅研院介绍 - 学院联系方式   | yyjs\_jbqk4   |
| ✅招生信息                  | yjsy          |
| ✅招生信息 - 硕士研究生招生 | yjsy\_yjszs   |
| ✅招生信息 - 博士研究生招生 | yjsy\_bsyjszs |
| ✅招生信息 - 其他类型招生   | yjsy\_qtlxzs  |
| ✅培养管理                  | pygl          |
| ✅培养管理 - 学术学位       | pygl\_xsxw    |
| ✅培养管理 - 专业学位       | pygl\_zyxw    |
| ✅培养管理 - 教学管理       | pygl\_jxgl    |
| ✅培养管理 - 课程建设       | pygl\_jxgl1   |
| ✅培养管理 - 管理规定       | pygl\_jxgl2   |
| ✅培养管理 - 国际交流       | pygl\_jxgl3   |
| ✅培养管理 - 办事流程       | pygl\_bslc    |
| ✅学位授予                  | xwsy          |
| ✅学位授予 - 通知公告       | xwsy\_tzgg    |
| ✅学位授予 - 规章制度       | xwsy\_gzzd    |
| ✅学位授予 - 授位名单       | xwsy\_swmd    |
| ✅学位授予 - 资料下载       | xwsy\_zlxz    |

## Parameters
- `category`: 通知类别，默认为主页-通知公告


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
  - `gr.xidian.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 文章来源                    | 参数          |\n| --------------------------- | ------------- |\n| ✅主页 - 最新动态           | home\\_zxdt    |\n| ✅主页 - 通知公告           | home\\_tzgg1   |\n| ✅主页 - 讲座报告           | home\\_jzbg    |\n| ✅研院介绍 - 基本情况       | yyjs\\_jbqk    |\n| ✅研院介绍 - 机构设置       | yyjs\\_jbqk1   |\n| ✅研院介绍 - 部门领导       | yyjs\\_jbqk2   |\n| ✅研院介绍 - 服务指南       | yyjs\\_jbqk3   |\n| ✅研院介绍 - 学院联系方式   | yyjs\\_jbqk4   |\n| ✅招生信息                  | yjsy          |\n| ✅招生信息 - 硕士研究生招生 | yjsy\\_yjszs   |\n| ✅招生信息 - 博士研究生招生 | yjsy\\_bsyjszs |\n| ✅招生信息 - 其他类型招生   | yjsy\\_qtlxzs  |\n| ✅培养管理                  | pygl          |\n| ✅培养管理 - 学术学位       | pygl\\_xsxw    |\n| ✅培养管理 - 专业学位       | pygl\\_zyxw    |\n| ✅培养管理 - 教学管理       | pygl\\_jxgl    |\n| ✅培养管理 - 课程建设       | pygl\\_jxgl1   |\n| ✅培养管理 - 管理规定       | pygl\\_jxgl2   |\n| ✅培养管理 - 国际交流       | pygl\\_jxgl3   |\n| ✅培养管理 - 办事流程       | pygl\\_bslc    |\n| ✅学位授予                  | xwsy          |\n| ✅学位授予 - 通知公告       | xwsy\\_tzgg    |\n| ✅学位授予 - 规章制度       | xwsy\\_gzzd    |\n| ✅学位授予 - 授位名单       | xwsy\\_swmd    |\n| ✅学位授予 - 资料下载       | xwsy\\_zlxz    |",
  "example": "/xidian/gr/home_tzgg1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "gr.ts",
  "maintainers": [
    "ZiHao256"
  ],
  "name": "研究生院/卓越工程师学院",
  "parameters": {
    "category": "通知类别，默认为主页-通知公告"
  },
  "path": "/gr/:category?",
  "radar": [
    {
      "source": [
        "gr.xidian.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "硕士研究生招生-研究生院/卓越工程师学院-西安电子科技大学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88422444595401728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gr.xidian.edu.cn//yjsy/yjszs.htm",
      "title": "硕士研究生招生-研究生院/卓越工程师学院-西安电子科技大学",
      "type": "feed",
      "url": "rsshub://xidian/gr/yjsy_yjszs"
    },
    {
      "description": "通知公告-研究生院-西安电子科技大学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88422062290453504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gr.xidian.edu.cn//tzgg1.htm",
      "title": "通知公告-研究生院-西安电子科技大学",
      "type": "feed",
      "url": "rsshub://xidian/gr/home_tzgg1"
    }
  ],
  "url": "gr.xidian.edu.cn"
}
```
