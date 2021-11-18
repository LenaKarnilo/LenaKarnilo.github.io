# LenaKarnilo.github.io

**Классы для стилизации контента**

Пример:

```
<div class="box">
    <p class="text-center">Example text</p>
    <!-- Так же одному элементу можно задать несколько классов, через пробел -->
    <p class="font-size-24 font-weight-bold mb-24">Second text</p>
</div>
```

**font-weight-light** - начертание шрифта 300 <br>
**font-weight-normal** - начертание шрифта 400 <br>
**font-weight-medium** - начертание шрифта 500 <br>
**font-weight-bold** - начертание шрифта 700 <br>

**font-size-14** - размер шрифта 14px <br>
**font-size-16** - размер шрифта 16px <br>
**font-size-24** - размер шрифта 24px <br>
**font-size-35** - размер шрифта 35px <br>

**text-left** - выравниваение текста по левой стороне <br>
**text-right** - выравниваение текста по правой стороне <br>
**text-center** - выравниваение текста по центру <br>

**text-underline** - сделать текст подчёркнутым <br>
**title-color** - цвет шрифта #212121 <br>
**text-color** - цвет шрифта #424242 <br>

**no-list-style** - убрать у тегов ul, ol паддинг слева и маркер у элемента li <br>

**link-with-arrow** - ссылка со стрелкой <br>

**mb-0** - убрать отступ снизу <br>
**mb-8** - отступ снизу 8px <br>
**mb-16** - отступ снизу 16px <br>
**mb-24** - отступ снизу 24px <br>
**mb-32** - отступ снизу 32px <br>
**mb-40** - отступ снизу 40px <br>

**hide-for-mobile** - при разрешении экрана < 768px элемент будет скрыт <br>
**hide-for-desktop** - при разрешении экрана >= 768px элемент будет скрыт <br>

**box** - контейнер с макс. шириной 640px и расположением по центру <br>

**contact-list** - неупорядоченный спиок (ul) с маркерами как в макете <br>

```
<ul class="contact-list">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

**image-wrapper** - обертка для изображения с серым фоном и падингами <br>

```
<div class="image-wrapper">
    <img src="/images/example-image.{png, jpg}" srcset="/images/example-image_2x.png 2x" width="1301" height="566" loading="lazy" alt="Описание изображения" />
</div>
```
