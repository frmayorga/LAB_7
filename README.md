# LAB_7


# OBJETIVOS

## OBJETIVO GENERAL 
- mediante los conocimientos impartidos en clase desarrollar nuestras habilidades para la manipulacion de instrumentos de medicion tales como el osciloscopio de tal manera que podamos manipular los datos arrojados por circuitos de corriente alterna que contiene capacitores he inductores en serie o en paralelo.  

## OBJETIVO ESPECIFICO
- comprender como funciona el osciloscopio.
- analizar el efecto producido en la onda sinuidal por circuitos que contienen capacitores he inductores.
- analizar el comportamiento de la corriente y el voltaje en circuitos de corriente alterna.
# MARCO TEORICO

![capacitores](https://user-images.githubusercontent.com/93361435/152892515-5b58dbc9-13c9-48c4-bb3c-85d0e7bffd16.jpg)


**CODIGO DE COLORES PARA RESISTORES DE 4 BANDAS** 

| DIGITO | COLOR |
|--------|------------|
| 0 | Negro |
| 1 | Café |
| 2 | Rojo |
| 3 | Naranja |
| 4 | Amarillo |
| 5 | Verde |
| 6 | Azul |
| 7 | Violeta |
| 8 | Gris |
| 9 | Blanco |

TOLERANCIA : Oro +- 5%; Plata +- 10%.



# PROCEDIMIENTO

Se utilizo los siguientes materiales 

- Generador de señales
- Fuente DC.
- Osciloscopio.
- Protoboard
- Multímetro
- Cables conductores
- Resistencias, bobinas y capacitores.


## Parte 1:

Para el procedimiento de la tabla 1.1 se armo el siguiente circuito en DCACLAB: 

![image](https://user-images.githubusercontent.com/93361435/152783023-831ae50b-0932-41b2-98e1-1b05c83d5684.png)

Despues de realizar el armado se tomo las mediciones de voltaje Vo con diferentes frecuencias, tambien se realizo las medidas de voltajes picos con el osciloscopio: 

- OSCILOSCOPIO

![image](https://user-images.githubusercontent.com/93361435/152783211-f789b1c6-4f0c-498e-8523-2ee7ad8f236a.png)

- VOLTAJE

![image](https://user-images.githubusercontent.com/93361435/152783261-aa173ebd-6c92-478b-9119-42c4e0839553.png)

Los valores de corriente no se han tomado en cuenta debido a que los valores en el multimetro cambiaban sin quedar en un valor fijo.

## Parte 2:

Para el procedimiento de la tabla 1.2 se armo el siguiente circuito en DCACLAB: 

![image](https://user-images.githubusercontent.com/93561706/152915505-8c594653-e7e1-4fae-855e-2fe7b8568ee9.png)

Despues de realizar el armado se tomo las mediciones de voltaje Vo con diferentes frecuencias, tambien se realizo las medidas de voltajes picos con el osciloscopio: 

- OSCILOSCOPIO

![image](https://user-images.githubusercontent.com/93561706/152915536-c3cddc6e-9e09-4472-b8cf-3d6100ad896e.png)

- VOLTAJE

![image](https://user-images.githubusercontent.com/93561706/152915561-ac93a20e-388c-409e-a7bd-fc5bc0020869.png)

Algunos valores de corriente no se han tomado en cuenta ya que los valores en el multimetro cambiaban sin quedar en un valor fijo.



# RESPUESTA DE INTERROGANTES

**TABLA 1.1 CAPACITORES**

| FRECUENCIA | VOLTAJE MULTIMETRO | VOLTAJE PICO OSCILOSCOPIO |
|------------|--------------------|---------------------------|
| 0 Hz | 8.346 V | 0 V |
| 10 Hz | 7.135 V | 10 V |
| 50 Hz | 7.079 V | 9.97 V |
| 100 Hz | 6.974 V | 9.77 V |
| 500 Hz | 5.949 V | 8.4 V |
| 1000 Hz | 4.336 V | 6.15 V |

**TABLA 1.2 CAPACITORES**

![image](https://user-images.githubusercontent.com/93561706/152915694-ec00519d-88d5-42d8-8603-448cbb0ba207.png)

#### 1) ¿como se comportan la bonina y el capacitor con cero hz?
- cuando se trata del capacitor podemos notar que aun existe una onda periodica, sin embargo, el tiempo que tarda en completar cada ciclo es demaciado extenzo y en un punto de este ciclo la extensa onda se detiene en cero volts, podemos asumir que esto sucede devido aun corto que puede estar relacionado con una falla en los capacitores.  
![image](https://user-images.githubusercontent.com/93398718/152890627-3d702be4-485c-4c5c-9542-e67e450ac647.png)

- apesar de que en el inductor la onde sinuidal se prolonga durante mas tiempo se obtiene el mismo resultado que con el inductor, pues en cierto punto la onda llega a cero volts y se detiene.  
![image](https://user-images.githubusercontent.com/93398718/152890295-549b45d7-3a2d-46f1-ba4e-4eda52c9e9bf.png)
 
#### 2) ¿como se comportan la bobina y el capacitor en corriente alterna?

- bonina: Las bobinas o solenoides almacenan energía en forma de campo magnético. Al conectar una corriente continua, la bobina retiene el paso de electrones hasta que se establece el campo magnético. Cuando se elimina la pila, la energía de este campo magnético continúa moviendo electrones, fenómeno llamado autoinducción que proboca que estas se produzcan voltaje y corriente. Ademas la energia magnetical almacenada en la bobina provoca que la corriente este en desjace con respecto a la corriente.
- capacitor: En corriente alterna, el voltaje está constantemente cambiando su polaridad, y ésto se traduce en que el condensador se está cargando y descargando constantemente al ritmo de la frecuencia que posee el generador, por lo que la intensidad se ve afectada.

#### 3) ¿ Que cree usted que ocurrira con el voltaje Vo y la corriente de la resistenccia en los circuitos analizados en esta practica, si se utilizan dos bobinas o dos capacitores de valores distintos?
- en caso de que utilicemos dos inductores con balores distintos en el circuito prodemos notar como el voltaje y la corriente aumentan dependiendo de los valores que estemos usando en estos componentes. caso contrario sucede con las bobinas donde podemos apreciar que en todo el circuito el voltaje se reduce al igual que la corriente esto sucede devido a que el campo electromagnetico que se produce en estos inductores afecta a todo el circuito.


#### 4) ¿Que son los valores eficaces de voltaje y corriente?
- el valor root meat square mayormente conocido por sus siglas rms que significan raiz cuadrada del valor medio es el valor eficas de un circuito, El valor eficaz de una corriente o voltaje alterna, es el valor que tendría una corriente o vpltajecontinua que produjera la misma potencia que dicha corriente o voltaje alterna, al aplicar ambas, primero una y luego otra, sobre una misma resistencia.



# VIDEO


# CONCLUSIONES

- gracias al desarrollo de esta practica comprendemos de mejor manera los datos que podemos obtener haciendo uso de herramientas de analisis tales como el osciloscapio que no solo nos permite observar el comportamiento de la onda seno, tambien mediante el analisis de la misma podemos observar su frecuencia, los valores pico de voltaje estas caracteristicas mensionadas son solo pocas de las muchas cosas que podemos observar gracias a este intrumento de medicion.
- mediante la experimentacion aprendimos que los capacitores influyen en el aumento del voltaje y corriente dentro de circuitos de ca mientras que con los inductores observamos un efecto contrario, esto lo pudimos afirmar de mejor manera cuando usamos valores de capacitores he inductores distintos. 
- el comportamiento de la corriente y el voltaje esta directamente relacionado con los valores de frecuencia que la fuente de ca puede administrar comprobamos esto al momento de encender el circuito con valores de 0 hz, donde luedo de un momento se producia corto en el circuito.

# BIBLIOGRAFIA

- Floyd, T. (2007). *Principios de circuitos eléctricos*. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) *Analisis de circuitos Teoria y Practica*. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.

