# Optimización del código en Java

## Buenas prácticas

- Evita código duplicado.
- Usa bucles `for-each` en lugar de `for` tradicional cuando sea posible.
- Usa estructuras de datos adecuadas (`ArrayList`, `HashMap`, etc.).
- Divide métodos largos en métodos más pequeños y específicos.

## Ejemplo de código optimizado

```java
for (String nombre : listaDeNombres) {
    System.out.println(nombre);
}
```
