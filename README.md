<!-- INICIO PROJECT LOGO -->
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://assetspwa.liverpool.com.mx/assets/images/logos/liverpool-logo.svg" alt="Liverpool Logo" width="400" height="125">
  </a>
<!-- FIN PROJECT LOGO -->

# OMS (Order Management System)

Este repositorio contiene la evidencia del desarrollo de pruebas de rendimiento para el sistema de OMS.
Las pruebas se realizaron utilizando Rational Performance Tester versión 10.1.3

## Tabla de Contenido 

- [Contexto](#contexto)
- [Uso](#uso)
- [Objetivo](#objetivo)
- [Interfaces](#interfaces)
- [Plan de Trabajo y Pruebas](#plan-de-trabajo-y-pruebas)
- [Documentación](#documentación)
- [Entregables](#documentación)
- [Colaboradores](#colaboradores)
- [Agradecimientos](#agradecimientos)

## Contexto

El Order Management System (OMS) de Liverpool es una herramienta que centraliza y optimiza la gestión de los pedidos de los clientes. Este sistema permite realizar un seguimiento de los pedidos desde el momento en que se realizan hasta su entrega o recogida. Algunas de las funciones clave de un OMS incluyen:

- Unificación del stock: Gestiona el inventario de manera centralizada, asegurando que la información sobre la disponibilidad de productos esté siempre actualizada.
- Seguimiento de pedidos: Permite rastrear el estado de cada pedido en tiempo real, desde cualquier ubicación del almacén.
- Procesamiento de devoluciones: Facilita la gestión de devoluciones y cambios de productos.
- Optimización de la entrega: Segura que los pedidos se entreguen de manera eficiente y puntual.

En resumen, el OMS de Liverpool mejora la experiencia de compra al garantizar que los pedidos se gestionen de manera eficiente y precisa.


## Objetivo

Optimizar el rendimiento del OMS identificando áreas de mejora mediante la evaluación de la estabilidad del sistema bajo condiciones de carga variables, asegurando así su correcto funcionamiento en diversos escenarios y que la solución tenga: 
- Escalabilidad: Capacidad para manejar picos de transacciones durante las horas de mayor demanda.
- Alto rendimiento: Respuesta rápida y eficiente, cumpliendo con los tiempos de respuesta requeridos.
- Facilidad de soporte: Mínima intervención humana y pocas quejas de los usuarios por bajo rendimiento o inestabilidad.

## Documentación Interfaces

Las pruebas de OMS consisten en probar las diferentes interfaces y servicios

- **INT-111**: [Inventory Adjustment](https://drive.google.com/drive/folders/1vNmlEHPB8Q2FOHtBBrkaS3Gfn-kXS-no?usp=drive_link): 
- **INT-1001**: [Inventory Availability](https://drive.google.com/drive/folders/11zGQder7oojGuce_EF75FJryMR0iEaxp?usp=drive_link)
- **INT-2002**: [Refund Update from BCS](https://drive.google.com/drive/folders/1x5Zur6qxaVszt7mY7DkoY8drj5Qwy0rs?usp=drive_link)
- **INT-2010**: [GetOrderDetails](https://drive.google.com/drive/folders/18T_XAcGKxvSyGidQr07X1H4L7fQiPgFp?usp=drive_link)
- **INT-2015**: [OrderCancelService](https://drive.google.com/drive/folders/1bbstco3AD3CaEk9RTCyxPRhEAeMDoOFh?usp=drive_link)
- **INT-307**: [Receive TO/PO](https://drive.google.com/drive/folders/1-GrJ-j_zY8pFUfswmXXIM8-hzpt3sVpa?usp=drive_link)
- **INT-301**: [Confirm Shipment](https://drive.google.com/drive/folders/12loZEEitU-fFQdIxXb8lE1Hv0RAhx58e?usp=drive_link)
- **INT-200**: [Order Load](https://drive.google.com/drive/folders/1bkZNn_a_SxGeuLrbdDMH44O4bDR4-uuh?usp=drive_link)
- **INT-400**: [Delivery Updates](https://drive.google.com/drive/folders/11dNfRVqcPUV70euhj2BmxBJB1r4Cnpva?usp=drive_link)
- Storage Engagement-Backroom Pick and Pack
- Storage Engagement-Click and Collect
- Click and Collect–Order Inquiry
- Click and Collect-Order Modifications


## Uso

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/PT-LP/OMS.git
    ```

2. Importar el repositorio en **`IBM Rational Tester (RPT)`**:
    
    1\. **Clic en:** <kbd>File</kbd>  
    2\. **Clic en:** <kbd>Import...</kbd>  
    3\. **Expandir opción:** <kbd>Git</kbd>  
    4\. **Seleccionar opción:** <kbd>Projects from Git (with smart import)</kbd>  
    5\. **Clic en botón:** <kbd>Next</kbd>  
    6\. **Seleccionar opción:** <kbd>Existing local repository</kbd>  
    7\. **Clic en botón:** <kbd>Next</kbd>  
    8\. **Clic en botón:** <kbd>Add</kbd>  
    9\. **Clic en botón:** <kbd>Browse</kbd>  
    10\. **Seleccionar carpeta del proyecto clonado**  
    11\. **Seleccionar el proyecto importado:** <kbd>[x]</kbd>  
    12\. **Clic en botón:** <kbd>Add</kbd>  
    13\. **Clic en botón:** <kbd>Next</kbd>  
    14\. :warning:¡IMPORTANTE!:warning:</span> **Seleccionar únicamente la casilla que dice** <kbd>Eclipse Project</kbd>  
    15\. **Clic en botón:** <kbd>Finish</kbd>

3. (Ejecución de RPT)

## Plan de Trabajo y Pruebas

El plan de trabajo se encuentra en:

- [OMS  - Plan de Trabajo y Pruebas] :warning:PENDIENTE:warning:

## Documentación

La documentación del proyecto se encuentra en: 

- [OMS - Documentación](https://docs.google.com/document/d/12-_omzk3pkPhf8Hol8DsMt9luUHu7N-F/edit)

## Entregables

Las pruebas de rendimiento incluyen los siguientes entregables:

- [x] 1 (un) Reporte de resultados  
    1\. [Reporte Junio 2024](https://drive.google.com/file/d/1dFFZgS0iV5nkreoHyT7xhO-6IdQFD_s-/view?usp=drive_link)  


 

## Colaboradores

| Area                | Nombre/Correo                  |
|---------------------|----------------------------------------------------------------|
| QA-Non Functional   | Juan Rene Limón Jimenez: jrlimonj@liverpool.com.mx             |
| QA-Non Functional   | Luis Fernando Alvarado Alcantara: lfalvaradoa@liverpool.com.mx |
| QA-Non Functional   | Oscar Eduardo Sanchez Hidalgo: oesanchezh@liverpool.com.mx     |
| QA-Non Functional   | Eduardo Avila Carranza: edavila@liverpool.com.mx               |


## Contactos

| Equipo/Area          | Nombre/Correo                  |
|--------------------|-------------------------------------------------------|
| Líder técnico      |       |
| QA                 |              |
| Funcional          | PENDIENTE |
| Infraestructura    |            |
| Middleware         |        |

**¿Quieres Colaborar?**

Para contribuir en el proyecto acercate con Juan Rene Limón Jimenez.


## Agradecimientos

* Gracias a todos los colaboradores que han participado en este proyecto.

---
