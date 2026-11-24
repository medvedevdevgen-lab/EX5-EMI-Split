# EX5 EMI Split

Разделение экрана для Geely EX5 / EX5 EM-i. В Split 1.68 русский и английский доступны в одном приложении. Переключатель **RU / EN** находится слева внизу. Интерфейс Split всегда тёмный.

**[Открыть веб-установщик](https://ex5-split.pages.dev/)** · **[Скачать Split 1.68](https://github.com/medvedevdevgen-lab/EX5-EMI-Split/releases/latest)**

## Установка и первый запуск

- **Через браузер.** Для USB используйте Chrome или Edge. Для Wi-Fi скачайте мост для Windows или Android с сайта либо из релиза. После перезагрузки ГУ установщик открывает Split, проверяет подключение службы и разрешение показывать приложение поверх других окон. Если служба не подключилась, он повторяет попытку и проверяет результат перед отметкой «Готово».
- **Из одного APK.** Установите `EX5-EMI-Split-1.68-One-APK.apk`. При первой установке откройте приложение и нажмите «Настроить Split». Для этой настройки нужен уже включённый локальный ADB с root на порту `7777`. Если Split уже настроен, установите APK поверх прежней версии, чтобы сохранить профили.

Для полной установки через браузер нужны включённый ADB и доступные `adb root` и `adb remount`. Устанавливайте, когда машина стоит в P. Целевая платформа — Android 11 на Geely EX5 / EX5 EM-i. Совместимость с прошивками до 2.2 пока не подтверждена.

Английский интерфейс и восстановление отключённой службы проверены на ГУ владельца. Сценарий проверки после перезагрузки прошёл автоматические тесты. Полный цикл новой версии с перезагрузкой на автомобиле ещё предстоит проверить.

## English

**[Web installer](https://ex5-split.pages.dev/)** · **[Download Split 1.68](https://github.com/medvedevdevgen-lab/EX5-EMI-Split/releases/latest)**

Split 1.68 uses one APK for Russian and English. Switch languages in the bottom-left corner. Split stays in dark mode independently of the head unit theme.

- **Web installation.** Use Chrome or Edge for USB, or the Windows or Android bridge for Wi-Fi. After the head unit restarts, the installer opens Split and verifies that its accessibility service is connected and overlay permission is granted. It retries the service once if needed and reports success after verification.
- **Standalone APK.** Open Split after installing it and select **Set up Split**. First-time setup requires local root ADB on port `7777`. Install over a configured copy of Split to keep your profiles.

The supported target is Geely EX5 / EX5 EM-i with Android 11 and ADB already enabled. Full web installation requires working `adb root` and `adb remount`. Park in P before installing. Compatibility with firmware earlier than 2.2 is unconfirmed.

The English UI and service recovery were checked on the owner's head unit. Automated tests covered post-restart verification. A full on-vehicle installation of this version including a restart remains unverified.

[Поддержать разработку / Support development](https://buymeacoffee.com/medvedevdep)
