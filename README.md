# AJS-8.2
# Домашнее задание к лекции «Контейнеры»

**Важно**: каждая задача выполняется в виде отдельного проекта с собственным GitHub репозиторием.

**Важно**: код должен проходить ESLint без ошибок.

**Важно**: тесты должны обеспечивать 100% покрытие тестируемых функций по строкам.

**Важно**: решения должны быть построены на базе [шаблона Webpack](/ci-template).

В личном кабинете на сайте [netology.ru](http://netology.ru/) в поле комментария к домашней работе вставьте ссылки на ваш GitHub-проекты.

---


## Map

### Легенда

Вы решили упорядочить работу с ошибками в своём приложении, а именно ввести цетрализованно числовой код ошибки и её описание. И при генерации любых ошибок в коде приложения брать их из централизованного хранилища.

### Описание

Создайте свой класс `ErrorRepository` внутри которого храните `Map`, в котором ключ - это код ошибки (число), а значение - текстовое описание (человекочитаемое).

Реализуйте метод `translate(code)`, позволяющий по коду получить текст ошибки, а в случае отсутствия подобного кода возвращать строку `'Unknown error'`.

Не забудьте написать unit-тесты, которые обеспечивают 100% покрытие функций и классов, которые вы тестируете.

----

### Map

[![Build status](https://ci.appveyor.com/api/projects/status/9mcd8m4ax8w3wcwp/branch/main?svg=true)](https://ci.appveyor.com/project/222Alexa44925/ajs-8-2-q4tmg/branch/main)

---