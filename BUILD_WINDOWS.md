# Сборка приложения для Windows

## Скачать готовую сборку

1. Откройте репозиторий на GitHub.
2. Перейдите во вкладку **Actions**.
3. Выберите **Build Windows executable**.
4. Нажмите **Run workflow**.
5. Откройте завершённый запуск.
6. В разделе **Artifacts** скачайте
   `Order-Studio-DEMO-windows-x64`.
7. Распакуйте ZIP и запустите полученный `.exe`.

Windows может показать предупреждение SmartScreen для неподписанного файла — это стандартное предупреждение для неподписанных новых приложений.

## Структура репозитория

Должны находиться:

- `index.html`
- `main.js`
- `package.json`
- `manifest.webmanifest`
- `icon.svg`
- `sw.js` — необязателен для настольной сборки
- `.github/workflows/build-windows.yml`
- `.gitignore`
- `BUILD_WINDOWS.md`
