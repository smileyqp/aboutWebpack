>- #### 安装
> `npm install --global webpack`
>  `npm install --global webpack-cli`
>  - ##### 初步测试
>  - `mkdir testFloder`
>  - 进入testFloder并且`mkdir src`在src下面touch一个index.js文件
>  - `webpack --mode=developement`(development开发环境或者production生产环境或者none)
>  - 指定打包输出`webpack --mode=development ./src/hello.js --output ./dist/hello.js`