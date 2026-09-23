# PROJECT_STATE — Cosmic

> Главный источник состояния проекта. Все утверждённые требования, решения, риски и переходы между этапами фиксируются здесь.
> Последнее обновление: 2026-09-21.

## 1. Управление проектом
- Продюсер и лицо, утверждающее продуктовые решения: пользователь.
- ChatGPT выполняет роли product manager / game producer / system analyst / technical lead / development lead.
- Работа ведётся по 16-этапному циклу из мастер-документа проекта.
- Этап нельзя считать завершённым без проверки критериев и подтверждения продюсера.
- Изменение утверждённого требования фиксируется как новое решение с указанием заменяемого решения.

## 2. Текущий статус
- Этап 1 «Идея и видение продукта»: УТВЕРЖДЁН 2026-09-21.
- Текущий этап: 2 «Исследование рынка и аудитории».
- Разработка gameplay ещё не начата.
- Следующий обязательный продуктовый checkpoint после создания первого полностью рабочего уровня: определить архитектуру карты после первых 20 уровней (прокрутка общей карты или новая карта/локация каждые 20 уровней).

## 3. Продукт
- Рабочее название: «Космические приключения».
- Название НЕ утверждено как коммерческое: требуется naming-sprint и проверка уникальности на русском, английском и турецком.
- Тип: браузерная HTML5-игра.
- Жанр: Match-3 / «3 в ряд».
- Тематика: космическое приключение.
- Тон: приключенческий sci-fi.
- Целевая аудитория: максимально широкая семейная аудитория всех возрастов.
- Целевой возрастной рейтинг: 0+ (финальная классификация должна быть проверена перед публикацией).
- Целевая платформа первой версии: Яндекс Игры.

### Продуктовая формула
Мы создаём доступную игрокам всех возрастов кинематографичную Match-3 игру о путешествии через космос, в которой привычная механика «3 в ряд» превращается в визуально насыщенное приключение с живыми 2.5D-фишками, зрелищными комбинациями, сюжетными главами и меняющимися космическими локациями.

### Главные отличия
1. Высокое визуальное качество при браузерном формате.
2. Космическая история и ощущение путешествия.
3. Живые 2.5D игровые элементы и выразительные реакции на действия игрока.

### Главная гипотеза
Высококачественная космическая визуальная подача + удовлетворяющая механика Match-3 + ощущение постоянного путешествия способны повысить интерес к прохождению следующих уровней по сравнению с визуально типовыми браузерными Match-3.

## 4. Core Loop
Запуск уровня → перестановка соседних фишек → совпадение → каскады/спецэффекты → выполнение целей → победа/поражение → награда → прогресс по космическому путешествию → следующий уровень.

## 5. Прогрессия и контент
- Сначала создаётся один полностью рабочий уровень (Vertical Slice).
- Затем создаётся игровая карта первой главы на 20 уровней.
- Игрок путешествует к планетам и космическим объектам, не обязательно высаживаясь на них.
- Предусматриваются сюжетные главы.
- Возможный герой/проводник — продуктовая гипотеза; не является обязательной механикой первого уровня.
- После Level 1 обязательно обсудить: непрерывная прокручиваемая карта или новая карта/локация каждые 20 уровней.

## 6. Gameplay — предварительно утверждено
Базовые типы фишек/объектов: ракета, космонавт, НЛО, планета, звезда, марсоход; также рассматриваются кристаллы, спутники и метеориты в зависимости от роли (фишка/цель/препятствие).

Предварительные специальные элементы:
- 4 в ряд → плазменная ракета;
- 5 в ряд → чёрная дыра;
- T/L → энергетический специальный элемент / сверхновая;
- комбинации специальных элементов должны давать усиленные реакции.

Предварительные цели уровней: сбор объектов, спасение космонавтов, разрушение метеоритов/препятствий, сбор кристаллов и другие тематические задачи. Точные правила утверждаются на этапах концепции/MVP.

## 7. Visual Direction
- Реалистичные/кинематографичные космические фоны.
- Игровые фишки: 2.5D, объёмные, яркие, читаемые, с качественными материалами и светом.
- Визуальная цель: «живо, объёмно, сочно, залипательно», без визуального шума.
- Игровая доска может восприниматься как голографическая/технологическая панель.
- Явные линии сетки не показывать.
- Микроанимации: мягкий idle, glint/блик, небольшая реакция на hover/touch.
- Падение: плавная динамика, squash/stretch и мягкий impact.
- Совпадения получают короткие тематические эффекты вместо простого исчезновения.
- Недостающие ассеты разрешено генерировать в согласованном стиле.

## 8. Responsive UI
- Одна игра и одна кодовая база для desktop и mobile.
- Основные целевые композиции: 16:9 desktop и 9:16 mobile.
- UI автоматически перестраивается, а не просто масштабируется.
- Максимальная длинная сторона внутреннего рендера: 1920 px.
- Конкретные breakpoints и правила safe-area будут определены на UX/техническом этапе.

## 9. Art / Asset Pipeline
Решение: использовать оптимизированные прозрачные элементы и texture atlases.
Предварительные группы:
- atlas_tiles — обычные фишки;
- atlas_specials — специальные элементы;
- atlas_obstacles — препятствия;
- atlas_ui — UI;
- atlas_fx — подходящие спрайтовые эффекты;
- backgrounds — отдельные оптимизированные изображения локаций.

Принцип: не загружать контент всех будущих глав на старте. Контент должен загружаться по необходимости/локациям. Форматы, размеры, compression budget и поддержка WebP/PNG будут подтверждены после проверки требований целевой платформы и тестов качества.

## 10. Технологические решения
- Игровой движок: Phaser 3.
- Язык/клиент: JavaScript, точная структура сборки утверждается на этапе архитектуры.
- Репозиторий: Sergius20232023/Cosmic.
- Внешняя платформа: Yandex Games SDK — точный набор интеграций проверяется по актуальной документации.
- Производительность, размер загрузки и стабильность равноправны финальному визуальному качеству.

## 11. Монетизация — направление
- Rewarded ads: дополнительные ходы / бустер / награда и другие добровольные награды.
- In-app purchases: игровая валюта/бустеры/пакеты — окончательная экономика позже.
- Реклама и покупки должны соответствовать актуальным требованиям Яндекс Игр.
- Монетизация не должна ломать обучение и первые игровые сессии.

## 12. MVP / Vertical Slice
Первый milestone: один законченный уровень, пригодный для реального тестирования.

Предварительный функциональный минимум:
- запуск;
- адаптивное игровое поле;
- swap соседних элементов;
- проверка допустимого хода;
- match 3/4/5;
- каскады;
- падение/refill;
- блокировка ввода во время разрешения поля;
- цели;
- счётчик ходов;
- победа/поражение;
- базовые спецэлементы;
- базовые VFX/SFX;
- сохранение;
- браузерная сборка;
- интеграционный слой Яндекс Игр с безопасным fallback для локальной разработки.

Точный scope фиксируется на Этапе 5.

## 13. Performance Principles
- Быстрый первый запуск.
- Не допускать лагов из-за декоративных эффектов.
- Атласы, lazy/on-demand loading и повторное использование ресурсов.
- Ограничение длинной стороны рендера 1920 px.
- Performance budgets (вес первой загрузки, память, FPS, draw calls и т. п.) установить на техническом этапе после измерений и требований платформы.
- Эффекты должны деградировать gracefully на слабых устройствах, если это потребуется.

## 14. Naming
Статус: OPEN.
Рабочие варианты «Космические приключения» / «Space Adventures» / «Uzay Maceraları» не считать уникальным коммерческим брендом.
На Этапе 2:
1. Создать пул брендовых кандидатов.
2. Проверить RU / EN / TR.
3. Проверить очевидные конфликты в играх, приложениях, веб-поиске и доступных источниках товарных знаков.
4. Не путать предварительный поиск с юридическим trademark clearance.

## 15. Риски
- Большой вес графики и медленная первая загрузка.
- Просадки FPS/GPU на слабых мобильных устройствах.
- Избыток прозрачности, частиц и постэффектов.
- Потеря читаемости Match-3 из-за сложного фона.
- Scope creep до проверки Core Loop.
- Неуникальное текущее рабочее название.
- Возможные изменения/ограничения требований Яндекс Игр.

## 16. Открытые вопросы
- Финальное коммерческое название RU/EN/TR.
- Нужен ли постоянный герой и какова его роль.
- Архитектура карты после первого уровня и первой главы из 20 уровней.
- Точный размер поля и стартовый набор типов фишек.
- Точные performance budgets.
- Финальная экономика и рекламные точки.
- Локализация релизной версии.

## 17. История решений
### 2026-09-21 — D-001
Утверждён Phaser 3 и HTML5/Yandex Games как направление первой версии.

### 2026-09-21 — D-002
Утверждена единая адаптивная игра для 16:9 desktop и 9:16 mobile. Длинная сторона внутреннего рендера ограничивается 1920 px.

### 2026-09-21 — D-003
Утверждён 2.5D визуальный подход с реалистичными космическими фонами.

### 2026-09-21 — D-004
Утверждён asset pipeline на основе прозрачных элементов/атласов с оптимизацией и загрузкой контента по необходимости.

### 2026-09-21 — D-005
Vertical Slice начинается с одного полностью рабочего уровня. После него обязательное обсуждение карты; первая планируемая глава — 20 уровней.

### 2026-09-21 — D-006
Текущее название остаётся рабочим до naming-sprint RU/EN/TR.

## 18. Stage Gates
- Stage 1: APPROVED.
- Stage 2: IN PROGRESS.
- Stage 3–16: NOT STARTED.

## 19. Следующее действие
Выполнить Этап 2: исследовать прямых/косвенных конкурентов и аудиторию, отзывы, монетизацию, платформенные риски и naming; сформировать проверяемое отличие и предварительную гипотезу спроса.

## 20. Stage 2 — Research Update 2026-09-23
Подробное исследование ведётся в `docs/STAGE_02_MARKET_AUDIENCE_RESEARCH.md`.

### Утверждённые продюсером входные данные Stage 2
- Полная структура контента: 5 глав × 20 последовательных уровней = 100 уровней.
- Прогресс должен сохраняться.
- Сложность должна расти постепенно.
- Необходимо избежать шаблонной формулы «космос + Match-3».
- Одобрены реакции мира: спасённый космонавт летит к шлюзу; разрушенный метеорит вылетает фрагментами за поле; победа продвигает корабль; Match-5 может вызывать редкое внешнее космическое событие/НЛО; каскады получают усиливающиеся combo-эффекты.
- Stage 2 не закрывается до тщательного исследования и отдельного утверждения продюсером.

### Рабочее конкурентное отличие
`Reactive Space Journey`: Match-3 является системой управления живым путешествием; действия на поле имеют непосредственные визуальные последствия в кабине, корабле и внешнем космосе. Это рабочая гипотеза USP, ещё не финально утверждённая.

### Герой
Статус: EXPERIMENT. Герой/пилот рассматривается как лёгкий сюжетный проводник и источник эмоциональной непрерывности, но не как обязательная gameplay-механика Vertical Slice. Решение принять после тестирования.

### Naming shortlist v0.1 — НЕ ФИНАЛЬНЫЙ
1. STARQUANTA / СтарКванта
2. COSMIONYX / Космионикс
3. STELLARQUA / Стелларква
4. ASTRAVOY / Астравой
5. QUANTASTRA / Квантастра

Все кандидаты требуют расширенной проверки RU/EN/TR, игровых магазинов и товарных знаков до выбора. Предварительный веб-поиск не является юридическим clearance.

### Новые риски
- Даже космическое путешествие + combo встречается у конкурентов; USP должен проявляться системно в gameplay.
- Слишком активное реактивное окружение может отвлекать от читаемости поля.
- Герой может замедлить короткие сессии, если диалоги обязательны.
- 100 уровней требуют контролируемой кривой сложности и контентного pipeline.
- Нужна версия схемы cloud save и защита от потери прогресса.

### Stage Gate
Stage 2: IN PROGRESS. Не переходить к Stage 3 без финальной проверки критериев и подтверждения продюсера.


## 21. Stage 2 — Producer Decisions, Iteration 2 (2026-09-23)
Source detail: `docs/STAGE_02_MARKET_AUDIENCE_RESEARCH.md`.

### D-007 — APPROVED: Reactive Space Journey
Final Stage-2 USP direction approved: **MATCH-3 → REACTIVE LIVING WORLD → CONTINUATION OF THE JOURNEY.** Match-3 actions physically affect the cockpit/ship/external-space scene.

### D-008 — APPROVED: Hyperdrive Combo
Cascades receive escalating audiovisual feedback and may culminate in a short hyperdrive-like event without harming board readability.

### D-009 — APPROVED: 5 chapters × 20 levels
Total planned campaign: 100 sequential levels. Difficulty increases gradually. Every ~10 levels a Challenge/Bonus cadence may be used, but it must not become an automatic unfair spike.

### D-010 — APPROVED: obstacle progression
Core obstacle families begin with layered frozen/cryo cells, rock/regolith cells, scorched/burnt breakable cells, meteorite/debris blockers and later energy shields. Advanced obstacles require multiple hits/layers with visually explicit damage states. Gravity anomaly remains experimental.

### D-011 — APPROVED: astronaut reactive text
The astronaut/pilot may deliver short contextual/humorous 0+ phrases triggered by gameplay events, localized RU/EN/TR, with cooldown/anti-repeat and without covering critical cells.

### D-012 — APPROVED: fairness principles
No artificial difficulty walls; no deliberately predetermined-feeling RNG losses; no ad interrupting an active cascade; no progress loss; loss reason must be understandable; celebratory animations must not become forced friction.

### D-013 — APPROVED: controlled RNG
Guarantee valid moves/recovery, controlled generation, automated simulations and statistical level validation.

### D-014 — APPROVED: save architecture
Cloud-backed campaign progress; versioned SaveService separated from Match-3 engine; Yandex adapter plus local fallback.

### D-015 — APPROVED: scope exclusions
Before core validation do not add base building, PvP, clans, battle pass, many currencies, pets or RPG ship progression.

### Setting direction — OPEN
Do not default to the Solar System. Research real exoplanet systems versus original science-inspired systems. Current technical/product recommendation: fictional destinations inspired by real astronomy, to preserve visual/story freedom while avoiding false claims about speculative habitability/appearance. Producer decision pending.

### Hero — PRELIMINARILY APPROVED
Hero is the astronaut/pilot-explorer sent to investigate potentially habitable/new worlds. Role as lightweight guide/story anchor is provisionally accepted, not final.

### Lives — OPEN
Finite lives approved in principle. Exact cap, regeneration, loss and rewarded recovery parameters remain unapproved pending design/playtesting.

### Naming — PRELIMINARILY APPROVED
`STARQUANTA` is the preferred working candidate, not final. Deeper search found prior open-web use of “StarQuanta” as a fictional video-game company in an LSAT question and “Gold Star Quanta” as a technical product phrase. This does not by itself establish a game-trademark conflict, but prevents claiming uniqueness. Long subtitle “Космическое путешествие” rejected.

### Stage Gate
Stage 2 remains IN PROGRESS. Remaining: setting decision, final naming clearance/choice, lives parameters, 100-level macro curve, demand-validation metrics/thresholds.


## 22. Stage 2 — Producer Decisions, Iteration 3 (2026-09-24)

### D-016 — APPROVED: Science-Inspired Fiction
Original fictional star systems inspired by real astrophysics. Do not use the Solar System as campaign structure and do not present speculative real exoplanet habitability/appearance as fact.

### D-017 — Chapter setting direction
- Ch1: red-dwarf frontier — approved.
- Ch2: frozen planet + blue giant — approved direction; science-inspired, not strict astrophysical habitability claim.
- Ch3: oceanic world — approved.
- Ch4: binary-star system + asteroid fields — approved.
- Ch5: exotic finale near black-hole / luminous violet-blue-green environment — concept under refinement.
Chapter names remain OPEN.

### D-018 — APPROVED: chapter-map route families
Ch1 smoothed complex cycloid; Ch2 sinusoid; Ch3 circle involute; Ch4 Cornu/Euler spiral; Ch5 tightening spiral with final node in center. Geometry is art-direction guidance; readability/node spacing wins over mathematical purity.

### D-019 — Obstacle implementation direction
Energy Shield: Ch3, 1–2 layers, transparent/readable; possible emitter-linked variant later.
Gravity Anomaly: Ch5; v1 is localized, telegraphed pull behavior between resolution steps. Global gravity rotation rejected for MVP.

### D-020 — Hero tone
Pilot-explorer: competent, curious, humane; seriousness + restrained dry/self-aware humor. Tonal inspiration may come from Ryland Grace / Project Hail Mary, but no copying of dialogue, likeness, backstory, costume or protected expression. Status remains PRELIMINARILY APPROVED pending original character bible.

### D-021 — Lives experiment
Finite lives. Prototype candidate: cap 5; lose one on failed level; replenish approximately 25–30 min; optional opt-in rewarded recovery; no technical-failure consumption. Exact values remain OPEN pending data.

### D-022 — Monetization direction
Rewarded-first; all rewarded ads explicitly opt-in with clear reward. Interstitial only natural pauses and never active gameplay; conservative eligibility/cooldown. Sticky banner only map/menu if premium presentation survives testing; hide on board. IAP later; no paywall-driven difficulty.

### Naming update
Rejected/low-priority after search: «Космический джем» (Space Jam conflict), «Звёздный искатель» (active STARSEEKER game use), «Космический фонтан» (established technical concept), «Космические поиски» (generic/existing phrase usage). New Russian-first candidates requiring clearance: «Космопоиск», «Звёздный импульс», «Космокаскад», «Кванты звёзд», «Звёздный манёвр». STARQUANTA remains parallel working candidate.

### D-023 — Macrocurve v0.1
100-level macrocurve drafted in `docs/STAGE_02_MARKET_AUDIENCE_RESEARCH.md`: obstacle/mechanic introductions are staged across chapters; every 10-level block follows teach/practice/combine/challenge-or-bonus; L100 is mastery/story payoff rather than a new-rule dump.

### D-024 — Stage 3 validation gates proposed
Prototype gates include tutorial/objective comprehension, Reactive Space Journey recognition, continuation/retry behavior, session-duration investigation thresholds, fairness/satisfaction survey scores, and later D1/D3/D7 cohort tracking. Exact thresholds are project hypotheses and must be calibrated from real test data.

### Visual asset plan
Stage 2/3 concept assets needed: 5 chapter maps, 5 cockpit/environment keyframes, obstacle sheet, hero expression sheet, board-effects sheet, and Level-1 full-screen mockup. Generate only after briefs/route directions are approved to avoid waste.

### Stage Gate
Stage 2 remains IN PROGRESS. Remaining: chapter names + final Ch5 art concept; naming final shortlist/clearance; approve obstacle implementations; approve macrocurve v0.1; approve Stage-3 metric gates; finalize hero originality brief; lives remain experiment by design.
