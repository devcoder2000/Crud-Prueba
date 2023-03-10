# CRUD - PRUEBA
* Prueba Entrada
## Tabla de Contenido
***
1. [Información General](#información-general)
2. [Tecnologías](#tecnologías)
3. [Instalación](#instalación)

## Información General
***
Aplicacion CRUD realizada con las Angular, C#, SqlServer utilizando los editores de código Visual Studio Code (FrontEnd) y Visual Studio 2022 (BackEnd)

## Tecnologías
***
A list of technologies used within the project:
* [Angular CLI](https://angular.io/): Version 15.2.2 
* [Node](https://nodejs.org/en/): Version 18.13.0
* [Npm](https://www.npmjs.com/): Version 8.19.3
* [.NET](https://dotnet.microsoft.com/en-us/download/dotnet/6.0): Version 6.0

## Instalación
***
Guia de instalación
```
- Crea una carpeta con el nombre que desees.

*********************** Configuracion FrontEnd ***********************

- Abrimos el cmd en la ruta de esa carpeta.
- Escribimos el siguiente comando:
$ git clone https://github.com/devcoder2000/Crud-Prueba.git

Ingresamos hasta la carpeta del FrontEnd (CrudMascotas)
- Escribimos el siguiente comando:
$ cd Crud-Prueba/CrudMascotas

- Instalamos el npm (node_modules)
- Escribimos el siguiente comando:
$ npm install


*********************** Configuracion BackEnd ***********************

********************** Visual Studio 2022 - C# **********************
- Abrimos la solucion BackendCrud.sln con Visual Studio 2022.
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

********************** Base de Datos - C# **********************
- Ejecutamos el script bd.sql que se encuentra ubicado en la
carpeta ScriptDB

```