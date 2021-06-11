---
title: Introducción a las notificaciones push para Android
description: Este tutorial le guía por los pasos necesarios para enviar notificaciones push desde Adobe Campaign y recibir estas notificaciones en la aplicación de Android™.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: ht
source-wordcount: '318'
ht-degree: 100%

---

# Introducción a las notificaciones push para Android, presentación

Adobe Campaign permite enviar notificaciones [!DNL push] personalizadas y segmentadas a dispositivos móviles [!DNL iOS] y [!DNL Android™]. En este tutorial, se explican los pasos necesarios para enviar notificaciones [!DNL push] de Adobe Campaign a una aplicación de [!DNL Android™].

## Requisitos previos

Antes de empezar, debe tener lo siguiente:

1) **Aplicación móvil de Android™**

   Este tutorial no cubre los pasos detallados necesarios para configurar la aplicación móvil. Debe tener una aplicación móvil **[!DNL Android™]con el [!DNL Campaign SDK] integrado**.

   Puede encontrar la descripción detallada de los pasos necesarios en la documentación del producto:

   [Integración del SDK de Campaign en la aplicación móvil](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=es)

2) El paquete **[!DNL Mobile App channel]instalado**

   El paquete [!DNL Mobile App channel] debe estar instalado en su instancia de [!DNL Campaign]. El siguiente vídeo explica cómo comprobar si [!DNL Mobile App channel] está instalado en la instancia y, en caso contrario, cómo instalarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Información general del tutorial

El objetivo es enviar una notificación [!DNL push] promocional personalizada a los suscriptores de la aplicación móvil [!DNL Neotrip] [!DNL Android™] La aplicación [!DNL Neotrip] se configura con [!DNL Campaign SDK] y [!DNL Mobile App channel] se activa en la instancia de [!DNL Campaign].

Se requieren los siguientes pasos para la configuración:

### Paso 1: Ampliar del esquema de suscripción de la aplicación para personalizar las notificaciones [!DNL push]

Para poder personalizar la notificación [!DNL push], primero debe [ampliar el esquema de suscripción de la aplicación](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). Esto permite al sistema almacenar los valores de personalización que se reciben de la aplicación cuando el usuario se suscribe al servicio.

### Paso 2: Configurar el servicio de Android™ y crear la aplicación móvil en Campaign

A continuación, [el servicio Android™ debe estar configurado y la aplicación móvil debe crearse en Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). En este paso, la aplicación [!DNL Neotrip] se define como el destino de la notificación push.

### Paso 3: Configurar y enviar la notificación push

Ahora la notificación push está lista para [configurarse y enviarse](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md).

## Inicio del tutorial

Paso 1: [Ampliar el esquema de suscripción de la aplicación](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
