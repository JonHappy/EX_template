# EX_template
пример использования тэга  &lt;template&gt; для построения "модального" окна и меню, открывающегося
по правой кнопке мыши.<br>
-работает и в Firefox, надо только в about:config    dom.webcomponents.enabled  в true<br>
-в Firefox надо быть внимательнее с jquery https://learn.javascript.ru/webcomponent-build#проблема-с-jquery

Демонстрация "кадрирования" картинок.

- РАБОТАЕТ СHROME и FIREFOX!!!


- для наблюдения всех фич необходимо запускать в IDE.

- запускаемым файлом является index.html

в модальном окне(открываемого по клику по кнопке хххх), по клику по зелёному крестику, открывется новая вкладка (необходимо разрешить)
- загружатются картинки по кнопке "Выбрать файлы" либо методом Drag-and-drop в рамку
- ползунок слева - поворот картинки относительно центра рамки (дейстствует колесо мыши)
- перемещение картинки мышью, при нажатии на Shift/Ctrl ограничивается перемещение только по одной координате, добавляется возможность перемещения колесом мыши
- правый ползунок - изменение размера
- колесо мыши на катринке - изменение размера
- Shift/Ctrl + колесо мыши на катринке  - перемещение по осям
- красные ползунки внизу и справа - задают границы обрезки
- кнопка x/xx задаёт скорость изменения размера при помощи колеса мыши
- при сктановлении желаемого кадрирования полного размера - клик по кнопке "обрезать", справа появляется обрезанная картинка с крестиком.
- крестик позволяет удалить результат и повторить процесс кадрирования снова
- после изготовления картинки полного вида, предлагается произвести обрезку для превью(если предложенное автоматом устраивает), либо произвести кадрирование превью, для большей наглядности превью.
- если полный вид и превью устраивает - нопка "сохранить" отсылает полный вид и превью в модальное окно первой вкладки и (если выбрано несколько файов) в рамке появляется следующая картинка.
- после кадрирования последней картинки, окно автоматом закрывается, в модальном окне отображены превью всех обработанных каринок.



