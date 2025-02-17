---
title: "teamsAppSettings resource type"
description: "Represents Teams App Settings"
author: "sthapliyal"
ms.localizationpriority: medium
ms.prod: "microsoft-teams"
doc_type: resourcePageType
---

# teamsAppSettings resource type

Namespace: microsoft.graph

Represents tenant-wide settings for all [Teams apps](teamsapp.md) in the tenant.

Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get teamsAppSettings](../api/teamsappsettings-get.md)|[teamsAppSettings](../resources/teamsappsettings.md)|Get the tenant-wide settings for all Teams apps in the tenant.|
|[Update teamsAppSettings](../api/teamsappsettings-update.md)|[teamsAppSettings](../resources/teamsappsettings.md)|Update the tenant-wide settings for all Teams apps in the tenant.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowUserRequestsForAppAccess|Boolean|Indicates whether users are allowed to request access to the unavailable Teams apps.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.teamsAppSettings",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.teamsAppSettings",
  "id": "String (identifier)",
  "allowUserRequestsForAppAccess": "Boolean",
  "isChatResourceSpecificConsentEnabled": "Boolean"
}
```

## See also

- [Resource-specific consent](/microsoftteams/platform/graph-api/rsc/resource-specific-consent)