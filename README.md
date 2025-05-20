# Calculadora en Java con Swing

Esta es una aplicación de calculadora simple desarrollada en Java utilizando la biblioteca Swing para la interfaz gráfica. Permite realizar operaciones aritméticas básicas como suma, resta, multiplicación, división, raíz cuadrada y potencias.

## 📋 Características

- Interfaz gráfica amigable con botones para dígitos y operaciones.
- Soporta las operaciones:
  - Suma (`+`)
  - Resta (`-`)
  - Multiplicación (`x`)
  - División (`/`)
  - Raíz cuadrada (`√`)
  - Potencia (`^`)
- Control de errores al dividir por cero o ingresar datos no válidos.
- Botón de limpieza (`C`) para borrar la entrada.
- Salida del programa con botón `Salir`.

## 🛠️ Requisitos

- Java JDK 8 o superior
- IDE que soporte Java (NetBeans, IntelliJ, Eclipse, etc.)

## 🚀 Ejecución

1. Clona o descarga este repositorio.
2. Abre el proyecto en tu IDE favorito.
3. Ejecuta la clase `vtn1.java` que contiene el método `main`.

```bash
javac vtn1.java
java vtn1
```

## 🧱 Estructura del Código

- `vtn1.java`: Clase principal que contiene toda la lógica de la calculadora y la interfaz gráfica.
- `txt1`: Campo de texto donde se muestran los números y resultados.
- `btn[0-9]`: Botones numéricos.
- `btnsuma`, `btnresta`, `btnmulti`, `btndiv`: Operaciones básicas.
- `btnraiz`, `btn19` (potencia): Operaciones adicionales.
- `btnigual`: Calcula el resultado.
- `jButton1`: Limpia la entrada.
- `btn17`: Cierra la aplicación.

## ✏️ Notas

- El operador raíz (`√`) se ejecuta al presionar `Igual` después de seleccionar la raíz.
- El botón de potencia espera dos valores: base y exponente.
- El punto decimal solo puede usarse una vez por número.

## 📌 Autor

Benyi Uriel Cordero Sanchez

---

¡Gracias por usar esta calculadora! Puedes modificarla y extenderla como desees.
