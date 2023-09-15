<%"---"%>
Дата: <% tp.date.now("YYYY-MM-DD") %>
Категория: Запись дня
Заголовок: 
Описание: 
Адрес: 
Иллюстрация: 
Настроение: 3
Погода: 
Избранное: false
cssclasses:
  - diary
locations:
<%"---"%>

`button-save` <% await tp.file.move("/Notes/" + tp.date.now())%>%%<%"\<\% tp.file.rename(tp.frontmatter[\"Дата\"]) \%\>"%>%%

# <% tp.date.now("D MMMM YYYY / dddd") %>

#метки

Запись

***
[[<% tp.date.now("YYYY") %>-12-31-EG|<% tp.date.now("YYYY") %>]]