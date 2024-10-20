# mini-browser

> JIT（即时编译）

编译器：

1. 词法分析
2. 语法分析
3. 语义分析
4. 运行时环境
5. 中间代码
6. 代码优化
7. 生成目标代码

> 无头浏览器

静态作用域和词法环境、变量对象(VO)和活动对象(AO)

函数调用栈

客户端服务端双向通信: HTTP轮询、XHR Streaming和Server-sent events


<https://www.chromium.org/blink/>

<https://ecma-international.org/publications-and-standards/standards/ecma-262/>

GUI渲染线程和JavaScript脚本引擎线程互斥

> `CSSOM`和视觉格式化模型

光栅化

```js
const controller = new AbortController()
			
document.getElementById('scroll-bar').addEventListener('click', e=>{

}, {
  signal: controller.signal,
  once: true,
  capture: true,
  passive: true,
})


```

> 包含块

注: `z-index`值的设置只会决定同一父元素中同级子元素的堆叠顺序

v8内存分配和垃圾回收

- 新生代：Scavenge算法
- 老生代: 标记整理清除（增量标记和三色标记法）

```sh
node --max-old-space-size=2048 

```


## Severless

## Micro Frontend

## PWA

## WebAssembly

## WebGL

## GraphQL
