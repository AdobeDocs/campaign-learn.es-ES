---
title: Creación de envíos recurrentes y continuos
description: Aprenda a configurar un envío recurrente y continuo, y comprenda las diferencias entre los dos enfoques.
feature: Workflows
kt: 7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 100%

---

# Creación de envíos recurrentes y continuos

Este tutorial explica cómo configurar un envío recurrente y continuo, y las diferencias entre los dos enfoques.

## Seguimiento de envío recurrente y continuo {#recurring-and-continuous-delivery-tracking}

Los envíos recurrentes y continuos difieren en la forma en que se administran los datos de contacto:

* Los **envíos continuos** le permiten añadir destinatarios nuevos a un envío existente, lo que evita tener que crear un envío nuevo cada vez que se añade un nuevo destinatario. Puede actualizar el elemento creativo directamente en el flujo de trabajo de campaña para que se actualice la plantilla en la carpeta recurso de plantilla de envíos.

   Un envío continuo creará un envío ÚNICO y registros de envío (broadLog) y registros de seguimiento que hacen referencia a que se agrega un envío cada vez que se ejecuta.

![Envío continuo](/help/assets/delivery_continuous.jpg)

* Un **envío recurrente** creará una nueva instancia de envío cada vez que se ejecute. Por ejemplo, si el flujo de trabajo está programado para ejecutarse una vez a la semana, el resultado sería de 52 envíos al cabo de un año. Esto también significa que el registro y los registros de seguimiento se separarán por cada instancia de envío.

![Envío recurrente](/help/assets/delivery_recurring.jpg)

## Configuración de un envío recurrente {#how-to-set-up-a-recurring-delivery}

En este vídeo se explica cómo configurar un envío recurrente y una actividad de planificador.

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on)

## Configuración de envíos continuos {#how-to-set-up-a-continuous-delivery}

Este vídeo muestra cómo configurar un envío continua con una consulta incremental.

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on)
