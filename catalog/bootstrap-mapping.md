# Выбор компонента

Источник — [Bootstrap Community Kit](https://www.figma.com/design/z0mUSQgmrlvdYjKAixYr41/Bootstrap-5-Design-System---UI-Kit--Community-?node-id=0-1). Строка задаёт канон Figma; CSS-класс разрешён для роли в Bootstrap 5.3. `Custom` требует готовой обёртки для кода. Варианты перечислены по именам свойств Figma; используй существующую комбинацию.

- [Действия и поля](bootstrap-controls.md)
- [Специальный ввод и загрузка](bootstrap-forms.md)
- [Контент и обратная связь](bootstrap-content.md)
- [Профиль «Здоровье»](health.md)

## Навигация и оверлеи

| UI-задача | Figma | Код 5.3 | Варианты | Когда запрещён | Ключ Figma |
| --- | --- | --- | --- | --- | --- |
| Путь до страницы | `breadcrumb` | `.breadcrumb` | Divider="/" | шаги формы | `881dfad8d0277b5f728a09700d1c7de97007a301` |
| Шапка сайта | `navbar/responsive` | `.navbar` | Expanded=false/true | нижняя навигация | `4219856f8d47e531971ca7ef135e48918161bb6e` |
| Меню разделов | `navigation` | `.nav` | Mode=horizontal/vertical | панели одной страницы | `5b39af0bd728cfcc906c05f41f1581f8208cafdc` |
| Панели страницы | `tabs/top` | `.nav-tabs` | Centered=false/true | переход между разделами | `d0d262024b6329501d02f0eb999d5a8d4f16acab` |
| Страницы выдачи | `pagination` | `.pagination` | Size=small/medium/large | табы | `fc4a7923f63c2f3b16c28fd151515526655200db` |
| Контекстное меню | `dropdown-trigger-with-menu` | `.dropdown` | Opened=false/true | выбор значения | `bf393423291e2ec4a7a0dab041bce846d5673201` |
| Несколько секций | `accordion` | `.accordion` | Flush=false/true | главное действие | `fe4644fde5bb20f522d4e718d246a8ae401dac3c` |
| Одна раскрываемая область | `collapse` | `.collapse` | Open Element=1st/close-all | группа секций | `c74542cbb039c167bd7eee2d0f5d5f90da99ac25` |
| Шторка | `offcanvas` | `.offcanvas` | Position=bottom/left/right | блокирующее подтверждение | `2691df266874651167cab38fc6fe59027a87c17e` |
| Подтверждение | `modal` | `.modal` | Type=text; Size=default | обычная навигация | `99b6f7840bcb342f195310a0c379f8a4031038e7` |

Для HTML-таблицы разрешён класс `.table`. Figma: бери готовую таблицу целевого продукта; служебные строки и ячейки исключены.

## SberZdorovie · при работе в его коде

Канон из [shared/ui](https://github.com/heteraff1-tech/SberZdorovie/tree/main/app/src/shared/ui).

| UI-задача | Обёртка | Допустимо | Запрет |
| --- | --- | --- | --- |
| CTA | `UiButton` | primary / secondary / quiet | `.btn` |
| Действие-иконка | `UiIconButton` | label обязателен | голый SVG |
| Шторка | `UiBottomSheet` | open / expanded | `.offcanvas`, `.modal` |
| Нижние разделы | `UiTabBar` | items / modelValue | `.nav-tabs` |
