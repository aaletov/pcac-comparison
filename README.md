# Шаблон диплома для СПбПУ ВШПИ 2022

Не идеален, но за основу взять можно

Изменения кидайте пулл реквестом

В списке литературы нужны sortkey = 1 для рускоязычных чтоб они шли раньше 


## Запуск 
Советую использовать VSCode и расширение. Иначе xelatex

## Уже реализовано 
* Документ
  * Поля 30 10 20 20
  * Шрифт Times new roman
  * Кегель 14
  * Интервал 1.5
  * Красная строка везде = 1.25см
  * Нумерация страниц по центру снизу
* Оглавление
  * Содержит основные разделы без нумерации
  * Выровнены по левому краю без отступов
  * Между заголовкой и страницей точечки ........
* Подписи
  * Рисунки  
    * Снизу по центру
    * Рис. N.n: Название
    * Нумерация по вложенности
  * Таблицы
    * Сверху слева
    * Таблица N: Название 
    * Нумерация сквозная на весь документ
  * Листинги
    * Сверху по центру 
    * Листинг N.n
    * Нумерация по вложенности
* Списки
  * Интервал равен интервалу документа
* Литература
  * Через biblatex 
  * На основе ГОСТ 7.0.5-2008 [стиль](https://github.com/odomanov/biblatex-gost/)
  * Иностранные источники в конце, остальное по тексту


## Обновления

- [21.05.2022]
  - обновление оформления заголовков секций
  - буквы подзаголовков на русском, например, Рис. 2.1 (а) и Рис. 2.1 (б)
  - добавлены приложения 
  - добавлены удобные ссылки на приложения `refAppendix{name}`и рисунки `refImg{name}`
