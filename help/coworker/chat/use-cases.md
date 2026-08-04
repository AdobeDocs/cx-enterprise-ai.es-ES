---
description: Casos de uso y ejemplos de mensajes de texto de Browse Coworker Chat, organizados por área en las perspectivas de datos, audiencias, recorridos y operaciones de la plataforma.
title: Casos de uso
source-git-commit: 5de0afec89309ab62bd50e0c2cb1d0e96890c57f
workflow-type: tm+mt
source-wordcount: '1134'
ht-degree: 3%

---

# Casos de uso {#use-cases}

A continuación se muestran casos de uso y ejemplos de mensajes que los profesionales utilizan en Adobe Coworker Chat, organizado por área de trabajo. Cada mensaje se crea para copiarse, adaptarse con sus propios datos y contexto, y refinarse a través de la conversación.

## Perspectivas de datos

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Extraer informes y métricas de CJA | Consulte CJA en tiempo real para extraer métricas, dimensiones, segmentos y vistas de datos | `cja` | Customer Journey Analytics (CJA) | &quot;Mostrarme vistas de página de los últimos 30 días&quot; · &quot;Enumerar los segmentos principales en la vista de datos maestra&quot; |
| Análisis comparativo | Comparar métricas en varios canales, períodos de tiempo o segmentos en paralelo | `cja` | Customer Journey Analytics (CJA) | &quot;Comparar los ingresos por canal mes tras mes&quot; · &quot;¿Qué aspecto tienen las conversiones móviles frente a los equipos de escritorio este trimestre?&quot; |
| Análisis de funnel | Recorra canales de conversión de varios pasos con entrega en cada fase | `cja` | Customer Journey Analytics (CJA) | &quot;Guíame a través del funnel de pago y envío&quot; · &quot;Mostrar funnel de conversión de PDP a compra&quot; |
| Previsión | Proyectar valores de métricas futuras en función de datos históricos de CJA | `cja` | Customer Journey Analytics (CJA) | &quot;Sesiones de pronóstico para los próximos 30 días&quot; · &quot;¿Estamos en camino de alcanzar nuestra meta de ingresos?&quot; |
| Análisis de la causa raíz | Investigue por qué ha cambiado una métrica: diagnosticar caídas, picos y anomalías | `cja-root-cause-analysis` | Customer Journey Analytics (CJA) | &quot;¿Por qué cayeron las conversiones la semana pasada?&quot; · &quot;¿Qué causó el pico de ingresos del 15 de enero?&quot; |
| Resúmenes ejecutivos y resúmenes de KPI | Produzca resúmenes de rendimiento listos para las partes interesadas, recomendaciones prescriptivas y descripciones de diapositivas | `cja-executive-summary` | Customer Journey Analytics (CJA) | &quot;Dame un resumen ejecutivo del mes pasado&quot; · &quot;Crea un esquema de diapositivas a partir de los datos de este trimestre&quot; |
| Validación de datos de CJA de AA ↔ | Comparar, auditar y reconciliar datos entre Adobe Analytics y Customer Journey Analytics | `aa-cja-validation` | ADOBE ANALYTICS + CJA | &quot;Comparar mi grupo de informes AA con mi vista de datos de CJA&quot; · &quot;Validar vistas de página entre AA y CJA&quot; |
| Serie temporal operativa y análisis causal | Consultar y analizar datos de series temporales históricas para audiencias, conjuntos de datos y recorridos con atribución causal | `operational-stats-causal-analysis` | Todas las solicitudes elegibles | &quot;Mostrarme las tendencias de tamaño de audiencia en los últimos 90 días&quot; · &quot;¿Por qué aumentó el recuento de filas del conjunto de datos el 3 de marzo?&quot; |
| Crear habilidades personalizadas de CJA | Convierta los patrones analíticos en habilidades reutilizables y repetibles que persisten entre sesiones | `cja-skill-creator` | Customer Journey Analytics (CJA) | &quot;Convierta este análisis de ingresos semanal en una aptitud reutilizable&quot; · &quot;Guarde esta aptitud para la creación de informes mensuales de funnel&quot; |

## Públicos

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Crear audiencias a partir de lenguaje natural | Orquestación de la creación de audiencias paso a paso con la aprobación del usuario en cada fase | `audience-creation-flow` | Real-Time CDP (RTCDP) | &quot;Crear una audiencia de usuarios que hayan realizado compras en los últimos 30 días&quot; · &quot;Crear un segmento para miembros fieles de alto valor en California&quot; |
| Generar definiciones de PQL | Montar definiciones de audiencia de propiedades XDM, eventos de comportamiento o audiencias existentes; admitir ventanas de tiempo y agregación | `segment-definition-assembly` | Real-Time CDP (RTCDP) | &quot;Crear un PQL para usuarios que hayan visto más de 3 productos pero no hayan comprado&quot; · &quot;Añadir un periodo de tiempo de 7 días a mi condición de evento&quot; |
| Buscar y buscar audiencias | Buscar audiencias por ID, nombre y búsqueda semántica; detectar duplicados y analizar la superposición | `audience-search` | Real-Time CDP (RTCDP) | &quot;Buscar todas las audiencias de fidelidad&quot; · &quot;¿Hay un duplicado de mi segmento &quot;Compradores de vacaciones&quot;?&quot; |
| Calcular tamaño de audiencia | Calcular el alcance del perfil para una expresión de PQL mediante la API de previsualización de AEP con sondeo | `audience-size-estimate` | Real-Time CDP (RTCDP) | &quot;¿Qué tamaño tiene esta audiencia?&quot; · &quot;Alcance estimado de esta expresión de PQL&quot; |
| Cascada de tamaño de audiencia | Descomponga una PQL en subpredicados y muestre cómo cada condición contribuye al tamaño final de la audiencia | `audience-size-waterfall` | Real-Time CDP (RTCDP) | &quot;Mostrarme el salto de agua de este PQL&quot; · &quot;Desglose cómo reduce la audiencia cada condición&quot; |
| Descubra los campos XDM para la segmentación | Busque campos por nombre, descripción o valor de datos; vea dónde viven y dónde ya se utilizan | `field-discovery` | Real-Time CDP (RTCDP) | &quot;¿Qué campos puedo utilizar para segmentar clientes fieles?&quot; · &quot;Buscar campos relacionados con el historial de compras&quot; |
| Publicación o guardado de audiencias | Mantener las definiciones de audiencia en el servicio de segmentación de AEP con convenciones de nomenclatura y comprobaciones de conformidad | `audience-publish` | Real-Time CDP (RTCDP) | &quot;Guardar como borrador&quot; · &quot;Publicar la audiencia con el nombre &#39;Compradores de rebajas de primavera&#39;&quot; |

## Recorridos

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Crear recorridos a partir del lenguaje natural | Organizar la creación de recorridos en AJO desde un mensaje de texto o una imagen/diagrama de flujo cargado | `journey-create` | Adobe Journey Optimizer (AJO) | &quot;Cree un recorrido de bienvenida que envíe un correo electrónico después de la suscripción, espere 3 días y, a continuación, envíe un seguimiento&quot; · &quot;Crear un recorrido a partir de esta imagen de diagrama de flujo cargada&quot; |
| Analizar conflictos de recorrido | Detectar superposición de audiencias, conflictos de programación y problemas de deduplicación entre recorridos activos | `journey-analyze-conflict` | Adobe Journey Optimizer (AJO) | &quot;¿El abandono del carro de compras entra en recorrido con algún otro recorrido?&quot; · &quot;Comprobar si hay superposición de audiencias entre mis recorridos activos&quot; |

## Elementos básicos

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Conocimiento y documentación del producto | Responda preguntas prácticas, conceptuales, de resolución de problemas y prácticas recomendadas de los documentos oficiales de Adobe | `product-knowledge` | Todas las solicitudes elegibles | &quot;¿Cómo configuro un destino de streaming?&quot; · &quot;¿Cuál es la diferencia entre la segmentación por lotes y la segmentación por streaming?&quot; |
| Consultar entidades de AEP/AJO | Sirva como punto de entrada principal para preguntas sobre las entidades de la plataforma; enrute a KG, detección de campos o API según sea necesario | `operational-insights` | Todas las solicitudes elegibles | &quot;¿Cuántos conjuntos de datos tengo?&quot; · &quot;Mostrar todos los recorridos activos&quot; · &quot;Enumerar mis destinos&quot; |
| Consultas de Knowledge Graph | Recuentos agregados, uniones entre entidades, búsquedas de relaciones y exploración de metadatos mediante consultas SQL únicas | `knowledge-graph` | Todas las solicitudes elegibles | &quot;¿Qué audiencias utilizan este conjunto de datos?&quot; · &quot;Mostrar mis relaciones entre esquemas y conjuntos de datos&quot; |
| Operaciones de API de AEP/AJO/CJA | Proporcione una puerta de enlace de API directa para mutaciones, comprobaciones de estado en tiempo real y tipos de entidades que no estén en el Gráfico de conocimiento | `cxo-api` | Todas las solicitudes elegibles | &quot;Eliminar conjunto de datos X&quot; · &quot;Comprobar el estado de mi trabajo de ingesta por lotes&quot; |
| Resolución y vinculación de entidades | Utilice la búsqueda semántica y léxica para resolver las menciones de entidad a entidades AEP reales y descubrir campos XDM | `entity-linking` | Adobe Experience Platform (AEP) | &quot;Resolver &quot;Compradores de vacaciones&quot; en una audiencia real&quot; · &quot;Buscar campos relacionados con el historial de compras&quot; |
| Crear contexto personal | Genere un perfil de usuario personalizado a partir de los registros de actividad de AEP, CJA o Workfront | `build-my-context` | Todas las solicitudes elegibles | &quot;Crear mi contexto a partir de la actividad de AEP y CJA&quot; · &quot;¿Quién soy yo en esta organización?&quot; |
| Contexto de organización de Destilación | Extraer conocimiento de toda la organización de un documento en la wiki compartida de contexto de organización. | `distill-org-context` | Todas las solicitudes elegibles | &quot;Destilar este documento en la wiki de la organización&quot; · &quot;Agregar este archivo al contexto de la organización&quot; |
| Destilar contexto de usuario | Extraer el contexto de trabajo personal de un documento en su wiki de contexto de usuario | `distill-user-context` | Todas las solicitudes elegibles | &quot;Agregar este archivo a mi contexto de usuario&quot; · &quot;Extraer mi contexto de trabajo de este documento&quot; |
| Administrar aptitudes personalizadas | Guardar, modificar o eliminar habilidades reutilizables propiedad del usuario que persisten entre sesiones | `manage-skill` | Todas las solicitudes elegibles | &quot;Guardar ese flujo de trabajo como una aptitud&quot; · &quot;Eliminar mi aptitud de informe semanal&quot; · &quot;Convertir esto en una aptitud reutilizable&quot; |

## Herramientas de zona protegida

| Caso de uso | Descripción | Aptitud/aptitudes | Aplicación | Indicadores de ejemplo |
| --- | --- | --- | --- | --- |
| Mover metadatos de objetos entre zonas protegidas | Migre sin problemas esquemas, audiencias y otras configuraciones de objetos entre entornos limitados, con dependencias resueltas automáticamente | `sandbox-tooling-workflow` | Adobe Experience Platform (AEP) | &quot;Mueva el esquema Platino de los miembros de la lealtad de Luma de la zona protegida actual a la zona protegida de producción&quot; · &quot;Promocione la audiencia de miembros de la lealtad de oro de EE. UU. a la fase&quot; |
