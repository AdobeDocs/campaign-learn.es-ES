---
title: Panel de control de Campaign de Solución de problemas
description: Obtenga información sobre cómo solucionar problemas de Panel de control de Campaign
feature: Panel de control de Campaign
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: 4fc34f56e13c3df5f1c42c24c87a6c7c5caff04b
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 19%

---

# Solución de problemas [!UICONTROL Panel de control de Campaign]

Obtenga información sobre cómo solucionar problemas de Panel de control de Campaign.

## Inicio de sesión y página principal

### Síntoma: No se puede iniciar sesión en el Experience Cloud

**Qué hacer:**
El usuario debe localizar su ID de organización de IMS (xxx). El administrador debe agregar el usuario al Perfil de producto &quot;Campaign-xxx-administradores&quot; para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: Los vínculos de la página de inicio del Experience Cloud para acceder al [!UICONTROL Panel de control de Campaign] no aparecen para un usuario

**Causa:**
los usuarios no ven los vínculos hasta que se añaden como usuarios al Perfil de producto  _Campaign-xxx-Administradores/Admin_.

**Qué hacer:**
El administrador debe agregar el usuario al Perfil de productos  _Campaign-xxx-_  Administradores para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como usuario.

### Síntoma: Una instancia no aparece en el [!UICONTROL Panel de control de Campaign]

**Causa:**
es muy probable que el usuario deba agregarse como  ** usuarioProduct Profile  _Campaign-xxx-Administradores/_ Administrador para la instancia que falta

**Qué hacer:**
El administrador debe agregar el usuario al Perfil de productos  _Campaign-xxx-_  Administradores para cada instancia que desee administrar. Si el usuario es administrador de todas las instancias, debe añadirse como &quot;usuario&quot;.

### Vídeos útiles

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Comprobación del identificador de organización de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Cómo añadir un administrador a los administradores de perfil de producto para poder utilizar el  [!UICONTROL Panel de control]  (1:03 min)*

### Documentación útil

* [Descubra el panel de control de Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=es)
* [Administración de permisos del  [!UICONTROL Panel de control de Campaign]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Establecimiento de la conexión con el servidor SFTP (cliente o API)

La conexión a los servidores SFTP requiere lo siguiente:

* [!UICONTROL Permitir ] listar la dirección IP desde la que se está conectando al servidor SFTP
* Par de clave pública/privada que debe registrarse con Adobe Campaign
* Para conectarse directamente al servidor SFTP, también necesita el software de cliente SFTP

### Documentación útil {#helpful-docs}

* [Inicio de sesión en el servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
