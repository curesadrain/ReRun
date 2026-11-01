# ReRun (New Game Templates)

Fast preset manager for saving and loading new game setups in **S.T.A.L.K.E.R. Anomaly / G.A.M.M.A.** without overwriting interface files.

[English](#english) • [Українська](#українська) • [Русский](#русский)

---

## English

### Overview

**ReRun** is a quality-of-life add-on for S.T.A.L.K.E.R. Anomaly and G.A.M.M.A. that allows you to instantly save and restore complete new game configurations.

Saves your chosen faction, character name, icon/portrait, spawn location, difficulty, economy presets, starting gear (loadout), and all gameplay modes (Story, Mystery of the Zone, Warfare, Survival, Ironman, Campfires, Routes, Timer, Soulslike, etc.).

### Key Features

- **Zero UI Overwrites (100% Conflict-Free):** The mod does not overwrite `ui_mm_faction_select.xml`, `ui_mm_faction_select_16.xml`, or `ui_mm_faction_select.script`. The button and manager dialog are injected non-destructively via DXML and script hooks, making it completely immune to UI mod conflicts and modpack updates.
- **Modern & Legible UI:** Redesigned dialog window featuring high-contrast text fields, enlarged crisp font (`letterica18`), and intuitive status cues.
- **Interactive FOMOD Installer:** Choose from 6 button positions on the character creation screen (`Top-Left`, `Top-Center`, `Top-Right`, `Bottom-Left`, `Bottom-Center`, `Bottom-Right`) to fit any custom UI layout.
- **Up to 24 Preset Slots:** All templates are saved to `appdata/axr_options.ltx` (under `[flx_new_game_templates]`), ensuring your presets persist across mod updates and reinstalls.

### Installation

1. Download the latest `ReRun_v1.1.0.zip` from [Releases](https://github.com/curesadrain/ReRun/releases).
2. Install via **Mod Organizer 2** (*Install a new mod from an archive*).
3. Select your preferred button placement in the FOMOD installer and click **Install**.
4. Enable the mod in your load order. Load order relative to UI mods does not matter.

> **Upgrading from v1.0.x:** Select **Replace** when installing in MO2 to ensure legacy overwritten `ui_mm_faction_select.*` files are cleanly removed.

### Credits & Acknowledgments

- **Sorano ([curesadrain](https://github.com/curesadrain))** — ReRun adaptation, DXML refactoring, FOMOD installer, UI enhancements.
- **flx** — original New Game Templates mod concept and logic.
- **Grok & the G.A.M.M.A. Team** — for the incredible modding platform.

---

## Українська

### Огляд

**ReRun** — це корисний аддон для S.T.A.L.K.E.R. Anomaly та G.A.M.M.A., який дозволяє швидко зберігати та завантажувати повні пресети нової гри.

Зберігає обране угруповання, ім'я персонажа, аватарку, точку появи, складність, економіку, стартове спорядження (loadout) та всі додаткові режими (Сюжет, Таємниця Зони, Війна угруповань, Виживання, Залізна людина, Багаття, Маршрути, Таймер, Soulslike тощо).

### Особливості

- **Повна сумісність з будь-якими UI-модами:** Аддон не перезаписує ванільні файли `ui_mm_faction_select.xml`, `ui_mm_faction_select_16.xml` та `ui_mm_faction_select.script`. Кнопка та вікно шаблонів додаються поверх інтерфейсу через DXML та скриптові хуки, що виключає конфлікти з оновленнями збірок.
- **Зручний та контрастний інтерфейс:** Оновлене вікно менеджера шаблонів з чіткими полями введення та списку, збільшеним шрифтом (`letterica18`) і кольоровою індикацією стану.
- **Гнучкий FOMOD-інсталятор:** Під час встановлення в Mod Organizer 2 можна обрати одне з 6 розташувань кнопки «Шаблони» на екрані (`Верх-Ліво`, `Верх-Центр`, `Верх-Право`, `Низ-Ліво`, `Низ-Центр`, `Низ-Право`).
- **До 24 слотів збереження:** Пресети надійно записуються в `appdata/axr_options.ltx` (секція `[flx_new_game_templates]`) і не зникають після оновлення або перевстановлення моду.

### Встановлення

1. Завантажте архів `ReRun_v1.1.0.zip` з розділу [Releases](https://github.com/curesadrain/ReRun/releases).
2. Встановіть через **Mod Organizer 2** (*Встановити новий мод з архіву*).
3. Оберіть зручне розташування кнопки у вікні FOMOD та натисніть **Install**.
4. Активуйте мод у списку. Порядок завантаження відносно UI-модів значення не має.

> **Оновлення з версій 1.0.x:** Під час встановлення в MO2 оберіть **Replace**, щоб видалити застарілі файли `ui_mm_faction_select.*`.

### Автори та подяки

- **Sorano ([curesadrain](https://github.com/curesadrain))** — адаптація ReRun, перехід на DXML, універсальний FOMOD-інсталятор, доопрацювання інтерфейсу.
- **flx** — оригінальна ідея та логіка моду New Game Templates.
- **Команда G.A.M.M.A. та Grok** — за чудову платформу та екосистему моддингу.

---

## Русский

### Описание

**ReRun** — удобный аддон для S.T.A.L.K.E.R. Anomaly и G.A.M.M.A., позволяющий сохранять и в один клик загружать готовые пресеты новой игры.

Сохраняет выбранную группировку, имя персонажа, портрет, точку спавна, сложность, экономику, стартовое снаряжение (loadout) и все игровые режимы (Сюжет, Тайна Зоны, Война группировок, Выживание, Железный человек, Костры, Маршруты, Таймер, Soulslike и др.).

### Особенности

- **Полная совместимость с любыми UI-модами:** Мод не перезаписывает оригинальные файлы `ui_mm_faction_select.xml`, `ui_mm_faction_select_16.xml` и `ui_mm_faction_select.script`. Кнопка и меню шаблонов безопасно подгружаются через DXML и скриптовый хук, полностью исключая конфликты с кастомными интерфейсами.
- **Обновлённый читаемый интерфейс:** Переработанное окно менеджера с контрастными полями ввода и списка, увеличенным шрифтом (`letterica18`) и цветовой индикацией статуса.
- **FOMOD-установщик:** При установке в Mod Organizer 2 можно выбрать одно из 6 положений кнопки «Шаблоны» на экране (`Верх-Лево`, `Верх-Центр`, `Верх-Право`, `Низ-Лево`, `Низ-Центр`, `Низ-Право`).
- **До 24 слотов шаблонов:** Пресеты сохраняются в `appdata/axr_options.ltx` (секция `[flx_new_game_templates]`) и остаются нетронутыми при обновлении сборки или переустановке мода.

### Установка

1. Скачайте архив `ReRun_v1.1.0.zip` со страницы [Releases](https://github.com/curesadrain/ReRun/releases).
2. Установите через **Mod Organizer 2** (*Install a new mod from an archive*).
3. Выберите удобное расположение кнопки «Шаблоны» в окне FOMOD и нажмите **Install**.
4. Активируйте мод в списке. Порядок загрузки относительно интерфейсных модов значения не имеет.

> **Обновление с версий 1.0.x:** Выберите **Replace** при установке в MO2, чтобы гарантированно удалить старые перезаписанные файлы `ui_mm_faction_select.*`.

### Авторы и благодарности

- **Sorano ([curesadrain](https://github.com/curesadrain))** — адаптация ReRun, реализация DXML, универсальный FOMOD-установщик, доработка UI.
- **flx** — оригинальная концепция и логика мода New Game Templates.
- **Grok и сообщество G.A.M.M.A.** — за отличную платформу и поддержку моддинга.
