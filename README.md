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

<!-- eventra-stable-026:start -->

## Eventra 0.2.6 · Stable

**[Скачать последнюю версию / Download latest](https://github.com/xook303/eventra-releases/releases/latest/download/Eventra-0.2.6-windows-x64-portable.zip)** · [Изменения / Release notes](https://github.com/xook303/eventra-releases/releases/tag/v0.2.6)


## Изменения после 0.2.5
- Исправлена раскладка файлового менеджера в Windows-сборке: ширина боковой панели, положение заголовков, отступы и оформление полос прокрутки.
- Исправлено переключение категорий медиатеки: пустые поля расположения больше не вызывают ошибку «Некорректное расположение медиатеки».
- Кнопка закрытия файлового менеджера использует штатное закрытие модуля без лишней пустой строки сверху.
- Восстановлены тонкие разделители под верхней панелью и рядом с левым меню. Разделитель между файловым менеджером и медиаплеером позволяет менять ширину панели мышью.
- Надпись «Добавить» в пустых медиапэдах выровнена по центру; номера всегда видны в углу. Исправлены границы панели рядом с медиаплеером и нижняя линия.
- При обновлении старые подписанные штатные `.evmod` заменяются новыми пакетами того же издателя. Предыдущие пакеты сохраняются в резервной копии. Неизвестные, изменённые и более новые пакеты не заменяются.

- Кнопка полного экрана и F11 используют весь текущий монитор. F11 передаётся в CORE из встроенных модулей, в том числе при фокусе в поле ввода.

## Как обновиться
Откройте **Настройки → Обновления → Проверить обновления** или **Справка → Проверить обновления**. Сохраните проект, остановите воспроизведение и закройте второй экран перед установкой. Версия 0.2.6 опубликована в стабильном канале.

Сборка рассчитана на переход со старых версий с поддержкой подписанных обновлений, включая 0.2.0 и 0.2.5. Старые папки модулей и пользовательские проекты сохраняются. Для сборок без рабочего обновлятора скачайте ZIP и распакуйте целиком в новую папку.

## English
- Fixed Windows File Manager layout, navigation width, headings, spacing and scrollbars.
- Fixed category navigation failing on empty location fields.
- Removed the extra empty header row and restored the native module close action.
- Restored the thin divider beside the left navigation.
- Bundled updates now replace older verified public modules from the same publisher, retaining backups. Unknown, modified and newer packages are preserved.

Use **Settings → Updates → Check for updates**. Save your project and stop playback before installing. Stable channel; Windows x64 Portable. Personal Music Lotto is not included.
<!-- eventra-stable-026:end -->

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
