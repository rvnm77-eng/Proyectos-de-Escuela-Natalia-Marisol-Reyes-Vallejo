# Proyectos de Escuela — Natalia Marisol Reyes Vallejo

Repositorio con proyectos desarrollados a lo largo de la carrera de Ingeniería en Sistemas Computacionales en el Tecnológico Superior de Zapopan (TecMM).

## 🗂️ Índice de Proyectos

| Proyecto | Tecnología | Descripción |
| :--- | :--- | :--- |
| [Calculadora WYSIWYG](Calculadora-Swing/) | Java, Java Swing | Calculadora de escritorio con interfaz gráfica |
| Calculadora Android | Java, Android, XML | Calculadora móvil con diseño TableLayout |
| CRUD MySQL | Java, MySQL, JDBC | Sistema de gestión de alumnos |
| SQLite Android | SQLite, Android | Base de datos local móvil |
| Convertidor de Temp. | Java | Conversión entre escalas |
| Editor de Texto | Java Swing | Editor de texto básico |
| Instalación Linux | Linux | Documentación de instalación |
| Práctica SSH | SSH, Linux | Conexiones remotas seguras |
| Práctica DDL | SQL | Lenguaje de definición de datos |
| Práctica Proxy | Redes | Servidores proxy |
| Windows 2019 | Windows Server | Administración de sistemas |

---

##  Calculadora WYSIWYG — Java Swing
**Materia:** Tópicos Avanzados de Programación | **Docente:** Mtro. José Luis García Cerpas

Aplicación de escritorio con interfaz gráfica que realiza las cuatro operaciones aritméticas básicas, incluyendo validación de errores.

* **Conceptos:** Programación orientada a objetos, manejo de excepciones (`NumberFormatException`), componentes Swing.

---

##  Calculadora Android — Android Studio
**Materia:** Tópicos Avanzados de Programación

Aplicación móvil con interfaz construida en XML usando `TableLayout` para una cuadrícula responsiva.

* **Conceptos:** Diseño XML, arquitectura Android, compatibilidad API 21+.

---

##  CRUD Base de Datos MySQL
**Materia:** Tópicos Avanzados de Programación | **Docente:** Mtro. José Luis García Cerpas

Sistema de gestión de alumnos con operaciones CRUD y arquitectura MVC.

```sql
CREATE DATABASE escuela;
CREATE TABLE alumnos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(50) NOT NULL,
    edad INT NOT NULL
);
