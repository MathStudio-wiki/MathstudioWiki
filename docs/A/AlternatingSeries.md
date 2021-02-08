### AlternatingSeries(*n, [terms]*)

***n***
<br>
实数

***[terms]***
<br>
返回的最大项数

### 描述

此函数以交错级数求出给定的实数的近似值。

结果以矩阵形式返回，第一行代表分子，第二行代表不同项的分母。

注意分子中的交替符号！

### 示例

[在MathStudio中浏览](http://mathstud.io/?input[0]=QWx0ZXJuYXRpbmdTZXJpZXMoQHBpLDcp&input[1]=QWx0ZXJuYXRpbmdTZXJpZXMobG4oMiksMTAp&input[2]=QWx0ZXJuYXRpbmdTZXJpZXMoc3FydCgyKSwxMCk%3D&input[3]=QWx0ZXJuYXRpbmdTZXJpZXMoLTMuMjMp&input[4]=QWx0ZXJuYXRpbmdTZXJpZXMoMTIzNDU2Nzg5Lzk4NzY1NDMyMSk%3D&input[5]=QWx0ZXJuYXRpbmdTZXJpZXMoLjY2Nik%3D&input[6]=QWx0ZXJuYXRpbmdTZXJpZXMoLjEyMTIxMjEyKQ%3D%3D&input[7]=QWx0ZXJuYXRpbmdTZXJpZXMoLjM2MzYzKQ%3D%3D)

> ```math
> AlternatingSeries(@pi, 7)
> ```
>
> |  3   |  1   | -1   |   1   |   -1    |     1      |     -1     |
> | :--: | :--: | ---- | :---: | :-----: | :--------: | :--------: |
> |  1   |  7   | 742  | 11978 | 3740526 | 1099482930 | 2202719155 |

> ```math
> AlternatingSeries(ln(2), 10)
> ```
>
> |  0   |  1   |  -1  |  1   |  -1  |  1   |  -1   |   1   |   -1   |    1    |
> | :--: | :--: | :--: | :--: | :--: | :--: | :---: | :---: | :----: | :-----: |
> |  1   |  1   |  3   |  30  | 130  | 1144 | 24376 | 10105 | 234330 | 1058658 |

> ```math
> AlternatingSeries(sqrt(2), 10)
> ```
>
> |  1   |  1   |  -1  |  1   |  -1  |  1   |  -1   |   1   |   -1   |    1     |
> | :--: | :--: | :--: | :--: | :--: | :--: | :---: | :---: | :----: | :------: |
> |  1   |  2   |  10  |  60  | 348  | 2030 | 11830 | 68952 | 401880 | 2 342330 |

> ```math
> AlternatingSeries(-3.237)
> ```
>
> |  -3  |  -1  |  1   |  -1  |  1   |
> | :--: | :--: | :--: | :--: | :--: |
> |  1   |  4   |  36  | 117  | 1300 |

> ```math
> AlternatingSeries(123456789/987654321)
> ```
>
> |  0   |  1   |    -1     |
> | :--: | :--: | :-------: |
> |  1   |  8   | 877914888 |

> ```math
> AlternatingSeries(.666)
> ```
>
> |  0   |  1   |  -1  | 1    | -1   |
> | :--: | :--: | :--: | ---- | ---- |
> |  1   |  1   |  2   | 6    | 1500 |

> ```math
> AlternatingSeries(.12121212)
> ```
>
> |  0   |  1   |  -1  | 1    | -1        |
> | :--: | :--: | :--: | ---- | --------- |
> |  1   |  8   | 200  | 825  | 825000000 |

> ```math
> AlternatingSeries(.36363)
> ```
>
> |  0   |  1   |  -1  |  1   |   -1    |      1      |      -1       |
> | :--: | :--: | :--: | :--: | :-----: | :---------: | :-----------: |
> |  1   |  2   |  6   |  33  | 157 091 | 408 051 013 | 2 857 300 000 |

### 相关函数

*[Convergents](C/Convergents), [cFrac](C/cFrac)*
