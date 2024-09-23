# бэйз тэги

- >< это символы тегов
- теги бывают парные (/) и непарные (meta)
- h1 - 6 - теги заголовков
- h1 - на странице не более одного раза
- p - тег параграфа
- img - тэг изображения
- ol (li) - список нумерован
- ul - нененумер список
- a - ссылка
-  - href = "#" - переход на верх страницы
   - href = "#down" -  переход к тэгу с id = "down"
   - target ="_blank" - атрибут для открытия ссылки в новой вкладке
   - href="tel: +375296666666" - ссылка на набор телефона
 
#CSS

- подключение  CSS в index.html - link
- файл CSS это обычный текстовый файл
- структура записи - селектор{ свойства: значения; }
- в качастве селектора используют - тэки, классы


#Блочная модель
- классическая - размер = контент + внутр.отступ (padding) + рамка (border) + внешний отступ (margin)
- упрощенный (box-sizing: border-box) - внешний отступ (margin) + все остальное
- костыль - между блоками ЕСТЬ зазор
- строчные элементы (буквицы) - размер аналогичен выше описанному  ... НО НЕ работае вверх-ввниз
- дизайн - скругление блоков с помощью border-radius

#Работа с изображениями (img) 
- единственный тэг который пропорционально изменяется по ОДНОЙ из сторон
- атрибут alt - атрибут сео-шника для пробвижения сайта
- изображения ведут себя как строчно-блочные элементы
- все изображения на сайте необходимо активизировать под их размеры
- анализ загрузки файлов сайта - F12 - Network - Ctrl + F5 

#Работа со шрифтами
- в любом браузере шрифтов НЕТ
- самые "бстрые" шрифты - системные
- к макету сайта обязательно прилагать шрифты
- базовый размер шрифтов 16 пикселей

#Работа с фоном и навигация 
- bgc - равномерный фон блока - все блоки прозрачные кроме блока с тегом body - он белый
- bgi - изображение на фоне - по умолчанию изображение клонирцуется по горизонтали и вертикали
- bgi - градиентная заливка...
- bgr - повторять или не повторять изображение на фоне
- bgs - изменяем размеры фонового изображения (cover)
- bgp - позиционирование фонового изображения (0,0 - верхний левый угол блока)
- bga - фиксация фонового изображения

  #Навигация и ссылки
  - тэг a - ссылки - три классическийх признака
    - синий цвет
    - подчеркивание
    - cursor: pointer (hover)
- логотип - видет на главную страницу сайта
- горизонтальное меню (3-7)
- вертикальное меню
- смешанное меню (недо-меню)
- поиск по сайту
- "Хлебные крошки" - путь страниц
- пагинация - разбитие инфы на страницы

#Позиционирование 

- position: absolute - элемент приподнимается и его место занимают соседи
- position: relative - соседи думают что элемент не смещается
  - изпользуется для ограничения перемещения по блоку (absolute)
- position: fixed - элемент подпрыгивает как абсолют ификсируется
- всепозиттион элементы можно смешать
  - left
  - right
- position (sticky) - прилипание - чтобы заработало нужно указать где блок должен прилипнуть
- 
#ОДностраничный сайт с видео фоном

- особое внимание к подбору видео фону (брать не тяжелые видео)
- при ярком видеоряде необходимо затушевать его 
  - bottom
- все позитион элементы можно приближать или отдалять z-index - работает только для позицианированных объектов

#Позиционирование Flex

- управление через "родителя" dissplay: flex;
- чтобы блоки "не поджимались" - flex-wrap: wrap;
- выравнивание в горизонте - justify-content
- выравнивание по вертикали - align-items
- иконочный шрифт - см интелект-карту - настройки такие как у обычного шрифта 

#Flex akordion

- flex-basis: 25% - базовая штрины флек контейнера
- text-shadow - тень вокруг текста (см интелект карту)

#Фреймворк Bootstrap
- набор готовых решений
- 12-колоночная система
- класс container - формирует адаптивгую обертку с отступами
- класс conteiner-fluid - формирует "обертку" на всю ширину экрана
- для верного управления 12-колоночной сеткой используется обертка с классом "row"
-  классы col-1..col-12 - указывают количество колонок для блоков внутри row E
 Extra small (xs)
Small (sm)
Medium (md)
Large (lg)
Extra large (xl)
Extra extra large (xxl)
- фиксированные внутренние отступы p-0..p-5
- фиксированные внешние отступы m-0...m-5
- интиресные готовые решения:
  - кнопки
  - аккардион
  - карусель (изображение одного размера)
  - навигационная панель (меню)
  - модальные окна
  - вне холста
  - карточки товаров
  - 
