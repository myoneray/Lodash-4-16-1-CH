# Lodash-4.16.1-CH
熟悉Lodash-4.16.1　顺带做下中文翻译


##Array 的方法






##chunk－指定长度切割
```
_.chunk(array, [size=1])
```
>　按照指定长度切割一个数组放在新的数组中．如果数组不能均等的切分，则最后的块包含剩余部分．

#### 参数
`array (Array)`: 要处理的数组.
`[size=1] (number)`: 每个块的长度
#### 结果
`array` 返回新的数组
####示例

```
_.chunk(['a', 'b', 'c', 'd'], 2);
// => [['a', 'b'], ['c', 'd']]

_.chunk(['a', 'b', 'c', 'd'], 3);
// => [['a', 'b', 'c'], ['d']]
```


##compact－数组过滤
```
_.compact(array)
```
>创建一个数组移除所有非法字符，包括　false, null, 0, "", undefined, NaN

#### 参数
`array (Array)`: 要处理的数组.

#### 结果
`array` 返回过滤后的新数组．

####示例
```
_.compact([0, 1, false, 2, '', 3]);
// => [1, 2, 3]
```


##concat－数组合并
```
_.concat(array, [values])
```
>Creates a new array concatenating array with any additional arrays and/or values.
>将一个数组与其他数组／值链接起来，放在一个新的数组中．

#### 参数
`array (Array)`: 链接的数组
`[values] (...*)`: 链接的值

#### 结果
`array` 返回新链接后的新数组

####示例
```
var array = [1];
var other = _.concat(array, 2, [3], [[4]]);

console.log(other);
// => [1, 2, 3, [4]]

console.log(array);
// => [1]
```

##difference－Ａ与Ｂ做对比，取出Ａ数组中的不同部分
```
_.difference(array, [values])
```
>用SameValueZero的方式去判断，将数组中不包含在提供的数组中的元素提取出来，放在新的数组中．

#### 参数
`array (Array)`: 需要过滤的数组
`[values] (...Array)`: 作为比对的数组

#### 结果
`array`: 返回 array 的剩余部分。

####示例
```
_.difference([2, 1], [2, 3]);
// => [1]
_.difference([1, 2, 3], [4, 2]);
// => [1, 3]
_.difference([1, '2', 3], [4, 2]);
// => [1, "2", 3]
```

##differenceBy
```
_.differenceBy(array, [values], [iteratee=_.identity])
```
>用指定的方式去判断，将数组中不包含在提供的数组中的元素提取出来，放在新的数组中．

#### 参数

`array (Array)`: 取值数组.
`[values] (...Array)`: 比对数组.
`[iteratee=_.identity] (Function)`: 每个元素比对调用的方法

#### 结果
`array` 返回新的数组

####示例
```
console.log(_.differenceBy([2.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7], [1.9,2.0,2.3, 3.4], Math.floor));
// => [1.2, 1.3, 1.4, 1.5]

console.log(Math.floor(0.1));
//0
//Math.floor求一个最接近它的整数，它的值小于或等于这个浮点数。
// The `_.property` iteratee shorthand.
_.differenceBy([{ 'x': 2 }, { 'x': 1 }], [{ 'x': 1 }], 'x');
// => [{ 'x': 2 }]
```

##ＸＸＸＸ
```
ＸＸＸＸ
```
>ＸＸＸＸ

#### 参数
`ＸＸＸＸ`: ＸＸＸＸ
`ＸＸＸＸ`: ＸＸＸＸ

#### 结果
`array` 返回新的数组

####示例
```
ＸＸＸＸ
```

##ＸＸＸＸ
```
ＸＸＸＸ
```
>ＸＸＸＸ

#### 参数
`ＸＸＸＸ`: ＸＸＸＸ
`ＸＸＸＸ`: ＸＸＸＸ

#### 结果
`array` 返回新的数组

####示例
```
ＸＸＸＸ
```

##ＸＸＸＸ
```
ＸＸＸＸ
```
>ＸＸＸＸ

#### 参数
`ＸＸＸＸ`: ＸＸＸＸ
`ＸＸＸＸ`: ＸＸＸＸ

#### 结果
`array` 返回新的数组

####示例
```
ＸＸＸＸ
```

##ＸＸＸＸ
```
ＸＸＸＸ
```
>ＸＸＸＸ

#### 参数
`ＸＸＸＸ`: ＸＸＸＸ
`ＸＸＸＸ`: ＸＸＸＸ

#### 结果
`array` 返回新的数组

####示例
```
ＸＸＸＸ
```

##ＸＸＸＸ
```
ＸＸＸＸ
```
>ＸＸＸＸ

#### 参数
`ＸＸＸＸ`: ＸＸＸＸ
`ＸＸＸＸ`: ＸＸＸＸ

#### 结果
`array` 返回新的数组

####示例
```
_.difference([1, 2, 3], [4, 2]);
// => [1, 3]
_.difference([1, '2', 3], [4, 2]);
// => [1, "2", 3]
```

##ＸＸＸＸ
```
ＸＸＸＸ
```
>ＸＸＸＸ

#### 参数
`ＸＸＸＸ`: ＸＸＸＸ
`ＸＸＸＸ`: ＸＸＸＸ

#### 结果
`array` 返回新的数组

####示例
```
ＸＸＸＸ
```
