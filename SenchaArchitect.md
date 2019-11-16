# Sencha Architect
Sencha Architect permite crear aplicaciones HTML5 arrastrando y soltando componentes, de modo que se pasa menos tiempo en la codificación manual, se evitan errores de codificación y el código de su aplicación se optimiza para obtener un alto rendimiento.
___
### Ventajas y Desventajas
| Ventajas de uso | Desventajas de uso |
| ---------- | ---------- |
| Posee componentes predefinidos   | Necesidad de ExtJS   |
| Menor codificación manual   | Programa pago   |
| Menos errores humanos en la codificación   | No poder modificar el 100% del código   |
| Ahorro de tiempo en codificación   
___
### Requisitos para la instalación
![](https://4.bp.blogspot.com/-gTiw6OELPy0/XJorCue1joI/AAAAAAAACkA/mII85pOuZKYLQlFx6wjkxgkJYrULjv4hQCLcBGAs/s1600/java.png)
Se requiere JDK a partir de la versión 1.6 en adelante.
___
### Pasos para la instalacion 
1. Descargar el paquete Sencha Architect desde la pagina oficial.
1. Abrir la terminal y posicionarse en la ubicación del paquete.
1. Descomprimir Sencha Architect mediante el siguiente comando: 
    ~~~
    tar -czvf nombre_del_paquete.tar.gz.
    ~~~
1. Luego ingresar a la carpeta descomprimida con el siguiente comando:
    ~~~
    cd /carpeta_descomprimida
    ~~~
1. Una vez dentro de la carpeta con la terminal ejecutar el siguiente comando:
    (Para transformar al archivo en un archivo ejecutable)
    ~~~
    sudo chmod +x "archivo.sh"
    ~~~
    
1. Por ultimo correr el siguiente comando:
    (Para ejecutar el archivo)
    ~~~    
    ./archivo.sh
    ~~~
1. Una vez realizados estos pasos se abrira una interfaz grafica de instalacion donde se debe aceptar las licencias, elegir el lugar de instalacion y por ultimo instalar.

    ![](https://raw.githubusercontent.com/benjagilardini/ImagenesMarkdown/master/ScreenInterfaz.png)
    ![](https://raw.githubusercontent.com/benjagilardini/ImagenesMarkdown/master/ScreenInterfaz2.png)
    ![](https://raw.githubusercontent.com/benjagilardini/ImagenesMarkdown/master/ScreenInterfaz3.png)
___
### Ejemplo realizado con Sencha Architect
Consiste en una pagina web muy simple que carga personas con nombre y apellido en una grilla, esta pagina esta compuesta por un modelo (nombre y apellido), un store (donde se guarda la informacion), una vista (los componentes) y un controller (donde se encuntra la funcion del boton)
![](https://raw.githubusercontent.com/benjagilardini/ImagenesMarkdown/master/Ejemplo.gif)