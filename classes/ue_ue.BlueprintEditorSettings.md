[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintEditorSettings

# Class: BlueprintEditorSettings

[ue/ue](../modules/ue_ue.md).BlueprintEditorSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BlueprintEditorSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintEditorSettings.md#constructor)

### Properties

- [BookmarkNodes](ue_ue.BlueprintEditorSettings.md#bookmarknodes)
- [Bookmarks](ue_ue.BlueprintEditorSettings.md#bookmarks)
- [CompileEventDisplayThresholdMs](ue_ue.BlueprintEditorSettings.md#compileeventdisplaythresholdms)
- [GraphEditorQuickJumps](ue_ue.BlueprintEditorSettings.md#grapheditorquickjumps)
- [NodeTemplateCacheCapMB](ue_ue.BlueprintEditorSettings.md#nodetemplatecachecapmb)
- [SaveOnCompile](ue_ue.BlueprintEditorSettings.md#saveoncompile)
- [\_\_tid\_BlueprintEditorSettings\_\_](ue_ue.BlueprintEditorSettings.md#__tid_blueprinteditorsettings__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintEditorSettings.md#__tid_object__)
- [bAllowExplicitImpureNodeDisabling](ue_ue.BlueprintEditorSettings.md#ballowexplicitimpurenodedisabling)
- [bAlwaysShowInterfacesInOverrides](ue_ue.BlueprintEditorSettings.md#balwaysshowinterfacesinoverrides)
- [bAutoCastObjectConnections](ue_ue.BlueprintEditorSettings.md#bautocastobjectconnections)
- [bBlueprintNodeUniqueNames](ue_ue.BlueprintEditorSettings.md#bblueprintnodeuniquenames)
- [bCompactCallOnMemberNodes](ue_ue.BlueprintEditorSettings.md#bcompactcallonmembernodes)
- [bDrawMidpointArrowsInBlueprints](ue_ue.BlueprintEditorSettings.md#bdrawmidpointarrowsinblueprints)
- [bExposeAllMemberComponentFunctions](ue_ue.BlueprintEditorSettings.md#bexposeallmembercomponentfunctions)
- [bExposeDeprecatedFunctions](ue_ue.BlueprintEditorSettings.md#bexposedeprecatedfunctions)
- [bFavorPureCastNodes](ue_ue.BlueprintEditorSettings.md#bfavorpurecastnodes)
- [bFlattenFavoritesMenus](ue_ue.BlueprintEditorSettings.md#bflattenfavoritesmenus)
- [bHideConstructionScriptComponentsInDetailsView](ue_ue.BlueprintEditorSettings.md#bhideconstructionscriptcomponentsindetailsview)
- [bHostFindInBlueprintsInGlobalTab](ue_ue.BlueprintEditorSettings.md#bhostfindinblueprintsinglobaltab)
- [bIncludeCommentNodesInBookmarksTab](ue_ue.BlueprintEditorSettings.md#bincludecommentnodesinbookmarkstab)
- [bJumpToNodeErrors](ue_ue.BlueprintEditorSettings.md#bjumptonodeerrors)
- [bNavigateToNativeFunctionsFromCallNodes](ue_ue.BlueprintEditorSettings.md#bnavigatetonativefunctionsfromcallnodes)
- [bShowActionMenuItemSignatures](ue_ue.BlueprintEditorSettings.md#bshowactionmenuitemsignatures)
- [bShowBookmarksForCurrentDocumentOnlyInTab](ue_ue.BlueprintEditorSettings.md#bshowbookmarksforcurrentdocumentonlyintab)
- [bShowContextualFavorites](ue_ue.BlueprintEditorSettings.md#bshowcontextualfavorites)
- [bShowDetailedCompileResults](ue_ue.BlueprintEditorSettings.md#bshowdetailedcompileresults)
- [bShowEmptySections](ue_ue.BlueprintEditorSettings.md#bshowemptysections)
- [bShowGraphInstructionText](ue_ue.BlueprintEditorSettings.md#bshowgraphinstructiontext)
- [bShowInheritedVariables](ue_ue.BlueprintEditorSettings.md#bshowinheritedvariables)
- [bShowParentClassInOverrides](ue_ue.BlueprintEditorSettings.md#bshowparentclassinoverrides)
- [bShowViewportOnSimulate](ue_ue.BlueprintEditorSettings.md#bshowviewportonsimulate)
- [bSpawnDefaultBlueprintNodes](ue_ue.BlueprintEditorSettings.md#bspawndefaultblueprintnodes)
- [bSplitContextTargetSettings](ue_ue.BlueprintEditorSettings.md#bsplitcontexttargetsettings)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintEditorSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintEditorSettings.md#executeubergraph)
- [GetClass](ue_ue.BlueprintEditorSettings.md#getclass)
- [GetName](ue_ue.BlueprintEditorSettings.md#getname)
- [GetOuter](ue_ue.BlueprintEditorSettings.md#getouter)
- [GetWorld](ue_ue.BlueprintEditorSettings.md#getworld)
- [Find](ue_ue.BlueprintEditorSettings.md#find)
- [Load](ue_ue.BlueprintEditorSettings.md#load)
- [StaticClass](ue_ue.BlueprintEditorSettings.md#staticclass)

## Constructors

### constructor

• **new BlueprintEditorSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:24010](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24010)

## Properties

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

#### Defined in

[ue/ue.d.ts:24031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24031)

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Defined in

[ue/ue.d.ts:24030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24030)

___

### CompileEventDisplayThresholdMs

• **CompileEventDisplayThresholdMs**: `number`

#### Defined in

[ue/ue.d.ts:24041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24041)

___

### GraphEditorQuickJumps

• **GraphEditorQuickJumps**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Defined in

[ue/ue.d.ts:24034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24034)

___

### NodeTemplateCacheCapMB

• **NodeTemplateCacheCapMB**: `number`

#### Defined in

[ue/ue.d.ts:24042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24042)

___

### SaveOnCompile

• **SaveOnCompile**: [`ESaveOnCompile`](../enums/ue_ue.ESaveOnCompile.md)

#### Defined in

[ue/ue.d.ts:24035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24035)

___

### \_\_tid\_BlueprintEditorSettings\_\_

• **\_\_tid\_BlueprintEditorSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24047)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAllowExplicitImpureNodeDisabling

• **bAllowExplicitImpureNodeDisabling**: `boolean`

#### Defined in

[ue/ue.d.ts:24037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24037)

___

### bAlwaysShowInterfacesInOverrides

• **bAlwaysShowInterfacesInOverrides**: `boolean`

#### Defined in

[ue/ue.d.ts:24023](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24023)

___

### bAutoCastObjectConnections

• **bAutoCastObjectConnections**: `boolean`

#### Defined in

[ue/ue.d.ts:24020](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24020)

___

### bBlueprintNodeUniqueNames

• **bBlueprintNodeUniqueNames**: `boolean`

#### Defined in

[ue/ue.d.ts:24039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24039)

___

### bCompactCallOnMemberNodes

• **bCompactCallOnMemberNodes**: `boolean`

#### Defined in

[ue/ue.d.ts:24017](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24017)

___

### bDrawMidpointArrowsInBlueprints

• **bDrawMidpointArrowsInBlueprints**: `boolean`

#### Defined in

[ue/ue.d.ts:24011](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24011)

___

### bExposeAllMemberComponentFunctions

• **bExposeAllMemberComponentFunctions**: `boolean`

#### Defined in

[ue/ue.d.ts:24014](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24014)

___

### bExposeDeprecatedFunctions

• **bExposeDeprecatedFunctions**: `boolean`

#### Defined in

[ue/ue.d.ts:24016](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24016)

___

### bFavorPureCastNodes

• **bFavorPureCastNodes**: `boolean`

#### Defined in

[ue/ue.d.ts:24019](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24019)

___

### bFlattenFavoritesMenus

• **bFlattenFavoritesMenus**: `boolean`

#### Defined in

[ue/ue.d.ts:24018](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24018)

___

### bHideConstructionScriptComponentsInDetailsView

• **bHideConstructionScriptComponentsInDetailsView**: `boolean`

#### Defined in

[ue/ue.d.ts:24027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24027)

___

### bHostFindInBlueprintsInGlobalTab

• **bHostFindInBlueprintsInGlobalTab**: `boolean`

#### Defined in

[ue/ue.d.ts:24028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24028)

___

### bIncludeCommentNodesInBookmarksTab

• **bIncludeCommentNodesInBookmarksTab**: `boolean`

#### Defined in

[ue/ue.d.ts:24032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24032)

___

### bJumpToNodeErrors

• **bJumpToNodeErrors**: `boolean`

#### Defined in

[ue/ue.d.ts:24036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24036)

___

### bNavigateToNativeFunctionsFromCallNodes

• **bNavigateToNativeFunctionsFromCallNodes**: `boolean`

#### Defined in

[ue/ue.d.ts:24029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24029)

___

### bShowActionMenuItemSignatures

• **bShowActionMenuItemSignatures**: `boolean`

#### Defined in

[ue/ue.d.ts:24038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24038)

___

### bShowBookmarksForCurrentDocumentOnlyInTab

• **bShowBookmarksForCurrentDocumentOnlyInTab**: `boolean`

#### Defined in

[ue/ue.d.ts:24033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24033)

___

### bShowContextualFavorites

• **bShowContextualFavorites**: `boolean`

#### Defined in

[ue/ue.d.ts:24015](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24015)

___

### bShowDetailedCompileResults

• **bShowDetailedCompileResults**: `boolean`

#### Defined in

[ue/ue.d.ts:24040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24040)

___

### bShowEmptySections

• **bShowEmptySections**: `boolean`

#### Defined in

[ue/ue.d.ts:24025](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24025)

___

### bShowGraphInstructionText

• **bShowGraphInstructionText**: `boolean`

#### Defined in

[ue/ue.d.ts:24012](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24012)

___

### bShowInheritedVariables

• **bShowInheritedVariables**: `boolean`

#### Defined in

[ue/ue.d.ts:24022](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24022)

___

### bShowParentClassInOverrides

• **bShowParentClassInOverrides**: `boolean`

#### Defined in

[ue/ue.d.ts:24024](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24024)

___

### bShowViewportOnSimulate

• **bShowViewportOnSimulate**: `boolean`

#### Defined in

[ue/ue.d.ts:24021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24021)

___

### bSpawnDefaultBlueprintNodes

• **bSpawnDefaultBlueprintNodes**: `boolean`

#### Defined in

[ue/ue.d.ts:24026](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24026)

___

### bSplitContextTargetSettings

• **bSplitContextTargetSettings**: `boolean`

#### Defined in

[ue/ue.d.ts:24013](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24013)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintEditorSettings`](ue_ue.BlueprintEditorSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintEditorSettings`](ue_ue.BlueprintEditorSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:24044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24044)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintEditorSettings`](ue_ue.BlueprintEditorSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintEditorSettings`](ue_ue.BlueprintEditorSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:24045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24045)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:24043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24043)
