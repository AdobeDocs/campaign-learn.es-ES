---
title: Solución de problemas del Panel de control de Campaign
description: Obtenga información sobre cómo solucionar problemas del Panel de control de Campaign
feature: Control Panel
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 0dca4676-2d5e-411b-9fdf-fbfd1081cb0e
source-git-commit: f7cb6c57d9cd6b00def9f0a4ccbcc94267f0d593
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 100%

---

# Solución de problemas del [!UICONTROL Panel de control de Campaign]

Obtenga información sobre cómo solucionar problemas del Panel de control de Campaign.

## Inicio de sesión y página de inicio

### Síntoma: no se puede iniciar sesión en Experience Cloud

**Qué hacer:**
el usuario debe localizar su identificador de organización de IMS (xxx). El administrador debe añadir el usuario al Perfil de productos “Campaign-xxx-Admins” para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: los vínculos de la página principal de Experience Cloud para acceder al [!UICONTROL Panel de control de Campaign] no aparecen para un usuario.

**Causa:**
Los usuarios no verán los vínculos hasta que se añadan como usuarios al Perfil de productos _Campaign-xxx-Administradores/Admin_.

**Qué hacer:**
el administrador debe añadir el usuario al Perfil de productos _Campaign-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: una instancia no aparece en la lista del [!UICONTROL Panel de control de Campaign]

**Causa:**
Es muy probable que el usuario deba añadirse como *usuario* al Perfil de productos _Campaign-xxx-Administradores/Admin_ para la instancia que falta.

**Qué hacer:**
el administrador debe añadir el usuario al Perfil de productos _Campaign-xxx-Admins_ para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como “usuario”.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Comprobación del identificador de organización de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Cómo añadir un administrador a los administradores de perfil de productos para poder utilizar el [!UICONTROL Panel de control de Campaign] (01:03 min)*

### Documentación útil

* [Descubra el panel de control de Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)
* [Administración de permisos en el [!UICONTROL Panel de control de Campaign]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere lo siguiente:

* [!UICONTROL Permite incluir en la lista de permitidos] la dirección IP desde la que se conecta al servidor SFTP
* Par de claves públicas/privadas que debe registrarse con Adobe Campaign
* Para conectarse directamente al servidor SFTP, también necesitará el software de cliente SFTP

### Documentación útil {#helpful-docs}

* [Inicio de sesión en el servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
