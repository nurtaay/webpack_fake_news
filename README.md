Шаг 1. Создать проект

mkdir my-webpack-app
cd my-webpack-app
npm init -y

Объяснение:

mkdir my-webpack-app: Создает новый каталог для проекта.
cd my-webpack-app: вход в вновь созданный каталог.
npm init -y: Инициализирует новый проект npm с настройками по умолчанию.


Шаг 2. Установите Webpack и зависимости
npm install webpack webpack-cli --save-dev

Объяснение:

npm install: Устанавливает зависимости для проекта.
webpack webpack-cli --save-dev: Устанавливает webpack и webpack-cli в качестве зависимостей разработки.

Шаг 3. Настройте веб-пакет
Создайте webpack.config.js файл в корневом каталоге вашего проекта:

Шаг 4. Настройте веб-пакет
touch webpack.config.js

Объяснение:

touch webpack.config.js: Создает пустой файл конфигурации веб-пакета.

Шаг 5. Создать приложение
npx webpack --config webpack.config.js

Объяснение:

npx webpack: запускает веб-пакет для объединения приложения.
--config webpack.config.js: указывает файл конфигурации веб-пакета, который будет использоваться.

Шаг 6: Добавить HTML, CSS ,JS -файл

Шаг 7: Запустить приложение
 npx webpack serve --open
