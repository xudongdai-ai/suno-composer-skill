# Suno Songwriting Skill

[中文](README.md) | English

A songwriting assistant for GPT covering lyrics, genres, form, harmony, arrangement, instrumental music and focused revisions.

**81 genre profiles · 9 families · 17 forms · 26 harmony prototypes**

## Use it directly

1. Download [the complete English MD](en/01_Upload_to_GPT_Songwriting_Assistant.md) and attach it to a new GPT conversation.
2. Describe your theme, intended sound and vocal or instrumental preference.
3. Copy the relevant output to Suno's Styles, Lyrics and Exclude fields. For an instrumental, enable Instrumental and leave Lyrics empty.

```text
Use the uploaded Songwriting Assistant.
Write an English song about driving home at night and starting again.
Keep it warm and gently retro, with an easy-to-remember chorus.
Suggest the voice, tempo and structure.
Give me complete lyrics, English Styles, Exclude and an arrangement table.
```

You can also ask for lyrics only, music for unchanged lyrics, a chorus rewrite or an instrumental.

## Chinese and English documents

| Purpose | 中文 | English |
|---|---|---|
| Instructions | [先看这里](zh-CN/先看这里.md) | [Start here](en/00_Start_Here.md) |
| Upload to GPT | [完整 MD](zh-CN/01-作曲助手.md) | [Complete MD](en/01_Upload_to_GPT_Songwriting_Assistant.md) |
| Brief template | [填写需求](zh-CN/02_填写你的创作需求.md) | [Creative brief](en/02_Creative_Brief_Template.md) |
| Example requests | [复制示例](zh-CN/03_直接复制的提问示例.md) | [Example requests](en/03_Ready_to_Use_Requests.md) |
| Topic references | [分类参考](zh-CN/分类参考/) | [References](en/References/) |
| Genre profiles | [风格库](zh-CN/风格库/) | [Genre library](en/Genre_Library/) |

## Download packages

- [Chinese ZIP](downloads/suno-composer-skill-zh-CN.zip)
- [English ZIP](downloads/suno-composer-skill-en.zip)
- [Bilingual ZIP](downloads/suno-composer-skill-bilingual.zip)

## Use as a Skill

[SKILL.md](SKILL.md) is the standard entry point. Tools supporting local Skills can place the complete `suno-composer-skill` folder in their skill directory. Keep `zh-CN/` and `en/` together with the entry point. For ordinary GPT conversations, attach the complete MD linked above.

This repository provides text plans. Suno generates the audio; tempo, chords, sections and duration need listening checks.
