## Series(f(z), z, n)

求函数在0附近的级数展开。这个函数与麦克劳林级数相同。此函数可用于所有常用和最特殊的函数。


## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=U2VyaWVzKHNpbih4KStjb3MoeCkseCw4KQ%3D%3D&input[1]=U2VyaWVzKGV4cCgyeikseiwxMCk%3D&input[2]=U2VyaWVzKHRhbmgoM3kpLHksOCk%3D&input[3]=U2VyaWVzKEJlc3NlbEooMCx6KSx6LDgp&input[4]=U2VyaWVzKEJlc3NlbEooMCx4KStCZXNzZWxKKDEseCkseCw2KQ%3D%3D&input[5]=U2VyaWVzKGFzaW4oeCkseCwxNSk%3D&input[6]=U2VyaWVzKEZyZXNuZWxDb3Moeikseiw4KQ%3D%3D&input[7]=U2VyaWVzKEVpKHgpLHgsNyk%3D)



>   ```math
>   Series(sin(x)+cos(x), x, 8)
>   ```
>   $ x-\frac{x^{2}}{2} - \frac{x^{3}}{6}-\frac{x^{6}}{720}-0.000198412698 x^{7}+0.000024801587 x^{8}+\frac{x^{5}}{120}+\frac{x^{4}}{24}+1 $



>   ```math
>   Series(exp(2z), z, 10)
>   ```
>   $ 0.000282186949 z^{10}+0.001410934744 z^{9}+\frac{2 z^{8}}{315}+\frac{8 z^{7}}{315}+\frac{4 z^{6}}{45}+\frac{4 z^{5}}{15}+\frac{2 z^{4}}{3}+\frac{4 z^{3}}{3}+2 z+2 z^{2}+1 $



>   ```math
>   Series(tanh(3y), y, 8)
>   ```
>   $ -\frac{4131 \mathrm{y}^{7}}{35}-9 \mathrm{y}^{3}+3 \mathrm{y}+\frac{162 \mathrm{y}^{5}}{5} $



>   ```math
>   Series(BesselJ(0, z), z, 8)
>   ```
>   $ -\frac{z^{2}}{4} \cdot 0.000434027778 z^{6}+0.000006781684 z^{8}+\frac{z^{4}}{64}+1 $



>   ```math
>   Series(BesselJ(0, x)+BesselJ(1, x), x, 6)
>   ```
>   $ -\frac{x^{2}}{4} \cdot \frac{x^{3}}{16}-0.000434027778 x^{6}+\frac{x^{5}}{384}+\frac{x^{4}}{64}+\frac{x}{2}+1 $



>   ```math
>   Series(asin(x), x, 15)
>   ```
>   $ x+0.01396484375 x^{15}+0.017352764423 x^{13}+0.022372159091 x^{11}+0.030381944444 x^{9}+\frac{5 x^{7}}{112}+\frac{3 x^{5}}{40}+\frac{x^{3}}{6} $



>   ```math
>   Series(FresnelCos(z), z, 8)
>   ```
>   $ z-\frac{\pi^{2} z^{5}}{40}+0.000289351852 \pi^{4} z^{9} $



>   ```math
>   Series(Ei(x), x, 7)
>   ```
>   $ \gamma+x+0.000028344671 x^{7}+0.000231481481 x^{6}+\frac{x^{5}}{600}+\frac{x^{4}}{96}+\frac{x^{3}}{18}+\frac{x^{2}}{4}+\ln (x) $


## 参考

http://mathworld.wolfram.com/MaclaurinSeries.html

http://en.wikipedia.org/wiki/Maclaurin_series


## 相关函数

[Product](P/Product)
[Sum](S/Sum)