---
title: Configuración de campañas de correo electrónico recurrentes y continuas
description: Aprenda a configurar un envío recurrente y continuo y comprenda las diferencias entre los dos enfoques.
feature: Flujos de trabajo
kt: 7982
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
source-git-commit: 7609aa35dba225a05c8f5e3d3f75f4b6023772a0
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 21%

---


# Configuración de campañas de correo electrónico recurrentes y continuas

Este tutorial explica cómo configurar un envío recurrente y continuo y las diferencias entre los dos enfoques.

## Seguimiento de envío recurrente y continuo {#recurring-and-continuous-delivery-tracking}

Los envíos recurrentes y continuos difieren en la forma en que se administran los datos de contacto:

* El **envío continuo** permite añadir nuevos destinatarios a un envío existente, lo que evita tener que crear un envío cada vez que se añade un nuevo destinatario. Puede actualizar el elemento creativo directamente en el flujo de trabajo de la campaña y así actualizar la plantilla en la carpeta de recursos de la plantilla de envío.

   Un envío continuo crea un envío ÚNICO y registros de envío (broadLog) y registros de seguimiento, que hacen referencia a que se agrega un envío cada vez que se ejecuta.

![Entrega continua](/help/assets/delivery_continuous.jpg)

* Un **envío recurrente** crea una instancia de envío cada vez que se ejecuta. Por ejemplo, si el flujo de trabajo está programado para ejecutarse una vez a la semana, el resultado sería de 52 envíos al cabo de un año. También significa que el registro amplio y los registros de seguimiento están separados por una instancia de envío.

![Entrega recurrente](/help/assets/delivery_recurring.jpg)

## Configuración de un envío recurrente {#how-to-set-up-a-recurring-delivery}

En el vídeo se explica cómo configurar un envío recurrente y una actividad de planificador.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Configuración de envíos continuos {#how-to-set-up-a-continuous-delivery}

Este vídeo muestra cómo configurar un envío continuo con una consulta incremental.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)
