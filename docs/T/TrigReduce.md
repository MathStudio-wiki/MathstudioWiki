## TrigReduce(expression)


将三角函数的乘积和幂用表达式重写为具有组合参数的三角函数。


## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=VHJpZ1JlZHVjZShzaW4oeCleMipjb3MoeCkgKyA1KmNvcyh4KV4zICsgMipzaW4oeCkqY29zKHgpKQ%3D%3D&input[1]=VHJpZ1JlZHVjZSgtM2Nvcyh4KSpzaW4oNSktY29zKDUpKnNpbih4KSs0Y29zKHgpXjMqc2luKDUpKzRjb3MoeCleMipjb3MoNSkqc2luKHgpKQ%3D%3D&input[2]=VHJpZ1JlZHVjZShjb3MoeF4yKSpjb3Moc3FydCh5KSktc2luKHNxcnQoeSkpKnNpbih4XjIpKQ%3D%3D&input[3]=VHJpZ1JlZHVjZSgzKnNpbih4KSpjb3MoeCktc2luKHgpXjIrY29zKHgpXjIp&input[4]=VHJpZ1JlZHVjZShjb3MoeSkqc2luKHopKnNpbih4KStjb3MoeikqY29zKHgpKmNvcyh5KStjb3Moeikqc2luKHkpKnNpbih4KS1jb3MoeCkqc2luKHopKnNpbih5KSk%3D&input[5]=VHJpZ1JlZHVjZSg0Kihjb3MoeCp5KV4yKSpzaW4oeCp5KS1zaW4oeCp5KSk%3D&input[6]=VHJpZ1JlZHVjZSgzMiooY29zKHgpXjMpKnNpbih4KS02KmNvcyh4KSpzaW4oeCktMzIqKGNvcyh4KV41KSpzaW4oeCkp&input[7]=VHJpZ1JlZHVjZSgxNiooY29zKHgqeSleNCkqc2luKHgqeSktMTIqKGNvcyh4KnkpXjIpKnNpbih4KnkpK3Npbih4KnkpKQ%3D%3D)



>   ```math
>   TrigReduce(sin(x)^2*cos(x) + 5*cos(x)^3 + 2*sin(x)*cos(x))
>   ```
>   $ 4 \cos (x)+\cos (3 x)+\sin (2 x) $

>   ```math
>   TrigReduce(-3cos(x)*sin(5)-cos(5)*sin(x)+4cos(x)^3*sin(5)+4cos(x)^2*cos(5)*sin(x))
>   ```
>   $ \sin (3 x+5) $

>   ```math
>   TrigReduce(cos(x^2)*cos(sqrt(y))-sin(sqrt(y))*sin(x^2))
>   ```
>   $ \cos \left(x^{2}+\sqrt{y}\right) $


>   ```math
>   TrigReduce(3*sin(x)*cos(x)-sin(x)^2+cos(x)^2)
>   ```
>   $\frac{3}{2} \sin (2 x)+\cos (2 x)  $

>   ```math
>   TrigReduce(cos(y)*sin(z)*sin(x)+cos(z)*cos(x)*cos(y)+cos(z)*sin(y)*sin(x)-cos(x)*sin(z)*sin(y))
>   ```
>   $ \cos (x-y-z) $

>   ```math
>   TrigReduce(4*(cos(x*y)^2)*sin(x*y)-sin(x*y))
>   ```
>   $ \sin (3 x y) $

>   ```math
>   TrigReduce(32*(cos(x)^3)*sin(x)-6*cos(x)*sin(x)-32*(cos(x)^5)*sin(x))
>   ```
>   $ -\sin (6 x) $

>   ```math
>   TrigReduce(16*(cos(x*y)^4)*sin(x*y)-12*(cos(x*y)^2)*sin(x*y)+sin(x*y))
>   ```
>   $ \sin (5 x y) $



## 相关函数

[ExpConvert](E/ExpConvert)

[TrigConvert](T/TrigConvert)

[TrigExpand](T/TrigExpand)
