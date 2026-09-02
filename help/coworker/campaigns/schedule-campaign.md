---
description: la descripción se incluye aquí.
title: Programar una campaña
product_v2: id: fdae8433-07cd-42e7-acce-738afe63f6bb
feature_v2: id: fdae8433-07cd-42e7-acce-738afe63f6bb
source-git-commit: a3df1a0f8e1014d95483f977aaa64435c18e6578
workflow-type: tm+mt
source-wordcount: 676
ht-degree: 1%

---

# Programar una campaña {#schedule-campaign}

Al lanzar una campaña, los usuarios ahora pueden elegir exactamente cuándo sale: inmediatamente, en una fecha y hora futuras específicas o en una programación repetida (recurrente). Los usuarios también pueden volver más tarde y cambiar la programación de una campaña que ya se ha iniciado o programado.

> **Lo que cambió**: Anteriormente, las campañas solo se podían iniciar inmediatamente. Esta versión añade una programación futura única, programaciones recurrentes y la capacidad de editar una programación después del lanzamiento.

## Requisitos previos

- La campaña debe estar lista para iniciarse (se ha completado toda la configuración necesaria).
- No se requieren requisitos previos más allá de tener una campaña en un estado de inicio.

## Qué hace esta función

Cuando un usuario inicia una campaña, elige uno de los tres modos de programación y luego confirma. La programación elegida determina cuándo comienza a enviarse la campaña y, en el caso de las campañas recurrentes, con qué frecuencia se repite y cuándo (o si) finaliza. Una vez que una campaña está programada o activa, su programación se puede editar desde la configuración de la campaña.

### Comportamientos clave

- Hay tres modos de horario disponibles al iniciar: **Ahora**, **Programar una vez** y **Recurrente**.
- Una campaña programada para el futuro muestra el estado &quot;Programada&quot; hasta que llega su hora de inicio y luego cambia automáticamente a &quot;En vivo&quot;.
- Una campaña recurrente que ha comenzado muestra &quot;En vivo&quot; junto con un resumen de su periodicidad (por ejemplo, &quot;Semanalmente el martes, jueves a las 9:00 AM&quot;).
- Las campañas recurrentes se pueden configurar para que se ejecuten de forma indefinida (&quot;Nunca&quot; finalizar) o hasta una fecha de finalización específica. Las campañas únicas e inmediatas no tienen una opción de fecha de finalización, ya que se ejecutan una vez.
- Los usuarios pueden editar la programación de una campaña que ya se ha iniciado o programado, utilizando las mismas opciones de programación, desde la configuración de la campaña.

## Cómo se usa

**Para programar una campaña al inicio:**

1. En la campaña, haga clic en **Listo para iniciar**.
2. En el cuadro de diálogo de lanzamiento, elija una opción de programación:
   - **Ahora**: la campaña comienza a enviarse inmediatamente después del lanzamiento.
   - **Programar una vez** — elija una **fecha de inicio** futura (fecha y hora juntas).
   - **Recurrente** — elige una **Frecuencia** (Diaria, Semanal o Mensual) y una hora de inicio, luego establece el patrón de periodicidad (consulta los campos a continuación).
3. Si se selecciona Recurrente, elija si la campaña finaliza **Nunca** o **En una fecha**, y elija una fecha de finalización si corresponde.
4. Confirme para iniciar la campaña con la programación seleccionada.

**Para editar una programación existente:**

1. Abra la campaña y vaya a su configuración.
2. Busque la sección de programación y seleccione el resumen de programación actual.
3. Actualice la programación utilizando las mismas opciones descritas anteriormente.
4. Guarde el cambio.

### Campos/parámetros de entrada

| Campo | Descripción | ¿Requerido? |
| --- | --- | --- |
| Modo de horario | Opción de ahora, programar una vez o recurrente | Sí |
| Fecha de inicio | Fecha y hora de inicio de la campaña (modo Schedule once) | Sí, para Programar una vez |
| Frecuencia | Diario, Semanal o Mensual (modo recurrente) | Sí, para recurrente |
| Hora de inicio | Hora del día en que la campaña recurrente envía | Sí, para recurrente |
| Días de la semana | Qué día(s) de la campaña se repite | Sí, para frecuencia semanal |
| Día del mes | En qué día del mes se repite la campaña | Sí, para la frecuencia mensual |
| Finalizar campaña | Nunca, o en una fecha de finalización específica | Sí, para recurrente |

## Llamadas de IU

> **Nota del redactor técnico**: Se necesitan capturas de pantalla para lo siguiente:

- [ ] El cuadro de diálogo de inicio que muestra las opciones Ahora / Programar una vez / Recurrente
- [ ] El selector de fecha y hora de Programar una vez
- [ ] Las opciones recurrentes: selector de frecuencia, alternadores de día semanales, cuadrícula mensual de día del mes
- [ ] &quot;Finalizar campaña&quot; Nunca / En una opción de fecha
- [ ]: el distintivo de estado &quot;Programado&quot; en una campaña que espera su hora de inicio.
- [ ]: el distintivo de estado &quot;Activo&quot; con un resumen de periodicidad (por ejemplo, &quot;Semanal el martes, jueves a las 9:00 a. m.&quot;)
- [ ]: sección de programación en la configuración de campaña, que muestra el punto de entrada de edición

## Qué no hace esta función

- No admite intervalos de repetición personalizados, como &quot;cada 2 semanas&quot; o &quot;cada 3 días&quot;; solo están disponibles las frecuencias diarias, semanales o mensuales estándar.
- No admite la periodicidad mensual relativa, como &quot;el segundo lunes del mes&quot;; solo está disponible la selección específica de día del mes para mensual.
- No ofrece una fecha de finalización para las campañas **Ahora** o **Programar una vez**: una fecha de finalización solo está disponible cuando se selecciona Recurrente, ya que las campañas de una sola vez se ejecutan una vez por definición.
