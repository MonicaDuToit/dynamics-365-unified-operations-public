---
# required metadata

title: What's new or changed in Dynamics 365 Talent (October 29, 2019)
description: This topic describes features that are either new or changed in Microsoft Dynamics 365 Talent for October 29, 2019.
author: andreabichsel
ms.date: 10/29/2019
ms.topic: article
ms.prod: 
ms.technology: 

# optional metadata

ms.search.form: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: 
ms.search.region: Global
# ms.search.industry: 
ms.author: anbichse
ms.search.validFrom: 2019-10-29
ms.dyn365.ops.version: Talent

---

# What's new or changed in Dynamics 365 Talent (October 29, 2019)



This topic describes features that are either new or changed in Dynamics 365 Talent.

## Changes in Attract

This release includes minor bug fixes for Dynamics 365 Talent: Attract.

## Changes in Onboard

This release includes minor bug fixes for Dynamics 365 Talent: Onboard.

## Changes in Core HR

Changes described in this section apply to build number 8.1.2586. The numbers in parentheses in some headings refer to support numbers in Microsoft Dynamics Lifecycle Services (LCS).

### Delete parties with no roles should be on by default (371233)

When you provision a new environment in Talent, **Delete parties if no roles exist** is on by default. When you delete a worker, the party associated with the worker isn't removed unless this setting is on. This change limits duplicate records in the global address book when you need to import, change, or reimport workers.

### Should be able to delete draft and canceled leave requests in Dataverse (376999)

With this change, you can delete leave requests with a status of **Draft** or **Canceled** in Dataverse.

### Additional list values in custom columns aren't reflected in Dataverse after clicking Apply on the Custom columns form (379599)

When you add new list values to an existing custom column already synchronized with Dataverse, they're now available in Dataverse after you apply your changes in the **Custom columns** form.

### Apply onboarding checklists across legal entities when more than one employment exists (371270)

In this week's release, you can apply checklists to employees with more than one employment in **Worker form > Checklists**.

### Benefits open enrollment preview feature has been removed

With our announcement in the [Strategic investments in core HR drive operational excellence](https://cloudblogs.microsoft.com/dynamics365/bdm/2019/10/02/strategic-investments-in-core-hr-drive-operational-excellence) blog post, Microsoft has removed the benefits open enrollment feature from public preview. New functionality will be released in the future. Production use of the benefits open enrollment feature isn't be supported.

## Coming soon

### Print performance reviews

See [Print performance reviews](/dynamics365-release-plan/2019wave2/dynamics365-talent/print-performance-reviews) in the Dynamics 365: 2019 release wave 2 plan.

### Feature management workspace

Features are added and updated in every release. The feature management experience provides a workspace where you can view a list of features that have been delivered in each release. By default, new features are turned off. You can use the workspace to turn them on and view the documentation for them.

To learn more about the changes coming with feature management, see [Feature management overview](../fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview.md).


[!INCLUDE[footer-include](../includes/footer-banner.md)]