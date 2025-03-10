---
title: Azure Monitor Logs reference - ExchangeAssessmentRecommendation
description: Reference for ExchangeAssessmentRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 12/30/2021
---

# ExchangeAssessmentRecommendation

 Recommendations generated by Exchange assessments that are started through a scheduled task. When you schedule the assessment it runs by default every 7 days and upload the data into Azure Log Analytics

## Categories

- Workloads
## Solutions

- ExchangeAssessment




## Columns

| Column | Type | Description |
| --- | --- | --- |
| ActionArea | string | The segment in which action is to be performed |
| ActionAreaId | string | ID generated for Action Area |
| ActiveDirectorySite | string |  |
| AffectedObjectName | string | Name of the affected object |
| AffectedObjectType | string | Type of object which is affected |
| AssessmentId | string | ID of the assessment |
| Computer | string | The machine from which data is uploaded |
| CustomData | string |  |
| Description | string | Description of the recommendation |
| ExchangeAdminGroup | string |  |
| ExchangeDAG | string |  |
| ExchangeMailboxDatabase | string |  |
| ExchangeOrganization | string |  |
| ExchangePublicFolderDatabase | string |  |
| ExchangeServer | string |  |
| FocusArea | string | Area to be focussed on |
| FocusAreaId | string | ID of the Focus Area |
| Recommendation | string | Generated recommendation |
| RecommendationId | string | ID of the recommendation generated |
| RecommendationResult | string | Result of the recommendation generated |
| RecommendationWeight | real | Weight of recommendation |
| SourceSystem | string |  |
| Technology | string |  |
| TimeGenerated | datetime | Date and time the record was created. |
| Type | string | The name of the table |
