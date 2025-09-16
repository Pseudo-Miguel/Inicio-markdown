# Hola mundo en java
### Necesitaremos

1. Visual Studio Code
2. JDK
3. Un ordenador

### Explicación

Instalamos Visual Studio Code desde su [web oficial](https://code.visualstudio.com/) o desde la tienda de microsoft. Dentro de la aplicacion, instalamos el pack de extensiones [*Extension Pack for Java*](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack).

Para instalar el JDK solo tenemos que descargarlo de su [web oficial](https://www.oracle.com/es/java/technologies/downloads/), abrir el ejecutable y crear la variable de entorno de java

Despues de preparar el IDE y el JDK debemos crear una carpeta donde guardar el proyecto.

Dentro de Visual Code abrimos la carpeta y creamos el proyecto de Java

La carpeta src es en la cual vamos a programar.

#### Código

public class holamundo{

    public static void main(String [] args){
        System.out.println("Hola mundo");
    }

}

#### Código explicado

- **public class holamundo**. El archivo contiene una clase publica donde holamundo es el nombre del archivo que usamos

- **public class void main (String [] args)**. Es la clase principal del codigo

- **System.out.println("")**. Lanza el mensaje entrecomillado por consola con un salto de linea.