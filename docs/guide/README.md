# 介绍

**rainforest-js** 是 [结构、安全、自动化](#结构、安全、自动化) 的类型描述系统，用于使用数据结构化编程。

它可以马上应用于你的任何现有项目中，无需修改任何部分，没有任何限制。

## 什么是数据结构化编程？

::: tip 程序的本质是从输入数据结构，来获取输出数据结构。
首先，我们应该认可这个概念。
:::

编排输入数据结构的字段，即可自动化执行程序，获得预期输出数据结构的编程方式。  
**当数据准备好时，即可获得预期结果。**

这种新的编程方式，可以解放思维，无需关心数据的具体生成过程，只关心预期结果。

### 过程是导致复杂的原因

实际上过程本身就是复杂的，一直都是。  
少量的过程是可以阅读并理解的，而过多的过程是难以理解的。  
更令人悲伤的是，过程一般是无法精简的，所以过程总是难以阅读理解的。

这就是面向过程编程的本质复杂性，无法避免。

### 数据结构化 VS 面向过程

数据结构化的行为是：准备需要的数据，获得预期结果。  
唯一需要做的工作，就是提供数据。一旦数据都准备好，就能获得结果。  
具体实现过程是无需关心的，也就是无需思考复杂的部分。

### 使用场景

常用的场景包括但不限于：

- 用于封装模块对接部分
- 用于编排组合各个模块协同工作
- 通过编排组合模块，实现程序的最终交付
- ...

## 结构、安全、自动化

**结构：** 将结构体（视为配置文件）作为模块的接口，通过编排字段来控制模块的行为，  
易于组织出层次清晰的大型程序。

**安全：** 类型描述用来保障实际的输入值符合预期结果。

**自动化：** 当期待的数据准备好时，自动触发程序，生成交付结果。

## 安装

使用 npm 安装

```sh
npm install rainforest-js
```

或在浏览器中使用

```html
<script src="https://unpkg.com/rainforest-js"></script>
```