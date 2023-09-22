<%"---"%>
Дата: <% tp.date.now("YYYY-MM-DD") %>
Категория: Ссылка
Заголовок: 
Описание: 
Адрес: 
Иллюстрация: 
Настроение: 3
Погода: 
Избранное: true
cssclasses:
  - diary
locations: 
<%"---"%>

`button-DiarySave` <% await tp.file.move("/Notes/_link_" + tp.date.now())%>%%<%"\<\% tp.file.rename(tp.frontmatter[\"Дата\"]) \%\>"%>%%

diary-link:: "<% "[[" + moment().endOf('month').format("YYYY-MM-DD") + "]]"%>"