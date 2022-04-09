## 更新项目所有包
```javascript
  npm i -g npm-check-updates
  ncu // 产看所有更新
  nuc -u // 新版本号更新到package.json（注意检查各更新包后慎重执行）
```

## webpack 构建生成es5代码
```javascript
  {
    target: ["web","es5"]
  }
```

## url-loader file-loader raw-loader 不在支持 webpack 5

[webpack 5 内置资源模块（asset module）代替 url-loader file-loader raw-loader](https://webpack.docschina.org/guides/asset-modules/)

## eslint-loader 弃用 替换为 eslint-webpack-plugin

-   [eslint-loader（已经弃用）](https://github.com/webpack-contrib/eslint-loader)
-   [eslint-webpack-plugin](https://github.com/webpack-contrib/eslint-webpack-plugin)

## 代码分割 optimization.splitChunks

[optimization.splitChunks](https://webpack.docschina.org/plugins/split-chunks-plugin/)

## 代码压缩

### css 压缩 optimize-css-assets-webpack-plugin 替换为 css-minimizer-webpack-plugin

-   [optimize-css-assets-webpack-plugin（已经弃用）](https://github.com/NMFR/optimize-css-assets-webpack-plugin)
-   [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin)

### js 压缩 terser-webpack-plugin

-   [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin)

### gzip

-   [compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin)
