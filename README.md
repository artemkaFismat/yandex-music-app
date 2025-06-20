# yandex-music-app
Простое десктопное приложение Яндекс Музыки на базе Electron для Linux.

## Установка и запуск

1. Установите зависимости:
   ```bash
   npm install
   ```
2. Запустите приложение:
   ```bash
   npm start
   ```

## Сборка AppImage

1. Установите зависимости (если не сделали этого ранее):
   ```bash
   npm install
   ```
2. Соберите AppImage:
   ```bash
   npm run dist
   ```
   Готовый файл будет в папке `dist/`.

## Зависимости
- [Electron](https://www.electronjs.org/)
- [electron-builder](https://www.electron.build/)

## Иконка
Поместите файл `icon.png` (512x512) в корень проекта для красивой иконки приложения. 
