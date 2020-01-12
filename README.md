# PryBaseSpringHibernate
Configuración de un proyecto base que utiliza Springboot, Hibernate y SpringSecurity.

## Objetivo
El objetivo del presente respositorio es mostrar la configuración base de un proyecto utilizando SpringBoot y para la capa de persistencia de datos Hibernate.

se utiliza el patrón MVC para configurar la estructura de paquetes.

## Estructura de paquetes
| Paquete      | Descripción |
| --------- | -----|
| com.xxx.app.configuration  | Clases de configuración de la aplicación |
| com.xxx.app.negocio.repository     | Interfaces para definir la lógica de negocio |
| com.xxx.app.negocio.repository.imp      | Implementación de la lógica de negocio |
| com.xxx.app.negocio.services      | Clases para exponer los servicios implementados en el repository |
| com.xxx.app.negocio.vista      |  Implementación de los Controladores. |

## Ambiente de Desarrollo
- Spring Tool Suite 4
- Spring boot
- Hibernate
- Lombok
- Swagger
- Thymeleaf

## Configurar Lombok en Eclipse
1. Descargar Lombok.jar desde el sitio web https://projectlombok.org/download
2. Ubicar el archivo lombok.jar donde se encuentra instalado el eclipse o Spring Tool Suite (mismo lugar donde se encuentra el archivo SpringToolSuite4.ini)
3. Modificar el archivo SpringToolSuite4.ini y agregar la línea (sin espacios):
`-javaagent:Ruta_instalacion_STSoEclipse\SpringToolSuite-4.5.0\lombok.jar`
