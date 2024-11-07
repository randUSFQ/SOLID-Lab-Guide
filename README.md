# Guía de Laboratorio: Aplicación de los Principios SOLID en un Sistema de E-Commerce

## Objetivo General
Desarrollar habilidades para aplicar los principios SOLID en el diseño de software de un sistema de e-commerce, mejorando su mantenibilidad, escalabilidad y flexibilidad mediante buenas prácticas de programación orientada a objetos.

## Objetivos Específicos
1. Comprender la teoría y aplicación de cada principio SOLID mediante la revisión de código y ejercicios prácticos.
2. Refactorizar código existente de un sistema de e-commerce para cumplir con los principios SOLID.
3. Evaluar el impacto de SOLID en la modularidad y extensibilidad del sistema de e-commerce.

---

## Código Inicial del Sistema de E-Commerce (Simplificado en Java)

Ubicado en el directorio `src/ecommerce/`.

### `Product.java`
```java
public class Product {
    private String name;
    private double price;

    public Product(String name, double price) {
        this.name = name;
        this.price = price;
    }

    public String getName() { return name; }
    public double getPrice() { return price; }
}