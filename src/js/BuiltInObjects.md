# 内置对象
## JavaScript
### Array
### Date
```javascript
const date = new Date();
// 获取年份
console.log(date.getFullYear());
// 获取月
console.log(date.getMonth()+1);
// 获取日
console.log(date.getDate());
// 获取星期
console.log(date.getDay());
// 获取时
console.log(date.getHours());
// 获取分
console.log(date.getMinutes());
// 获取秒
console.log(date.getSeconds())
// 获取毫秒
console.log(date.getMilliseconds())

const date1 = new Date(2019,1,25,13,10)
console.log(date1) // Mon Feb 25 2019 13:10:00 GMT+0800 (中国标准时间)
```
### RegExp
### Math
### Boolean
### String
### Number
### Object
```javascript
// 用于创建对象
Object.create()
// 用于将所有可枚举属性的值从一个或多个源对象复制到目标对象。它将返回目标对象。
Object.assign()
// 用于冻结对象，一个被冻结的对象再也不能被修改；冻结了一个对象则不能向这个对象添加新的属性，不能删除已有属性，不能修改该对象已有属性的可枚举性、可配置性、可写性，以及不能修改已有属性的值。此外，冻结一个对象后该对象的原型也不能被修改。
Object.freeze()
// 会直接在一个对象上定义一个新属性，或者修改一个对象的现有属性，并返回此对象。
Object.defineProperty
```
### Set
### Map
## Browser
### Window
### Navigator
### Screen
### History
### Location
## Node
