---
cssclass: diary, diary_plus
---
# Меню навигации

***

```button
name ◉
type line(1) template
action DiaryFilterMain
replace [1,100]
class diary-button
```
^button-DiaryFilterMain

```button
name ◉
type line(1) template
action DiaryFilterMainCategory
replace [1,100]
class diary-buttonActive
```
^button-DiaryFilterMainActive

```button
name ◉
type type line(1) template
action DiaryFilterMain
replace [1,100]
class diary-buttonActive
```
^button-DiaryFilterMainActiveReturn

***

```button
name ★
type line(1) template
action DiaryFilterStar
replace [1,100]
class diary-button
```
^button-DiaryFilterStar

```button
name ★
type line(1) template
action DiaryFilterStarTag
replace [1,100]
class diary-buttonActive
```
^button-DiaryFilterStarActive

```button
name ★
type line(1) template
action DiaryFilterStar
replace [1,100]
class diary-buttonActive
```
^button-DiaryFilterStarActiveReturn

***

```button
name ◀◀
type line(1) template
action DiaryFilterAgo
replace [1,100]
class diary-button
```
^button-DiaryFilterAgo

```button
name ◀◀
type line(1) template
action DiaryFilterAgoYear
replace [1,100]
class diary-buttonActive
```
^button-DiaryFilterAgoActive

```button
name ◀◀
type line(1) template
action DiaryFilterAgo
replace [1,100]
class diary-buttonActive
```
^button-DiaryFilterAgoActiveReturn

***

```button
name ❖
type command
action Map View: Open Map View
class diary-button
```
^button-DiaryFilterMap

***

```button
name ✱*
type line(1) template
action DiaryFilterSettingsTemplates
replace [1,100]
class diary-button
```
^button-DiaryFilterSettings

```button
name ✱*
type link
action obsidian://advanced-uri?vault=Diary&workspace=Заметки
class diary-buttonActive
```
^button-DiaryFilterSettingsActive

***

```button
name ✚
type line(6) template
action DiaryNoteAdd
class diary-button-Link
```
^button-DiaryNoteAdd

## Меню настроек

```button
name ➤ справочник
type link
action obsidian://open?vault=Diary&file=DiaryFilterSettingsHelp
class diary-buttonWide
```
^button-DiaryFilterSettingsHelp

```button
name ◐ светлая тема
type command
action Использовать светлую тему
class diary-buttonWide
```
^button-DiaryLight

```button
name ◑ темная тема
type command
action Использовать темную тему
class diary-buttonWide
```
^button-DiaryDark

```button
name # теги дневника
type link
type line(1) template
action DiaryFilterSettingsTags
replace [1,100]
class diary-buttonWide
```
^button-DiaryFilterSettingsTags

```button
name # теги дневника
class diary-buttonWideActive
```
^button-DiaryFilterSettingsTagsActive

```button
name ❐ список шаблонов
type link
type line(1) template
action DiaryFilterSettingsTemplates
replace [1,100]
class diary-buttonWide
```
^button-DiaryFilterSettingsTemplates

```button
name ❐ список шаблонов
class diary-buttonWideActive
```
^button-DiaryFilterSettingsTemplatesActive


# Кнопки действий
***

```button
name Сохранить
type command
action Templater: Replace templates in the active file
remove true
class diary-buttonWide
```
^button-DiarySave

```button
name ◉ DIARY
type link
action obsidian://advanced-uri?vault=Diary&workspace=Дневник
class diary-buttonWide
```
^button-DiaryOpen