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

## Properties

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

___

### CompileEventDisplayThresholdMs

• **CompileEventDisplayThresholdMs**: `number`

___

### GraphEditorQuickJumps

• **GraphEditorQuickJumps**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

___

### NodeTemplateCacheCapMB

• **NodeTemplateCacheCapMB**: `number`

___

### SaveOnCompile

• **SaveOnCompile**: [`ESaveOnCompile`](../enums/ue_ue.ESaveOnCompile.md)

___

### \_\_tid\_BlueprintEditorSettings\_\_

• **\_\_tid\_BlueprintEditorSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAllowExplicitImpureNodeDisabling

• **bAllowExplicitImpureNodeDisabling**: `boolean`

___

### bAlwaysShowInterfacesInOverrides

• **bAlwaysShowInterfacesInOverrides**: `boolean`

___

### bAutoCastObjectConnections

• **bAutoCastObjectConnections**: `boolean`

___

### bBlueprintNodeUniqueNames

• **bBlueprintNodeUniqueNames**: `boolean`

___

### bCompactCallOnMemberNodes

• **bCompactCallOnMemberNodes**: `boolean`

___

### bDrawMidpointArrowsInBlueprints

• **bDrawMidpointArrowsInBlueprints**: `boolean`

___

### bExposeAllMemberComponentFunctions

• **bExposeAllMemberComponentFunctions**: `boolean`

___

### bExposeDeprecatedFunctions

• **bExposeDeprecatedFunctions**: `boolean`

___

### bFavorPureCastNodes

• **bFavorPureCastNodes**: `boolean`

___

### bFlattenFavoritesMenus

• **bFlattenFavoritesMenus**: `boolean`

___

### bHideConstructionScriptComponentsInDetailsView

• **bHideConstructionScriptComponentsInDetailsView**: `boolean`

___

### bHostFindInBlueprintsInGlobalTab

• **bHostFindInBlueprintsInGlobalTab**: `boolean`

___

### bIncludeCommentNodesInBookmarksTab

• **bIncludeCommentNodesInBookmarksTab**: `boolean`

___

### bJumpToNodeErrors

• **bJumpToNodeErrors**: `boolean`

___

### bNavigateToNativeFunctionsFromCallNodes

• **bNavigateToNativeFunctionsFromCallNodes**: `boolean`

___

### bShowActionMenuItemSignatures

• **bShowActionMenuItemSignatures**: `boolean`

___

### bShowBookmarksForCurrentDocumentOnlyInTab

• **bShowBookmarksForCurrentDocumentOnlyInTab**: `boolean`

___

### bShowContextualFavorites

• **bShowContextualFavorites**: `boolean`

___

### bShowDetailedCompileResults

• **bShowDetailedCompileResults**: `boolean`

___

### bShowEmptySections

• **bShowEmptySections**: `boolean`

___

### bShowGraphInstructionText

• **bShowGraphInstructionText**: `boolean`

___

### bShowInheritedVariables

• **bShowInheritedVariables**: `boolean`

___

### bShowParentClassInOverrides

• **bShowParentClassInOverrides**: `boolean`

___

### bShowViewportOnSimulate

• **bShowViewportOnSimulate**: `boolean`

___

### bSpawnDefaultBlueprintNodes

• **bSpawnDefaultBlueprintNodes**: `boolean`

___

### bSplitContextTargetSettings

• **bSplitContextTargetSettings**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
