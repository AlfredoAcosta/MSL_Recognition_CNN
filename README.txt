-------------------------------------------------------------
Pasos a seguir para la correcta ejecución de los
programas pertenecientes al proyecto:
"Reconocimiento de signos estáticos de la lengua de
señas Mexicana usando Redes Neuronales Convolucionales"
- Alfredo Antonio Estevez Acosta
- Maestría en Electrónica, Opción: Sistemas Inteligentes
  Aplicados.
--------------------------------------------------------------

--------------------------------------------------------------
		1) OBTENER EL CONJUNTO DE DATOS
--------------------------------------------------------------
La base de datos se puede obtener de GoogleDrive en:
https://drive.google.com/file/d/1FyF_Ut7WUxJ56FarHsxYbpY_
DtN3HNLB/view?usp=sharing

O copiando directamente al entorno de trabajo el archivo:
LSM_reduced.csv que se encuentra en la carpeta "codigo fuente"
--------------------------------------------------------------
		2) CREAR EL ENTORNO DE TRABAJO
--------------------------------------------------------------
-Primero se necesita tener Python 3 instalado, de lo contrario
 obtenerlo de https://www.python.org/
-Crear un entorno de trabajo para el código y dataset.
    - Abrir una terminal y escribir los siguientes comandos
      después del simbolo '$': 
      
    $ export ML_PATH="$HOME/ml" #cambiar la ruta si se desea.
    $ mkdir -p $ML_PATH
    
- Se requieren varios módulos de Python como: Juyter, Numpy,
  pandas, Matlplotlib, y Scikit-Learn.
  Para instalarlos se puede hacer uso de algún manejador de 
  paquetes como Anaconda o el propio de Python 'pip'. Para 
  verificar si se encuentra instalado escribir lo siguiente:
  
    $ python3 -m pip --version
    
  Para tener la versión mas reciente de pip instalada:
  
    $ python3 -m pip install --user -U pip
--------------------------------------------------------------
          3) CREANDO UN ENTORNO AISLADO (Recomendable)
-------------------------------------------------------------- 
-Para evitar conflictos con versiones de bibliotecas de otros 
 proyectos se procede a crear un entorno aislado:  
 
    $ sudo apt install python3-virtualenv
    $ cd $ML_PATH
    $ virtualenv my_env

-Para activar cada vez que se requiera el entorno aislado:

    $ cd $ML_PATH
    $ source my_env/bin/activate # en Linux o macOS
    $ .\my_env\Scripts\activate # en Windows     
--------------------------------------------------------------
          4) INSTALACIÓN DE MÓDULOS REQUERIDOS
--------------------------------------------------------------     
    $ sudo apt install python3 jupyter-notebook
    $ sudo apt-get install python3-matplotlib
    $ sudo apt-get install python3-numpy
    $ sudo apt-get install python3-sklearn
--------------------------------------------------------------
          4) EJECUCIÓN DE LOS PROGRAMAS
--------------------------------------------------------------     
Desde la consola escribir:

    $ jupyter-notebook 
    
Una vez dentro de este entorno, ubicar el cuaderno de
jupyter ubicado dentro de la carpeta "codigo ejecutable"        
    
    
    
    
    
    
    
    
    
