---
description: Casos de uso y ejemplos de mensajes de texto de Browse Coworker Chat, organizados por área en las perspectivas de datos, audiencias, recorridos y operaciones de la plataforma.
title: Casos de uso de chat con compañeros
feature_v2: id: fdae8433-07cd-42e7-acce-738afe63f6bb
source-git-commit: 261f478d3dec0845c0a5532201ef6ddc81808372
workflow-type: tm+mt
source-wordcount: 3729
ht-degree: 6%

---

# Casos de uso de chat con compañeros{#use-cases}

El chat de compañeros de trabajo le permite consultar, analizar y actuar en los datos de [!DNL Experience Platform] con lenguaje natural en lugar de navegar por varias IU o escribir consultas manualmente. Esta página cataloga los casos de uso en los que más se basan los profesionales, organizados por área de trabajo: perspectivas de datos, audiencias, recorridos, elementos fundacionales y herramientas de zona protegida. Cada entrada incluye la aptitud que invoca, las aplicaciones con las que trabaja y los indicadores de ejemplo que puede copiar, adaptar a sus propios datos y refinar a través de la conversación.

>[!NOTE]
>
>Muy pronto:
>
>Nuevas funciones agénticas de AEM a través de CX Enterprise Coworker, creadas para ayudarle a hacer más y más rápido.
>
>Todos los clientes elegibles tendrán acceso a las funciones de agente de Adobe Experience Manager en Coworker, de forma gradual.
>
>Consulte también [IA en AEM: información general sobre las capacidades de agente en AEM](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/overview).

## Experiencia de marca

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Actualizar páginas de AEM | Realice acciones como actualizar, quitar, reemplazar o agregar elementos de contenido para mantener las experiencias precisas y actualizadas. Las entradas pueden ser lenguaje natural o anotaciones visuales como PDF o capturas de pantalla. | `aem-sites-pages-update` | Adobe Experience Manager (AEM) - AEM Sites | En &lt;URL>, actualiza el titular a Hello World<br><br>en &lt;URL> cambia el botón &quot;Prueba de café&quot; a una versión más atractiva<br><br>Actualiza &lt;URL> según el adjunto<br><br>en &lt;URL> Quiero agregar una nueva sección de teaser al final de la página acerca de una promoción que estamos ejecutando en el mes de agosto que es comprar una máquina de café y obtener 2 bolsas de café gratis. Encuentra también una imagen de amigos tomando café y úsala en el teaser |
| Actualización de AEM de forma masiva | Realice acciones masivas en varias páginas al mismo tiempo, como quitar, reemplazar o agregar elementos de contenido para mantener las experiencias precisas y actuales. | `aem-sites-pages-bulkreplace` | Adobe Experience Manager (AEM) - AEM Sites | en &lt;aem path> actualice todas las páginas que contengan copiar &quot;MyBarista\&quot; a &quot;BrewPass&quot; |
| Pasar de Figma a fragmento de contenido visual | Importe diseños directamente desde Figma a Adobe Experience Manager utilizando un lenguaje natural. La aptitud crea automáticamente el modelo de contenido, el fragmento de contenido, los recursos y la plantilla de visualización necesarios, lo que permite a los usuarios empresariales pasar del diseño al contenido compatible con la web en minutos sin necesidad de una configuración manual. | `aem-sites-visualcontentfragments-create` | Adobe Experience Manager (AEM) - AEM Sites | Importar desde &lt;Figma_URL> |

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Crear formulario | Generar un nuevo formulario adaptable a partir de una descripción en lenguaje sencillo, una descripción adjunta, una imagen o una PDF | `aem-forms-adaptiveform-create` | Adobe Experience Manager (AEM) - AEM Forms | &quot;Crear un formulario de incorporación de un empleado&quot;<br><br>&quot;Crear un formulario utilizando el informe adjunto (imagen o pdf)&quot;<br><br>&quot;Crear un &lt;tipo de formulario> formulario adaptable&quot; |
| Editar/actualizar formulario | Modificar un formulario existente: agregar o editar campos, ajustar un diseño simple, configurar acciones de envío o aplicar cambios de un documento de directrices adjunto | `aem-forms-adaptiveform-edit` | Adobe Experience Manager (AEM) - AEM Forms | &quot;Agregar el campo Segundo nombre debajo del campo Nombre&quot;<br><br>&quot;Poner los campos Nombre y Apellidos en un diseño de 2 columnas, 50/50&quot;<br><br>&quot;Configurar el formulario para enviar datos a un extremo REST&quot;<br><br>&quot;Actualizar este formulario para que coincida con el documento de directrices adjunto&quot;<br><br>&quot;Agregar el campo &lt;nombre de campo> debajo del campo &lt;existente>&quot; |
| Agregar lógica empresarial | Crear reglas sencillas, como mostrar u ocultar un campo basado en el valor de otro campo | `aem-forms-adaptiveform-edit` | Adobe Experience Manager (AEM) - AEM Forms | &quot;Mostrar el campo Compañía solo cuando el tipo de empleado es Contratista&quot;<br><br>&quot;Mostrar el campo &lt;field> solo cuando &lt;other field> sea &lt;value>&quot; |
| Incrustar formulario | Coloque un formulario existente o recién creado en una página designada de AEM Sites (solo compatible con páginas de Edge Delivery Services) | `aem-forms-adaptiveform-embed` | Adobe Experience Manager (AEM) - AEM Forms | &quot;Incrustar este formulario en la página principal del sitio&quot;<br><br>&quot;Incrustar este formulario en &lt;ruta de página>&quot; |

**Información relacionada**

* [Funciones agénticas en AEM: experiencia de marca, producción de experiencias, sitios](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/brand-experience/experience-production/use-cases#use-cases-sites)

* [Funciones agénticas en AEM: experiencia de marca, producción de experiencias, Forms](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/brand-experience/experience-production/use-cases#use-cases-forms)

### Desarrollo

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Administrar canalizaciones de Cloud Manager | Cree, ejecute y supervise canalizaciones de AEM Cloud Manager, incluidos registros, artefactos, variables y configuración | `cloud-manager-pipeline-management` | Adobe Experience Manager (AEM) | &quot;Enumerar canalizaciones para el programa 12345&quot;<br><br>&quot;¿Cuál es el estado de mi canalización más reciente?&quot; |
| Administración de entornos de Cloud Manager | Crear, configurar y mantener entornos de AEM Cloud Manager, incluidos RDE, variables de entorno, registros y backups | `cloud-manager-environment-management` | Adobe Experience Manager (AEM) | &quot;Enumerar mis entornos para el programa 12345&quot;<br><br>&quot;Restablecer mi RDE&quot; |
| Administrar programas de Cloud Manager | Enumerar, inspeccionar y eliminar programas de AEM Cloud Manager, incluidas sus canalizaciones y entornos | `cloud-manager-program-management` | Adobe Experience Manager (AEM) | &quot;Enumerar mis programas de Cloud Manager&quot;<br><br>&quot;Obtener detalles para la 12345 del programa&quot; |
| Administrar las programaciones de actualización de versiones de AEM | Configure horas tranquilas diarias y periodos sin actualizaciones para el mantenimiento automatizado y consulte las ventanas globales de congelación de código de Adobe | `cloud-manager-release-management` | Adobe Experience Manager (AEM) | &quot;¿Cuál es mi ventana de horas tranquilas actual?&quot;<br><br>&quot;Programe un período sin actualizaciones del 20 de diciembre al 2 de enero&quot; |

**Información relacionada**

* [Capacidades agénticas en AEM: experiencia de marca - desarrollo](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/brand-experience/development/use-cases)

### Incorporación

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Incorporación integral guiada | Orquesta el ciclo vital de incorporación completo, la selección del repositorio, la delegación a la carpeta, la etiqueta, los metadatos, la importación y las subaptitudes de búsqueda, si no conoce la tarea de incorporación específica que necesita. | `aem-onboarding-workflow` | Adobe Experience Manager (AEM): AEM Assets | &quot;Incorporar nuestro equipo a los AEM Assets&quot;<br><br>&quot;Guíame a través de la incorporación de AEM DAM&quot; |
| Diseño y creación de jerarquías de carpetas | Recomienda y crea estructuras de carpetas escalables en AEM Assets (en `/content/dam`) según las necesidades comerciales o las entradas CSV. | `aem-folder-management` | Adobe Experience Manager (AEM): AEM Assets | &quot;Recomendar una estructura de carpetas para nuestros recursos de marketing de estilo de vida&quot;<br><br>&quot;Crear carpetas basadas en este archivo CSV&quot; |
| Diseño y creación de etiquetas | Diseña y crea vocabularios de etiquetas controlados en `/content/cq:tags`: áreas de nombres, etiquetas jerárquicas y operaciones de etiquetas por lotes. | `aem-tag-taxonomy` | Adobe Experience Manager (AEM): AEM Assets | &quot;Diseñar una taxonomía de etiquetas con áreas de nombres para nuestras categorías de productos&quot;<br><br>&quot;Importar etiquetas de este CSV&quot;<br><br>&quot;Crear estas etiquetas jerárquicas en AEM&quot; |
| Crear y asignar formularios de metadatos | Diseña y crea formularios de metadatos personalizados, que los autores de contenido de la interfaz de usuario de creación utilizan, desde un CSV, una tabla, un documento de requisitos o una descripción, y luego los asigna de forma opcional a las carpetas. | `aem-metadata-form` | Adobe Experience Manager (AEM): AEM Assets | &quot;Crear un formulario de metadatos de esta lista de campos&quot;<br><br>&quot;Asignar este formulario a la carpeta `campaigns`&quot; |

**Información relacionada**

* [Capacidades agénticas en AEM: experiencia de marca - incorporación](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/brand-experience/onboarding/use-cases)

## Asesor de contenido

### Detección de contenido

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Buscar por tema semántico | Busque recursos por concepto, estado de ánimo o tema visual mediante la coincidencia semántica con tecnología de IA. | `aem-assets-discovery` | Adobe Experience Manager (AEM): AEM Assets | &quot;Encuéntrame imágenes de estilo de vida de café matutino&quot; |
| Buscar por metadatos personalizados | Filtre los recursos por campos de metadatos personalizados (por ejemplo, Mezcla de café, Marca, Nivel de tueste). | `aem-assets-discovery` | Adobe Experience Manager (AEM): AEM Assets | &quot;Buscar recursos donde `Coffee Blend` es `Morning Muse`&quot;<br><br>&quot;Obtener recursos cuya licencia no haya caducado&quot;<br><br>&quot;Encontrar recursos cuyo nombre de campaña no esté establecido (la propiedad debe estar indizada para obtener los resultados correspondientes).&quot; |
| Buscar por estado de aprobación | Filtre los recursos en función del estado de aprobación. Por ejemplo, estado aprobado, en revisión, rechazado o ausente. | `aem-assets-discovery` | Adobe Experience Manager (AEM): AEM Assets | &quot;Mostrar todos los recursos aprobados en la carpeta `Campaign`&quot; |
| Buscar por carpeta/ruta | Identifique los recursos mediante la interpretación de indicaciones en lenguaje natural que hagan referencia a nombres de carpetas en AEM. Simplemente puede mencionar la carpeta en su solicitud, sin navegar manualmente por el repositorio, lo que reduce significativamente el número de clics necesarios para localizar el contenido correcto. | `aem-assets-discovery` | Adobe Experience Manager (AEM): AEM Assets | &quot;¿Hay algún svgs en la carpeta `WKND`&quot;?<br><br>&quot;Mostrar los recursos modificados después del 1 de noviembre de 2025 en la carpeta `WKND`&quot; |

**Información relacionada**

* [Capacidades agénticas en AEM: Asesor de contenido: detección de contenido](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/content-advisor/discovery/use-cases)

### Optimización de contenido

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Creación de representaciones de alta resolución y representaciones optimizadas para el canal | Generar nuevas representaciones de un recurso con una resolución y un nivel de calidad especificados, lo que facilita la preparación de variaciones preparadas para el canal sin edición manual. También puede producir representaciones adaptadas a los requisitos específicos de la plataforma, como Historias de Instagram, lo que garantiza que los recursos cumplan automáticamente las directrices de formato, proporción y calidad. | `aem-assets-content-optimisation` | Adobe Experience Manager (AEM): AEM Assets | &quot;Crear una representación de `2000px` como `JPEG` con `80% quality`&quot;<br><br>&quot;Crear una representación para una historia de Instagram&quot; |
| Superposiciones de marcas y generación compuesta | Aplique gráficos promocionales, superposiciones o distintivos a los recursos existentes con una ubicación precisa, lo que permite la creación rápida de composiciones listas para su uso en campañas. | `aem-assets-content-optimisation` | Adobe Experience Manager (AEM): AEM Assets | &quot;Superponga la imagen con `30%` gráficos de descuento sobre el titular promocional, colocándolo `100px` desde el centro&quot; |
| Mejoras de imagen, ajustes de color de fondo, transformaciones de orientación | Aplique mejoras visuales (enfoque de imagen), reemplace los colores de fondo y realice transformaciones de orientación. | `aem-assets-content-optimisation` | Adobe Experience Manager (AEM): AEM Assets | &quot;Cambiar el color de fondo de `PNG` a `#ff8932`&quot;<br><br>&quot;Enfoque de la imagen&quot;<br><br>&quot;Reflejar la imagen horizontalmente&quot; |

**Información relacionada**

* [Capacidades agénticas en AEM: Asesor de contenido: optimización de contenido](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/content-advisor/content-optimization/use-cases)

## Gobernanza de marca

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Directrices y búsqueda de segmentos | Recuperar directrices de marca detalladas, con alcance por segmento, mercado o categoría. | contexto empresarial | Adobe Experience Manager (AEM) | &quot;¿Cuáles son las directrices de tono de voz para esta marca?&quot;<br>&quot;Enumerar las categorías de notificación utilizadas en el vertical de mantenimiento&quot; |
| Evaluar el contenido con las directrices de marca | Evaluar una página, bloque de texto o imagen publicada o creada con comprobaciones de marca configuradas | aem-governance | Adobe Experience Manager (AEM) | &quot;Evaluar esta página de aterrizaje según las directrices de SecurBank&quot;<br>&quot;¿Este lema supera nuestras comprobaciones de tono de voz?&quot; |
| Depuración de permisos de AEM | Depurar o comprender las directivas de permisos, ACL y reglas de herencia. | aem-governance | Adobe Experience Manager (AEM) | &quot;¿Por qué el administrador principal puede escribir `/content/folder/us` en `https://author/` ?&quot;<br>&quot;Por qué no puede el autor de muestra escribir en `/content/dam` en `https://author`&quot; |

**Información relacionada**

* [Capacidades agénticas en AEM: administración de marcas](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/ai-in-aem/agentic-capabilities/brand-governance/use-cases)

## Perspectivas de datos

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| [Extraer informes y métricas de CJA](data-insights/analytics-chat.md) | Consulte CJA en tiempo real para extraer métricas, dimensiones, segmentos y vistas de datos | `cja` | Customer Journey Analytics (CJA) | &quot;Mostrarme vistas de página de los últimos 30 días&quot; <br> &quot;Enumerar los segmentos principales en la vista de datos maestra&quot; |
| Análisis comparativo | Comparar métricas en varios canales, períodos de tiempo o segmentos en paralelo | `cja-root-cause-analysis`, `cja`, `dx-api`, `knowledge-graph` | Customer Journey Analytics (CJA) | &quot;Comparar ingresos por canal mes tras mes&quot; <br> &quot;¿Qué aspecto tiene la conversión de dispositivos móviles frente a equipos de escritorio este trimestre?&quot; |
| Rendimiento de campaña | Mida el rendimiento de las campañas, los canales y las propiedades web durante un periodo determinado. | `cja`, `dx-api`, `knowledge-graph` | | &quot;¿Qué rendimiento tuvieron nuestras campañas web de Acrobat el mes pasado?&quot; |
| Análisis de funnel | Recorra canales de conversión de varios pasos con entrega en cada fase | `cja` | Customer Journey Analytics (CJA) | &quot;Mostrarme el funnel de cierre de compra&quot; <br> &quot;Mostrar funnel de conversión de PDP a compra&quot; |
| Previsión | Proyectar valores de métricas futuras en función de datos históricos de CJA | `cja` | Customer Journey Analytics (CJA) | &quot;Sesiones de pronóstico para los próximos 30 días&quot; <br> &quot;¿Estamos en camino de alcanzar nuestra meta de ingresos?&quot; |
| [Análisis de causa raíz](data-insights/root-cause-analysis.md) | Investigue por qué ha cambiado una métrica: diagnosticar caídas, picos y anomalías | `cja-root-cause-analysis` | Customer Journey Analytics (CJA) | &quot;¿Por qué cayeron las conversiones la semana pasada?&quot; <br> &quot;¿Qué causó el pico de ingresos el 15 de enero?&quot; |
| Resúmenes ejecutivos y resúmenes de KPI | Produzca resúmenes de rendimiento listos para las partes interesadas, recomendaciones prescriptivas y descripciones de diapositivas | `cja-executive-summary`, `cja-bacom-anomaly-tracker-v2`, `cja-cno-weekly-pulse`, `cja-reporting`, `cja`, `dx-api` | Customer Journey Analytics (CJA) | &quot;Proporcionarme un resumen ejecutivo del mes pasado&quot; <br> &quot;Crear un esquema de presentación de diapositivas a partir de los datos de este trimestre&quot; |
| [AA ↔ validación de datos de CJA](data-insights/data-validation-aa-cja.md) | Compare, audite y concilie datos entre Adobe Analytics y Customer Journey Analytics, especialmente al actualizar de Adobe Analytics a Customer Journey Analytics | `aa-cja-validation`, `cja`, `dx-api` | ADOBE ANALYTICS + CJA | &quot;Comparar mi grupo de informes AA con mi vista de datos de CJA&quot; <br> &quot;Validar vistas de página entre AA y CJA&quot; |
| Serie temporal operativa y análisis causal | Consultar y analizar datos de series temporales históricas para audiencias, conjuntos de datos y recorridos con atribución causal | `operational-stats-causal-analysis` | Todas las solicitudes elegibles | &quot;Mostrarme las tendencias de tamaño de audiencia de los últimos 90 días&quot; <br> &quot;¿Por qué aumentó el recuento de filas del conjunto de datos el 3 de marzo?&quot; |
| Crear habilidades personalizadas de CJA | Convierta los patrones analíticos en habilidades reutilizables y repetibles que persisten entre sesiones | `cja-skill-creator` | Customer Journey Analytics (CJA) | &quot;Convierta este análisis de ingresos semanal en una aptitud reutilizable&quot; <br> &quot;Guarde esto como una aptitud para los informes mensuales de funnel&quot; |

## Públicos

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| [Crear audiencias a partir de idioma natural](audiences/create-audience-from-natural-language.md) | Orquestación de la creación de audiencias paso a paso con la aprobación del usuario en cada fase | `audience-creation-flow` | Real-Time CDP (RTCDP) | &quot;Crear una audiencia de usuarios que compraron en los últimos 30 días&quot; <br> &quot;Crear un segmento para miembros de fidelidad de alto valor en California&quot; |
| Generar definiciones de PQL | Montar definiciones de audiencia de propiedades XDM, eventos de comportamiento o audiencias existentes; admitir ventanas de tiempo y agregación | `segment-definition-assembly` | Real-Time CDP (RTCDP) | &quot;Crear un PQL para usuarios que vieron más de 3 productos pero no compraron&quot; <br> &quot;Agregar un período de tiempo de 7 días a mi condición de evento&quot; |
| Buscar y buscar audiencias | Buscar audiencias por ID, nombre y búsqueda semántica; detectar duplicados y analizar la superposición | `audience-search` | Real-Time CDP (RTCDP) | &quot;Buscar todas las audiencias de fidelidad&quot; <br> &quot;¿Hay un duplicado de mi segmento &#39;Compradores de vacaciones&#39;?&quot; |
| Calcular tamaño de audiencia | Calcular el alcance del perfil para una expresión de PQL mediante la API de previsualización de Adobe Experience Platform con sondeo | `audience-size-estimate` | Real-Time CDP (RTCDP) | &quot;¿Qué tamaño tiene esta audiencia?&quot; <br> &quot;Alcance estimado de esta expresión PQL&quot; |
| Cascada de tamaño de audiencia | Descomponga una PQL en subpredicados y muestre cómo cada condición contribuye al tamaño final de la audiencia | `audience-size-waterfall` | Real-Time CDP (RTCDP) | &quot;Mostrarme el salto de agua de este PQL&quot; <br> &quot;Desglose cómo reduce la audiencia cada condición&quot; |
| Descubra los campos XDM para la segmentación | Busque campos por nombre, descripción o valor de datos; vea dónde viven y dónde ya se utilizan | `field-discovery` | Real-Time CDP (RTCDP) | &quot;¿Qué campos puedo utilizar para segmentar clientes fieles?&quot; <br> &quot;Buscar campos relacionados con el historial de compras&quot; |
| Publicación o guardado de audiencias | Mantener las definiciones de audiencia en el servicio de segmentación de Experience Platform con convenciones de nomenclatura y comprobaciones de conformidad | `audience-publish` | Real-Time CDP (RTCDP) | &quot;Guardar esto como borrador&quot; <br> &quot;Publicar la audiencia con el nombre &#39;Compradores de rebajas de primavera&#39;&quot; |

## Recorridos

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| [Crear recorridos a partir de lenguaje natural](journeys/create-journey-from-natural-language.md) | Organizar la creación de recorridos en AJO desde un mensaje de texto o una imagen/diagrama de flujo cargado | `journey-create` | Adobe Journey Optimizer (AJO) | &quot;Cree un recorrido de bienvenida que envíe un correo electrónico después de la suscripción, espere 3 días y envíe un seguimiento&quot; <br> &quot;Genere un recorrido a partir de esta imagen de diagrama de flujo cargada&quot; |
| Analizar conflictos de recorrido | Detectar superposición de audiencias, conflictos de programación y problemas de deduplicación entre recorridos activos | `journey-analyze-conflict` | Adobe Journey Optimizer (AJO) | &quot;¿Está en conflicto el recorrido de abandono del carro de compras con otros recorridos?&quot; <br> &quot;Comprobar si hay superposición de audiencias entre mis recorridos activos&quot; |
| Analizar visitas en el orden previsto de recorrido | Identificar dónde y por qué los clientes abandonan durante un recorrido y detectar patrones de comportamiento que conducen a la desparticipación | `journey-analyze-fallout` | Adobe Journey Optimizer (AJO) | &quot;¿Dónde van a dejar las personas en mi recorrido de renovación de la participación?&quot; <br> &quot;¿Qué nodos del recorrido X tienen las visitas en orden previsto más altas?&quot; |
| Analizar errores de acciones personalizadas | Identifique cuándo las acciones personalizadas producen errores o las tasas de error aumentan dentro de un recorrido y diagnostique las causas raíz antes de que los errores se propaguen en cascada hasta una interrupción más amplia | `journey-analyze-custom-action` | Adobe Journey Optimizer (AJO) | &quot;¿Por qué las acciones personalizadas fallan en mi recorrido de suscripción de fidelización?&quot; <br> &quot;Mostrarme la tasa de error para la acción personalizada ExternalPush en mi recorrido de bienvenida&quot;. |
| [Crear, editar y administrar desafíos de lealtad](journeys/create-loyalty-challenge.md) | Simplificación y aceleración de la administración de programas de fidelización | `loyalty` | Adobe Journey Optimizer (AJO) | &quot;Cree un desafío que anime a los miembros a probar una nueva bebida de temporada&quot; <br> &quot;Muéstreme los desafíos de fidelidad con las tasas más altas de bajas de miembros&quot;. |

## Elementos básicos

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Conocimiento y documentación del producto | Responda preguntas prácticas, conceptuales, de resolución de problemas y prácticas recomendadas de los documentos oficiales de Adobe | `product-knowledge` | Todas las solicitudes elegibles | &quot;¿Cómo configuro un destino de flujo continuo?&quot; <br> &quot;¿Cuál es la diferencia entre la segmentación por lotes y la segmentación por streaming?&quot; |
| Consultar entidades de Experience Platform/Journey Optimizer | Sirva como punto de entrada principal para preguntas sobre las entidades de la plataforma; enrute a KG, detección de campos o API según sea necesario | `operational-insights` | Todas las solicitudes elegibles | &quot;¿Cuántos conjuntos de datos tengo?&quot; <br> &quot;Mostrarme todos los recorridos activos&quot; <br> &quot;Enumerar mis destinos&quot; |
| Consultas de Knowledge Graph | Recuentos agregados, uniones entre entidades, búsquedas de relaciones y exploración de metadatos mediante consultas SQL únicas | `knowledge-graph` | Todas las solicitudes elegibles | &quot;¿Qué audiencias utilizan este conjunto de datos?&quot; <br> &quot;Mostrar mis relaciones entre esquemas y conjuntos de datos&quot; |
| Operaciones de API de Experience Platform/Journey Optimizer/Customer Journey Analytics | Proporcione una puerta de enlace de API directa para mutaciones, comprobaciones de estado en tiempo real y tipos de entidades que no estén en el Gráfico de conocimiento | `cxo-api` | Todas las solicitudes elegibles | &quot;Eliminar conjunto de datos X&quot; <br> &quot;Comprobar el estado de mi trabajo de ingesta por lotes&quot; |
| Resolución y vinculación de entidades | Utilice la búsqueda semántica y léxica para resolver las menciones de entidad a entidades Experience Platform reales y descubrir campos XDM | `entity-linking` | Adobe Experience Platform | &quot;Resolver &#39;Compradores de vacaciones&#39; en una audiencia real&quot; <br> &quot;Encuéntrenme campos relacionados con el historial de compras&quot; |
| Administrar aptitudes personalizadas | Guardar, modificar o eliminar habilidades reutilizables propiedad del usuario que persisten entre sesiones | `manage-skill` | Todas las solicitudes elegibles | &quot;Guardar ese flujo de trabajo como una aptitud&quot; <br> &quot;Eliminar mi aptitud de informe semanal&quot; <br> &quot;Convertir esto en una aptitud reutilizable&quot; |
| Monitorización de la capacidad de streaming y brechas | Compruebe el uso, la capacidad y el estado de brecha de flujo actual e histórico en los entornos limitados | `observability-streaming-capacity`, `observability-streaming-usage`, `observability-capacity-breaches` | Adobe Experience Platform | &quot;¿Cuál es mi capacidad de flujo actual en mi zona protegida actual?&quot; <br> &quot;¿Mi zona protegida actual ha superado los límites de capacidad en la última semana?&quot; |
| [Ver resultados de la evaluación de comprobación de estado](https://experienceleague.adobe.com/en/docs/experience-platform/run-and-operate/health-checks/overview) | Vea la última evaluación de comprobación de estado de la zona protegida, explore en profundidad una comprobación que da error y vea las entidades afectadas | `rao-view-latest-health-checks-assessment` | Adobe Experience Platform | &quot;¿Qué hay de malo en mi zona protegida?&quot; <br> &quot;Informarme sobre la última evaluación de la comprobación de estado&quot; <br> &quot;¿Cuáles son los problemas de la comprobación de descripción de área de nombres personalizada?&quot; |
| Solucionar problemas de comprobación de estado | Corrija los problemas del área de nombres de identidad, la política de combinación y el esquema marcados directamente desde el chat, con su aprobación antes de realizar cualquier cambio | `rao-remediate-identity-namespace-description`, `rao-remediate-merge-policy-duplicate-name`, `rao-remediate-missing-audit-field-group`, `rao-remediate-default-merge-policy-naming` | Adobe Experience Platform | &quot;Corregir descripciones del área de nombres de identidad&quot; <br> &quot;Corregir nombres de políticas de combinación duplicados&quot; <br> &quot;Corregir esquemas que no tienen el grupo de campos de auditoría&quot; <br> &quot;Corregir nombres de políticas de combinación predeterminados&quot; |

## Herramientas de zona protegida

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| [Mover objetos entre zonas protegidas](/help/agents/sandbox-tooling.md) | Migre sin problemas esquemas, audiencias y otras configuraciones de objetos entre entornos limitados, con dependencias resueltas automáticamente | `sandbox-tooling-workflow` | Adobe Experience Platform | &quot;Mover el esquema Platino de miembros de fidelidad de Luma de la zona protegida actual a la zona protegida de producción&quot; <br> &quot;Promocionar la audiencia de miembros de fidelidad de oro de EE. UU. a la fase&quot; |

## Alertas de clientes

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Administrar suscripciones de alerta | Ver y administrar suscripciones de alerta mediante conversaciones en lenguaje natural. | `alerts-subscribe` | Adobe Experience Platform | &quot;¿A qué alertas estoy suscrito?&quot;<br><br>&quot;Suscribirme a esta alerta.&quot;<br><br>&quot;Quitar mi suscripción a esta alerta.&quot; |
| Revisar actividad de alerta | Revisar el estado de alerta actual y la actividad de alerta histórica durante un período de tiempo especificado. | `alerts-list` | Adobe Experience Platform | &quot;¿Qué ha sucedido en las últimas 24 horas?&quot;<br><br>&quot;¿Qué alertas se han activado en las últimas 24 horas?&quot;<br><br>&quot;Mostrar alertas activas de los últimos siete días.&quot; |
| Identificación de patrones de alerta recurrentes | Analice el historial de alertas para identificar los tipos de alertas activados con frecuencia y las tendencias operativas. | `alerts-list` | Adobe Experience Platform | &quot;Mostrarme los 3 tipos de alertas desencadenadas principales.&quot;<br><br>&quot;¿Qué tipos de alertas se produjeron con mayor frecuencia este mes?&quot;<br><br>&quot;¿Qué patrones de alerta se han visto en los últimos siete días?&quot; |
| Centrarse en cuestiones de alta prioridad | Filtre la actividad de alerta por gravedad para priorizar los esfuerzos de investigación. | `alerts-list` | Adobe Experience Platform | &quot;Mostrar solo alertas de gravedad alta.&quot;<br><br>&quot;¿Qué alertas críticas se activaron esta semana?&quot;<br><br>&quot;Mostrar alertas críticas de los últimos 30 días.&quot; |
| Comprender el radio de impacto de las alertas | Identificar los objetos más afectados por las alertas y determinar dónde debe comenzar la investigación. | `alerts-list` | Adobe Experience Platform | &quot;¿Cuáles son los 5 objetos más afectados?&quot;<br><br>&quot;¿Qué objetos están asociados con las alertas de gravedad más alta?&quot; |
| Conexión de tipos de alerta a objetos afectados | Analizar las relaciones entre los tipos de alerta y los recursos afectados. | `alerts-list` | Adobe Experience Platform | &quot;¿Qué tipos de alerta afectaron a este conjunto de datos con mayor frecuencia?&quot;<br><br>&quot;Muestra la relación entre los tipos de alerta y los objetos afectados.&quot;<br><br>&quot;¿Qué tipo de alerta afectó al objeto afectado con mayor frecuencia?&quot; |
| Centrarse en Mis alertas | Analice las alertas a las que se suscribe y de las que es responsable la monitorización. | `alerts-list` | Adobe Experience Platform | &quot;Mostrarme las alertas de alta gravedad a las que me suscribo.&quot;<br><br>&quot;¿Qué alertas de Mis alertas se activaron esta semana?&quot;<br><br>&quot;¿Alguna de mis alertas suscritas requiere atención?&quot; |

## Flujo de trabajo y planificación

| Caso de uso | Descripción | Habilidades | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Administrar espacio de trabajo de Planning | Cree y desarrolle espacios de trabajo, secciones, tipos de registros y campos de Workfront Planning para organizar programas y realizar un seguimiento del trabajo | `manage-workfront-planning`, `wf-planning-solution-architect` | Planificación de Workfront | &quot;Cree un espacio de trabajo denominado MKG Hub y configure tipos de registros para realizar el seguimiento de programas por región&quot; <br> &quot;Configure los tipos de registros y las relaciones necesarias para realizar el seguimiento de los programas MKG en todos los canales y regiones&quot; |
| Administrar registros de Planning | Crear y actualizar registros de planificación (campañas, informes) y sus valores de campo en un espacio de trabajo. | `manage-workfront-planning` | Planificación de Workfront | &quot;Crear una información para la campaña de Otoño de Brand Launch con el objetivo, la audiencia de destino y los mensajes clave&quot; <br> &quot;Actualizar la información de Otoño de Brand Launch con el presupuesto y los canales principales&quot; |
| Creación y administración de proyectos | Girar y estructurar proyectos: aplicar plantillas, establecer prioridades y presupuestos, secuenciar tareas, agregar fases y dependencias y asignar personas o roles | `manage-workfront-workflow` | Flujo de trabajo Workfront | &quot;Cree una campaña de primavera, establézcala de alta prioridad con un presupuesto de 200.000 $ y secuencie las tareas&quot; <br> &quot;Cree un plan de proyecto de Workfront denominado [nombre de proyecto] a partir de [plantilla de proyecto]&quot; <br> &quot;Genere un plan de proyecto para Launch de otoño - Campaña social con tareas para concebir, diseñar, copiar y revisar&quot; <br> &quot;Agregue una nueva tarea de marketing por correo electrónico y asígnela a Rachel Smith&quot; |
| Acelerar revisiones y aprobaciones | Configure aprobaciones de varias fases, aplique plantillas de aprobación, añada o elimine aprobadores, envíe recordatorios y realice actualizaciones masivas | `manage-workfront-workflow` | Flujo de trabajo Workfront | &quot;Crear una aprobación de varias fases (copiar, diseñar, legal) y recordar a todo el que no haya aprobado&quot; <br> &quot;Quitar a Chris Smith de todas las aprobaciones abiertas y reemplazarla por Jane Francis&quot; |
| Actualizar estado de trabajo y tarea | Marcar las tareas como completadas, actualizar el porcentaje completado y cerrar el trabajo | `manage-workfront-workflow` | Flujo de trabajo Workfront | &quot;Marcar mi tarea &#39;Producir ilustraciones clave&#39; en el lanzamiento de otoño como completada&quot; <br> &quot;Cerrar mi tarea de copia del lanzamiento de otoño al 100%&quot; |
| Perspectivas de trabajo superficial | Haga preguntas exploratorias para encontrar trabajo en riesgo, tareas sin asignar, problemas pendientes y estado en todos los proyectos | `query-workfront` | Flujo de trabajo Workfront | &quot;Encontrar tareas incompletas en proyectos actuales que no están asignados a nadie y que vencen esta semana&quot; <br> &quot;¿Cuántos problemas pendientes hay en los proyectos actuales?&quot; |
| Resumen de proyectos y tareas | Extraer listas, tablas y recuentos de proyectos, tareas, problemas y asignaciones | `query-workfront` | Flujo de trabajo Workfront | &quot;Mostrarme una tabla de mis tareas que están listas para iniciarse, con el nombre del proyecto, la fecha de vencimiento de la tarea y el usuario asignado&quot; <br> &quot;Asignarme todas las tareas asignadas a [nombre de usuario]&quot; |
| Seguimiento de aprobaciones y estado del portafolio | Comprobar el estado de las aprobaciones y resumir el trabajo incompleto por portafolio | `query-workfront` | Flujo de trabajo Workfront | &quot;Mostrarme el estado de mis aprobaciones&quot; <br> &quot;Mostrarme una tabla con problemas incompletos que forman parte del portafolio [Portfolio name]&quot; |
