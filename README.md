![Edteam Logo](./assets/logo.svg)

>Gestión y Desarrollo de Proyectos Web

# Cierre de ventas y levantar requerimientos

## Ciclo de ventas
Las ventas tienen un ciclo

Prospecto es cualquier persona que puede ser un cliente

Prospecto no es cliente, no hay que confundir

Los prospectos deben ser calificados manualmente, la idea es que este prospecto se convierta en cliente

CRM nos ayudan a prospectar y a calificar a nuestros prospectos

B2B empresa que vende a empresas
B2C empresa que vende a clientes

Los prospectos se convierten en oportunidad cuando muestran interés

Prospecto - Evualar - Oportunidad 

Venta perdida se lo:
1. Incuba
2. Lead nutturing (Nutrir al propecto)
3. Descartar (Si es muy regateador)

Venta cerrada:
1. Up sellig 
2. Cross selling
3. Fidelización

## Producto
El producto es tangible y la marca es algo intangible

## Marca

Construcción de la marca | LINKEAR
Reputacion o personalidad

## Cotizacion

Ya cuando se convirtio un prospecto en oportunidad

Cotizacion aproximada en una primera etap
Plazo aproximado en un primera etapa

## Levantar requerimientos

https://bit.ly/2INInmO

- Brief (cuestionario)
  Es necesario saber que quiere el cliente especificamente
  - Identificar el problema a solucionar  

## Contrato de servicios

https://bit.ly/2tM3g7x

# UX/UI

## Wireframes
Hacer primero los wireframes antes de continuar para que todos los participantes del equipo conozcan sobre el proyecto.

Distribuir el espacio con la información que se necesite.

Trabajar en la experiencia de usuario que sea intuitivo.

Es importante realizar a un grupo de personas que nos ayuden con el feedback

Disminuir la cantidad de pasos para llegar

Despues de realizar los wireframes se debe realizar el prototipo y probarlo 

## Mockups

! Importante , guías de estilo

https://www.prototypr.io/prototyping-tools/

# Diseño de la base de datos

Requerimientos

Para diseñar una buena base de datos nos ayuda el prototipo, porque nos da un un flujo de usuario y vemos lo que necesitamos guardar en la base de datos.

Diseño Conceptual. Modelos dependiendo del tipo de la base de datos que vamos a trabajar

Base de datos relacional
Base de datos no relacional
New SQL

Diseño Lógico. aterrizar en una base de datos.

Diseño Físico. Motores de base de datos.

### Entidades. representan un objeto (elemento) del universo de discurso (problema a resolver)

- Entidad Débil. 
Representa un objeto (elemento) del univarso de discurso pero necesita de una relación con tora entidad para poder identificarse


### Atributos. 
Los atributos representan las caracteristicas de las entidades

1. Atributo simple y monovaluado
2. Atributo identificador principal
3. Atributo multivaluado
4. Atributo opcional
5. Atributo compuesto

### Relaciones. 
Que hay entre las entidades y la unión entre las mismas

1. Restricciones son el tipo de correspondencia de cardinalidades

[E] (0,1) --- 1:N --- (0,N) [E]

Para BigData debemos trabajar con MongoDB

# Flujo de trabajo con git

> git init . inicia un repositorio en la carpeta actual

[Untraked] - [Unmodified] - [Modified] - [Staged]

[Untraked] ------ Add File ------> [Staged]
[Unmodified] ---- Edit the File ----> Stage the file
[Modified]
[Untraked] <---- Remove the file ----[Unmodified]
[Unmodified] <---- Commit ----- [Staged]

> git add . Agrega un archivo a la zona de preparacion

> git commit . Confirma los archivos preparados

> .gitignore . patrones de nombres de archivos que git ignorara 

> git log . muestra el historial de confirmaciones


Metodologia de trabajo
Cuando van hacer un push, es primero hacer un pull antes de un push

