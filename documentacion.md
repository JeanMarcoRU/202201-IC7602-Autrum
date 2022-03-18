# **¿Por qué las voces de los integrantes son distintas?**

## Abstract

En el presente documento se brinda una investigación de los armónicos presentes en las voces de cada uno de los integrantes del presente proyecto. Se brindan conceptos clave y definiciones necesarias para realizar un análisis de los resultados de las grabaciones de los integrantes.

## Introducción

Muchas son las variantes que pueden presentarse al momento de ejecutar sonido y estructurar palabras con la boca. Además, la grabación de la voz es otro acto en el que puede variar los resultados.
Las ondas de sonido se producen en el interior de nuestra garganta y se afectan por las múltiples cajas de resonancia dentro y fuera de nuestro cuerpo antes de llegar a cualquier posible receptor. Según la intensidad de estas ondas es como nosotros entendemos la potencia del sonido, pero según cómo varía la aparición de estas ondas según el tiempo, se genera, a través de fourier, el gráfico de amplitud con respecto al tiempo, del cual podemos extraer los armónicos presentes en las ondas sonoras originales.

## Marco Teórico

En esta sección se detallan los conceptos clave se deben tener en cuenta para comprender las diferencias que se pueden presentar en las voces de determinadas personas, pero también se aclaran posibles factores externos a la voz que pueden derivar en un espectro armónico distinto en las voces humanas.

### Tono

Se define como la altura o elevación de la voz que resulta de la frecuencia de las vibraciones de las cuerdas vocales (Rodero, 2002) y altera las propiedades de emoción o el acento que denota la voz.

### Timbre

La RAE lo describe como "Cualidad de los sonidos determinada por el efecto perceptivo que produce en los oyentes", lo cual nos puede dar una idea de lo subjetivo del término, pero cabe resaltar que es el aspecto más único de cada voz humana, por lo que puede ser un determinante clave para identificar diferencias entre voces de las personas.

### Articulación

Esta variante se presenta al modificar los gestos o la posición de los elementos que influyen en la creación del sonido, por ejemplo los labios y la boca: estos pueden ser posicionados de una u otra forma para decir la misma palabra, si esto sucede, se estaría articulando de distintas formas la misma palabra.

### Intensidad

Se trata el énfasis que se le da a cada sílaba o letra de la cadena sonora. Se determina según la potencia con la que el aire es expulsado de los pulmones para generar la consecuente voz.

### Factores externos

Además de las cualidades que varían típicamente de una persona a otra, es razonable considerar las variables de calidad de recolección del sonido, oséase, la capacidad del micrófono en que grabó cada integrante, ya que si se tiene un micrófono de mayor calidad, este recolectará un espectro más amplio de la voz del integrante, pero también posiblemente de una forma más nítida.

También no solo las características del hardware de grabación son importantes en la recolección del sonido sino también el ambiente en el que se realiza la grabación, ya que por poner un caso extremo en los cuartos de grabaciones profesionales las habitaciones están completamente acondicionadas para que no entre ningún sonido externo y tampoco se genere ningún tipo de eco o resonancia.

## Desarrollo

El sonido es una perturbación que se produce al momento de la vibración de un objeto. Esto es determinado por una serie de ondas propagadas por un medio. Cuando hablamos realizamos el proceso de producir una resonancia mediante la expulsión de aire por vías respiratorias, específicamente por la tráquea y la laringe. Este proceso genera una vibración de las cuerdas vocales permitiendo la generación de sonidos. Estas vibraciones salen en forma de onda, las cuales son afectadas por una serie de elementos que hacen que sean únicas, por ejemplo el movimiento de la lengua en coordinación con los músculos de la boca que controlan la apertura, permiten crear diferentes tipos de sonidos.

Debemos de tomar en cuenta que cada persona tiene un contexto de vida diferente, los seres humanos al vivir en comunidad son afectados por sus pares, por lo que en muchos casos tienden a imitar estilos y sonidos para encajar. A lo largo de la evolución hemos desarrollado lenguajes como la facultad del ser humano para expresarse y comunicarse con los demás a través del sonido articulado(- Asale, s. f.), lo que influye en nuestra forma de mover los músculos para producir sonidos.

Para experimentar la similitud o diferencia entre las voces de los integrantes se procede a realizar una grabación de 4 segundos por cada uno en la que se diga la frase "hola mundo redes", con el fin de generar el gráfico de ondas de sonido a través del tiempo y también el gráfico de amplitudes según la frecuencia (armónicos) y analizar el resultado.

### Gráficos de ondas de sonido de cada participante

En estos gráficos se logra apreciar que cuando se pronuncian cada una de las 3 palabras elegidas, se presenta un pico en la cantidad y potencia registrada de las ondas de sonido, siendo posible identificar estos 3 picos en cada uno de los gráficos de los integrantes.

#### Jean Marco Rojas

</br><img src="https://github.com/JeanMarcoRU/202201-IC7602-Autrum/blob/main/scripts/data/output/rec_jeanmarco/jeanmarcoGrafico.png" width=400 height=400>

#### Alonso Obando

</br><img src="https://github.com/JeanMarcoRU/202201-IC7602-Autrum/blob/main/scripts/data/output/rec_alonso/grafico1.png" width=400 height=400>

#### Esteban Cruz

</br><img src="https://github.com/JeanMarcoRU/202201-IC7602-Autrum/blob/main/scripts/data/output/rec_esteban/espectro%20esteban.png" width=400 height=400>

### Gráficos de armónicos

A continuación se presentan los gráficos de armónicos para cada participante del proyecto.

#### Jean Marco Rojas

Si se comparan los gráficos de armónicos de los participantes con los gráficos de armónicos de las notas puras, se logra apreciar que este integrante es el que posee la voz más armoniosa, con un patrón de picos bastante regular y decayendo en cantidad de picos a un buen ritmo, hasta llegar a las frecuencias de más de tres mil que dejan de presentarse picos globales. Además es destacable el pronunciado valle que se encuentra justo antes de los 2000 Hz, alcanzando armónicos casi nulos para después presentarse una nueva montaña.
</br><img src="https://github.com/JeanMarcoRU/202201-IC7602-Autrum/blob/main/scripts/data/output/rec_jeanmarco/jeanmarcoFFT.png" width=400 height=400>

#### Alonso Obando

Los armónicos de este integrante son un poco menos regulares que el del anterior, llegando al pico máximo cerca de los 500 Hz para después decaer abruptamente cerca de los 650 Hz. Después de esto se logra identificar un nuevo aumento en la intensidad de los armónicos entre 1025 Hz y 1150 Hz, para de nuevo presentarse el valle de antes de los 2000 Hz y finalizar con la última montaña de armónicos cerca de los 2500 Hz.
</br><img src="https://github.com/JeanMarcoRU/202201-IC7602-Autrum/blob/main/scripts/data/output/rec_alonso/grafico2.png" width=400 height=400>

#### Esteban Cruz

Este integrante presenta 2 puntos claves en su gráfico de armónicos los cuales están en 179.75 Hz y en 470.9 Hz, este último presenta 3 'réplicas' de menor intensidad pero igualmente destacables en los hertz: 493, 509 y finalizando en 517.25.

Este gráfico de armónicos es bastante irregular por lo que no transmite armonía.

De nueva cuenta se presenta el valle de antes de los 2000 Hz que da pie al último grupo de armónicos destacables presentes en la grabación.
</br><img src="https://github.com/JeanMarcoRU/202201-IC7602-Autrum/blob/main/scripts/data/output/rec_esteban/armónicos%20esteban.png" width=400 height=400>

## Conclusión

Según lo analizado en este documento se logra concluir que las voces de los integrantes presentan amplias diferencias debido tanto a factores externos (como el entorno de grabación y el hardware con el que se realiza la grabación), como internos (como las cualidades propias a cada individuo de su voz) pero aislar los factores que propician la variación de la muestra se escapa de nuestras manos.

Se recomienda replicar el proceso de grabación utilizando los mismos instrumentos y entorno, debido a que existen grandes variaciones en el hardware y en el entorno de grabación que pueden afectar a la hora de realizar los experimentos que debe de tomarse en cuenta como margen de error a la hora de desarrollar este tipo de pruebas. También se recomienda realizar grabaciones distintas pero en la que los integrantes realicen un sonido más puro, ya que como se logra observar en los gráficos de ondas según el tiempo, las grabaciones fueron muy heterogéneas.

## Bibliografía

Rodero, Emma (2002). El tono de la voz masculina y femenina en los informativos radiofónicos: un análisis comparativo

Asale, R. (s. f.). _lenguaje | Diccionario de la lengua española_. «Diccionario de la lengua española» - Edición del Tricentenario. Recuperado 15 de marzo de 2022, de https://dle.rae.es/lenguaje
