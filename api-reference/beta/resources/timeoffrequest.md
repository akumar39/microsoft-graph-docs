---
title: "timeOffRequest resource type"
description: "PROVIDE DESCRIPTION HERE"
localization_priority: Normal
author: "akumar39"
ms.prod: "Microsoft-Teams"
doc_type: "resourcePageType"
---

# timeOffRequest resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

PROVIDE DESCRIPTION HERE

## Methods

| Method       | Return Type | Description |
|:-------------|:------------|:------------|
| [Get timeOffRequest](../api/timeoffrequest-get.md) | [timeOffRequest](timeoffrequest.md) | Read properties and relationships of timeOffRequest object. |
| [Update](../api/timeoffrequest-update.md) | [timeOffRequest](timeoffrequest.md) | Update timeOffRequest object. |
| [Delete](../api/timeoffrequest-delete.md) | None | Delete timeOffRequest object. |
|[Approve](../api/timeoffrequest-approve.md)|None||
|[Decline](../api/timeoffrequest-decline.md)|None||

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|endDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: `'2014-01-01T00:00:00Z'`|
|startDateTime|DateTimeOffset|The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: `'2014-01-01T00:00:00Z'`|
|timeOffReasonId|String||

## Relationships

None

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.timeOffRequest",
  "baseType": ""
}-->

```json
{
  "endDateTime": "String (timestamp)",
  "startDateTime": "String (timestamp)",
  "timeOffReasonId": "String"
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "timeOffRequest resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->