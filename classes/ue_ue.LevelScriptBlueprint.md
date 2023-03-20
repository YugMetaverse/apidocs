[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelScriptBlueprint

# Class: LevelScriptBlueprint

[ue/ue](../modules/ue_ue.md).LevelScriptBlueprint

## Hierarchy

- [`Blueprint`](ue_ue.Blueprint.md)

  ↳ **`LevelScriptBlueprint`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelScriptBlueprint.md#constructor)

### Properties

- [BlueprintCategory](ue_ue.LevelScriptBlueprint.md#blueprintcategory)
- [BlueprintDescription](ue_ue.LevelScriptBlueprint.md#blueprintdescription)
- [BlueprintDisplayName](ue_ue.LevelScriptBlueprint.md#blueprintdisplayname)
- [BlueprintGuid](ue_ue.LevelScriptBlueprint.md#blueprintguid)
- [BlueprintSystemVersion](ue_ue.LevelScriptBlueprint.md#blueprintsystemversion)
- [BlueprintType](ue_ue.LevelScriptBlueprint.md#blueprinttype)
- [BookmarkNodes](ue_ue.LevelScriptBlueprint.md#bookmarknodes)
- [Bookmarks](ue_ue.LevelScriptBlueprint.md#bookmarks)
- [Breakpoints](ue_ue.LevelScriptBlueprint.md#breakpoints)
- [CategorySorting](ue_ue.LevelScriptBlueprint.md#categorysorting)
- [CompileMode](ue_ue.LevelScriptBlueprint.md#compilemode)
- [ComponentClassOverrides](ue_ue.LevelScriptBlueprint.md#componentclassoverrides)
- [ComponentTemplateNameIndex](ue_ue.LevelScriptBlueprint.md#componenttemplatenameindex)
- [ComponentTemplates](ue_ue.LevelScriptBlueprint.md#componenttemplates)
- [CrcLastCompiledCDO](ue_ue.LevelScriptBlueprint.md#crclastcompiledcdo)
- [CrcLastCompiledSignature](ue_ue.LevelScriptBlueprint.md#crclastcompiledsignature)
- [DelegateSignatureGraphs](ue_ue.LevelScriptBlueprint.md#delegatesignaturegraphs)
- [DeprecatedPinWatches](ue_ue.LevelScriptBlueprint.md#deprecatedpinwatches)
- [EventGraphs](ue_ue.LevelScriptBlueprint.md#eventgraphs)
- [Extensions](ue_ue.LevelScriptBlueprint.md#extensions)
- [FriendlyName](ue_ue.LevelScriptBlueprint.md#friendlyname)
- [FunctionGraphs](ue_ue.LevelScriptBlueprint.md#functiongraphs)
- [GeneratedClass](ue_ue.LevelScriptBlueprint.md#generatedclass)
- [HideCategories](ue_ue.LevelScriptBlueprint.md#hidecategories)
- [ImplementedInterfaces](ue_ue.LevelScriptBlueprint.md#implementedinterfaces)
- [InheritableComponentHandler](ue_ue.LevelScriptBlueprint.md#inheritablecomponenthandler)
- [IntermediateGeneratedGraphs](ue_ue.LevelScriptBlueprint.md#intermediategeneratedgraphs)
- [LastEditedDocuments](ue_ue.LevelScriptBlueprint.md#lastediteddocuments)
- [MacroGraphs](ue_ue.LevelScriptBlueprint.md#macrographs)
- [NativizationFlag](ue_ue.LevelScriptBlueprint.md#nativizationflag)
- [NewVariables](ue_ue.LevelScriptBlueprint.md#newvariables)
- [OldToNewComponentTemplateNames](ue_ue.LevelScriptBlueprint.md#oldtonewcomponenttemplatenames)
- [OriginalClass](ue_ue.LevelScriptBlueprint.md#originalclass)
- [PRIVATE\_CachedMacroInfo](ue_ue.LevelScriptBlueprint.md#private_cachedmacroinfo)
- [ParentClass](ue_ue.LevelScriptBlueprint.md#parentclass)
- [SearchGuid](ue_ue.LevelScriptBlueprint.md#searchguid)
- [SimpleConstructionScript](ue_ue.LevelScriptBlueprint.md#simpleconstructionscript)
- [SkeletonGeneratedClass](ue_ue.LevelScriptBlueprint.md#skeletongeneratedclass)
- [Status](ue_ue.LevelScriptBlueprint.md#status)
- [ThumbnailInfo](ue_ue.LevelScriptBlueprint.md#thumbnailinfo)
- [Timelines](ue_ue.LevelScriptBlueprint.md#timelines)
- [UbergraphPages](ue_ue.LevelScriptBlueprint.md#ubergraphpages)
- [WatchedPins](ue_ue.LevelScriptBlueprint.md#watchedpins)
- [\_\_tid\_BlueprintCore\_\_](ue_ue.LevelScriptBlueprint.md#__tid_blueprintcore__)
- [\_\_tid\_Blueprint\_\_](ue_ue.LevelScriptBlueprint.md#__tid_blueprint__)
- [\_\_tid\_LevelScriptBlueprint\_\_](ue_ue.LevelScriptBlueprint.md#__tid_levelscriptblueprint__)
- [\_\_tid\_Object\_\_](ue_ue.LevelScriptBlueprint.md#__tid_object__)
- [bBeingCompiled](ue_ue.LevelScriptBlueprint.md#bbeingcompiled)
- [bDeprecate](ue_ue.LevelScriptBlueprint.md#bdeprecate)
- [bDisplayCompilePIEWarning](ue_ue.LevelScriptBlueprint.md#bdisplaycompilepiewarning)
- [bDuplicatingReadOnly](ue_ue.LevelScriptBlueprint.md#bduplicatingreadonly)
- [bForceFullEditor](ue_ue.LevelScriptBlueprint.md#bforcefulleditor)
- [bGenerateAbstractClass](ue_ue.LevelScriptBlueprint.md#bgenerateabstractclass)
- [bGenerateConstClass](ue_ue.LevelScriptBlueprint.md#bgenerateconstclass)
- [bHasBeenRegenerated](ue_ue.LevelScriptBlueprint.md#bhasbeenregenerated)
- [bIsNewlyCreated](ue_ue.LevelScriptBlueprint.md#bisnewlycreated)
- [bIsRegeneratingOnLoad](ue_ue.LevelScriptBlueprint.md#bisregeneratingonload)
- [bLegacyNeedToPurgeSkelRefs](ue_ue.LevelScriptBlueprint.md#blegacyneedtopurgeskelrefs)
- [bNativize](ue_ue.LevelScriptBlueprint.md#bnativize)
- [bQueuedForCompilation](ue_ue.LevelScriptBlueprint.md#bqueuedforcompilation)
- [bRecompileOnLoad](ue_ue.LevelScriptBlueprint.md#brecompileonload)
- [bRunConstructionScriptInSequencer](ue_ue.LevelScriptBlueprint.md#brunconstructionscriptinsequencer)
- [bRunConstructionScriptOnDrag](ue_ue.LevelScriptBlueprint.md#brunconstructionscriptondrag)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelScriptBlueprint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelScriptBlueprint.md#executeubergraph)
- [GetClass](ue_ue.LevelScriptBlueprint.md#getclass)
- [GetName](ue_ue.LevelScriptBlueprint.md#getname)
- [GetOuter](ue_ue.LevelScriptBlueprint.md#getouter)
- [GetWorld](ue_ue.LevelScriptBlueprint.md#getworld)
- [Find](ue_ue.LevelScriptBlueprint.md#find)
- [Load](ue_ue.LevelScriptBlueprint.md#load)
- [StaticClass](ue_ue.LevelScriptBlueprint.md#staticclass)

## Constructors

### constructor

• **new LevelScriptBlueprint**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[constructor](ue_ue.Blueprint.md#constructor)

## Properties

### BlueprintCategory

• **BlueprintCategory**: `string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintCategory](ue_ue.Blueprint.md#blueprintcategory)

___

### BlueprintDescription

• **BlueprintDescription**: `string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintDescription](ue_ue.Blueprint.md#blueprintdescription)

___

### BlueprintDisplayName

• **BlueprintDisplayName**: `string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintDisplayName](ue_ue.Blueprint.md#blueprintdisplayname)

___

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintGuid](ue_ue.Blueprint.md#blueprintguid)

___

### BlueprintSystemVersion

• **BlueprintSystemVersion**: `number`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintSystemVersion](ue_ue.Blueprint.md#blueprintsystemversion)

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintType](ue_ue.Blueprint.md#blueprinttype)

___

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BookmarkNodes](ue_ue.Blueprint.md#bookmarknodes)

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Bookmarks](ue_ue.Blueprint.md#bookmarks)

___

### Breakpoints

• **Breakpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Breakpoint`](ue_ue.Breakpoint.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Breakpoints](ue_ue.Blueprint.md#breakpoints)

___

### CategorySorting

• **CategorySorting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CategorySorting](ue_ue.Blueprint.md#categorysorting)

___

### CompileMode

• **CompileMode**: [`EBlueprintCompileMode`](../enums/ue_ue.EBlueprintCompileMode.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CompileMode](ue_ue.Blueprint.md#compilemode)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ComponentClassOverrides](ue_ue.Blueprint.md#componentclassoverrides)

___

### ComponentTemplateNameIndex

• **ComponentTemplateNameIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ComponentTemplateNameIndex](ue_ue.Blueprint.md#componenttemplatenameindex)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ComponentTemplates](ue_ue.Blueprint.md#componenttemplates)

___

### CrcLastCompiledCDO

• **CrcLastCompiledCDO**: `number`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CrcLastCompiledCDO](ue_ue.Blueprint.md#crclastcompiledcdo)

___

### CrcLastCompiledSignature

• **CrcLastCompiledSignature**: `number`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CrcLastCompiledSignature](ue_ue.Blueprint.md#crclastcompiledsignature)

___

### DelegateSignatureGraphs

• **DelegateSignatureGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[DelegateSignatureGraphs](ue_ue.Blueprint.md#delegatesignaturegraphs)

___

### DeprecatedPinWatches

• **DeprecatedPinWatches**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[DeprecatedPinWatches](ue_ue.Blueprint.md#deprecatedpinwatches)

___

### EventGraphs

• **EventGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[EventGraphs](ue_ue.Blueprint.md#eventgraphs)

___

### Extensions

• **Extensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintExtension`](ue_ue.BlueprintExtension.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Extensions](ue_ue.Blueprint.md#extensions)

___

### FriendlyName

• **FriendlyName**: `string`

___

### FunctionGraphs

• **FunctionGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[FunctionGraphs](ue_ue.Blueprint.md#functiongraphs)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GeneratedClass](ue_ue.Blueprint.md#generatedclass)

___

### HideCategories

• **HideCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[HideCategories](ue_ue.Blueprint.md#hidecategories)

___

### ImplementedInterfaces

• **ImplementedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPInterfaceDescription`](ue_ue.BPInterfaceDescription.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ImplementedInterfaces](ue_ue.Blueprint.md#implementedinterfaces)

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[InheritableComponentHandler](ue_ue.Blueprint.md#inheritablecomponenthandler)

___

### IntermediateGeneratedGraphs

• **IntermediateGeneratedGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[IntermediateGeneratedGraphs](ue_ue.Blueprint.md#intermediategeneratedgraphs)

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[LastEditedDocuments](ue_ue.Blueprint.md#lastediteddocuments)

___

### MacroGraphs

• **MacroGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[MacroGraphs](ue_ue.Blueprint.md#macrographs)

___

### NativizationFlag

• **NativizationFlag**: [`EBlueprintNativizationFlag`](../enums/ue_ue.EBlueprintNativizationFlag.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[NativizationFlag](ue_ue.Blueprint.md#nativizationflag)

___

### NewVariables

• **NewVariables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableDescription`](ue_ue.BPVariableDescription.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[NewVariables](ue_ue.Blueprint.md#newvariables)

___

### OldToNewComponentTemplateNames

• **OldToNewComponentTemplateNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[OldToNewComponentTemplateNames](ue_ue.Blueprint.md#oldtonewcomponenttemplatenames)

___

### OriginalClass

• **OriginalClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[OriginalClass](ue_ue.Blueprint.md#originalclass)

___

### PRIVATE\_CachedMacroInfo

• **PRIVATE\_CachedMacroInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EdGraph`](ue_ue.EdGraph.md), [`BlueprintMacroCosmeticInfo`](ue_ue.BlueprintMacroCosmeticInfo.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[PRIVATE_CachedMacroInfo](ue_ue.Blueprint.md#private_cachedmacroinfo)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ParentClass](ue_ue.Blueprint.md#parentclass)

___

### SearchGuid

• **SearchGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[SearchGuid](ue_ue.Blueprint.md#searchguid)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[SimpleConstructionScript](ue_ue.Blueprint.md#simpleconstructionscript)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[SkeletonGeneratedClass](ue_ue.Blueprint.md#skeletongeneratedclass)

___

### Status

• **Status**: [`EBlueprintStatus`](../enums/ue_ue.EBlueprintStatus.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Status](ue_ue.Blueprint.md#status)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ThumbnailInfo](ue_ue.Blueprint.md#thumbnailinfo)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Timelines](ue_ue.Blueprint.md#timelines)

___

### UbergraphPages

• **UbergraphPages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[UbergraphPages](ue_ue.Blueprint.md#ubergraphpages)

___

### WatchedPins

• **WatchedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPinReference`](ue_ue.EdGraphPinReference.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[WatchedPins](ue_ue.Blueprint.md#watchedpins)

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[__tid_BlueprintCore__](ue_ue.Blueprint.md#__tid_blueprintcore__)

___

### \_\_tid\_Blueprint\_\_

• **\_\_tid\_Blueprint\_\_**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[__tid_Blueprint__](ue_ue.Blueprint.md#__tid_blueprint__)

___

### \_\_tid\_LevelScriptBlueprint\_\_

• **\_\_tid\_LevelScriptBlueprint\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[__tid_Object__](ue_ue.Blueprint.md#__tid_object__)

___

### bBeingCompiled

• **bBeingCompiled**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bBeingCompiled](ue_ue.Blueprint.md#bbeingcompiled)

___

### bDeprecate

• **bDeprecate**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bDeprecate](ue_ue.Blueprint.md#bdeprecate)

___

### bDisplayCompilePIEWarning

• **bDisplayCompilePIEWarning**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bDisplayCompilePIEWarning](ue_ue.Blueprint.md#bdisplaycompilepiewarning)

___

### bDuplicatingReadOnly

• **bDuplicatingReadOnly**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bDuplicatingReadOnly](ue_ue.Blueprint.md#bduplicatingreadonly)

___

### bForceFullEditor

• **bForceFullEditor**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bForceFullEditor](ue_ue.Blueprint.md#bforcefulleditor)

___

### bGenerateAbstractClass

• **bGenerateAbstractClass**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bGenerateAbstractClass](ue_ue.Blueprint.md#bgenerateabstractclass)

___

### bGenerateConstClass

• **bGenerateConstClass**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bGenerateConstClass](ue_ue.Blueprint.md#bgenerateconstclass)

___

### bHasBeenRegenerated

• **bHasBeenRegenerated**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bHasBeenRegenerated](ue_ue.Blueprint.md#bhasbeenregenerated)

___

### bIsNewlyCreated

• **bIsNewlyCreated**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bIsNewlyCreated](ue_ue.Blueprint.md#bisnewlycreated)

___

### bIsRegeneratingOnLoad

• **bIsRegeneratingOnLoad**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bIsRegeneratingOnLoad](ue_ue.Blueprint.md#bisregeneratingonload)

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bLegacyNeedToPurgeSkelRefs](ue_ue.Blueprint.md#blegacyneedtopurgeskelrefs)

___

### bNativize

• **bNativize**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bNativize](ue_ue.Blueprint.md#bnativize)

___

### bQueuedForCompilation

• **bQueuedForCompilation**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bQueuedForCompilation](ue_ue.Blueprint.md#bqueuedforcompilation)

___

### bRecompileOnLoad

• **bRecompileOnLoad**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bRecompileOnLoad](ue_ue.Blueprint.md#brecompileonload)

___

### bRunConstructionScriptInSequencer

• **bRunConstructionScriptInSequencer**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bRunConstructionScriptInSequencer](ue_ue.Blueprint.md#brunconstructionscriptinsequencer)

___

### bRunConstructionScriptOnDrag

• **bRunConstructionScriptOnDrag**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bRunConstructionScriptOnDrag](ue_ue.Blueprint.md#brunconstructionscriptondrag)

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

[Blueprint](ue_ue.Blueprint.md).[CreateDefaultSubobject](ue_ue.Blueprint.md#createdefaultsubobject)

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

[Blueprint](ue_ue.Blueprint.md).[ExecuteUbergraph](ue_ue.Blueprint.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetClass](ue_ue.Blueprint.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetName](ue_ue.Blueprint.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetOuter](ue_ue.Blueprint.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetWorld](ue_ue.Blueprint.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[Find](ue_ue.Blueprint.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[Load](ue_ue.Blueprint.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[StaticClass](ue_ue.Blueprint.md#staticclass)
