# Токены и Text Styles

Статус продуктовых токенов — `blocked`. Поля ниже фиксируют покрытие; значения проверяй в [DTCG](tokens-dtcg.json) после импорта подтверждённой темы.

| Группа | Подтверждённые продуктовые имена |
| --- | --- |
| Переопределения `--bs-*` | Нужен исходник темы Bootstrap 5.3. |
| Семантические цвета | Нужны Variables и их CSS-имена по ролям. |
| Радиусы | Нужна шкала с привязкой к компонентам. |
| Отступы | Нужна продуктовая шкала и её CSS-алиасы. |
| Тап-зоны | Нужны имена размеров интерактивных областей. |
| Text Styles | Нужен экспорт стилей библиотеки. |

Подключённый Bootstrap Community Kit предоставляет Variables `Theme Colors/Primary`, `Theme Colors/Secondary` и Text Styles `Body/Regular`, `Body/Bold`, `Body/Small`. Это имена активов Community Kit. Используй их в его черновом профиле. Связи с продуктовыми `--bs-*` требуют проверки по исходнику темы.

## Профиль «Здоровье»

В исходном файле Figma 54 Variables в `Health · Colors` (Light, Dark) и 30 в `Health · Dimensions` (Value). Имена цветов, размеров, радиусов и привязок смотри в [семантическом списке проекта](https://github.com/heteraff1-tech/design-harness/blob/main/rules/tokens-summary.md). Имена CSS, шкала отступов и размеры контролов описаны в [репозитории реализации](https://github.com/heteraff1-tech/SberZdorovie/blob/main/app/docs/design-system.md).

Подтверждённые Text Styles

- `Health/Display/Metric`
- `Health/Display/Metric-2`
- `Health/Heading/H1`
- `Health/Heading/H2`
- `Health/Heading/H3`
- `Health/Heading/H4`
- `Health/Text/Body`
- `Health/Text/Caption`
- `Health/Text/Footnote`
- `Health/Text/Label`
- `Health/Text/Small`
