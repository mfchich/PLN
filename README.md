 
<p align="center"> <h1 align="center">:boom: ** CARATULA EN DESARROLLO **:boom:</h1> </p>

<p align="center"> <h1 align="center">:book: Procesamiento de Lenguaje Natural (PLN) :book:</h1> </p>

<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="500" src="https://github.com/mfchich/PLN/blob/main/imagenes/PLN.JPG" ></a></p>

<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="400" src="https://github.com/mfchich/PLN/blob/main/imagenes/logoFIUBA.jpg" ></a></p>
 

## Marcelo chichiri

<a name="top"></a>
## Desafios 
* [:notebook: Desafio 1 : TF-IDF (Term frequency-Inverse term frequency) ](#desafio1) 
* [:space_invader: Desafio 2 : Construcción de BOT simple](#desafio2)
* [:twisted_rightwards_arrows: Desafio 3 : Creación de embeddings de palabras basado en contexto](#desafio3)
* [:repeat_one: Desafio 4 : Predicción de próxima palabra](#desafio4)
* [:performing_arts: Desafio 5 : Análisis de sentimientos ](#desafio5)
* [:interrobang: Desafio 6 : Creación de un bot conversacional](#desafio6)
## 

<a name="desafio1"></a>
## <p align="center"> TF-IDF (Term frequency-Inverse term frequency) </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="300" src="https://github.com/mfchich/PLN/blob/main/imagenes/TF_IDF.JPG" ></a></p>

### Este desafío consiste en calcular, con herramientas de numpy, las métricas TF (Term Frequency) e IDF (Inverse Term Frequency). Estas métricas se utilizan como indicador de cuán importante es una palabra (o un término) en un documento. 
### El indicador TF muestra la frecuencia de aparición de un término en un documento.  
### El indicador IDF muestra la proporción de documentos en el corpus que poseen el término dado.

[Volver](#top)

##
<a name="desafio2"></a>
## <p align="center"> Construcción de BOT simple </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Bot_grande.JPG" ></a></p>

### Este desafío consiste en construir un bot simple que sea capaz de responder preguntas simples. En este caso se utilizó un corpus para un bot de un servicio de venta y reclamos de un servicio de TV por cable (Cablin).
### Se definieron 11 clases ('Subscripcion', 'agradecimientos', 'baja', 'consulta_pago', 'contacto', 'despedida', 'hablar_humano', 'nombre', 'reclamos_cobro', 'reclamos_servicios', 'saludos') con un vocabulario de 93 términos.

[Volver](#top)

##
<a name="desafio3"></a>
## <p align="center"> Creación de embeddings de palabras basado en contexto </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Bot_grande.JPG" ></a></p>

### Este desafío consiste en utilizar documentos/corpus para crear embeddings de palabras basado en ese contexto. Se utilizará canciones de bandas para generar los embeddings, es decir, que los vectores tendrán la forma en función de como esa banda haya utilizado las palabras en sus canciones.

### Se usó un corpus de aproximadamente 40 canciones de Joan Manuel Serrat. El dataset fue creado a mano. Las letras fueron obtenidas de https://www.musica.com/letras.asp?letras=7599

###  Este desafío consiste en crear vectores con Gensim. Probar términos de interés y explicar similitudes en el espacio de embeddings. Graficarlos. Sacar conclusiones

### El objetivo es utilizar documentos / corpus para crear embeddings de palabras basado en ese contexto. Se utilizará canciones de bandas para generar los embeddings, es decir, que los vectores tendrán la forma en función de como esa banda haya utilizado las palabras en sus canciones.

Se usó un corpus de aproximadamente 40 canciones de Joan Manuel Serrat. El dataset fue creado a mano. Las letras fueron obtenidas de https://www.musica.com/letras.asp?letras=7599
Se estableció en 2 la cantidad de repeticiones mínimas del término para ser tomada en cuenta. Esto es principalmente porque hay terminos que se repiten poco pero dan significado a otras que se repiten mas.
Se comprueba que los términos se pueden relaciona con distintos párrafos de canciones de cantautor.



La temática de los temas de cantautor es muy variada por lo cual los términos aparecen en contextos variados.

Se estableció en 2 la cantidad de repeticiones mínimas del término para ser tomada en cuenta. Esto es principalmente porque hay terminos que se repiten poco pero dan significado a otras que se repiten mas.

En el gráfico de embedding no se puede ver la misma relación, lo cual puede deberse a que fue necesario usar solo dos dimenciones para poder presentarlo.

Se prueba el modelo con varios términos como amigos, camino, flores, piratas y hombres

Se comprueba que los términos se pueden relaciona con distintos párrafos de canciones de cantautor.

[Volver](#top)

##
<a name="desafio4"></a>
### Predicción de próxima palabr
[Volver](#top)

##
<a name="desafio5"></a>
###  Análisis de sentimientos
[Volver](#top)

##
<a name="desafio6"></a>
### Creación de un bot conversacional
[Volver](#top)


