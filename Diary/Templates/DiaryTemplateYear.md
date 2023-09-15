<%"---"%>
Дата: <% moment().endOf('year').format("YYYY-MM-DD") %>
Категория: Итоги года
Заголовок: Итоги <% tp.date.now("YYYY") %> года
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

<% await tp.file.move("/Notes/" + moment().endOf('year').format("YYYY-MM-DD")) %>

# Итоги года / <% tp.date.now("YYYY") %>      

***
[[<% tp.date.now("YYYY", -400) %>-12-31|< <% tp.date.now("YYYY", -400) %>]] | [[<% tp.date.now("YYYY", +400) %>-12-31|<% tp.date.now("YYYY", +400) %> >]]
