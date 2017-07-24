# React-carousel
this is react-carousel component and it suport Responsive layout!(suport gesture operation!)

这是个react轮播图组件,并且它是响应式的!(支持手势操作!)


#Start
```
git clone https://github.com/SmartDoubleXiao/react-carousel.git master

npm install

npm start

```
#Usage
```html
<link rel="stylesheet" href="./css/font-awesome.min.css">
```

```js
import React from 'react';
import ReactDOM from 'react-dom'
import Slider from './slider.jsx';
var slides = [{
    background: "./imgs/1.jpg",
    link: "http://xxwu.tech/"
  }, {
    background: "./imgs/2.jpg",
    link: "http://xxwu.tech/"
  }, {
    background: "./imgs/3.jpg",
    link: "http://xxwu.tech/"
  }];

ReactDOM.render( < Slider slides= {slides} time="2000"/ > , document.getElementById("app"));
```
