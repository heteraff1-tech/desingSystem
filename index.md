# AI Harness

**Статус продуктовой индексации: blocked.** По ссылке на Figma доступна пустая страница с двумя подключёнными библиотеками. Локальные компоненты, Variables и Text Styles отсутствуют. Число 6 930 и состав продуктовой библиотеки пока не подтверждены. Для завершения нужны исходный файл опубликованной библиотеки и код темы или экспорт переопределений Bootstrap 5.3.

| Файл | Назначение |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Порядок чтения и пять запретов. |
| [index.md](index.md) | Карта харнеса, источники и статус покрытия. |
| [tokens/summary.md](tokens/summary.md) | Семантические имена, Text Styles и покрытие токенов. |
| [tokens/tokens-dtcg.json](tokens/tokens-dtcg.json) | DTCG-реестр для точечной сверки и статус источников значений. |
| [catalog/bootstrap-mapping.md](catalog/bootstrap-mapping.md) | Выбор по UI-роли, ограничения и ключи подтверждённых Figma-компонентов Community Kit. |
| [catalog/ignore-and-deprecated.md](catalog/ignore-and-deprecated.md) | Фильтры служебных элементов и запреты на дубли. |
| [.skills/build-from-ds/SKILL.md](.skills/build-from-ds/SKILL.md) | Сборка прототипа или прод-интерфейса и самопроверка. |

## Источники

- [Файл сценариев Figma](https://www.figma.com/design/0AZ3iKitwR3w56MMVtPWCa?node-id=0-1) подключён к `Bootstrap 5 Design System - UI Kit (Community)` и одной командной библиотеке. Подключение само по себе не подтверждает продуктовый канон.
- [CSS-переменные Bootstrap 5.3](https://getbootstrap.com/docs/5.3/customize/css-variables/) задают версию базы. Переданная [инструкция установки 6.0](https://getbootstrap.com/docs/6.0/getting-started/install/) относится к другой ветке.
- [SberZdorovie](https://github.com/heteraff1-tech/SberZdorovie/blob/main/AGENTS.md) подтверждает собственные Vue-обёртки для этого репозитория. Его [зависимости](https://github.com/heteraff1-tech/SberZdorovie/blob/main/app/package.json) не включают Bootstrap. Используй профиль только при работе с этим репозиторием.
