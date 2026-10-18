<div align="center">

![EVENTRA — Event control, in one place](assets/eventra-banner.svg)

**Музыка · Видео · Сцены · Второй экран**  
**Music · Video · Scenes · Audience display**

[![Windows x64](https://img.shields.io/badge/Windows-x64-101923?style=flat-square&logo=windows&logoColor=white)](#ru)
[![Portable](https://img.shields.io/badge/Distribution-Portable-101923?style=flat-square)](#installation)
[![Stable](https://img.shields.io/badge/Status-Stable-58d6ad?style=flat-square)](#status)

[Русский](#ru) · [English](#en) · [Релизы / Releases](https://github.com/xook303/eventra-releases/releases)

**[Скачать / Download latest](https://github.com/xook303/eventra-releases/releases/latest)**

</div>

---

<!-- eventra-stable-025:start -->

## Eventra 0.2.5 · Stable

**[Скачать последнюю версию / Download latest](https://github.com/xook303/eventra-releases/releases/latest/download/Eventra-0.2.5-windows-x64-portable.zip)** · [Изменения / Release notes](https://github.com/xook303/eventra-releases/releases/tag/v0.2.5)


## Русский

Публичная Windows x64 Portable-сборка без музыкального лото.

### Что изменилось после 0.2.0
- Модули поставляются подписанными контейнерами `.evmod`. При первом запуске проверенные штатные пакеты размещаются в `modules/`; старые папки сохраняются.
- Работа с проектами `.evnt`: новый проект, открытие, сохранение, «Сохранить как» и последние проекты. Название и несохранённые изменения отображаются в меню «Файл».
- Быстрый старт можно показывать при запуске и включать в настройках.
- Верхняя панель собрана в группы с одинаковыми разделителями. Полноэкранная кнопка находится рядом с управлением окном; активный второй экран выделяется зелёным.
- Единая кнопка проверки готовности находится внизу слева.
- Обновлён таймер: ввод ММ:СС, быстрые длительности, прямой и обратный отсчёт, вывод гостям на второй экран и встроенный сигнал окончания. Мини-таймер и большой модуль используют один отсчёт. Сигнал можно выключить; занятый канал B не прерывается.
- Упрощены карточки медиапэдов, размеры кнопок плеера и разделители панелей.
- В настройках обновлений оставлен только стабильный канал. Новая версия отмечается красной точкой в «Справка».

### Обновление с 0.2.0
В настройках программы откройте «Обновления» и нажмите «Проверить обновления». Перед установкой сохраните проект, остановите воспроизведение и закройте второй экран. Следуйте командам установленной версии. Для ручной установки распакуйте архив целиком в новую папку.

Штатный обновлятор сохраняет `modules/` и данные пользователя. Версия 0.2.5 устанавливает только отсутствующие штатные `.evmod`; существующие контейнеры и личные пакеты не заменяет. В публичной сборке личные модули не загружаются. Сохраните отдельную копию проекта перед переходом.

Сборка и программные проверки не заменяют проверку звука, устройств и второго монитора на площадке. Проверка на чистой Windows VM не выполнялась. Новый логотип ещё не выбран: сохранён текущий знак.

## English

Public Windows x64 Portable release. Music Lotto is not included.

### Changes since 0.2.0
- Signed `.evmod` module containers. Verified defaults are installed into `modules/` on first launch; legacy folders are retained.
- `.evnt` project creation, opening, Save, Save As and recent projects. The File menu displays the project name and unsaved changes.
- Optional Quick Start on launch, configurable in Settings.
- Grouped title bar with consistent dividers, fullscreen beside window controls and a green active audience-display button.
- A single readiness-check button in the lower left corner.
- Revised timer: MM:SS input, duration shortcuts, count up/down, audience display and an optional built-in completion signal. The mini timer shares the same clock. An occupied channel B is never interrupted by the signal.
- Refined Media Pads, player controls and panel resize grips.
- Stable updates only, with a red update indicator in Help.

### Updating from 0.2.0
Open Settings → Updates → Check for updates. Save your project, stop playback and close the audience display before installing. Follow the installed version's prompts. For manual installation, extract the complete archive into a new folder.

The updater preserves modules and user data. Version 0.2.5 installs missing default `.evmod` files only; existing containers and personal packages are not overwritten. The public edition does not load private modules. Keep a separate project backup.

Build checks do not replace venue testing of audio devices and physical displays. A clean Windows VM was not tested. The current logo is retained pending selection of a new design.
<!-- eventra-stable-025:end -->

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

Доступна публичная версия **0.2.0** для Windows x64. Скачайте полный Portable ZIP по ссылке выше и распакуйте в новую папку. Автоматический переход со старых сборок на модульную поставку ещё не готов.

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

Public version **0.2.0** for Windows x64 is available. Download the complete Portable ZIP and extract it into a new folder. Automatic migration from older builds to the modular distribution is not ready.

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
