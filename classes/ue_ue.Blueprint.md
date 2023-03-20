[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Blueprint

# Class: Blueprint

[ue/ue](../modules/ue_ue.md).Blueprint

## Hierarchy

- [`BlueprintCore`](ue_ue.BlueprintCore.md)

  ↳ **`Blueprint`**

  ↳↳ [`AnimBlueprint`](ue_ue.AnimBlueprint.md)

  ↳↳ [`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

  ↳↳ [`BaseWidgetBlueprint`](ue_ue.BaseWidgetBlueprint.md)

  ↳↳ [`EditorUtilityBlueprint`](ue_ue.EditorUtilityBlueprint.md)

  ↳↳ [`LegacyLevelSequenceDirectorBlueprint`](ue_ue.LegacyLevelSequenceDirectorBlueprint.md)

  ↳↳ [`TypeScriptBlueprint`](ue_ue.TypeScriptBlueprint.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Blueprint.md#constructor)

### Properties

- [BlueprintCategory](ue_ue.Blueprint.md#blueprintcategory)
- [BlueprintDescription](ue_ue.Blueprint.md#blueprintdescription)
- [BlueprintDisplayName](ue_ue.Blueprint.md#blueprintdisplayname)
- [BlueprintGuid](ue_ue.Blueprint.md#blueprintguid)
- [BlueprintSystemVersion](ue_ue.Blueprint.md#blueprintsystemversion)
- [BlueprintType](ue_ue.Blueprint.md#blueprinttype)
- [BookmarkNodes](ue_ue.Blueprint.md#bookmarknodes)
- [Bookmarks](ue_ue.Blueprint.md#bookmarks)
- [Breakpoints](ue_ue.Blueprint.md#breakpoints)
- [CategorySorting](ue_ue.Blueprint.md#categorysorting)
- [CompileMode](ue_ue.Blueprint.md#compilemode)
- [ComponentClassOverrides](ue_ue.Blueprint.md#componentclassoverrides)
- [ComponentTemplateNameIndex](ue_ue.Blueprint.md#componenttemplatenameindex)
- [ComponentTemplates](ue_ue.Blueprint.md#componenttemplates)
- [CrcLastCompiledCDO](ue_ue.Blueprint.md#crclastcompiledcdo)
- [CrcLastCompiledSignature](ue_ue.Blueprint.md#crclastcompiledsignature)
- [DelegateSignatureGraphs](ue_ue.Blueprint.md#delegatesignaturegraphs)
- [DeprecatedPinWatches](ue_ue.Blueprint.md#deprecatedpinwatches)
- [EventGraphs](ue_ue.Blueprint.md#eventgraphs)
- [Extensions](ue_ue.Blueprint.md#extensions)
- [FunctionGraphs](ue_ue.Blueprint.md#functiongraphs)
- [GeneratedClass](ue_ue.Blueprint.md#generatedclass)
- [HideCategories](ue_ue.Blueprint.md#hidecategories)
- [ImplementedInterfaces](ue_ue.Blueprint.md#implementedinterfaces)
- [InheritableComponentHandler](ue_ue.Blueprint.md#inheritablecomponenthandler)
- [IntermediateGeneratedGraphs](ue_ue.Blueprint.md#intermediategeneratedgraphs)
- [LastEditedDocuments](ue_ue.Blueprint.md#lastediteddocuments)
- [MacroGraphs](ue_ue.Blueprint.md#macrographs)
- [NativizationFlag](ue_ue.Blueprint.md#nativizationflag)
- [NewVariables](ue_ue.Blueprint.md#newvariables)
- [OldToNewComponentTemplateNames](ue_ue.Blueprint.md#oldtonewcomponenttemplatenames)
- [OriginalClass](ue_ue.Blueprint.md#originalclass)
- [PRIVATE\_CachedMacroInfo](ue_ue.Blueprint.md#private_cachedmacroinfo)
- [ParentClass](ue_ue.Blueprint.md#parentclass)
- [SearchGuid](ue_ue.Blueprint.md#searchguid)
- [SimpleConstructionScript](ue_ue.Blueprint.md#simpleconstructionscript)
- [SkeletonGeneratedClass](ue_ue.Blueprint.md#skeletongeneratedclass)
- [Status](ue_ue.Blueprint.md#status)
- [ThumbnailInfo](ue_ue.Blueprint.md#thumbnailinfo)
- [Timelines](ue_ue.Blueprint.md#timelines)
- [UbergraphPages](ue_ue.Blueprint.md#ubergraphpages)
- [WatchedPins](ue_ue.Blueprint.md#watchedpins)
- [\_\_tid\_BlueprintCore\_\_](ue_ue.Blueprint.md#__tid_blueprintcore__)
- [\_\_tid\_Blueprint\_\_](ue_ue.Blueprint.md#__tid_blueprint__)
- [\_\_tid\_Object\_\_](ue_ue.Blueprint.md#__tid_object__)
- [bBeingCompiled](ue_ue.Blueprint.md#bbeingcompiled)
- [bDeprecate](ue_ue.Blueprint.md#bdeprecate)
- [bDisplayCompilePIEWarning](ue_ue.Blueprint.md#bdisplaycompilepiewarning)
- [bDuplicatingReadOnly](ue_ue.Blueprint.md#bduplicatingreadonly)
- [bForceFullEditor](ue_ue.Blueprint.md#bforcefulleditor)
- [bGenerateAbstractClass](ue_ue.Blueprint.md#bgenerateabstractclass)
- [bGenerateConstClass](ue_ue.Blueprint.md#bgenerateconstclass)
- [bHasBeenRegenerated](ue_ue.Blueprint.md#bhasbeenregenerated)
- [bIsNewlyCreated](ue_ue.Blueprint.md#bisnewlycreated)
- [bIsRegeneratingOnLoad](ue_ue.Blueprint.md#bisregeneratingonload)
- [bLegacyNeedToPurgeSkelRefs](ue_ue.Blueprint.md#blegacyneedtopurgeskelrefs)
- [bNativize](ue_ue.Blueprint.md#bnativize)
- [bQueuedForCompilation](ue_ue.Blueprint.md#bqueuedforcompilation)
- [bRecompileOnLoad](ue_ue.Blueprint.md#brecompileonload)
- [bRunConstructionScriptInSequencer](ue_ue.Blueprint.md#brunconstructionscriptinsequencer)
- [bRunConstructionScriptOnDrag](ue_ue.Blueprint.md#brunconstructionscriptondrag)

### Methods

- [CreateDefaultSubobject](ue_ue.Blueprint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Blueprint.md#executeubergraph)
- [GetClass](ue_ue.Blueprint.md#getclass)
- [GetName](ue_ue.Blueprint.md#getname)
- [GetOuter](ue_ue.Blueprint.md#getouter)
- [GetWorld](ue_ue.Blueprint.md#getworld)
- [Find](ue_ue.Blueprint.md#find)
- [Load](ue_ue.Blueprint.md#load)
- [StaticClass](ue_ue.Blueprint.md#staticclass)

## Constructors

### constructor

• **new Blueprint**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintCore](ue_ue.BlueprintCore.md).[constructor](ue_ue.BlueprintCore.md#constructor)

## Properties

### BlueprintCategory

• **BlueprintCategory**: `string`

___

### BlueprintDescription

• **BlueprintDescription**: `string`

___

### BlueprintDisplayName

• **BlueprintDisplayName**: `string`

___

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[BlueprintGuid](ue_ue.BlueprintCore.md#blueprintguid)

___

### BlueprintSystemVersion

• **BlueprintSystemVersion**: `number`

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

___

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

___

### Breakpoints

• **Breakpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Breakpoint`](ue_ue.Breakpoint.md)\>

___

### CategorySorting

• **CategorySorting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### CompileMode

• **CompileMode**: [`EBlueprintCompileMode`](../enums/ue_ue.EBlueprintCompileMode.md)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

___

### ComponentTemplateNameIndex

• **ComponentTemplateNameIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### CrcLastCompiledCDO

• **CrcLastCompiledCDO**: `number`

___

### CrcLastCompiledSignature

• **CrcLastCompiledSignature**: `number`

___

### DelegateSignatureGraphs

• **DelegateSignatureGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

___

### DeprecatedPinWatches

• **DeprecatedPinWatches**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

___

### EventGraphs

• **EventGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

___

### Extensions

• **Extensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintExtension`](ue_ue.BlueprintExtension.md)\>

___

### FunctionGraphs

• **FunctionGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GeneratedClass](ue_ue.BlueprintCore.md#generatedclass)

___

### HideCategories

• **HideCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ImplementedInterfaces

• **ImplementedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPInterfaceDescription`](ue_ue.BPInterfaceDescription.md)\>

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

___

### IntermediateGeneratedGraphs

• **IntermediateGeneratedGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

___

### MacroGraphs

• **MacroGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

___

### NativizationFlag

• **NativizationFlag**: [`EBlueprintNativizationFlag`](../enums/ue_ue.EBlueprintNativizationFlag.md)

___

### NewVariables

• **NewVariables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableDescription`](ue_ue.BPVariableDescription.md)\>

___

### OldToNewComponentTemplateNames

• **OldToNewComponentTemplateNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### OriginalClass

• **OriginalClass**: [`Class`](ue_ue.Class.md)

___

### PRIVATE\_CachedMacroInfo

• **PRIVATE\_CachedMacroInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EdGraph`](ue_ue.EdGraph.md), [`BlueprintMacroCosmeticInfo`](ue_ue.BlueprintMacroCosmeticInfo.md)\>

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

___

### SearchGuid

• **SearchGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[SkeletonGeneratedClass](ue_ue.BlueprintCore.md#skeletongeneratedclass)

___

### Status

• **Status**: [`EBlueprintStatus`](../enums/ue_ue.EBlueprintStatus.md)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

___

### UbergraphPages

• **UbergraphPages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

___

### WatchedPins

• **WatchedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPinReference`](ue_ue.EdGraphPinReference.md)\>

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[__tid_BlueprintCore__](ue_ue.BlueprintCore.md#__tid_blueprintcore__)

___

### \_\_tid\_Blueprint\_\_

• **\_\_tid\_Blueprint\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[__tid_Object__](ue_ue.BlueprintCore.md#__tid_object__)

___

### bBeingCompiled

• **bBeingCompiled**: `boolean`

___

### bDeprecate

• **bDeprecate**: `boolean`

___

### bDisplayCompilePIEWarning

• **bDisplayCompilePIEWarning**: `boolean`

___

### bDuplicatingReadOnly

• **bDuplicatingReadOnly**: `boolean`

___

### bForceFullEditor

• **bForceFullEditor**: `boolean`

___

### bGenerateAbstractClass

• **bGenerateAbstractClass**: `boolean`

___

### bGenerateConstClass

• **bGenerateConstClass**: `boolean`

___

### bHasBeenRegenerated

• **bHasBeenRegenerated**: `boolean`

___

### bIsNewlyCreated

• **bIsNewlyCreated**: `boolean`

___

### bIsRegeneratingOnLoad

• **bIsRegeneratingOnLoad**: `boolean`

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[bLegacyNeedToPurgeSkelRefs](ue_ue.BlueprintCore.md#blegacyneedtopurgeskelrefs)

___

### bNativize

• **bNativize**: `boolean`

___

### bQueuedForCompilation

• **bQueuedForCompilation**: `boolean`

___

### bRecompileOnLoad

• **bRecompileOnLoad**: `boolean`

___

### bRunConstructionScriptInSequencer

• **bRunConstructionScriptInSequencer**: `boolean`

___

### bRunConstructionScriptOnDrag

• **bRunConstructionScriptOnDrag**: `boolean`

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

[BlueprintCore](ue_ue.BlueprintCore.md).[CreateDefaultSubobject](ue_ue.BlueprintCore.md#createdefaultsubobject)

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

[BlueprintCore](ue_ue.BlueprintCore.md).[ExecuteUbergraph](ue_ue.BlueprintCore.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetClass](ue_ue.BlueprintCore.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetName](ue_ue.BlueprintCore.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetOuter](ue_ue.BlueprintCore.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetWorld](ue_ue.BlueprintCore.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Blueprint`](ue_ue.Blueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Blueprint`](ue_ue.Blueprint.md)

#### Overrides

[BlueprintCore](ue_ue.BlueprintCore.md).[Find](ue_ue.BlueprintCore.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Blueprint`](ue_ue.Blueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Blueprint`](ue_ue.Blueprint.md)

#### Overrides

[BlueprintCore](ue_ue.BlueprintCore.md).[Load](ue_ue.BlueprintCore.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintCore](ue_ue.BlueprintCore.md).[StaticClass](ue_ue.BlueprintCore.md#staticclass)
