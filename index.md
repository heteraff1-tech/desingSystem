# AI Harness

[Bootstrap Community Kit](https://www.figma.com/design/z0mUSQgmrlvdYjKAixYr41/Bootstrap-5-Design-System---UI-Kit--Community-?node-id=0-1) проиндексирован целиком. В рабочем каталоге 54 канона, у каждого подтверждён ключ публикации. Продуктовые переопределения Bootstrap 5.3 остаются открытым вопросом до сверки с кодом темы.

| Файл | Назначение |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Порядок чтения и пять запретов. |
| [index.md](index.md) | Покрытие, источники и карта харнеса. |
| [tokens/summary.md](tokens/summary.md) | Имена Variables, семантических стилей и Text Styles. |
| [tokens/tokens-dtcg.json](tokens/tokens-dtcg.json) | Значения Figma для точечной сверки по имени. |
| [catalog/bootstrap-mapping.md](catalog/bootstrap-mapping.md) | Навигация, оверлеи и карта профилей. |
| [catalog/bootstrap-controls.md](catalog/bootstrap-controls.md) | Кнопки, основные поля и выбор. |
| [catalog/bootstrap-forms.md](catalog/bootstrap-forms.md) | Специальные поля, загрузка и перенос. |
| [catalog/bootstrap-content.md](catalog/bootstrap-content.md) | Контент, состояния и обратная связь. |
| [catalog/ignore-and-deprecated.md](catalog/ignore-and-deprecated.md) | Служебные элементы, повторяющиеся обёртки и архивные версии. |
| [catalog/health.md](catalog/health.md) | Каноны опубликованного профиля «Здоровье». |
| [.skills/build-from-ds/SKILL.md](.skills/build-from-ds/SKILL.md) | Сборка и самопроверка по выбранному профилю. |

## Покрытие Bootstrap Community Kit

| Срез Figma | Количество |
| --- | ---: |
| Страницы | 62 |
| Одиночные компоненты / наборы / варианты | 2 155 / 217 / 4 374 |
| Определения компонентов, всего | 6 746 |
| В том числе определения на странице Icons | 2 118 |
| Variables / Text Styles / Paint Styles / Effect Styles / Grid Styles | 2 / 36 / 421 / 27 / 9 |
| Всего определений и токенов | 7 241 |
| Публичные каноны, подтверждённые ключом | 54 |

Компонентные варианты учитываются в инвентаризации и выбираются внутри родительского набора. В каталоге остаётся одна строка на UI-роль. Профиль «Здоровье» имеет собственные 13 канонов Figma и Vue-обёртки. Его размеры и типографика заданы собственными токенами.

## Источники кода

- [Документация CSS-переменных Bootstrap 5.3](https://getbootstrap.com/docs/5.3/customize/css-variables/) задаёт базу. Переданная [инструкция установки 6.0](https://getbootstrap.com/docs/6.0/getting-started/install/) относится к другой ветке.
- [SberZdorovie](https://github.com/heteraff1-tech/SberZdorovie/blob/main/AGENTS.md) использует Vue-обёртки и [собственные токены](https://github.com/heteraff1-tech/SberZdorovie/blob/main/app/docs/design-system.md).
