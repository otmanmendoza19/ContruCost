# ConstruCost

**ConstruCost** es una aplicación web orientada a la elaboración y gestión de **Análisis de Precios Unitarios (APU)** para actividades de construcción.

El proyecto nace como una propuesta para facilitar la organización de materiales, mano de obra, equipos y demás recursos que intervienen en la elaboración de un APU, buscando ofrecer una interfaz más organizada y especializada que una hoja de cálculo tradicional.

> Actualmente, el proyecto se encuentra en una primera etapa de desarrollo enfocada en el diseño de la interfaz y la estructura visual de la aplicación.

---

## Estado actual

Actualmente ConstruCost se encuentra en fase de **diseño y maquetación frontend**.

### Tecnologías utilizadas

- HTML5
- CSS3

### Próximas tecnologías

A medida que avance el proyecto se contempla incorporar:

- JavaScript
- PHP o Spring Boot
- MySQL
- Generación de reportes en PDF

Estas tecnologías se incorporarán posteriormente, por lo que **actualmente no forman parte de la implementación funcional del proyecto**.

---

## Funcionalidades previstas

La aplicación está diseñada para crecer progresivamente y contará con diferentes módulos.

### Autenticación

- Inicio de sesión
- Registro de usuarios
- Cierre de sesión

### Dashboard

Panel principal para visualizar de manera general la información del sistema.

Se contempla mostrar:

- Cantidad de APU registrados
- Cantidad de materiales
- Cantidad de proveedores
- Cantidad de equipos y maquinaria
- APU registrados recientemente

### APU

Módulo principal de ConstruCost.

Permitirá crear y administrar Análisis de Precios Unitarios asociados a diferentes actividades de construcción.

Cada APU podrá contener:

- Código
- Nombre de la actividad
- Unidad
- Descripción
- Materiales
- Mano de obra
- Equipos y maquinaria
- Herramienta menor
- Costos parciales
- Costo directo unitario

### Materiales

Permitir gestionar los materiales utilizados en las actividades de construcción.

Información prevista:

- Nombre del material
- Unidad de medida
- Precio unitario
- Proveedor

### Mano de obra

Se busca trabajar con **cuadrillas de trabajo**, permitiendo definir los recursos humanos necesarios para ejecutar una actividad.

Se contempla manejar:

- Nombre de la cuadrilla
- Personal que la compone
- Roles o cargos
- Cantidad de trabajadores
- Costo de mano de obra
- Rendimiento diario

### Equipos y maquinaria

Permitir registrar los equipos y maquinaria utilizados en las actividades.

Información prevista:

- Nombre
- Unidad
- Costo
- Proveedor

### Proveedores

Módulo para administrar los proveedores relacionados con materiales, equipos y otros recursos.

---

## Herramienta menor

La herramienta menor se manejará inicialmente mediante una opción sencilla dentro del APU.

El usuario podrá indicar si desea incluirla y posteriormente se podrá establecer el porcentaje correspondiente.

---

## Reportes

Como parte de las futuras funcionalidades se contempla la generación de un **reporte del APU en formato PDF**.

El reporte podrá incluir:

- Información general de la actividad
- Materiales
- Mano de obra
- Equipos y maquinaria
- Herramienta menor
- Subtotales
- Costo directo unitario

---

## Estructura inicial del proyecto

Actualmente el proyecto está enfocado principalmente en la construcción de las interfaces mediante HTML y CSS.

Una estructura inicial puede organizarse de la siguiente manera:

```text
ConstruCost/
│
├── css/
│   ├── inicio.css
│   ├── registro.css
│   ├── dashboard.css
│   └── apu.css
│
├── vistas/
│   ├── inicio.html
│   ├── registro.html
│   ├── dashboard.html
│   └── apu.html
│
└── README.md
```
