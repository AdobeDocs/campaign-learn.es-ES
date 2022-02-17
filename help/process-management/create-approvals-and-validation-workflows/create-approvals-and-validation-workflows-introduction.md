---
title: 'Creación de aprobaciones y flujos de trabajo de validación: introducción'
description: Obtenga información sobre cómo configurar diferentes flujos de trabajo de validación de aprobación.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: ca13bdbd7d95e6646aff88af595e866bd3666bb2
workflow-type: ht
source-wordcount: '262'
ht-degree: 100%

---

# Creación de aprobaciones y flujos de trabajo de validación: introducción

Adobe Campaign ofrece varias opciones para que los especialistas en marketing puedan revisar y proporcionar contenido de entrega, objetivos de campaña, extracción de datos y aprobaciones de presupuesto. Obtenga información sobre cómo [administrar las aprobaciones](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Requisito previo {#prerequisite}

Antes de activar los pasos de aprobación, el equipo de marketing debe definir revisores individuales:

* La función de revisor de Adobe Campaign dentro de una actividad de aprobación puede ser un solo revisor (Operador) o un grupo de revisores (función de operador).
* Para permitir que los desarrolladores de campañas seleccionen a los revisores como aprobadores en una campaña o envío, un administrador debe configurar los grupos de revisores y revisores en Adobe Campaign.

## Configuración de aprobaciones {#configuring-approvals}

1. [Configure aprobaciones para las campañas](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md): si tiene el mismo conjunto de revisores para todas las entregas en el flujo de trabajo de la campaña, aplique la funcionalidad de aprobación de la campaña configurando las aprobaciones y los revisores en el nivel de campaña. Las tareas de aprobación y los revisores se envían a cada actividad de entrega del flujo de trabajo una vez que este se ejecuta.
2. [Configure aprobaciones para las entregas](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md):
también puede configurar aprobaciones en el nivel de entrega. Si los pasos y revisores de las aprobaciones de entrega difieren de los pasos y revisores de aprobación de la campaña, la configuración de entrega anula la configuración de la campaña.
3. [Cree un proceso de aprobación en un flujo de trabajo](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md):
la actividad de aprobación permite crear un proceso de aprobación dentro de un flujo de trabajo. De este modo, la lógica de selección de objetivos se puede aprobar antes de iniciar el envío. También permite la aprobación en varios niveles dentro del flujo de trabajo si es necesario.

Para obtener más información, consulte la [documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=es).
