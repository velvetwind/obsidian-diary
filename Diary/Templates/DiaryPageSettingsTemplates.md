---
cssclass: diary, diary_plus
---

<small class="diary__year diary__yearFirst">Настройки</small>

**◉ DIARY V1.0**

- `button-diaryPageHowto`
- `button-diaryLight`
- `button-diaryDark`
- `button-diaryPageSettingsTags`
- `button-diaryPageSettingsTemplatesActive`

**ПЛАГИНЫ**

- [Dataview](obsidian://show-plugin?id=dataview)
- [Templater](obsidian://show-plugin?id=templater-obsidian)
- [Buttons](obsidian://show-plugin?id=buttons)
- [Map View](obsidian://show-plugin?id=obsidian-map-view)
- [Advanced URL](obsidian://show-plugin?id=obsidian-advanced-uri)
- [Minimal Theme Settings](obsidian://show-plugin?id=obsidian-minimal-settings)
- [Minimal (Тема)](https://github.com/kepano/obsidian-minimal)

**ШАБЛОНЫ**

```dataview
table WITHOUT ID " - " + file.link AS  "`button-diaryMain` `button-diaryStar` `button-diaryAgo` `button-diaryMap` `button-diarySettingsActive` `button-diaryNote`" WHERE contains(file.folder, "Templates") AND contains(file.name, "Diary") SORT file.name asc
```

***
[Страница проекта](https://evgenytarasov.ru/diary/?utm_source=diary&utm_medium=guide&utm_campaign=v1) • [Группа в Телеграм](https://t.me/vedenie_dnevnika) • GitHub