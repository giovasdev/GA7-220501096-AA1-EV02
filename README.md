# 🧠✨ Estándares de Codificación - Paradigma Orientado a Objetos

## 📌 Objetivo
Definir un conjunto de **estándares de codificación** para el desarrollo de software, asegurando buenas prácticas, coherencia, mantenibilidad y calidad del código, de acuerdo con el componente formativo **"Aplicación del paradigma orientado a objetos"**.

---

## 🛠️ Plataforma de Desarrollo

- 💻 Lenguaje: **Java**
- 📦 IDE recomendado: **IntelliJ IDEA / Eclipse / NetBeans**
- 🧱 Paradigma: **Programación Orientada a Objetos (POO)**

---

## ✍️ Estándares de Codificación

### 🔤 Nombres (Naming Conventions)
- **Clases**: `PascalCase` → `ClienteController`
- **Métodos**: `camelCase` → `calcularPromedio()`
- **Variables**: `camelCase` → `totalVentas`
- **Constantes**: `MAYÚSCULAS_CON_GUIONES` → `MAX_USUARIOS`

---

### 🧩 Organización del Código

- ✅ Una clase por archivo
- ✅ Uso correcto de los modificadores de acceso (`public`, `private`, `protected`)
- ✅ Separar capas lógicas (modelo, vista, controlador)
- ✅ Documentar con **JavaDoc** cada clase y método

---

### 📄 Estructura Básica de una Clase

```java
/**
 * Clase que representa un producto en inventario.
 * @author Andres
 */
public class Producto {
    private int id;
    private String nombre;
    private double precio;

    public Producto(int id, String nombre, double precio) {
        this.id = id;
        this.nombre = nombre;
        this.precio = precio;
    }

    public double calcularImpuesto() {
        return precio * 0.19;
    }

    // Getters y Setters
}
