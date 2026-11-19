# Выбор компонента

## Bootstrap 5.3 · черновой прототип

Одна строка на роль. Figma — Community Kit из [index](../index.md). Варианты описывают UI; сверяй свойства экземпляра. Классы допускаются в черновике. Прод допуск требует продуктового источника.

| UI-задача | Figma / класс 5.3 | Допустимо | Запрет | Ключ Figma |
| --- | --- | --- | --- | --- |
| CTA | `button` / `.btn` | primary / secondary | icon-only | `3aad87adb4de2ef06be25cffb9cc28a7864c7268` |
| Закрытие | `close-button` / `.btn-close` | default / disabled | обычный CTA | `2381bb462d681d71f3ab425e0664d1f8a107171d` |
| Карточка | `card` / `.card` | body / header | метрика продукта | `98903e930d866faf4a280b5c424a4de36f7c8401` |
| Шторка | `offcanvas` / `.offcanvas-bottom` | bottom | подтверждение | `2691df266874651167cab38fc6fe59027a87c17e` |
| Диалог | `modal` / `.modal` | default | обычная навигация | `99b6f7840bcb342f195310a0c379f8a4031038e7` |
| Меню | `dropdown-trigger-with-menu` / `.dropdown` | actions | значение поля | `bf393423291e2ec4a7a0dab041bce846d5673201` |
| Уведомление | `toast` / `.toast` | dismissible | критичная ошибка | `c8d3e642390b4028d58635542d3c63fac6274a70` |
| Сообщение | `alert` / `.alert` | info / warning / danger | только цвет | `bd83a70884e71e6e543867241e235e1157aa0881` |
| Статус | `badge` / `.badge` | text | действие | `ef1c26a16d578bcc56c9d4abed9f90b4aff58346` |
| Ввод | `input` / `.form-control` | default / invalid | множественный выбор | `851a36eb979496a12c0b93de49bbeb99b373b6b7` |
| Число | `input-number` / `.form-control` | number | точное время | `2755eda6ae679eb6ae1843b90513112fac37f906` |
| Выбор | `select` / `.form-select` | single | действие меню | `03052880730500ab6786999031f1c30795ba2781` |
| Отметка | `checkbox-input` / `.form-check` | checked / unchecked | выбор одного | `833c89b98540fbb8de818561772960ba6bac49ed` |
| Один ответ | `radio-group` / `.form-check` | one selected | независимые ответы | `029bb627c175bc2bceaf965b340f753e440ac901` |
| Переключатель | `switch-input` / `.form-switch` | on / off | отправка формы | `7f814ef073e86a0c464fbcf72c38d8ea5833d720` |
| Список | `list-group` / `.list-group` | static / action | табличные данные | `cb5210fe24d8b1ab60f0c9eb590ad5042460141b` |
| Таблица | `table` / `.table` | default | сетка страницы | `1b767e21837fcd3f3f875cc568b5f213330bf8ab` |
| Раскрытие | `accordion` / `.accordion` | expanded / collapsed | главный CTA | `fe4644fde5bb20f522d4e718d246a8ae401dac3c` |
| Шаг прогресса | `progress` / `.progress` | determinate | нет оценки | `7ffe7eb1d4ca7fe6ca95f4cfe86ac2cf695c6744` |
| Ожидание | `spinner` / `.spinner-border` | indeterminate | известный процент | `74763cf846227e3e5d2efd53721ec6ae274ce84e` |

## SberZdorovie · при работе в его коде

Канон из [shared/ui](https://github.com/heteraff1-tech/SberZdorovie/tree/main/app/src/shared/ui).

| UI-задача | Обёртка | Допустимо | Запрет |
| --- | --- | --- | --- |
| CTA | `UiButton` | primary / secondary / quiet | `.btn` |
| Действие-иконка | `UiIconButton` | label обязателен | голый SVG |
| Шторка | `UiBottomSheet` | open / expanded | `.offcanvas`, `.modal` |
| Нижние разделы | `UiTabBar` | items / modelValue | `.nav-tabs` |
