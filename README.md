# API
В рамках задания проверял XML на ошибки
# Задание и решение

| **№** | **Описание элемента**                         | **Ошибка**                                                                                                                                                                  |
|-------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | `<note date="12/05/2022">`                   | Указанный формат даты (`12/05/2022`) не соответствует стандарту [ISO 8601](https://www.w3schools.com/xml/schema_dtypes_date.asp).                                          |
| 2     | `<to><name>Alena</to></name>`                | Неправильный порядок закрывающих тэгов: `<to>` закрыт раньше, чем `<name>`.                                                                                               |
| 3     | `<lastname>Petrova</lastname>`               | Этот элемент находится вне контекста, т.е. неясно, к какому элементу он относится.                                                                                        |
| 4     | `<from>Alex</From>`                          | Несоответствие регистра открывающего и закрывающего тэгов: `<from>` и `<From>`.                                                                                          |
| 5     | `<update=12/05/2022><update>`                | Некорректный формат записи атрибута: отсутствуют кавычки вокруг значения.                                               |
| 6     | `</note>`                                    | Закрытие корневого тега `<note>` корректное.                                                                                                                              |

---

