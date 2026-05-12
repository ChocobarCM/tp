# Propuesta TP DSW

## Grupo
### Integrantes
50968 Chocobar Carlos Maximo  
47340 Tarantola Federico
50309 Taborda Astudilla Santiago


### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema- Gestión de Casos Criminales-

### Descripción
Plataforma web full-stack diseñada para la centralización y seguimiento de investigaciones delictivas en la ciudad. El sistema permite a las fuerzas de seguridad gestionar expedientes, catalogar evidencias vinculadas y administrar el cuerpo de oficiales, facilitando la visualización de datos críticos para la resolución de crímenes

### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo de Delito<br>2. CRUD Oficial/Detective<br>3. CRUD Ubicación/Zona|
|CRUD dependiente|1. CRUD Caso Criminal (depende de Tipo de Delito) <br>2. CRUD Evidencia (depende de Caso Criminal)|
|Listado<br>+<br>detalle| Listado de Casos filtrado por Zona => detalle del Caso y Oficial asignado. => detalle CRUD Habitacion<br> 2. Listado de Oficiales por Estado (Activo/Inactivo) => detalle de casos resueltos por el oficial.|
|CUU/Epic|1. Confección y Apertura de nuevo expediente criminal.<br>2.Auditoría de movimientos y cambios de estado en un caso.|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |a definir|
|CUU/Epic|a definir|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |a definir|
|CUU/Epic|1. a definir|
|Otros|1. a definir|

