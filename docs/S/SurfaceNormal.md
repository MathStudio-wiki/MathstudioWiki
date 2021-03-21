## SurfaceNormal(function, [varlist], [point])

### [varlist]
默认值为[x，y，z]。

### [point]

如果给定了点，则在给定点处计算法线向量。 如果不是，则使用[x，y，z]。

## 说明

计算点处函数给定的曲面的法向量。

同时返回正法向量和负法向量。



## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=U3VyZmFjZU5vcm1hbCh4KnleMy16LTIsW3gseSx6XSxbMSwxLC0xXSk%3D&input[1]=U3VyZmFjZU5vcm1hbCh4XjIqeSp6LTEsW3gseSx6XSxbMSwxLDFdKQ%3D%3D&input[2]=U3VyZmFjZU5vcm1hbCh4XjIreV4yK3peMixbeCx5LHpdLFs1LDAsMTJdKQ%3D%3D&input[3]=U3VyZmFjZU5vcm1hbCh4XjIreV4yLFt4LHldLFthLGJdKQ%3D%3D)




>   ```math
>   SurfaceNormal(x*y^3-z-2, [x, y, z], [1, 1, -1])
>   ```
>   $ [ (\frac{1}{\sqrt{11}},\frac{3}{\sqrt{11}},-\frac{1}{\sqrt{11}})   ,(-\frac{1}{\sqrt{11}},-\frac{3}{\sqrt{11}},\frac{1}{\sqrt{11}})                    ]$



>   ```math
>   SurfaceNormal(x^2*y*z-1, [x, y, z], [1, 1, 1])
>   ```
>   $ [ (\frac{2}{\sqrt{6}},\frac{1}{\sqrt{6}},\frac{1}{\sqrt{6}})   ,(-\frac{2}{\sqrt{6}},-\frac{1}{\sqrt{6}},-\frac{1}{\sqrt{6}})   ]$




>   ```math
>   SurfaceNormal(x^2+y^2+z^2, [x, y, z], [5, 0, 12])
>   ```
>   $ [ (\frac{5}{13},0,\frac{12}{13})   ,(-\frac{5}{13},0,-\frac{12}{13})   ]$


>   ```math
>   SurfaceNormal(x^2+y^2, [x, y], [a, b])
>   ```
>   $ [ (\frac{2 a}{\sqrt{\operatorname{abs}(2 a)^{2}+\operatorname{abs}(2 b)^{2}}},\frac{2 b}{\sqrt{\operatorname{abs}(2 a)^{2}+\operatorname{abs}(2 b)^{2}}})   ,(-\frac{2 a}{\sqrt{\operatorname{abs}(2 a)^{2}+\operatorname{abs}(2 b)^{2}}},-\frac{2 b}{\sqrt{\operatorname{abs}(2 a)^{2}+\operatorname{abs}(2 b)^{2}}})  ]$





## 参考
http://mathworld.wolfram.com/NormalVector.html

## 相关函数

[Curl](C/Curl)

[Divergence](D/Divergence)

[Duf](D/Duf)

[Hessian](H/Hessian)

[Jacobian](J/Jacobian)

[Laplacian](L/Laplacian)

[Gradient](G/Gradient)












