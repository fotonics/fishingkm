---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_foto.jpg
widget1:
  title: "Болонская ловля"
  url: 'https://youtu.be/PUKzrA7Rmog'
  image: 'https://i.ytimg.com/vi/PUKzrA7Rmog/maxresdefault.jpg'
  text: 'Болонские поплавки. <br/>Болонская ловля на течении. Обзор<br/>
  Всем привет! Решил записать на тему болонская ловля видео и сделать обзор про болонские поплавки, какие есть в моем арсенале...'
  video: '<a href="#" data-reveal-id="videoModal1"><img src="https://i.ytimg.com/vi/PUKzrA7Rmog/maxresdefault.jpg" width="302" height="182" alt="Болонская ловля"/></a>'
widget2:
  title: "Штекерная ловля"
  url: 'https://youtu.be/yZFnqmQq6dY'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://i.ytimg.com/vi/yZFnqmQq6dY/maxresdefault.jpg" width="302" height="182" alt="Ловля на штекер"/></a>'
  image: 'https://i.ytimg.com/vi/yZFnqmQq6dY/maxresdefault.jpg'
  text: 'Ловля на штекер. <br/>Увлекательная рыбалка 2019<br/> Всем привет! В этот раз штекерная ловля, расскажу и покажу мои оснастки. ловля на штекер увлекательная рыбалка...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://i.ytimg.com/vi/yZFnqmQq6dY/maxresdefault.jpg" width="302" height="182" alt="Ловля на штекер"/></a>'
widget3:
  title: "Ловля фидером"
  url: 'https://youtu.be/syt79wTv70Q'
  image: 'https://i.ytimg.com/vi/syt79wTv70Q/maxresdefault.jpg'
  text: 'Всем привет! Когда в моей жизни была активна ловля на фидер где-то 2009-2013 гг. Были рыбалки, когда шел крупный лещ на фидер, также  фидер на реке, иногда снимал фидерная ловля видео. Приятного просмотра на канале anglergold.tv '
  video: '<a href="#" data-reveal-id="videoModa2"><img src="https://i.ytimg.com/vi/syt79wTv70Q/maxresdefault.jpg" width="302" height="182" alt="Ловля на штекер"/></a>'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/fotonics
  text: Подпишитесь на нашу рассылку ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
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