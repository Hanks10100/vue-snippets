# Useful Vue.js Code Snippets for Weex

欢迎贡献例子。Feel free to send a PR.

## 环境信息 (Environment)

+ [获取 Weex 执行环境 (Get Weex running environment)](http://dotwe.org/weex/8c2fb817f19d9837a4f773e163d9cc45)

## 组件 (Components)

> [官方文档](http://weex.apache.org/cn/references/components/index.html) （[Official documents](http://weex.apache.org/references/components/index.html)）

+ `<div>`
  + [最简例子 (Simple)](http://dotwe.org/vue/0d82873994de7626b853cb0a97b7431d)
  + [`<div>` 中不能写文本 (Can't write text node within `<div>`)](http://dotwe.org/vue/ac2349905fa09fd6ba3148ab64f428dc)
+ `<text>`
  + [最简例子 (Simple)](http://dotwe.org/vue/c72256d520c9303c348f3ce1c7daf246)
  + [使用 `lines` 属性 (Use `lines` property)](http://dotwe.org/vue/17925761ce71f04f55b2cbd11b715565)
+ `<image>`
  + [最简例子 (Simple)](http://dotwe.org/vue/41b0009dacffba0198f5ac535448bec1)
  + [使用 `resize` 属性 (Use `resize` property)](http://dotwe.org/vue/67686fd2546e41683eb8eee01640aae3)
+ `<a>`
  + [最简例子 (Simple)](http://dotwe.org/vue/a6a6ab6d3807349daae32138585d7153)
+ `<list>`
  + [最简例子 (Simple)](http://dotwe.org/vue/bef3519b9a00f94a0fc4a127e9b43405)
  + [使用 loadmore (Use loadmore)](http://dotwe.org/vue/6f340bb6f5dc19d53b7ce26cfc420787)
  + [使用 `<header>` (Use `<header>`)]-()
  + [使用 `<loading>` (Use `<loading>`)]-()
  + [使用 `<refresh>` (Use `<refresh>`)]-()
+ `<scroller>`
  + [最简例子 (Simple)](http://dotwe.org/vue/563b9cf57ec3463592c5590abcd259fc)
  + [横滚 (Horizontal)](http://dotwe.org/vue/c93cededd4ae439c5d4d6892c113af72)
  + [使用 loadmore (Use loadmore)](http://dotwe.org/vue/3c61f3d1e4c6b62f4bbddce65a1ffe72)
  + [使用 `<loading>` (Use `<loading>`)]-()
  + [使用 `<refresh>` (Use `<refresh>`)]-()
+ `<slider>`
  + [最简例子 (Simple)](http://dotwe.org/vue/90975eafba77caee11521ff94b4a51e3)
  + [自动播放 (Autoplay)](http://dotwe.org/vue/8964d77f68a3d0eb170cb88751d9add7)
  + [自定义 indicator (Custom indicator)]-()
+ `<switch>`
  + [最简例子 (Simple)](http://dotwe.org/vue/d12f3515d1ee577d4c11dd0c9a15485b)
  + [checked & disabled](http://dotwe.org/vue/f7903c8299789ed1367cfd661c3e8d02)
  + [监听 change 事件 (Listen change event)](http://dotwe.org/vue/4003f58f12defd80c5a3866bb783227f)
+ `<input>`
  + [最简例子 (Simple)](http://dotwe.org/vue/6a9b794e2b9485c88ff8c3704df6aa3c)
  + [placeholder](http://dotwe.org/vue/be40c1ca9c5218efd17ed665500cde03)
  + [autofocus & disabled & maxlength](http://dotwe.org/vue/2231a60892fb13a9d5284fce028e343e)
  + [多种不同的类型 (Different types)](http://dotwe.org/vue/5526f23be29212c109a4aab0ab82b59f)
  + [`input`, `change`, `focus`, `blur` events](http://dotwe.org/vue/bb84e9930a84e64e0f126a6fcc112a66)
+ `<textarea>`
  + [最简例子 (Simple)](http://dotwe.org/vue/6b704d89f2195f00806f31c767e8c7aa)
  + [placeholder](http://dotwe.org/vue/161db9198a0af29fb3092207ea94cd52)
  + [autofocus & disabled & maxlength](http://dotwe.org/vue/f8294778a6ac7081e93fdf388431a42c)
  + [使用 `rows` 属性 (Use `rows` property)](http://dotwe.org/vue/177bae11b1e469fbe099facd2da8708b)
  + [`input`, `change`, `focus`, `blur` events](http://dotwe.org/vue/1ebd061d17c44ba5b1239fecb640cb51)
+ `<video>`
  + [最简例子 (Simple)](http://dotwe.org/vue/2c8df693bf2b8a50669a2c5d9618e6b4)
  + [`start`, `pause`, `finish`, `fail` events](http://dotwe.org/vue/2246907a52dc3b48e281f7d5ea4bc816)
+ `<web>`
  + [最简例子 (Simple)](http://dotwe.org/vue/d5754bc4b7d5cba92ae7e75a776a7eba)

## 模块 (Modules)

> [官方文档](http://weex.apache.org/cn/references/modules/index.html) （[Official documents](http://weex.apache.org/references/modules/index.html)）

+ 模态框 (modal)
  + [`alert`](http://dotwe.org/vue/5bd7a4c9ae3958ddc41749696be7be16)
  + [`toast`](http://dotwe.org/vue/168178602437c108eb9011e6e5a36110)
  + [`confirm`](http://dotwe.org/vue/1c523d5b277b3881d4e29deef960248a)
  + [`prompt`](http://dotwe.org/vue/dfb3a27df6831d0a15f7bf39c578b2b2)
+ 网络请求 (stream)
  + [基本用法 (Simple)](http://dotwe.org/vue/fe759defe8a60654633d3453d3dfde48)
+ 元素相关 (dom)
  + [`getComponentRect`](http://dotwe.org/vue/9dfef337f96127a121f199f4d389c654)
  + [`scrollToElement`](http://dotwe.org/vue/d44685798cc62b7a627982908c10ba64)
+ 动画 (animation)
  + [基本用法 (Simple)](http://dotwe.org/vue/c874958a49e10706aa8aea6c63030ff1)
+ 页面导航 (navigator)
  + [`jump` & `back`](http://dotwe.org/vue/89ea5081fef08a600b75752c19fa52cf)
+ 剪切板 (clipboard)
  + [基本用法 (Simple)]-()
+ 本地存储 (storage)
  + [基本用法 (Simple)]-()
+ 选择器 (picker)
  + [普通选项 (Options)](http://dotwe.org/vue/2b41249916567fcecc6b1d6281232cd6)
  + [日期 (Date)](http://dotwe.org/vue/8c4f40accafb8ae6365a2e6619580e5a)
  + [时间 (Time)](http://dotwe.org/vue/0e4aa7590610829e78a9420c1618314e)

## 布局 (Layouts)

+ [三角形 (Triangles)]-()
+ [多标签布局 (multiple labels)](http://dotwe.org/vue/f640a056edab078d23d019a981eaaae0)

## 样式 (Styles)

+ [阴影 (box-shadow)](http://dotwe.org/vue/e40ee07bcd8769298c084112721a0259)

## Vue.js 的语法特性 (Vue.js Features)

## 其他 (Others)

+ [Support WebAssembly ?](http://dotwe.org/vue/dc146caf0acc08c471a155d2e3d27444)
+ [骨骼动画 (Skeleton animation)](http://dotwe.org/weex/133a36671d6651c91de274df02ed2b89)
