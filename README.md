# daycaca

[![Build Status](https://travis-ci.org/JackPu/daycaca.svg?branch=master)](https://travis-ci.org/JackPu/daycaca)
[![npm](https://img.shields.io/npm/v/daycaca.svg?maxAge=2592000)]()


<img src="http://img1.vued.vanthink.cn/vuede494856de5f2390a5727a6d98d488305.png" width="400">

A pure JavaScript library to handle image via canvas.


## How to use

### npm

``` bash
$  npm install daycaca -save
```


``` es6
// es6
import daycaca from 'daycaca';
// src specify an image src (url or base64)
daycaca.rotate(src, degress, (data, w, h) => {
  // your code here
});

```

### CDN

``` js
<script src="./dist/index.js"></script>

<script>
  // src specify an image src (url or base64)
  daycaca.rotate(src, degress, (data, w, h) => {
    // your code here
  });
</script>
```



## API

### base64(el, callback)

将图片转换成 base64 code 值；参数 `el` 可以为一个图片的 Dom 节点也可以是一个图片地址；

``` js
const img = document.querySelector('img')
daycaca.base64(img, (data) => {
  //... handle base64
})
```



+ compress

+ crop

+ rotate

+ reszie
