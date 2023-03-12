# CRUD - PRUEBA
* Prueba Entrada
## Tabla de Contenido
***
1. [Información General](#información-general)
2. [Tecnologías](#tecnologías)
3. [Instalación](#instalación)

## Información General
***
Aplicación CRUD realizada con Angular, C#, SqlServer utilizando los editores de código Visual Studio Code (FrontEnd), Visual Studio 2022 (BackEnd) como tambien SqlServer para la base de datos.

## Tecnologías
***
Lista de las tecnologías utilizadas en el proyecto
* [Angular CLI](https://angular.io/): Version 15.2.2 
* [Node](https://nodejs.org/en/): Version 18.13.0
* [Npm](https://www.npmjs.com/): Version 8.19.3
* [.NET](https://dotnet.microsoft.com/en-us/download/dotnet/6.0): Version 6.0

## Instalación
***
Guia de instalación
```
- Crea una carpeta con el nombre que desees.

*********************** Configuración FrontEnd ***********************

- Abrimos el cmd en la ruta de esa carpeta.
- Escribimos el siguiente comando:
$ git clone https://github.com/devcoder2000/Crud-Prueba.git

Ingresamos hasta la carpeta del FrontEnd (CrudMascotas)
- Escribimos el siguiente comando:
$ cd Crud-Prueba/CrudMascotas

(En caso de no tener instalado Angular)
Instalarlo globalmente en la version 15.2.2
$ npm install -g @angular/cli

- Instalamos el npm (node_modules)
- Escribimos el siguiente comando:
$ npm install

- Utilizamos Angular Material
$ ng add @angular/material


*********************** Configuración BackEnd ***********************

********************** Visual Studio 2022 - C# **********************
- Abrimos la solución BackendCrud.sln con Visual Studio 2022.
- Nos ubicamos en el Explorador de Soluciones.
- Ubicamos el archivo appsettings.json
- Modificamos nuestro servidor de base de datos:

$ "Server=[TUSERVIDOR]; DataBase=Veterinaria; Trusted_Connection=True; TrustServerCertificate=True"

- Instalamos las dependencias en el Administrador de Paquetes NuGet:

 * AutoMapper.Extensions.Microsoft.DependencyInjection (12.0.0)
 * Microsoft.EntityFrameworkCore (7.0.3)
 * Microsoft.EntityFrameworkCore.SqlServer (7.0.3)
 * Microsoft.EntityFrameworkCore.Tools (7.0.3)
 * Swashbuckle.AspNetCore (6.2.3)

 En caso de ya estar instalados omitir este paso.

******************** Base de Datos - SqlServer *********************
- Ejecutamos el script bd.sql que se encuentra ubicado en la
carpeta ScriptDB

********************** Levantamos el Proyecto **********************
- Abrimos la solución BackendCrud.sln (BackEnd) con Visual Studio 2022.
- Ejecutamos el proyecto

- Dentro de la carpeta CrudMascotas (FrontEnd)
- Abrimos la terminal y ejecutamos el comando:
 
$ ng serve -o

```