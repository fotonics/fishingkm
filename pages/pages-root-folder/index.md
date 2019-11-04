---
#
# Используйте виджеты ниже, и содержание будет
# автоматически вставляется в веб-страницу
# вы должны использовать › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_foto.jpg
widget1:
  title: "Болонская ловля"
  url: 'https://youtu.be/PUKzrA7Rmog'
  image: 'https://i.ytimg.com/vi/PUKzrA7Rmog/maxresdefault.jpg'
  text: ''
  video: '<a href="#" data-reveal-id="videoModal1"><img src="https://i.ytimg.com/vi/PUKzrA7Rmog/maxresdefault.jpg" width="302" height="182" alt="Болонская ловля"/></a>'
widget2:
  title: "Штекерная ловля"
  url: 'https://youtu.be/yZFnqmQq6dY'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://i.ytimg.com/vi/yZFnqmQq6dY/maxresdefault.jpg" width="302" height="182" alt="Ловля на штекер"/></a>'
  image: 'https://i.ytimg.com/vi/yZFnqmQq6dY/maxresdefault.jpg'
  text: ''
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://i.ytimg.com/vi/yZFnqmQq6dY/maxresdefault.jpg" width="302" height="182" alt="Ловля на штекер"/></a>'
widget3:
  title: "Ловля фидером"
  url: 'https://youtu.be/syt79wTv70Q'
  image: 'https://i.ytimg.com/vi/syt79wTv70Q/maxresdefault.jpg'
  text: '.'
  video: '<a href="#" data-reveal-id="videoModa2"><img src="https://i.ytimg.com/vi/syt79wTv70Q/maxresdefault.jpg" width="302" height="182" alt="Ловля на штекер"/></a>'
#
# Используйте призыв к действию, чтобы показать кнопку на главной странице
#
# Чтобы сделать внутренние ссылки, просто используйте постоянную ссылку, как это
url: /getting-started/
#
# Чтобы придать кнопке другой цвет, не используйте значение
# чтобы использовать основной цвет или успех, предупреждение или вторичный.
# Чтобы изменить цвета см. sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/fotonics
  text: Подпишитесь на нашу рассылку ›
  style: alert
permalink: /index.html
#
# Это хак, чтобы сделать навигационную подсветку
# эта страница активна в верхней панели навигации
#
homepage: true
---

<div id="videoModal1" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/PUKzrA7Rmog" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/yZFnqmQq6dY" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
<div id="videoModa2" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/syt79wTv70Q" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>