# aa
Proyecto genereado para la nateria de Aprendizaje de méquina.
<ul>
  <li>Consiste en un modelo denominado encoder-decoder</li>
  <ul>
    <li>Dentro del cual se ingresan imagenes representativas de espresiones matematicas escritas a mano (online) a una Fully Convolutional Network</li>
    <li>Posteriormente se hace uso de un enfoque conocido como Bahdanau Attention para obtener un contexto que permita reconocer las zonas de la imagen a las cuales prestar atención previo a la ralización de predicciones </li>
    <li>Por último se hace uso de un GRU (Gated Recurrent Unit) mediante el cual, haciendo uso del contexto generado por Bahdanau y la salida del Encoder se generan predicciones que representan la probabilidad de que determinada sección de la imagen represente determinado comnado de LaTeX, número, letra o símbolo </li>
  </ul>
</ul>

<div>Para hacer uso del modelo es necesario abrir el Jupiter Notebook, ejecutar la importacion de dependencias asi como aquellas celdas en las que se define el modelo y se importan los pesos derivados del proceso de entrenamiento</div>
<h2>Dependencias requeridas</h2>
<ul>
  <li>tensorflow 2.5.0</li>
  <li>elementpath 2.3.2</li>
  <li>json</li>
  <li>jiwer 2.3.0</li>
  <li>sympy 1.9</li>
  <li>antlr4 </li>
</ul>
