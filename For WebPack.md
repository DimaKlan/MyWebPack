npm init -y

npm install webpack -D
npm install webpack-cli webpack-dev-server -D
npm install --save-dev html-webpack-plugin
npm install --save-dev html-loader
npm install --save-dev style-loader
npm install --save-dev css-loader
npm install sass-loader sass webpack --save-dev
npm install css-minimizer-webpack-plugin --save-dev
npm install --save-dev postcss-loader postcss
npm install -D babel-loader @babel/core @babel/preset-env webpack
npm install --save @babel/polyfill
npm install image-webpack-loader --save-dev

npm install html-minimizer-webpack-plugin --save-dev

<!-- Для работы с проектом -->

npm run build-prod - сборка для продакшен (папка dist)
npm run build-dev - сборка для проверки
npm run start - запуск сервера
npm run start clear - отчищает папку dist
