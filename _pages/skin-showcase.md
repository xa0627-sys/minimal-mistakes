---
title: "Vibe Coding 皮膚展示"
permalink: /skin-showcase/
layout: single
lang: zh-TW
classes: wide
---

想以巷弄跑步與 Vibe Coding 風格重新換裝，這裡提供四款新皮膚可直接在 `_config.yml` 設定 `minimal_mistakes_skin` 切換：

| 皮膚代號 | 特色 | 建議使用場景 |
| --- | --- | --- |
| `vibe-alley-dawn` | 霓虹日出、粉藍與洋紅的雙色漸層，呼應巷弄晨跑與資料流光感。 | 需要高亮主題、科技感文章或專案頁。 |
| `vibe-alley-night` | 深青雨夜、柔和霓虹招牌光，聚焦在文字可讀性與冷調氛圍。 | 長文閱讀、技術筆記與冷靜色系的敘事。 |
| `vibe-alley-fusion` | 將日出與雨夜並置，呈現雙色霓虹融合的節奏感。 | 作品集、案例展示與需要動態背景的頁面。 |
| `vibe-alley-ink` | 墨色極簡、帶點霓虹邊框與細緻粒子，沉穩又保有巷弄訊號感。 | 低調專業、文件頁或想保留留白的文章。 |

在 `_config.yml` 內更新：

```yaml
minimal_mistakes_skin: vibe-alley-dawn
```

其他皮膚可將值改為上表的代號即可，`bundle exec jekyll serve` 後重新整理即可看到效果。
