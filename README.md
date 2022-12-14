# Исследование надёжности заёмщиков
## Описание
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.
## Вопросы
1. Есть ли зависимость между количеством детей и возвратом кредита в срок?
2. Есть ли зависимость между семейным положением и возвратом кредита в срок?
3. Есть ли зависимость между уровнем дохода и возвратом кредита в срок?
4. Как разные цели кредита влияют на его возврат в срок?
## Данные
**Описания колонок:**
* `children` — количество детей в семье;
* `days_employed` — общий трудовой стаж в днях;
* `dob_years` — возраст клиента в годах;
* `education` — уровень образования клиента;
* `education_id` — идентификатор уровня образования;
* `family_status` — семейное положение;
* `family_status_id` — идентификатор семейного положения;
* `gender` — пол клиента;
* `income_type` — тип занятости;
* `debt` — имел ли задолженность по возврату кредитов;
* `total_income` — ежемесячный доход;
* `purpose` — цель получения кредита.
## Задачи
- Выяснить есть ли зависимость между количеством детей и возвратом кредита в срок?
- Выяснить есть ли зависимость между семейным положением и возвратом кредита в срок?
- Выяснить есть ли зависимость между уровнем дохода и возвратом кредита в срок?
- Выяснить как разные цели кредита влияют на его возврат в срок?
## Используемые библиотеки
_pandas_
