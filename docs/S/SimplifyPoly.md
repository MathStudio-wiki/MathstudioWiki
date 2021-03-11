## SimplifyPoly(f(x)/g(x), [variable])

### f(x)/g(x)
此参数可以是以下任何形式。


f(x) , f(x)/g(x) , f(x)^n/g(x) , f(x)/g(x)^n

### [variable]

此参数是可选的。 如果未指定变量，MathStudio将搜索正确的变量。


## 说明

通过对分子f(x)，分母g(x)进行因子分解，然后计算最终的因子形式，可以简化多项式商f(x)/g(x)。



## 举例

[在Mathstudio上浏览](http://mathstud.io/?input[0]=U2ltcGxpZnlQb2x5KCh4XjYrMTF4XjQrMjR4XjItMzYpLyh4XjQrNXheMi02KSk%3D&input[1]=U2ltcGxpZnlQb2x5KDI1NnpeOD0xLHop&input[2]=U2ltcGxpZnlQb2x5KCh4XjYtNnheNSsxNHheNCsxMHheMy0xMTF4XjIrNTZ4KzE1NikvKHheNCs1eF4yLTYpKQ%3D%3D&input[3]=U2ltcGxpZnlQb2x5KHpeMj0xNzEp&input[4]=U2ltcGxpZnlQb2x5KGEqeF4yKzJ4KzEseCk%3D&input[5]=U2ltcGxpZnlQb2x5KHheNisxMXheNCsyNHheMi0zNik%3D)



>   ```math
>   SimplifyPoly((x^6+11x^4+24x^2-36)/(x^4+5x^2-6))
>   ```
>   $ x ^ { 2 } + 6   $

>   ```math
>   SimplifyPoly(256z^8=1, z)
>   ```
>   $ 256\left(z-\frac{1}{2}\right)\left(z^{2}+\frac{1}{4}\right)\left(z+\frac{1}{2}\right)\left(\frac{z \sqrt{2}}{2}+z^{2}+\frac{1}{4}\right)\left(-\frac{z \sqrt{2}}{2}+z^{2}+\frac{1}{4}\right) $

>   ```math
>   SimplifyPoly((x^6-6x^5+14x^4+10x^3-111x^2+56x+156)/(x^4+5x^2-6))
>   ```
>   $ \frac{(x-3)(x-2)(x+2)\left(-4 x+x^{2}+13\right)}{(x-1)\left(x^{2}+6\right)}$

>   ```math
>   SimplifyPoly(z^2=171)
>   ```
>   $ (z+3 \sqrt{19})(z-3 \sqrt{19}) $

>   ```math
>   SimplifyPoly(a*x^2+2x+1, x)
>   ```
>   $ 2 x+a x^{2}+1$

>   ```math
>   SimplifyPoly(x^6+11x^4+24x^2-36)
>   ```
>   $(x-1)(x+1)\left(x^{2}+6\right)^{2}$

## 相关函数

[Apart](A/Apart)
[Factor](F/Factor)
[Together](T/Together)
[TrigExpand](T/TrigExpand)
[TrigReduce](T/TrigReduce)
[Expand](E/Expand)