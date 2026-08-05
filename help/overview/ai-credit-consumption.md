---
title: Consumo de crédito de IA
description: Obtenga información sobre el consumo de créditos de IA en aplicaciones de CX Enterprise.
solution: Experience Cloud
topic: Artificial Intelligence
feature: Agentic AI, AI Tools
role: Admin, User
level: Intermediate
last-update: '2026-05-21T00:00:00.000Z'
feature_v2: id: f84b2906-3ce9-4ef0-86f6-cda249273937
source-git-commit: 28e8b218e0923c9e463cce763a182b56a660d275
workflow-type: tm+mt
source-wordcount: 967
ht-degree: 5%

---

# Consumo de créditos de IA

Obtenga información sobre el consumo de créditos de IA en aplicaciones de CX Enterprise.

## Créditos de IA

Un _crédito de IA_ es una métrica basada en el uso que cuantifica la ejecución de acciones o trabajos.

## Servicios aptos que consumen créditos de IA

* [CX Enterprise Coworker](#cx-enterprise-coworker-credit-rate)
* [Agentes AEP](#aep-agents-credit-rate)

### Tasa de crédito de los compañeros de CX Enterprise

Durante un periodo de introducción limitado, las entradas de Coworker consumen créditos de IA a una tasa de 25 créditos de IA por entrada. Esta tarifa está disponible por tiempo limitado y está sujeta a cambios.

### Tasa de crédito de agentes de AEP

Un _trabajo de agente_ es una serie de tareas y acciones que ejecuta un agente de AEP para lograr un resultado específico, según lo indicado por las entradas del cliente.

Con las indicaciones en lenguaje natural a través del asistente de IA, puede pedir a los agentes que realicen trabajos específicos. En función de estas entradas, Agent Orchestrator coordina los agentes adecuados para ejecutar cada paso dentro de las aplicaciones de CX Enterprise relevantes.

El uso del crédito de IA puede variar según la complejidad y el valor del trabajo ejecutado:

* Las tareas sencillas (a menudo de un solo paso) consumen menos créditos
* Las tareas complejas (a menudo de varios pasos) consumen más créditos
* Las tareas que implican razonamiento avanzado, validación, coordinación de varios agentes o integración consumen más créditos

Para ver qué agentes de AEP y qué trabajos de agentes están disponibles en sus aplicaciones empresariales con licencia de CX, consulte [Catálogo de funciones de inteligencia artificial aplicada a la empresa de CX](https://agentic-capability-explorer.entapp.adproto.com/).

#### Tasas de crédito estimadas del trabajo del agente

| Agente | Trabajo | Aplicaciones compatibles | Créditos estimados de IA | Ejemplos de peticiones de datos |
| ------ | ----- | ------------------------ | ----------------------- | ----------------- |
| Audience Agent | Audiencia/ideación de cuenta | <ul><li>Real-Time CDP (Ediciones B2B, B2C y B2P)</li><li>Adobe Journey Optimizer (B2C Edition)</li></ul> | 50 | <ul><li><em>Mostrarme campos para compradores adinerados</em></li><li><em>Buscar todos los campos relacionados con las preferencias del cliente</em></li></ul> |
| Audience Agent | Administración de audiencias y cuentas | <ul><li>Real-Time CDP (Ediciones B2B, B2C y B2P)</li><li>Adobe Journey Optimizer (B2C Edition)</li></ul> | 25 | <ul><li><em>¿Tengo audiencias duplicadas?</em></li><li><em>Mostrarme las 5 audiencias más grandes.</em></li><li><em>Mostrar audiencias que no están activadas en ningún destino</em></li><li><em>Enumerar todas las audiencias utilizadas en recorridos activos</em></li></ul> |
| Audience Agent | Análisis de audiencia/cuenta | <ul><li>Real-Time CDP (Ediciones B2B, B2C y B2P)</li><li>Adobe Journey Optimizer (B2C Edition)</li></ul> | 25 | <ul><li><em>¿Qué audiencias aumentaron en tamaño en más de un 20% en la última semana?</em></li><li><em>¿Cuánto ha cambiado la audiencia &quot;Platino fiel&quot; en comparación con el valor de hace 30 días?</em></li><li><em>¿Cuál es mi audiencia que crece más rápido?</em></li></ul> |
| Audience Agent | Ideación de grupo de compra | <ul><li>Adobe Journey Optimizer (B2B edition)</li></ul> | 25 | <ul><li><em>¿Qué cuentas muestran intención para estos productos?</em></li><li><em>Mostrarme las personas principales por intención de producto para XYZ.</em></li><li><em>¿Qué grupos compradores tienen más de 5 miembros?</em></li></ul> |
| Data Insights Agent | Análisis y visualización de datos | <ul><li>Customer Journey Analytics (Ediciones B2C y B2B)</li></ul> | 25 | <ul><li><em>Tendencia de pedidos en julio</em></li><li><em>Mostrar ingresos por región.</em></li><li><em>Mostrar pedidos por sexo, de marzo a junio.</em></li><li><em>Cuáles fueron mis 10 SKU principales por beneficio en junio</em></li><li><em>Proporción de compras por mes del año</em></li><li><em>Porcentaje de ingresos por categoría de producto</em></li></ul> |
| Journey Agent | ideación de recorrido | <ul><li>Adobe Journey Optimizer (B2B edition)</li></ul> | 25 | <ul><li><em>Cree un recorrido para cuentas de espacio en blanco con intención de usar mi solución, centrándose en las personas que participan con contenido en el sitio web</em></li></ul> |
| Journey Agent | análisis de recorrido | <ul><li>Adobe Journey Optimizer (Ediciones B2B y B2C)</li></ul> | 50 | <ul><li><em>Quiero analizar las visitas en el orden previsto por nodo para la campaña del 4 de julio de recorrido.</em></li><li><em>Hay algún conflicto de programación para el recorrido X</em></li><li><em>Mostrarme conflictos de superposición de audiencia para el recorrido X</em></li></ul> |
| Journey Agent | administración de recorrido | <ul><li>Adobe Journey Optimizer (Ediciones B2B y B2C)</li></ul> | 25 | <ul><li><em>¿Cuántos recorridos activos tengo?</em></li><li><em>Enumerar todos los recorridos con la audiencia X.</em></li><li><em>Enumerar todos los recorridos que se encuentran actualmente en modo de prueba</em></li></ul> |
| Agente de soporte del producto | Solución de problemas basada en conocimientos | <ul><li>Real-Time CDP (Ediciones B2B, B2C y B2P)</li><li>Adobe Journey Optimizer (Ediciones B2C y B2B)</li><li>Customer Journey Analytics (Ediciones B2C y B2B)</li></ul> | 0 | <ul><li><em>¿Por qué difiere el recuento de perfiles en el Tablero de uso de licencias y en la página de inicio de Experience Platform?</em></li><li><em>¿Cuáles son las razones por las que no se activa un recorrido?</em></li><li><em>¿Cómo crea Adobe Experience Platform experiencias en tiempo real?</em></li><li><em>¿Cómo se configuran y utilizan las alertas en Adobe Experience Platform?</em></li><li><em>¿Cuál es el límite promedio de riqueza de perfiles en Adobe Experience Platform Activation?</em></li></ul> |
| Agente de soporte del producto | Creación y seguimiento de casos de soporte | <ul><li>Real-Time CDP (Ediciones B2B, B2C y B2P)</li><li>Adobe Journey Optimizer (Ediciones B2C y B2B)</li><li>Customer Journey Analytics (Ediciones B2C y B2B)</li><li>Adobe Experience Manager</li></ul> | 10 | <ul><li><em>Crear un nuevo ticket de soporte para mi trabajo de segmentación con errores</em></li><li><em>¿Cuál es el estado del ticket E-001772068?</em></li></ul> |
| Agente del Asesor de contenido | Detección de contenido | <ul><li>Adobe Experience Manager</li></ul> | 5 | <ul><li><em>Mostrar fragmentos de contenido para crear la campaña de ofertas WKND.</em></li><li><em>Buscar imágenes PNG para empaquetar productos.</em></li><li><em>Mostrar imágenes etiquetadas de Office en la carpeta WKND.</em></li><li><em>¿Hay algún svg en la carpeta WKND?</em></li><li><em>Mostrarme todos los formularios de solicitud de préstamo.</em></li><li><em>Busco formularios de incorporación de empleados.</em></li></ul> |
| Agente del Asesor de contenido | <ul><li>Optimización de contenido</li></ul> | <ul><li>Adobe Experience Manager Assets y Dynamic Media</li></ul> | 10 | <ul><li><em>Cree una representación de 2000 px como JPEG con una calidad del 80 %.</em></li><li><em>Crear una representación para una historia de Instagram.</em></li><li><em>Superponga la imagen con gráficos con un descuento del 30% sobre el titular promocional, situándola a 100 píxeles del centro.</em></li><li><em>Cambiar el color de fondo del PNG a #ff8932.</em></li></ul> |
| Agente de control de marca | <ul><li>Comprobaciones de directivas de marca</li></ul><ul><li>Permisos con Content Hub</li></ul><ul><li>Caducidad de recursos</li></ul> | <ul><li>Adobe Experience Manager Sites (Políticas de marca)</li></ul><ul><li>Adobe Experience Manager Assets</li></ul> | 25 | <ul><li><em>¿Esta página está alineada con mi marca? `https://www.website/en.html`</em></li><li><em>Mostrar todas las reglas ABAC de Content Hub existentes</em></li><li><em>¿Alguno de mis recursos caducará pronto?</em></li></ul> |
| Brand Experience Agent | <ul><li>Actualización de contenido</li><li>Creación de Forms</li><li>Solución de problemas de canalización</li></ul> | <ul><li>Adobe Experience Manager Cloud Services</li><li>Adobe Experience Manager Sites</li><li>Adobe Experience Manager Forms</li></ul> | 50 | <ul><li><em>El `URL`, actualice el titular a Hello world</em></li><li><em>Crear un formulario de contacto con campos de nombre, correo electrónico y mensaje</em></li><li><em>Solucionar problemas de mi canalización con errores</em></li><li><em>Enumerar mis canalizaciones con errores para el programa principal.</em></li></ul> |
| Brand Experience Agent | Modernización del sitio | Adobe Experience Manager Cloud Services | 100 | <ul><li><em>Migrar la página `https://wknd-trendsetters.site`</em></li></ul> |

>[!NOTE]
>
>El consumo real de crédito de IA puede variar según el número de pasos ejecutados y las iteraciones por paso.

## Más ayuda sobre este tema

* [GenAI en CX Enterprise](generative-ai.md)
* [IA agéntica en CX Enterprise](agentic-ai.md)
* [Prueba enlazada al uso de agentes de Adobe Experience Platform](https://experienceleague.adobe.com/en/docs/cx-enterprise-ai/experience-cloud-ai/agents/trial)
