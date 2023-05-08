
# Making_README
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


