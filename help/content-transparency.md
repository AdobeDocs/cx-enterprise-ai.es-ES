---
title: Transparencia de contenido de IA generativa
description: Descubra cómo Adobe adjunta automáticamente los metadatos de C2PA al contenido generado por GenAI y editado por GenAI en las aplicaciones empresariales de Adobe CX.
feature_v2:
  - id: f84b2906-3ce9-4ef0-86f6-cda249273937
  - id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
source-git-commit: 02de82fd17bdf3f806ce120b93cbbd85b50f9b8a
workflow-type: tm+mt
source-wordcount: 1539
ht-degree: 1%

---


# Transparencia de contenido de IA generativa

A lo largo de agosto de 2026, Adobe está implementando gradualmente la compatibilidad con los metadatos de C2PA en las aplicaciones empresariales de Adobe Creative Cloud, Adobe Document Cloud, Adobe Firefly y Adobe CX.

>[!NOTE]
>
>Después del despliegue, los flujos de trabajo futuros que impliquen la creación o edición de contenido mediante IA tendrán automáticamente compatibilidad con metadatos de C2PA.

Esta página cubre detalles sobre cómo Adobe gestiona el adjunto automático de metadatos de C2PA en las aplicaciones empresariales de Adobe CX.

Las nuevas regulaciones requieren que los proveedores de tecnologías de IA generativa admitan divulgaciones duraderas y legibles por máquina asociadas con flujos de trabajo de contenido generados por GenAI y editados por GenAI para una mayor transparencia.

Como proveedor de herramientas, Adobe adjunta automáticamente metadatos de C2PA legibles por el equipo al contenido generado por GenAI y editado por GenAI mediante tecnologías de Adobe (incluidos modelos de IA generativos de terceros compatibles con flujos de trabajo de Adobe). [Más información sobre C2PA](https://c2pa.org/).

## Qué está cambiando

En agosto de 2026, Adobe presentará la compatibilidad con metadatos C2PA en las aplicaciones empresariales Adobe Creative Cloud, Adobe Document Cloud, Adobe Firefly y Adobe CX.

Esta versión incluye:

* Se adjuntan automáticamente metadatos de C2PA al contenido compatible generado por GenAI y editado por GenAI.
* Compatibilidad con tipos de contenido, como imágenes, vídeo, audio y texto.
* Conservación de metadatos de C2PA a través de flujos de trabajo de Adobe admitidos.

No se requiere ninguna acción adicional para adjuntar metadatos de C2PA al contenido de IA generativo correspondiente.

>[!NOTE]
>
>Los metadatos de C2PA no afectarán el aspecto del contenido. Los metadatos de C2PA y las marcas de agua visibles tienen diferentes propósitos. Los metadatos de C2PA proporcionan información de procedencia legible por el equipo, mientras que las marcas de agua visibles proporcionan divulgación visual. Puede elegir añadir marcas de agua visibles al contenido en función de las necesidades comerciales y los requisitos legales de cada jurisdicción aplicable.

## Qué detalles se agregan como parte de los metadatos de C2PA

Los metadatos de C2PA adjuntos automáticamente pueden incluir información como:

* Información sobre el nombre y la versión del sistema de IA utilizado (por ejemplo, Adobe GenStudio, Adobe Firefly)
* Modelo de IA utilizado (por ejemplo, Adobe Firefly)
* Uso: Si se generó o editó mediante GenAI
* Fecha y hora de creación o modificación del contenido con las herramientas de IA generativa
* Identificador único (que puede utilizarse para distinguir cada uso de IA generativa)

## Metadatos de C2PA en el supply chain de contenido

Los metadatos de C2PA están diseñados para permanecer asociados al contenido admitido, a medida que se mueve entre aplicaciones de Adobe y plataformas de terceros compatibles.

A medida que se publica, distribuye o comparte contenido, las plataformas que admiten metadatos C2PA o tecnologías de procedencia relacionadas pueden leer metadatos adjuntos y mostrar información de transparencia a los usuarios.

Adobe no controla cómo los servicios externos interpretan, muestran o utilizan los metadatos de C2PA una vez que el contenido abandona las aplicaciones de Adobe. Los clientes deben consultar la documentación de las plataformas de publicación individuales para comprender cómo se gestionan los metadatos de C2PA.

## Marca de agua visible

En algunas circunstancias y en ciertas regiones geográficas, las organizaciones pueden elegir o se les puede requerir que identifiquen visiblemente el contenido generado por GenAI o editado por GenAI.

Adobe proporciona [orientación](https://helpx.adobe.com/creative-cloud/apps/generative-ai/ai-content-watermarks-faq.html) sobre el uso de funciones de marca de agua existentes admitidas mediante aplicaciones Adobe. La necesidad de una marca de agua visible depende de los requisitos comerciales de una organización y de las leyes y regulaciones aplicables en las jurisdicciones donde se publica el contenido.

>[!NOTE]
>
>Los metadatos de C2PA y las marcas de agua visibles tienen diferentes propósitos. Los metadatos de C2PA proporcionan información de procedencia legible por el equipo, mientras que las marcas de agua visibles proporcionan una divulgación visual que las organizaciones pueden elegir aplicar.

## Disponibilidad y versiones

Estas características se implementarán a lo largo del **agosto de 2026** en todos los flujos de trabajo empresariales de Adobe CX compatibles.

>[!NOTE]
>
>Después del despliegue, los flujos de trabajo futuros que impliquen la creación o edición de contenido mediante IA tendrán automáticamente compatibilidad con metadatos de C2PA.

La versión incluye:

### Metadatos automáticos de C2PA

Los metadatos de C2PA se adjuntan automáticamente al contenido compatible generado por GenAI y editado por GenAI. Esta funcionalidad está habilitada de forma predeterminada y no se puede deshabilitar.

### Guía de filigrana

Adobe proporciona [documentación](https://helpx.adobe.com/creative-cloud/apps/generative-ai/ai-content-watermarks-faq.html) que describe cómo usar las funciones de marca de agua existentes disponibles en las aplicaciones de Adobe compatibles para las organizaciones que eligen o necesitan aplicar etiquetas visibles.

## Aplicaciones compatibles en Adobe CX Enterprise {#supported-applications}

Las siguientes aplicaciones y servicios de Adobe proporcionan información adicional sobre cómo y cuándo se adjuntan los metadatos de C2PA al contenido apto en determinadas aplicaciones de CX Enterprise.

Sin embargo, cuando corresponda, todas las aplicaciones empresariales de Adobe CX siguen conservando los metadatos de C2PA existentes a medida que los recursos admitidos se mueven a través de los flujos de trabajo de Adobe. Esto ayuda a mantener la integridad de la información de procedencia a través de la supply chain de contenido.

>[!NOTE]
>
>Las notas de la versión o directrices para cada una de las aplicaciones enumeradas a continuación estarán disponibles en Experience League en las secciones de la página de producto de sus respectivas aplicaciones. La tabla se actualizará con los vínculos a medida que estén disponibles. Consulte las secciones de productos más recientes sobre Experience League.

| Aplicación/Solución | Notas de la versión/Directrices |
|---|---|
| Adobe Advertising Cloud | |
| Adobe Experience Manager (AEM) | |
| Asistente de IA para la generación de contenido (función de Adobe Journey Optimizer/Adobe Campaign) | <!--[Documentation] (https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b/user/content-management/assets/c2pa-metadata)--> |
| Adobe Journey Optimizer B2B edition | <!--[Documentation] (https://experienceleague.adobe.com/en/docs/journey-optimizer-b2b/user/content-management/assets/content-credentials)--> |
| Adobe Journey Optimizer B2C | |
| Adobe Campaign | |
| Adobe Commerce | |
| GenStudio for Performance Marketing | |
| Adobe Marketo Engage | |
| Adobe Workfront | |
| Campañas de compañeros de CX Enterprise (anteriormente HALO) | <!--[Documentation](https://experienceleague.adobe.com/en/docs/cx-enterprise-ai/experience-cloud-ai/coworker/campaigns/generative-c2pa-metadata)--> |

## Vínculos relacionados

* [Guía de marcas de agua visibles](https://helpx.adobe.com/creative-cloud/apps/generative-ai/ai-content-watermarks-faq.html)
* [Adobe Inspect](https://contentauthenticity.adobe.com/inspect)

## Preguntas frecuentes

**¿Qué aplicaciones de Adobe aplican metadatos de C2PA al contenido generado, editado o creado?**

Las aplicaciones empresariales de Adobe CX compatibles adjuntan automáticamente metadatos de C2PA al contenido apto generado por GenAI y editado por GenAI. Consulte la sección [Aplicaciones compatibles](#supported-applications) para obtener más información sobre las aplicaciones empresariales de Adobe CX.

**¿A qué tipos de contenido agrega Adobe metadatos de C2PA?**

En general, las imágenes, el audio, el vídeo, los documentos y el texto están dentro del ámbito. Sin embargo, consulte la documentación en la sección [Aplicaciones compatibles](#supported-applications) para ver cómo cada aplicación admite metadatos de C2PA en diferentes productos y tipos de contenido.

**¿Qué aplicaciones de Adobe CX conservan los metadatos de C2PA durante la edición y publicación?**

Todas las aplicaciones empresariales de Adobe CX están diseñadas para conservar los metadatos de C2PA a medida que el contenido se mueve a través de flujos de trabajo de Adobe compatibles. La conservación fuera de las aplicaciones de Adobe depende de si las plataformas externas admiten metadatos de C2PA.

**¿Qué sucede cuando se combinan varias imágenes generadas por GenAI en una sola imagen?**

Los metadatos de C2PA resultantes dependen de la aplicación y del flujo de trabajo utilizados. Si es compatible, Adobe conserva la información de procedencia durante todo el proceso de edición. Consulte la sección [Aplicaciones compatibles](#supported-applications-across-adobe-cx-enterprise) para obtener documentación sobre el comportamiento específico del flujo de trabajo en cada aplicación.

**¿Qué sucede cuando se combinan imágenes generadas por GenAI de aplicaciones de Adobe y que no son de Adobe?**

Adobe conserva los metadatos de C2PA disponibles y compatibles con el flujo de trabajo. Siempre que sea aplicable, Adobe actualizará los metadatos subyacentes con la información más reciente siempre que se edite o cree contenido (imagen, audio, vídeo, texto) aplicable con GenAI en los flujos de trabajo de Adobe. Al combinar varias fuentes en un nuevo recurso, los metadatos subyacentes no se sustituyen ni pierden. En su lugar, el nuevo recurso obtiene sus propios metadatos de C2PA y los detalles de cada fuente se conservan dentro de él. Si una fuente ya tenía sus propios metadatos de C2PA (ya provengan de una herramienta Adobe o que no sea de Adobe), el historial permanece adjunto a ella. Esto significa que el recurso final lleva una imagen completa: su propio registro de ser creado o editado con GenAI, además de la historia individual de cada pieza que entró en él.

**¿Los flujos de trabajo editados por GenAI y creados por GenAI en aplicaciones de Adobe CX adjuntan automáticamente metadatos de C2PA?**

Sí. Para los flujos de trabajo de IA generativa admitidos, Adobe adjunta automáticamente metadatos de C2PA que identifican si el contenido se generó mediante GenAI o se editó mediante GenAI junto con otra información de procedencia, como marcas de tiempo, información del sistema de IA e identificadores únicos.

**¿Cómo se mantienen los metadatos de C2PA en el supply chain de contenido?**

Los metadatos de C2PA son metadatos duraderos diseñados para permanecer asociados al contenido admitido a medida que se mueve entre aplicaciones de Adobe compatibles y plataformas de terceros compatibles. Los servicios externos determinan cómo se muestra la información de procedencia adjunta después de la publicación.

**¿Cómo pueden las organizaciones agregar su propia información autenticada sin romper la cadena de procedencia?**

Algunas aplicaciones de Adobe permiten a los creadores y las organizaciones agregar información autenticada adicional a los metadatos de C2PA existentes, conservando al mismo tiempo la procedencia. La disponibilidad varía según la aplicación.

**¿Es posible desactivar el archivo adjunto automático de metadatos de C2PA?**

No. Las nuevas leyes generativas de transparencia de IA requieren que las empresas que proporcionan herramientas de IA generativa, incluido Adobe, adjunten metadatos duraderos al contenido apto generado o editado con IA generativa. No se puede desactivar el adjunto automático de metadatos de C2PA.

**¿Qué sucede con el contenido creado o editado con IA generativa antes de la versión de agosto?**

El contenido creado o editado con herramientas de IA generativa antes de la versión de agosto de 2026 no tiene metadatos de C2PA automáticos adjuntos. Sin embargo, el contenido creado en la web de Firefly y otras aplicaciones a las que se aplicaban metadatos de C2PA anteriormente, sigue teniéndolos adjuntos.

**¿Cómo puede un cliente comprobar si el contenido tiene metadatos de C2PA adjuntos?**

Los clientes pueden comprobar si el contenido tiene metadatos de C2PA adjuntos al cargarlo en la página [Adobe Inspect](https://contentauthenticity.adobe.com/inspect).

**¿Cómo muestran las plataformas externas los metadatos de C2PA una vez que se publica o comparte el contenido?**

A medida que el contenido se mueve entre plataformas de publicación, canales de medios sociales, servicios de correo electrónico y otros ecosistemas digitales, los servicios descendentes que admiten metadatos de C2PA o tecnologías de procedencia relacionadas pueden leer metadatos adjuntos y elegir mostrar divulgaciones o indicadores basados en esa información. Adobe no controla cómo las plataformas externas muestran, interpretan o aplican las divulgaciones asociadas con los metadatos de C2PA adjuntos. Para obtener la información más actual sobre cómo gestiona una plataforma específica la información de procedencia, los clientes deben comprobar directamente las directrices de esa plataforma.

**¿Estos cambios aumentan el costo de los productos o suscripciones de Adobe?**

No. Los metadatos de C2PA no afectan al coste de los productos de Adobe.
