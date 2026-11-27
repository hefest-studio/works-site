[English](README.md) | **Русский**

<p align="center"><img src="docs/cover.png" alt="works-site" width="100%"></p>

[![Website](https://img.shields.io/website?url=https://works.hefest.ru&label=site&up_message=online&down_message=offline)](https://works.hefest.ru)
![Deploy](https://img.shields.io/badge/deploy-Vercel-000000?logo=vercel)
![Stack](https://img.shields.io/badge/HTML%20%C2%B7%20CSS%20%C2%B7%20JS-no%20build-E34F26?logo=html5&logoColor=white)
[![Hefest](https://img.shields.io/badge/made%20by-Hefest%20AI%20studio-EA6A12)](https://hefest.ru)

# works-site — витрина работ студии «Гефест»

Публичный одностраничник-портфолио на русском и английском: `works.hefest.ru` открывается по-русски, `works.hefest.online` — по-английски; переключатель RU / EN на странице и `?lang=ru|en` важнее домена, выбор запоминается. Что дальше — [роадмап](ROADMAP.ru.md).
Статика, деплой на Vercel (авто-HTTPS). Работа студии «Гефест».

## Содержимое
- `index.html` — витрина: карточки работ (Полиинструментальный цех, Зал ретро-игр, Кузня вкладок) + раздел «Примеры».
- `examples/` — курированные публичные примеры-деливераблы (из проекта reports; личное исключено).

## Деплой
Vercel → проект `works-site` → домены `works.hefest.ru` + `works.hefest.online`.
Карточки работ ведут на поддомены `workshop.hefest.ru` (music-book) и `arcade.hefest.ru` (retro-games); Кузня вкладок — на репозиторий/стор.

## Приватность / 152-ФЗ
Статическая витрина без сбора ПДн. Если добавится форма заявок — приём ПДн граждан РФ направлять на РФ-эндпоинт (не на Vercel). См. core/docs/BUSINESS/renewals.md, studio-works.md.
