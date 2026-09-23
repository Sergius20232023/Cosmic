# Этап 2 — Исследование рынка и аудитории

Дата: 2026-09-23  
Статус: IN PROGRESS — документ не является финальным Stage 2.

## 1. Цель исследования
Определить, чем проект Cosmic может отличаться от шаблонного «космос + Match-3», какие элементы повышают удержание, какие причины ухода нужно исключать, нужен ли герой, как строить 5 глав по 20 уровней и какие названия достойны финальной проверки.

## 2. Зафиксированные требования продюсера
- 5 глав × 20 последовательных уровней = 100 уровней.
- Прогресс сохраняется.
- Сложность растёт постепенно.
- Тема: приключенческое sci-fi путешествие.
- Не высаживаемся на планеты как обязательная механика: корабль путешествует между космическими объектами.
- Финальное визуальное качество важно с первого Vertical Slice.
- Desktop 16:9 + mobile 9:16, один проект; длинная сторона внутреннего рендера ≤1920 px.
- Реалистичные космические фоны + 2.5D фишки.
- Атласы и загрузка контента по главам/необходимости.

## 3. Конкурентное поле

### Прямые конкуренты на Яндекс Играх
1. «Космический три в ряд» (2026): космическая тема, задания, препятствия, уровни, бустеры, рулетка, облачные сохранения.
2. «Галактический бум: Три в ряд» (2026): ракеты, планеты, НЛО, спутники, метеоры; короткие сессии, каскады, перемешивание при отсутствии ходов, облачные сохранения.

Вывод: космос, ракеты, НЛО и планеты — сеттинг, а не USP.

### Косвенные/жанровые ориентиры
- Royal Match: handcrafted уровни, препятствия, power-ups, открытие новых областей/комнат, события и награды. Сильная связка «пазл → мета-прогресс».
- Gardenscapes: Match-3 + восстановление/исследование зон + персонаж и сюжет.
- Fishdom: Match-3 + живое пространство между уровнями; существа реагируют на игрока.
- DOPA-MATCH3: Cosmic Journey (2026): космос + Match-3 + HEAT/combo + постоянные upgrades. Это подтверждает, что даже «космическое путешествие + комбо» само по себе уже недостаточно уникально.

## 4. Что может стать настоящим отличием

### Рабочая концепция: Reactive Space Journey
Игровое поле — не отдельная таблица поверх фоновой картинки. Это навигационно-энергетическая система корабля, а результат Match-3 физически отражается на окружающем путешествии.

Три слоя должны работать одновременно:
1. Puzzle Layer — понятный, качественный Match-3.
2. Reactive Journey Layer — окружение реагирует на совпадения и цели.
3. Chapter Journey Layer — каждое прохождение реально продвигает корабль по маршруту пяти глав.

### Конкретные реакции мира
- Спасённый космонавт покидает клетку/капсулу, пролетает за границу поля и направляется к шлюзу.
- Разрушенный метеорит раскалывается с глубиной, фрагменты уходят за плоскость доски.
- Кристаллы/энергия визуально транспортируются в двигатель или корабельную систему.
- Победа: доска переходит в безопасный режим, двигатель зажигается, внешний фон получает движение/параллакс и корабль продолжает маршрут.
- Match-5: редкое «космическое окно» — уникальное НЛО, аномалия, комета или краткая смена внешней сцены. Это награда-сюрприз, не влияющая на честность уровня.
- Каскады: растущий Combo/Hyperdrive meter. Каждая последовательная автоматическая реакция усиливает свет, звук и динамику; при высоком комбо корабль кратко входит в режим гиперпрыжка.
- Спецкомбо должны иметь разные «физические» последствия: плазменный луч, гравитационная линза чёрной дыры, ударная волна сверхновой.

### Почему это лучше обычного тематического Match-3
USP формулируется не как «Match-3 в космосе», а как:
**«Каждая комбинация управляет живым космическим путешествием вокруг игрового поля».**
Это проверяемое продуктовое обещание: если убрать реактивное окружение и путешествие, игра должна заметно потерять идентичность.

## 5. Пять глав
Рабочая структура, пока не финальная:
- Глава 1 — Орбита Земли: обучение, станция, спутники, первые спасательные задачи.
- Глава 2 — Луна и Марс: пыль, метеориты, повреждённые аппараты, первые составные препятствия.
- Глава 3 — Пояс астероидов: более динамичная среда, опасности и защитные задачи.
- Глава 4 — Газовые гиганты: магнитные/энергетические явления, новые типы препятствий.
- Глава 5 — Глубокий космос: аномалии, редкие НЛО, финальные комбинации знакомых механик.

Правило сложности: новая механика вводится безопасно, затем комбинируется с уже знакомыми; сложность не должна расти только за счёт уменьшения ходов.

## 6. Герой — исследовательская гипотеза

### Что герой может дать
- эмоциональную непрерывность между 100 уровнями;
- понятный голос обучения;
- причину двигаться дальше («миссия», а не список уровней);
- реакцию на открытия и редкие события;
- узнаваемый образ для иконки/промо;
- возможность коротких сюжетных сообщений без тяжёлых кат-сцен.

### Риски
- дорогая анимация и локализация;
- герой может закрывать игровое поле;
- слишком много диалогов замедляет короткую сессию;
- плохо написанный герой раздражает сильнее, чем отсутствие героя.

### Рабочее решение
Для Vertical Slice герой НЕ является обязательной механикой. Проверяем «лёгкого проводника»: пилот/исследователь появляется в начале главы, в редких реакциях и после ключевых уровней; обучение — короткие реплики/жесты. Никаких обязательных длинных диалогов. После пользовательского теста сравниваем понимание, эмоциональную вовлечённость и желание продолжить.

## 7. Ожидания игроков и причины ухода

### Ожидания
- мгновенно понятное управление;
- честный и читаемый результат хода;
- быстрые анимации без потери сочности;
- разнообразные цели;
- заметная награда за skillful combo;
- отсутствие тупиков;
- сохранение прогресса;
- ощущение продвижения;
- добровольная, полезная rewarded-реклама.

### Причины ухода и профилактика
- Резкий difficulty spike → кривая сложности, telemetry, лимит повторных поражений при тестировании.
- Уровень кажется зависимым от RNG → гарантировать допустимые ходы, контролировать генерацию и стартовое поле; тестировать solvability статистически.
- Долгие/навязчивые анимации → большинство эффектов короткие; после первого просмотра допускается ускорение.
- Навязчивая реклама → rewarded-first; полноэкранную рекламу только в естественных паузах и согласно правилам платформы.
- Потеря прогресса → cloud save, versioned save schema, безопасный fallback.
- Непонятные цели → цель видна до старта и во время уровня; первый пример каждой новой механики максимально очевиден.
- Повторяемость → новая механика/вариация ритмично вводится по главам, но без feature overload.
- Paywall feeling → первые главы должны проходиться без покупки; покупка ускоряет/помогает, а не заменяет решение пазла.
- Слабая связь метаигры с Match-3 → реакции мира должны происходить прямо во время уровня, а не только на отдельной карте.
- Тяжёлая загрузка/лаги → атласы, on-demand chapter assets, caps на частицы, pooling, quality tiers, performance tests на слабых устройствах.
- Ложные ожидания рекламы/описания → маркетинговые скриншоты и ролики показывают реальный core gameplay.

## 8. Монетизация — направление
- Rewarded ad: дополнительные ходы после поражения (с ограничением), дополнительная награда, бесплатный pre-level booster, редкий бонус.
- Interstitial: только в естественных паузах и не так, чтобы разрушать flow; частоту определить тестами и требованиями платформы.
- IAP: валюта/бустеры/пакеты — после проектирования экономики.
- Не строить сложность намеренно вокруг принуждения к просмотру рекламы/покупке.
- Слой монетизации отделён от Match-3 engine.

## 9. Сохранения
Для 100 последовательных уровней облачное сохранение — базовое требование проекта. Сохранять как минимум: schemaVersion, highestUnlockedLevel, completedLevels, chapterProgress, currencies, boosters, settings, tutorialFlags, storyFlags, purchases/entitlements where applicable. Match-3 runtime не должен напрямую зависеть от Yandex SDK: использовать SaveService/adapters.

## 10. Naming sprint — SHORTLIST v0.1
Ни одно имя пока не утверждено. Это только кандидаты для дальнейшей проверки RU/EN/TR и юридического clearance.

### A. STARQUANTA / «СтарКванта»
Сильная связь «звёзды + квант/энергия». Хорошо подходит к sci-fi и механике энергетических комбинаций. Предварительный веб-поиск не выявил очевидного одноимённого игрового проекта в проверенных запросах. Нужна расширенная trademark/store/domain проверка.

### B. COSMIONYX / «Космионикс»
Cosmos + onyx/технологическое звучание. Хорошо для более премиального sci-fi бренда. Предварительный поиск не выявил очевидного одноимённого игрового проекта в проверенных запросах. Требуется расширенная проверка.

### C. STELLARQUA / «Стелларква»
Stellar + вымышленный технологический суффикс. Сразу считывается звёздная тема, но требует проверки произношения/восприятия в TR и trademark search.

### D. ASTRAVOY / «Астравой»
Astra + voyage. Смысл путешествия читается без слова Adventures. Требуется расширенная проверка на сходные бренды и варианты AstraVoy/Astravoy.

### E. QUANTASTRA / «Квантастра»
Quanta + astra. Связывает Match-3 энергию/комбо с космосом. Предварительный кандидат; требуется расширенная проверка магазинов, доменов и товарных знаков.

Исключённые в ходе предварительного поиска варианты: Space Adventures, Cosmic Journey, Cosmic Odyssey, Starward, Starweave, Astronelle, Astralume, Novalume, Nebulora, Orbitara и другие — обнаружены существующие игры/бренды/активные обозначения.

### Локализация названия
Предпочтение: один международный бренд без перевода + локализованный descriptor:
- RU: [BRAND] — Космическое путешествие
- EN: [BRAND] — A Space Match Adventure
- TR: [BRAND] — Uzay Eşleştirme Macerası
Descriptor не является частью уникального word mark до отдельного решения.

## 11. Критерии дальнейшего выбора имени
Финалист должен:
- легко читаться на русском, английском и турецком;
- явно или через визуальный бренд ассоциироваться с космосом;
- не путаться с крупной существующей игрой/приложением;
- быть коротким для иконки и каталога;
- иметь приемлемый поисковый шум;
- пройти отдельную проверку игровых магазинов, веба и доступных реестров товарных знаков.
Предварительная проверка не является юридическим заключением.

## 12. Что проверяем до закрытия Stage 2
- расширить конкурентную таблицу и выделить механики, которые берём как стандарт качества, а не копируем;
- сформировать difficulty/retention principles для 100 уровней;
- выбрать один из пяти naming-кандидатов либо сформировать второй shortlist;
- окончательно утвердить USP;
- определить роль героя как «есть / нет / эксперимент»;
- сформировать риски спроса и метрики будущей проверки идеи.

## 13. Текущий вывод
Направление «Match-3 + sci-fi путешествие» является хорошей базой для первой игры, потому что core mechanic знаком игроку и снижает стоимость обучения. Но рыночное отличие должно появляться не из темы, а из системной связи пазла с путешествием. Рабочий кандидат USP: **Reactive Space Journey — Match-3, где успешные действия физически оживляют кабину, корабль и внешний космос, а каждая победа продолжает единое путешествие через 5 глав.**


## 14. Producer Review — Iteration 2 (2026-09-23)

### APPROVED — Core differentiation
Approved product formula:
**MATCH-3 → REACTIVE LIVING WORLD → CONTINUATION OF THE JOURNEY.**

The board is part of controlling the space journey. Player actions physically change the surrounding scene. Internal working name of the system: **Reactive Space Journey**.

### APPROVED — Reactive world examples
- Rescued astronaut flies from the board to the airlock.
- Destroyed meteorite breaks into fragments that leave the board plane.
- Collected energy/resources can visually travel into ship systems.
- Level completion advances the ship toward the next destination.
- Match-5 can trigger a rare external-space event (UFO/anomaly/comet/scene event).
- Cascades drive the approved Hyperdrive Combo presentation.

### UPDATED — Setting
The five chapters MUST NOT default to the Solar System.
Two directions remain under research:
A. Science-inspired route based on real exoplanet systems / habitable-zone discoveries.
B. Original fictional systems inspired by real astrophysics, allowing stronger art direction and story freedom.

Research conclusion for next decision: prefer a **science-inspired fictional route** unless producer later chooses strict real-system names. Real astronomy can inspire star type, tidal locking, ocean/ice worlds, atmospheric colors and orbital geometry, while fictional destinations avoid falsely presenting speculative planet appearance or habitability as established fact.

Scientific reference pool:
- TRAPPIST-1: seven Earth-sized rocky planets; e/f/g are in the conventional habitable zone. Useful visual ideas: ultra-cool red dwarf, compact sky, tidal-locking-inspired day/night contrasts.
- K2-18 b: habitable-zone sub-Neptune/super-Earth-scale world with methane and CO2 detections; useful inspiration for oceanic/hydrogen-atmosphere imagery, but NOT proof of habitability or life.
Rule: “habitable zone” must never be presented as “inhabited.”

### APPROVED — Obstacle progression
Obstacle system becomes a core progression axis. Initial families:
- Cryo/Frozen cell: layered ice; early version 1 hit, advanced variants 2–3 layers.
- Rock/Regolith cell: cracked rocky shell; progressively reinforced variants.
- Scorched/Burnt cell: brittle heat-damaged layer; breakable, visually distinct from rock.
- Meteorite/Space debris blocker: physical obstacle with staged damage.
- Energy shield: later chapter obstacle; disabled by adjacent matches or specified energy interactions.
- Gravity anomaly: late-game candidate that affects board rules; remains EXPERIMENT until concept/MVP stage.

Design rule: obstacle difficulty grows through layers and combinations, not only by lowering available moves. Every obstacle requires a clear damage-state visual.

### APPROVED — Astronaut reactive phrases
The astronaut/pilot may produce short contextual phrases after noteworthy events. Requirements:
- short enough not to interrupt play;
- family-safe / 0+;
- localized RU/EN/TR;
- event-triggered with cooldown and anti-repetition;
- text bubble/voice-like UI must never cover critical board cells.
Example event categories: large combo, near-failure, rare UFO, astronaut rescue, first encounter with a new obstacle, victory.

### APPROVED — Difficulty philosophy
No artificial difficulty walls. No loss that feels predetermined by RNG. No advertising that interrupts an active cascade. No progress loss. Loss must communicate why it happened. Long celebratory animations must not become mandatory friction.

Proposed cadence to test:
- Levels 1–8: normal progression/training/application.
- Level 9: preparation/combination challenge.
- Level 10: Challenge Mission OR Bonus Mission.
This cadence repeats per ten-level block but MUST NOT automatically mean a difficulty spike every tenth level. Challenge levels test mastery; Bonus levels provide relief/reward. Exact alternation will be designed in Stage 4/5 and validated by telemetry.

### Lives — OPEN DESIGN
Lives are finite, not infinite. Exact cap, regeneration timer, loss rules and rewarded recovery are NOT yet approved. Required principles:
- enough attempts to learn without immediate session termination;
- scarcity must not become coercive;
- rewarded ad may provide an optional extra life/attempt where platform rules permit;
- economy must be tuned from playtest data, not guessed as final at Stage 2.

### APPROVED — RNG
Controlled board generation, guaranteed valid moves, shuffle/recovery, automated simulation and statistical level validation are required.

### APPROVED — Save architecture
Cloud-backed progression is required for the 100-level journey. SaveService must be separated from Match-3 logic and use a Yandex adapter plus local-development fallback. Save schema is versioned.

### Monetization — Stage 2 recommendation
Rewarded-first remains the preferred model. Rewarded ads are optional and must clearly state the reward. Interstitial calls are limited to logical pauses and never interrupt active cascades/gameplay. Final frequency is deliberately not fixed before retention/playtest data.

### Naming update — STARQUANTA
Producer status: **PRELIMINARILY APPROVED, NOT FINAL.**
Important new conflict discovered during deeper search: “StarQuanta” already appears as the name of a fictional video-game company in an LSAT question that has been republished across multiple educational sites. This is not evidence of a registered game trademark, but it means the string is not genuinely unique on the open web.
Also “Gold Star Quanta” is an existing technical product name in liquid-scintillation materials.
Decision: keep STARQUANTA as the current preferred working candidate, but DO NOT finalize it before trademark/store/domain/confusion checks. A long subtitle such as “Космическое путешествие” is rejected by the producer. If a descriptor is needed, research shorter alternatives later.

### APPROVED — Scope exclusions
Do not add base-building, PvP, clans, battle pass, many currencies, pets, or RPG ship progression before the core loop proves itself.

## 15. Revised Stage 2 Gate
- [x] Target audience defined.
- [x] Direct competitors identified.
- [x] Core market risk identified: space theme alone is not differentiation.
- [x] USP concept approved: Reactive Space Journey.
- [x] 5 chapters × 20 levels approved.
- [x] Gradual difficulty philosophy approved.
- [x] Obstacles established as progression system.
- [x] RNG-control principles approved.
- [x] Save architecture principles approved.
- [x] Core churn-prevention principles approved.
- [x] Hero direction narrowed to astronaut/pilot-explorer, still requiring final role validation.
- [ ] Real vs fictional/science-inspired star systems — producer decision pending after research.
- [ ] Lives economy — parameters pending playtest-oriented design.
- [ ] STARQUANTA — final clearance/selection pending.
- [ ] 100-level macro difficulty/content curve — not yet specified.
- [ ] Stage 2 demand-validation metrics and thresholds — not yet finalized.

Stage 2 remains **IN PROGRESS**.


## 16. Producer Review — Iteration 3 (2026-09-24)

### APPROVED — Setting model
Science-Inspired Fiction is approved. The campaign uses original fictional star systems informed by real astrophysical phenomena, not the Solar System and not claims that speculative real exoplanets are inhabited.

### Chapter visual brief v0.2
1. Chapter 1: approved red-dwarf frontier concept. Mood: wonder, confidence, first-contact-with-the-unknown; warm red/coral light against cool cockpit UI.
2. Chapter 2: frozen planet under a blue giant. Mood: crystalline beauty, clarity, controlled danger rather than darkness. Scientific note: strict realism is intentionally relaxed; a blue giant is a short-lived, high-radiation star, so the chapter is science-inspired rather than a claim of likely habitability.
3. Chapter 3: approved oceanic world. Mood: discovery, calm grandeur, electrical atmosphere, deep cyan/turquoise/violet palette.
4. Chapter 4: binary-star system + asteroid fields. Mood: speed, navigation, unstable illumination, high-energy expedition; two moving light sources visually distinguish the chapter.
5. Chapter 5: exotic finale near a black hole with a blue-green/violet luminous companion/accretion environment. Recommended concept: “The Last Signal” — a safe fictional observation region around an exotic compact-object system, with gravitational lensing, warped starfield and a mysterious signal. Mood: awe, mystery, culmination, not horror.

Chapter names remain OPEN and must be co-selected with producer.

### APPROVED — Chapter map geometry
- Chapter 1: complex cycloid-like route with softened/smoothed turns.
- Chapter 2: sinusoidal route.
- Chapter 3: involute-of-a-circle route.
- Chapter 4: Cornu/Euler spiral route.
- Chapter 5: tightening spiral with the finale at the center.
Implementation note: these are visual path families, not strict mathematical plots; level-node spacing and tap readability override mathematical purity.

### Obstacle design — proposed implementation
**Energy Shield**
- Introduced Chapter 3.
- A translucent shield covers a cell/target but does not hide readability.
- Shield I: remove with one adjacent match or direct special hit.
- Shield II: two charge layers; first hit visibly destabilizes it.
- Later linked-shield variant: a small group shares an emitter; destroy/disable emitter to drop linked shields. Linked variant remains Stage-4/5 content candidate.
- Shield never changes tile color or makes legal-move recognition ambiguous.

**Gravity Anomaly**
- Introduced only in Chapter 5 after all core board rules are learned.
- Recommended v1: localized gravity well, not global direction reversal.
- It occupies a marked cell/zone and, after resolution, pulls a nearby movable tile one cell toward its center when this can be done without violating resolution-state safety.
- It is telegraphed before movement and never acts during player input.
- Special hits can destabilize/remove it depending on level objective.
- Full-board gravity rotation is rejected for MVP because it changes the mental model too sharply and increases implementation/test complexity.

### Hero — PRELIMINARILY APPROVED tone
The pilot-explorer should be competent, scientifically curious, humane, serious when stakes require it, and use dry/self-aware humor as tension relief. Inspiration is the tonal balance of Ryland Grace in Project Hail Mary; do not copy dialogue, likeness, backstory, costume or protected character-specific expression.
Hero phrases: serious + ironic + humorous, with cooldown, anti-repeat, localization and no board obstruction.

### Lives research — evidence and provisional design
Public sources rarely publish a reliable universal statistic for “attempts before frustration” specifically for Match-3; do not invent one. Useful observed anchors:
- Royal Match currently uses a 5-life cap and replenishes one life every 30 minutes.
- Broad 2025 mobile benchmarks from GameAnalytics show median sessions around 3.1–3.5 minutes, top-quartile around 5.2 minutes, with high performers longer; this is cross-game, not Match-3-specific.
Therefore the project should treat lives as an experiment, not copy a competitor blindly.

Provisional test configuration for prototype/closed test:
- cap: 5 lives;
- lose 1 only on failed level, not on quit before first move / technical failure;
- regeneration: 1 per 25–30 minutes (A/B candidate, not final);
- never consume a life on victory;
- optional rewarded recovery, clearly opt-in;
- first-session protection: early tutorial levels should be tuned so life depletion is unlikely.
Decision remains OPEN until Stage 3/14 data.

### Monetization — loyalty/revenue balance
Recommended launch philosophy:
1. Rewarded-first, opt-in.
2. Best placements: after loss for extra moves (limited), pre-level optional booster, post-win reward multiplier/bonus, optional life recovery.
3. Do NOT chain an interstitial immediately after rewarded.
4. Interstitial calls only at natural transitions and never active gameplay; use a conservative cooldown/eligibility layer even though Yandex controls actual serving frequency.
5. Sticky banner only on map/menu if visual tests show it does not damage premium presentation; hide during the board.
6. IAP later: small starter pack, currency/boosters, and optionally ad-removal for eligible non-rewarded formats; no pay-to-win wall.
7. Revenue optimization is subordinate to retention: track rewarded opt-in, ad-related exits, level-start continuation and D1/D7 before increasing ad pressure.

### Naming research — Russian-first round
Producer ideas reviewed:
- «Космический джем» — reject: strongly conflicts with the established Russian title of Space Jam and an existing Space Jam game/IP.
- «Звёздный искатель» — reject as primary brand: STARSEEKER / «Звёздный искатель» is already in active game use in the Astroneer ecosystem.
- «Космический фонтан» — not preferred: already an established technical concept for a space-launch megastructure; semantically weak for Match-3 journey.
- «Космические поиски» — understandable but generic; existing event/title usage appears in search and it undersells the reactive journey.

New Russian-first naming candidates for the next clearance round:
- «Космопоиск»
- «Звёздный импульс»
- «Космокаскад»
- «Кванты звёзд»
- «Звёздный манёвр»
These are candidates only, NOT cleared or final. STARQUANTA remains a parallel working candidate until final naming decision.

### Macrocurve 1–100 v0.1
Design principle per 10-level block: teach → practice → combine → challenge/relief. Challenge/Bonus cadence alternates to avoid predictable punishment.

| Levels | Chapter / focus | New or emphasized mechanics | Gate |
|---|---|---|---|
| 1–10 | Ch1 Red Frontier | basic swap/match, goals, moves; Cryo I at 4; simple collect/rescue at 6; rocket special at 7; cascades/Hyperdrive feedback | L10 Challenge: rescue + Cryo I |
| 11–20 | Ch1 | Cryo II; meteor/debris I; black-hole Match-5; T/L supernova; first mixed goals | L20 Chapter Finale: multi-goal, Rare Space Event |
| 21–30 | Ch2 Frozen World | Cryo III; Rock I; restricted-space layouts; stronger rescue | L30 Bonus: high-cascade crystal storm |
| 31–40 | Ch2 | Rock II/III; Scorched I introduced as thermal damage contrast; two-obstacle combinations | L40 Challenge: layered ice + rock |
| 41–50 | Ch3 Ocean World | Energy Shield I; energy-delivery objective; moving visual energy to ship | L50 Bonus: shield-chain spectacle, generous cascades |
| 51–60 | Ch3 | Energy Shield II; emitter/linked-shield prototype if readable; Scorched II; three-goal levels begin sparingly | L60 Challenge: shield + energy routing |
| 61–70 | Ch4 Binary/Asteroids | Meteor II/III; denser shaped boards; alternating environmental visual events (no rule ambiguity) | L70 Bonus: asteroid shower spectacle |
| 71–80 | Ch4 | reinforced debris; mixed layered obstacles; special-combo mastery; fewer tutorials | L80 Chapter Finale Challenge: mastery of Ch1–4 systems |
| 81–90 | Ch5 Last Signal | Gravity Anomaly I localized; anomaly objectives; advanced Rare Space Events | L90 Bonus: controlled anomaly cascade / high spectacle |
| 91–100 | Ch5 | Gravity Anomaly II + selected prior obstacles; mastery rather than new-rule overload | L100 Finale: multi-phase-feeling board, story payoff, center of spiral |

Balancing guardrails:
- Never introduce more than one cognitively major mechanic in the same level.
- First encounter is intentionally easy and demonstrates cause/effect.
- Advanced layer appears only after several exposures.
- Challenge level tests learned skills; it is not an arbitrary move reduction.
- Bonus level must be genuinely generous and visually rewarding.
- Level 100 combines mastered systems but should not introduce an entirely new core rule.

### Stage 3 validation metrics — proposed measurable gates
Because benchmarks differ by platform/source, these are INTERNAL prototype gates, not claimed industry laws.

Qualitative usability gates:
- ≥90% testers can make a valid first move without explanation after tutorial cue.
- ≥80% can correctly explain the current level objective after the first 3 tutorial levels.
- ≥80% correctly understand what damaged at least the first three obstacle families.
- ≥70% spontaneously notice at least one Reactive Space Journey reaction.
- ≥60% can describe the game afterward using both a Match-3 concept and a journey/world-reaction concept.

Behavioral prototype gates:
- Tutorial completion ≥85%.
- Level-1 completion ≥80% among users who start it.
- First-session reach Level 3 ≥65%.
- First-session reach Level 5 ≥45%.
- Median first-session active play target ≥8 minutes for recruited prototype testers; investigate if <5 min.
- “Play another level” continuation after first win ≥70%.
- Immediate retry after a fair loss ≥55%.
- Quit-after-loss rate should not materially spike on Challenge levels relative to surrounding levels; investigate >10 percentage-point spike.
- No single early level target median attempts >2.5 before Level 10; no early level should create a long-tail of repeated failures without an identified reason.

Experience survey gates (5-point scale):
- “Moves feel satisfying” mean ≥4.0.
- “I understand why I won/lost” ≥4.0.
- “The space world feels alive” ≥4.0.
- “I want to see the next destination” ≥4.0.
- “Ads/reward offers feel optional” ≥4.0 once monetization is tested.

Retention after public/closed test (not Stage-3 prototype-only):
Track D1, D3, D7 by source/device; do not declare universal pass/fail from a generic mobile benchmark. Establish project baseline first, then compare cohorts and iterations.

### Required visual assets — planning list
Do NOT generate final production art before chapter briefs are approved. For Stage 2/3 concept validation, generate:
1. Five chapter-map concept images (one per chapter), both landscape master composition and later responsive portrait adaptation.
2. Five cockpit/window environment keyframes (one per chapter).
3. One obstacle sheet: Cryo I–III, Rock I–III, Scorched I–II, Meteor I–III, Shield I–II, Gravity Anomaly.
4. One hero character sheet: neutral, focused, amused/ironic, surprised, victory reaction.
5. One board-effects sheet: Hyperdrive combo stages, Match-5 Rare Event, rescue-to-airlock, meteor break, energy-to-engine.
6. One Level-1 full-screen vertical-slice mockup after these visual rules are approved.

Prompt briefs are maintained below for image generation when producer requests generation.
