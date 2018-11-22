# Basta de loops, hagamos exploración de datos con Pandas y Altair.
Taller a realizarse durante la PyConAr2018


Los contenidos del taller los voy a subir la noche previa al taller.
Pero para que ya tengan su ambiente de trabajo preparado, dejo aquí los requerimientos mínimos.


## Requerimientos

El requerimiento para realizar este taller es tener un ambiente con python3 y las siguientes librerías:

 - JupyterLab o Jupyter Notebook
 - altair
 - pandas


### Instalación

Primero antes que nada, cloná este repositorio. Lo podés hacer descargando el [zip](https://github.com/akielbowicz/pandas-altair_2018/archive/master.zip) o si tenés instalado _git_ ejecutar en la consola:

```
git clone https://github.com/akielbowicz/pandas-altair_2018.git
cd pandas-altair_2018
```

Si no tenés python instalado, te recomiendo bajarte [miniconda](https://conda.io/miniconda.html)

Una vez ya instalada:

Si estas en Windows, abrí la consola de miniconda desde la barra de inicio.

Si estás en un ambiente Unix, abrí la una consola de tu preferencia.
 
En esa consola cambiá de directorio a donde clonaste el repositorio y ejecutá
 
```
conda env create --name pandas-altair --file environment.yml
```

Una vez que termine de instalar todo, tenés que activar el ambiente de _conda_ ejecutando:

Alguno de estos comandos ( depende del ambiente y la consola ):

```bash
conda activate pandas-altair
source activate pandas-altair
activate pandas-altair
```

Una vez activado hay que abrir Jupyter ejecutando:

`jupyter lab`

Se va a abrir un navegador y ya podemos empezar a probar cosas.


> Para los usuarios de Windows seguramente hay una forma un poco más sencilla ejecutar JupyterLab
> instalando la versión completa de [Anaconda](https://conda.io/docs/user-guide/install/windows.html).


# Versiones Online

Los notebooks también se pueden correr el online en [Google Colab](https://colab.research.google.com/github/akielbowicz/pandas-altair_2018/blob/master/notebooks/Indice.ipynb) o en [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akielbowicz/pandas-altair_2018/master?filepath=notebooks%2FIndice.ipynb) pero para el taller es recomendable tener una versión local, para no depender de la conexión de internet.


# Conjuntos de datos

En el taller se utilizaran tres conjuntos de datos de Presidentes, Senadores y Diputados de Argentina.

Los datos de presidentes se extrajeron de la página de la Casa Rosada.
Los datos de senadores se descargaron del sistema de datos abiertos de la Cámara de Senadores, el 28/10/2018.
Los datos de diputados se descargaron del sistema de datos abiertos de la Cámara de Diputados, en las versiones:

    firmantes-leyes-sancionadas1.5.csv 
    diputados1.3.csv 