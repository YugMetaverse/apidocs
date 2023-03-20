[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetBlueprint

# Class: WidgetBlueprint

[ue/ue](../modules/ue_ue.md).WidgetBlueprint

## Hierarchy

- [`BaseWidgetBlueprint`](ue_ue.BaseWidgetBlueprint.md)

  ↳ **`WidgetBlueprint`**

  ↳↳ [`EditorUtilityWidgetBlueprint`](ue_ue.EditorUtilityWidgetBlueprint.md)

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetBlueprint.md#constructor)

### Properties

- [AnimationData](ue_ue.WidgetBlueprint.md#animationdata)
- [Animations](ue_ue.WidgetBlueprint.md#animations)
- [Bindings](ue_ue.WidgetBlueprint.md#bindings)
- [BlueprintCategory](ue_ue.WidgetBlueprint.md#blueprintcategory)
- [BlueprintDescription](ue_ue.WidgetBlueprint.md#blueprintdescription)
- [BlueprintDisplayName](ue_ue.WidgetBlueprint.md#blueprintdisplayname)
- [BlueprintGuid](ue_ue.WidgetBlueprint.md#blueprintguid)
- [BlueprintSystemVersion](ue_ue.WidgetBlueprint.md#blueprintsystemversion)
- [BlueprintType](ue_ue.WidgetBlueprint.md#blueprinttype)
- [BookmarkNodes](ue_ue.WidgetBlueprint.md#bookmarknodes)
- [Bookmarks](ue_ue.WidgetBlueprint.md#bookmarks)
- [Breakpoints](ue_ue.WidgetBlueprint.md#breakpoints)
- [CategorySorting](ue_ue.WidgetBlueprint.md#categorysorting)
- [CompileMode](ue_ue.WidgetBlueprint.md#compilemode)
- [ComponentClassOverrides](ue_ue.WidgetBlueprint.md#componentclassoverrides)
- [ComponentTemplateNameIndex](ue_ue.WidgetBlueprint.md#componenttemplatenameindex)
- [ComponentTemplates](ue_ue.WidgetBlueprint.md#componenttemplates)
- [CrcLastCompiledCDO](ue_ue.WidgetBlueprint.md#crclastcompiledcdo)
- [CrcLastCompiledSignature](ue_ue.WidgetBlueprint.md#crclastcompiledsignature)
- [DelegateSignatureGraphs](ue_ue.WidgetBlueprint.md#delegatesignaturegraphs)
- [DeprecatedPinWatches](ue_ue.WidgetBlueprint.md#deprecatedpinwatches)
- [EstimatedTemplateSize](ue_ue.WidgetBlueprint.md#estimatedtemplatesize)
- [EventGraphs](ue_ue.WidgetBlueprint.md#eventgraphs)
- [Extensions](ue_ue.WidgetBlueprint.md#extensions)
- [FunctionGraphs](ue_ue.WidgetBlueprint.md#functiongraphs)
- [GeneratedClass](ue_ue.WidgetBlueprint.md#generatedclass)
- [HideCategories](ue_ue.WidgetBlueprint.md#hidecategories)
- [ImplementedInterfaces](ue_ue.WidgetBlueprint.md#implementedinterfaces)
- [InclusiveWidgets](ue_ue.WidgetBlueprint.md#inclusivewidgets)
- [InheritableComponentHandler](ue_ue.WidgetBlueprint.md#inheritablecomponenthandler)
- [IntermediateGeneratedGraphs](ue_ue.WidgetBlueprint.md#intermediategeneratedgraphs)
- [LastEditedDocuments](ue_ue.WidgetBlueprint.md#lastediteddocuments)
- [MacroGraphs](ue_ue.WidgetBlueprint.md#macrographs)
- [NativizationFlag](ue_ue.WidgetBlueprint.md#nativizationflag)
- [NewVariables](ue_ue.WidgetBlueprint.md#newvariables)
- [OldToNewComponentTemplateNames](ue_ue.WidgetBlueprint.md#oldtonewcomponenttemplatenames)
- [OriginalClass](ue_ue.WidgetBlueprint.md#originalclass)
- [PRIVATE\_CachedMacroInfo](ue_ue.WidgetBlueprint.md#private_cachedmacroinfo)
- [PaletteCategory](ue_ue.WidgetBlueprint.md#palettecategory)
- [ParentClass](ue_ue.WidgetBlueprint.md#parentclass)
- [PropertyBindings](ue_ue.WidgetBlueprint.md#propertybindings)
- [SearchGuid](ue_ue.WidgetBlueprint.md#searchguid)
- [SimpleConstructionScript](ue_ue.WidgetBlueprint.md#simpleconstructionscript)
- [SkeletonGeneratedClass](ue_ue.WidgetBlueprint.md#skeletongeneratedclass)
- [Status](ue_ue.WidgetBlueprint.md#status)
- [SupportDynamicCreation](ue_ue.WidgetBlueprint.md#supportdynamiccreation)
- [ThumbnailInfo](ue_ue.WidgetBlueprint.md#thumbnailinfo)
- [TickFrequency](ue_ue.WidgetBlueprint.md#tickfrequency)
- [TickPrediction](ue_ue.WidgetBlueprint.md#tickprediction)
- [TickPredictionReason](ue_ue.WidgetBlueprint.md#tickpredictionreason)
- [Timelines](ue_ue.WidgetBlueprint.md#timelines)
- [UbergraphPages](ue_ue.WidgetBlueprint.md#ubergraphpages)
- [WatchedPins](ue_ue.WidgetBlueprint.md#watchedpins)
- [WidgetTree](ue_ue.WidgetBlueprint.md#widgettree)
- [\_\_tid\_BaseWidgetBlueprint\_\_](ue_ue.WidgetBlueprint.md#__tid_basewidgetblueprint__)
- [\_\_tid\_BlueprintCore\_\_](ue_ue.WidgetBlueprint.md#__tid_blueprintcore__)
- [\_\_tid\_Blueprint\_\_](ue_ue.WidgetBlueprint.md#__tid_blueprint__)
- [\_\_tid\_Object\_\_](ue_ue.WidgetBlueprint.md#__tid_object__)
- [\_\_tid\_WidgetBlueprint\_\_](ue_ue.WidgetBlueprint.md#__tid_widgetblueprint__)
- [bBeingCompiled](ue_ue.WidgetBlueprint.md#bbeingcompiled)
- [bDeprecate](ue_ue.WidgetBlueprint.md#bdeprecate)
- [bDisplayCompilePIEWarning](ue_ue.WidgetBlueprint.md#bdisplaycompilepiewarning)
- [bDuplicatingReadOnly](ue_ue.WidgetBlueprint.md#bduplicatingreadonly)
- [bForceFullEditor](ue_ue.WidgetBlueprint.md#bforcefulleditor)
- [bForceSlowConstructionPath](ue_ue.WidgetBlueprint.md#bforceslowconstructionpath)
- [bGenerateAbstractClass](ue_ue.WidgetBlueprint.md#bgenerateabstractclass)
- [bGenerateConstClass](ue_ue.WidgetBlueprint.md#bgenerateconstclass)
- [bHasBeenRegenerated](ue_ue.WidgetBlueprint.md#bhasbeenregenerated)
- [bIsNewlyCreated](ue_ue.WidgetBlueprint.md#bisnewlycreated)
- [bIsRegeneratingOnLoad](ue_ue.WidgetBlueprint.md#bisregeneratingonload)
- [bLegacyNeedToPurgeSkelRefs](ue_ue.WidgetBlueprint.md#blegacyneedtopurgeskelrefs)
- [bNativize](ue_ue.WidgetBlueprint.md#bnativize)
- [bQueuedForCompilation](ue_ue.WidgetBlueprint.md#bqueuedforcompilation)
- [bRecompileOnLoad](ue_ue.WidgetBlueprint.md#brecompileonload)
- [bRunConstructionScriptInSequencer](ue_ue.WidgetBlueprint.md#brunconstructionscriptinsequencer)
- [bRunConstructionScriptOnDrag](ue_ue.WidgetBlueprint.md#brunconstructionscriptondrag)

### Methods

- [CreateDefaultSubobject](ue_ue.WidgetBlueprint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WidgetBlueprint.md#executeubergraph)
- [GetClass](ue_ue.WidgetBlueprint.md#getclass)
- [GetName](ue_ue.WidgetBlueprint.md#getname)
- [GetOuter](ue_ue.WidgetBlueprint.md#getouter)
- [GetWorld](ue_ue.WidgetBlueprint.md#getworld)
- [Find](ue_ue.WidgetBlueprint.md#find)
- [Load](ue_ue.WidgetBlueprint.md#load)
- [StaticClass](ue_ue.WidgetBlueprint.md#staticclass)

## Constructors

### constructor

• **new WidgetBlueprint**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[constructor](ue_ue.BaseWidgetBlueprint.md#constructor)

#### Defined in

[ue/ue.d.ts:33647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33647)

## Properties

### AnimationData

• **AnimationData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimation_DEPRECATED`](ue_ue.WidgetAnimation_DEPRECATED.md)\>

#### Defined in

[ue/ue.d.ts:33649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33649)

___

### Animations

• **Animations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\>

#### Defined in

[ue/ue.d.ts:33650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33650)

___

### Bindings

• **Bindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateEditorBinding`](ue_ue.DelegateEditorBinding.md)\>

#### Defined in

[ue/ue.d.ts:33648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33648)

___

### BlueprintCategory

• **BlueprintCategory**: `string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintCategory](ue_ue.BaseWidgetBlueprint.md#blueprintcategory)

#### Defined in

[ue/ue.d.ts:4482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4482)

___

### BlueprintDescription

• **BlueprintDescription**: `string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintDescription](ue_ue.BaseWidgetBlueprint.md#blueprintdescription)

#### Defined in

[ue/ue.d.ts:4481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4481)

___

### BlueprintDisplayName

• **BlueprintDisplayName**: `string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintDisplayName](ue_ue.BaseWidgetBlueprint.md#blueprintdisplayname)

#### Defined in

[ue/ue.d.ts:4480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4480)

___

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintGuid](ue_ue.BaseWidgetBlueprint.md#blueprintguid)

#### Defined in

[ue/ue.d.ts:4077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4077)

___

### BlueprintSystemVersion

• **BlueprintSystemVersion**: `number`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintSystemVersion](ue_ue.BaseWidgetBlueprint.md#blueprintsystemversion)

#### Defined in

[ue/ue.d.ts:4485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4485)

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintType](ue_ue.BaseWidgetBlueprint.md#blueprinttype)

#### Defined in

[ue/ue.d.ts:4461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4461)

___

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BookmarkNodes](ue_ue.BaseWidgetBlueprint.md#bookmarknodes)

#### Defined in

[ue/ue.d.ts:4503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4503)

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Bookmarks](ue_ue.BaseWidgetBlueprint.md#bookmarks)

#### Defined in

[ue/ue.d.ts:4502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4502)

___

### Breakpoints

• **Breakpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Breakpoint`](ue_ue.Breakpoint.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Breakpoints](ue_ue.BaseWidgetBlueprint.md#breakpoints)

#### Defined in

[ue/ue.d.ts:4504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4504)

___

### CategorySorting

• **CategorySorting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CategorySorting](ue_ue.BaseWidgetBlueprint.md#categorysorting)

#### Defined in

[ue/ue.d.ts:4499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4499)

___

### CompileMode

• **CompileMode**: [`EBlueprintCompileMode`](../enums/ue_ue.EBlueprintCompileMode.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CompileMode](ue_ue.BaseWidgetBlueprint.md#compilemode)

#### Defined in

[ue/ue.d.ts:4478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4478)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ComponentClassOverrides](ue_ue.BaseWidgetBlueprint.md#componentclassoverrides)

#### Defined in

[ue/ue.d.ts:4496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4496)

___

### ComponentTemplateNameIndex

• **ComponentTemplateNameIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ComponentTemplateNameIndex](ue_ue.BaseWidgetBlueprint.md#componenttemplatenameindex)

#### Defined in

[ue/ue.d.ts:4507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4507)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ComponentTemplates](ue_ue.BaseWidgetBlueprint.md#componenttemplates)

#### Defined in

[ue/ue.d.ts:4494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4494)

___

### CrcLastCompiledCDO

• **CrcLastCompiledCDO**: `number`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CrcLastCompiledCDO](ue_ue.BaseWidgetBlueprint.md#crclastcompiledcdo)

#### Defined in

[ue/ue.d.ts:4511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4511)

___

### CrcLastCompiledSignature

• **CrcLastCompiledSignature**: `number`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CrcLastCompiledSignature](ue_ue.BaseWidgetBlueprint.md#crclastcompiledsignature)

#### Defined in

[ue/ue.d.ts:4512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4512)

___

### DelegateSignatureGraphs

• **DelegateSignatureGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[DelegateSignatureGraphs](ue_ue.BaseWidgetBlueprint.md#delegatesignaturegraphs)

#### Defined in

[ue/ue.d.ts:4489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4489)

___

### DeprecatedPinWatches

• **DeprecatedPinWatches**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[DeprecatedPinWatches](ue_ue.BaseWidgetBlueprint.md#deprecatedpinwatches)

#### Defined in

[ue/ue.d.ts:4506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4506)

___

### EstimatedTemplateSize

• **EstimatedTemplateSize**: `number`

#### Defined in

[ue/ue.d.ts:33655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33655)

___

### EventGraphs

• **EventGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[EventGraphs](ue_ue.BaseWidgetBlueprint.md#eventgraphs)

#### Defined in

[ue/ue.d.ts:4492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4492)

___

### Extensions

• **Extensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintExtension`](ue_ue.BlueprintExtension.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Extensions](ue_ue.BaseWidgetBlueprint.md#extensions)

#### Defined in

[ue/ue.d.ts:4509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4509)

___

### FunctionGraphs

• **FunctionGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[FunctionGraphs](ue_ue.BaseWidgetBlueprint.md#functiongraphs)

#### Defined in

[ue/ue.d.ts:4488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4488)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GeneratedClass](ue_ue.BaseWidgetBlueprint.md#generatedclass)

#### Defined in

[ue/ue.d.ts:4075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4075)

___

### HideCategories

• **HideCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[HideCategories](ue_ue.BaseWidgetBlueprint.md#hidecategories)

#### Defined in

[ue/ue.d.ts:4483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4483)

___

### ImplementedInterfaces

• **ImplementedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPInterfaceDescription`](ue_ue.BPInterfaceDescription.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ImplementedInterfaces](ue_ue.BaseWidgetBlueprint.md#implementedinterfaces)

#### Defined in

[ue/ue.d.ts:4500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4500)

___

### InclusiveWidgets

• **InclusiveWidgets**: `number`

#### Defined in

[ue/ue.d.ts:33654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33654)

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[InheritableComponentHandler](ue_ue.BaseWidgetBlueprint.md#inheritablecomponenthandler)

#### Defined in

[ue/ue.d.ts:4497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4497)

___

### IntermediateGeneratedGraphs

• **IntermediateGeneratedGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[IntermediateGeneratedGraphs](ue_ue.BaseWidgetBlueprint.md#intermediategeneratedgraphs)

#### Defined in

[ue/ue.d.ts:4491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4491)

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[LastEditedDocuments](ue_ue.BaseWidgetBlueprint.md#lastediteddocuments)

#### Defined in

[ue/ue.d.ts:4501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4501)

___

### MacroGraphs

• **MacroGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[MacroGraphs](ue_ue.BaseWidgetBlueprint.md#macrographs)

#### Defined in

[ue/ue.d.ts:4490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4490)

___

### NativizationFlag

• **NativizationFlag**: [`EBlueprintNativizationFlag`](../enums/ue_ue.EBlueprintNativizationFlag.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[NativizationFlag](ue_ue.BaseWidgetBlueprint.md#nativizationflag)

#### Defined in

[ue/ue.d.ts:4477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4477)

___

### NewVariables

• **NewVariables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableDescription`](ue_ue.BPVariableDescription.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[NewVariables](ue_ue.BaseWidgetBlueprint.md#newvariables)

#### Defined in

[ue/ue.d.ts:4498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4498)

___

### OldToNewComponentTemplateNames

• **OldToNewComponentTemplateNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[OldToNewComponentTemplateNames](ue_ue.BaseWidgetBlueprint.md#oldtonewcomponenttemplatenames)

#### Defined in

[ue/ue.d.ts:4508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4508)

___

### OriginalClass

• **OriginalClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[OriginalClass](ue_ue.BaseWidgetBlueprint.md#originalclass)

#### Defined in

[ue/ue.d.ts:4513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4513)

___

### PRIVATE\_CachedMacroInfo

• **PRIVATE\_CachedMacroInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EdGraph`](ue_ue.EdGraph.md), [`BlueprintMacroCosmeticInfo`](ue_ue.BlueprintMacroCosmeticInfo.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[PRIVATE_CachedMacroInfo](ue_ue.BaseWidgetBlueprint.md#private_cachedmacroinfo)

#### Defined in

[ue/ue.d.ts:4493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4493)

___

### PaletteCategory

• **PaletteCategory**: `string`

#### Defined in

[ue/ue.d.ts:33651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33651)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ParentClass](ue_ue.BaseWidgetBlueprint.md#parentclass)

#### Defined in

[ue/ue.d.ts:4460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4460)

___

### PropertyBindings

• **PropertyBindings**: `number`

#### Defined in

[ue/ue.d.ts:33659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33659)

___

### SearchGuid

• **SearchGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[SearchGuid](ue_ue.BaseWidgetBlueprint.md#searchguid)

#### Defined in

[ue/ue.d.ts:4484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4484)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[SimpleConstructionScript](ue_ue.BaseWidgetBlueprint.md#simpleconstructionscript)

#### Defined in

[ue/ue.d.ts:4486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4486)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[SkeletonGeneratedClass](ue_ue.BaseWidgetBlueprint.md#skeletongeneratedclass)

#### Defined in

[ue/ue.d.ts:4074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4074)

___

### Status

• **Status**: [`EBlueprintStatus`](../enums/ue_ue.EBlueprintStatus.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Status](ue_ue.BaseWidgetBlueprint.md#status)

#### Defined in

[ue/ue.d.ts:4479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4479)

___

### SupportDynamicCreation

• **SupportDynamicCreation**: [`EWidgetSupportsDynamicCreation`](../enums/ue_ue.EWidgetSupportsDynamicCreation.md)

#### Defined in

[ue/ue.d.ts:33653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33653)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ThumbnailInfo](ue_ue.BaseWidgetBlueprint.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:4510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4510)

___

### TickFrequency

• **TickFrequency**: [`EWidgetTickFrequency`](../enums/ue_ue.EWidgetTickFrequency.md)

#### Defined in

[ue/ue.d.ts:33656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33656)

___

### TickPrediction

• **TickPrediction**: [`EWidgetCompileTimeTickPrediction`](../enums/ue_ue.EWidgetCompileTimeTickPrediction.md)

#### Defined in

[ue/ue.d.ts:33657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33657)

___

### TickPredictionReason

• **TickPredictionReason**: `string`

#### Defined in

[ue/ue.d.ts:33658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33658)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Timelines](ue_ue.BaseWidgetBlueprint.md#timelines)

#### Defined in

[ue/ue.d.ts:4495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4495)

___

### UbergraphPages

• **UbergraphPages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[UbergraphPages](ue_ue.BaseWidgetBlueprint.md#ubergraphpages)

#### Defined in

[ue/ue.d.ts:4487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4487)

___

### WatchedPins

• **WatchedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPinReference`](ue_ue.EdGraphPinReference.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[WatchedPins](ue_ue.BaseWidgetBlueprint.md#watchedpins)

#### Defined in

[ue/ue.d.ts:4505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4505)

___

### WidgetTree

• **WidgetTree**: [`WidgetTree`](ue_ue.WidgetTree.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[WidgetTree](ue_ue.BaseWidgetBlueprint.md#widgettree)

#### Defined in

[ue/ue.d.ts:23518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23518)

___

### \_\_tid\_BaseWidgetBlueprint\_\_

• **\_\_tid\_BaseWidgetBlueprint\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_BaseWidgetBlueprint__](ue_ue.BaseWidgetBlueprint.md#__tid_basewidgetblueprint__)

#### Defined in

[ue/ue.d.ts:23523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23523)

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_BlueprintCore__](ue_ue.BaseWidgetBlueprint.md#__tid_blueprintcore__)

#### Defined in

[ue/ue.d.ts:4082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4082)

___

### \_\_tid\_Blueprint\_\_

• **\_\_tid\_Blueprint\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_Blueprint__](ue_ue.BaseWidgetBlueprint.md#__tid_blueprint__)

#### Defined in

[ue/ue.d.ts:4518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4518)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_Object__](ue_ue.BaseWidgetBlueprint.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_WidgetBlueprint\_\_

• **\_\_tid\_WidgetBlueprint\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33664)

___

### bBeingCompiled

• **bBeingCompiled**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bBeingCompiled](ue_ue.BaseWidgetBlueprint.md#bbeingcompiled)

#### Defined in

[ue/ue.d.ts:4465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4465)

___

### bDeprecate

• **bDeprecate**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bDeprecate](ue_ue.BaseWidgetBlueprint.md#bdeprecate)

#### Defined in

[ue/ue.d.ts:4474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4474)

___

### bDisplayCompilePIEWarning

• **bDisplayCompilePIEWarning**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bDisplayCompilePIEWarning](ue_ue.BaseWidgetBlueprint.md#bdisplaycompilepiewarning)

#### Defined in

[ue/ue.d.ts:4473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4473)

___

### bDuplicatingReadOnly

• **bDuplicatingReadOnly**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bDuplicatingReadOnly](ue_ue.BaseWidgetBlueprint.md#bduplicatingreadonly)

#### Defined in

[ue/ue.d.ts:4475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4475)

___

### bForceFullEditor

• **bForceFullEditor**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bForceFullEditor](ue_ue.BaseWidgetBlueprint.md#bforcefulleditor)

#### Defined in

[ue/ue.d.ts:4467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4467)

___

### bForceSlowConstructionPath

• **bForceSlowConstructionPath**: `boolean`

#### Defined in

[ue/ue.d.ts:33652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33652)

___

### bGenerateAbstractClass

• **bGenerateAbstractClass**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bGenerateAbstractClass](ue_ue.BaseWidgetBlueprint.md#bgenerateabstractclass)

#### Defined in

[ue/ue.d.ts:4472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4472)

___

### bGenerateConstClass

• **bGenerateConstClass**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bGenerateConstClass](ue_ue.BaseWidgetBlueprint.md#bgenerateconstclass)

#### Defined in

[ue/ue.d.ts:4471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4471)

___

### bHasBeenRegenerated

• **bHasBeenRegenerated**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bHasBeenRegenerated](ue_ue.BaseWidgetBlueprint.md#bhasbeenregenerated)

#### Defined in

[ue/ue.d.ts:4463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4463)

___

### bIsNewlyCreated

• **bIsNewlyCreated**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bIsNewlyCreated](ue_ue.BaseWidgetBlueprint.md#bisnewlycreated)

#### Defined in

[ue/ue.d.ts:4466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4466)

___

### bIsRegeneratingOnLoad

• **bIsRegeneratingOnLoad**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bIsRegeneratingOnLoad](ue_ue.BaseWidgetBlueprint.md#bisregeneratingonload)

#### Defined in

[ue/ue.d.ts:4464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4464)

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bLegacyNeedToPurgeSkelRefs](ue_ue.BaseWidgetBlueprint.md#blegacyneedtopurgeskelrefs)

#### Defined in

[ue/ue.d.ts:4076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4076)

___

### bNativize

• **bNativize**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bNativize](ue_ue.BaseWidgetBlueprint.md#bnativize)

#### Defined in

[ue/ue.d.ts:4476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4476)

___

### bQueuedForCompilation

• **bQueuedForCompilation**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bQueuedForCompilation](ue_ue.BaseWidgetBlueprint.md#bqueuedforcompilation)

#### Defined in

[ue/ue.d.ts:4468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4468)

___

### bRecompileOnLoad

• **bRecompileOnLoad**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bRecompileOnLoad](ue_ue.BaseWidgetBlueprint.md#brecompileonload)

#### Defined in

[ue/ue.d.ts:4462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4462)

___

### bRunConstructionScriptInSequencer

• **bRunConstructionScriptInSequencer**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bRunConstructionScriptInSequencer](ue_ue.BaseWidgetBlueprint.md#brunconstructionscriptinsequencer)

#### Defined in

[ue/ue.d.ts:4470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4470)

___

### bRunConstructionScriptOnDrag

• **bRunConstructionScriptOnDrag**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bRunConstructionScriptOnDrag](ue_ue.BaseWidgetBlueprint.md#brunconstructionscriptondrag)

#### Defined in

[ue/ue.d.ts:4469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4469)

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

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CreateDefaultSubobject](ue_ue.BaseWidgetBlueprint.md#createdefaultsubobject)

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

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ExecuteUbergraph](ue_ue.BaseWidgetBlueprint.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetClass](ue_ue.BaseWidgetBlueprint.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetName](ue_ue.BaseWidgetBlueprint.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetOuter](ue_ue.BaseWidgetBlueprint.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetWorld](ue_ue.BaseWidgetBlueprint.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WidgetBlueprint`](ue_ue.WidgetBlueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WidgetBlueprint`](ue_ue.WidgetBlueprint.md)

#### Overrides

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Find](ue_ue.BaseWidgetBlueprint.md#find)

#### Defined in

[ue/ue.d.ts:33661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33661)

___

### Load

▸ `Static` **Load**(`InName`): [`WidgetBlueprint`](ue_ue.WidgetBlueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WidgetBlueprint`](ue_ue.WidgetBlueprint.md)

#### Overrides

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Load](ue_ue.BaseWidgetBlueprint.md#load)

#### Defined in

[ue/ue.d.ts:33662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33662)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[StaticClass](ue_ue.BaseWidgetBlueprint.md#staticclass)

#### Defined in

[ue/ue.d.ts:33660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33660)
