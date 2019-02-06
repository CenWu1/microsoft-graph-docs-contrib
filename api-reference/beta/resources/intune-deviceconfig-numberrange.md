---
title: "numberRange resource type"
description: "Number Range definition."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# numberRange resource type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Number Range definition.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|lowerNumber|Int32|Lower number.|
|upperNumber|Int32|Upper number.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.numberRange"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.numberRange",
  "lowerNumber": 1024,
  "upperNumber": 1024
}
```



