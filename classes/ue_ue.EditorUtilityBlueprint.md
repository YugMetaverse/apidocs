[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorUtilityBlueprint

# Class: EditorUtilityBlueprint

[ue/ue](../modules/ue_ue.md).EditorUtilityBlueprint

## Hierarchy

- [`Blueprint`](ue_ue.Blueprint.md)

  ↳ **`EditorUtilityBlueprint`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorUtilityBlueprint.md#constructor)

### Properties

- [BlueprintCategory](ue_ue.EditorUtilityBlueprint.md#blueprintcategory)
- [BlueprintDescription](ue_ue.EditorUtilityBlueprint.md#blueprintdescription)
- [BlueprintDisplayName](ue_ue.EditorUtilityBlueprint.md#blueprintdisplayname)
- [BlueprintGuid](ue_ue.EditorUtilityBlueprint.md#blueprintguid)
- [BlueprintSystemVersion](ue_ue.EditorUtilityBlueprint.md#blueprintsystemversion)
- [BlueprintType](ue_ue.EditorUtilityBlueprint.md#blueprinttype)
- [BookmarkNodes](ue_ue.EditorUtilityBlueprint.md#bookmarknodes)
- [Bookmarks](ue_ue.EditorUtilityBlueprint.md#bookmarks)
- [Breakpoints](ue_ue.EditorUtilityBlueprint.md#breakpoints)
- [CategorySorting](ue_ue.EditorUtilityBlueprint.md#categorysorting)
- [CompileMode](ue_ue.EditorUtilityBlueprint.md#compilemode)
- [ComponentClassOverrides](ue_ue.EditorUtilityBlueprint.md#componentclassoverrides)
- [ComponentTemplateNameIndex](ue_ue.EditorUtilityBlueprint.md#componenttemplatenameindex)
- [ComponentTemplates](ue_ue.EditorUtilityBlueprint.md#componenttemplates)
- [CrcLastCompiledCDO](ue_ue.EditorUtilityBlueprint.md#crclastcompiledcdo)
- [CrcLastCompiledSignature](ue_ue.EditorUtilityBlueprint.md#crclastcompiledsignature)
- [DelegateSignatureGraphs](ue_ue.EditorUtilityBlueprint.md#delegatesignaturegraphs)
- [DeprecatedPinWatches](ue_ue.EditorUtilityBlueprint.md#deprecatedpinwatches)
- [EventGraphs](ue_ue.EditorUtilityBlueprint.md#eventgraphs)
- [Extensions](ue_ue.EditorUtilityBlueprint.md#extensions)
- [FunctionGraphs](ue_ue.EditorUtilityBlueprint.md#functiongraphs)
- [GeneratedClass](ue_ue.EditorUtilityBlueprint.md#generatedclass)
- [HideCategories](ue_ue.EditorUtilityBlueprint.md#hidecategories)
- [ImplementedInterfaces](ue_ue.EditorUtilityBlueprint.md#implementedinterfaces)
- [InheritableComponentHandler](ue_ue.EditorUtilityBlueprint.md#inheritablecomponenthandler)
- [IntermediateGeneratedGraphs](ue_ue.EditorUtilityBlueprint.md#intermediategeneratedgraphs)
- [LastEditedDocuments](ue_ue.EditorUtilityBlueprint.md#lastediteddocuments)
- [MacroGraphs](ue_ue.EditorUtilityBlueprint.md#macrographs)
- [NativizationFlag](ue_ue.EditorUtilityBlueprint.md#nativizationflag)
- [NewVariables](ue_ue.EditorUtilityBlueprint.md#newvariables)
- [OldToNewComponentTemplateNames](ue_ue.EditorUtilityBlueprint.md#oldtonewcomponenttemplatenames)
- [OriginalClass](ue_ue.EditorUtilityBlueprint.md#originalclass)
- [PRIVATE\_CachedMacroInfo](ue_ue.EditorUtilityBlueprint.md#private_cachedmacroinfo)
- [ParentClass](ue_ue.EditorUtilityBlueprint.md#parentclass)
- [SearchGuid](ue_ue.EditorUtilityBlueprint.md#searchguid)
- [SimpleConstructionScript](ue_ue.EditorUtilityBlueprint.md#simpleconstructionscript)
- [SkeletonGeneratedClass](ue_ue.EditorUtilityBlueprint.md#skeletongeneratedclass)
- [Status](ue_ue.EditorUtilityBlueprint.md#status)
- [ThumbnailInfo](ue_ue.EditorUtilityBlueprint.md#thumbnailinfo)
- [Timelines](ue_ue.EditorUtilityBlueprint.md#timelines)
- [UbergraphPages](ue_ue.EditorUtilityBlueprint.md#ubergraphpages)
- [WatchedPins](ue_ue.EditorUtilityBlueprint.md#watchedpins)
- [\_\_tid\_BlueprintCore\_\_](ue_ue.EditorUtilityBlueprint.md#__tid_blueprintcore__)
- [\_\_tid\_Blueprint\_\_](ue_ue.EditorUtilityBlueprint.md#__tid_blueprint__)
- [\_\_tid\_EditorUtilityBlueprint\_\_](ue_ue.EditorUtilityBlueprint.md#__tid_editorutilityblueprint__)
- [\_\_tid\_Object\_\_](ue_ue.EditorUtilityBlueprint.md#__tid_object__)
- [bBeingCompiled](ue_ue.EditorUtilityBlueprint.md#bbeingcompiled)
- [bDeprecate](ue_ue.EditorUtilityBlueprint.md#bdeprecate)
- [bDisplayCompilePIEWarning](ue_ue.EditorUtilityBlueprint.md#bdisplaycompilepiewarning)
- [bDuplicatingReadOnly](ue_ue.EditorUtilityBlueprint.md#bduplicatingreadonly)
- [bForceFullEditor](ue_ue.EditorUtilityBlueprint.md#bforcefulleditor)
- [bGenerateAbstractClass](ue_ue.EditorUtilityBlueprint.md#bgenerateabstractclass)
- [bGenerateConstClass](ue_ue.EditorUtilityBlueprint.md#bgenerateconstclass)
- [bHasBeenRegenerated](ue_ue.EditorUtilityBlueprint.md#bhasbeenregenerated)
- [bIsNewlyCreated](ue_ue.EditorUtilityBlueprint.md#bisnewlycreated)
- [bIsRegeneratingOnLoad](ue_ue.EditorUtilityBlueprint.md#bisregeneratingonload)
- [bLegacyNeedToPurgeSkelRefs](ue_ue.EditorUtilityBlueprint.md#blegacyneedtopurgeskelrefs)
- [bNativize](ue_ue.EditorUtilityBlueprint.md#bnativize)
- [bQueuedForCompilation](ue_ue.EditorUtilityBlueprint.md#bqueuedforcompilation)
- [bRecompileOnLoad](ue_ue.EditorUtilityBlueprint.md#brecompileonload)
- [bRunConstructionScriptInSequencer](ue_ue.EditorUtilityBlueprint.md#brunconstructionscriptinsequencer)
- [bRunConstructionScriptOnDrag](ue_ue.EditorUtilityBlueprint.md#brunconstructionscriptondrag)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorUtilityBlueprint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorUtilityBlueprint.md#executeubergraph)
- [GetClass](ue_ue.EditorUtilityBlueprint.md#getclass)
- [GetName](ue_ue.EditorUtilityBlueprint.md#getname)
- [GetOuter](ue_ue.EditorUtilityBlueprint.md#getouter)
- [GetWorld](ue_ue.EditorUtilityBlueprint.md#getworld)
- [Find](ue_ue.EditorUtilityBlueprint.md#find)
- [Load](ue_ue.EditorUtilityBlueprint.md#load)
- [StaticClass](ue_ue.EditorUtilityBlueprint.md#staticclass)

## Constructors

### constructor

• **new EditorUtilityBlueprint**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[constructor](ue_ue.Blueprint.md#constructor)

#### Defined in

[ue/ue.d.ts:33534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33534)

## Properties

### BlueprintCategory

• **BlueprintCategory**: `string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintCategory](ue_ue.Blueprint.md#blueprintcategory)

#### Defined in

[ue/ue.d.ts:4482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4482)

___

### BlueprintDescription

• **BlueprintDescription**: `string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintDescription](ue_ue.Blueprint.md#blueprintdescription)

#### Defined in

[ue/ue.d.ts:4481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4481)

___

### BlueprintDisplayName

• **BlueprintDisplayName**: `string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintDisplayName](ue_ue.Blueprint.md#blueprintdisplayname)

#### Defined in

[ue/ue.d.ts:4480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4480)

___

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintGuid](ue_ue.Blueprint.md#blueprintguid)

#### Defined in

[ue/ue.d.ts:4077](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4077)

___

### BlueprintSystemVersion

• **BlueprintSystemVersion**: `number`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintSystemVersion](ue_ue.Blueprint.md#blueprintsystemversion)

#### Defined in

[ue/ue.d.ts:4485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4485)

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BlueprintType](ue_ue.Blueprint.md#blueprinttype)

#### Defined in

[ue/ue.d.ts:4461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4461)

___

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[BookmarkNodes](ue_ue.Blueprint.md#bookmarknodes)

#### Defined in

[ue/ue.d.ts:4503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4503)

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Bookmarks](ue_ue.Blueprint.md#bookmarks)

#### Defined in

[ue/ue.d.ts:4502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4502)

___

### Breakpoints

• **Breakpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Breakpoint`](ue_ue.Breakpoint.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Breakpoints](ue_ue.Blueprint.md#breakpoints)

#### Defined in

[ue/ue.d.ts:4504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4504)

___

### CategorySorting

• **CategorySorting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CategorySorting](ue_ue.Blueprint.md#categorysorting)

#### Defined in

[ue/ue.d.ts:4499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4499)

___

### CompileMode

• **CompileMode**: [`EBlueprintCompileMode`](../enums/ue_ue.EBlueprintCompileMode.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CompileMode](ue_ue.Blueprint.md#compilemode)

#### Defined in

[ue/ue.d.ts:4478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4478)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ComponentClassOverrides](ue_ue.Blueprint.md#componentclassoverrides)

#### Defined in

[ue/ue.d.ts:4496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4496)

___

### ComponentTemplateNameIndex

• **ComponentTemplateNameIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ComponentTemplateNameIndex](ue_ue.Blueprint.md#componenttemplatenameindex)

#### Defined in

[ue/ue.d.ts:4507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4507)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ComponentTemplates](ue_ue.Blueprint.md#componenttemplates)

#### Defined in

[ue/ue.d.ts:4494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4494)

___

### CrcLastCompiledCDO

• **CrcLastCompiledCDO**: `number`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CrcLastCompiledCDO](ue_ue.Blueprint.md#crclastcompiledcdo)

#### Defined in

[ue/ue.d.ts:4511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4511)

___

### CrcLastCompiledSignature

• **CrcLastCompiledSignature**: `number`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[CrcLastCompiledSignature](ue_ue.Blueprint.md#crclastcompiledsignature)

#### Defined in

[ue/ue.d.ts:4512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4512)

___

### DelegateSignatureGraphs

• **DelegateSignatureGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[DelegateSignatureGraphs](ue_ue.Blueprint.md#delegatesignaturegraphs)

#### Defined in

[ue/ue.d.ts:4489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4489)

___

### DeprecatedPinWatches

• **DeprecatedPinWatches**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[DeprecatedPinWatches](ue_ue.Blueprint.md#deprecatedpinwatches)

#### Defined in

[ue/ue.d.ts:4506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4506)

___

### EventGraphs

• **EventGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[EventGraphs](ue_ue.Blueprint.md#eventgraphs)

#### Defined in

[ue/ue.d.ts:4492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4492)

___

### Extensions

• **Extensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintExtension`](ue_ue.BlueprintExtension.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Extensions](ue_ue.Blueprint.md#extensions)

#### Defined in

[ue/ue.d.ts:4509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4509)

___

### FunctionGraphs

• **FunctionGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[FunctionGraphs](ue_ue.Blueprint.md#functiongraphs)

#### Defined in

[ue/ue.d.ts:4488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4488)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GeneratedClass](ue_ue.Blueprint.md#generatedclass)

#### Defined in

[ue/ue.d.ts:4075](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4075)

___

### HideCategories

• **HideCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[HideCategories](ue_ue.Blueprint.md#hidecategories)

#### Defined in

[ue/ue.d.ts:4483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4483)

___

### ImplementedInterfaces

• **ImplementedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPInterfaceDescription`](ue_ue.BPInterfaceDescription.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ImplementedInterfaces](ue_ue.Blueprint.md#implementedinterfaces)

#### Defined in

[ue/ue.d.ts:4500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4500)

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[InheritableComponentHandler](ue_ue.Blueprint.md#inheritablecomponenthandler)

#### Defined in

[ue/ue.d.ts:4497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4497)

___

### IntermediateGeneratedGraphs

• **IntermediateGeneratedGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[IntermediateGeneratedGraphs](ue_ue.Blueprint.md#intermediategeneratedgraphs)

#### Defined in

[ue/ue.d.ts:4491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4491)

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[LastEditedDocuments](ue_ue.Blueprint.md#lastediteddocuments)

#### Defined in

[ue/ue.d.ts:4501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4501)

___

### MacroGraphs

• **MacroGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[MacroGraphs](ue_ue.Blueprint.md#macrographs)

#### Defined in

[ue/ue.d.ts:4490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4490)

___

### NativizationFlag

• **NativizationFlag**: [`EBlueprintNativizationFlag`](../enums/ue_ue.EBlueprintNativizationFlag.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[NativizationFlag](ue_ue.Blueprint.md#nativizationflag)

#### Defined in

[ue/ue.d.ts:4477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4477)

___

### NewVariables

• **NewVariables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableDescription`](ue_ue.BPVariableDescription.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[NewVariables](ue_ue.Blueprint.md#newvariables)

#### Defined in

[ue/ue.d.ts:4498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4498)

___

### OldToNewComponentTemplateNames

• **OldToNewComponentTemplateNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[OldToNewComponentTemplateNames](ue_ue.Blueprint.md#oldtonewcomponenttemplatenames)

#### Defined in

[ue/ue.d.ts:4508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4508)

___

### OriginalClass

• **OriginalClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[OriginalClass](ue_ue.Blueprint.md#originalclass)

#### Defined in

[ue/ue.d.ts:4513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4513)

___

### PRIVATE\_CachedMacroInfo

• **PRIVATE\_CachedMacroInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EdGraph`](ue_ue.EdGraph.md), [`BlueprintMacroCosmeticInfo`](ue_ue.BlueprintMacroCosmeticInfo.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[PRIVATE_CachedMacroInfo](ue_ue.Blueprint.md#private_cachedmacroinfo)

#### Defined in

[ue/ue.d.ts:4493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4493)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ParentClass](ue_ue.Blueprint.md#parentclass)

#### Defined in

[ue/ue.d.ts:4460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4460)

___

### SearchGuid

• **SearchGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[SearchGuid](ue_ue.Blueprint.md#searchguid)

#### Defined in

[ue/ue.d.ts:4484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4484)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[SimpleConstructionScript](ue_ue.Blueprint.md#simpleconstructionscript)

#### Defined in

[ue/ue.d.ts:4486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4486)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[SkeletonGeneratedClass](ue_ue.Blueprint.md#skeletongeneratedclass)

#### Defined in

[ue/ue.d.ts:4074](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4074)

___

### Status

• **Status**: [`EBlueprintStatus`](../enums/ue_ue.EBlueprintStatus.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Status](ue_ue.Blueprint.md#status)

#### Defined in

[ue/ue.d.ts:4479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4479)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[ThumbnailInfo](ue_ue.Blueprint.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:4510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4510)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[Timelines](ue_ue.Blueprint.md#timelines)

#### Defined in

[ue/ue.d.ts:4495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4495)

___

### UbergraphPages

• **UbergraphPages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[UbergraphPages](ue_ue.Blueprint.md#ubergraphpages)

#### Defined in

[ue/ue.d.ts:4487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4487)

___

### WatchedPins

• **WatchedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPinReference`](ue_ue.EdGraphPinReference.md)\>

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[WatchedPins](ue_ue.Blueprint.md#watchedpins)

#### Defined in

[ue/ue.d.ts:4505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4505)

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[__tid_BlueprintCore__](ue_ue.Blueprint.md#__tid_blueprintcore__)

#### Defined in

[ue/ue.d.ts:4082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4082)

___

### \_\_tid\_Blueprint\_\_

• **\_\_tid\_Blueprint\_\_**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[__tid_Blueprint__](ue_ue.Blueprint.md#__tid_blueprint__)

#### Defined in

[ue/ue.d.ts:4518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4518)

___

### \_\_tid\_EditorUtilityBlueprint\_\_

• **\_\_tid\_EditorUtilityBlueprint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33539)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[__tid_Object__](ue_ue.Blueprint.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bBeingCompiled

• **bBeingCompiled**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bBeingCompiled](ue_ue.Blueprint.md#bbeingcompiled)

#### Defined in

[ue/ue.d.ts:4465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4465)

___

### bDeprecate

• **bDeprecate**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bDeprecate](ue_ue.Blueprint.md#bdeprecate)

#### Defined in

[ue/ue.d.ts:4474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4474)

___

### bDisplayCompilePIEWarning

• **bDisplayCompilePIEWarning**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bDisplayCompilePIEWarning](ue_ue.Blueprint.md#bdisplaycompilepiewarning)

#### Defined in

[ue/ue.d.ts:4473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4473)

___

### bDuplicatingReadOnly

• **bDuplicatingReadOnly**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bDuplicatingReadOnly](ue_ue.Blueprint.md#bduplicatingreadonly)

#### Defined in

[ue/ue.d.ts:4475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4475)

___

### bForceFullEditor

• **bForceFullEditor**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bForceFullEditor](ue_ue.Blueprint.md#bforcefulleditor)

#### Defined in

[ue/ue.d.ts:4467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4467)

___

### bGenerateAbstractClass

• **bGenerateAbstractClass**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bGenerateAbstractClass](ue_ue.Blueprint.md#bgenerateabstractclass)

#### Defined in

[ue/ue.d.ts:4472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4472)

___

### bGenerateConstClass

• **bGenerateConstClass**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bGenerateConstClass](ue_ue.Blueprint.md#bgenerateconstclass)

#### Defined in

[ue/ue.d.ts:4471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4471)

___

### bHasBeenRegenerated

• **bHasBeenRegenerated**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bHasBeenRegenerated](ue_ue.Blueprint.md#bhasbeenregenerated)

#### Defined in

[ue/ue.d.ts:4463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4463)

___

### bIsNewlyCreated

• **bIsNewlyCreated**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bIsNewlyCreated](ue_ue.Blueprint.md#bisnewlycreated)

#### Defined in

[ue/ue.d.ts:4466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4466)

___

### bIsRegeneratingOnLoad

• **bIsRegeneratingOnLoad**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bIsRegeneratingOnLoad](ue_ue.Blueprint.md#bisregeneratingonload)

#### Defined in

[ue/ue.d.ts:4464](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4464)

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bLegacyNeedToPurgeSkelRefs](ue_ue.Blueprint.md#blegacyneedtopurgeskelrefs)

#### Defined in

[ue/ue.d.ts:4076](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4076)

___

### bNativize

• **bNativize**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bNativize](ue_ue.Blueprint.md#bnativize)

#### Defined in

[ue/ue.d.ts:4476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4476)

___

### bQueuedForCompilation

• **bQueuedForCompilation**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bQueuedForCompilation](ue_ue.Blueprint.md#bqueuedforcompilation)

#### Defined in

[ue/ue.d.ts:4468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4468)

___

### bRecompileOnLoad

• **bRecompileOnLoad**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bRecompileOnLoad](ue_ue.Blueprint.md#brecompileonload)

#### Defined in

[ue/ue.d.ts:4462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4462)

___

### bRunConstructionScriptInSequencer

• **bRunConstructionScriptInSequencer**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bRunConstructionScriptInSequencer](ue_ue.Blueprint.md#brunconstructionscriptinsequencer)

#### Defined in

[ue/ue.d.ts:4470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4470)

___

### bRunConstructionScriptOnDrag

• **bRunConstructionScriptOnDrag**: `boolean`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[bRunConstructionScriptOnDrag](ue_ue.Blueprint.md#brunconstructionscriptondrag)

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

[Blueprint](ue_ue.Blueprint.md).[CreateDefaultSubobject](ue_ue.Blueprint.md#createdefaultsubobject)

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

[Blueprint](ue_ue.Blueprint.md).[ExecuteUbergraph](ue_ue.Blueprint.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetClass](ue_ue.Blueprint.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetName](ue_ue.Blueprint.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetOuter](ue_ue.Blueprint.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Blueprint](ue_ue.Blueprint.md).[GetWorld](ue_ue.Blueprint.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorUtilityBlueprint`](ue_ue.EditorUtilityBlueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorUtilityBlueprint`](ue_ue.EditorUtilityBlueprint.md)

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[Find](ue_ue.Blueprint.md#find)

#### Defined in

[ue/ue.d.ts:33536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33536)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorUtilityBlueprint`](ue_ue.EditorUtilityBlueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorUtilityBlueprint`](ue_ue.EditorUtilityBlueprint.md)

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[Load](ue_ue.Blueprint.md#load)

#### Defined in

[ue/ue.d.ts:33537](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33537)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Blueprint](ue_ue.Blueprint.md).[StaticClass](ue_ue.Blueprint.md#staticclass)

#### Defined in

[ue/ue.d.ts:33535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33535)
