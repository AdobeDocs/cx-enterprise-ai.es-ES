---
description: la descripción se incluye aquí.
title: Detener una campaña
source-git-commit: 500932a1e705af1682a71ce460b6fa62e4ffd4ac
workflow-type: tm+mt
source-wordcount: '410'
ht-degree: 0%

---

# Detener una campaña {#stop-campaign}

Los usuarios ahora pueden detener una campaña que se envía activamente (una campaña &quot;en directo&quot;) directamente desde la página de detalles de la campaña. La detención de una campaña es permanente: los destinatarios dejan de avanzar por la campaña inmediatamente y la campaña no se puede reanudar ni reiniciar posteriormente.

## Requisitos previos

- La campaña debe estar en estado activo (envío activo). La acción Detener no está disponible para campañas en borrador, programadas o ya detenidas.
- [NECESITA ENTRADA — para confirmarlo con el ingeniero: ¿la detención de una campaña requiere un rol o permiso específico, o puede hacerlo cualquier usuario con acceso a la campaña?]

## Qué hace esta función

Cada vez que una campaña está activa, aparece una acción &quot;Detener campaña&quot; en el encabezado de detalles de la campaña. Al seleccionarla, se abre un cuadro de diálogo de confirmación en el que se advierte de que la acción es permanente. La confirmación llama al back-end para detener la campaña; si se realiza correctamente, el estado de la campaña cambia a Detenido y aparece un mensaje de confirmación.

### Comportamientos clave

- La acción Detener campaña solo aparece mientras una campaña está activa (enviando activamente).
- La detención es permanente: los destinatarios dejan de avanzar por la campaña y no se puede reanudar.
- Un cuadro de diálogo de confirmación requiere que el usuario confirme explícitamente antes de que se detenga la campaña.
- Después de detenerse, la insignia de estado de la campaña se actualiza a &quot;Detenido&quot;.
- Si la solicitud de detención falla, se muestra un mensaje de error y la campaña permanece activa.

## Cómo se usa

1. Abra una campaña que esté activa (enviando activamente).
2. En el encabezado de detalles de la campaña, haga clic en **Detener campaña**.
3. En el cuadro de diálogo de confirmación, revise la advertencia: &quot;Detener la campaña es permanente. Todos los destinatarios dejarán de progresar y la campaña no se puede reanudar&quot;.
4. Haga clic en **Detener** para confirmar.
5. Una &quot;Campaña detenida&quot;. Aparece un mensaje de confirmación y el estado de la campaña se actualiza a Detenido.

### Campos/parámetros de entrada

No aplicable: esta función es una única acción de confirmación sin campos de entrada.

## Llamadas de IU

> **Nota del redactor técnico**: Se necesitan capturas de pantalla para lo siguiente:

- [ ] El botón &quot;Detener campaña&quot; en el encabezado de detalles de campaña, mostrado en una campaña en vivo
- [ ] El cuadro de diálogo de confirmación con la advertencia de permanencia
- [ ]: el distintivo de estado &quot;Detenido&quot; después de una detención correcta
- [ ] El mensaje de error que se muestra si falla la detención

## Qué no hace esta función

- No pausa una campaña temporalmente. No hay forma de reanudar una campaña detenida; la detención es una acción unidireccional.
- No admite el reinicio o relanzamiento de una campaña detenida desde el mismo registro de campaña.
- [NECESITA ENTRADA — para confirmarlo con el ingeniero: ¿se planea una capacidad de &quot;pausar y reanudar&quot; por separado, o es Detener el envío de la única acción de control de estado en esta versión?]
