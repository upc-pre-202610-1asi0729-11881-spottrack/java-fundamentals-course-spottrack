# Lección 6: Introducción a la POO

## Ejercicio 1. Completa el código siguiendo el tutorial, o puedes agregar ocsas por tu cuenta.
public class Zombi {
    int vida;
    double daño;

    public Zombi() {
        this.vida = 10;
        this.daño = 5;
    }

    void atacar() {
        System.out.println("El zombi te ataca y te quita " + this.daño + " corazones");
    }

    public static void main(String args[]) {
        Zombi zombi = new Zombi();
        zombi.atacar();
    }
}
