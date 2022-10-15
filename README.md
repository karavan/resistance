# Антикризисный риск-менеджмент

[![Contributors Welcome](https://img.shields.io/badge/contributing-welcome-blue.svg)](CONTRIBUTING.md)
[![GitHub license](https://img.shields.io/badge/license-CC0-blue.svg)](LICENSE)

***Снижаем персональные риски в условиях кризиса***.

---

В проекте:

:heavy_plus_sign: Рассматривается использование *исключительно экономических или юридических* методов для минимизации *персональных рисков*.

:heavy_minus_sign: *Не* рассматривается использование никаких *политических* методов: они важны для общества, но увеличивают риски для индивидуума.

:heavy_check_mark: Берегите себя. Не нарушайте законы юрисдикции(й), в которой(ых) живете.

---

> :information_source: Содержимое проекта носит исключительно образовательный характер и не является рекомендацией к каким-либо действиям. Учитывайте, что к моменту прочтения часть информации может устареть.

## :newspaper: **Последние обновления**

Октябрь 2020:

- :heavy_exclamation_mark: Начата работа над [списком мер для снижения риска быть незаконно мобилизованным](#мобилизация)
- :heavy_exclamation_mark: Начата работа над [Иммиграция: экстренная и плановая](#иммиграция)

Июнь 2022:

- Обновлены [требования к брокерам](lists.md#требования-к-брокерам)
- Обновлена информация [по блокировкам со стороны Coinbase](lists.md#криптобиржи)
- Обновлена информация [VPN сервисам](lists.md#vpn-cервисы).

Maй 2022:

- Отразил кейс с обвалом стейблкоина UST на ~~>70%~~ 100% в [сравнительной таблице стейблкоинов](lists.md#stablecoins)

Апрель 2022:

- Binance: [aктуализация органичений для резидентов РФ](sanctions-risks-in-cryptocurrency.md#pushpin-где-хранить-а-что-не-стоит).
- Расширенное сравнение для:
  - [стейблкоинов](lists.md#stablecoins)
  - [VPN сервисов](lists.md#vpn)
  - [кошельков](lists.md#некастодиальные-кошельки).
- Для формирования низкорискованного валютного портфеля:
  - добавил скрипт [анализа волатильности валют](src/fx_currencies_analysis.md)
  - добавил скрипт [моделирования цен валют с использованием метода Монте-Карло](src/fx_currency_portfolio__assets_selection.ipynb).

Март 2022:

- Обновление списка [стейблкоинов](lists.md#stablecoins)
- Рефакторинг списка [VPN сервисов](lists.md#vpn)
- Обновлена структура `README.md`
- Уточнен список бирж, вводивших ограничения против резидентов РФ
- Добавлена секция [Важные новости](sanctions-risks-in-cryptocurrency.md#важные-новости) в части санкций, касаюющих криптобирж.

---

## Мобилизация

![Status](https://img.shields.io/badge/status-in_progress-green.svg) ![Priority](https://img.shields.io/static/v1?label=priority&message=critical&color=red)

Список мер для снижения риска быть незаконно мобилизованным:

- [Кому попытаются вручить повестку?](mobilization-resistance.md#кому-попытаются-вручить-повестку)
- [Если ищут коллекторы...](mobilization-resistance.md#если-ищут-коллекторы)
- [Когда пытаются вручить повестку...](mobilization-resistance.md#когда-пытаются-вручить-повестку)
- [Когда вручили повестку...](mobilization-resistance.md#когда-вручили-повестку)
- [В военкомате...](mobilization-resistance.md#в-военкомате)
- [:telephone_receiver: Экстренные контакты](mobilization-resistance.md#telephone_receiver-экстренные-контакты)
- [:link: Полезные ссылки](mobilization-resistance.md#link-полезные-ссылки)

## Иммиграция

![Status](https://img.shields.io/badge/status-in_progress-green.svg)

Чек-лист по подготовке к экстренной и плановой релокации:

- [Документы](relocation.md#документы)
  - [Первоочередные документы](relocation.md#первоочередные-документы)
  - [Дополнительные документы](relocation.md#дополнительные-документы)
  - [Для получение рабочей визы/ВНЖ](relocation.md#для-получение-рабочей-визывнж)
- [Экстренная релокация](relocation.md#экстренная-релокация)
  - [Подготовка](relocation.md#подготовка)
  - [В аэропорту/на границе](relocation.md#в-аэропортуна-границе)
  - [В стране иммиграции](relocation.md#в-стране-иммиграции)
- [Плановая релокация](relocation.md#плановая-релокация)
  - [Подготовка](relocation.md#подготовка-1)
- [:link: Полезные ссылки](relocation.md#link-полезные-ссылки)

## Личные финаны условиях санкций

![Status](https://img.shields.io/badge/status-archive-lightgrey.svg)

Риск-менеджмент личных финансов условиях санкций и/или финансового кризиса:

- [Глупые стратегии и большие риски](introduction-to-risks.md#глупые-стратегии-и-большие-риски)
- [Сценарий I: «Черный день»](introduction-to-risks.md#сценарий-i-черный-день)
  - [Цель](introduction-to-risks.md#цель)
  - [План](introduction-to-risks.md#план)
  - [Сроки](introduction-to-risks.md#сроки)
- [Сценарий II: Блэкаут](introduction-to-risks.md#сценарий-ii-блэкаут)
  - [Цель](introduction-to-risks.md#цель-1)
  - [План](introduction-to-risks.md#план-1)
  - [Сроки](introduction-to-risks.md#сроки-1)
- [Сценарий III: Утрата сбережений](introduction-to-risks.md#сценарий-iii-утрата-сбережений)
  - [Цель](introduction-to-risks.md#цель-2)
  - [План](introduction-to-risks.md#план-2)
  - [Сроки](introduction-to-risks.md#сроки-2)
- [Итак...](introduction-to-risks.md#итак)
- [~~Общее~~ Важное](introduction-to-risks.md#общее-важное)
- [:link: Полезные ссылки](introduction-to-risks.md#link-полезные-ссылки)


## Инвестиции в криптовалюту в условии санкций

![Status](https://img.shields.io/badge/status-archive-lightgrey.svg) 

Риск-менеджмент инвестиций в криптовалюту в условии санкций:

- [:date: Важные новости](sanctions-risks-in-cryptocurrency.md#date-важные-новости)
- [TL;DR](sanctions-risks-in-cryptocurrency.md#tldr)
- [0. Правила игры (подготовка)](sanctions-risks-in-cryptocurrency.md#0-правила-игры-подготовка)
- [1. Что хранить?](sanctions-risks-in-cryptocurrency.md#1-что-хранить)
  - [Криптовалюта со свободным курсом](sanctions-risks-in-cryptocurrency.md#криптовалюта-со-свободным-курсом)
  - [Стейблкоин](sanctions-risks-in-cryptocurrency.md#стейблкоин)
  - [:pushpin: Что хранить... а что не стоит](sanctions-risks-in-cryptocurrency.md#pushpin-что-хранить-а-что-не-стоит)
- [2. Где хранить?](sanctions-risks-in-cryptocurrency.md#2-где-хранить)
  - [Биржи](sanctions-risks-in-cryptocurrency.md#биржи)
  - [Кошельки](sanctions-risks-in-cryptocurrency.md#кошельки)
  - [:pushpin: Где хранить... а где не стоит](sanctions-risks-in-cryptocurrency.md#pushpin-где-хранить-а-где-не-стоит)
- [Итак](sanctions-risks-in-cryptocurrency.md#итак)
- [:link: Полезные ссылки](sanctions-risks-in-cryptocurrency.md#link-полезные-ссылки)


## Важные списки

Наиболее полезные списки:

- [Законодательные акты](lists.md#законодательные-акты)
  - [Ограничения по операция с иностранной валюты](lists.md#ограничения-по-операция-с-иностранной-валюты)
  - [Список недружественных государств](lists.md#список-недружественных-государств)
  - [Полезные ссылки](lists.md#полезные-ссылки)
- [Список надежных российских банков.](lists.md#список-надежных-российских-банков)
  - [Требования к банкам](lists.md#требования-к-банкам)
  - [Банки под санкциями](lists.md#банки-под-санкциями)
  - [Список надежных банков](lists.md#список-надежных-банков)
  - [Полезные ссылки](lists.md#полезные-ссылки-1)
- [Список надежных российских брокеров](lists.md#список-надежных-российских-брокеров)
  - [Иностранные брокеры](lists.md#иностранные-брокеры)
  - [Российские брокеры](lists.md#российские-брокеры)
  - [Полезные ссылки](lists.md#полезные-ссылки-2)
- [Надежные почтовые сервисы](lists.md#надежные-почтовые-сервисы)
  - [Российские почтовые сервисы](lists.md#российские-почтовые-сервисы)
  - [Иностранные почтовые сервисы](lists.md#иностранные-почтовые-сервисы)
- [Криптовалюты](lists.md#криптовалюты)
  - [Stablecoins](lists.md#stablecoins)
  - [Некастодиальные кошельки](lists.md#некастодиальные-кошельки)
  - [Криптобиржи](lists.md#криптобиржи)
  - [Сервисы поиска обменников](lists.md#сервисы-поиска-обменников)
- [VPN](lists.md#vpn)
  - [VPN cервисы](lists.md#vpn-cервисы)
  - [Другие инструменты обхода блокировок](lists.md#другие-инструменты-обхода-блокировок)
  - [Полезные ссылки](lists.md#полезные-ссылки-3)
- [Список софта](lists.md#список-софта)
