---
title: 'Creación de un flujo de trabajo de exportación (parte 1): Búsqueda de la última fecha de modificación para una lista de destinatarios'
description: En esta primera parte del tutorial Creación de un flujo de trabajo de exportación, aprenda a crear un flujo de trabajo que encuentre la última fecha de modificación para una lista de destinatarios creados a partir de un segmento de Experience Platform.
feature: Data Management, Workflows
jira: KT-8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
TQID: https://experienceleague.adobe.com/0C-fRmXsfzB-1kePFSNtzUFtqPHDQ1wW1LH2-6Zuw5g
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 123
ht-degree: 100%

---

# Creación de un flujo de trabajo de exportación (parte 1): Búsqueda de la última fecha de modificación para una lista de destinatarios

En esta primera parte del tutorial Creación de un flujo de trabajo de exportación, aprenda a crear un flujo de trabajo que encuentre la última fecha de modificación para una lista de destinatarios creados a partir de un segmento de Experience Platform.

>[!VIDEO](https://video.tv.adobe.com/v/3450050?captions=spa&quality=12&learn=on){transcript=true}

## Recursos

JavaScript para establecer intervalos de fechas:

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## Vídeo siguiente

[Creación de un flujo de trabajo de exportación (parte 2): Extracción, formateo y guardado de datos en una cuenta externa](extract-format-save-data-to-external-account.md)
