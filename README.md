
# Making_README
![GitHub all releases](https://img.shields.io/github/downloads/babahasko/Making_README/total?logo=GitHub)![GitHub watchers](https://img.shields.io/github/watchers/babahasko/Making_README?logo=GitHub)

## Что это?
Этот документ содержит краткие фичи для создания хорошего README файла и предназначен для начинающих разработчиков.

Для проекта надо подготовить хорошее описание. При составлении описания можно придерживаться такого плана:

- название (желательно и его изображение тоже);
- описание (с использованием слов и изображений);
- демо (изображения, ссылки на видео, интерактивные демо-ссылки);
- технологии в проекте;
- что-то характерное для проекта (проблемы, с которыми пришлось столкнуться, уникальные составляющие проекта);
- техническое описание проекта (установка, настройка, как помочь проекту).

Используемый здесь проект будем считать за образец. У него один из красивейших файлов readme, который мне приходилось видеть. Код файла Readme.md можно найти здесь:silent-lad/VueSolitaire

## 1. Добавляем картинки
У вас может быть отличная фотографическая память, но интересующимся вашим проектом могут понадобиться фотографии его демо-версии.

Так, в описание нашего образцового проекта «Паук» в readme добавлены такие изображения:
<p align="center">
<img src="./readme_assets/p1.png" width="80%"></p>
Чтобы добавить изображение используйте следующий синтаксис:

- `![](https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png)`

Но часто возникает необходимость центрировать картинку или изменить её размер. Для этого в файла Markdown поддерживается язык html разметки.
Перепишем верхнюю ссылку на картинку в формате html разметки.
- `<p align="center">`
- `<img src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="80%">`
- `</p>`

Но я столкнулся с проблемой, что при использовании ссылки на картинку она не центрируется. Решил я эту проблему добавиви в проект папку
с используемыми картинками(в данном случае readme_assets) и синтаксис для добавления картинки стал выглядеть так.
- `<p align="center">`
- `<img src="./readme_assets/p1.png" width="80%">`
- `</p>`
Кроме изображений, вы можете добавить и видео-описание проекта. Вот только Github не разрешает добавлять видео в readme… Что же делать?

## Используем gif
<p align="center">
<img src="https://media.giphy.com/media/7OWdOQupgCClrZb19P/giphy.gif" width="80%"></p>

чтобы вствать gif в файл README используйте тот же синтаксис, что и для картинок.
- `<p align="center">`
- `<img src="https://media.giphy.com/media/7OWdOQupgCClrZb19P/giphy.gif" width="80%">`
- `</p>`
 
Однако чтобы ваш gif работал его необходимо опубликовать на каком либо сайте. в данном случае media.giphy.com

image url должен оканчиваться "gif"

 
## 2. Элементы оформления
Элементы оформления создадут у читающего readme ощущение уникальности вашего проекта. Нестандартные или активно используемые элементы оформления для репозитория можно раздобыть здесь: https://shields.io

Для этого переходите на сайт <a href="https://shields.io" rel="nofollow">shields.io</a>

<p align="center">
<img src="./readme_assets/Shields.io.png" width="80%"></p>

В строке поиска вводим название интересующего нас "шилда". В данном случае "download"

<p align="center">
<img src="./readme_assets/Downloads_Shields.png" width="80%"></p>

Из появившегося списка находим нужный нам и нажимаем на него ПКМ.

<p align="center">
<img src="./readme_assets/needed_shield.png" width="80%"></p>

В Появившемся окне вводим имя пользователя github и название репозитория. В этом же окне можем выбрать стиль оформления "шилда" и цвет.

<p align="center">
<img src="./readme_assets/Shield_editing.png" width="80%"></p>

Так же в данном окне можно добавить логотип(в данном случае GitHub) и также изменить его цвет. Цвте вводится в кодировке RGB например #000000 – черный

После того как вы определились с внешним видом вашего "шилда". Копируете ссылку на него в стиле MarkDown и вставляете в ваш README файл.

<p align="center">
<img src="./readme_assets/Load_shield.png" width="80%"></p>

# 3. Добавляем демо-версию
Если есть возможность, разместите проект на своих ресурсах и скопируйте ссылку на демо-версию и добавьте её в ваш README файл. 
Для добавления ссылок можно использовать следующий синтаксис:

- `<h2 align="center"><a  href="https://solitairevue.firebaseapp.com">Live Demo</a></h2>`

Как это будет выглядеть в вашем README файле на примере "паука".

<p align="center">
<img src="./readme_assets/demo.png" width="80%"></p>


