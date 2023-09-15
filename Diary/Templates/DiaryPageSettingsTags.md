---
cssclass: diary, diary_plus
---

<small class="diary__year diary__yearFirst">Настройки</small>

**◉ DIARY V1.0**

- `button-diaryPageHowto`
- `button-diaryLight`
- `button-diaryDark`
- `button-diaryPageSettingsTagsActive`
- `button-diaryPageSettingsTemplates`

**ПЛАГИНЫ**

- [Dataview](obsidian://show-plugin?id=dataview)
- [Templater](obsidian://show-plugin?id=templater-obsidian)
- [Buttons](obsidian://show-plugin?id=buttons)
- [Map View](obsidian://show-plugin?id=obsidian-map-view)
- [Advanced URL](obsidian://show-plugin?id=obsidian-advanced-uri)
- [Minimal Theme Settings](obsidian://show-plugin?id=obsidian-minimal-settings)
- [Minimal (Тема)](https://github.com/kepano/obsidian-minimal)

**ТЕГИ**

```dataview 
TABLE WITHOUT ID ("- " + length(rows.file.link) + " " + tag ) AS "`button-diaryMain` `button-diaryStar` `button-diaryAgo` `button-diaryMap` `button-diarySettingsActive` `button-diaryNote`" WHERE Категория != null FLATTEN file.tags AS tag WHERE contains(tag, "") GROUP BY tag SORT length(rows.file.link) DESC 
```

***
[Страница проекта](https://evgenytarasov.ru/diary/?utm_source=diary&utm_medium=guide&utm_campaign=v1) • [Группа в Телеграм](https://t.me/vedenie_dnevnika) • GitHub