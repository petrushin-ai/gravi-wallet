# gravi-wallet

Liittle hack for pool.gravitsapa.space

Небольшой плагин-лайфхак для gravitsapa pool

- Автосохранение кошелька в local-storage
- Предложение перейти в кошелек, если вы входите на страницу статистики, а кошелек у вас уже сохранен
- Ссылки в меню навигации на страница Payouts и Wallet так же подправлены, чтобы не вводить повторно кошелек
- Есть ещё одна недокументированная фича, за которую наверное наругает @sergeybrava но тут, уж, как говорится, кто знает - тот поймёт

Руководство по установке плагина:

0. Скачать актуальную версию плагина  https://github.com/petrushin-a/gravi-wallet/raw/main/build/gravi-wal-plugin_v0.0.1.zip
1. Распаковать в любую локальную папку
2. В Chrome зайти в меню настроек и выбрать 'Дополнительные инструменты' - 'Расширения'
3. Включить режим разработчика
4. Нажать 'Загрузить распакованное расширение' и указать путь до папки с распакованными файлами

# Changelog


### V. 0.0.2
- на странице "Founds" блоки, найденные тем кошельком, который сохранен в local storage - помечены красным цветом текста

### V. 0.0.3
- небольшой фикс, теперь если локальный адрес кошелька присутствует - заменяю ссылки на wallet и payouts всегда

### V. 0.0.5
- Добавлено уведомление о новом блоке (разрешите уведомления chrome)
  https://support.google.com/chrome/answer/3220216?hl=ru&co=GENIE.Platform%3DDesktop

- Добавлен калькулятор доходности

Всем дохода! enjoy ;)
