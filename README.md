# Wiki de Microservicios y Arquitectura Moderna

Bienvenido a la wiki del proyecto **Microservicios y Arquitectura Moderna**. Aquí encontrarás toda la documentación y pruebas de concepto desarrolladas para entender, implementar y comparar arquitecturas basadas en microservicios.

---

## Índice

- [Unidad 1: Concepto de Microservicios y Principios Básicos](#unidad-1-concepto-de-microservicios-y-principios-básicos)
  - [Parte Conceptual](#parte-conceptual)
  - [Prueba de Concepto](#prueba-de-concepto)
- [Unidad 2: Ventajas y Desventajas de los Microservicios](#unidad-2-ventajas-y-desventajas-de-los-microservicios)
  - [Parte Conceptual](#parte-conceptual-1)
  - [Prueba de Concepto](#prueba-de-concepto-1)

---

## Unidad 1: Concepto de Microservicios y Principios Básicos

### Parte Conceptual

Esta sección presenta una introducción en una sola hoja a los microservicios y los principios fundamentales que los rigen:

- **Definición de Microservicios**:  
  Una arquitectura que divide una aplicación en servicios pequeños, autónomos y escalables.
  
- **Principios Básicos**:
  - **Independencia**: Cada servicio funciona de manera autónoma.
  - **Cohesión**: Los servicios se enfocan en funcionalidades específicas.
  - **Acoplamiento Reducido**: Se minimiza la dependencia entre servicios.
  - **Despliegue Independiente**: Posibilidad de actualizar y escalar servicios sin impactar el sistema completo.

> ![Diagrama conceptual de microservicios](ruta/a/diagrama-microservicios.jpg)  
> *(Imagen ilustrativa de la arquitectura de microservicios)*

### Prueba de Concepto

Se ha desarrollado una pequeña aplicación de **gestión de usuarios** que implementa un microservicio básico. Este servicio realiza operaciones CRUD (Crear, Leer, Actualizar, Eliminar) de forma independiente.

- **Características del Servicio**:
  - Gestión de usuarios de forma autónoma.
  - Despliegue independiente, permitiendo actualizaciones sin afectar a otros componentes.

---

## Unidad 2: Ventajas y Desventajas de los Microservicios

### Parte Conceptual

En esta unidad se abordan en una hoja los pros y contras de implementar una arquitectura de microservicios:

- **Ventajas**:
  - **Escalabilidad**: Capacidad para escalar cada servicio de forma individual.
  - **Flexibilidad**: Mayor facilidad para actualizar y evolucionar componentes.
  - **Despliegue Continuo**: Implementaciones rápidas y sin interrupciones.
  - **Resiliencia**: Aislamiento de fallos, mejorando la tolerancia a errores.

- **Desventajas**:
  - **Complejidad**: Requiere gestionar múltiples servicios en lugar de una sola aplicación.
  - **Gestión de Transacciones**: Dificultades para mantener la consistencia en operaciones distribuidas.
  - **Latencia**: Comunicación entre servicios puede incrementar tiempos de respuesta.
  - **Costos de Desarrollo**: Mayor inversión en infraestructura y mantenimiento.

> ![Comparativa ventajas y desventajas](ruta/a/grafico-ventajas-desventajas.jpg)  
> *(Gráfico comparativo de microservicios vs. sistemas monolíticos)*

### Prueba de Concepto

Se realizó una demostración comparativa entre un sistema **monolítico** y otro basado en **microservicios**, utilizando un sistema de gestión de órdenes de compra.

- **Comparación de Sistemas**:
  - **Sistema Monolítico**:  
    Todas las funcionalidades (usuarios, productos, órdenes) se integran en una única aplicación.
    
  - **Sistema Basado en Microservicios**:  
    Cada funcionalidad se implementa como un servicio independiente, permitiendo escalarlos por separado.

- **Mediciones y Observaciones**:
  - Se destacó la capacidad de escalar horizontalmente el microservicio encargado de la gestión de órdenes, mostrando mejoras en rendimiento bajo alta carga.

---

Esta wiki ofrece una visión integral, combinando teoría y práctica, para que puedas comprender y aplicar la arquitectura de microservicios en el desarrollo de aplicaciones modernas.

¡Explora, aprende y experimenta con las diferentes propuestas de este proyecto!
