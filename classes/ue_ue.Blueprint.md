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

#### Defined in

[ue/ue.d.ts:4459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4459)

## Properties

### BlueprintCategory

• **BlueprintCategory**: `string`

#### Defined in

[ue/ue.d.ts:4482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4482)

___

### BlueprintDescription

• **BlueprintDescription**: `string`

#### Defined in

[ue/ue.d.ts:4481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4481)

___

### BlueprintDisplayName

• **BlueprintDisplayName**: `string`

#### Defined in

[ue/ue.d.ts:4480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4480)

___

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[BlueprintGuid](ue_ue.BlueprintCore.md#blueprintguid)

#### Defined in

[ue/ue.d.ts:4077](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4077)

___

### BlueprintSystemVersion

• **BlueprintSystemVersion**: `number`

#### Defined in

[ue/ue.d.ts:4485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4485)

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

#### Defined in

[ue/ue.d.ts:4461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4461)

___

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

#### Defined in

[ue/ue.d.ts:4503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4503)

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Defined in

[ue/ue.d.ts:4502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4502)

___

### Breakpoints

• **Breakpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Breakpoint`](ue_ue.Breakpoint.md)\>

#### Defined in

[ue/ue.d.ts:4504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4504)

___

### CategorySorting

• **CategorySorting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:4499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4499)

___

### CompileMode

• **CompileMode**: [`EBlueprintCompileMode`](../enums/ue_ue.EBlueprintCompileMode.md)

#### Defined in

[ue/ue.d.ts:4478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4478)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Defined in

[ue/ue.d.ts:4496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4496)

___

### ComponentTemplateNameIndex

• **ComponentTemplateNameIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Defined in

[ue/ue.d.ts:4507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4507)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Defined in

[ue/ue.d.ts:4494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4494)

___

### CrcLastCompiledCDO

• **CrcLastCompiledCDO**: `number`

#### Defined in

[ue/ue.d.ts:4511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4511)

___

### CrcLastCompiledSignature

• **CrcLastCompiledSignature**: `number`

#### Defined in

[ue/ue.d.ts:4512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4512)

___

### DelegateSignatureGraphs

• **DelegateSignatureGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4489)

___

### DeprecatedPinWatches

• **DeprecatedPinWatches**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Defined in

[ue/ue.d.ts:4506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4506)

___

### EventGraphs

• **EventGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4492)

___

### Extensions

• **Extensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintExtension`](ue_ue.BlueprintExtension.md)\>

#### Defined in

[ue/ue.d.ts:4509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4509)

___

### FunctionGraphs

• **FunctionGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4488)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GeneratedClass](ue_ue.BlueprintCore.md#generatedclass)

#### Defined in

[ue/ue.d.ts:4075](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4075)

___

### HideCategories

• **HideCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:4483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4483)

___

### ImplementedInterfaces

• **ImplementedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPInterfaceDescription`](ue_ue.BPInterfaceDescription.md)\>

#### Defined in

[ue/ue.d.ts:4500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4500)

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Defined in

[ue/ue.d.ts:4497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4497)

___

### IntermediateGeneratedGraphs

• **IntermediateGeneratedGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4491)

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Defined in

[ue/ue.d.ts:4501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4501)

___

### MacroGraphs

• **MacroGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4490)

___

### NativizationFlag

• **NativizationFlag**: [`EBlueprintNativizationFlag`](../enums/ue_ue.EBlueprintNativizationFlag.md)

#### Defined in

[ue/ue.d.ts:4477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4477)

___

### NewVariables

• **NewVariables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableDescription`](ue_ue.BPVariableDescription.md)\>

#### Defined in

[ue/ue.d.ts:4498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4498)

___

### OldToNewComponentTemplateNames

• **OldToNewComponentTemplateNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Defined in

[ue/ue.d.ts:4508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4508)

___

### OriginalClass

• **OriginalClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:4513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4513)

___

### PRIVATE\_CachedMacroInfo

• **PRIVATE\_CachedMacroInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EdGraph`](ue_ue.EdGraph.md), [`BlueprintMacroCosmeticInfo`](ue_ue.BlueprintMacroCosmeticInfo.md)\>

#### Defined in

[ue/ue.d.ts:4493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4493)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:4460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4460)

___

### SearchGuid

• **SearchGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:4484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4484)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Defined in

[ue/ue.d.ts:4486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4486)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[SkeletonGeneratedClass](ue_ue.BlueprintCore.md#skeletongeneratedclass)

#### Defined in

[ue/ue.d.ts:4074](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4074)

___

### Status

• **Status**: [`EBlueprintStatus`](../enums/ue_ue.EBlueprintStatus.md)

#### Defined in

[ue/ue.d.ts:4479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4479)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:4510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4510)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Defined in

[ue/ue.d.ts:4495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4495)

___

### UbergraphPages

• **UbergraphPages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Defined in

[ue/ue.d.ts:4487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4487)

___

### WatchedPins

• **WatchedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPinReference`](ue_ue.EdGraphPinReference.md)\>

#### Defined in

[ue/ue.d.ts:4505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4505)

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[__tid_BlueprintCore__](ue_ue.BlueprintCore.md#__tid_blueprintcore__)

#### Defined in

[ue/ue.d.ts:4082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4082)

___

### \_\_tid\_Blueprint\_\_

• **\_\_tid\_Blueprint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4518)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[__tid_Object__](ue_ue.BlueprintCore.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bBeingCompiled

• **bBeingCompiled**: `boolean`

#### Defined in

[ue/ue.d.ts:4465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4465)

___

### bDeprecate

• **bDeprecate**: `boolean`

#### Defined in

[ue/ue.d.ts:4474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4474)

___

### bDisplayCompilePIEWarning

• **bDisplayCompilePIEWarning**: `boolean`

#### Defined in

[ue/ue.d.ts:4473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4473)

___

### bDuplicatingReadOnly

• **bDuplicatingReadOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:4475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4475)

___

### bForceFullEditor

• **bForceFullEditor**: `boolean`

#### Defined in

[ue/ue.d.ts:4467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4467)

___

### bGenerateAbstractClass

• **bGenerateAbstractClass**: `boolean`

#### Defined in

[ue/ue.d.ts:4472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4472)

___

### bGenerateConstClass

• **bGenerateConstClass**: `boolean`

#### Defined in

[ue/ue.d.ts:4471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4471)

___

### bHasBeenRegenerated

• **bHasBeenRegenerated**: `boolean`

#### Defined in

[ue/ue.d.ts:4463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4463)

___

### bIsNewlyCreated

• **bIsNewlyCreated**: `boolean`

#### Defined in

[ue/ue.d.ts:4466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4466)

___

### bIsRegeneratingOnLoad

• **bIsRegeneratingOnLoad**: `boolean`

#### Defined in

[ue/ue.d.ts:4464](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4464)

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[bLegacyNeedToPurgeSkelRefs](ue_ue.BlueprintCore.md#blegacyneedtopurgeskelrefs)

#### Defined in

[ue/ue.d.ts:4076](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4076)

___

### bNativize

• **bNativize**: `boolean`

#### Defined in

[ue/ue.d.ts:4476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4476)

___

### bQueuedForCompilation

• **bQueuedForCompilation**: `boolean`

#### Defined in

[ue/ue.d.ts:4468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4468)

___

### bRecompileOnLoad

• **bRecompileOnLoad**: `boolean`

#### Defined in

[ue/ue.d.ts:4462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4462)

___

### bRunConstructionScriptInSequencer

• **bRunConstructionScriptInSequencer**: `boolean`

#### Defined in

[ue/ue.d.ts:4470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4470)

___

### bRunConstructionScriptOnDrag

• **bRunConstructionScriptOnDrag**: `boolean`

#### Defined in

[ue/ue.d.ts:4469](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4469)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetClass](ue_ue.BlueprintCore.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetName](ue_ue.BlueprintCore.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetOuter](ue_ue.BlueprintCore.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintCore](ue_ue.BlueprintCore.md).[GetWorld](ue_ue.BlueprintCore.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:4515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4515)

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

#### Defined in

[ue/ue.d.ts:4516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4516)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintCore](ue_ue.BlueprintCore.md).[StaticClass](ue_ue.BlueprintCore.md#staticclass)

#### Defined in

[ue/ue.d.ts:4514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4514)
