# Тема: Введение в CSS
**C**ascading **S**tyle **S**heets(CSS) - **Язык стилей** используемый для описания **внешнего вида и форматирования документов**, написанных на языке HTML.
>_CSS позволяет делать веб страницы **красивыми** и приятными глазу, а также **оптимизировать** код_

    До появления CSS, верстальщики использовали теги внутри HTML, но на сегодняшний момент, использование этих тегов считается устаревшим и неправильным

## Синтаксис
В начале пишется для **чего будет использован стиль**, для тега, класса или Id, а потом в фигурных скобках **({})** пишутся через точку с запятой **(;)** стили и их значение после двоеточия **(:)**.
```CSS
Файл .css
h1{
    color: green;
    font-size: 24px;
}
p{
    color: blue;
}
```