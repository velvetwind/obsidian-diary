---
cssclass: diary, diary_plus
---
# Меню навигации

***

```button
name ◉
type type line(1) template
action DiaryPageMain
replace [1,100]
class diary-button
```
^button-diaryMain

```button
name ◉
type type line(1) template
action DiaryPageMainCategory
replace [1,100]
class diary-buttonActive
```
^button-diaryMainActive

```button
name ◉
type type line(1) template
action DiaryPageMain
replace [1,100]
class diary-buttonActive
```
^button-diaryMainActiveReturn

***

```button
name ★
type type line(1) template
action DiaryPageStar
replace [1,100]
class diary-button
```
^button-diaryStar

```button
name ★
type type line(1) template
action DiaryPageStarTag
replace [1,100]
class diary-buttonActive
```
^button-diaryStarActive

```button
name ★
type type line(1) template
action DiaryPageStar
replace [1,100]
class diary-buttonActive
```
^button-diaryStarActiveReturn

***

```button
name ◀◀
type type line(1) template
action DiaryPageAgo
replace [1,100]
class diary-button
```
^button-diaryAgo

```button
name ◀◀
type type line(1) template
action DiaryPageAgoYear
replace [1,100]
class diary-buttonActive
```
^button-diaryAgoActive

```button
name ◀◀
type type line(1) template
action DiaryPageAgo
replace [1,100]
class diary-buttonActive
```
^button-diaryAgoActiveReturn

***

```button
name ❖
type command
action Map View: Open Map View
class diary-button
```
^button-diaryMap

***

```button
name ✱*
type type line(1) template
action DiaryPageSettingsTemplates
replace [1,100]
class diary-button
```
^button-diarySettings

```button
name ✱*
type link
action obsidian://advanced-uri?vault=Diary&workspace=Заметки
class diary-buttonActive
```
^button-diarySettingsActive

***

```button
name ✚
type link
action obsidian://open?vault=Diary&file=DiaryNew
class diary-button-Link
```
^button-diaryNote

## Меню настроек

```button
name ➤ справочник
type link
action obsidian://open?vault=Diary&file=DiaryPageSettingsHowto
class diary-buttonWide
```
^button-diaryPageHowto

```button
name ◐ светлая тема
type command
action Использовать светлую тему
class diary-buttonWide
```
^button-diaryLight

```button
name ◑ темная тема
type command
action Использовать темную тему
class diary-buttonWide
```
^button-diaryDark

```button
name ♯ теги дневника
type link
type type line(1) template
action DiaryPageSettingsTags
replace [1,100]
class diary-buttonWide
```
^button-diaryPageSettingsTags

```button
name ♯ теги дневника
class diary-buttonWideActive
```
^button-diaryPageSettingsTagsActive

```button
name ❐ список шаблонов
type link
type type line(1) template
action DiaryPageSettingsTemplates
replace [1,100]
class diary-buttonWide
```
^button-diaryPageSettingsTemplates

```button
name ❐ список шаблонов
class diary-buttonWideActive
```
^button-diaryPageSettingsTemplatesActive


# Кнопки действий
***

```button
name ✚ выбрать шаблон
type line(6) template
action DiaryNewChoice
replace [6,6]
class diary-buttonWide
```
^button-diaryNoteCreate

```button
name Сохранить
type command
action Templater: Replace templates in the active file
remove true
class diary-buttonWide
```
^button-save

```button
name ◉ DIARY
type link
action obsidian://advanced-uri?vault=Diary&workspace=Дневник
class diary-buttonWide
```
^button-diaryOpen