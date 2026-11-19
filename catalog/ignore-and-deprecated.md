# Исключения каталога

| Правило | Действие |
| --- | --- |
| Сегмент имени начинается с `.` или `_` | Исключить из публичного каталога. |
| Сегмент `Base` или `Internal` без учёта регистра | Исключить путь и дочерние варианты. |
| Иконки и пиктограммы | Переиспользовать только как зависимости компонентов. |
| Вариант в Component Set | Выбирать через параметры родительского набора. |
| Документация, примеры, заглушки конструктора, внутренние слои `components/` | Не вставлять отдельно. Разрешены публичные комбинации из каталога. |
| Архивный статус | Запретить новую вставку и записать замену. |

## Исключения из исходного Bootstrap Community Kit

| Служебная запись или дубль | Канон |
| --- | --- |
| `comment/nested(backup)` | `comment/nested` |
| `button-list` для группы кнопок | `button-group` |
| `navbar/default` для шапки | `navbar/responsive` |
| `tabs/left`, `components/tabs-top`, `components/tabs-left` для панелей | `tabs/top` |
| `dropdown-menu`, `dropdown-trigger`, `components/dropdown-menu-item*` отдельно | `dropdown-trigger-with-menu` |
| `_change-value`, `_input-number-base`, `_input-number-handler` | `input-number` |
| `components/checkbox`, `components/radio`, `_switch-nob` | `checkbox-input`, `radio-group`, `switch-input` по назначению |
| `components/accordion-item`, `components/list-group-item` | `accordion`, `list-group` |
| `date-picker-dropdown`, `time-picker-dropdown` | `date-picker`, `time-picker` |
| `placeholders-line` | `placeholders` |
| `table/row-base`, `table/col-base`, `components/table-*` отдельно | Готовая таблица продукта |
| `layout-slots/base`, `_grid_container`, `spacer` отдельно | Сетка и отступы целевого проекта |

В «Здоровье» исключай `Health/Icons/*` и самостоятельную вставку `Health/Control/Sheet pull handle`. Ручка используется внутри продуктовой панели.
