# Transformada de Laplace
## 1.  ¿Que es la transformada de Laplace?
Es una tecnica para resolver ecuaciones diferenciales con condiciones iniciales, por medio de un cambio de espacio geometrico del dominio del tiempo hacia el dominio de la frecuecia compleja.
A continuacion vemos como es ecuacion de la transformada:
$$\mathcal{L}\{f(t)\}=\int_0^{+\infty} e^{-s t} f(t) d t$$
## 2. Transformada inversa de Laplace
La trasnformada iversa nos ayuda a pasar del dominio de la frecuencia compleja a el diminio del tiempo para que nuestro reltado se pueda manejar mas facil.
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
## 4. Transformada de una funcion
$\mathcal{L}[f(x)]=F(s)$
## 5. Transformada de la deriavda
$\mathcal{L}[f'(x)]=sF(s)-f(0)$

$\mathcal{L}[f''(x)]=s^{2}F(s)-sf'(0)$

$\mathcal{L}[f^{n}(x)]=s^{n}F(s)-s^{n-1}f(0)-...-sf^{n-1}-f^{n}$
## Referencias
1. [https://www.uv.mx/personal/aherrera/files/2014/04/18.-PROPIEDADES-DE-LA-TRANSFORMADA-DE-LAPLACE1.pdf]
2.(https://caminos.udc.es/info/asignaturas/master_iccp/miccp511/images/Imagenes_complementarios/resumen_laplace.pdf)
