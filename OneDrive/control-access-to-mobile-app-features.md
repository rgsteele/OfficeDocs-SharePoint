---
title: "Control access to features in the OneDrive and SharePoint mobile apps"
ms.reviewer: 
ms.author: kaarins
author: kaarins
manager: serdars
ms.date: 06/25/2018
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: one-drive
localization_priority: Normal
ms.collection: 
- Strat_OD_admin
- M365-collaboration
search.appverid:
- ODB160
- ODB150
- MET150
ms.assetid: d25713bb-5cf8-4874-9b5b-e8bee3b94f13
ms.custom: seo-marvel-apr2020
description: "Learn how to create a mobile application management policy for the OneDrive and SharePoint mobile apps in the OneDrive admin center. "
---

# Control access to features in the OneDrive and SharePoint mobile apps

If your organization has **Microsoft Intune** or **Enterprise Mobility + Security**, you can use the OneDrive admin center to create a global policy that manages the OneDrive and SharePoint mobile apps for Android and iOS. This policy only applies to users in your organization who are licensed for Microsoft Intune or Enterprise Mobility + Security.
  
 > [!NOTE]
 > Your admin account needs to have an Intune license assigned to it for you to change the mobile application management settings in the OneDrive admin center. 

 > [!NOTE]
 > Disabling a policy won't remove it from Intune.
  
Go to the Device access page of the [OneDrive admin center](https://admin.onedrive.com) to:
  
- Block downloading files in the apps.
    
- Block taking screenshots in the Android apps.
    
- Block copying files and content within files.
    
- Block printing files in the apps.
    
- Block backing up app data.
    
- Require an app passcode.
    
- Block opening OneDrive and SharePoint files in other apps.
    
- Encrypt app data when the device is locked.

- Require Microsoft 365 sign-in each time the app is opened.
    
- Choose values for how often to verify user access and when to wipe app data when a device is offline.
    
 **To manage features in the OneDrive and SharePoint mobile apps**
  
1. In the **Mobile application management** section, turn on the **Deploy this policy** setting. 
    
    ![Manage the OneDrive and SharePoint mobile apps in the OneDrive admin center](media/7a555916-f97a-45f7-874b-ebd08de7022d.png)
  
2. Select the check boxes for the features you want to enable.
    
3. Choose values for how often to verify user access and when to wipe app data when a device is offline.
    
4. Click **Save**.
    
## Related topics

[Intune Documentation](/mem/intune/)
  
[How to create and assign app protection policies](/mem/intune/apps/app-protection-policies)
  
[Control access based on network location or app](control-access-based-on-network-location-or-app.md)
