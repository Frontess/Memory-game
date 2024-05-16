## Game memory numbers / Игра найди пару цифр (с адаптивом)    
****

### Игра аналогична игре ["Найди пару сладостей"](https://github.com/Frontess/Game_memory_sweets) и игре ["Найди пару цифр"](https://github.com/Frontess/Game-memory-numbers)

<img width="1436" alt="Снимок экрана 2024-04-29 в 17 54 21" src="https://github.com/Frontess/Memory-game/assets/127450758/e490480b-9b24-4a78-8775-7018bbe45887">


Поле карточек и функионал выполнены в JavaScript, в папке `js` файлы `main.js` и `card.js`

Таблица и новые элементы создаются в модицикации DOM, используя JavaScript.    

DOM-узел создаем следующими методами:
- создаем элементы `document.getElementById('id')`
- создаем новый элемент с заданным тегом `document.createElement('tag')`
- добавляем стили из bootstrap `classList.add('перечень стилей')`
- создаем новый текстовый узел с заданным текстом `document.textContent = 'наш текст'`
- добавляем элементы в таблицу `tableHeadTr.append($tableHeadThFIO)`

:game_die: Оформление игры: 
- игровое поле разделено на 16 одинаковых карточек, за которыми спрятаны пары цифр от :one: до :eight:.
- все цифры изначально находятся на игровом поле в случайном положении.

:game_die: Правила игры: 
- нажмите на карточку, запомните расположение цифры и найдите аналогичную на другой картoчке.
- если игрок нажал разные цифры, карточки закрываются и необходимо попытаться еще раз.
- игра заканчивается, когда игрок правильно нашел совпадения всех цифр.

:game_die: Технологический стек: JavaScript, HTML, CSS.

:100: Вы можете изменить цветовое оформление игры на своё усмотрение в файле `style.css`.
<div id="footer">
