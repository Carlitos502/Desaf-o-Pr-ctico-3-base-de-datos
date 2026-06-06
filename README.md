Este repositorio contiene la arquitectura de datos diseñada para la **Constructora Futura**. El sistema permite la gestión eficiente de proyectos de infraestructura, asegurando la integridad de la información financiera y la trazabilidad operativa.

 Objetivos Técnicos
* **Gestión de Fondos:** Implementación de una jerarquía `ISA` para la administración exclusiva entre Créditos Bancarios y Subsidios Estatales.
* **Control Operativo:** Gestión dinámica de expertos externos y sus competencias técnicas aplicadas a proyectos específicos.
* **Normalización:** Diseño relacional normalizado para eliminar redundancias y garantizar la consistencia de los datos.

Arquitectura del Modelo
El diseño se divide en dos etapas fundamentales:

### 1. Modelo Entidad-Relación (MER)
Representación conceptual de las entidades: `Financiaciones`, `Proyectos`, `Subcontratistas` y `Especialidades`. 

### 2. Modelo Relacional (MR)
Implementación física incluyendo claves primarias (PK), claves foráneas (FK) y relaciones referenciales.

Implementación Técnica
El modelo fue desarrollado utilizando **DBML (Database Markup Language)** y visualizado mediante **dbdiagram.io**.
