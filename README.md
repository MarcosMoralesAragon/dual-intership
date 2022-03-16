# Práctica Dual
## Empresa

<img src= "https://github.com/MarcosMoralesAragon/dual-intership/blob/main/Dekra.jpg" width="200" />
> Dekra digital

## Tecnologías


## Proyecto
El proyecto está compuesto de 2 partes:

-> [Front : Diseñado en Angular](https://github.com/MarcosMoralesAragon/portal-gestion) <img src= "https://github.com/MarcosMoralesAragon/dual-intership/blob/main/Angular.png" width="50" />

-> [Back : Diseñado en Java + Springboot](https://github.com/MarcosMoralesAragon/apirestjava) <img src= "https://github.com/MarcosMoralesAragon/dual-intership/blob/main/spring.png" width="50" /><img src= "https://github.com/MarcosMoralesAragon/dual-intership/blob/main/Javalogo.jpg" width="50" />

Ambos proyectos tienen sus enlaces propios en GitHub. Aunque para una descripción detallada del proyecto y su funcionamiento lea este repositorio.

El objetivo de este programa es crear un sistema de gestión de empleados manejado desde un front (angular) realizando peticiones a un back (java + springboot), realizando las funciones de un CRUD (crear, editar, borrar y listar datos). Además el proyecto cuenta con un lector de .xlsx con los que puedes cargar gran cantidad de datos de manera más eficiente.

## Formato de datos
Esta tabla vale tanto como para el front y back. En el código 
|             x             | Empleado       | Contrato        | Dirección        |
|---------------------------|----------------|-----------------|------------------|
|Id                `String` | *Prefijo W-* ✓ | *Prefijo C-* ✓  | *Prefijo A-* ✓  |
| Nombre           `String` |ㅤㅤ ✓           |ㅤㅤㅤ x          | ㅤㅤㅤx          |
| Primer apellido  `String` | ㅤㅤ✓           |ㅤㅤㅤ x          | ㅤㅤㅤx          |
| Segundo apellido `String` | ㅤㅤ✓           | ㅤㅤㅤx          | ㅤㅤㅤx          |
| DNI              `String` | ㅤㅤ✓           | ㅤㅤㅤx          | ㅤㅤㅤx          |
| Fecha nacimiento   `Date` | ㅤㅤ✓           | ㅤㅤㅤx          | ㅤㅤㅤx          |
| Nacionalidad     `String` | ㅤㅤ✓           | ㅤㅤㅤx          | ㅤㅤㅤx          |
| Estado             `Enum` | ㅤㅤ✓           | ㅤㅤㅤx          | ㅤㅤㅤx          |
| Dirección       `Address` | ㅤㅤ✓           |  ㅤㅤㅤx          | ㅤㅤㅤx          |
| Fecha inicio       `Date` | ㅤㅤx           | ㅤㅤㅤ✓          | ㅤㅤㅤx          |
| Fecha fin          `Date` | ㅤㅤx           | *Admite null* ✓ | ㅤㅤㅤx          |
| Fecha fin estimada `Date` | ㅤㅤx           | *Admite null* ✓ | ㅤㅤㅤx          |
| Salario          `Number` | ㅤㅤx           | ㅤㅤㅤ✓          | ㅤㅤㅤx          |
| Calle            `String` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Número           `Number` | ㅤㅤx           | ㅤㅤㅤx          | *Admite null* ✓ |
| Bloque           `String` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Planta           `String` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Puerta           `String` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Código postal    `Number` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Localidad        `String` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Provincia        `String` | ㅤㅤx           | ㅤㅤㅤx          | ㅤㅤㅤ✓          |
| Id empleado      `String` | ㅤㅤx           | ㅤㅤㅤ✓          | ㅤㅤㅤ✓          |



## Excel

[Plantilla](https://github.com/MarcosMoralesAragon/dual-intership/blob/main/Plantilla.xlsx)

## Mapa visual

<img src= "https://github.com/MarcosMoralesAragon/dual-intership/blob/main/Esquema.png" width="300" />
