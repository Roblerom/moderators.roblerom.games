<link rel="stylesheet" href="https://cdn.roblerom.games/css/moderators_cases.css">
<link rel="icon" href="/favicon.ico" type="image/x-icon"/>

# **Справочник по варнам (предупреждениям)**

## **Описание**

> <span class="text">Выдача предупреждения пользователю</span>

## **Шаблон использования**

`[...]` - обязательный аргумент\
`(...)` - необязательный аргумент

> `l.warn [@пользователь] (время) (причина)`

## **Примеры**

> - `l.warn @User#1234 выдача себя за администрацию` <span class="text">- выдаст варн с причиной</span> `выдача себя за администрацию`
> - `l.warn @User@1234 1d2h3m4s бебра` <span class="text">- выдаст варн с причиной</span> `бебра` <span class="text">на</span> `1 день 2 часа 3 минуты 4 секунды`
