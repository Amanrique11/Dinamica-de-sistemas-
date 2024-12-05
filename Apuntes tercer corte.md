# 1.Funcion de Transferencia 
## 1.1 Definicion y conceptos clave:
la funcion de transferencia describe la relacion entre la entrada y la salida de un sistema lineal en el dominio de Laplace. Se expresa como:

$$G(s)=\frac{Y(s)}{U(s)}$$

## 1.2 Clasificacion de las funciones de transferencia
1. Impropias: Grado de numerador $$N(s)$$ > grado del denominador $$D(s)$$.
2. Estrictamente propias: Grado $$D(s)$$ > grado de $$N(s)$$.
3. Bipropias: Grados iguales en $$N(s)$$ y $$D(s)$$.
## 1.3 Zeros y Polos
Zeros: Son los valores de $$s$$ que hacen cero el numerador $$N(s)$$ de la funcion de transferenci $$G(s)$$
Polos: Son los valores de $$s$$ que hacen cero el denominador $$D(s)$$ de $$G(s)$$, lo que hace la funcion de transferencia tienda a infinito.
## 1.4 Representacion en el plano complejo
Eje real: Indica componentes relacionadas con la rapidez de la repuesta del sistema.
*Polos en el semiplano izquierdo: La funcion de transferencia es estable.
*Polos en el semiplano derecho: La funcion es inestable.
Eje imaginario: Indica componentes oscilatorias de la respuesta.
## 1.5 Teorema del valor final
Permite calcular el valor final de la salida:
$$\lim_{t\rightarrow\infty}y(t)=\lim_{s\rightarrow0}Y(s)$$

💡**Ejemplo 1:** Dada la ecucion diferencial:
$$y''(t)+3y'(t)+2y(t)=3u'(t)+3u(t)$$
Solucion:
1. Aplicar transformada de Laplace:
   $$(s^2+3s+2)Y(s)=(3s+3)U(s)$$

    $$G(s)=\frac{Y(s)}{U(s)}=\frac{3s+3}{s^2+3s+2}$$

    Polos: $$s^2+3s+s=0$$

   $$s_1=-1, s_2=-2$$

   Zeros= $$3s+3=0$$

   $$s=1$$

   # 2. Modelamiento por diagrama de bloques
   ## 2.1 Definicion
   Un diagrama de bloques es una representacion grafica de un sistema dinamico mediante  bloques funcionales que describen relaciones matematicas. Las flechas indican el flujo de señales.
   ## 2.2 Componentes de un diagrma de bloques:
   1. Bloques funcionales: Realizan operacions matematicas.
   2. Puntos de suma: Permite sumar o restar señales.
   3. Ramificaniones: Dividen una señal para enviarla a varios bloques.
   ## 2.3 Modelos comunes:
   1. Motores DC: Incluyen corriente de campo y armadura,torque y velocidad angular.
   2. Elementos mecanicos: Engranajes y poleas modifican torque y velocidad.
  ## 2.3 Algebra de bloques:
  El algebra de bloques se utiliza para simplificar diagramas complejos, cambiando funciones de transferencia individuales.
