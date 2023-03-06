# Кибериммунное устройство мониторинга оборудования (КУМО).

## Краткое описание назначения и применения продукта.

КУМО получает данные от промышленного оборудования из внутренней сети, обрабатывает эти данные, в случае превышения пороговых значений генерирует события, которые пользователь из внешней сети может получить для дальнейшего анализа.

## Ценности продукта

- Информативность передаваемых данных.
- Корректность регистрации триггеров событий.
- Корректность передаваемых инструкций.
- Конфиденциальность информации о тех. процессе (коммерческая тайна).

## Неприемлемые события или сценарии в отношении ценностей продукта

- Сбой в работе сервера.
  - Нарушение тех. процесса.
  - Аварийные ситуации влекущие поломку оборудования.
  - Аварийные ситуации влекущие производственные травмы и/или гибель людей.
  - Простой оборудования.
- Вмешательство в передачу информации/сценариев.
  - Аварийные ситуации влекущие поломку оборудования.
  - Простой оборудования.
  - Утечка информации о тех. процессе.
  - Нарушение целостности передаваемой информации.

## Цели безопасности

- Возможность полного или частичного обновления КУМО.
- Доступ к информационной системе имеется только у авторизованных сотрудников имеющих право на доступ.
- Конфиденциальность данных о тех. процессе.
- Корректность регистрации триггеров событий.
- Корректность передаваемых инструкций.

## Предположения безопасности

- Авторизованные сотрудники с правом на доступ к информационной системе считаются благонадежными.

- Потенциальные злоумышленники не имеют возможности физического воздействия на КУМО.

- Не существует технически осуществимого сценария компрометации данных аутентификации и авторизации.

- Во время передачи данных используется сквозное шифрование.

  

## Роли пользователей

#### Оператор технологического оборудования

* Мониторинг состояния закреплённого за оператором технологического оборудования.
* Мониторинг технического процесса проходящего на закреплённом за оператором технологическим оборудованием.

#### Инженер технолог

* Мониторинг состояния всего технологического оборудования на предприятии.
* Мониторинг всех технологических процессов процессов проходящих на предприятии.
* Управление системой оповещения аварийных ситуаций.
* Журнал обслуживания и ремонта технологического оборудования. 

#### Мастер бригады ремонта и обслуживания технологического оборудования

* Ремонт и обслуживания технологического оборудования на предприятии.

## Верхнеуровневые сценарии (режимы) работы продукта

![верхнеуровневый сценарий]([C:\Users\Egorka\Desktop\киберимунка дз\верхнеуровневый сценарий.PNG](https://github.com/Egor-Always-AFK/course_cyberimmune/blob/homework1/%D0%B2%D0%B5%D1%80%D1%85%D0%BD%D0%B5%D1%83%D1%80%D0%BE%D0%B2%D0%BD%D0%B5%D0%B2%D1%8B%D0%B9%20%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B9.PNG?raw=true))
