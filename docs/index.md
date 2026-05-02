# Главная страница

[Об авторе](about_me.md)

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

Настройки и материалы для mkdocs [mkdocs-material](https://squidfunk.github.io/mkdocs-material/reference/lists/).

## Commands

cd /Users/macbookpro/code/auto 

source .venv/bin/activate

mkdocs serve --dev-addr 127.0.0.1:8000 --livereload

git add .
git commit -m "update" 
git push
mkdocs gh-deploy



* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs serve --dev-addr 127.0.0.1:8000 --livereload` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Свернуть строки
    <!-- #region название блока -->
        длинный текст
        много строк
    <!-- #endregion -->

## Маленький текст

<small>Журнал «Проблемы экспертизы в автомобильно-дорожной отрасли»</small>


## Блоки

???+ info
    тест


???+ warning
    тест


???+ danger
    тест


???+ quote
    тест

???+ example
    тест

## Фото

![logo](assets/logo.ico)

*подпись фото*

## Блок

!!! info inline "пример"

    тест


    тест

<br>
<br>
<br>
<br>

## Картинка сбоку текста

!!! info inline ""

    ![Image title](assets/logo.ico){ align=left }

<br>
<br>
<br>

## Пропуск строки
<br> 