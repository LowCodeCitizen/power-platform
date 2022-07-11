---
title: Sharing limits
description: Limit the number of canvas apps that can be shared in your managed environments.
ms.component: pa-admin
ms.topic: conceptual
ms.date: 07/07/2022
author: alaug 
ms.author: alaug
ms.reviewer: jimholtz
contributors:
  - mikferland-msft
  - alaug 
ms.subservice: admin
ms.custom: "admin-security"
search.audienceType: 
  - admin
search.app:
  - D365CE
  - PowerApps
  - Powerplatform
  - Flow
---
# Sharing limits

<!-- https://go.microsoft.com/fwlink/?linkid=2194484 -->

In managed environments, admins can limit how broadly makers can share canvas apps. There are two sharing controls.  

| Sharing control | System behavior when selected |
| --- | --- |
| **Exclude sharing with security groups** | Makers aren't allowed to share canvas apps with any security group. Admins may share with a limit on who an app can be shared with. |
| **Limit total individuals who can be shared to** | Makers aren't allowed to share canvas apps with more people than specified. |

**Limit total individuals who can be shared to** is available only if **Exclude sharing with security groups** is selected. This is because security groups may have unbounded membership. For instance, a maker might share an app with a security group that has 5 members one day and 500 members a month later.  

:::image type="content" source="media/managed-environment-limit-sharing.png" alt-text="Screenshot of an Edit Environment Management settings screen, with Limit sharing highlighted.":::

> [!NOTE]
> Sharing rules are enforced when makers try to share an app. Sharing rules don't change who an app has already been shared with.
>
> After sharing rules are set in the Power Platform admin center, it may take up to an hour for them to propagate and start being enforced.

### See also

[Managed Environments overview](managed-environment-overview.md)  
[Enable Managed Environment](managed-environment-enable.md)  
[Weekly digests](managed-environment-weekly-digests.md)  
[Data policies](managed-environment-data-policies.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]