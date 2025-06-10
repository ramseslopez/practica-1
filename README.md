# Práctica 1: Expresiones y Tipos. 📌

En esta práctica se tocarán los temas de las expresiones tanto aritmércas como lógicas, así como el uso de la clase _String_ y _Math_.

## Autores 😊
* **Salvador López Mendoza** - *Titular* - [Correo](slm@ciencias.unam.mx)
* **Gerardo Emiliano Figueroa Sandoval** - *Teoría* - [Emiliano-Fs](https://github.com/Emiliano-FS)
* **Ramsés Antonio López Soto** - *Laboratorio* - [ramseslopez](https://github.com/ramseslopez)
  
## Objetivos 🚀

- Comprender la declaración de variables, constantes y asignación de valores.
- Aprender a utilizar los diferentes tipos de operadores.
- Comprender a los tipos primitivos y su uso en expresiones.
- Aprender a hacer uso de la clase String y Math, y a leer la documentación oficial de la mismas.

### Pre-requisitos 📋

- Sistema Operativo Linux (Ubuntu, Debian, Fedora, etc.)
- Git versión 2.43.0
- Java versión 21.0.7
- Perfil de GitHub

### Instalación 🔧

- Git

Para instalar la versión más reciente de Git:
```bash
sudo apt-get install git
```
Una vez instalado, verifica la versión instalada.
```
git -v
```

- Java
  
Instala Java con el siguiente comando:
```
sudo apt-get install openjdk-21-jre
```
Al finalizar, verifica la versión instalada.
```
java --version
```
y también del compilador:
```
javac --version
``` 

## Recursos 📖

Puedes encontrar más información de los recursos a utilizar en:
- [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)
- [Math](https://docs.oracle.com/javase/8/docs/api/java/lang/Math.html)
- [Scanner](https://docs.oracle.com/javase/8/docs/api/java/util/Scanner.html)

## Ejercicios ⌨️

Resuelve los siguientes ejercicios:

### Área y Volúmen

Implementa un programa que determine el área y volumen de un prisma triangular y un toroide.

  * En el caso del prisma triangular, el programa debe de solicitar un lado del triángulo y la altura del prisma en centímetros. Las fórmulas que se necesitan son las siguientes:

    - Área:

    $$a_{total} = a_{lateral} + 2\cdot a_{base}$$
    
    - Volúmen:

    $$v = a_{base} \cdot h$$

    La salida del programa debe ser la siguiente:

    ```
    Ingresa un lado del triángulo: 3 
    Ingresa la altura del prisma: 9

            ***  Área y volumen del prisma triangular ***
                El  área del prisma es: 88.79 cm^2
                El volumen del prisma es: 35.07 cm^3
    ```
  * En el caso del toroide, el programa debe de solicitar el radio mayor y el radio menor en centímetros. Las formulas que se necesitan son las siguientes:

    - Área:

      $$a = 4\cdot \pi^2\cdot R\cdot r$$

    - Volúmen:

      $$a = 2\cdot \pi^2\cdot R\cdot r^2$$

    La salida del programa debe ser la siguiente:

    ```
    Ingresa un lado del triángulo: 3 
    Ingresa la altura del prisma: 9

            ***  Área y volumen del prisma triangular ***
                El  área del prisma es: 88.79 cm^2
                El volumen del prisma es: 35.07 cm^3
    ```
### Nickname

Implementa un programa que genere un _nickname_ para una plataforma de videojuegos online de la siguiente manera:

- El programa solicita el nombre completo del usuario separando el nombre y los apellidos por una coma.
- El programa también solicita la fecha de nacimiento del usuario en el formato **dd/mm/aaaa**.
- El _nickname_ se debe formar por:
  - El nombre de pila concatenando la primera y última letra de su nombre en mayúsculas (en caso de que haya segundo nombre, solo considera el primero).
  - El año de su nacimiento.
  - Las primeras tres letras de su segundo apellido en mayúsculas.
  - Su mes de nacimiento.
  - Las últimas dos letras de su primer apellido en mayúsculas.
  - Agregar el día de nacimiento.
  - Y al final agregar la cadena `#<*>@`.

La salida del programa debe de verse como se muestra a continuación:

```
Te damos la bienvenida a nuestro sitio.
Ingresa tu nombre completo separando nombre y apellidos por una coma.
> Ramses, Lopez Soto
Ingresa tu fecha de nacimiento en el formato dd/mm/aaaa:
> 20/10/2006
Tu nuevo nombre de usuario es: RamsesRS06SOT10EZ20#<*>@
```

## Intrucciones

* La práctica se entrega de forma individual.
* Debes de clonar el este repositorio, agregar tu nombre en la parte de `Nombre: ` y seguido de tu número de cuenta en `NumCuenta: `.
* El código debe ser legible y el nombre varialbes y métodos debe ser adecuado.
* Sube la solución de la práctica antes de las 23:59 del día de mañana.
* Ningún tipo de copia y/o plagio será tolerado.

## Licencia 📄

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para más detalles.
