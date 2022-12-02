 
<p align="center"> <h1 align="center">:boom: ** CARATULA EN DESARROLLO **:boom:</h1> </p>

<p align="center"> <h1 align="center">:book: Procesamiento de Lenguaje Natural (PLN) :book:</h1> </p>

<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="500" src="https://github.com/mfchich/PLN/blob/main/imagenes/PLN.JPG" ></a></p>

<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="400" src="https://github.com/mfchich/PLN/blob/main/imagenes/logoFIUBA.jpg" ></a></p>
 

## Marcelo chichiri

<a name="top"></a>
## Desafios 
* [:notebook: Desafio 1 : TF-IDF (Term frequency-Inverse term frequency) ](#desafio1) 
* [:space_invader: Desafio 2 : Construcción de BOT basado en reglas](#desafio2)
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

:bookmark_tabs: <a href="https://github.com/mfchich/PLN/blob/main/1a%20-%20word2vec_M-CHICHIRI.ipynb" target="_blank">Ir al código del desafio 1</a>

[:arrow_heading_up: Volver](#top)

##
<a name="desafio2"></a>
## <p align="center"> Construcción de BOT basado en reglas </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Bot_grande.JPG" ></a></p>

### Este desafío consiste en construir un bot basado en reglas que sea capaz de responder preguntas simples. En este caso se utilizó un corpus para un bot de un servicio de venta y reclamos de un servicio de TV por cable (Cablin).
### Se definieron 11 clases ('Subscripcion', 'agradecimientos', 'baja', 'consulta_pago', 'contacto', 'despedida', 'hablar_humano', 'nombre', 'reclamos_cobro', 'reclamos_servicios', 'saludos') con un vocabulario de 93 términos.
### considerando la reducida cantidad de clases y de términos los resultados obtenidos fueron muy buenos. 

<a href="https://github.com/mfchich/PLN/blob/main/2b%20-%20bot_dnn_spacy_esp_M-CHICHIRI.ipynb" target="_blank">Ir al código del desafio 2</a>

[:arrow_heading_up: Volver](#top)

##
<a name="desafio3"></a>
## <p align="center"> Creación de embeddings de palabras basado en contexto </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Relacion_palabras.JPG" ></a></p>

### Este desafío consiste en utilizar documentos/corpus para crear embeddings de palabras basado en ese contexto. Se utilizará canciones de bandas para generar los embeddings, es decir, que los vectores tendrán la forma en función de como esa banda haya utilizado las palabras en sus canciones.

### Se usó un corpus de aproximadamente 40 canciones de Joan Manuel Serrat. El dataset fue creado a mano. Las letras fueron obtenidas de https://www.musica.com/letras.asp?letras=7599
### Se estableció en 2 la cantidad de repeticiones mínimas del término para ser tomada en cuenta. Esto es principalmente porque hay términos que se repiten poco, pero dan significado a otras que se repiten más.
### La temática de los temas de cantautor es muy variada por lo cual los términos aparecen en contextos variados. Se comprueba que los términos se pueden relacionar con distintos párrafos de canciones de cantautor.

<a href="https://github.com/mfchich/PLN/blob/main/3b-Custom_embedding_con_Gensim-M-CHICHIRI.ipynb" target="_blank">Ir al código del desafio 3</a>

[:arrow_heading_up: Volver](#top)

##
<a name="desafio4"></a>
## <p align="center"> Predicción de próxima palabra </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Proxima_palabra.JPG" ></a></p>

### Este desafío consiste en utilizar un dataset y poner en práctica la predicción de próxima palabra.

### Se usó un corpus de aproximadamente 4566 documentos (con 141318 tokens), formados por el texto del libro "La Vuelta al Mundo en 80 días" y de "Viaje al Centro de la Tierra", ambos de Julio Verne, concatenados y convertidos en un archivo csv. Ambos textos fueron obtenidos de https://www.textos.info/

### Los resultados no fueron muy buenos. Se ve que la palabra predicha no se ajusta a lo que se espera de sugerencia como palabra siguiente. Esto se explica por la reducida cantidad de documentos en el corpus.

<a href="https://github.com/mfchich/PLN/blob/main/4d%20-%20predicci%C3%B3n_palabra_M-CHICHIRI.ipynb" target="_blank">Ir al código del desafio 4</a>

[:arrow_heading_up: Volver](#top)

##
<a name="desafio5"></a>
## <p align="center"> Análisis de sentimientos </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Analisis_sentimientos2.JPG" ></a></p>

### El objetivo es utilizar las críticas de compradores de ropa para que el sistema determine la evaluación del comprador y su crítica (cuantas estrellas le asigna al producto).
### Se utilizó como dataset críticas de compradores de ropa por eCommerce , los cuales puntuaron a cada prenda con un puntaje de 1 a 5 estrellas.

<a href="https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews" target="_blank">Referencia del dataset</a>

### El datset original tiene 5 clases, pero como están muy desbalanceados se juntaron clases para concluir solo en tres clases mas balanceadas. Entonces la clase 0 sería malo y regular, la clase 1 bueno y muy bueno y la clase 3 excelente/perfecto. Este cambio no balanceó por completo el dataset pero lo mejoró significativamente, lo cual mejoró el entrenamiento del modelo.

### Se utilizaron distintas configuraciones de redes, tanto con capas lstm con conexiones bidireccionales como sin conexiones bidireccionales, adaptando las redes para cada caso, buscando el mejor resultado.

<a href="https://github.com/mfchich/PLN/blob/main/5%20-%20clothing_ecommerce_reviews-M-CHICHIRI.ipynb" target="_blank">Ir al código del desafio 5</a>

[:arrow_heading_up: Volver](#top)

##
<a name="desafio6"></a>
## <p align="center"> Creación de un bot conversacional </p>
<p align="center"><a target="_blank" rel="noopener noreferrer"><img width="200" src="https://github.com/mfchich/PLN/blob/main/imagenes/Bot_conversacion.JPG" ></a></p>

### Este desafío consiste en construir un BOT para responder a preguntas del usuario (QA). El objecto es utilizar datos disponibles del challenge ConvAI2 (Conversational Intelligence Challenge 2) de conversaciones en inglés, utilizado la técnica seq2seq.

### Se utilizó una red neuronal con embeddings de Glove de dimensión 50 y una capa de entrada de 128 unidades. El dataset de entrenamiento tiene aproximadamente 1980 palabras. Los resultados fueron bastante variados, en algunos casos la respuesta del bot fue buena y en otros bastante deficiente, pero considerando la reducida dimensión del corpus de entrenamiento, los resultados generales fueron aceptables.

<a href="https://github.com/mfchich/PLN/blob/main/6-%20bot_qa_M-CHICHIRI.ipynb" target="_blank">Ir al código del desafio 6</a>

[:arrow_heading_up: Volver](#top)
