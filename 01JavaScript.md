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

   - typeof NaN -> Number
   - NaN instanceof Number -> false
   - NaN ==NaN -> false

2. Infinity
   - Infinity >NaN -> false
