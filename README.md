# Book Manager

## Sprint actual: Sprint 1

## Objetivo

Aplicar los conocimientos adquiridos en programación orientada a objetos y
almacenamiento de datos en archivos para su persistencia.

## Introducción y contexto

Una librería con venta al público necesita modernizar su sistema de gestión de
inventario de libros. Debido a la fluctuación en los costos de importación de
material bibliográfico, el sistema debe gestionar precios en diferentes monedas
y seguir de cerca la cotización del dólar para actualizar sus valores en tiempo
real.

Se desarrolla una aplicación de consola (CLI) en Python que permite gestionar el
inventario de la librería, cotizar los libros según el valor del dólar y
comparar precios con la competencia web, tomando como referencia el sitio
Cúspide.

### Entidades del sistema

- **Libro**: cada título del catálogo.
- **Genero**: categoría literaria del libro.
- **Editorial**: proveedor/distribuidora de los libros.
- **Moneda**: monedas en las que se expresa un precio (ARS, USD, etc.).
- **TipoCotizacion**: tipos de cotización del dólar (Oficial, Blue, MEP, etc.).
- **Precio**: valor de un libro en una moneda determinada.
- **Stock**: cantidad disponible de cada libro.
- **CotizacionDolar**: registro histórico de cotizaciones por tipo y fecha.