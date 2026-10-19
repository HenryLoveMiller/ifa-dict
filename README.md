# IFA 词库 · ifa-dict

一线 IFA 日常展业用的中文输入词库：港险术语、产品名、展业话术，打字直接上屏。

> 🎁 **免费领完整版**：本仓库是「通用版」（61 条展业实战词条）。「完整版」多含 100 条展业话术短语 + 131 条 IFA 圈层术语（繁/简双版）——去 [Issue 区](https://github.com/HenryLoveMiller/ifa-dict/issues) 留言「话术版」，我发你网盘链接。

v0.1 共 61 条，词条来自真实展业用语，每周五更新。免费开放，欢迎同行一起养。

## 文件

- `ifa.dict.yaml` — 展业实战词库（61 条，Rime 格式）
- `dicts/ifa-circle-trad.dict.yaml` — IFA 圈层术语（繁体，133 条，Rime 格式）
- `dicts/ifa-circle-simp.dict.yaml` — IFA 圈层术语（简体，132 条，Rime 格式）

📖 在线版《港险 IFA 术语词典》（131 条，可搜索、中英对照、带释义）：https://pages.liaozh.top/ifa-shuyu-cidian-20261019.html

## 用法

- **Rime（小狼毫 / 鼠须管 / 同文）**：把 `ifa.dict.yaml` 放进 Rime 用户目录，在方案里 `import` 即可。
- **搜狗 / 百度输入法**：用词库转换工具把 Rime 词库转成 `.scel` 再导入（搜狗细胞词库也支持直接投稿分享）。
- **水杉输入法**：参考 [msime-customdict](https://github.com/metasequoiaime/msime-customdict) 的格式规范。

## 加词

发现展业常用但词库里没有的词，欢迎提 Issue 或 PR：

```
词条<TAB>拼音码<TAB>词频
```

例如：

```
趸交	dun jiao	800
```

## 说明

- 词条均为通用行业用语，不含任何客户信息。
- 产品名称、条款口径以各保险公司官网为准，词库只解决打字效率问题。
- License: MIT
