Este repositorio contiene el material utilizado en la charla-taller:

[Lógica y programación funcional - dos caras de la misma moneda](https://docs.google.com/presentation/d/1kTiWcl-Er0ZPPr1DD62fwzzKztUbO9SKkw762S4TrJM/edit?usp=sharing)

impartida en la conferencia [el día de Pi](https://eventos.urjc.es/60207/detail/dia-de-pi-2021.html) celebrada en la Universidad Rey Juan Carlos.

Durante esta charla se hará uso de los notebooks de jupyter y el lenguaje de programación Scala. Para utilizar los notebooks de jupyter con Scala se pueden seguir los siguientes pasos: 

### Alternativa 1 

* Instalar el gestor de paquetes [conda](https://docs.conda.io/en/latest/miniconda.html). Alternativamente, también podremos utilizar pip, el gestor de paquetes que viene ya instalado con python. 
* Instalar jupyter utilizando conda o pip, según se explica en las siguientes [instrucciones](https://jupyter.org/install).
* Instalar el kernel de Scala para jupyter, según se indica en la siguiente [página](https://almond.sh/docs/quick-start-install).

### Alternativa 2

El entorno virtual MyApps de la URJC ya tiene instalados tanto jupyter como el kernel de Scala. Para abrir un notebook de Scala el alumno dispone del enlace "Jupiter (Anaconda 3)". 

### Alternativa 3

Alternativamente, también se pueden utilizar los notebooks de jupyter a través de docker. Para ello, sigue los siguientes pasos:

* Instala docker si no lo has hecho ya (Linux, Windows, MAC)
* Ejecuta el siguiente comando: 

LINUX: 
docker run -it --rm -p 8888:8888 -p 4040:4040 -m 4g -v "$PWD":/home/jovyan/work almondsh/almond:latest
Windows: 
docker run -it --rm -p 8888:8888 -p 4040:4040 -m 4g -v <<c:/path/to/downloaded/folder>>:/home/jovyan/work almondsh/almond:latest
Algunos comentarios:

En el caso de windows puede ser necesario ejecutar la consola de comandos como administrador. 
En el caso de linux, se sobreentiende que el comando se ejecuta en el directorio donde se encuentra descargado el repositorio; es posible especificar la ruta de forma relativa
En el caso de Windows, se proporciona esta ruta explícitamente y en términos absolutos; por ejemplo, /c/users/jserrano/documents/urjc-pd. 
En ambos casos, es posible que la imagen de docker incluya varios kernels de Scala, en cuyo caso se deberá elegir la más reciente cuando se abra un notebook del repositorio.

### Descarga y ejecución de los notebooks

Para acceder a los notebooks del repositorio del curso, ejecutar el comando 

> jupyter notebook 

desde el directorio donde se clonó el repositorio. Para clonar el repositorio utilzar el siguiente comando: 

> git clone https://github.com/jserranohidalgo/lahoradelambda.git

