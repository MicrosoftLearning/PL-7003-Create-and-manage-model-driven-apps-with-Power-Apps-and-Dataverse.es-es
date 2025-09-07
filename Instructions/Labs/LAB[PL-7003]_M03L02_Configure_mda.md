---
lab:
  title: "Laboratorio\_5: Configuración de una aplicación controlada por modelos"
  module: 'Module 3: Configure forms, charts, and dashboards in model-driven apps'
---

# Laboratorio de práctica 5: configuración de una aplicación controlada por modelos

## Escenario

En este laboratorio, configurará una aplicación controlada por modelos.

## Aprendizaje

- Configuración de la navegación para una aplicación controlada por modelos
- Cómo restringir las vistas en una aplicación controlada por modelos

## Pasos de alto nivel del laboratorio

- Agregar grupos a la navegación
- Mover tablas en la navegación
- Restringir vistas en la aplicación
  
## Requisitos previos

- Debe de haber completado la práctica **Laboratorio 2: Modelo de datos**, **Lab 3: Crear una aplicación basada en modelos**, y **Lab 4: Configuración de formularios y vistas**

## Pasos detallados

## Ejercicio 1: Configuración de la aplicación controlada por modelos

En este ejercicio, configurará la navegación y las tablas de una aplicación controlada por modelos.

### Tarea 1.1: Configurar grupos

1. Vaya al portal de Power Apps Maker <https://make.powerapps.com>.

1. Asegúrese de que está en el entorno **Dev One**.

1. Seleccione **Soluciones**.

1. Abra la solución **Descripciones de propiedades**.

1. En el panel **Objetos** de la izquierda, seleccione **Aplicaciones**.

1. Seleccione la aplicación **Administración de propiedades**, seleccione el menú **Comandos** (...), y seleccione **Editar** > **Editar en nueva pestaña**.

1. Seleccione **Nuevo Grupo** en el panel **Navegación**.

    ![Captura de pantalla del grupo de aplicaciones controladas por modelos.](../media/mda-group.png)

1. En el panel de propiedades, escriba `Clients` en **Título**.

1. Selecciona **Navegación**, selecciona el menú **Comandos** (...) y **Nuevo grupo**.

1. En el panel de propiedades, escriba `Properties` en **Título**.

1. En el **Panel de navegación**, seleccione **Mostrar vista**, seleccione el menú **Comandos** (...) y seleccione **Desplazar hacia abajo**.

1. En el **Panel de navegación**, seleccione **Vista de propiedades inmobiliarias**, seleccione el menú **Comandos** (...) y seleccione **Desplazar hacia abajo**.

1. En el **Panel de navegación**, seleccione **Abrir vista Casas**, seleccione el menú **Comandos** (...) y seleccione **Desplazarse hacia abajo** tres veces.

    ![Captura de pantalla del diseñador de aplicaciones basado en modelos con navegación.](../media/mda-navigation.png)

### Tarea 1.2: Restringir vistas

1. En el panel **Navegación**, seleccione **Mostrar vista**.

1. En el panel **Mostrar**, seleccione la pestaña **Vistas**.

1. Seleccione la vista **Mostrar vistas inactivas**, en el panel derecho, y seleccione el menú **Comandos** (...) y seleccione **Eliminar**.

    ![Captura de pantalla de la eliminación de una vista en el diseñador de aplicaciones controladas por modelos.](../media/mda-remove-view.png)

1. Seleccione **Guardar y publicar**.

1. **Cierre** el diseñador de aplicaciones y seleccione **Listo**.
