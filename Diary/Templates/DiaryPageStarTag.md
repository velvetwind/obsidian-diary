---
cssclass: diary, diary_plus
---

<%* const tag = tp.system.prompt("С каким тегом показать записи?") _%>
<span class="diary__year">\#<%tag%></span>

```dataview
table WITHOUT ID "<a href=\"obsidian://advanced-uri?filename=" + choice(Категория = "Ссылка", regexreplace(substring(diary-link, 2), "]]", "") + "&heading=" + dateformat(date(Дата), "yyyy-MM-dd"),  file.name) + "\" class=\"diary__link\"><span class=\"diary__star" + choice(Избранное = false, "diary__hide", "") + "\"></span><span class=\"diary__date\">" + dateformat(Дата, "d MMMM yyyy / EEEE") + "</span><span class=\"diary__body\"><span class=\"diary__excerpt\"><span class=\"diary__title " + choice(Заголовок = null, "diary__hide", "") + "\">" + Заголовок + "</span><span class=\"" + choice(Заголовок = null, "diary__text-long", "diary__text") + choice(Адрес = null, choice(Погода = null, choice(contains(Настроение, 5) = false, choice(contains(Настроение, 4) = false, choice(contains(Настроение, 3) = false, choice(contains(Настроение, 2) = false, choice(contains(Настроение, 1) = false, choice(Заголовок = null, " diary__text-long-long", " diary__text-long"),""),""),""),""),""),""),"") + "\">" + Описание + "</span><span class=\"diary__position " + choice(Адрес = null, "diary__hide", "") + "\">" + Адрес + "</span><span class=\"diary__weather " + choice(Погода = null, "diary__hide", "") + "\"><span class=\"" + choice(Адрес = null, "", "diary__devide") + "\"></span>" + Погода + "</span><span class=\"diary__mood " + choice(contains(Настроение, 5), " diary__mood5", choice(contains(Настроение, 4), " diary__mood4", choice(contains(Настроение, 3), " diary__mood3", choice(contains(Настроение, 2), " diary__mood2", choice(contains(Настроение, 1), " diary__mood1", " diary__hide"))))) + "\"><span class=\"" + choice(Адрес = null, choice(Погода = null, "", "diary__devide"), "diary__devide") + "\"></span></span></span><span class=\"diary__imgContainer" + choice(Иллюстрация = null, " diary__hide", "") + "\"><img src=\"file://blank/Diary/Media/" + Иллюстрация + "\" class=\"diary__img\"></span></span></a>"  AS "`button-diaryMain` `button-diaryStarActiveReturn` `button-diaryAgo` `button-diaryMap` `button-diarySettings` `button-diaryNote`" FROM #<%tag%> WHERE Категория != null AND Категория != "Ссылка" SORT Дата desc
```