HTML5

<header>, <main>, <section>, <footer> - семантичні теги для правильної структури документа
<nav> - навігаційне меню
<video> з атрибутами autoplay, muted, loop, playsinline - фонове відео
alt - атрибут для зображень
id та href - навігація для сторінки

Google Fonts
<link href="https://fonts.googleapis.com/css2?family=Momo+Trust+Display&display=swap"> - кастомний шрифт

CSS3

* {...} - скидання стандартних стилів браузера
:root {...} - змінні для кольорів та відступів

Flexbox
display: flex - розташування елементів
justify-content, align-items, gap - вирівнювання елементів
flex-direction: column - вертикальний напрямок

CSS Grid
display: grid - сітка
grid-template-columns: 1fr 2fr - двовимірна сітка для розташування секцій (1:2)
grid-template-columns: 1fr 1fr 1fr - тристовпцева сітка 
grid-template-columns: 1fr 1fr - двостовпцева сітка
grid-template-columns: 1fr - одностовпцева сітка

Positioning
position: fixed - фіксація певних елементів
position: relative - позиція батьківських контейнерів
position: absolute - позиція декоративних елементів
z-index - контроль шарів

Pseudo-elements
.about_info::after { ... } - декоративний елемент на фоні

Pseudo-classes
:hover - ефекти при наведенні
:active - ефект натискання
:focus - стилі для активних полів форми
:checked - ефекти при відкритому або закритому checkbox
::placeholder - стилі для placeholder

Transitions & Transforms
transition - плавні анімації
transform - трансформації

Box Shadow
box-shadow - тіні для елементів

Backdrop Filter
backdrop-filter - розмиття фону


Linear Gradient
linear-gradient (...) - градієнтовий фон для елементів

Smooth Scrolling
scroll-behavior: smooth - плавний прокрут сторінки 
scroll-margin-top: - прокрут на вказану дистанцію по верху

Float
float - обтікання елементів

Responsive Design (Media Queries)
@media screen and (min-width: 768px) and (max-width: 1023px) - стилізація для планшетів
@media screen and (max-width: 767px) - стилізація для мобільних пристроїв
@media screen and (max-width: 480px) - стилізація для маленьких телефонів

Burger Menu (Checkbox Hack)
.burger-toggle:checked ~ .nav, .burger-toggle:checked + .burger-menu span:nth-child(1) - мобільне меню через checkbox

Aspect Ratio
aspect-ratio: 3/4 - зберігає розміри зображення

JavaScript

onclick="window.open('URL')" - відкриття посилання у новій сторінці

