---
title: Azure Monitor Logs reference - ADAssessmentRecommendation
description: Reference for ADAssessmentRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 12/30/2021
---

# ADAssessmentRecommendation

 Recommendations generated by AD assessments that are started through a scheduled task. When you schedule the assessment it runs by default every 7 days and upload the data into Azure Log Analytics

## Categories

- Workloads
## Solutions

- Active Directory Health Check
- ADAssessmentPlus
## Resource types

- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager




## Columns

| Column | Type | Description |
| --- | --- | --- |
| ActionArea | string | The segment in which action is to be performed |
| ActionAreaId | string | ID generated for Action Area |
| AffectedObjectName | string | Name of the affected object |
| AffectedObjectType | string | Type of object which is affected |
| AssessmentId | string | ID of the assessment |
| Computer | string | The machine from which data is uploaded |
| CustomData | string |  |
| Description | string | Description of the recommendation |
| Domain | string | Domain of the system |
| DomainController | string |  |
| FocusArea | string | Area to be focussed on |
| FocusAreaId | string | ID of the Focus Area |
| Forest | string |  |
| Recommendation | string | Generated recommendation |
| RecommendationId | string | ID of the recommendation generated |
| RecommendationResult | string | Result of the recommendation generated |
| RecommendationWeight | real | Weight of recommendation |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | OpsManager |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| Technology | string |  |
| TimeGenerated | datetime | Date and time the record was created. |
| Type | string | The name of the table |
