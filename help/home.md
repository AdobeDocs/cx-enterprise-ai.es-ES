---
title: IA en aplicaciones de CX Enterprise
description: Descubra cómo las aplicaciones de CX Enterprise utilizan IA generativa (GenAI), AI Assistant, IA auténtica, CX Enterprise Coworker y herramientas MCP.
TQID: https://experienceleague.adobe.com/heALjEZbowNaygG24oOM2HSlHa9oYVI5ViUNZDr19Ds
product_v2:
  - id: d0a3eab4-7b10-4d96-a71e-6c0f8e7b7c87
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
topic_v2:
  - id: c1579802-ddd4-4214-8a91-97b2066abe11
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
source-git-commit: ca4515cb9010fb352489700108bbfe95396b0ad3
workflow-type: tm+mt
source-wordcount: 864
ht-degree: 3%

---

# IA en CX Enterprise

Esta guía cubre las funciones de IA en Adobe CX Enterprise: IA generativa, AI Assistant, Agent Orchestrator, agentes de Experience Platform, compañeros de CX Enterprise y MCP.

## Resumen de capacidades de IA

Comience aquí para obtener una guía sobre dónde y cómo se utiliza la IA en CX Enterprise:

- [IA generativa](./overview/generative-ai.md) describe qué aplicaciones de CX Enterprise admiten IA generativa y el Asistente de IA, y cómo se comparan.
- [Inteligencia artificial aplicada a agentes](./overview/agentic-ai.md) explica cómo funcionan los agentes de Experience Platform tanto en las aplicaciones empresariales de CX existentes como en las aplicaciones de IA-First, y enumera los agentes disponibles en cada una de ellas.
- [Supervisión de IA del agente](./overview/monitoring.md) cubre los paneles que hacen un seguimiento de la adopción del agente, el uso, los comentarios y el consumo de crédito de IA.
- [Trabajos de agente y consumo de crédito de IA](./overview/ai-credit-consumption.md) explica cómo los trabajos de agente consumen créditos de IA, con tasas de consumo estimadas por agente y tipo de trabajo.
- [Las herramientas agénticas de CX Enterprise](https://experienceleague.adobe.com/es/docs/cx-enterprise-agentic-tools/using/overview) cubren habilidades y herramientas agénticas adicionales que amplían los agentes de CX Enterprise (tutoriales en vídeo).

## Asistente de IA

[Asistente de IA](./ai-assistant/ai-assistant-ui.md) es una herramienta conversacional y generativa de IA disponible en aplicaciones basadas en Adobe Experience Platform. Utilícelo para obtener información sobre el producto, solucionar problemas, encontrar perspectivas operativas y acceder a los agentes de Experience Platform, todo ello a través de indicaciones en lenguaje natural en una interfaz de pantalla completa o de vista de carril.

Para aprender a navegar por la interfaz, lea la [guía de la interfaz de usuario del Asistente de IA](./ai-assistant/ai-assistant-ui.md). Para ver las indicaciones de ejemplo del agente, consulte la [biblioteca de indicaciones](./ai-assistant/prompt-library.md).

## Agentes de Agent Orchestrator y Experience Platform

[Agent Orchestrator](./agents/agent-orchestrator.md) es la capa agéntica que alimenta a los agentes de Experience Platform. Cuando hace una pregunta a AI Assistant, Agent Orchestrator planifica el trabajo, llama a los agentes especializados necesarios para responderlo y devuelve una respuesta unificada, todo con supervisión humana.

Los siguientes agentes de Experience Platform están documentados en esta guía:

- [Audience Agent](./agents/audience.md)
- [Data Insights Agent](./agents/cja-data-insights-agent.md)
- [Experimentation Agent](./agents/agent-experiment.md)
- [Agente de detección de campos](./agents/field-discovery-agent.md)
- [Journey Agent](./agents/ajo-agent.md)
- [Agente de notificaciones](./agents/notifications.md)
- [Agente de soporte del producto](./agents/product-support.md)
- [Adobe Marketing Agent for Microsoft 365 Copilot](./agents/ama-ms.md)
- [Validación de los datos](./agents/data-validation.md)

Para obtener la lista completa de agentes, las aplicaciones compatibles y los requisitos de idoneidad, consulte [Inteligencia artificial aplicada a la agencia en CX Enterprise](./overview/agentic-ai.md).

## Compañero

Coworker es una evolución del asistente de IA que da prioridad al agente y automatiza la experiencia del cliente y los flujos de trabajo de marketing para que su equipo pueda centrarse en los objetivos comerciales en lugar de en la ejecución rutinaria. En lugar de hacer una pregunta a la vez, se describe un objetivo. El compañero planifica, ejecuta, valida y devuelve el trabajo terminado para su aprobación. El compañero incluye:

- **[Chat del compañero](https://experienceleague.adobe.com/es/docs/cx-enterprise-ai/experience-cloud-ai/coworker/chat/overview)**: Una interfaz conversacional para explorar los datos, validar audiencias y recorridos y completar tareas de varios pasos en las aplicaciones de CX Enterprise.
- **[Campañas de compañeros de trabajo](https://experienceleague.adobe.com/es/docs/cx-enterprise-ai/experience-cloud-ai/coworker/campaigns/overview)**: una aplicación nativa de IA que consolida la información de la campaña, la creación de audiencias, la generación de contenido, el diseño de recorridos y la revisión en una sola experiencia de conversación. Utiliza plantillas integradas, prácticas recomendadas y sugerencias para ayudar a equipos pequeños y ágiles a iniciar campañas rápidamente.
- **Proyectos de compañeros** (próximamente): Un espacio de trabajo unificado para automatizar los flujos de trabajo de la orquestación de la experiencia del cliente de extremo a extremo, lo que ayuda a los equipos a coordinar tareas, aprobaciones y ejecuciones para dirigir los resultados desde la estrategia hasta la entrega. La documentación de los proyectos estará disponible próximamente.

Los clientes aptos se están trasladando gradualmente del asistente de IA y los agentes de Experience Platform al chat con el compañero. Lea la [Prueba para colaboradores](./agents/trial.md) para obtener información sobre la elegibilidad del periodo de prueba, el uso del crédito de IA y cómo obtener acceso.

Para ver el chat de compañeros en acción, visita [Chat de compañeros en el patio](./coworker/playground-coworker-chat.md) o lee casos de uso reales como [Validar datos de migración de AA a CJA](./coworker/data-validation-aa-cja.md) y [Analizar datos de CJA](./coworker/chat/analytics-chat.md).

Para obtener documentación completa del producto sobre Chat, campañas y proyectos de compañeros de trabajo, consulta [Colaborador](./coworker/overview.md). Para la replicación de objetos de espacio aislado a espacio aislado, consulte [Aptitudes de agente de herramientas de espacio aislado](./agents/sandbox-tooling.md).

## MCP

[Adobe CX Coworker Gateway](./mcp/overview.md) es el punto final del Protocolo de contexto de modelo (MCP) unificado para CX Enterprise. Proporciona a los clientes compatibles con MCP, como [!DNL Claude], [!DNL ChatGPT] y [!DNL Cursor], una única conexión controlada a las herramientas de producto que puede utilizar su organización. Estas herramientas incluyen [!DNL Real-Time CDP], [!DNL Experience Platform], [!DNL Journey Optimizer], [!DNL Customer Journey Analytics], [!DNL Adobe Analytics] y [!DNL Workfront].

¿Es nuevo en CX Coworker Gateway? Consulte [Acceder a las herramientas de CX Coworker Gateway](./mcp/access.md) e [Instalar CX Coworker Gateway](./mcp/install.md) para conectarse.

## Introducción

### Requisitos de acceso

El administrador de Adobe debe conceder los permisos adecuados para poder utilizar el asistente de IA y los agentes de Experience Platform. Los requisitos varían según la aplicación; consulte [Acceso](./agents/agent-orchestrator.md#access) en la guía de Agent Orchestrator para obtener detalles.

### Privacidad y seguridad

El asistente de IA y los agentes de Experience Platform dan prioridad a la privacidad, la seguridad y la gobernanza, incluido el aislamiento de datos específico de la zona protegida y las políticas de control de acceso existentes. Para obtener información detallada, lee [Privacidad, seguridad y administración en el asistente de IA](./ai-assistant/privacy.md).

## Prácticas recomendadas

Para obtener el máximo valor de su experiencia de asistente de IA o compañero de trabajo, siga estas prácticas recomendadas:

- **Sea específico** en sus indicaciones para obtener información relevante y de destino.
- **Verifique las respuestas** revisando las citas de origen y las explicaciones de razonamiento proporcionadas.
- **Use la configuración de contexto** para asegurarse de que se usan las fuentes de datos más relevantes para sus preguntas.
- **Proporcione comentarios** para ayudar a mejorar el rendimiento y la precisión con el tiempo.
- **Combine datos** de varios agentes para obtener un análisis más completo.

## Consideraciones legales

Actualmente, el asistente de IA solo admite respuestas en inglés, y los modelos de idioma a veces cometen errores. Compruebe siempre la información proporcionada y siga los pasos de razonamiento incluidos en cada respuesta para comprender cómo se generó. Para obtener información detallada, lea la [exención de responsabilidad legal](./ai-assistant/legal-disclaimer.md).

