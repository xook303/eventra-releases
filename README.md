<div align="center">

![EVENTRA — Event control, in one place](assets/eventra-banner.svg)

**Музыка · Видео · Сцены · Второй экран**  
**Music · Video · Scenes · Audience display**

[![Windows x64](https://img.shields.io/badge/Windows-x64-101923?style=flat-square&logo=windows&logoColor=white)](#ru)
[![Portable](https://img.shields.io/badge/Distribution-Portable-101923?style=flat-square)](#installation)
[![Alpha](https://img.shields.io/badge/Status-Alpha-d9a441?style=flat-square)](#status)

[Русский](#ru) · [English](#en) · [Релизы / Releases](https://github.com/xook303/eventra-releases/releases)

**[Скачать / Download latest](https://github.com/xook303/eventra-releases/releases/latest)**

</div>

---

<!-- eventra-preview-020:start -->

## Eventra 0.2.0 · Preview

**[Скачать 0.2.0 / Download 0.2.0](https://github.com/xook303/eventra-releases/releases/download/v0.2.0/Eventra-0.2.0-windows-x64-portable.zip)** · [Release notes](https://github.com/xook303/eventra-releases/releases/tag/v0.2.0)

### Что изменилось после 0.1.1

- **Модули в отдельных папках.** Файловый менеджер, медиаплеер, сцены, медиапэды и таймер поставляются подписанными пакетами в `modules/` и работают внутри общего окна Eventra.
- **Обновлённая верхняя панель.** Меню и управление окном собраны в общей шапке с разделителями. Убрана дублирующая кнопка настроек слева.
- **Аккуратнее рабочее пространство.** Выровнены панели, нижние полосы и кнопки закрытия. Команды заставки и Blackout объединены с нижней панелью действий.
- **Файловый менеджер.** Единый размер карточек папок, меньше повторяющихся названий. При создании папки название сразу выделяется, Enter подтверждает ввод.
- **Медиапэды.** Русское название, переключатели «Общие / Сцена», обновлённые карточки и цветовые полосы.
- **Медиаплеер.** Компактная команда «Создать плейлист» по центру пустой панели.
- **Первый запуск.** Приветствие с выбором языка и рабочего пространства; его можно открыть повторно из справки.
- **Русский и английский.** Общие словари перевода для интерфейса CORE и модулей. Редкие технические сообщения ещё требуют редакторской проверки.

Публичная сборка **без музыкального лото**. Это тестовый выпуск: распакуйте архив целиком **в новую папку**. Автоматический переход с 0.1.1 на модульную поставку пока не готов; стабильный канал остаётся на 0.1.1.

Проверены сборка, подписи пяти модулей, запуск со встроенным WebView2 и штатное закрытие. Проверка на чистой Windows и полный сценарий живого мероприятия ещё не завершены.

### Changes since 0.1.1

- **Separate module folders.** The file manager, media player, scenes, Media Pads and timer ship as signed packages in `modules/` and run inside the Eventra window.
- **Updated title bar.** Menus and window controls share a single header with separators. Removed the duplicate Settings button from the left sidebar.
- **Refined workspace.** Aligned panels, bottom bars and close controls. Event splash and Blackout controls share the bottom action bar.
- **File manager.** Consistent folder-card sizes and fewer repeated labels. New-folder text is selected immediately; Enter confirms the name.
- **Media Pads.** Revised cards, color strips and Global / Scene tabs, with a localized Russian title.
- **Media player.** A compact Create playlist action is centered in the empty panel.
- **First launch.** A welcome flow offers language and workspace selection and can be reopened from Help.
- **Russian and English.** Shared translation dictionaries cover CORE and module interfaces. Some technical messages still need editorial review.

The public build **excludes Music Lotto**. This is a preview: extract the complete archive **into a new folder**. Automatic migration from 0.1.1 is not ready; the stable channel remains on 0.1.1.

Build, five module signatures, bundled WebView2 startup and normal exit were checked. Clean Windows and full live-event validation are not complete.

<!-- eventra-preview-020:end -->

---

<a id="ru"></a>

## Eventra — управление мероприятием

Настольное приложение для подготовки и проведения мероприятий. Соберите медиа, подготовьте сцены и управляйте показом из одного рабочего пространства.

| Рабочая область | Для чего |
| :--- | :--- |
| **Медиатека и плеер** | Файлы, коллекции, плейлисты и воспроизведение |
| **Сцены** | Последовательность действий и запуск следующего шага через GO |
| **Media Pads** | Быстрый запуск аудио и видео из общих банков и банков сцен |
| **Второй экран** | Видео, изображения, PDF и заставка для зрителей |
| **Модули** | Таймер и вспомогательные инструменты |

### Скачать и запустить

**[Скачать последнюю версию для Windows →](https://github.com/xook303/eventra-releases/releases/latest)**

Ссылка автоматически открывает последний опубликованный стабильный релиз. ZIP находится в разделе **Assets**. При выходе новой версии адрес ссылки останется тем же.

Доступна публичная версия **0.1.1** для Windows x64. Скачайте полный Portable ZIP по ссылке выше. Если у вас уже установлена 0.1.1, распакуйте новый пакет в отдельную папку: замена пакета с тем же номером не запускает автоматическое обновление.

1. Скачайте `Eventra-VERSION-windows-x64-portable.zip` из раздела **Assets** нужного релиза.
2. Распакуйте архив целиком в отдельную папку.
3. Запустите `Eventra.exe` из распакованной папки.

Не переносите EXE отдельно: рядом должны остаться библиотеки FFmpeg, среда WebView2 и остальные файлы пакета. Проекты и свои медиа храните вне папки программы.

### Что нового в 0.1.1

- Настроен источник обновлений через GitHub Releases.
- Добавлены доверенный публичный ключ и проверка Ed25519-подписи пакета.
- В «Справке» появилась команда **«Проверить обновления»**.
- В настройках обновлений доступны версия, каналы Stable/Beta и прогресс загрузки.
- При установке сохраняются резервная версия и журнал операции.
- Исправлено восстановление банка пэдов по умолчанию.

### Как обновлять

Откройте **«Справка → Проверить обновления»**, скачайте доступную версию и дождитесь проверки пакета. Сохраните проект, остановите медиа, завершите активный сеанс и закройте второй экран. Подтвердите **«Установить при выходе»**, затем закройте Eventra обычным способом.

Установка выполняется после выхода. Программа не закрывается автоматически во время мероприятия. Сборки без настроенного источника обновлений необходимо сначала заменить вручную на полный настроенный пакет.

<a id="status"></a>

### Статус и обратная связь

**Alpha для тестирования на Windows x64.** Проверка на чистой Windows 10/11 и в полном живом мероприятии ещё не завершена. Перед обновлением сохраняйте отдельную копию проекта.

При сообщении об ошибке укажите версию Eventra, версию Windows, шаги воспроизведения и точный текст ошибки. Не публикуйте личные проекты, медиа и конфиденциальные журналы.

Этот репозиторий содержит дистрибутивы и информацию об обновлениях. Исходный код здесь не публикуется. Сведения о сторонних компонентах и их лицензиях находятся в пакете.

---

<a id="en"></a>

## Eventra — event control, in one place

A desktop application for preparing and running events. Organize media, prepare scenes, and control your audience display from one workspace.

| Workspace | Purpose |
| :--- | :--- |
| **Media library & player** | Files, collections, playlists, and playback |
| **Scenes** | Action sequences with GO to trigger the next step |
| **Media Pads** | Quick audio and video cues from shared and scene banks |
| **Audience display** | Video, images, PDF, and an event splash screen |
| **Modules** | A timer and supporting tools |

<a id="installation"></a>

### Download and run

**[Download the latest Windows version →](https://github.com/xook303/eventra-releases/releases/latest)**

This link automatically opens the latest published stable release. Download the ZIP from **Assets**. The link stays the same when a new version is released.

Public version **0.1.1** for Windows x64 is available. Download the complete Portable ZIP using the link above. If 0.1.1 is already installed, extract the new package into a separate folder: a same-version package replacement does not trigger an automatic update.

1. Download `Eventra-VERSION-windows-x64-portable.zip` from the release **Assets**.
2. Extract the entire archive into a separate folder.
3. Run `Eventra.exe` from that folder.

Keep FFmpeg libraries, WebView2, and all other package files beside the application. Store your projects and media outside the application folder.

### New in 0.1.1

- A GitHub Releases update source is configured.
- A trusted public key verifies Ed25519-signed update packages.
- **Check for updates** is available in the Help menu.
- Update settings show the version, Stable/Beta channels, and download progress.
- Installation keeps a backup of the previous version and a transaction log.
- Default media-pad bank restoration is fixed.

### Updating

Open **Help → Check for updates**, download the available version, and wait for package verification. Save your project, stop playback, end the active session, and close the audience display. Confirm **Install on exit**, then close Eventra normally.

Installation runs after exit. Eventra does not automatically close during an event. Older builds without an update source require an initial manual replacement with the complete configured package.

### Status and feedback

**Windows x64 Alpha for testing.** Clean Windows 10/11 and full live-event validation are not yet complete. Keep a separate project backup before updating.

When reporting a problem, include the Eventra version, Windows version, reproduction steps, and the exact error message. Do not publish personal projects, media, or confidential logs.

This repository hosts distributions and update information. Source code is not published here. Third-party component and license information is included in the package.

---

<div align="center">

**EVENTRA** · Подготовьте. Запустите. Управляйте.  
Prepare. Run. Control.

</div>
