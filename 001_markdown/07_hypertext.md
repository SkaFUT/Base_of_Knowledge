# Тема: Гиперссылки

    Гиперссылки позволяют добавлять в текст ссылки на различный контент в интернете(Статьи, видео, картинки), а также ссылаться на локальные документы на компутрахтере, например на другие .md файлы.

^e89034

## Синтаксис
### Первый вариант классический
    [Текст ссылки](Ссылка)
### Для создания ссылки нужно:  
Указать текст ссылки, **то что будет видно** в **квадратных [], а __саму ссылку__ в круглых ()**.  

[Ссылочка на мой контактик](https://vk.com/rafuslik) 

>[!Important]
>_В VSCode Такими ссылками можно указывать на другие файлы для создания связей.
>НО в OBSIDIAN, для создания ссылки на локальный файл нужно указыdать [[]]._



### Второй вариант(не везде работает)
    [Текст ссылки][1]  

    [1]: Ссылка

Указать текст ссылки, **то что будет видно** в *квадратных []*, а **саму ссылку** *вынести в конец документа*, что то на подобии сноски.  
[Stepik][1]  

[1]: https://stepik.org/
***


### Ссылка с подсказками
    Для создания подсказки при наведении мыши на ссылку, нужно [Текст ссылки](Ссылка "Всплывающая подсказка")
Наведи курсор и узнай, что за ссылка))
[СсылОчка](https://vk.com/rafuslik "Контакт Рафека")  
***

### Сноски(не везде работает)
    Какой то текст в основном тексте[^1]
    [^1]: Текст находящийся в сноске
***


### Автоматические ссылки
    <Ссылка>
Просто ссылка в тексте, будет показываться как ссылка.  
<https://stepik.org/>
***


### Относительные ссылки
    [Текст ссылки на другой файл](../folder/file.md)

Позволяет удобно соединять документы между собой и создавать личную Базу Знаний.  
Например:  
[Списки](06_list.md)
***


### Добавление картинки в .md файл

^9a39ce

    ![Текст если картинки не будет](Ссылка на картинку)

    Также можно использовать html тег: 
    <img src="путь к картинке/ссылка" alt="alt-текст" width="150" height="150">
![Игорька не загрузили](https://avatars.cloudflare.steamstatic.com/c3b9c9624fe4b4612af5db8c5322c2ef525f77f0_medium.jpg)
***


### Ссылки в картинке
    [![alt-текст](Ссылка на картинку)](Ссылка на ресурс)
[![Картинка не найдена](https://topcheck.ru/wp-content/uploads/2022/04/stepik-otzyvy-o-kursah-i-obuchenii.png)](https://stepik.org/)
***

[[MarkDown|Оглавление]]