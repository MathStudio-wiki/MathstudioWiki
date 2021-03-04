## Sequence(f(x), x, start, end, [step], [start term], [number of terms])

以列表的形式返回序列。


## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=U2VxdWVuY2UoaSxpLDEsNSk%3D&input[1]=U2VxdWVuY2UoaV4yLGksMSw1KQ%3D%3D&input[2]=U2VxdWVuY2UoaSxpLDEsMTUsMik%3D&input[3]=U2VxdWVuY2UoMS9uXjIsbiwxLDEwKQ%3D%3D&input[4]=U2VxdWVuY2UoMS9uXjIsbiwxLDEwMCwxMCw0LDMp&input[5]=U2VxdWVuY2UoMS9uXjIsbiwxLDEwMCwxMCwtNCwzKQ%3D%3D&input[6]=U2VxdWVuY2UoMS9uXjIsbiwxLDEwMCwxMCwtNCk%3D)


>   ```math
>   Sequence(i, i, 1, 5)
>   ```
>   $\lbrack 1 , 2 , 3 , 4 , 5 \rbrack  $


>   ```math
>   Sequence(i^2, i, 1, 5)
>   ```
>   $[1,4,9,16,25]$


>   ```math
>   Sequence(i, i, 1, 15, 2)
>   ```
>   $[1,3,5,7,9,11,13,15]$


>   ```math
>   Sequence(1/n^2, n, 1, 10)
>   ```
>   $\lbrack 1 , \frac { 1 } { 4 } , \frac { 1 } { 1 6 } , \frac { 1 } { 1 6 } , \frac { 1 } { 2 5 } , \frac { 1 } { 4 9 } , \frac { 1 } { 4 9 } , \frac { 1 } { 8 4 } , \frac { 1 } { 1 0 0 } \rbrack  $


>   ```math
>   Sequence(1/n^2, n, 1, 100, 10, 4, 3)
>   ```
>   $\lbrack \frac { 1 } { 9 6 1 } , 0 . 0 0 5 9 4 8 9 8 , 0 . 0 3 8 4 4 6 7 2 \rbrack  $



>   ```math
>   Sequence(1/n^2, n, 1, 100, 10, -4, 3)
>   ```
>   $[0.000268744961,0.000384467512,0.000594883998]$

## Show sequence in reversed order

>   ```math
>   Sequence(1/n^2, n, 1, 100, 10, -4)
>   ```
>   $\left[0.000268744961,0.000384467512,0.000594883998, \frac{1}{961}, \frac{1}{441}, \frac{1}{121}, 1\right]$

