## Solve(f(x), x, [guess])

### f(x)

要解决的表达式。

### x

要解决的变量。


### [guess]
求解方程的初始猜测值。 如果给出两个值的列表，例如Solve(sin(x)=0,x，[0,6@pi])，Solve将返回给定范围内的解。


## 说明

解决给定变量的表达式。

如果没有给出等号，则Solve假定表达式等于零。 例如，Solve(x^2-3)将表达式求解为x^2-3 = 0。

可以通过输入每个系数作为参数来求解二次方程。 例如，也可以将Solve(5x^2+3x+4)也可以输入为Solve(5,3,4)。

Solve也可以求解方程组。

求解（方程1，方程2，方程3，...）


## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=U29sdmUoM3grNT0wLHgp&input[1]=U29sdmUoM3grNSk%3D&input[2]=U29sdmUoeF4yLTV4KzY9MCk%3D&input[3]=U29sdmUoMSwtNSw2KQ%3D%3D&input[4]=U29sdmUoeCt5K3o9NSx4KzJ5PTYsei14PTMp&input[5]=U29sdmUoeF4yK3leMj0yNSwgeV4yPXheMiszKQ%3D%3D&input[6]=U29sdmUoeT14XjIsIHk9OC14XjIp&input[7]=U29sdmUoM3gteT0tMiwgMnheMi15PTAp&input[8]=U29sdmUoMy4zMzMweCsxNTkyMHkrMTAuMzMzej03OTUzLCAyLjIyMjB4KzE2LjcxMHkrOS42MTIwej0wLjk2NSwgLTEuNTYxMXgrNS4xNzkyeS0xLjY4NTV6PTIuNzE0KQ%3D%3D&input[9]=U29sdmUoeF42KzE2eF4zKzY0LHgp&input[10]=U29sdmUoc2luKDN4KStjb3MoM3gpPTAp&input[11]=U29sdmUoNHNpbih4KV4zKzJzaW4oeCleMi0yc2luKHgpPTEseCk%3D&input[12]=U29sdmUoMyp0YW4oeCleMj0xLHgp&input[13]=U29sdmUoZXhwKDN4KT0yLHgp&input[14]=U29sdmUodGFuKHgpXjI9Myk%3D&input[15]=U29sdmUobG4oeCk9MSx4KQ%3D%3D&input[16]=U29sdmUoM3Npbih4KStleHAoeCk9Mix4LFstMkBwaSwyQHBpXSk%3D&input[17]=U29sdmUoYXNpbih4KT1AcGkvNCx4KQ%3D%3D&input[18]=U29sdmUoU2koeCk9MS8yKQ%3D%3D&input[19]=U29sdmUoQmVzc2VsSigwLHgpPTIvMyk%3D&input[20]=U29sdmUoTGVnZW5kcmVQKDMseCktMT0wKQ%3D%3D&input[21]=U29sdmUoR2FtbWEoeCk9NTA0MCx4LFsxLDEwXSk%3D)


## 线性方程


>   ```math
>   Solve(3x+5=0, x)
>   ```
>   $ -1.666666666667 $


>   ```math
>   Solve(3x+5)
>   ```
>   $ -1.666666666667 $


## 一元二次方程



>   ```math
>   Solve(x^2-5x+6=0)
>   ```
>   $ [2,3] $



>   ```math
>   Solve(1, -5, 6)
>   ```
>   $ [2,3] $

## 解方程组


>   ```math
>   Solve(x+y+z=5, x+2y=6, z-x=3)
>   ```
>   + x: -0.666666666667
>   + y: 3.333333333333
>   + z: 2.333333333333



>   ```math
>   Solve(x^2+y^2=25, y^2=x^2+3)
>   ```
>   + x
>      - $ -\sqrt {1 1 }  $
>      - $ \sqrt {1 1 }  $
>   + y
>     - $ \sqrt {1 4 }  $
>     - $ -\sqrt {1 4 }  $


>   ```math
>   Solve(y=x^2, y=8-x^2)
>   ```
>   + x
>      - $ 2  $
>      - $ -2  $
>   + y : $ 4 $



>   ```math
>   Solve(3x-y=-2, 2x^2-y=0)
>   ```
>   + x
>      - $ - \frac { 1 } { 2 }   $
>      - $ 2  $
>   + y
>     - $ \frac { 1 } { 2 }    $
>     - $ 8  $



>   ```math
>   Solve(3.3330x+15920y+10.333z=7953, 2.2220x+16.710y+9.6120z=0.965, -1.5611x+5.1792y-1.6855z=2.714)
>   ```
>   + x: $ 1    $
>   + y
>     - $ \frac { 1 } { 2 }    $
>   + z: $ -1    $


## 其它示例



>   ```math
>   Solve(x^6+16x^3+64, x)
>   ```
>   $ [-2,-2,-i \sqrt{3}+1,-i \sqrt{3}+1, i \sqrt{3}+1, i \sqrt{3}+1] $


>   ```math
>   Solve(sin(3x)+cos(3x)=0)
>   ```
>   $ \left[\frac{\pi}{4}, \frac{7 \pi}{12}, \frac{11 \pi}{12}, \frac{5 \pi}{4}, \frac{19 \pi}{12}, \frac{23 \pi}{12}\right]  $

 
>   ```math
>   Solve(4sin(x)^3+2sin(x)^2-2sin(x)=1, x)
>   ```
>   $ \left[\frac{\pi}{4}, \frac{3 \pi}{4}, \frac{7 \pi}{6}, \frac{5 \pi}{4}, \frac{7 \pi}{4}, \frac{11 \pi}{6}\right] $



 
>   ```math
>   Solve(3*tan(x)^2=1, x)
>   ```
>   $ \left[\frac{\pi}{6}, \frac{5 \pi}{6}, \frac{7 \pi}{6}, \frac{11 \pi}{6}\right] $


 
>   ```math
>   Solve(exp(3x)=2, x)
>   ```
>   $ \frac{1}{3} \ln (2) $

 
>   ```math
>   Solve(tan(x)^2=3)
>   ```
>   $ \left[\frac{\pi}{3}, \frac{2 \pi}{3}, \frac{4 \pi}{3}, \frac{5 \pi}{3}\right] $

 
>   ```math
>   Solve(ln(x)=1, x)
>   ```
>   $ e $

 
>   ```math
>   Solve(3sin(x)+exp(x)=2, x, [-2@pi, 2@pi])
>   ```
>   $ [-1.768270574843 \pi,-1.229298744332 \pi, 0.077583802413 \pi] $

 
>   ```math
>   Solve(asin(x)=@pi/4, x)
>   ```
>   $ \frac{\sqrt{2}}{2} $

## 特殊函数

>   ```math
>   Solve(Si(x)=1/2)
>   ```
>   $ [0.507192780789,...] $

>   ```math
>   Solve(BesselJ(0, x)=2/3)
>   ```
>   $ [1.208942379514,...]$

>   ```math
>   Solve(LegendreP(3, x)-1=0)
>   ```
>   $ \left[\frac{i \sqrt{15}}{10}-\frac{1}{2},-\frac{i \sqrt{15}}{10}-\frac{1}{2}, 1\right] $

>   ```math
>   Solve(Gamma(x)=5040, x, [1, 10])
>   ```
>   $ 8 $

## 相关函数


[Eval](E/Eval)
[SolveSystem](S/SolveSystem)