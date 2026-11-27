# OpenChamber RU — сборки

Неофициальные сборки [OpenChamber](https://github.com/openchamber/openchamber)
с русским переводом.

Актуальный релиз: **v2.8.1** — Linux и Windows, см. раздел Releases.

## Что внутри

- Перевод 100% ключей интерфейса, вшит в исходники до сборки.
- Локальный патч: отключена клиентская выгрузка локаций OpenCode, из-за которой
  убивались серверные взаимодействия («Interaction cancelled because the
  location shut down»).
- **Linux:** пакет `openchamber-desktop-ru` для Arch/CachyOS.
  Установка: `sudo pacman -U openchamber-desktop-ru-2.8.1-1-x86_64.pkg.tar.zst`.
- **Windows:** NSIS-установщик x64. Не подписан, Windows покажет SmartScreen.
  exe собран без правки ресурсов, поэтому у него стандартные иконка и версия.

## Лицензия и изменения

Сборки — производная от OpenChamber (MIT, © Bohdan Triapitsyn). Полный текст
лицензии — в [LICENSE](LICENSE), список изменений — в [NOTICE.md](NOTICE.md).
Сборки не связаны с авторами OpenChamber.
