# Специальный ввод и загрузка

[Правила выбора и источник](bootstrap-mapping.md). `Custom` требует готовой обёртки целевого проекта.

| UI-задача | Figma | Код 5.3 | Варианты | Когда запрещён | Ключ Figma |
| --- | --- | --- | --- | --- | --- |
| Число ползунком | `range` | `.form-range` | From - To=false | точный ввод | `28277defee4a8ba819ccbcafcb62b43ed7a84693` |
| Дата | `date-picker` | Custom | Ranged=false/true | время суток | `a342304e4d658b24c8440a9be78f7c351c726a39` |
| Время | `time-picker` | Custom | Ranged=false/true | дата | `e20c9171b3123ae8aa4a89ccc66b4d227f5f6725` |
| Выбрать цвет | `color-picker` | Custom | State=normal/focused | статус | `90afdd43c9e4785fa238f330724792a9e7109b22` |
| Оценка звёздами | `rate` | Custom | Items=quintuple | прогресс | `6a5f52405e05bb97d32ee8299f6db2886f1136d1` |
| Выбрать файл | `file-input` | `.form-control` | Validation=normal/invalid | зона drop | `3df9a0dbfa9d11590eec93fc12e1f545c6471ab8` |
| Перетащить файл | `upload/dragger` | Custom | base | единственный путь загрузки | `aa8f03d558aebf171e34880207fb39c4d76f185f` |
| Очередь изображений | `upload-list/images` | Custom | Direction=horizontal/vertical | список документов | `85a3b6088a59bbcad5fac7fa6dc8df9ef558745f` |
| Очередь файлов | `components/upload-list/files` | Custom | Items=1/2/3 | галерея | `cf52f44b7188165bc4c0c8404faefed761c5ea44` |
| Перенести между списками | `transfer` | Custom | base | одно поле выбора | `eee65e128989a9e1ff7fbe6fa7089650b7a76121` |
