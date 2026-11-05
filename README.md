# RetoPython
# JAVA
<!-- Investigar cómo se escribe un condicional (if/else) o un bucle (for/while) en vuestro lenguaje asignado.
Escribir un ejemplo. Podéis utilizar los ejemplos de abajo o inventar uno propio.
Crear un repositorio en GitHub utilizando Git y subir:
El archivo con vuestro código.
Un README.md con los nombres de los integrantes, el lenguaje asignado y las respuestas a estas preguntas:

¿Cómo se declaran las variables?
Indicando el tipo de las variables. Ej
int numero = 20;

¿Cómo se delimitan los bloques de código?
A diferencia de Python, los bloques de código se delimitan con llaves; {}

¿Qué cambia en la sintaxis respecto a Python?
- Declarar el tipo de variables
- Las condiciones tienen que estar entre paréntesiss
- Todos los bloques tienen que cerrarse con corchetes: {}
- System.out.println()
- Todas las líneas de código acaban en ;

¿Qué parte de la lógica se mantiene igual? -->
<!-- - La parte lógica es igual -->

BUCLES

public class Bucles {
    public static void main(String[] args) {

        String[] nombres = {"Ana", "Pedro", "Lucía"};

        for (String nombre : nombres) {
            System.out.println("Hola " + nombre);
        }

    }
}