# Greencharts v17

Полная версия статической библиотеки префлоп-диапазонов. Сохранены интерфейс, 35 ситуаций, матрицы, переключатель ВКЛ/ВЫКЛ и адаптивное уменьшение матрицы по высоте окна.

## Фразы

Общий пул содержит 211 уникальных фраз. По просьбе пользователя удалены реплики про ICM, Омаху/PLO, Spin&Go, DoN, СНГ, сателлиты и пуш-фолд по таблицам Нэша. Покерные диапазоны и интерфейс не изменены. Происхождение предоставленных фраз отдельно не верифицировалось. Точные дубли не добавляются повторно.

Фразы выбираются локально и перемешиваются без повторения до исчерпания цикла. При выключенном переключателе текст не выбирается и не отображается.

## Состав

- `index.html` — разметка и подключения файлов
- `style.css` — оформление и адаптивная матрица
- `app.js` — интерактивность ситуаций, матрица и переключатель текста
- `charts.js` — сохранённые префлоп-диапазоны
- `phrases.js` — общий пул реплик

## Обновление на GitHub Pages

Загрузите все шесть файлов в корень репозитория, заменив файлы с такими же именами, и выполните Commit changes.


## v17 update
- Added 100 new phrases supplied by the user.
- Added 32 short excerpts from researched PokerStrategy/GipsyTeam pages; source links are documented in the accompanying response, while author attributions and quote marks are omitted from the interface.
- General phrase pool: 343 unique entries.
- No chart ranges or situation buttons were modified. The phrase list itself is a mix of user-provided material and short researched forum excerpts; not every user-provided slogan is independently verified as historical quotation.


## v17 update
- Restored the per-situation phrase pools: 700 spot-linked comments across 35 clickable situations. They appear when the matching situation is selected.
- Preserved 343 general phrases, including the previously added user-supplied bankroll/preflop advice list and researched excerpts.
- Cleaned visible phrase text: removed quotation glyphs and list-number prefixes. Hand names and meaningful numbers such as 3-bet, 7-2, stack sizes and percentages are retained.
- Kept the existing chart data and matrix rendering unchanged.
- Bumped cache query parameters to v17 for app.js, charts.js and phrases.js.
