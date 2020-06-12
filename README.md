# vue-stars-rating

`npm i webpack webpack-dev-server --save-dev`  
`npm i -D webpack-cli`

## webpack

[devServer.contentBase](https://webpack.js.org/configuration/dev-server/#devservercontentbase)

`webpack-dev-server --content-base`

webpack-dev-server 是一個非常小的 Node.js Express server，他使用了 webpack-dev-middleware 來服務 webpack 的綑綁功能，而 webpack-dev-server 背後使用了 socket.IO  基本上 webpack-dev-server 是用於測試環境的，不是拿來用於編譯的
