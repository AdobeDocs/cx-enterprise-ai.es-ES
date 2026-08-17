---
description: la descripción se incluye aquí.
title: Lanzamiento de una campaña
feature_v2: id: fdae8433-07cd-42e7-acce-738afe63f6bb
source-git-commit: 1c4f9585c04eae8693e38541084cead08412d192
workflow-type: tm+mt
source-wordcount: 757
ht-degree: 0%

---

# Lanzamiento de una campaña {#launch-campaign}

El inicio de una campaña es la acción que la mueve del borrador al envío activo. Antes de que se abra el cuadro de diálogo de lanzamiento, Halo comprueba que la campaña está lista y bloquea el lanzamiento hasta que se complete la configuración requerida. El cuadro de diálogo de lanzamiento muestra una previsualización del correo electrónico y la audiencia, permite al usuario revisar o cambiar la programación de envío en línea e informa si el lanzamiento se ha realizado correctamente. Esta sección cubre la experiencia de inicio de extremo a extremo; para ver las opciones de programación ofrecidas durante el inicio, consulte [Programar una campaña](/help/coworker/campaigns/schedule-campaign.md).

## Requisitos previos

- La campaña debe estar en estado de Borrador. <!-- The Launch action isn't available once a campaign is already live. -->
<!-- - The campaign must pass a readiness check: sending settings configured, at least one test email sent, and a real (non-sample) audience uploaded. -->
- [NECESITA INTRODUCCIÓN, para confirmarlo con el ingeniero: es posible que algunos usuarios vean una experiencia &quot;próximamente&quot; en lugar de un botón de Launch real, que solo ofrece descargar la campaña o enviar un correo electrónico de prueba en lugar de iniciar en la aplicación. Confirme qué determina qué experiencia obtiene un usuario o una campaña determinados.]

## Qué hace esta función

Cuando un usuario inicia una campaña, Halo primero valida que la campaña está lista. Si falta algo necesario, un cuadro de diálogo indica lo que debe corregirse antes de continuar con el lanzamiento. Una vez superada la validación, el cuadro de diálogo de lanzamiento muestra una previsualización del correo electrónico y la audiencia/flujo de trabajo, permite al usuario revisar o editar la programación de envío sin abandonar el flujo y, para los envíos grandes, muestra un aviso de volumen de envío estimado. Al confirmar los déclencheur en el lanzamiento, y Halo informa de uno de los tres resultados: iniciado, ya iniciado o fallido.

### Comportamientos clave

- Launch solo está disponible para campañas en estado Borrador; una campaña que ya está activa no se puede iniciar de nuevo.
- Se ejecuta automáticamente una comprobación de disponibilidad antes de que se abra el cuadro de diálogo de inicio. Los problemas sin resolver bloquean el inicio y se enumeran con una forma de resolverlos cada uno.
- El cuadro de diálogo de lanzamiento muestra una vista previa del correo electrónico (asunto, encabezado previo, remitente) y una vista previa de la audiencia/flujo de trabajo.
- La programación de envío se puede revisar o cambiar desde el cuadro de diálogo de lanzamiento.
- Para envíos grandes, el cuadro de diálogo muestra un impacto estimado del volumen de envío. [NECESITA ENTRADA — la redacción exacta de este aviso no estaba disponible en el código]
- Si se realiza correctamente, el estado de la campaña se actualiza a &quot;Programada&quot; o &quot;En directo&quot; (según la programación seleccionada) y un mensaje de confirmación indica que las perspectivas de la campaña estarán disponibles en un plazo de 2 horas.
- Si la campaña ya se ha iniciado (por ejemplo, por un clic duplicado), Halo muestra un mensaje &quot;ya iniciado&quot; en lugar de un error.
- Si el inicio falla, aparece un mensaje de error y la campaña permanece en Borrador; el usuario puede intentarlo de nuevo.
- Una vez que se detiene una campaña <!--(see [Stop a live campaign](./stop-live-campaign.md))-->, no se puede reiniciar desde el mismo registro de campaña; la detención es un estado permanente independiente.

## Cómo acceder a

**Para iniciar una campaña:**

1. En la campaña, haga clic en **Iniciar** (se muestra como &quot;Listo para iniciar&quot; mientras está en borrador).
2. Si falta algo, un diálogo titulado &quot;Algunas cosas todavía necesitan atención&quot; enumera lo que hay que completar:
   - **Configurar la configuración del correo electrónico** — los parámetros de envío (remitente/dominio) aún no se han configurado.
   - **Correos electrónicos no probados**: envíe al menos un correo electrónico de prueba para probar el correo electrónico antes del inicio.
   - **Se requiere audiencia real para el lanzamiento**; la campaña todavía está usando una audiencia de muestra; cargue un CSV de audiencia real.
     Resuelva cada elemento e intente Launch de nuevo.
3. Una vez que la campaña pasa la comprobación de preparación, se abre el cuadro de diálogo de inicio con una previsualización del correo electrónico y la audiencia.
4. Revise la programación que se muestra en el cuadro de diálogo. Para cambiarlo, usa las opciones de horario descritas en [Programar cuando se inicie una campaña](/help/coworker/campaigns/schedule-campaign.md) y, a continuación, guarda.
5. Confirme para iniciar. Si se realiza correctamente, aparece un mensaje de confirmación y se actualiza el estado de la campaña (a &quot;Programada&quot; o &quot;En directo&quot;).

<!-- 
## Input fields / parameters

Not applicable beyond the schedule fields already documented in [Schedule when a campaign launches](/help/coworker/campaigns/schedule-campaign.md) — launching itself doesn't require any additional input. 
-->

## Llamadas de IU

> **Nota del redactor técnico**: Se necesitan capturas de pantalla para lo siguiente:

- [ ]: el punto/botón de entrada de Launch en el encabezado de detalles de la campaña.
- [ ] elementos incompletos en el cuadro de diálogo de preparación/validación
- [ ]: cuadro de diálogo de lanzamiento que muestra la sección correo electrónico + vista previa de audiencia y programación
- [ ]: el aviso de impacto del volumen de envío estimado (para audiencias grandes)
- [ ] El mensaje de confirmación de éxito después del lanzamiento
- [ ]: el mensaje &quot;ya iniciado&quot;
- [ ]: mensaje de error genérico de inicio-error

## Qué no hace esta función

- No permite que se inicie una campaña con una audiencia de muestra (no real), correos electrónicos no probados o configuraciones de envío no configuradas; primero deben resolverse los tres.
- El inicio no acepta una programación como parte de la misma acción; la programación se guarda por separado (desde el mismo cuadro de diálogo) antes o como parte de la confirmación del inicio.
- No admite el relanzamiento de una campaña que se ha detenido; la detención es permanente <!--(see [Stop a live campaign](./stop-live-campaign.md))-->.
- [NECESITA ENTRADA, para confirmarlo con ingeniero/PM: para algunos usuarios, Launch puede reemplazarse por una experiencia &quot;próximamente&quot; que ofrezca solo una descarga de campaña (PDF/DOCX) o un envío de correo electrónico de prueba, sin el inicio del autoservicio en la aplicación. Confirme la audiencia a la que se aplica antes de publicar, ya que cambia los pasos de procedimiento para esa cohorte.]
