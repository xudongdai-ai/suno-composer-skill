# Suno 作曲 Skill

中文 | [English](README.en.md)

给 GPT 使用的作曲助手，支持歌词、风格、曲式、和声、编曲、纯音乐和局部修改。

**81 种风格 · 9 个风格家族 · 17 种曲式 · 26 组和声原型**

## 直接使用

1. 下载 [中文完整 MD](zh-CN/01-作曲助手.md)，上传到 GPT 新对话。
2. 说明主题、想要的听感，以及人声或纯音乐。
3. 将输出分别复制到 Suno 的 Styles、Lyrics 和 Exclude；纯音乐开启 Instrumental，歌词栏留空。

```text
请按上传的作曲助手工作。
写一首中文歌，主题是夜里开车回家，温暖复古，副歌容易记住。
请建议人声、速度和曲式。
给完整歌词、英文 Styles、Exclude 和中文编曲表。
```

也可以只要求“只写歌词”“原词不改，只配曲”“只改副歌”或“做纯音乐”。

## 中英文文件

| 用途 | 中文 | English |
|---|---|---|
| 使用说明 | [先看这里](zh-CN/先看这里.md) | [Start here](en/00_Start_Here.md) |
| 上传给 GPT | [完整 MD](zh-CN/01-作曲助手.md) | [Complete MD](en/01_Upload_to_GPT_Songwriting_Assistant.md) |
| 需求模板 | [填写需求](zh-CN/02_填写你的创作需求.md) | [Creative brief](en/02_Creative_Brief_Template.md) |
| 提问示例 | [复制示例](zh-CN/03_直接复制的提问示例.md) | [Example requests](en/03_Ready_to_Use_Requests.md) |
| 分类资料 | [分类参考](zh-CN/分类参考/) | [References](en/References/) |
| 风格资料 | [风格库](zh-CN/风格库/) | [Genre library](en/Genre_Library/) |

## 下载包

- [中文版 ZIP](downloads/suno-composer-skill-zh-CN.zip)
- [English ZIP](downloads/suno-composer-skill-en.zip)
- [中英双语 ZIP](downloads/suno-composer-skill-bilingual.zip)

## 作为 Skill 使用

仓库根目录的 [SKILL.md](SKILL.md) 是标准入口。支持本地 Skills 的工具可以将整个 `suno-composer-skill` 文件夹放入其技能目录；保留 `zh-CN/` 和 `en/`，不要只复制入口文件。普通 GPT 对话直接上传上面的完整 MD 即可。

本仓库提供文字创作与制作方案。音频由 Suno 生成；速度、和弦、段落和时长需要试听核对。
