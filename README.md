# LMSGI-04 Chatbot.aiml

Unos de los dialectos de ***XML***, es ***AIML***, que significa Lenguaje de Marcado para la Inteligencia Artificial.
Con ***AIML*** se puede definir el comportamiento de los **bots** conversacionales denominados, ***Chatbots***.

 1. ## Primera Tarea:
En esta tarea hay que hacer dos ***Chatbots***. El primero de ellos tiene como punto de partida la traducción, en mi caso lo haré al _Español_, de un ejemplo de información turística en _Inglés_ disponible en el tutorial de [Steve Worswick](https://medium.com/pandorabots-blog/aiml-tutorial-creating-a-context-aware-multi-functional-chatbot-e5e82c027a6a).
![Chatbot Turístico](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/aiml-tutorial-steve-worswick.jpg)
Para la realización de la tarea hay que acceder a la plataforma [Pandorabots](https://home.pandorabots.com/home.html), crear una cuenta y acceder a la plataforma. En donde podremos crear nuestro primer ***Chatbot*** desde el panel superior izquierdo pulsando en ***MY BOTS +*** , donde indicaremos el nombre y lenguaje del **Bot**, así como el contenido del bot en donde indicaremos que sea en blanco para realizarlo desde cero.

Crear nuevo bot:


![New bot](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/crear-bot.jpg)

Configuración inicial bot:


![Creación del bot](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/crear-bot-turistico-simple.jpg).

Una vez creado el primer bot, lo editamos:

![Editor de código aiml](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/editar-bot-code-editor.jpg)


Desde File, creamos un nuevo archivo .aiml:

![Nuevo File .aiml](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/file-new-aiml.jpg)


Ahora creamos el archivo codificandolo como:

 `<?xml version="1.0" encoding="UTF-8"?>`

  `<aiml version="2.0">`

Agregamos las características del ejemplo de _Steve Worswick_ traducidas a la lengua _Española_.



![Archivo .aiml turismo](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/aiml-turismo.jpg)

Una vez creado el bot y configuradas las categorías en el archivo _.aiml_ creado, se ha realizado un vídeo desde camtasia en donde se explica todo el proceso del ejemplo de Steve Worswick, así como la creación, configuración y prueba de funcionamiento del bot, en donde comprobamos como responde a nuestras preguntas.

Aquí la dirección del vídeo en YouTube:

[Chatbot turistico "turibot" ](https://www.youtube.com/watch?v=q4npW5NG2qE).

---


 2. ## Segunda Tarea:
En esta segunda tarea hay que hacer un ***Chatbot*** sobre cualquier tema que nos interese o hacer modificaciones tanto sustanciales como ampliaciones de algunos de los ejemplos disponibles en ***Github*** en el repositorio de [Pandorabots](https://github.com/pandorabots/free-AIML).
He decidido mejorar el ***chatbot*** de la primera tarea agregando mas archivos *.aiml*, en donde he creado mapas *.maps* y sets *.sets* para poder ofrecer la prevision meteorologica de las diferentes poblaciones de las Islas Baleares, en donde en este caso se puede usar palabras compuestas como puede ser **Palma de Mallorca**, la cual daba error en el archivo *.aiml* del chatbot del ejercicio **1** en donde lo enlazabamos a la .url de *weather-foreccast*.
Seguidamente se muestran unas capturas de pantalla, donde se pueden ver los archivos *.aiml* creados así como los *.maps* y *.sets* asignados a las diferentes categorías en los *.aiml* creados.
. Archivo .aiml mallorca, con información turistica de Mallorca, asi como de restaurantes y meteorología en las diferentes poblaciones de las Islas Baleares:
![aiml mallorca](https://github.com/andreshmb/LMSGI-04.github.io/blob/master/img/turibot2-aiml-mallorca.jpg).
. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk0NjU3OTE2MywtNDQwOTMwNTE5LDQyND
E0MDE0NiwtMTE3MjM4NjQ2NiwtMjAxODQzNzA5NCwtOTg3MTI3
OTcyLDE2OTcxMDg2NzcsNjU3Mjk2MDUzLDQyNTcyNDk4LDk4MT
AxNDEwNl19
-->
