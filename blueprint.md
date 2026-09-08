---
project: manusan-site
created: 2026-09-08
subject: Виктор (сценическое имя MANOO SON / Manusan, домен manooson.com)
site_type: landing
sources_pulled: [assets/photos/, assets/video/, Instagram @manooson.live, чат с Марией, Проекты/ROMB-Drums-Site]
---

# Blueprint — Manusan

## A. Бренд-ДНК → см. Design.md [source: фото/видео + мнение Марии ("дорого-богато", "ОГОНЬ"), PROPOSAL не подтверждено]

## B. Голос/ToV → см. voice-profile.md [source: слова Марии + Instagram-подписи Виктора]

## C. Glossary
whitelist: Afro House Drums, Tribal Beats, Live Percussion (собственные термины бренда, не переводить)
ban-list: пусто

## D. Факты-канон
```
facts:
  - claim: "На сцене с 2014 года"
    value: "2014"
    source: подтверждено-экспертом
    status: confirmed
  - claim: "Выступал в Zion Sky Lounge & Dining, Вьетнам"
    value: "Zion Vietnam"
    source: внешний-пруф
    proof_link: "публичный пост Instagram @manooson.live, 28.07.2026"
    status: confirmed
  - claim: "Живые выступления в Бангалоре, Индия"
    value: "Bangalore"
    source: внешний-пруф
    proof_link: "публичный пост Instagram @manooson.live, 03.09.2026"
    status: confirmed
  - claim: "Жанр — Afro House Drums, Tribal Beats x Club Culture; также Melodic House, Organic House, Bollywood House Remixes"
    value: "Afro House Drums"
    source: подтверждено-экспертом
    proof_link: "официальный Press Kit MANOO_SON_PressKit.pdf"
    status: confirmed
  - claim: "Соло-проект, отдельно от дуэта RomBBeat"
    value: "solo"
    source: подтверждено-экспертом
    status: confirmed
  - claim: "Базируется в Гоа, Индия; регулярно выступает в Индии и России (Гоа, Пуне, Хайдарабад, Манали, Лакхнау, Москва, Санкт-Петербург)"
    value: "Goa, India + India/Russia tour circuit"
    source: подтверждено-экспертом
    proof_link: "официальный Press Kit"
    status: confirmed
  - claim: "Выступал на площадках: JW Marriott, W Hotel, OCCO, Raeeth, Purple Martini, Mayan, Tikitii, Dubki, Noah, Romeo Lane, Thalassa, Titlie, Tomatoes, Summer House, Bastian Riviera, Bastian Garden, Moai, Kaze, Zion"
    value: "venue list"
    source: подтверждено-экспертом
    proof_link: "официальный Press Kit"
    status: confirmed
  - claim: "Базовый сетап: дарбука, бубен, 2 джембе, 2 бонго, 2 тарелки, малая перкуссия; расширенный сетап и LED-барабаны — по запросу"
    value: "instrument setup"
    source: подтверждено-экспертом
    proof_link: "официальный Press Kit + Technical Rider"
    status: confirmed

promises_to_prove_later:
  - "Число выступлений/подписчиков — не публикуем (875 подписчиков Instagram — недостаточно для proof-бара)"
  - "Связь с Manoo из RomBBeat — визуально и по площадке (Zion) совпадает, но Мария явно не подтвердила тождество, факты не смешиваю"
```

## E. Оффер → см. offer-canon.md [цена: status pending]

## F. Аудитория и Big Idea
```
site_type: landing (booking EPK, по аналогии с ROMB-Drums-Site)
audience:
  segment: "организаторы luxury-мероприятий, владельцы клубов/ресторанов, event-агентства в Индии/Азии" [source: подтверждено Марией 2026-09-08]
  desires: ["живая энергия на площадке, зал должен чувствовать шоу"]
big_idea: "Сольное afro house percussion-шоу, которое меняет энергию танцпола/сета"
differentiation: "Персональный сценический бренд Виктора отдельно от дуэта RomBBeat, узнаваемый образ (шляпа/очки/золото) + живая работа с залом"
```

## G. Hero-состав
```
hero_blueprint:
  slots: [badge, h1, subhead, objection, cta, proof_bar]
  proof_facts: ["На сцене с 2014", "Zion Sky Lounge, Вьетнам", "Bangalore, India"]
scarcity: не применяется (evergreen booking-сайт, не запуск/лист ожидания)
infra:
  subject: "Manusan / MANOO SON"
  main_site: "manooson.com"
  deploy: "GitHub Pages (Sturza-Lab/manooson-site) — уже живой, не Vercel"
```

## H. references_intent
```
sitewide: ["ROMB-Drums-Site (тот же формат booking EPK, семейный сайт)"] — остальные ≥10 сам соберу в Фазе 2 (жанр: solo performer/DJ booking EPK)
```

## I. env
```
node: ok (v24.19.0)
playwright: ok (1.63.0)
```
