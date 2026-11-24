# Prácticas de C# y ASP.NET

Repositorio de ejercicios y proyectos de práctica orientados a los fundamentos de C# y al desarrollo web con ASP.NET Web Forms. Los ejemplos están organizados como proyectos independientes y muestran distintas etapas de aprendizaje: desde controles de servidor y eventos hasta persistencia con Entity Framework.

> Son ejemplos educativos basados en tecnologías clásicas de .NET Framework; no constituyen una aplicación única ni una plantilla lista para producción.

## Stack y herramientas

- **C#** sobre **.NET Framework 4.0 y 4.5**, según el proyecto.
- **ASP.NET Web Forms**, con páginas `.aspx`, controles de servidor y code-behind.
- **HTML y JavaScript** para la interfaz y algunos ejemplos de validación.
- **Entity Framework 6** y un modelo **EDMX** en el ejercicio de persistencia.
- **SQL Server** para el ejemplo de base de datos.
- Soluciones y proyectos clásicos de **Visual Studio** (`.sln` / `.csproj`); las aplicaciones web pueden ejecutarse con IIS Express desde Visual Studio.

## Proyectos y prácticas

| Proyecto | Qué se practica |
| --- | --- |
| [Calculadora v1](Calculadora/Calculadora%20v1/Calculadora%20v1.sln) | Suma y manejo de eventos de botones. |
| [Calculadora v2](Calculadora/Calculadora%20v2/Calculadora%20v2.sln) | Operaciones aritméticas seleccionables y limpieza de campos. |
| [Calculadora v3](Calculadora/Calculadora%20v3/Calculadora%20v3.sln) | Separación de operaciones en una biblioteca de clases. |
| [Calculadora v4](Calculadora/Calculadora%20v4/Calculadora%20v4.sln) | Evolución de la calculadora y reutilización de una biblioteca de operaciones. |
| [Calculadora v5](Calculadora/Calculadora%20v5/Calculadora%20v5.sln) | Selección de operaciones alimentada desde una clase de operaciones. |
| [Fútbol v1](F%C3%BAtbol/F%C3%BAtbol%20v1/F%C3%BAtbol.sln) | Clases de personas, jugadores, equipos, árbitros y partidos. |
| [Fútbol v2](F%C3%BAtbol/F%C3%BAtbol%20v2/F%C3%BAtbol.sln) | Evolución del modelo de dominio: interfaces y partidos de fútbol y vóley. |
| [Custom Validator](Custom%20Validator/aspnet-customvalidator.sln) | Validación de formularios con `RequiredFieldValidator` y `CustomValidator`, en servidor y cliente. |
| [Formulario de registración](FormularioDeRegistraci%C3%B3n/FormularioDeRegistraci%C3%B3n.sln) | Validación de campos, edad, formato de correo y coincidencia de contraseñas. |
| [Login](Log%20in/Log%20in.sln) | Maquetado de un formulario de inicio de sesión y controles de servidor. |
| [Formulario con Master Page y User Control](Formulario%20usando%20uc%20y%20mp/Formulario%20usando%20uc%20y%20mp.sln) | Diseño compartido con página maestra y reutilización de un control de usuario. |
| [Pasaje de datos](PasajeDeDatos/PasajeDeDatos.sln) | Transferencia de datos entre páginas mediante query string, `Session` y `Application`. |
| [EF-EMPRESA](EF-EMPRESA/EF-EMPRESA.sln) | Alta y listado de empleados con Entity Framework, EDMX y SQL Server. |

Las versiones de la calculadora y de Fútbol son ejercicios separados, no componentes de una misma solución. El directorio `Custom Validator/Backup` contiene una copia adicional del ejemplo.

## Cómo abrir y ejecutar

1. En Windows, instala Visual Studio con la carga de trabajo de ASP.NET y los paquetes de destino de .NET Framework que requiera el proyecto.
2. Abre el archivo `.sln` de la práctica que quieras ejecutar. No hay una solución general en la raíz del repositorio.
3. Selecciona el proyecto web como proyecto de inicio y ejecútalo con IIS Express desde Visual Studio.
4. Para **EF-EMPRESA**, configura una instancia de SQL Server con la base de datos esperada por el modelo y ajusta la cadena `Contexto` en `EF-EMPRESA/EF-EMPRESA/Web.config` a tu entorno. El ejemplo utiliza Entity Framework 6.

## Alcance

El repositorio sirve como material de estudio de C#, programación orientada a objetos, eventos de Web Forms, validación, composición de interfaces, manejo de estado y acceso a datos. Web Forms y .NET Framework son tecnologías heredadas; considera esto al elegir herramientas y al reutilizar código fuera del contexto de aprendizaje.
