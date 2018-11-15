# Ejemplos de los algoritmos KNN y SVM utilizando OpenCV

## Ejemplo de KNN

Para el siguiente ejemplo, se requiere contar con una computadora con el sistema operativo Ubuntu 16.04 o superior, además de conexión a internet. 
Clonar el siguiente repositorio:
https://github.com/vrantrax/IntroduccionKNNySVM

Una vez que cuente con el repositorio de manera local, debe descomprimirlo (sea el caso). 
Al descomprimir, podrá ingresar a la carpeta Script del proyecto. Mueva el único archivo de la carpeta a su carpeta Home o inicio. Dentro de la carpeta donde colocó el archivo Scripts_install-opencv.sh, debe abrir la terminal de Ubuntu y ejecutar el siguiente comando:
sudo sh Scripts_install-opencv.sh

Al terminar de instalar las bibliotecas y OpenCV, ahora debe entrar a la carpeta KNN. En ella encontrará el archivo KNN.py, ejecútalo ingresando el siguiente comando en la terminal dentro de la carpeta KNN:
python KNN.py

Una ventana similar a la siguiente debe ser desplegada. 

![Imagen del ejemplo KNN](https://github.com/vrantrax/IntroduccionKNNySVM/blob/master/Images/knn.png)

Al oprimir el botón B, los clicks del ratón dentro de la ventana desplegarán cuadros azules.

Al oprimir el botón R, los clicks del ratón dentro de la ventana desplegarán cuadros rojos.
Al oprimir el botón G, los clicks del ratón dentro de la ventana desplegarán cuadros verdes. Los cuadros verdes representan los nuevos valores de entrada que el algoritmo KNN clasificará. 

Presione 1, 3, 5, 7 o 9 para seleccionar un valor de k diferente al valor inicial K=1. 
Se recomienda que ingrese algunos cuadros rojos, otros azules y uno verde. Luego de esto, oprima la tecla C para calcular el resultado, clasificando el cuadro verde entre la clase roja y azul.
Presione la tecla ESC para finalizar la ejecución del programa.
