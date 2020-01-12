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
