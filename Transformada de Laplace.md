# Transformada de Laplace
## 1.  ¿Que es la transformada de Laplace?
Es una tecnica para resolver ecuaciones diferenciales con condiciones iniciales, por medio de un cambio de espacio geometrico del dominio del tiempo hacia el dominio de la frecuecia compleja.
A continuacion vemos como es ecuacion de la transformada:
$$\mathcal{L}\{f(t)\}=\int_0^{+\infty} e^{-s t} f(t) d t$$
## 2. Transformada inversa de Laplace
La trasnformada iversa nos ayuda a pasar del dominio de la frecuencia compleja a el diminio del tiempo para que nuestro reltado se pueda manejar mas facil.
Si las funciones son simples utilizar la tabla de transformadas. Si las funciones son una combinacion o una composicion de varias funciones se debe realizar una expansion de fracciones parciales para obtner una suma de funciones mucho mas simple que se puedan encontrar en las tablas de transfromadas.
$$f=\mathcal{L}^{-1}(F)$$
## 3. Propiedades de la transformada de Laplace
### 3.1 Propiedad de la linealidad de la transformada de Laplpace
La transformacion de Laplace es lineal, esto es, dadas dos funciones f, g ∈ E se verifica.
$\mathcal{L}\left[C_1 f(t)+C_2 g(t)\right]=C_1 \mathcal{L}[f(t)]+C_2 \mathcal{L}[g(t)]$ donde C1 y C2 pertenece a los relaes.
### 3.2 Proppiedad de cambio de escala
Sea f(t) ∈ E. La funcion g(t) = f(αt) tambien pertenece a E y se verifica.
$$\mathcal{L}[g(t)] \equiv G(s)=\frac{1}{\alpha} F\left(\frac{s}{\alpha}\right)$$
### 3.3 Propiedad de desplazamiento en frecuencia
Sea f(t) ∈ E. La funcion $g(t)=e^{\omega t} f(t)$ tambien pertenece a E y se verifica.
$$\mathcal{L}\{f(t)\}=\int_0^{+\infty} e^{-s t} f(t) d t$$
### 3.4 Propiedad de desplazamiento en el tiempo
Sea f(t) ∈ E. La funcion $g(t)=f(t-\widetilde{T}) u(t-\widetilde{T})$ tambien pertenece a E y se verifica.
$\mathcal{L}[g(t)] \equiv G(s)=e^{-T s} F(s)$
![ecuacion](https://github.com/user-attachments/assets/a43b0964-61cb-4715-9590-31ac21478e3d)
## 4. Transformadas 
### 4.1 Transformada de una funcion
$\mathcal{L}[f(t)]=F(s)$
### 4.2 Transformada de la derivada
$\mathcal{L}[f'(t)]=sF(s)-f(0)$

$\mathcal{L}[f''(t)]=s^{2}F(s)-sf'(0)$

$\mathcal{L}[f^{n}(t)]=s^{n}F(s)-s^{n-1}f(0)-...-sf^{n-1}-f^{n}$
### 4.3 Transformada de la integral
$\mathcal{L}[\int f(t)]=\frac{1}{s}F(s)$
### 4.4 Tabla de transformadas
![Tabla de transformadas](https://github.com/user-attachments/assets/740994db-c24b-4de1-8525-7f45ccda0fd7)
Figura 1. Tabla de las transformadas
#  Ejercicios 
## 📚 1. Calcular la transformada de Laplace de $f(t)=2t^{3}+e^{5t}+\sin{3t}$
$\mathcal{L}[f(t)]=2\mathcal{L}[t^{3}]+\mathcal{L}[e^{3t}+4\mathcal{L}[sin{3t}]$

$\mathcal{L}[f(t)]=2\frac{6}{s^{4}}+\frac{1}{s-5}+4\frac{3}{s^{2}+9}$
## 📚 2. Hallar $f(t)$  de $\frac{8s}{(s^{2}+1)^{2}}$
$\mathcal{L}^{-1}[\frac{8s}{(s^{2}+1)^{2}}]=8\frac{1}{s^{2}+1}\frac{s}{s^{2}+1}$

$\mathcal{L}^{-1}[\frac{8s}{(s^{2}+1)^{2}}] = 8sin{t}cos{t}$
## Referencias
1. [https://www.uv.mx/personal/aherrera/files/2014/04/18.-PROPIEDADES-DE-LA-TRANSFORMADA-DE-LAPLACE1.pdf]
   
2.(https://caminos.udc.es/info/asignaturas/master_iccp/miccp511/images/Imagenes_complementarios/resumen_laplace.pdf)

3.https://cms.dm.uba.ar/academico/materias/2docuat2022/matematica4/Mate4-Laplace.pdf
