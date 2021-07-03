---
title: "Syntax Highlighting"
metaTitle: "Syntax Highlighting is the meta title tag for this page"
metaDescription: "This is the meta description for this page"
---

**オイラーの等式**
$$
e^{i\pi}+1= 0
$$
ネイピア数$e$、虚数$i$、円周率$\pi$と有名な定数に$0$と$1$がある全部入りの数式。

**正規分布（ガウス分布）**
$$
f(x) = \frac{1}{\sqrt{2\pi\sigma^2}}\exp{-\frac{(x-\mu)^2}{2\sigma^2}}
$$
平均を$\mu$, 分散を$\sigma^2 \gt 0$とする正規分布とは、確率密度関数が次の形で与えられる確率密度関数。

$$ katex $$

Lift($L$) can be determined by Lift Coefficient ($C_L$) like the following equation.

$$
L = \frac{1}{2} \rho v^2 S C_L
$$

katex

$a^2 + b^2 = c^2$

$$
a^2 + b^2 = c^2
$$

本文中に唐突に $E = mc^2$ 埋め込む。

インラインの式中に $a_n = \frac{1}{\pi} \int_{0}^{2\pi}f(x)\cos(nx)dx$ のような分数やインテグラルが入るとちょっと見にくくなるので、$\displaystyle b_n = \frac{1}{\pi} \int_{0}^{2\pi} f(x) \sin nx dx$ とすると見やすくなる。


The following is a code block with JavaScript language syntax highlighting.

```javascript
import React from 'react';
```

Supports multiple languages.

The following is a code block with diff. Lines with `+` highlighted in green shade indicating an addition. Lines with `-` highlighted in red shade indicating a deletion.

```javascript
- const data = ['1','2'];
+ const data = [1,2];
```

## Live Editing example

```javascript react-live=true
<button className={'btn btn-default'}>Change my text</button>
```
