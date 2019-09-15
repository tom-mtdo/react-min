* Create fresh project
mkdir react-min
cd react-min
npm init -y
npm install webpack --save-dev
npm install webpack-cli --save-dev
mkdir src
vmi src/index.js
mkdir dist
vmi dist/index.html
npm install --save lodash
npx webpack
vmi webpack.config.js
npx webpack --config webpack.config.js
vmi package.json
npm run build