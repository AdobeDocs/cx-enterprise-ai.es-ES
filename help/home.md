---
title: IA en aplicaciones de CX Enterprise
description: Descubra cómo las aplicaciones de CX Enterprise utilizan las herramientas de IA generativa (GenAI), CX Enterprise Coworker, AI Assistant, IA auténtica y MCP.
TQID: 'https://experienceleague.adobe.com/heALjEZbowNaygG24oOM2HSlHa9oYVI5ViUNZDr19Ds'
product_v2:
  - id: fdae8433-07cd-42e7-acce-738afe63f6bb
    internal-label: CX Enterprise Coworker
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
    internal-label: Leader
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
topic_v2:
  - id: c1579802-ddd4-4214-8a91-97b2066abe11
    internal-label: Troubleshooting
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
    internal-label: Governance
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
source-git-commit: 5810a7f782eaca7c34dda14a1eea12b435329c38
workflow-type: tm+mt
source-wordcount: '809'
ht-degree: 4%
---
# IA en aplicaciones de CX Enterprise

Esta guía cubre las funciones de IA en Adobe CX Enterprise: IA generativa, CX Enterprise Coworker, AI Assistant y Agent Orchestrator.

## Resumen de capacidades de IA

Comience aquí para obtener una guía sobre dónde y cómo se utiliza la IA en CX Enterprise:

- [Coworker](https://experienceleague.adobe.com/es/docs/coworker/content/home) es un compañero que planea, ejecuta, valida y devuelve el trabajo de marketing y la experiencia del cliente finalizados para su aprobación.
- [Acerca de la IA generativa](./overview/generative-ai.md) describe qué aplicaciones de CX Enterprise admiten IA generativa y el Asistente de IA, y cómo se comparan.
- [Acerca de la IA auténtica](./overview/agentic-ai.md) explica cómo funciona la IA auténtica tanto en aplicaciones CX Enterprise existentes como en aplicaciones con prioridad de IA, y enumera los agentes disponibles en cada una de ellas.
- [Supervisión de IA](./overview/monitoring.md) cubre los paneles que hacen un seguimiento de la adopción de los agentes, el uso, los comentarios y el consumo de crédito de IA.
- [Consumo de créditos de IA](./overview/ai-credit-consumption.md) explica cómo los trabajos del agente consumen créditos de IA, con tasas de consumo estimadas por agente y tipo de trabajo.
- [Transparencia del contenido de IA generativa](./content-transparency.md) explica cómo Adobe adjunta automáticamente los metadatos de C2PA al contenido generado y editado por GenAI en las aplicaciones de CX Enterprise.
- [Las herramientas agénticas de CX Enterprise](https://experienceleague.adobe.com/es/docs/cx-enterprise-agentic-tools/using/overview) cubren habilidades y herramientas agénticas adicionales que amplían los agentes de CX Enterprise (tutoriales en vídeo).

## Coworker

Coworker es una evolución del asistente de IA que da prioridad al agente y automatiza la experiencia del cliente y los flujos de trabajo de marketing para que su equipo pueda centrarse en los objetivos comerciales en lugar de en la ejecución rutinaria. En lugar de hacer una pregunta a la vez, se describe un objetivo. El compañero planifica, ejecuta, valida y devuelve el trabajo terminado para su aprobación. Más información sobre [Adobe for Business](https://business.adobe.com/products/cx-enterprise-coworker.html).

El compañero incluye:

- **[Chat del compañero](https://experienceleague.adobe.com/en/docs/coworker/content/chat/overview)**: Una interfaz conversacional para explorar tus datos, validar audiencias y recorridos y completar tareas de varios pasos en aplicaciones de CX Enterprise.
- **[Campañas de compañeros de trabajo](https://experienceleague.adobe.com/en/docs/coworker/content/campaigns/overview)**: una aplicación nativa de IA que consolida la información de la campaña, la creación de audiencias, la generación de contenido, el diseño de recorridos y la revisión en una sola experiencia de conversación. Utiliza plantillas integradas, prácticas recomendadas y sugerencias para ayudar a equipos pequeños y ágiles a iniciar campañas rápidamente. Más información sobre [Adobe for Business](https://business.adobe.com/products/cx-enterprise-coworker/teams.html).
- **Proyectos de compañeros** (próximamente): Un espacio de trabajo unificado para automatizar los flujos de trabajo de la orquestación de la experiencia del cliente de extremo a extremo, lo que ayuda a los equipos a coordinar tareas, aprobaciones y ejecuciones para dirigir los resultados desde la estrategia hasta la entrega. La documentación de los proyectos estará disponible próximamente.

Los clientes aptos se están trasladando gradualmente del asistente de IA y los agentes de Experience Platform al chat con el compañero.

### Recursos de compañeros

- Lea [Prueba de compañeros de trabajo](./agents/trial.md) para obtener información sobre la elegibilidad del periodo de prueba, el uso del crédito de IA y cómo obtener acceso.
- Ver [Página principal de ayuda de Coworker](https://experienceleague.adobe.com/es/docs/coworker/content/home) para obtener todo el contenido de Coworker.
- Para la replicación de objetos de espacio aislado a espacio aislado, consulte [Aptitudes de agente de herramientas de espacio aislado](https://experienceleague.adobe.com/en/docs/coworker/content/chat/use-cases/sandbox-tooling/sandbox-tooling).

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

<!--
## MCP

[Adobe CX Coworker Gateway](./mcp/overview.md) is the unified Model Context Protocol (MCP) endpoint for CX Enterprise. It gives MCP-compatible clients, such as [!DNL Claude], [!DNL ChatGPT], and [!DNL Cursor], a single governed connection to the product tools your organization is entitled to use:

- [Real-Time CDP tools](./mcp/rtcdp-mcp.md)
- [Experience Platform tools](./mcp/aep-mcp.md)
- [Journey Optimizer tools](./mcp/ajo-mcp.md)
- [Customer Journey Analytics tools](./mcp/cja-mcp.md)
- [Adobe Analytics tools](./mcp/analytics-mcp.md)
- [!DNL Workfront] tools, documented in the [Workfront MCP server guide](https://experienceleague.adobe.com/en/docs/workfront/using/basics/workfront-mcp-server/workfront-mcp-server-overview)
- [!DNL Target] tools, documented in the [Target MCP server guide](https://experienceleague.adobe.com/en/docs/target/using/mcp/target-mcp)

New to CX Coworker Gateway? See [Access CX Coworker Gateway tools](./mcp/access.md) and [Install CX Coworker Gateway](./mcp/install.md) to get connected. Once connected, use the [session context tools](./mcp/context-tools.md) to set the active organization, sandbox, and data view before calling product tools.

Before you use any of these tools, see [Before you begin](./overview/overview-ai-cxe.md#before-you-begin) for access requirements and privacy and security considerations.
-->

## Prácticas recomendadas

Para obtener el máximo valor de su experiencia de asistente de IA o compañero de trabajo, siga estas prácticas recomendadas:

- **Sea específico** en sus indicaciones para obtener información relevante y de destino.
- **Verifique las respuestas** revisando las citas de origen y las explicaciones de razonamiento proporcionadas.
- **Use la configuración de contexto** para asegurarse de que se usan las fuentes de datos más relevantes para sus preguntas.
- **Proporcione comentarios** para ayudar a mejorar el rendimiento y la precisión con el tiempo.
- **Combine datos** de varios agentes para obtener un análisis más completo.

## Consideraciones legales

Actualmente, el asistente de IA solo admite respuestas en inglés, y los modelos de idioma a veces cometen errores. Compruebe siempre la información proporcionada y siga los pasos de razonamiento incluidos en cada respuesta para comprender cómo se generó. Para obtener información detallada, lea la [exención de responsabilidad legal](./ai-assistant/legal-disclaimer.md).

Adobe también adjunta automáticamente metadatos de C2PA al contenido generado por GenAI y editado por GenAI en todas las aplicaciones de CX Enterprise, para cumplir con las regulaciones de transparencia generativas de IA. Para obtener más información, lea [Transparencia del contenido de IA generativa](./content-transparency.md).

