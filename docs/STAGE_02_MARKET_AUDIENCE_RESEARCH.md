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
