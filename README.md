# Sistema de Gestión Institucional

## Descripción

Sistema web de gestión institucional desarrollado bajo el patrón **MVC**, orientado a la administración integral de un instituto educativo.
El sistema permite gestionar estudiantes, docentes, cursos, inscripciones, pagos, facturación y reportes contables, optimizando los procesos administrativos y financieros de la institución.

El proyecto fue desarrollado como **solución real en producción** para una institución educativa.

> ⚠️ **Nota:** El código fuente se mantiene **privado por motivos de confidencialidad**, pero puede ser revisado durante una entrevista técnica.

---

## Funcionalidades Principales

### 📚 Gestión Académica

* Gestión de estudiantes, docentes y cursos
* Inscripciones a cursos
* Control de cuotas y pagos
* Administración de sedes

### 💰 Gestión Financiera

* Registro de pagos
* Facturación autoimpresa (Paraguay)
* Libro de ventas
* Libro de compras
* Gestión de productos y proveedores

### 📊 Reportes

* Generación de reportes en **PDF**
* Exportación de reportes en **Excel**
* Reportes de pagos realizados
* Reportes contables y administrativos

### 🔐 Seguridad y Control

* Autenticación de usuarios
* Gestión de usuarios y roles
* Registro de auditorías del sistema

---

## Arquitectura

El sistema está desarrollado utilizando el patrón **Modelo–Vista–Controlador (MVC)**, separando claramente la lógica de negocio, la presentación y el control de la aplicación.

### Controladores Principales

* `auditoriasControlador.php`
* `clientesControlador.php`
* `comprasControlador.php`
* `cuotasControlador.php`
* `cursosControlador.php`
* `docentesControlador.php`
* `estudiantesControlador.php`
* `inscripcionesControlador.php`
* `loginControlador.php`
* `pagosControlador.php`
* `productosControlador.php`
* `proveedoresControlador.php`
* `registrosControlador.php`
* `sedesControlador.php`
* `usuarioControlador.php`
* `vistasControlador.php`

---

## Tecnologías Utilizadas

### Backend

* PHP (arquitectura MVC)

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

### Base de Datos

* MySQL

### Librerías

* **PhpOffice** (exportación a Excel)
* **FPDF** (generación de reportes en PDF)

---

## Facturación

El sistema implementa **factura autoimpresa conforme a la normativa vigente en Paraguay**, permitiendo:

* Emisión de comprobantes
* Control de ventas
* Registro automático en libro de ventas

---

## Reportes

* Descarga de reportes en formato **PDF**
* Exportación de datos en **Excel**
* Reportes de pagos, ventas y compras

---

## Estado del Proyecto

🟢 **Finalizado y en uso**

---

## Autor

**Alexis Rolando Alderete Araujo**
Desarrollador de Software – Estudiante avanzado de Ingeniería en Informática

* LinkedIn: [https://linkedin.com/in/alexis-alderete](https://linkedin.com/in/alexis-alderete)
* GitHub: [https://github.com/alexisalderete](https://github.com/alexisalderete)

---

## Nota para Reclutadores

Este proyecto corresponde a un sistema real utilizado por una institución educativa.
Por razones de confidencialidad, el código fuente se mantiene privado, pero el diseño, arquitectura y decisiones técnicas pueden ser explicadas y revisadas durante una entrevista técnica.
