# Lección 4: Estructuras de Datos Simples — Solución

## Ejercicio 1. Completa el array y accede a sus elementos.

```java
public class Main {
    public static void main(String[] args) {

        int[] notas = {85, 92, 70, 88, 95};

        System.out.println("Primera nota: " + notas[0]);
        System.out.println("Tercera nota: " + notas[2]);
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
            System.out.println("Nota " + (i + 1) + ": " + notas[i]);
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
            new Estudiante("Ana", 92),
            new Estudiante("Luis", 78),
            new Estudiante("María", 85)
        };

        Estudiante mejor = salon[0];

        for (int i = 1; i < salon.length; i++) {
            if (salon[i].nota > mejor.nota) {
                mejor = salon[i];
            }
        }

        System.out.println("Mejor nota: " + mejor.nombre + " con " + mejor.nota);

    }
}
```