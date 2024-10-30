Solucion Ejercicio 1:

import java.util.Scanner;

public class Saludo {
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Escriba su nombre: ");
        
        String nombre = scanner.nextLine();
        
        System.out.print("Escriba su apellido: ");
        
        String apellido = scanner.nextLine();
        
        System.out.println("Mi nombre es " + nombre + " " + apellido + "!");

  Solucion Ejercicio 2

  import java.util.Scanner;

class Calculo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Introduzca el primer número: ");
        int numero1 = scanner.nextInt();  // Usar nextInt() para leer un entero
        
        System.out.print("Introduzca otro número: ");
        int numero2 = scanner.nextInt();  // Usar nextInt() para leer el segundo entero
        
        int suma = numero1 + numero2;  // Realizar la suma
        
        System.out.println("La suma de los números que ha elegido es: " + suma + "!");

        
