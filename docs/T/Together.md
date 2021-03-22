## Together

为多项式函数的每个加项找到公分母，并返回一个包含一个分子和一个分母的等价表达式。它执行与Apart函数相反的操作。

## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=VG9nZXRoZXIoMS9hKzEvYik%3D&input[1]=VG9nZXRoZXIoMi0xLyh4KzEpKzQvKHgtMikp&input[2]=VG9nZXRoZXIoMi0xLyh4KzEpKzQvKHgrMSleMik%3D&input[3]=VG9nZXRoZXIoZXhwKHopL2EtZXhwKHopXjIvYik%3D)




>   ```math
>   Together(1/a+1/b)
>   ```
>   $ \frac{a+b}{a b} $


>   ```math
>   Together(2-1/(x+1)+4/(x-2))
>   ```
>   $ \frac{x+2 x^{2}+2}{(x-2)(x+1)} $



>   ```math
>   Together(2-1/(x+1)+4/(x+1)^2)
>   ```
>   $ \frac{2 x^{2}+3 x+5}{(x+1)^{2}} $


>   ```math
>   Together(exp(z)/a-exp(z)^2/b)
>   ```
>   $ \frac{-a e^{2 z}+b e^{z}}{a b} $



## 相关函数

[Apart](A/Apart)

[Factor](F/Factor)

[TrigExpand](T/TrigExpand)

[TrigReduce](T/TrigReduce)

[Expand](E/Expand)
