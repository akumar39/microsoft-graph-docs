---
title: "openShift resource type"
description: "PROVIDE DESCRIPTION HERE"
localization_priority: Normal
author: "akumar39"
ms.prod: "Microsoft-Teams"
doc_type: "resourcePageType"
---

# openShift resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

PROVIDE DESCRIPTION HERE

## Methods

| Method       | Return Type | Description |
|:-------------|:------------|:------------|
| [Get openShift](../api/openshift-get.md) | [openShift](openshift.md) | Read properties and relationships of openShift object. |
| [Update](../api/openshift-update.md) | [openShift](openshift.md) | Update openShift object. |
| [Delete](../api/openshift-delete.md) | None | Delete openShift object. |

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|draftOpenShift|[openShiftItem](openshiftitem.md)||
|schedulingGroupId|String||
|sharedOpenShift|[openShiftItem](openshiftitem.md)||

## Relationships

None

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.openShift",
  "baseType": ""
}-->

```json
{
  "draftOpenShift": {"@odata.type": "microsoft.graph.openShiftItem"},
  "schedulingGroupId": "String",
  "sharedOpenShift": {"@odata.type": "microsoft.graph.openShiftItem"}
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "openShift resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->