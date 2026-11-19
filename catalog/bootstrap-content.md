# Контент и обратная связь

[Правила выбора и источник](bootstrap-mapping.md). `Custom` требует готовой обёртки целевого проекта.

| UI-задача | Figma | Код 5.3 | Варианты | Когда запрещён | Ключ Figma |
| --- | --- | --- | --- | --- | --- |
| Сообщение в потоке | `alert` | `.alert` | Type=info/warning/danger/success | сообщение только цветом | `bd83a70884e71e6e543867241e235e1157aa0881` |
| Метка статуса | `badge` | `.badge` | Type=normal/pill | действие | `ef1c26a16d578bcc56c9d4abed9f90b4aff58346` |
| Краткое уведомление | `toast` | `.toast` | Color=default/success | обязательная ошибка | `c8d3e642390b4028d58635542d3c63fac6274a70` |
| Известный прогресс | `progress` | `.progress` | Striped=false; Label=true | неизвестный процент | `7ffe7eb1d4ca7fe6ca95f4cfe86ac2cf695c6744` |
| Неизвестный прогресс | `spinner` | `.spinner-border` | Type=border | известный процент | `74763cf846227e3e5d2efd53721ec6ae274ce84e` |
| Загрузка структуры | `placeholders` | `.placeholder` | Type=multi-line/image + text | нет данных | `7c2c6c64ac7afb49d74a7a6cfecc700c99888dad` |
| Короткая подсказка | `tooltip` | `.tooltip` | Auto Width=true | обязательная инструкция | `8067644a1fc5625ca9d07a539fdfa3635b2e871a` |
| Дополнение к элементу | `popover` | `.popover` | Title=false/true | форма подтверждения | `2a5c7dac69f12249030f6bf55e38469c5106872b` |
| Нет данных | `empty` | Custom | Type=basic/simple | пока идёт загрузка | `3d234a55f5657705e466b06947052e570ec5da6d` |
| Карточка контента | `card` | `.card` | Type=vertical/horizontal | метрика «Здоровья» | `98903e930d866faf4a280b5c424a4de36f7c8401` |
| Листать медиа | `carousel` | `.carousel` | Dark=false/true | единственный доступ к действию | `2c1efacb021da6e83ca6c0a9dcf6024fda230c53` |
| Список | `list-group` | `.list-group` | Action=True/False | табличные данные | `cb5210fe24d8b1ab60f0c9eb590ad5042460141b` |
| Разделитель | `divider` | `hr` | Type=horizontal | заголовок | `37ff84a0e857118dfa72b3a1fedd470b8f11abfa` |
| Изображение | `image` | `.img-fluid` | Aspect ratio=1:1/16:9 | подпись рисунка | `4f50062fc898074bf3c9932c1b85541841a917b5` |
| Иллюстрация с подписью | `figure` | `.figure` | Text=start/end | галерея | `503bfddc93bcce000c9d3ecbdaf2dd03f71a38af` |
| Автор | `avatar` | Custom | Shape=circle; Type=text/image | статус | `f501691354c0e80ce0e248aa223bb1a1840aa7c0` |
| Несколько авторов | `avatar-group` | Custom | Items=2/3/4/5/6 | один автор | `181bb2047578d4b2a3f0679ba574f7827efb48c9` |
| Ветка комментариев | `comment/nested` | Custom | base | список уведомлений | `048d87a27730e87f567b6de8c2552314872c1a07` |
| Написать комментарий | `comment/comment-editor` | Custom | base | переписка | `79893258a6a62daf4fecdcce192849b9f2c1d899` |
| Группа тегов | `tag-group` | Custom | Count=1/2/3 | статус | `0f057fac0653838a9e7460d6492dd403333100e6` |
