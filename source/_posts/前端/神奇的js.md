---
title: 神奇的js
tags: []
id: '2009'
categories:
  - - web前端
date: 2018-04-07
---

```js
(!(~+[])+{})[--[~+""][+[]]*[~+[]] + ~~!+[]]+({}+[])[[~!+[]]*~+[]] === 'sb'
```

短路表达式、三元表达式

```js
a = b && 1
// 相当于
a = !!b ? 1 : b
if (b) { a = 1 } else { a = b }

a = b || 1
// 相当于
a = !!b ? b : 1
if (b) { a = b } else { a = 1 }
```

取整(不四舍五入)

```js
~~2.33 === 2
2.33 | 0 === 2
2.33 >> 0 === 2
```



```js
'0' == 0 // true
0 == [] // true

'0' == [] // false
```





