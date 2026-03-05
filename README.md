# EjerciciosCAP2
El repositorio incluye:

* Las implementaciones de los ejercicios en Flex.
* Archivos de entrada utilizados para las pruebas.
* Un informe donde se explica el proceso de desarrollo, las modificaciones realizadas y los resultados obtenidos.

---

## Contenido del proyecto

* `ejercicio1.l` → Programa que procesa archivos de texto y muestra las líneas numeradas.
* `ejercicio2.l` → Programa que genera una concordancia de palabras ignorando la diferencia entre mayúsculas y minúsculas.
* `ejercicio3.l` → Versión modificada del programa de concordancia con una tabla de símbolos que puede crecer dinámicamente.

También se incluyen archivos de prueba como:

* `entrada.txt`
* `entrada1.txt`
* `entrada2.txt`
* `entrada3.txt`
* `entrada4.txt`

Estos archivos fueron utilizados para verificar el funcionamiento de cada programa.

---

## Requisitos

Para ejecutar los programas es necesario tener instalado:

* **Flex**
* **GCC**
* Un entorno Linux o una terminal compatible.

---

## Compilación

Para compilar cualquiera de los ejercicios se utilizan los siguientes comandos:

```bash
flex nombre_del_archivo.l
gcc lex.yy.c -o programa -lfl
```

Ejemplo:

```bash
flex ejercicio1.l
gcc lex.yy.c -o ejercicio1 -lfl
```

---

## Ejecución

Una vez compilado el programa, se ejecuta indicando los archivos de entrada:

```bash
./programa archivo1.txt archivo2.txt
```

Ejemplo:

```bash
./ejercicio2 entrada1.txt entrada2.txt
```

El programa procesará los archivos y mostrará los resultados en la terminal.

---


