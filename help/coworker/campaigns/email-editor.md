---
description: descripción.
title: Comprender el editor de correo electrónico
source-git-commit: e5992ce91452c98e043e8367d7cc551d6914647b
workflow-type: tm+mt
source-wordcount: '707'
ht-degree: 0%

---

# Comprender el editor de correo electrónico {#email-editor}

El editor de correo electrónico permite refinar un correo electrónico generado por IA directamente en el tablero de campaña. Edite la línea de asunto y el preencabezado, dé formato al texto y a las imágenes en línea o cambie a una plantilla diferente. <!-- It's an inline editor over the email's actual HTML, not a drag-and-drop block builder. -->

>[!PREREQUISITES]
>
>Cree una campaña con un correo electrónico generado.

## Qué hace esta función

Al hacer clic en una tarjeta de correo electrónico en el tablero de campañas, se abre el editor de correo electrónico como un panel lateral. Desde allí, el usuario puede editar el asunto y el preencabezado (con alternativas sugeridas por IA), hacer clic en el cuerpo del correo electrónico para seleccionar y dar formato al texto o las imágenes, cambiar entre variantes generadas por IA, intercambiar la plantilla de HTML, comprobar la compatibilidad entre el cliente y el correo electrónico y enviar un correo electrónico de prueba a su propia bandeja de entrada. Los cambios se guardan automáticamente y las versiones anteriores se pueden revisar y restaurar.

### Comportamientos clave

- Al hacer clic en cualquier texto o imagen del cuerpo del correo electrónico, se selecciona y aparece una barra de herramientas de formato flotante.
- Opciones de formato de texto: negrita, cursiva, subrayado, fuente y tamaño de fuente.
- Opciones de imagen: Reemplazar, Eliminar, Vincular, Editar con Express, Generar imagen (AI), Cargar desde el equipo.
- Las cargas de imágenes tienen un límite de 10 MB; las imágenes de más de 3 MB se comprimen automáticamente, con una nota de calidad que recomienda imágenes de menos de 3 MB.
- Los campos Asunto y preencabezado tienen una opción &quot;Sugerencias inteligentes&quot; para alternativas generadas por IA.
- Cambios guardados automáticamente (al desenfocar y poco después de acciones de formato): un indicador de estado muestra Cambios no guardados, Guardar..., Guardado, Guardado automáticamente o No se puede guardar (con una opción Reintentar ).
- Deshacer/rehacer está disponible para la sesión de edición actual.
- Las versiones guardadas anteriores se pueden previsualizar y restaurar desde un panel del historial de versiones.
- Si existen varias variantes generadas por IA, el usuario puede alternar entre ellas desde un panel de miniaturas.
- La plantilla de HTML del correo electrónico se puede intercambiar con &quot;Cambiar plantilla de HTML&quot;.
- &quot;Enviar correo electrónico de prueba&quot; envía una vista previa real a la bandeja de entrada del usuario con datos de ejemplo; no afecta a la creación de informes de campaña.
- Hay disponible una comprobación de compatibilidad de cliente de correo electrónico en algunos entornos, que abarca Gmail, Outlook, Apple Mail, Yahoo Mail, Samsung Email y Thunderbird. [NECESITA ENTRADA: se encuentra detrás de un indicador de característica; confirme si está habilitado para la audiencia de destino antes de documentarlo como disponible de forma general]

## Cómo acceder a

1. Abra la campaña deseada y haga clic en Open editor en la tarjeta de correo electrónico.

CAPTURA DE PANTALLA

1. Edite directamente los campos **Subject** y **Preheader**, o haga clic en **Sugerencias inteligentes** junto a para buscar alternativas generadas por IA.
1. Haga clic en el cuerpo del correo electrónico para seleccionar un bloque de texto o una imagen y, a continuación, utilice la barra de herramientas flotante que aparece para dar formato al texto o administrar la imagen.
1. Use **Cambiar plantilla de HTML** para reemplazar el cuerpo del correo electrónico por una plantilla diferente.
1. Use **Enviar correo electrónico de prueba**, ingrese una dirección de destinatario y haga clic en **Enviar** para enviar por correo electrónico una vista previa activa a esa dirección.
1. Utilice el icono del historial de versiones para obtener una vista previa y restaurar una versión guardada anteriormente.
1. Los cambios se guardan automáticamente: no es necesario guardarlos manualmente.

### Campos/parámetros de entrada

| Campo | Descripción | ¿Requerido? |
| --- | --- | --- |
| Asunto | La línea de asunto del correo electrónico | No (puede dejarse en blanco; no se aplica actualmente) |
| Preencabezado | Texto de vista previa que se muestra junto al asunto en una bandeja de entrada | No |
| Dirección de correo electrónico del destinatario | Dónde enviar un correo electrónico de prueba | Sí, para enviar correo electrónico de prueba |

## Llamadas de IU

> **Nota del redactor técnico**: Se necesitan capturas de pantalla para lo siguiente:

- [ ]: panel lateral del editor de correo electrónico (campos de asunto/encabezado previo más cuerpo del correo electrónico)
- [ ]: barra de herramientas flotante para la selección de texto
- [ ]: barra de herramientas flotante para la selección de imágenes
- [ ]: el panel en miniatura de la variante AI
- [ ]: panel del historial de versiones
- [ ]: cuadro de diálogo &quot;Cambiar plantilla de HTML&quot;
- [ ]: cuadro de diálogo Enviar correo electrónico de prueba
- [ ]: comprobador de compatibilidad de clientes de correo electrónico (si está habilitado en el entorno de destino).

## Qué no hace esta función

- No es un generador de bloques de arrastrar y soltar: no hay ninguna biblioteca de bloques y los bloques de contenido no se pueden añadir, eliminar ni reordenar; la edición se realiza directamente en el HTML de correo electrónico existente.
- Actualmente no admite la inserción de etiquetas de personalización/combinación.
- No proporciona un campo de texto alternativo para las imágenes.
- No aplica una línea de asunto, un encabezado previo u otras comprobaciones de nivel de contenido antes de que un correo electrónico se considere &quot;listo&quot;: las únicas comprobaciones previas al inicio son de nivel de campaña (configuración del envío, envío de un correo electrónico de prueba, audiencia real), no comprobaciones del contenido del correo electrónico en sí.
- El alternado de previsualización de escritorio/móvil no está disponible en la vista de edición de correo electrónico de campaña estándar. [SE NECESITA ENTRADA para confirmar el ámbito]
- [NECESITA ENTRADA — para confirmar con el ingeniero: si el editor se convierte en de solo lectura (no solo en el campo del remitente) una vez que se ha activado/iniciado una campaña.]
