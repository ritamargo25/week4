# week_4

Макет Figma (неделя 3,задание 3 + неделя 4, задание 1)

https://www.figma.com/file/gqfPRHbtpGoG9efBMn7ZvE/mycite?node-id=0%3A1


<img width="919" alt="Снимок экрана 2022-08-31 в 23 12 56" src="https://user-images.githubusercontent.com/110172816/187779524-17b010ec-9b22-4b12-b242-39ce2e4f0a2a.png">

Ответы на вопросы. Неделя 4

1. Какими способами можно подключать CSS-стили? Найдите сами еще один способ, не указанный в уроке
с помощью атрибута style (для быстрого тестирования)
с помощью тега <style> (свойства css находятся в самом документе, описываются в заголовке веб-страницы)
с помощью тега <link> (подключаются стили, которые располагаются в отдельном файле - самый оптимальный способ)
с помощью команды @import (импортируется содержание css файла

2. Зачем нужен Normalize.css?
Он обеспечивает поддержку разных браузеров, чтобы сайт в разных браузерах выглядел более менее одинаково, помогает сохранять полезные настройки браузера, нормализовать стили, устанавливает единый размер шрифта, корректирует ошибки браузера.

3. Что такое CSS-директивы?
Это операторы CSS, команды, которые начинаются со знака @ и показывают CSS как себя вести.

4. В чем разница между **margin** и **padding**?
С помощью **margin** мы создаем внешний отступ от элемента, а с помощью **padding** создаем внутренние отступы, то есть содержимое элемента будет удаленно от его внутренних границ на указанные значения.

5. Как в CSS определяются приоритеты?
Когда в разных CSS-правилах есть одинаковые свойства с разными значениями, то они конфликтуют. Поэтому необходимо расставить приоритеты, чтобы определить какое из свойств важнее.
специфичность селектора разбивается на 4 группы: a,b,c,d.
полученное значение приводится к числу
селектор, обладающий большим значением специфичности, обладает и большим приоритетом
Какое из свойств будет приоритетнее - `#link .main` или `span #login`?
с этим мне сложно разобраться, пытаюсь понять по простым источникам))

6. В чем разница между CSS1 и CSS3?
CSS1 является базовой версией и не поддерживает адаптивный дизайн. CSS3 является последней версией и поддерживает адаптивный дизайн
CSS1 нельзя разбить на модули, а CSS3 можно.
CSS1 не совместим с CSS3, в то время как CSS3 совместим с CSS1
В CSS1 используются только безопасные для сети шрифты, которые каждый компьютер устанавливает и распознает, а в CSS3 используются специальные шрифты, которые можно загрузить на сервер и запустить с помощью кода CSS

7. Что такое псевдоклассы? А псевдоэлементы?
Псевдоклассы - это селекторы, которые определяют состояние уже существующих элементов, которое может меняться при определенных условиях.
Псевдоэлементы – это селекторы, которые определяют область элементов, которая изначально отсутствует в дереве документа. Эта область создается искусственно с помощью CSS.
Псевдоклассы определяют именно состояние элементов, которые уже существуют на странице, а псевдоэлементы создают области (искусственные элементы), которых изначально на веб-странице не было

8. Изучите статью про “плохие” теги [https://msiter.ru/tutorials/html-srednego-urovnya/plokhie-tegi](https://msiter.ru/tutorials/html-srednego-urovnya/plokhie-tegi) и пришлите список тегов, которые нежелательно использовать
<u>
<center>
<layer>
<blink>
<marquee>
<font>

9. Как можно подключать шрифты локально?
с помощью правила @font-face
Оно позволяет определить настройки шрифтов, а также загрузить специфичный шрифт на компьютер
При использовании этого способа файлы с шрифтами хранятся вместе с остальными файлами сайта.
Шрифты скачиваются со специальных ресурсов. После того, как шрифты загружены на компьютер, их необходимо подключить в CSS, для этого используется правило @font-face.

10. Почему не стоит использовать сокращенную запись без необходимости? И если все же использовать, как это делать правильно?
Сокращенная запись уменьшает размер кода, что очень удобно, но некоторые свойства без дополнительных значений могут потерять свою актуальность. Поэтому если уж и использовать сокращенную запись, то группируя свойства по смыслу.

11. Разберитесь самостоятельно, как сделать анимацию через CSS
Анимация в CSS делается с помощью 2 свойств:
@keyframes
animation
Объявляем правило @keyframes
Оно позволяет создавать анимацию с помощью набора ключевых кадров.
Записывается так
@keyframes имя анимации { список правил }
Эти кадры определяют какие свойства на каком шаге будут анимированы
После объявления правила @keyframes, мы можем ссылаться на него в свойстве animation, которое прописываем в стилях самого элемента для анимации.



2. Закрепите навыки работы с селекторами в забавной игре https://flukeout.github.io/
<img width="1280" alt="Снимок экрана 2022-09-01 в 00 45 08" src="https://user-images.githubusercontent.com/110172816/187790984-98eae0da-4705-4057-a761-7fd894db6da5.png">
