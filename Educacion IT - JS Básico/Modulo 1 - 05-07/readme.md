# **_Fundamentos de Javascript e instalacion de herramientas_**

herramientas :

- VSC
- Node JS
- NPM (cualquier package manager)

### **_Introducción a la programacion :_**

Podemos definir un programa como una secuencia de instrucciones finita que ejecuta un procesador de una computadora con el fin de realizar un proceso, completar una tarea, etc.

- "Un programa es un plan que se va a llevar a cabo"
- "Un programa no sabe hacer lo que no esta programado para hacer"

### **_¿Qué es el pseudocódigo?_**

Es un codigo omite detalles de lo que se usara a final, representa un bosquejo de lo que programaremos despues. Se utiliza para planificar aquello que llevaremos, dar mayor entendimiento a los problemas que debemos solventar, nos permite explicar y compartir ideas con nuestros pares a la hora de trabajar en equipo.

### **_¿Qué es una aplicación?_**

Una app es un programa especifico hecho para resolver un problema especifico.
Existen varios tipos de apps :

- App de escritorio
- App de consolas (bash. powershell)
- Aplicaciones web
- Aplicaciones mobile

### **_¿Qué es un lenguage de programación?_**

Se trata de un lenguage formal, con reglas estrictas de escritura, el cual nos permite comunicarle a quien vaya a ejecutar el programa, que y como interpretar el programa.
Todo lenguaje se conforma por simbolos, signos de puntuación, operadores, valores, pakabras clav e identificadores que permiten escribir instrucciones a ejecutar.

### **_Javascript_**

En particular, JS corre y se ejecuta en los navegadores, son ellos quienen interpretan nuestros programas.
Una web se conforma de tres partes fundamentales (pueden variar) :

- HTML
- CSS
- JAVASCRIPT
  Con JS podemos convertir nuestras páginas estaticas en dinámicas.

### **_¿Cómo implementamos JS?_**

Tenemos tres maneras :

- Internas (scripts) :

  ```
  <script>
  console.log("Hola Mundo")
  </script>
  ```

- En linea : cuando la implementacion esta dentro de la etiqueta html (no se utiliza)

  ```
  <script onLoad="alert('Hola Mundo')">
  ```

- Externo : cuando el codigo se encuentra en un fichero aparte de extensión .js

  ```
  <script src="index.js">

  ```

### **_Comenzando con un HTML_**

Para crear el esqueleto de un fichero html en VSC basta con tipear "!" y el editor de código completara el texto por nosotros.

En el fichero index.html se especifica el resto de ejercicios y conceptos de la clase.

Para ejecutar los ficheros html podemos :

- Abrirlos en algun navegador.
- Utilizar Live Server
- Utilizar Open in Browser

Javascript es un lenguaje de tipado dinámico, es decir que no restringe las variables a un tipo de dato.
