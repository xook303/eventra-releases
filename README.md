<div align="center">

![Event Studia — управление мероприятием](assets/eventra-banner.svg)

<img src="assets/event-studia-logo.svg" width="96" alt="Event Studia logo" />

# Event Studia

**Музыка · Видео · Сцены · Второй экран**  
**Music · Video · Scenes · Audience display**

[Скачать веб-установщик Event Studia](https://github.com/xook303/eventra-releases/releases/latest/download/EventStudiaSetup.exe) · [Изменения / Release notes](https://github.com/xook303/eventra-releases/releases/tag/v0.2.7)

[Иконка для ярлыка](https://github.com/xook303/eventra-releases/releases/latest/download/EventStudia.ico)

[Новый NSIS-веб-установщик](https://github.com/xook303/eventra-releases/releases/latest/download/EventStudiaSetup.exe) — скачивает последнюю стабильную версию, устанавливает программу, создаёт ярлыки и стандартное удаление Windows.

В обычной сборке один файл запуска — **EventStudia.exe**. Для новой NSIS-установки используйте удаление через настройки Windows. Пользовательские проекты и внешние медиа сохраняются.

Windows x64 · NSIS / Portable · Stable

</div>

## Русский

Event Studia — программа для управления медиа на мероприятии. Ранее она называлась Eventra.

- Медиатека с аудио, видео, изображениями и презентациями.
- Медиаплеер, сцены и медиапэды для работы ведущего.
- Второй экран для гостей и таймер со звуковым сигналом.
- Проекты `.evnt` и подписанные модули `.evmod`.
- Стабильные подписанные обновления через GitHub.

### Установка
Скачайте **EventStudiaSetup.exe** и следуйте мастеру. Он загрузит последнюю стабильную версию и проверит подпись Ed25519 и SHA-256 пакета. Установка по умолчанию — Program Files. Подписи Windows Authenticode пока нет: возможно предупреждение «Неизвестный издатель». Удаление — через настройки Windows. Portable ZIP остаётся отдельным вариантом в релизе.

### Обновление со старых версий
Откройте **Настройки → Обновления → Проверить обновления**. Перед установкой сохраните проект, остановите воспроизведение и закройте второй экран.

В чистой сборке 0.2.7 **Eventra.exe отсутствует**. Для её дальнейшего обновления используйте веб-установщик: он сохраняет прежнюю папку как резервную копию и переносит неизвестные пользовательские файлы. Встроенный старый обновлятор ещё требует прежнее имя EXE. Технический архив `Eventra-VERSION-windows-x64-portable.zip` сохранён отдельно для обновления прежних установок. Форматы проектов и модулей сохраняются.

Публичная сборка не включает личное музыкальное лото. [Все версии](https://github.com/xook303/eventra-releases/releases).

## English

**Event Studia**, formerly Eventra, is a Windows Portable application for operating event media: a media library, player, scenes, Media Pads, an audience display and a timer.

Extract the full ZIP and run **EventStudia.exe**. Keep `runtime`, `ffmpeg` and `resources` beside the executable. Signed default modules install into `modules/` on first launch.

The normal 0.2.7 package contains **EventStudia.exe** and **Uninstall.exe**, without the duplicate Eventra.exe. Use the web installer for subsequent upgrades of this clean package; the embedded legacy updater still expects the old executable name. The web installer preserves the prior installation as a backup. Uninstall offers optional removal of the app profile, library, cache and modules while preserving external source media and projects. A separate signed legacy update ZIP remains available to older installations. Personal Music Lotto is not included.
