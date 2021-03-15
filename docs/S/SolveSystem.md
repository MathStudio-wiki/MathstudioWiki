## SolveSystem(equations, [variables], [guesses])

用数值方法求解非线性方程组。


## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=U29sdmVTeXN0ZW0oW3grMnk9MSwgeF4yK3leMj0xMF0p&input[1]=U29sdmVTeXN0ZW0oW3heMit5XjI9MjUsIHleMj14XjIrM10p&input[2]=U29sdmVTeXN0ZW0oW3heMit5XjI9MjUsIHleMj14XjIrM10sIFt4LHldLCBbLTIsMF0p&input[3]=U29sdmVTeXN0ZW0oW3heMisyeV4yK2Nvcyh6KS13XjI9MCwgM3heMit5XjIrc2luKHopXjItd14yPTAsIC0yeF4yLXleMi1jb3Moeikrd14yPTAsIC14XjItMnleMi1jb3MoeileMit3XjI9MF0sW3cseCx5LHpdLFstMSwxLDAsMF0p)



>   ```math
>	SolveSystem([x+2y=1, x^2+y^2=10])
>   ```
>   <table>
>       <tr>
>           <th>$x$</th>
>           <th>$y$</th>
>       </tr>
>       <tr>
>           <th>$3$</th>
>           <th>$-1$</th>
>       </tr>
>   </table>


>   ```math
>	SolveSystem([x^2+y^2=25, y^2=x^2+3])
>   ```
>   <table>
>       <tr>
>           <th>$x$</th>
>           <th>$y$</th>
>       </tr>
>       <tr>
>           <th>$ \sqrt {1 1 }  $</th>
>           <th>$ \sqrt {1 4 }  $</th>
>       </tr>
>   </table>


>   ```math
>	SolveSystem([x^2+y^2=25, y^2=x^2+3], [x, y], [-2, 0])
>   ```
>   <table>
>       <tr>
>           <th>$x$</th>
>           <th>$y$</th>
>       </tr>
>       <tr>
>           <th>$ -\sqrt {1 1 }  $</th>
>           <th>$ \sqrt {1 4 }  $</th>
>       </tr>
>   </table>


>   ```math
>	SolveSystem([x^2+2y^2+cos(z)-w^2=0, 3x^2+y^2+sin(z)^2-w^2=0, -2x^2-y^2-cos(z)+w^2=0, -x^2-2y^2-cos(z)^2+w^2=0], [w, x, y, z], [-1, 1, 0, 0])
>   ```
>   <table>
>       <tr>
>           <th>$w$</th>
>           <th>$x$</th>
>           <th>$y$</th>
>           <th>$z$</th>
>       </tr>
>       <tr>
>           <th>$ -2 $</th>
>           <th>$ -1 $</th>
>           <th>$ 1 $</th>
>           <th>$ 0 $</th>
>       </tr>
>   </table>

## 相关函数

[Solve](S/Solve)