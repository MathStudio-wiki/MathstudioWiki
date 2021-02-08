### Angle(A, B)

返回两个向量A和B之间的夹角。

### 示例

[在MathStudio中浏览](http://mathstud.io/?input[0]=QW5nbGUoW2FAXzEsYkBfMSxjQF8xXSxbYUBfMixiQF8yLGNAXzJdKQ%3D%3D&input[1]=QW5nbGUoWzEsMiwzXSxbNCw1LDZdKQ%3D%3D)

> ```math
> Angle([a@_1, b@_1, c@_1], [a@_2, b@_2, c@_2])
> ```
>
> $
> acos(\\
> \frac{a_1 a_2}{\sqrt{abs(a_1)^2+abs(b_1)^2+abs(c_1)^2}\sqrt{abs(a_2)^2+abs(b_2)^2+abs(c_2)^2}} +\\
> \frac{b_1 b_2}{\sqrt{abs(a_1)^2+abs(b_1)^2+abs(c_1)^2}\sqrt{abs(a_2)^2+abs(b_2)^2+abs(c_2)^2}} +\\
> \frac{c_1 c_2}{\sqrt{abs(a_1)^2+abs(b_1)^2+abs(c_1)^2}\sqrt{abs(a_2)^2+abs(b_2)^2+abs(c_2)^2}}\\
> \\)
> $

> ```math
> Angle([1, 2, 3], [4, 5, 6])
> ```
>
> $acos(\frac{32}{7\sqrt{22}})$
> <br>
> *0.225726128553*
