---
layout: default
---

<h1 id="function-lsolve">Function lsolve <a href="#function-lsolve" title="Permalink">#</a></h1>

Solves the linear equation system by forwards substitution. Matrix must be a lower triangular matrix.

`L * x = b`


<h2 id="syntax">Syntax <a href="#syntax" title="Permalink">#</a></h2>

```js
math.lsolve(L, b);
```

<h3 id="parameters">Parameters <a href="#parameters" title="Permalink">#</a></h3>

Parameter | Type | Description
--------- | ---- | -----------
`L` | Matrix, Array | A N x N matrix or array (L)
`b` | Matrix, Array | A column vector with the b values

<h3 id="returns">Returns <a href="#returns" title="Permalink">#</a></h3>

Type | Description
---- | -----------
DenseMatrix &#124; Array | A column vector with the linear system solution (x)


<h2 id="examples">Examples <a href="#examples" title="Permalink">#</a></h2>

```js
var a = [[-2, 3], [2, 1]];
var b = [11, 9];
var x = lsolve(a, b);  // [[-5.5], [20]]
```


<h2 id="see-also">See also <a href="#see-also" title="Permalink">#</a></h2>

[lup](lup.html),
[slu](slu.html),
[usolve](usolve.html),
[lusolve](lusolve.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->