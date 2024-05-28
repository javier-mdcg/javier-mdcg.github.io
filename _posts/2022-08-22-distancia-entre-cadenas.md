---
layout: post
categories:
  - Proyecto
tags:
  - Estructuras de datos
  - Java
last_modified_at: 2022-08-22T14:25:52-06:00
---

Este proyecto de Java proporciona una implementación del algoritmo de distancia de edición para calcular la distancia entre dos cadenas. El repositorio está disponible en <a href= "https://github.com/javier-mdcg/DstanciaEntreCadenas">GitHub</a>.

El algoritmo de distancia de edición, también conocido como distancia de Levenshtein, es una medida de la cantidad mínima de operaciones necesarias para transformar una cadena en otra. Estas operaciones pueden ser inserciones, eliminaciones o sustituciones de caracteres.

## Uso

Puedes utilizarse esta funcionalidad en proyectos de Java siguiendo estos pasos:

1. Incluír la clase `distanciaEntreCadenas` en el proyecto Java.
2. Llamar al método `calculaDistancia(String s1, String s2)` proporcionando las dos cadenas que se desea comparar. Este método devolverá la distancia entre las cadenas.

```java
int distancia = distanciaEntreCadenas.calculaDistancia("cadena1", "cadena2");
System.out.println("La distancia entre las cadenas es: " + distancia);
```

## Ejemplo

```java
public class Main {
    public static void main(String[] args) {
        
        System.out.println(distanciaEntreCadenas.calculaDistancia("hola", "holse"));
    }
}
```
En este ejemplo la salida es `2`, pues se requieren dos operaciones para llegar de una cadena a la otra.