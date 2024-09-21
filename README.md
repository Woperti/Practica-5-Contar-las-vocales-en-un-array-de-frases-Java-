# Practica-5-Contar-las-vocales-en-un-array-de-frases-Java

1. Crea un metodo que cuente las vocales en un array de frase.

```java
  public class ContadorVocales {

    public static int contarVocales(String cadena) {
       /* Escribe aqui tu codig */
      
    }

    public static void testContarVocales(String cadena, int resultadoEsperado) {
        int resultadoObtenido = contarVocales(cadena);
        System.out.println("Cadena: " + cadena);
        System.out.println("Vocales contadas: " + resultadoObtenido);
        
        if (resultadoObtenido == resultadoEsperado) {
            System.out.println("Test passed.");
        } else {
            System.out.println("Test case not passed. Se esperaba: " + resultadoEsperado);
        }
        System.out.println();
    }

    public static void main(String[] args) {
        System.out.println("\n--- Ejecutando tests ---");
        testContarVocales("leetcode", 4); 
        testContarVocales("AEIOU", 5); 
        testContarVocales("abcde", 2); 
        testContarVocales("xyz", 0);
        testContarVocales("aEiOu", 5);  
    }
}
```
