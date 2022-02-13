Советы по выполнению задания CV#3. CV. Cross-Check
https://github.com/rolling-scopes-school/tasks/blob/master/tasks/cv/cv-stage0-hints.md

Прижать footer к низу
https://www.youtube.com/watch?v=kNGYuTelE3E
https://sgeek.pro/web/coding/5-sposobov-kak-prizhat-footer-k-nizu-stranitsy/
https://ru.stackoverflow.com/questions/556896/
https://prowebmastering.ru/css-kak-prizhat-futer-k-nizu-stranicy.html
%D0%9A%D0%B0%D0%BA-%D0%BF%D1%80%D0%B8%D0%B6%D0%B0%D1%82%D1%8C-footer-%D0%BA-%D0%BD%D0%B8%D0%B7%D1%83-%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D1%8B
https://proweb63.ru/help/all-about-css/css-footer-pribit#:~:text=Footer%20%D0%BF%D1%80%D0%B8%D0%B6%D0%B8%D0%BC%D0%B0%D0%B5%D1%82%D1%81%D1%8F%20%D0%B2%D0%BD%D0%B8%D0%B7%20%D0%BF%D1%83%D1%82%D0%B5%D0%BC%20%D0%B5%D0%B3%D0%BE,%D0%B8%D0%BD%D0%B0%D1%87%D0%B5%20%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%D0%B4%D0%BD%D0%B8%D0%B9%20%D0%B7%D0%B0%D0%BA%D1%80%D0%BE%D0%B5%D1%82%20%D1%87%D0%B0%D1%81%D1%82%D1%8C%20%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D1%82%D0%B0.

Как прижать footer к низу страницы
Укажем, что минимальная высота body не может быть меньше высоты страницы: min-height: 100vh;
Обнаруживаем, что у страницы появилась вертикальная прокрутка. Указываем body свойства margin: 0; padding: 0;, вертикальная прокрутка исчезает.

body {
display: flex;
flex-direction: column;
justify-content: space-between;
min-height: 100vh;
margin: 0;
padding: 0;
}
