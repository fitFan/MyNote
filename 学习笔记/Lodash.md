## 介绍

 Lodash 是一个一致性、模块化、高性能的 JavaScript 实用工具库。 

## 数组

## 集合

## 函数

对于函数的参数、调用执行时机、返回结果等作出修改；

### `_.rearg(func, indexes)`

根据指定的索引，这个索引对应的是实际传入参数的索引

```js
//a 取传入索引为2的参数即 'a', b 取传入索引为0的参数即 'b' ...
var rearged = _.rearg(function(a, b, c) {
  return [a, b, c];
}, [2, 0, 1]);

rearged('b', 'c', 'a')
// => ['a', 'b', 'c']
```

## 语言

转换、克隆（深浅克隆）、比较（对象比较与判断）

## 数学

数据的各种取值与操作

## 数字

限制大小、判断是否在区间、取随机数

## 对象

分配属性、枚举遍历

对象比较（深度比较）

## Seq

链式调用

## 字符串

## 实用函数

## Properties

## Methods

 `lodash` 引用  `_.templateSettings.imports._`