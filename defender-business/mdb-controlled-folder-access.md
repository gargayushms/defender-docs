---
title: Set up or edit your controlled folder access policy in Microsoft Defender for Business           
description: Get an overview of attack surface reduction capabilities in Microsoft Defender for Business            
author: siosulli
ms.author: siosulli
manager: deniseb 
ms.date: 08/21/2023
ms.topic: conceptual
ms.service: defender-business
ms.localizationpriority: medium 
ms.collection: 
- m365-security
- tier1
ms.reviewer: efratka 
search.appverid: MET150
f1.keywords: NOCSH 
audience: Admin
---

# Set up or edit your controlled folder access policy in Microsoft Defender for Business

Controlled folder access allows only trusted apps to access protected folders on Windows devices. Think of this capability as ransomware mitigation. You can set up or edit your controlled folder access policy using Microsoft Intune. 

## Set up controlled folder access

1. As a global administrator, in the [Microsoft Intune admin center](https://go.microsoft.com/fwlink/?linkid=2109431), go to **Endpoint security** > **Attack surface reduction**.

2. Select an existing policy, or choose **Create policy** to create a new policy.

   - For **Platform**, choose **Windows 10 and later**.
   - For Profile, select **Attack Surface Reduction Rules**, and then choose **Create**.

3. Set up your policy as follows:

   1. Specify a name and description, and then choose **Next**.
   
   2. Scroll down, and set **Enable Controlled Folder Access** to **Enabled**. Then choose **Next**.

   3. On the **Scope tags** step, choose **Next**.

   4. On the **Assignments** step, choose the users or devices to receive the rules, and then choose **Next**. (We recommend selecting **Add all devices**.)

   5. On the **Review + create** step, review the information, and then choose **Create**.

To learn more about controlled folder access, see [Protect important folders with controlled folder access](/defender-endpoint/controlled-folders).

## Next steps

- [Enable your attack surface reduction rules](mdb-asr.md)
- [Review settings for advanced features and the Microsoft Defender portal](mdb-portal-advanced-feature-settings.md).

