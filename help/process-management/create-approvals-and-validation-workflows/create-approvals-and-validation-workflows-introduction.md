---
title: 'Creación de aprobaciones y flujos de trabajo de validación: introducción'
description: Obtenga información sobre cómo configurar diferentes flujos de trabajo de validación de aprobación.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Intermediate
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
TQID: https://experienceleague.adobe.com/nVZT-SWtytNyXrkbV-J7LWhR5-KHo601s0dE9yUiOaY
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
feature_v2: id: a075b2c1-7748-4328-b7f6-343aa314616a
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: b5a62a22-46f7-4f0d-b151-3fc640bef588
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 267
ht-degree: 89%

---

# Creación de aprobaciones y flujos de trabajo de validación: introducción

Adobe Campaign ofrece varias opciones para que los especialistas en marketing puedan revisar y proporcionar contenido de entrega, objetivos de campaña, extracción de datos y aprobaciones de presupuesto. Obtenga información sobre cómo [administrar las aprobaciones](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Requisito previo {#prerequisite}

Antes de habilitar los pasos de aprobación, el equipo de marketing debe definir revisores individuales:

* La función de revisor de Adobe Campaign dentro de una actividad de aprobación puede ser un solo revisor (Operador) o un grupo de revisores (función de operador).
* Para permitir que los desarrolladores de campañas seleccionen a los revisores como aprobadores en una campaña o envío, un administrador debe configurar los grupos de revisores y revisores en Adobe Campaign.

## Configuración de aprobaciones {#configuring-approvals}

1. [Configurar aprobaciones para campañas](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md):
Si tiene el mismo conjunto de revisores para todas los envíos en el flujo de trabajo de la campaña, aplique la funcionalidad de aprobación de la campaña configurando las aprobaciones y los revisores en el nivel de campaña. Las tareas de aprobación y los revisores se envían a cada actividad de entrega del flujo de trabajo una vez que este se ejecuta.
2. [Configurar aprobaciones para entregas](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md):
También puede configurar aprobaciones en cuanto a envío. Si los pasos y revisores de las aprobaciones de entrega difieren de los pasos y revisores de aprobación de la campaña, la configuración de entrega anula la configuración de la campaña.
3. [Crear un proceso de aprobación en un flujo de trabajo](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md):
La actividad de aprobación permite crear un proceso de aprobación dentro de un flujo de trabajo. De este modo, la lógica de selección de objetivos se puede aprobar antes de iniciar el envío. También permite la aprobación en varios niveles dentro del flujo de trabajo si es necesario.

Para obtener más información, consulte la [documentación](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=es).
