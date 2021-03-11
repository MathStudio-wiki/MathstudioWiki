##  SimplifyFunction(expression)

将三角函数和指数函数简化为带有简化参数的函数。


## 举例

[在Mathstudio上浏览](http://mathstud.io/?input[0]=U2ltcGxpZnlGdW5jdGlvbihsbih4KSpsbigxL3gpKQ%3D%3D&input[1]=U2ltcGxpZnlGdW5jdGlvbihleHAobG4oeCkqbG4oMS94KSkp&input[2]=U2ltcGxpZnlGdW5jdGlvbihIeXBlcmdlb21fMkYxKDEsMSwzLzIsc2luKHopXjIpLHop&input[3]=U2ltcGxpZnlGdW5jdGlvbihleHAobG4oYSkqbG4oeCkpKQ%3D%3D&input[4]=U2ltcGxpZnlGdW5jdGlvbihleHAoYUBpK3grbG4oeSkpK2V4cChhKkBwaSt4K2xuKHkpKS1leHAoQHBpKkBpKm4reCtsbih5KSthc2luaCh6KSkp&input[5]=U2ltcGxpZnlGdW5jdGlvbihleHAoYXRhbmgoeCkrYWNvdGgoeCkpKQ%3D%3D&input[6]=U2ltcGxpZnlGdW5jdGlvbihleHAoYWNvc2goeCkrYXNpbmgoeCkpKQ%3D%3D&input[7]=U2ltcGxpZnlGdW5jdGlvbihleHAoYWNvc2goeCkvMikp&input[8]=U2ltcGxpZnlGdW5jdGlvbihleHAoM3QtQGlAcGkvMis0eC8zKSk%3D&input[9]=U2ltcGxpZnlGdW5jdGlvbihleHAoLUBpQHBpLzIpKQ%3D%3D&input[10]=U2ltcGxpZnlGdW5jdGlvbihleHAoM3gqbG4odCktNGxuKHQpL3grYSpiKnQtYS9sbih0KSkp&input[11]=U2ltcGxpZnlGdW5jdGlvbigxNC8oMngrNiktNHgvKDJ4KzYpLHgp&input[12]=U2ltcGxpZnlGdW5jdGlvbihzaW4oLTN5KkBwaSs0eCpAcGkpK3NpbigtNHgqQHBpKzN5KkBwaSkp)




>   ```math
>   SimplifyFunction(ln(x)*ln(1/x))
>   ```
>   $ -\ln (x)^{2} $



>   ```math
>   SimplifyFunction(exp(ln(x)*ln(1/x)))
>   ```
>   $ x^{\ln (1 / x)} $

>   ```math
>   SimplifyFunction(Hypergeom_2F1(1, 1, 3/2, sin(z)^2), z)
>   ```
>   $ zcsc(z)sec(z) $

>   ```math
>   SimplifyFunction(exp(ln(a)*ln(x)))
>   ```
>   $ a^{\ln (x)} $


>   ```math
>   SimplifyFunction(exp(a@i+x+ln(y))+exp(a*@pi+x+ln(y))-exp(@pi*@i*n+x+ln(y)+asinh(z)))
>   ```
>   $ y e^{i a+x+} y e^{\pi a+x}-(-1)^{n} e^{x} y\left(z+\sqrt{z^{2}+1}\right) $



>   ```math
>   SimplifyFunction(exp(atanh(x)+acoth(x)))
>   ```
>   $ \frac{x+1}{\sqrt{x-1} \sqrt{-x+1}} $

>   ```math
>   SimplifyFunction(exp(acosh(x)+asinh(x)))
>   ```
>   $ \left(x+\sqrt{x^{2}+1}\right)(x+\sqrt{x-1} \sqrt{x+1}) $

>   ```math
>   SimplifyFunction(exp(acosh(x)/2))
>   ```
>   $ \sqrt{x+\sqrt{x-1}} \sqrt{x+1} $




>   ```math
>   SimplifyFunction(exp(3t-@i@pi/2+4x/3))
>   ```
>   $ -i e^{3 t+4 x / 3} $


>   ```math
>   SimplifyFunction(exp(-@i@pi/2))
>   ```
>   $ -1i $



>   ```math
>   SimplifyFunction(exp(3x*ln(t)-4ln(t)/x+a*b*t-a/ln(t)))
>   ```
>   $ t(-4 / x+3 x) e \cdot a / \ln (t)+a b t$

>   ```math
>   SimplifyFunction(14/(2x+6)-4x/(2x+6), x)
>   ```
>   $ \frac{14}{2 x+6}-\frac{4 x}{2 x+6} $

>   ```math
>   SimplifyFunction(sin(-3y*@pi+4x*@pi)+sin(-4x*@pi+3y*@pi))
>   ```
>   $ 0 $

