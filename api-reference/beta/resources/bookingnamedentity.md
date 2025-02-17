---
title: "bookingNamedEntity resource type"
description: "This is a base type for Microsoft Bookings entities that provide a display name, for example, bookingBusiness, bookingPerson, bookingService."
ms.localizationpriority: medium
author: "arvindmicrosoft"
ms.prod: "bookings"
doc_type: resourcePageType
---

# bookingNamedEntity resource type

Namespace: microsoft.graph

 [!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]
 
This is a base type for Microsoft Bookings entities that provide a display name, for example, [bookingBusiness](bookingbusiness.md), [bookingPerson](bookingperson.md), [bookingService](bookingservice.md), [bookingCustomQuestion](bookingcustomquestion.md).

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|displayName|String|A name for the derived entity, which interfaces with customers.|
|id|String| The ID for the derived entity. Read-only.|

## Relationships
None


## JSON representation

Here's a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.bookingNamedEntity"
}-->

```json
{
  "displayName": "String",
  "id": "String (identifier)"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "bookingNamedEntity resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->


