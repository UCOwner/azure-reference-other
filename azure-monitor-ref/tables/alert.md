---
title: Azure Monitor Logs reference - Alert
description: Reference for Alert table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 12/30/2021
---

# Alert

 Alerts created by log alerts rules and SCOM alerts collected through Alert Management solution.

## Categories

- Azure Monitor
## Solutions

- LogManagement




## Columns

| Column | Type | Description |
| --- | --- | --- |
| AlertContext | string |  |
| AlertDescription | string | Detailed description of the alert. |
| AlertError | string |  |
| AlertId | string |  |
| AlertName | string | Name of the alert. |
| AlertPriority | string |  |
| AlertRuleId | string |  |
| AlertRuleInstanceId | string |  |
| AlertSeverity | string | Severity level of the alert. |
| AlertState | string | Latest resolution state of the alert. |
| AlertStatus | int |  |
| AlertTypeDescription | string |  |
| AlertTypeNumber | int |  |
| AlertValue | int |  |
| Comments | string |  |
| Computer | string |  |
| Custom1 | string |  |
| Custom10 | string |  |
| Custom2 | string |  |
| Custom3 | string |  |
| Custom4 | string |  |
| Custom5 | string |  |
| Custom6 | string |  |
| Custom7 | string |  |
| Custom8 | string |  |
| Custom9 | string |  |
| Expression | string |  |
| Flags | int |  |
| FlagsDescription | string |  |
| HostName | string |  |
| LastModifiedBy | string |  |
| LinkToSearchResults | string |  |
| ManagementGroupName | string |  |
| ObjectDisplayName | string |  |
| PriorityNumber | int |  |
| Query | string |  |
| QueryExecutionEndTime | datetime |  |
| QueryExecutionStartTime | datetime |  |
| RemediationJobId | string |  |
| RemediationRunbookName | string |  |
| RepeatCount | int |  |
| ResolvedBy | string |  |
| ResourceId | string |  |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ResourceType | string |  |
| ResourceValue | string |  |
| RootObjectName | string |  |
| ServiceDeskConnectionName | string |  |
| ServiceDeskId | string |  |
| ServiceDeskWorkItemLink | string |  |
| ServiceDeskWorkItemType | string |  |
| SourceDisplayName | string | Display name of the monitoring object that generated the alert. |
| SourceFullName | string |  |
| SourceSystem | string |  |
| StateType | string |  |
| StatusDescription | string |  |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TemplateId | string |  |
| ThresholdOperator | string |  |
| ThresholdValue | int |  |
| TicketId | string |  |
| TimeGenerated | datetime | Date and time the record was created. |
| TimeLastModified | datetime |  |
| TimeRaised | datetime |  |
| TimeResolved | datetime |  |
| TriggerId | string |  |
| Type | string | The name of the table |
| Url | string |  |
| ValueDescription | string |  |
| ValueFlags | int |  |
| ValueFlagsDescription | string |  |
