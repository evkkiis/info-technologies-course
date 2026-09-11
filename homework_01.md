# Домашняя работа №1. Журнал событий на сайтах

## Задание №1. Карта событий на сайте Л'Этуаль

### 1. Зашла на товар

---
- **Event:** `view_item_list`
- **Site:** LETUAL (cosmetics & perfumes)
- **URL:** https://www.letu.ru/browse/makiyazh
- **tid:** G-72YB0DGLLG
- **cid:** 549822742.1789141891
- **sid:** 1789141891
- **dl:** https%3A%2F%2Fwww.letu.ru%2Fbrowse%2Fmakiyazh
---

### 2. Добавила товар в избранные

---
- **Event:** `view_item_list`
- **Site:** LETUAL (cosmetics & perfumes)
- **URL:** https://www.letu.ru/browse/makiyazh
- **tid:** G-72YB0DGLLG
- **cid:** 549822742.1789141891
- **sid:** 1789144964
- **dl:** https%3A%2F%2Fwww.letu.ru%2Fproduct%2Fmissha-tonalnyi-bb-krem-m-perfect-cover-idealnoe-pokrytie-spf42-pa-%2F132400614
---

### 3. Добавила товар в корзину

---
- **Event:** `add_to_cart`
- **Site:** LETUAL (cosmetics & perfumes)
- **URL:** https://www.letu.ru/browse/makiyazh
- **tid:** G-72YB0DGLLG
- **cid:** 549822742.1789141891
- **sid:** 1789144964
- **dl:** https://www.letu.ru/product/missha-tonalnyi-bb-krem-m-perfect-cover-idealnoe-pokrytie-spf42-pa-/132400614
---

### 4. Зашла на короткое видео

---
- **Event:** `video_start`
- **Site:** LETUAL (cosmetics & perfumes)
- **URL:** https://www.letu.ru/browse/makiyazh
- **tid:** G-72YB0DGLLG
- **cid:** 549822742.1789141891
- **sid:** 1789144964
- **dl:** https%3A%2F%2Fwww.letu.ru%2F%3Futm_source%3Dyandex%26utm_medium%3Dcpc%26utm_campaign%3Dle_yd_spb_s_search_brand%26utm_term%3D---autotargeting%26srcid%3Dle_yd_spb_s_search_brand%26utm_content%3Dastat%3A53487801839%7Cret%3A53487801839%7Ckor%3A0%7Cdsa%3A53487801839%7Ccid%3A115308452%7Cgid%3A5506509530%7Caid%3A1914276300816843479%7Cpt%3Apremium%7Cpos%3A1%7Cst%3Asearch%7Csrc%3Anone%7Cdvc%3Adesktop%7Creg%3A2%7Cadp%3Ano%7Capt%3Anone%7Clink%3Amain%7Cseptember_presents%26etext%3D2202.w1mEWj5aIceliuRm-qU7SJ5mRYrAMcpqMeROWvl7ggFxbnZnbHFxbXJwd29pb3Rv.ad7db10a8a95d52382457f0176e2175ac3d152ee%26yclid%3D14629128457928835071%26utm_referrer%3Dhttps%3A%2F%2Fyandex.ru%2F
---

### 5. Зашла на вкладку "Детский уход и парфюмерия"

---
- **Event:** `page_view`
- **Site:** LETUAL (cosmetics & perfumes)
- **URL:** https://www.letu.ru/browse/makiyazh
- **tid:** G-72YB0DGLLG
- **cid:** 549822742.1789141891
- **sid:** 1789144964
- **dl:** https%3A%2F%2Fwww.letu.ru%2F%3Futm_source%3Dyandex%26utm_medium%3Dcpc%26utm_campaign%3Dle_yd_spb_s_search_brand%26utm_term%3D---autotargeting%26srcid%3Dle_yd_spb_s_search_brand%26utm_content%3Dastat%3A53487801839%7Cret%3A53487801839%7Ckor%3A0%7Cdsa%3A53487801839%7Ccid%3A115308452%7Cgid%3A5506509530%7Caid%3A1914276300816843479%7Cpt%3Apremium%7Cpos%3A1%7Cst%3Asearch%7Csrc%3Anone%7Cdvc%3Adesktop%7Creg%3A2%7Cadp%3Ano%7Capt%3Anone%7Clink%3Amain%7Cseptember_presents%26etext%3D2202.w1mEWj5aIceliuRm-qU7SJ5mRYrAMcpqMeROWvl7ggFxbnZnbHFxbXJwd29pb3Rv.ad7db10a8a95d52382457f0176e2175ac3d152ee%26yclid%3D14629128457928835071%26utm_referrer%3Dhttps%3A%2F%2Fyandex.ru%2F
---

## Задание №2. Сравнение двух сайтов

---
| Я сравнивала сайт "Вкусно и точка" с сайтом "Л'Этуаль". На letu.ru событий больше, чем на vkusnoitochka.ru, потому что это интернет‑магазин.А у «Вкусно и точка» сайт в основном информационный, тоесть там меню, акции и основные заказы идут в приложении и в ресторанах, поэтому событий меньше. Источник трафика на vkusnoitochka.ru чаще определён (органический поиск, прямые заходы). А на letu.ru часто бывает (not set), например, из‑за переходов из Telegram и приложений, где UTM‑метки теряются.
Разница в том, что у «Вкусно и точка» главный канал — офлайн и приложение, а «Летуаль» делает ставку на онлайн‑продажи, но трекинг настроен не идеально. |
---

## №3. Точка разрыва

---
Шаг 5: «Зашла на вкладку „Детский уход и парфюмерия“»
Как проверить на занятии 2:
1. Открыть letu.ru → F12 → вкладка Network → фильтр collect.
2. Перейти на вкладку «Детский уход и парфюмерия» (кликнуть по пункту меню).
3. Найти новый запрос к g/collect → открыть его → вкладка Payload.
4. Посмотреть параметр dl (document location) — сравнить его с тем, что в адресной строке браузера.
5. Если dl содержит utm_source, utm_medium, yclid и т. д., а не простой URL раздела — это и есть точка разрыва.
6. Проверить параметр dt (document title): если там тоже «мусор» из меток вместо нормального названия страницы — проблема подтверждается.
---