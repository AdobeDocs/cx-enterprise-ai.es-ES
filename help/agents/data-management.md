---
title: Agente de administración de datos para Adobe Experience Platform
description: Aprenda a utilizar el agente de administración de datos en CX Coworker para buscar y analizar conjuntos de datos de Adobe Experience Platform y administrar políticas de retención de lago de datos.
source-git-commit: 40f144c7a06592c78dccc6c17f19554b62f667c9
workflow-type: tm+mt
source-wordcount: '1016'
ht-degree: 3%
---
# Agente de gestión de datos

>[!AVAILABILITY]
>
>El agente de gestión de datos está disponible para todos los clientes con acceso a Adobe CX Enterprise Coworker.

Para comprender y administrar la retención del lago de datos para los conjuntos de datos de Evento de experiencia, utilice el Agente de administración de datos en CX Coworker. A medida que los conjuntos de datos de Experience Event en su lago de datos de Adobe Experience Platform aumentan, las consultas y los procesos descendentes pueden tardar más en completarse, mientras que los requisitos de retención se tornan más difíciles de administrar. Describa lo que desea lograr en lenguaje natural. El agente de administración de datos encuentra los conjuntos de datos de evento de experiencia relevantes, analiza su uso y modela la cantidad de datos que afectaría un período de retención propuesto. Cuando esté listo para actuar, le ayudará a establecer, cambiar o quitar una directiva de retención y le pedirá confirmación antes de que cambie algo.

## Qué puede hacer el agente de gestión de datos {#what-the-data-management-agent-can-do}

El agente de gestión de datos ofrece cuatro aptitudes.

>[!NOTE]
>
>Los conjuntos de datos List, Analizar el uso de los conjuntos de datos y Analizar las habilidades de retención de conjuntos de datos son de solo lectura. Solo la aptitud Administrar retención de conjuntos de datos puede cambiar una política de retención de lago de datos y requiere su confirmación explícita antes de aplicar cualquier cambio.

| Habilidad | Descripción |
|---|---|
| **Enumerar conjuntos de datos** | Se utiliza para decidir dónde iniciar una revisión de retención. Enumera los conjuntos de datos de evento de experiencia con el tamaño de almacenamiento, el recuento de filas, la configuración de retención existente y la habilitación de perfiles para que pueda identificar rápidamente los conjuntos de datos que pueden ser candidatos para una política de retención de lago de datos |
| **Analizar el uso del conjunto de datos** | Utilícelo antes de decidir si un conjunto de datos es un buen candidato para una política de retención de lago de datos. Clasifica la actividad con la que se utiliza un conjunto de datos específico en función de señales como la ingesta reciente, la actividad de consulta y el uso de aplicaciones descendentes. |
| **Analizar retención de conjuntos de datos** | Utilícelo antes de comprometerse con un periodo de retención. Muestra las métricas de almacenamiento de un conjunto de datos y la edad de sus datos; a continuación, utiliza esa distribución de edad para aproximarse a la cantidad de datos que conservaría o eliminaría un periodo de retención potencial. |
| **Administrar retención de conjuntos de datos** | Úsalo cuando estés listo para actuar. Establece, cambia o quita una política de retención de lago de datos en un conjunto de datos, con una vista previa de impacto y confirmación antes de que nada cambie. |

## Ámbito: retención del lago de datos frente a otras herramientas de administración de datos {#scope}

Utilice Data Management Agent cuando necesite buscar y analizar conjuntos de datos de Experience Event y establecer, cambiar o quitar una política de retención de lago de datos.

Si no está seguro de si una política de retención de lago de datos es la opción correcta para su objetivo, consulte [Elija la capacidad de administración del ciclo de vida de datos correcta](https://experienceleague.adobe.com/en/docs/experience-platform/data-lifecycle/choose-a-capability) para comparar las opciones de retención y eliminación disponibles.

Estas habilidades no administran las siguientes capacidades relacionadas:

- **Directiva de retención de almacén de perfiles.** Para administrar cuánto tiempo permanecen los eventos de experiencia en el almacén de perfiles, configure una directiva de caducidad de evento de experiencia en conjuntos de datos de evento de experiencia con perfil habilitado. Ver [caducidad del evento de experiencia](https://experienceleague.adobe.com/es/docs/experience-platform/profile/event-expirations).
- **Caducidad de datos de perfil seudónimos en toda la zona protegida.** Para eliminar automáticamente los datos de perfil seudónimos en una zona protegida cuando cumplan las condiciones configuradas, consulte [Perfiles seudónimos](https://experienceleague.adobe.com/es/docs/experience-platform/profile/pseudonymous-profiles).
- **Caducidad del conjunto de datos.** Para programar la eliminación de un conjunto de datos completo en una fecha futura, consulte [Caducidad del conjunto de datos](https://experienceleague.adobe.com/en/docs/experience-platform/data-lifecycle/ui/dataset-expiration).
- **Eliminación de registro.** Para quitar registros de perfiles individuales por motivos de privacidad o higiene, consulte [Eliminar registro](https://experienceleague.adobe.com/en/docs/experience-platform/data-lifecycle/ui/record-delete).

## Requisitos previos {#prerequisites}

Antes de empezar, asegúrese de que dispone de lo siguiente:

- Acceso a Adobe Experience Platform y a la zona protegida que contiene los conjuntos de datos que desea revisar.
- Los permisos de Adobe Experience Platform necesarios para los conjuntos de datos y las acciones de retención que desea utilizar. El agente de gestión de datos utiliza los permisos de Experience Platform existentes y no concede acceso adicional. Consulte la [Información general sobre el control de acceso](https://experienceleague.adobe.com/es/docs/experience-platform/access-control/home) para ver cómo funcionan los permisos y las funciones de Adobe Experience Platform.
- El complemento CXO de Adobe instalado en CX Coworker.

Para obtener instrucciones sobre la instalación de complementos, consulte la [guía de la interfaz de usuario de Coworker](https://experienceleague.adobe.com/en/docs/cx-enterprise-ai/experience-cloud-ai/coworker/chat/ui-guide).

## Uso del agente de gestión de datos {#use-the-data-management-agent}

Interactúe con el agente de gestión de datos a través de CX Coworker utilizando un lenguaje natural. Describa su objetivo y luego perfeccione los resultados con preguntas de seguimiento.

>[!NOTE]
>
>Antes de empezar, asegúrese de que está trabajando en el entorno limitado que contiene los conjuntos de datos que desea revisar.

Para utilizar el agente de gestión de datos:

1. Vaya a **[!UICONTROL CX Coworker]**. Para obtener más información, consulte la [Guía de la interfaz de usuario de Coworker](https://experienceleague.adobe.com/en/docs/cx-enterprise-ai/experience-cloud-ai/coworker/chat/ui-guide).
1. Introduzca una solicitud que describa lo que desea lograr.
1. Revise los resultados y utilice preguntas de seguimiento para continuar con la investigación.

Si una solicitud cambia una política de retención de lago de datos, el agente de gestión de datos muestra el impacto propuesto y requiere su confirmación antes de aplicar el cambio.

Para obtener un flujo de trabajo completo que identifique conjuntos de datos, analice el uso y el impacto de la retención y administre las políticas de retención del lago de datos, consulte [Administrar la retención del lago de datos](../coworker/chat/use-cases/data-management/manage-data-lake-retention.md).

## Funcionamiento del agente de gestión de datos {#how-the-data-management-agent-works}

El agente de administración de datos utiliza cálculos determinísticos para analizar el uso del conjunto de datos, por lo que las mismas entradas producen el mismo nivel de uso. También calcula el impacto de la retención mediante programación en lugar de depender de estimaciones generadas por IA. El impacto en la retención sigue siendo una aproximación porque se basa en la distribución por edad de los datos. El agente recupera datos directamente desde los servicios de Adobe Experience Platform para proporcionar información actual sobre los conjuntos de datos.

## Limitaciones {#limitations}

El agente de administración de datos puede identificar conjuntos de datos que pueden ser buenos candidatos para una política de retención de lago de datos, pero no decide si un conjunto de datos lo requiere. No se aplica, cambia ni elimina una directiva de retención sin su confirmación explícita.

## Próximos pasos {#next-steps}

Para obtener instrucciones sobre cómo usar cada aptitud para buscar, analizar y administrar la retención de lago de datos en los conjuntos de datos de Experience Event, consulte [Administrar la retención de lago de datos](../coworker/chat/use-cases/data-management/manage-data-lake-retention.md).

Para obtener más información sobre cómo funcionan las políticas de retención de lago de datos en Adobe Experience Platform, incluido el comportamiento de retención y la configuración, consulte la [guía de retención de conjuntos de datos de evento de experiencia (TTL)](https://experienceleague.adobe.com/en/docs/experience-platform/catalog/datasets/experience-event-dataset-retention-ttl-guide).
