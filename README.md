# EX5 EMI Split

Ветка Split проекта Geely EX5 EM-i: версии приложения RU/EN и инструменты установки для сообщества.

**[Открыть веб-установщик](https://ex5-split.pages.dev/)** · **[Скачать последнюю версию](https://github.com/medvedevdevgen-lab/EX5-EMI-Split/releases/latest)**

## Какой файл выбрать

| Файл | Назначение |
| --- | --- |
| `EX5-EMI-Split-Update-1.63.apk` | Обновление настроенного Split, русский язык |
| `EX5-EMI-Split-Update-1.63-EN.apk` | Обновление настроенного Split, English |
| `EX5-EMI-Split-Full-Auto-1.63.zip` | Полная установка с Windows, русский язык |
| `EX5-EMI-Split-Full-Auto-1.63-EN.zip` | Полная установка с Windows, English |
| `EX5-Split-Bridge-Windows.zip` | Локальный веб-установщик и Wi-Fi ADB для Windows |
| `EX5-Split-Bridge-Android.zip` | Локальный веб-установщик для Android/Termux |
| `EX5-Split-Cloudflare-Pages.zip` | Готовый сайт для развёртывания на статическом хостинге |
| `SHA256SUMS.txt` | Контрольные суммы файлов релиза |

APK обновления устанавливается поверх прежней версии с сохранением данных. Для первой установки используйте полный комплект или полную установку через веб. Инструкции находятся внутри архивов.

## Возможности 1.63

- Профили пар приложений, удаление профилей и ярлык возврата с любой стороны экрана.
- Крупные настройки в стилистике головного устройства.
- Автозапуск выбранного профиля после загрузки Android.
- Выбор любого цвета и толщины разделителя.
- RU/EN; в английской версии QR-код Buy Me a Coffee.
- Веб-установщик RU/EN: USB через Chrome/Edge, Wi-Fi через локальный мост.

## Совместимость и проверка

Geely EX5 / EX5 EM-i, Android 11, уже включённый ADB. Для полной установки нужны доступные `adb root` и `adb remount`. Машина должна стоять в режиме P. Сайт сам не включает закрытый ADB.

Приложение 1.63 проверялось на ГУ владельца. Установка через веб-версию на реальном ГУ ещё не проверена. Сбой с радио и узкой полосой карты из присланного видео в этой версии не исправлялся.

## English

**[Web installer](https://ex5-split.pages.dev/)** · **[Latest release](https://github.com/medvedevdevgen-lab/EX5-EMI-Split/releases/latest)**

Choose an Update APK for an existing Split setup, or a Full-Auto ZIP for a full Windows installation. RU and EN use the same app package; updating preserves your profiles. The website selects the matching APK when you switch languages.

Requires Geely EX5 / EX5 EM-i, Android 11 and ADB already enabled. Full installation requires working root/remount. Install only while parked in P. Real head-unit installation through the web installer has not yet been tested.

[Поддержать разработку / Support development](https://buymeacoffee.com/medvedevdep)
