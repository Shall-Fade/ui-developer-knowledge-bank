# Банк знаний верстальщика

Описание банка знаний...

## Разделы
1. HTML/CSS
2. jQuery
3. Примеры кода
4. Полезные ссылки

### HTML/CSS
- [Слова, часто используемые в CSS-классах](https://github.com/yoksel/common-words)
- [Подключение шрифтов](http://site4business.net/css/kak-podklyuchit-shrift.html)
- [Оптимизация изображений](https://squoosh.app/)
- [Шпаргалка по форматам изображений для веба](https://htmlacademy.ru/blog/html/image-formats)
- [Шпаргалка по CSS](https://adam-marsden.co.uk/css-cheat-sheet)

### jQuery
Это бесплатная JavaScript-библиотека с открытым исходным кодом. Она заметно упрощает веб-разработку, позволяя писать меньше кода, чем на ванильном JavaScript.

- [Документация jQuery](https://jquery-docs.ru/)
- [Шпаргалка jQuery](https://only-to-top.ru/blog/coding/2019-01-10-shpargalka-po-ispolzovaniyu-jquery.html)

### Примеры кода
Полный HTML-макет Swiper.js
```
<!-- Slider main container -->
<div class="swiper">
  <!-- Additional required wrapper -->
  <ul class="swiper-wrapper">
    <!-- Slides -->
    <li class="swiper-slide">Slide 1</li>
    <li class="swiper-slide">Slide 2</li>
    <li class="swiper-slide">Slide 3</li>
  </ul>
  <!-- If we need pagination -->
  <div class="swiper-pagination"></div>

  <!-- If we need navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>

  <!-- If we need scrollbar -->
  <div class="swiper-scrollbar"></div>
</div>
```

Сворачивание блока (пример: модалка, ме)
```
// Нажатие по области вне блока
$(document).mouseup(function (e) {
    let container = $(".container-example");
    if (container.has(e.target).length === 0) {
        $(".container-example").slideUp(300);
    }
});

// Нажатие на кнопку "esc"
$(document).keyup(function(e) {
    if (e.keyCode === 27) { 
        $('.container-example').slideUp(300);
    }
});
```

### Полезные ссылки
- [Swiper js](https://swiperjs.com/get-started)
- [jQuery CDN](https://releases.jquery.com/)
- [jQuery Masked Input](https://plugins.jquery.com/maskedinput/)
- [jQuery More Content](https://wahawaher.github.io/morecontent-js/)
- [Список шрифтов и начертаний используемых в макете Figma](https://www.figma.com/community/plugin/746097413727734148/Font-Fascia)
- [Шпаргалка функций плавности](https://easings.net/ru)
