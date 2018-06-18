# FrontCache

```
git clone https://github.com/xumenger/FrontCache.git
cd FrontCache/
npm init
vim package.json
mkdir src
mkdir release
mkdir doc
mkdir test
mkdir example
touch src/index.js
npm i babel-core babel-loader babel-polyfill babel-preset-es2015 babel-preset-latest webpack webpack-cli --save-dev
vim .babelrc
vim webpack.config.js
npm run release
vim example/test.html
sudo npm install http-server -g
npm run example
sudo npm i gitbook-cli -g
gitbook init
gitbook build
git tag -a 'v0.0.1' -m 'first commit'
git push origin v0.0.1
```

