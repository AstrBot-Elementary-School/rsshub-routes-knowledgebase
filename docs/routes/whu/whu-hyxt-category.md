# 武汉大学 - 弘毅学堂

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/hyxt/:category{.+}?`
- Route Name: `弘毅学堂`
- Example: `/whu/hyxt`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `hyxt.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 通知公告 | 学子风采 | 学术论坛 |
| -------- | -------- | -------- | -------- |
| xwdt     | tzgg     | xzfc     | xslt     |

<details>
  <summary>更多分类</summary>

#### 学堂简报

| 学堂简报 |
| -------- |
| xtjb     |

#### 人才培养

| 人才培养 | 招生工作  | 培养方案  | 科研训练  | 毕业去向  | 学习资源  |
| -------- | --------- | --------- | --------- | --------- | --------- |
| rcpy     | rcpy/zsgz | rcpy/pyfa | rcpy/kyxl | rcpy/byqx | rcpy/xxzy |

#### 学生工作

| 学生工作 | 党团建设  | 学术交流  | 书院生活  | 奖助体系  | 事务服务  |
| -------- | --------- | --------- | --------- | --------- | --------- |
| xsgz     | xsgz/dtjs | xsgz/xsjl | xsgz/sysh | xsgz/jztx | xsgz/swfw |

#### 国际合作

| 国际合作 | 国际交流  | 交流分享  |
| -------- | --------- | --------- |
| gjhz     | gjhz/gjjl | gjhz/jlfx |

#### 校友风采

| 校友风采 |
| -------- |
| xyfc     |

</details>

此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条内容；如果不指定默认为 30。

## Parameters
- `category`: 分类，见下表，默认为 `tzgg`， 即 **通知公告**


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻动态 | 通知公告 | 学子风采 | 学术论坛 |\n| -------- | -------- | -------- | -------- |\n| xwdt     | tzgg     | xzfc     | xslt     |\n\n<details>\n  <summary>更多分类</summary>\n\n#### 学堂简报\n\n| 学堂简报 |\n| -------- |\n| xtjb     |\n\n#### 人才培养\n\n| 人才培养 | 招生工作  | 培养方案  | 科研训练  | 毕业去向  | 学习资源  |\n| -------- | --------- | --------- | --------- | --------- | --------- |\n| rcpy     | rcpy/zsgz | rcpy/pyfa | rcpy/kyxl | rcpy/byqx | rcpy/xxzy |\n\n#### 学生工作\n\n| 学生工作 | 党团建设  | 学术交流  | 书院生活  | 奖助体系  | 事务服务  |\n| -------- | --------- | --------- | --------- | --------- | --------- |\n| xsgz     | xsgz/dtjs | xsgz/xsjl | xsgz/sysh | xsgz/jztx | xsgz/swfw |\n\n#### 国际合作\n\n| 国际合作 | 国际交流  | 交流分享  |\n| -------- | --------- | --------- |\n| gjhz     | gjhz/gjjl | gjhz/jlfx |\n\n#### 校友风采\n\n| 校友风采 |\n| -------- |\n| xyfc     |\n\n</details>\n\n此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条内容；如果不指定默认为 30。",
  "example": "/whu/hyxt",
  "heat": 0,
  "location": "hyxt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "弘毅学堂",
  "parameters": {
    "category": "分类，见下表，默认为 `tzgg`， 即 **通知公告**"
  },
  "path": "/hyxt/:category{.+}?",
  "topFeeds": []
}
```
