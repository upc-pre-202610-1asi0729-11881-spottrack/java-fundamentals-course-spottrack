# Lección 3: Estructuras de Control — Solución

## Ejercicio 1. Completa el código siguiendo el tutorial, o puedes agregar cosas por tu cuenta.

```java
public class Main {
    public static void main(String[] args) {

        int edad = 15;

        if (edad >= 13) {
            System.out.println("Puedes crear una cuenta.");
        } else {
            System.out.println("Necesitas tener al menos 13 años.");
        }

    }
}
```

## Ejercicio 2. Recorre los números del 1 al 10 usando un bucle for.

```java
public class Main {
    public static void main(String[] args) {

        for (int i = 1; i <= 10; i++) {
            System.out.println("Número: " + i);
        }

    }
}
```

## Ejercicio 3. Usa un bucle while para contar vidas.

```java
public class Main {
    public static void main(String[] args) {

        int vidas = 3;

        while (vidas > 0) {
            System.out.println("Sigues en el juego. Vidas: " + vidas);
            vidas--;
        }

        System.out.println("Game over.");

    }
}
```