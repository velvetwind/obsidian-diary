<%"---"%>
Дата: <% moment().endOf('month').format("YYYY-MM-DD") %>
Категория: Итоги месяца
Заголовок: Итоги <% tp.date.now("MMMM")%>
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
<% await tp.file.move("/Notes/" + moment().endOf('month').format("YYYY-MM-DD")) %>
# Итоги <% tp.date.now("MMMM")%> 

## <% tp.date.now("YYYY-MM-DD") %>

## <% tp.date.now("YYYY-MM-DD", +1) %>

## <% tp.date.now("YYYY-MM-DD", +2) %>

## <% tp.date.now("YYYY-MM-DD", +3) %>

## <% tp.date.now("YYYY-MM-DD", +4) %>

## <% tp.date.now("YYYY-MM-DD", +5) %>

## <% tp.date.now("YYYY-MM-DD", +6) %>

## <% tp.date.now("YYYY-MM-DD", +7) %>

## <% tp.date.now("YYYY-MM-DD", +8) %>

## <% tp.date.now("YYYY-MM-DD", +9) %>

## <% tp.date.now("YYYY-MM-DD", +10) %>

## <% tp.date.now("YYYY-MM-DD", +11) %>

## <% tp.date.now("YYYY-MM-DD", +12) %>

## <% tp.date.now("YYYY-MM-DD", +13) %>

## <% tp.date.now("YYYY-MM-DD", +14) %>

## <% tp.date.now("YYYY-MM-DD", +15) %>

## <% tp.date.now("YYYY-MM-DD", +16) %>

## <% tp.date.now("YYYY-MM-DD", +17) %>

## <% tp.date.now("YYYY-MM-DD", +18) %>

## <% tp.date.now("YYYY-MM-DD", +19) %>

## <% tp.date.now("YYYY-MM-DD", +20) %>

## <% tp.date.now("YYYY-MM-DD", +21) %>

## <% tp.date.now("YYYY-MM-DD", +22) %>

## <% tp.date.now("YYYY-MM-DD", +23) %>

## <% tp.date.now("YYYY-MM-DD", +24) %>

## <% tp.date.now("YYYY-MM-DD", +25) %>

## <% tp.date.now("YYYY-MM-DD", +26) %>

## <% tp.date.now("YYYY-MM-DD", +27) %>

## <% tp.date.now("YYYY-MM-DD", +28) %>

## <% tp.date.now("YYYY-MM-DD", +29) %>

## <% tp.date.now("YYYY-MM-DD", +30) %>

***
[[<% moment().subtract(1, 'month').endOf('month').format("YYYY-MM-DD")%>|< <% moment().subtract(1, 'month').endOf('month').format("MMMM")%>]] | [[<% tp.date.now("YYYY") %>-12-31|<% tp.date.now("YYYY") %>]]  | [[<% moment().add(1, 'M').endOf('month').format("YYYY-MM-DD")%>|<% moment().add(1, 'M').endOf('month').format("MMMM")%> >]]