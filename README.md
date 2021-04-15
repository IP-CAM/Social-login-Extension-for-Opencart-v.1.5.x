# Authorization through social networks for OpenCart 1.5

The module is a strongly modified version of the version of the "OpenCart Social Authorization by Nikita_Sp" module ``.
As the author fell into his creation, I developed on its basis the improved version for one of our customers.

## Installation

Installing the standard module for OpenCart 1.5 - simply copy the contents of `upload` in the root of your site. If you have not been installed the original module - copying must pass without any warnings or replacements.

**IMPORTANT**

To work with Twitter API, I used the twitter-async library. It is fixed as submodule in the repository (`System / Libraries / Twitter-Async`) if you download the repository as a zip archive, then you will probably also be needed to download this library separately.

## Transition from OpenCart Social Authorization by nikita_sp

Because The module uses the same routes and persistent variables for settings, the update via the replacement should not spoil your settings.

** However, I do not guarantee anything - follow the golden rule of the IT and make a backup! **

## Difference

1. Fixed work with Facebook
2. Added authorization through classmates
3. Added authorization via Twitter
4. Refactoring and simplify code
5. ** This version requires the installed PHP-CURL **

## TODO.

1. Add authorization via Instagram
2. Add it ability to add links to a page via the module
3. Conduct the code refactoring and add correct processing of API errors

## Why CURL?

This requirement is associated with classmates API, which requires send requests to them.
In the future, you can make this requirement optional if necessary.

## How to help

If you have found a bug or know how to make the module is better - you can create ** Issues **, and even better send me ** Pull Request **

------

# Авторизация через соцсети для Opencart 1.5

Модуль представляет из себя сильно доработанную версию модуля `"Opencart social authorization by Nikita_SP"`. 
Поскольку автор подзабил на своё творение, я разработал на его основе улучшенную версию для одного из наших клиентов.

## Установка

Установка модуля стандартна для Opencart 1.5 - просто копируйте содержимое `upload` в корень вашего сайта. Если у вас не был установлен оригинальный модуль - копирование должно пройти без каких-либо предупреждений или замен.

**ВАЖНО**

Для работы с Twitter API я использовал библиотеку twitter-async. Она закреплена как субмодуль в репозитории (`system/libraries/twitter-async`), если вы скачиваете репозиторий как zip архив, то, вероятно, вам также понадобится отдельно скачать эту библиотеку.

## Переход с Opencart social authorization by Nikita_SP

Т.к. модуль использует те же роуты и персистентные переменные для настроек, обновление через замену не должно испортить ваши настройки.

**Однако, я ничего не гарантирую - следуйте золотому правилу айтишников и делайте бэкап!**

## Отличия

1. Исправлена работа с Facebook
2. Добавлена авторизация через Одноклассники
3. Добавлена авторизация через Twitter
4. Произведён рефакторинг и упрощение кода
5. **Эта версия требует установленного php-curl**

## TODO

1. Добавить авторизацию через Instagram
2. Добавить возможность добавления ссылок на странице через модуль
3. Провести рефакторинг кода и добавить корректную обработку ошибок API

## Зачем CURL?

Это требование связано с API Одноклассников, которое требует отправлять им POST запросы.
В будущем можно сделать это требование опциональным, если нужно.

## Как помочь

Если нашли баг или знаете как сделать модуль лучше - можете создать **issues**, а ещё лучше отправьте мне **pull request**
