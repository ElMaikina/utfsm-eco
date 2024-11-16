# Economia 1
Tarea 3: Teoria de la Firma

* Miguel Soto Delgado
* Rol: 201973623-K

## Preguntas Conceptuales
1. Defina el beneficio de una firma, haciendo la diferencia entre la medición de un economista y un contador.

- El beneficio de una firma se define como la cantidad de dinero producido tras la venta de insumos o productos.
La diferencia principal entre la vision de los economistas y los contadores es que los economistas perciben
los beneficios de forma marginal, lo cual significa que buscan una proyeccion positiva a futuro y toman en
consideracion los costos implicitos y explicitos. Por otro lado, los contadores perciben el beneficio como 
la suma neta de dinero adquirida tras la venta. Esto en terminos matematicos se mide en base a la diferencia 
entre ingresos y costos totales.

2. En el equilibrio de largo plazo, la curva de oferta siempre tendrá pendiente positiva. Comente.

- En clases vimos que si los precios de los factores (costos) no cambian, entonces solo puede prevalecer un precio 
a largo plazo, independiente de como cambie la demanda, es decir, la curva de oferta a largo plazo es una linea 
horizontal en el nivel de este precio. La curva de oferta tambien puede tender a crecer o decrecer. En el primer 
caso, hace que aumenten los costos de los factores; la curva de oferta a LP tiene pendiente positiva. Finalmente, 
en el ultimo caso la entrada disminuye el costo de los factores; la curva de oferta a LP tiene pendiente negativa. 
Por ende la afirmacion es incorrecta.

3. La relación entre precio y calidad de un bien no es clara, es decir, un bien de peor calidad no necesariamente 
es más barato.

- Esto es evidentemente falso, vimos en clases de que el nivel de calidad es parte del factor que maximiza
el binestar del comprador y se puede formular como modelo matematico.

4. ¿Si una firma decidiera mantenerse en el mercado en el largo plazo, qué condición debería cumplir y por qué?

- Para que una firma se mantenga en el mercado en el largo plazo, debe ser capaz de cubrir al menos sus costos 
totales, lo que incluye tanto los costos explícitos como los costos de oportunidad. Esto significa que debe obtener 
un beneficio económico igual a cero, lo que es suficiente para que los propietarios de la firma consideren que su 
inversión es rentable en comparación con otras alternativas.

5. ¿Qué tipo de rendimientos tiene la firma con función de producción F(K, L) = AK^0.6L^0.45? Demuéstrelo.

- Tendria una funcion de produccion de tipo Cobb-Douglas. Para determinar el tipo de rendimientos, se puede analizar 
la función de producción. Si se duplica la cantidad de todos los insumos (K y L), se debe observar si la producción 
se duplica, aumenta más o menos. En este caso, al aplicar el teorema de homogeneidad, se puede ver que la suma de los 
exponentes (0.6 + 0.45 = 1.05) es mayor que 1, lo que indica que la firma experimenta rendimientos crecientes a escala.

6. Tanto en el corto como en el largo plazo, una firma puede modificar sus factores en aras de incrementar o 
disminuir producción. Comente.

- En el corto plazo, las firmas pueden ajustar la cantidad de insumos variables (como el trabajo) para aumentar 
o disminuir la producción, mientras que los insumos fijos (como el capital) son constantes. En el largo plazo, 
las firmas pueden ajustar todos los factores de producción, incluyendo el capital, lo que les permite adaptarse 
completamente a las condiciones del mercado y optimizar su producción según la demanda.

## Preguntas Matematicas

### Pregunta 2a: Precio y cantidad de equilibrio

Dada la función de costos totales de largo plazo de cada firma:

$$C(x) = 5^3 + 12x + 10000$$

Y la función de demanda del mercado:

$$X(p) = 4224 − 2p$$

Para encontrar el precio y la cantidad de equilibrio, primero necesitamos encontrar la función de ingreso total (IT) y la 
función de ingreso marginal (IM).

1. Función de ingreso total (IT):

$$IT = p * x$$

Para encontrar p en términos de x, despejamos p de la función de demanda:

$$p = \frac{4224 − x}{2}$$

Entonces, la función de ingreso total es:

$$IT = \frac{4224 − x}{2} * x = \frac{4224x − x^2}{2}$$

2. Función de ingreso marginal (IMg):

Derivamos la función de ingreso total respecto a x:

$$IMg = \frac{d(IT)}{dx} = \frac{d}{dx} (\frac{4224x − x^2}{2}) = 2112 - x$$

3. Función de costo marginal (CM):

Derivamos la función de costo total respecto a x:

$$CMg = \frac{d(C)}{dx} = \frac{d}{dx} (5^3 + 12x + 10000) = 15x^2 + 12$$

4. Condición de equilibrio:

En equilibrio, el ingreso marginal es igual al costo marginal:

$$IM = CM$$

Entonces, igualamos las dos expresiones:

$$2112 − x = 15x^2 + 12$$

Reorganizamos la ecuación:

$$15x^2 + x − 2100 = x^2 + \frac{x}{15} − \frac{2100}{15} = 0$$

5. Resolviendo la ecuación cuadrática:

Usamos la fórmula cuadrática calculamos el valor de x (tomando solo la solución positiva):

$$x \approx 11.8$$

6. Encontrando el precio de equilibrio:

Sustituyendo x en la función de demanda para encontrar p:

$$p = \frac{4224 − 11.8}{2} \approx 2116.1$$

### Pregunta 2b: Número de competidores en el mercado

Para determinar el número de competidores, necesitamos calcular el ingreso total (IT) y el 
ingreso marginal (IM). El ingreso total se calcula como:

$$IT = P \by x$$

Sustituyendo los valores:

$$IT \approx 2104.32 \by 11.82 \approx 24880.00$$

El ingreso marginal es igual al costo marginal en equilibrio. Para encontrar el número de 
competidores, dividimos el ingreso total por el ingreso por firma:

Si asumimos que cada firma tiene el mismo ingreso, el número de competidores N se puede calcular como:

$$N = \frac{Ingreso por firma}{IT}$$

Si asumimos que el ingreso por firma es igual al ingreso total dividido por el número de firmas, y si 
cada firma produce x:

$$N = frac{IT}{P \by x} = \frac{24880.00}{2104.32 \by 11.82}$$

Calculamos N:

$$N \approx frac{24880.00}{24880.00} = 1$$

Resultados Finales

- Número de competidores: N = 1

Esto indica que, bajo las condiciones dadas, parece que hay un solo competidor en el mercado. Sin embargo,
este resultado puede variar dependiendo de la interpretación de los ingresos y costos por firma.

### Pregunta 2c: Cambio en la demanda

La nueva función de demanda es:

$$X(p) = 5746 − 3p$$

1. Encontrar el nuevo precio de equilibrio:

Igualamos el nuevo ingreso marginal al costo marginal:

$$IM = 2112 − x$$
$$2112 − x = 15x^2 + 12$$

Resolviendo la ecuación cuadrática como antes, se puede determinar el nuevo equilibrio.

2. Argumentación:

Si la nueva demanda es mayor, se espera que el precio de equilibrio aumente, lo que podría atraer a más competidores al mercado. 
Sin embargo, si los costos son altos, algunas firmas podrían salir del mercado.

### Pregunta 2d: Ingresos, costos y beneficios

1. Ingresos de cada firma:

$$IT = p*x$$

2. Costos de cada firma:

$$C(x) = 5x^3 + 12x + 10000$$

3. Beneficios de cada firma:

Beneficio = $$IT − C(x)$$

4. Costos totales del mercado:

$$C_{total} = n*C(x)$$

donde n es el número de competidores.
