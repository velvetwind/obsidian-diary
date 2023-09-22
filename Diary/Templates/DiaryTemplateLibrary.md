<%"---"%>
Дата: 0001-01-<% tp.date.now("DD") %>
Категория: Библиотека
Заголовок: 
Описание: 
Адрес: 
Иллюстрация: 
Настроение: 
Погода: 
Избранное: false
cssclasses:
  - diary
locations: 
<%"---"%>

`button-DiarySave` <% await tp.file.move("/Notes/" + tp.date.now())%>%%<%"\<\% tp.file.rename(tp.frontmatter[\"Дата\"]) \%\>"%>%%

Текст