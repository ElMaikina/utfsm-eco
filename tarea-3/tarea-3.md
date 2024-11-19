# Economia 1
## Tarea 3: Teoría de la Firma

* Miguel Soto Delgado
* Rol: 201973623-K

## Preguntas Conceptuales

### 1. Definir en palabras y matemáticamente el costo medio y costo marginal.

El costo medio es lo que cuesta producir una unidad de un cierto producto, mientras que el costo marginal se refiere a cuánto cuesta producir una unidad EXTRA de este mismo producto. La distinción existe en que uno refiere al costo promedio y el otro a el costo agregado dada la cantidad de producción en un punto específico. Por ejemplo, para producir una unidad extra de un bien, me va a costar 20$ (costo marginal), sin embargo, al producir esa unidad extra, yo estaré gastando 100$ y produciendo 10 unidades, por lo que cada unidad me saldría 10$  (costo medio).

### 2. Defina el beneficio de una firma, haciendo la diferencia entre la medición de un economista y un contador.

El beneficio de una firma se define como la cantidad de dinero producido tras la venta de insumos o productos. La diferencia principal entre la visión de los economistas y los contadores es que los economistas perciben los beneficios de forma marginal, lo cual significa que buscan una proyección positiva a futuro y toman en consideración los costos implícitos y explícitos. Por otro lado, los contadores perciben el beneficio como la suma neta de dinero adquirida tras la venta. Esto en términos matemáticos se mide en base a la diferencia entre ingresos y costos totales.

### 3. En el equilibrio de largo plazo, la curva de oferta siempre tendrá una pendiente positiva. Comente.

En clases vimos que si los precios de los factores (costos) no cambian, entonces solo puede prevalecer un precio a largo plazo, independiente de cómo cambie la demanda, es decir, la curva de oferta a largo plazo es una línea horizontal en el nivel de este precio. La curva de oferta también puede tender a crecer o decrecer. En el primer caso, hace que aumenten los costos de los factores; la curva de oferta a LP tiene pendiente positiva. Finalmente, en el último caso la entrada disminuye el costo de los factores; la curva de oferta a LP tiene pendiente negativa. Por ende la afirmación es incorrecta.

### 4. La relación entre precio y calidad de un bien no es clara, es decir, un bien de peor calidad no necesariamente es más barato.

Esto es evidentemente falso, vimos en clases que el nivel de calidad es parte del factor que maximiza el bienestar del comprador y se puede formular como modelo matemático.

### 5. ¿Si una firma decidiera mantenerse en el mercado en el largo plazo, qué condición debe cumplir y por qué?

Para que una firma se mantenga en el mercado en el largo plazo, debe ser capaz de cubrir al menos sus costos totales, lo que incluye tanto los costos explícitos como los costos de oportunidad. Esto significa que debe obtener un beneficio económico igual a cero, lo que es suficiente para que los propietarios de la firma consideren que su inversión es rentable en comparación con otras alternativas.

### 6. ¿Que tipo de rendimientos tiene la firma con función de producción F(K, L) = AK0,6L0,45? Demuestrelo.

Tendría una función de producción CES. Para determinar el tipo de rendimientos, se puede analizar la función de producción. Si se duplica la cantidad de todos los insumos (K y L), se debe observar si la producción se duplica, aumenta más o menos. En este caso, al aplicar el teorema de homogeneidad, se puede ver que la suma de los exponentes (0.6 + 0.45 = 1.05) es mayor que 1, lo que indica que la firma experimenta rendimientos crecientes a escala.

### 7. Tanto en el corto como en el largo plazo una firma puede modificar sus factores en aras de incrementar o disminuir la producción. Comente.

En el corto plazo, las firmas pueden ajustar la cantidad de insumos variables (como el trabajo) para aumentar o disminuir la producción, mientras que los insumos fijos (como el capital) son constantes. En el largo plazo, las firmas pueden ajustar todos los factores de producción, incluyendo el capital, lo que les permite adaptarse completamente a las condiciones del mercado y optimizar su producción según la demanda.

## Preguntas Matemáticas

### a) (6 ptos) Los vendedores de bajos están muy complicados y desean saber cual es el precio y cantidad de equilibrio presentes en su mercado. Calcular estos datos para poder ayudar a estos comerciantes.

Dada la función de costos totales de largo plazo de cada firma: C(x) = $5x^3 + 12x + 10000$ Y la función de demanda del mercado: $X(p) = $4224 − 2p$

Nosotros sabemos que el equilibrio a largo plazo se alcanza con las siguientes condiciones:

* $Q_{oferta} = Q_{demanda}$
* p = CMg = CMe

Para esto, seguimos desde la segunda condición. Para obtener el Costo Marginal (Mg) tenemos que derivar el Costo Total (CT):

$$CMg(x) = \frac{d}{dx}(5x^3 + 12x + 10000)$$ 
$$CMg(x) = 15x^2 + 12$$

Luego, para el Costo Medio (CMe) tenemos que dividir el costo total por la cantidad a producir, en este caso x:

$$CMe(x) = \frac{5x^3 + 12x + 10000}{x}$$ 
$$CMe(x) = 5x^2 + 12 + \frac{10000}{x}$$

Ahora igualamos ambas ecuaciones:

$$CMg(x) CMe(x) = \frac{5x^3 + 12x + 10000}{x} = \frac{d}{dx}(5x^3 + 12x + 10000)$$

De esto, nosotros buscamos valores reales y positivos en esta ecuación. Para este caso, la única solución viable es: $x = 10$

Finalmente, reemplazamos este valor de x en la función de Costo Marginal (CMg) y hacemos uso de la propiedad: $p = CMg$

$$p = CMg = 15x^2 + 12 = 15(10)^2 + 12$$ 
$$p = 1512$$

### b) (6 ptos) Existe una directiva entre todos los vendedores de bajos y quieren convocar a una reunión para tomar decisiones importantes para el futuro de la música, pero tienen un problema: No saben cuántos competidores existen en este mercado. Le piden a usted que determine cuántos vendedores hay efectivamente en este mercado.

Visto que en el inciso anterior calculamos todas las condiciones necesarias, solo basta con introducir estos valores en la función de Demanda Total (X(p)) y posteriormente dividirla por la cantidad de ventas por firma (x):

$$C = 4224 - 2p$$ 
$$C = 4224 - 2(1512)$$ 
$$C = 2710$$

Ahora dividimos por la cantidad de ventas por firma:

$$Vendedores = \frac{2710}{10}$$ 
$$Vendedores = 271$$

### c) (6 ptos) Durante la reunión anual de productores de bajos eléctricos, la directiva plantea que ha habido un cambio en demanda, debido a que luego de un par de estudios de mercado, se han percatado que ahora está presenta el siguiente comportamiento:

$$X = 5746 −3p$$

### Por lo que el presidente de la asociación asegura que en el corto plazo eso no presentará un problema debido a que ahora hay competidores que sobran, por ende la nueva demanda será suplida de manera total. ¿Qué le diría´ıa usted al respecto? Argumente con cálculos y explique. 

Calculamos el valor de la Demanda Total en base al precio fijado anteriormente:

$$X = 5746 - 3(1512) = 1210$$ 
$$Vendedores = \frac{1210}{10} = 121$$ 
$$Vendedores Sobrantes = 271 - 121 = 150$$

Efectivamente se suplirá toda la demanda, sin embargo al mantener el precio fijado, se crea una sobreproducción de guitarras, por que se crearan excedentes en el mercado. De no ser asi, entonces algunos vendedores tendrán que retirarse del negocio.

### d) (12 ptos) Finalmente, los productores de bajos eléctricos se dan cuenta de que están en problemas, y necesitan la ayuda de un brillante ingeniero para determinar lo siguiente (tomando en cuenta la situaci´on inicial): ingresos de cada firma, costos de cada firma, beneficios de cada firma y costos totales del mercado.

$$IT_{firma} = p * q = 1512 * 10 = 15120$$
$$CT_{firma} = 5(10)^3 + 12(10) + 10000 = 15120$$ 
$$Beneficio = IT_{firma} - CT_{firma} = 15120 - 15120 = 0$$
$$CT_{mercado} = CT_{firma} * Vendedores = 4097520$$


