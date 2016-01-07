方便开始写 HTML 测试代码，就像在 [JSBIN](http://jsbin.com) 里面写代码一样。

## Usage

```
npm install && npm start
```

代码请都写在 `src` 目录里面，代码会自动编译 CSS, JS, Jade 代码 到 `www` 目录下。

## Feature

* Jade for HTML file.
* auto compile CSS file.
* auto transform Javascript file by Babel.
* live reload HTML page.

## QA

Q: 找不到 opener, parallelshell, http-server, jade, node-sass, live-reload, babel 的路径
A: export PATH=./node_modules/.bin:$PATH
