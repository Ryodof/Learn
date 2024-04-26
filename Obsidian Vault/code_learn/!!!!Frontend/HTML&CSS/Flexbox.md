 Свойства родительского контейнера (flex-контейнера):

- display: flex; - устанавливает элемент-контейнер как блочный flex-контейнер.

- display: inline-flex; - устанавливает элемент-контейнер как строчный flex-контейнер.

- flex-direction: row | row-reverse | column | column-reverse; - определяет направление основной оси.

- flex-wrap: nowrap | wrap | wrap-reverse; - определяет, должны ли элементы переноситься на новую строку.

- justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right; - выравнивание элементов по главной оси.

- align-items: stretch | flex-start | flex-end | center | baseline; - выравнивание элементов по поперечной оси.

- align-content: stretch | flex-start | flex-end | center | space-between | space-around; - управляет пространством между рядами элементов.

Свойства дочерних элементов (flex-элементов):

- order: <число>; - определяет порядок элемента в контейнере.

- flex-grow: <число>; - определяет способность элемента увеличиваться по ширине.

- flex-shrink: <число>; - определяет способность элемента уменьшаться по ширине.

- flex-basis: <длина> | auto; - задает начальный размер элемента до учета flex-grow и flex-shrink.

- flex: <flex-grow> <flex-shrink> <flex-basis>; - сокращенное свойство для установки flex-grow, flex-shrink и flex-basis в одной строке.

- align-self: auto | flex-start | flex-end | center | baseline | stretch; - переопределяет выравнивание элемента вдоль поперечной оси, заданное в align-items.

Эти свойства помогают управлять распределением пространства внутри flex-контейнера и настраивать поведение его дочерних элементов. 