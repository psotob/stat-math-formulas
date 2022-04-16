
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Derivadas

### Definición

------------------------------------------------------------------------

## Antiderivadas (Integrales)

![F](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;F "F"),
denominada **antiderivada** de
![f](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;f "f")
en el intervalo
![I](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;I "I")
si
![D_xF(x)=f(x)](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;D_xF%28x%29%3Df%28x%29 "D_xF(x)=f(x)")
en
![I](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;I "I");
donde
![F(x) = f(x)](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;F%28x%29%20%3D%20f%28x%29 "F(x) = f(x)"),
![\\forall x \\in I](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cforall%20x%20%5Cin%20I "\forall x \in I").

De esto se desprende:

-   ![D_x\\int f(x)dx = f(x)](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;D_x%5Cint%20f%28x%29dx%20%3D%20f%28x%29 "D_x\int f(x)dx = f(x)")

-   ![\\int\_{}{}D_xf(x)dx=f(x)+C](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7DD_xf%28x%29dx%3Df%28x%29%2BC "\int_{}{}D_xf(x)dx=f(x)+C")

![](README_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->

### Teorema A. Regla de la potencia

Si
![r](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;r "r")
es cualquier número racional, excepto -1, entonces

![
\\int\_{}{}x^rdx=\\frac{x^{r+1}}{r+1}+C
](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%0A%5Cint_%7B%7D%7B%7Dx%5Erdx%3D%5Cfrac%7Bx%5E%7Br%2B1%7D%7D%7Br%2B1%7D%2BC%0A "
\int_{}{}x^rdx=\frac{x^{r+1}}{r+1}+C
")

Se deducen dos cosas:

-   Caso
    ![r = 0](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;r%20%3D%200 "r = 0"):

    ![
    \\int\_{}{}1dx=x+C
    ](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%0A%5Cint_%7B%7D%7B%7D1dx%3Dx%2BC%0A "
    \int_{}{}1dx=x+C
    ")

-   Como no se especificó ningún intervalo, es tácito que la integral es
    válidad solo en los intervalos donde
    ![x^r](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;x%5Er "x^r")
    está definida.

    -   Si
        ![r \< 0](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;r%20%3C%200 "r < 0"),
        entonces el intervalo
        ![I](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;I "I")
        no debe incluir
        ![x = 0](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;x%20%3D%200 "x = 0").

    -   A esta integral donde no se le define el intervalo
        ![I](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;I "I")
        se le denomina **integral indefinida**, en lugar de
        antiderivada.

### Teorema B. Integral de senos y cosenos

![
\\int\_{}{}sen(x)dx=-cox(x)+C
](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%0A%5Cint_%7B%7D%7B%7Dsen%28x%29dx%3D-cox%28x%29%2BC%0A "
\int_{}{}sen(x)dx=-cox(x)+C
")

![
\\int\_{}{}cos(x)dx=sen(x)+C
](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%0A%5Cint_%7B%7D%7B%7Dcos%28x%29dx%3Dsen%28x%29%2BC%0A "
\int_{}{}cos(x)dx=sen(x)+C
")

### Teorema C. La integral definida es un operador lineal

Suponga que
![f](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;f "f")
y
![g](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;g "g")
tienen antiderivadas (integrales indefinidas) y sea
![k](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;k "k")
una constante. Entonces:

-   ![\\int\_{}{}kf(x)dx=k\\int\_{}{}f(x)dx](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7Dkf%28x%29dx%3Dk%5Cint_%7B%7D%7B%7Df%28x%29dx "\int_{}{}kf(x)dx=k\int_{}{}f(x)dx")

-   ![\\int\_{}{}\[f(x) + g(x)\]dx = \\int\_{}{}f(x)dx + \\int\_{}{}g(x)dx](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7D%5Bf%28x%29%20%2B%20g%28x%29%5Ddx%20%3D%20%5Cint_%7B%7D%7B%7Df%28x%29dx%20%2B%20%5Cint_%7B%7D%7B%7Dg%28x%29dx "\int_{}{}[f(x) + g(x)]dx = \int_{}{}f(x)dx + \int_{}{}g(x)dx")

-   ![\\int\_{}{}\[f(x)-g(x)\]dx = \\int\_{}{}f(x)dx - \\int\_{}{}g(x)dx](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7D%5Bf%28x%29-g%28x%29%5Ddx%20%3D%20%5Cint_%7B%7D%7B%7Df%28x%29dx%20-%20%5Cint_%7B%7D%7B%7Dg%28x%29dx "\int_{}{}[f(x)-g(x)]dx = \int_{}{}f(x)dx - \int_{}{}g(x)dx")

### Teorema D. Regla generalizada de la potencia

-   ![\\int\_{}{}\[g(x)\]^rg'(x)dx = \\frac{\[g(x)\]^{r+1}}{r+1}+C](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7D%5Bg%28x%29%5D%5Erg%27%28x%29dx%20%3D%20%5Cfrac%7B%5Bg%28x%29%5D%5E%7Br%2B1%7D%7D%7Br%2B1%7D%2BC "\int_{}{}[g(x)]^rg'(x)dx = \frac{[g(x)]^{r+1}}{r+1}+C")

### Extras

-   ![\\int\_{}{}\[f(x)g'(x) + g(x)f'(x)\]dx = f(x)g(x) + C](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7D%5Bf%28x%29g%27%28x%29%20%2B%20g%28x%29f%27%28x%29%5Ddx%20%3D%20f%28x%29g%28x%29%20%2B%20C "\int_{}{}[f(x)g'(x) + g(x)f'(x)]dx = f(x)g(x) + C")

-   ![\\int\_{}{}\\frac{g(x)f'(x) - f(x)g'(x)}{g^2(x)}dx = \\frac{f(x)}{g(x)} + C](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Cint_%7B%7D%7B%7D%5Cfrac%7Bg%28x%29f%27%28x%29%20-%20f%28x%29g%27%28x%29%7D%7Bg%5E2%28x%29%7Ddx%20%3D%20%5Cfrac%7Bf%28x%29%7D%7Bg%28x%29%7D%20%2B%20C "\int_{}{}\frac{g(x)f'(x) - f(x)g'(x)}{g^2(x)}dx = \frac{f(x)}{g(x)} + C")

## Sumatorias

![
\\sum\_{i = 1}^{n}a_i = a_1 + a_2 + a_3 + ... + a_n
](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%0A%5Csum_%7Bi%20%3D%201%7D%5E%7Bn%7Da_i%20%3D%20a_1%20%2B%20a_2%20%2B%20a_3%20%2B%20...%20%2B%20a_n%0A "
\sum_{i = 1}^{n}a_i = a_1 + a_2 + a_3 + ... + a_n
")

### Teorema A. Linealidad de ![\\sum](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum "\sum")

Si c es una constante, entonces

-   

    ![\\sum\_{i = 1}^{n}ca_i = c\\sum\_{i=1}^{n}a_i](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%20%3D%201%7D%5E%7Bn%7Dca_i%20%3D%20c%5Csum_%7Bi%3D1%7D%5E%7Bn%7Da_i "\sum_{i = 1}^{n}ca_i = c\sum_{i=1}^{n}a_i")

-   

    ![\\sum\_{i=1}^{n}(a_i+b_i) = \\sum\_{i=1}^{n}a_i + \\sum\_{i=1}^{n}b_i](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%28a_i%2Bb_i%29%20%3D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7Da_i%20%2B%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7Db_i "\sum_{i=1}^{n}(a_i+b_i) = \sum_{i=1}^{n}a_i + \sum_{i=1}^{n}b_i")

-   

    ![\\sum\_{i=1}^{n}(a_i - b_i) = \\sum\_{i=1}^{n}a_i - \\sum\_{i=1}^{n}b_i](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%28a_i%20-%20b_i%29%20%3D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7Da_i%20-%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7Db_i "\sum_{i=1}^{n}(a_i - b_i) = \sum_{i=1}^{n}a_i - \sum_{i=1}^{n}b_i")

### Formulas de sumatorias conocidas

-   

    ![\\sum\_{i=1}^{n}(a\_{i+1} - a_i) = a\_{n+1} - a_1](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%28a_%7Bi%2B1%7D%20-%20a_i%29%20%3D%20a_%7Bn%2B1%7D%20-%20a_1 "\sum_{i=1}^{n}(a_{i+1} - a_i) = a_{n+1} - a_1")

-   

    ![\\sum\_{i=1}^{n}\[(i + 1)^2 - i^2\] = (n+1)^2-1](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5B%28i%20%2B%201%29%5E2%20-%20i%5E2%5D%20%3D%20%28n%2B1%29%5E2-1 "\sum_{i=1}^{n}[(i + 1)^2 - i^2] = (n+1)^2-1")

-   

    ![\\sum\_{i=1}^{n}i = \\frac{n(n+1)}{2}](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7Di%20%3D%20%5Cfrac%7Bn%28n%2B1%29%7D%7B2%7D "\sum_{i=1}^{n}i = \frac{n(n+1)}{2}")

-   

    ![\\sum\_{i=1}^{n}i^2 = \\frac{n(n+1)(2n+1)}{6}](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7Di%5E2%20%3D%20%5Cfrac%7Bn%28n%2B1%29%282n%2B1%29%7D%7B6%7D "\sum_{i=1}^{n}i^2 = \frac{n(n+1)(2n+1)}{6}")

-   

    ![\\sum\_{i=1}^{n}i^3 = \[\\frac{n(n+1)}{2}\]^2](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7Di%5E3%20%3D%20%5B%5Cfrac%7Bn%28n%2B1%29%7D%7B2%7D%5D%5E2 "\sum_{i=1}^{n}i^3 = [\frac{n(n+1)}{2}]^2")

-   

    ![\\sum\_{i=1}^{n}i^4 = \\frac{n(n+1)(2n+1)(3n^2 + 3n - 1)}{30}](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D&space;%5Cbg_white&space;%5Csum_%7Bi%3D1%7D%5E%7Bn%7Di%5E4%20%3D%20%5Cfrac%7Bn%28n%2B1%29%282n%2B1%29%283n%5E2%20%2B%203n%20-%201%29%7D%7B30%7D "\sum_{i=1}^{n}i^4 = \frac{n(n+1)(2n+1)(3n^2 + 3n - 1)}{30}")
