---
title: Creación de flujos de trabajo de validación - Introducción
description: Obtenga información sobre cómo configurar diferentes flujos de trabajo de validación de aprobación.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: f25e3e7553d23aacf96c0f05e1ad78ee783192ff
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 66%

---

# Creación de flujos de trabajo de validación: Introducción

Adobe Campaign ofrece varias opciones para que los especialistas en marketing puedan revisar y proporcionar contenido de envío, objetivo de campaña, extracción de datos y aprobaciones de presupuesto.

## Requisito previo {#prerequisite}

Antes de activar los pasos de aprobación, el equipo de marketing debe definir revisores individuales:

* La función de revisor de Adobe Campaign dentro de una actividad de aprobación puede ser un solo revisor (Operador) o un grupo de revisores (función de operador).
* Para permitir que los desarrolladores de campañas seleccionen a los revisores como aprobadores en una campaña o envío, un administrador debe configurar los grupos de revisores y revisores en Adobe Campaign.

## Configuración de aprobaciones {#configuring-approvals}

Campaign ofrece tres niveles diferentes para aprobaciones:

1. [Configuración de aprobaciones para campañas](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md): Si tiene el mismo conjunto de revisores para todas las entregas en el flujo de trabajo de la campaña, aplique la funcionalidad de aprobación de la campaña configurando las aprobaciones y los revisores en el nivel de campaña. Las tareas de aprobación y los revisores se envían a cada actividad de envío del flujo de trabajo una vez que se ejecuta el flujo de trabajo.
2. [Configuración de aprobaciones para entregas](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md): También puede configurar aprobaciones a nivel de envío. Si los pasos y revisores de las aprobaciones de envío difieren de los pasos y revisores de aprobación de campaña, la configuración de envío anula la configuración de la campaña.
3. [Creación de un proceso de aprobación en un flujo de trabajo](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md): La actividad de aprobación permite crear un proceso de aprobación dentro de un flujo de trabajo. De este modo, la lógica de selección de objetivos se puede aprobar antes de iniciar el envío. También permite la aprobación en varios niveles dentro del flujo de trabajo si es necesario.

Para obtener más información, consulte [documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=es).
