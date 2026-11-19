# Токены и Text Styles

[Значения DTCG](tokens-dtcg.json) хранятся в `community.variables`, `community.textStyles`, `community.paintStyles` и `community.effectStyles`. Ищи точное имя Figma в метаданных. Стили с изображениями представлены ссылкой по ключу Figma.

| Группа | Доступные имена и правила |
| --- | --- |
| Семантические Variables | `Theme Colors/Primary`, `Theme Colors/Secondary` из коллекции `Color`. |
| Семантические Paint Styles | `Theme/Primary`, `Theme/Secondary`, `Theme/Success`, `Theme/Danger`, `Theme/Warning`, `Theme/Info`, `Body Text/Body Color`. |
| Фокус и тени | `Focus Ring/Primary`, `Focus Ring/Secondary`, `Shadows/shadow`, `Shadows/shadow-sm`, `Shadows/shadow-lg`, `Shadows/shadow-inset`. |
| CSS-переопределения | У обеих Variables поле CSS Code Syntax пустое. Используй `--bs-*` из темы, подключённой в целевом коде. Продуктовые переопределения ждут сверки с этой темой. |
| Радиусы, отступы, тап-зоны | Именованных Variables в этом файле нет. Для макета сохраняй размеры из выбранного варианта. Для кода бери шкалу целевого проекта. |

## Text Styles Bootstrap Community Kit

- `Body/Regular`, `Body/Bold`, `Body/Light`, `Body/Italic`, `Body/Underline`, `Body/Strike`, `Body/Small`, `Body/Code`, `Body/Lead`, `Body/Blockquote`
- `Heading/H1`–`Heading/H6`, `Display/H1`–`Display/H6`
- `Components/Badge/H1`–`Components/Badge/H6`
- `Components/Floating labels/Input Text`, `Components/Floating labels/Label Text Focused`
- `Components/Dropdowns/Dropdown Header`, `Components/Modal/Title`, `Components/Offcanvas/Title`
- `Components/Progress/Label`, `Components/Toast/Header Title`, `Components/Toast/Header Time`

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
