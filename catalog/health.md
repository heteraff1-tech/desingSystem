# Профиль «Здоровье»

Канон Figma с [опубликованной страницы Health · Design System](https://www.figma.com/design/u0EdPHQOmvdQuc7158uN5C/Untitled?node-id=237-1893). К каждому имени добавляй префикс `Health/`. Для веб-реализации сверяй [обёртки SberZdorovie](bootstrap-mapping.md#sberzdorovie--при-работе-в-его-коде).

| UI-задача | Figma | Разрешённые значения | Запрет для роли | Опубликованный ключ |
| --- | --- | --- | --- | --- |
| Открыть отчёт | `Control/Report row` | — | строка метрики | `d9a6398b3f95eff9cc9f5978dd0fe9ba73e0b0cd` |
| Ввести сообщение | `Control/Message composer` | — | форма замера | `d3e66ec1242826ac57d0edd4617a5ff2cfa364df` |
| Действие с текстом | `Button` | Type: Primary, Secondary, Quiet × State: Default, Pressed, Disabled | действие без текста | `98a711718ae787df31ccb9c3c2fa0aca687d72c9` |
| Действие с иконкой | `Icon button` | State: Default, Pressed, Disabled | CTA с подписью | `d76d3bb7010115aeafbcf1a49853c620f52435d0` |
| Период истории | `Control/Period selector` | Period: Day, Week, Month, Year | раздел приложения | `bbea9b91459b9241bb67b944910eb8414fe31edc` |
| Карточка давления | `Widget/Blood pressure` | — | карточка другой метрики | `e2226287d81093578fe80b7f855279c3e74c7b1c` |
| Пульс на панели | `Widget/Pulse summary` | — | значение на экране пульса | `a954779c29892e3f0481c54c965d58a898e3796a` |
| Карточка глюкозы | `Widget/Glucose` | — | карточка другой метрики | `5f0626fe3f21627635bd65fa54c4fd88c078cf6c` |
| Карточка веса | `Widget/Weight` | — | карточка другой метрики | `36056ee0bc9bb0ec5c48d82c850a8932db42e151` |
| История пульса | `Widget/Pulse history` | — | текущий замер | `850658499c4b8d271971cfddfffcc34d59596daa` |
| Рекомендация ИИ | `Widget/AI insight` | — | сырые замеры | `c9d5a8cc1380055db35544fea9c0703bb1afa7fb` |
| Пульс на экране замера | `Widget/Pulse hero` | — | компактная карточка | `8968581e57aa7de36b0d82dc4b980595443676a6` |
| Нижние разделы | `Navigation/Tab bar` | Theme: Light, Dark | переключение периода | `a7bee679861d3f60e479487443ffd1e0f5682f68` |
