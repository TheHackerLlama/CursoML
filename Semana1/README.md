# Machine Learning y Aprendizaje Supervisado

Este semana vimos varios temas:
- ¿Qué es AI y ML?
- ¿Para qué nos sirve ML?
- ¿Cuáles son los tipos de aprendizaje? 
- ¿Cuáles son las técnicas de ML?
- ¿Cuáles son los problemas dentro de Aprendizaje Supervisado?
- ¿Cómo funciona regresión lineal y cómo resolverlo con Gradient Descent?


Entre hoy y para la próxima semana, completa los siguientes ejercicios para que puedas estar preparado para trabajar.

1. **Git y Github** 
Git es una herramienta que permite subir código y otros recursos. Velo como un Dropbox para programadores. Git tiene muchas ventajas que permite tener control de versiones y trabajo colaborativo con facilidad. Aunque no deben saber mucho de Git, si es necesario que lo tengan para que puedan correr el cdigo.

Antes de iniciar, asegúrate de saber cómo crear carpetas y archivos, y moverte a través de ellos con la consola de tu sistema operativo. https://www.codecademy.com/learn/learn-the-command-line. En Windows usa PowerShell si lo tienes instalado.


1.1. Empieza haciendo el siguiente tutorial de Git en 15 minutos. Completa hasta la lección 12. https://try.github.io/levels/1/challenges/1
1.2 Instala Git en tu computadora. https://gist.github.com/derhuerst/1b15ff4652a867391f03


2. **Python**
Aunque tener los conceptos es muy importante, es necesario que podamos aplicarlos a la vida real. Para esto, vamos a utilizar Python. Python es un lenguaje de programación extremadamente amigable que ha sido muy adoptado por la comunidad de Machine Learning y de Data Science. Python tiene libreras que permiten, con gran facilidad, manipular muchos datos.

Completa hasta la lección 9 del siguiente tutorial: codecademy.com/learn/learn-python

3. **Configuración**
La instalación y configuración puede ser un poco tediosa, pero, si se hace bien, servirá para siempre. Anaconda es una herramienta que permite manejar ambientes de manera flexible y modular. Python tiene dos versiones diferentes del lenguaje y muchas libreras tienen diferencias. Esto puede hace difícil que tu código funcione en otras computadoras. Anaconda hace fácil esto creando un ambiente en tu computadora y usando versiones especficas de estos paquetes. Lo único que se necesita saber para lograr esto es utilizar la terminal de tu sistema operativo (sólo vamos a correr unos cuántos comandos, nada complicado).

Instala Anaconda en el siguiente enlace: https://conda.io/docs/installation.html. No es necesario tener nada más instalado. Elige Python 3.6 (desde Anaconda podrás instalar otras versiones más adelante). 

Una vez que hayas instalado Anaconda, sólo es necesario crear el ambiente

```
conda create -n curso-dl python=3.5
``` 

Finalmente, activamos el ambiente e instalamos libreras necesarias.

Mac o Linux: 

```source activate curso-dl```

Windows: 

```activate curso-dl```

Instalamos las librerías que vamos a estar utilizando
```
conda install numpy pandas jupyter notebook matplotlib
```

En este momento podemos correr el comando ```jupyter notebook``` en el directorio del archivo .ipynb, y este dará un enlace para abrir el cuaderno en cualquier navegador (se debe navegar a la carpeta donde está el cuaderno). Arriba a la derecha puedes descargar el cuaderno como zip. Para esto:
1. Clona o descarga el repositorio. Te sugiero clonar porque cada semana se agregarán cosas al repositorio. Para esto, abre tu terminal, anda a la carpeta donde quieres que se guarde el código y utiliza
```
git clone https://github.com/TheHackerLlama/CursoML.git
```
2. Luego, con la consola, anda a la carpeta. 
3. Una vez en la carpeta, ejecuta ```jupyter notebook```
4. Esto te dar un enlace que puedes copiar y abrir en tu navegador.

Una vez hecho esto, podrás abrir el archivo que termina con .ipynb. Cuando lo hagas, sigue las instrucciones para asegurarse que todo est bien instalado.

4. **Repasar temas**
Responde las pregunta que están en el archivo questions.txt.
