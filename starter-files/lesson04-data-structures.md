# Lección 4: Estructuras de Datos Simples

## Ejercicio 1. Completa el array y accede a sus elementos.

```java
public class Main {
    public static void main(String[] args) {

        int[] notas = { , , , , }; // TODO: agrega 5 notas de tu elección

        System.out.println("Primera nota: " + notas[0]);
        System.out.println("Tercera nota: " + notas[ ]); // TODO: índice correcto
        System.out.println("Total de notas: " + notas.length);

    }
}
```

## Ejercicio 2. Recorre el array completo con un bucle for.

```java
public class Main {
    public static void main(String[] args) {

        int[] notas = {85, 92, 70, 88, 95};

        for (int i = 0; i < notas.length; i++) {
            // TODO: imprime cada nota con su número de posición (desde 1)
        }

    }
}
```

## Ejercicio 3. Crea tu propio array de objetos Estudiante.

```java
class Estudiante {
    String nombre;
    int nota;

    Estudiante(String nombre, int nota) {
        this.nombre = nombre;
        this.nota = nota;
    }
}

public class Main {
    public static void main(String[] args) {

        Estudiante[] salon = {
            new Estudiante(" ", ), // TODO: agrega nombre y nota
            new Estudiante(" ", ), // TODO: agrega nombre y nota
            new Estudiante(" ", )  // TODO: agrega nombre y nota
        };

        Estudiante mejor = salon[0];

        for (int i = 1; i < salon.length; i++) {
            if (salon[i].nota > mejor.nota) {
                mejor = ; // TODO: actualiza al mejor estudiante
            }
        }

        // TODO: imprime el nombre y nota del mejor estudiante

    }
}
```