---
description: Descubra cómo Campañas de colaboración adjunta y conserva automáticamente los metadatos de C2PA (Content Credentials) en imágenes generadas y editadas por IA, sin necesidad de realizar ninguna acción.
title: Metadatos de C2PA en campañas de compañeros de trabajo
hide: true
source-git-commit: 785b5d106cb029d68506c90385786cbdae164991
workflow-type: tm+mt
source-wordcount: '684'
ht-degree: 2%

---

# Metadatos de C2PA en campañas de compañeros de trabajo {#overview}

Están surgiendo nuevas leyes en torno a la transparencia generativa de la IA, y Adobe está trabajando para cumplir con los requisitos aplicables en todas las jurisdicciones. [Metadatos de C2PA](https://c2pa.org/) (también conocidos como Content Credentials) es la herramienta de procedencia que utiliza Adobe para cumplir con los requisitos de estas leyes.

Los metadatos de C2PA son metadatos duraderos e invisibles que registran cómo se creó o editó un fragmento de contenido. Cuando se genera o edita una imagen con herramientas de IA generativa en Campañas de Coworker, los metadatos de C2PA se adjuntan automáticamente a esa imagen. No se requiere ninguna acción por su parte.

## Acciones que adjuntan metadatos de C2PA {#cc-workflows}

La siguiente tabla resume cuándo se adjuntan los metadatos de C2PA, en función de la acción de imagen realizada en la generación de imágenes en Campañas de Coworker.

| Acción | Descripción | ¿Metadatos de C2PA adjuntos? | Ejemplo de caso de uso |
| --- | --- | --- | --- |
| **Generar una imagen** | Cree una nueva imagen a partir de un mensaje de texto o una imagen de referencia, o genere una imagen similar a partir de una existente. | Siempre. La imagen se genera mediante IA generativa, por lo que siempre lleva metadatos frescos de C2PA. | Se genera una imagen de titular para una campaña de correo electrónico a partir de un mensaje de texto que describe el elemento visual deseado. |
| **Recortar una imagen** (recorte central o inteligente) | Ajuste de una imagen a las dimensiones solicitadas | Solo si la imagen de origen ya tenía metadatos de C2PA. El recorte vuelve a crear los píxeles de la imagen, lo que normalmente borraría esos metadatos de C2PA, por lo que la generación de imágenes en Campañas de colaboración la lee de la imagen de origen antes de recortarla y, a continuación, la vuelve a compilar y a adjuntar al resultado recortado. El recorte en sí no agrega una nueva acción de IA generativa; conserva la existente. | Se recorta una imagen de titular generada para que se ajuste a una página web: los metadatos de C2PA se conservan a través del recorte. <br> Se recorta una foto de archivo cargada que se utiliza como fondo de notificación push para ajustarse a la pantalla: como la foto de archivo no lleva ninguna acción de IA generativa, no se crean metadatos de C2PA. |
| **Agregar una superposición de texto** | Procesar texto generado sobre una imagen de fondo | Solo si la imagen de fondo ya tenía metadatos de C2PA. Al procesar la superposición, se produce una nueva imagen del fondo más el texto, que normalmente borraría esos metadatos de C2PA, por lo que la generación de imágenes en Campañas de colaboración la lee de antemano de la imagen de fondo y, a continuación, la reconstruye y la vuelve a adjuntar al resultado. El paso de superposición no agrega una nueva acción de IA generativa. | Un titular promocional se procesa como una superposición de texto en una imagen de fondo generada para una página de aterrizaje: se conservan los metadatos de C2PA de la imagen de fondo. |
| **Imágenes de superposición** | Componer dos o más imágenes juntas | Si alguna de las imágenes de origen tiene metadatos C2PA, la imagen combinada lleva todo, combinado en un único conjunto de metadatos C2PA. La composición produce una nueva imagen a partir de las fuentes, que normalmente borraría esos metadatos de C2PA, por lo que la generación de imágenes en Campañas de colaboración lee cada una antes de la composición y, a continuación, crea un registro de metadatos de C2PA combinado que enumera todas las fuentes que contribuyeron con una acción de IA generativa. | Una imagen de producto generada se compone de un fondo generado para un encabezado de correo electrónico: el resultado lleva metadatos de C2PA que reflejan ambas fuentes de IA generativas. <br> Dos fotos de marca cargadas se componen en un collage: como ninguna de las fuentes lleva una acción de IA generativa, no se crean metadatos de C2PA. |

## Tipos de contenido y su ámbito {#cc-content-types}

* **Imágenes**: Cubiertas. Los metadatos de C2PA se adjuntan cuando las imágenes se generan con IA generativa y se conservan mediante las operaciones de recorte, superposición de texto y superposición de imágenes realizadas por la generación de imágenes en Campañas de colaboración.
* **Texto**: No aplicable. Las salidas de solo texto de la generación de imágenes en Campañas de Coworker, como la generación de copias, la traducción y las sugerencias de alineación de marca, no requieren metadatos de C2PA.

## Qué sucede a medida que se mueve el contenido {#cc-content-moves}

Campañas de compañeros conserva Content Credentials asociado con los recursos de imagen admitidos. Si una imagen contiene Content Credentials cuando se importa en Campañas de compañeros, esas credenciales se conservan cuando el recurso se utiliza en el contenido de campaña generado y en las experiencias de correo electrónico saliente. [Más información acerca de los metadatos de C2PA](https://helpx.adobe.com/es/firefly/using/content-credentials.html){target="_blank"}.

<!-- Some ways of bringing images into your content, such as extracting an image from a PDF or from an embedded (base64) source, may not preserve the original C2PA metadata. In these cases, no C2PA metadata can be read from the source, and none is created for the result. -->

>[!MORELIKETHIS]
>
>[Directrices de usuario de IA generativa de Adobe Experience Cloud](https://www.adobe.com/legal/licenses-terms/adobe-dx-gen-ai-user-guidelines.html){target="_blank"}
