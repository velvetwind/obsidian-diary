<%*
const templateName = await tp.system.suggester(["Запись дня", "Итоги месяца", "Итоги года", "Библиотека", "Ссылка"], ["DiaryTemplateDay", "DiaryTemplateMonth", "DiaryTemplateYear", "DiaryTemplateLibrary", "DiaryTemplateLink"])
tp.file.create_new(tp.file.find_tfile(templateName), "", true, "") 
_%>