## TrigExpand(expression)

将三角函数中出现的和和整数倍数进行分解，并将三角函数的乘积展开为幂的和。


## 举例  
[在Mathstudio上浏览](http://mathstud.io/?input[0]=VHJpZ0V4cGFuZChzaW4oYStiKSk%3D&input[1]=VHJpZ0V4cGFuZChjb3MoeF4yK3NxcnQoeSkpKQ%3D%3D&input[2]=VHJpZ0V4cGFuZCh0YW5oKHgteSkp&input[3]=VHJpZ0V4cGFuZChzaW4oMngpKQ%3D%3D&input[4]=VHJpZ0V4cGFuZChjb3MoMngpKQ%3D%3D&input[5]=VHJpZ0V4cGFuZCh0YW4oMngpKQ%3D%3D&input[6]=VHJpZ0V4cGFuZCh0YW5oKDJ4KSk%3D&input[7]=VHJpZ0V4cGFuZChzaW4oM3gpKQ%3D%3D&input[8]=VHJpZ0V4cGFuZChjb3MoNHgpKQ%3D%3D&input[9]=VHJpZ0V4cGFuZChzaW4oKHgvMysyeSkvMykp)


## 两个角的和或差



>   ```math
>   TrigExpand(sin(a+b))
>   ```
>   $ \cos (a) \sin (b)+\cos (b) \sin (a) $



>   ```math
>   TrigExpand(cos(x^2+sqrt(y)))
>   ```
>   $ -\sin \left(x^{2}\right) \sin (\sqrt{y})+\cos \left(x^{2}\right) \cos (\sqrt{y}) $


>   ```math
>   TrigExpand(tanh(x-y))
>   ```
>   $ -\frac{\cosh (x) \sinh (y)}{-\sinh (x) \sinh (y)+\cosh (x) \cosh (y)}+\frac{\cosh (y) \sinh (x)}{-\sinh (x) \sinh (y)+\cosh (x) \cosh (y)} $


## 二倍角

>   ```math
>   TrigExpand(sin(2x))
>   ```
>   $ 2 \cos (x) \sin (x) $


>   ```math
>   TrigExpand(cos(2x))
>   ```
>   $ -\sin (x)^{2}+\cos (x)^{2} $


>   ```math
>   TrigExpand(tan(2x))
>   ```
>   $ \frac{2 \cos (x) \sin (x)}{-\sin (x)^{2}+\cos (x)^{2}} $


>   ```math
>   TrigExpand(tanh(2x))
>   ```
>   $ \frac{2 \cosh (x) \sinh (x)}{\cosh (x)^{2}+\sinh (x)^{2}} $

## 多倍角

>   ```math
>   TrigExpand(sin(3x))
>   ```
>   $ -\sin (x)^{3}+3 \cos (x)^{2} \sin (x) $


>   ```math
>   TrigExpand(cos(4x))
>   ```
>   $ \cos (x)^{4}+\sin (x)^{4}-6 \cos (x)^{2} \sin (x)^{2} $


## 组合 

>   ```math
>   TrigExpand(sin((x/3+2y)/3))
>   ```
>   $ -\sin \left(\frac{x}{9}\right) \sin \left(\frac{y}{3}\right)^{2}+\sin \left(\frac{x}{9}\right) \cos \left(\frac{y}{3}\right)^{2}+2 \cos \left(\frac{x}{9}\right) \cos \left(\frac{y}{3}\right) \sin \left(\frac{y}{3}\right) $


## 相关函数

[ExpConvert](E/ExpConvert)

[TrigConvert](T/TrigConvert)

[TrigReduce](T/TrigReduce)

