# 原始值与对象

1. 原始值
1. Number
1. Null
1. Undefined
1. String
1. Boolean

1. 对象

Object

3. 区别

1. 对象有唯一标识只严等于自己
1. 原始值只要编码值相同，即为相等
1. typeof 用于原始值 instanceof 用于对象

## Boolean

- 假值

  1. Number 0 -0 NaN
  2. String ''
  3. Boolean false

- 真值

  1. Number>0
  2. Object
  3. String

- 二元逻辑操作符

  1. true && foo()
  2. flase || foo()

- 等号操作符
  1. ==
  2. ===

## Number

1. NaN

   - 1+undefined -> NaN
   - typeof NaN -> Number
   - NaN instanceof Number -> false
   - NaN ==NaN -> false

2. Infinity
   - Infinity >NaN -> false

## Function

1.  声明方式

- 函数表达式
  const fn = function(){}
  右侧为匿名函数，即使为具名函数，也无法通过函数名找到原函数
- 函数声明
  function func (){}
  声明将提前作用域最前

2. 特性

- 闭包
  函数与它所连接的周围作用域的变量即为闭包
  每个函数与它周围作用域变量保持连接，哪怕离开它创建时的作用域也是如此
- 作用域
- 匿名函数
  函数声明必须为具名函数
- IIFE
  (function(){}())
  立即执行函数

3. 属性

- name
  函数名
- length
  参数数量

4. argument

- 类数组

5. 方法
   5.1. 改变 this
   - call
   - apply
     参数为数组
   - bind
     返回函数
