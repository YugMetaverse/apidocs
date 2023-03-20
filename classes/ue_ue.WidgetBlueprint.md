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

## Properties

### AnimationData

• **AnimationData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimation_DEPRECATED`](ue_ue.WidgetAnimation_DEPRECATED.md)\>

___

### Animations

• **Animations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\>

___

### Bindings

• **Bindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateEditorBinding`](ue_ue.DelegateEditorBinding.md)\>

___

### BlueprintCategory

• **BlueprintCategory**: `string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintCategory](ue_ue.BaseWidgetBlueprint.md#blueprintcategory)

___

### BlueprintDescription

• **BlueprintDescription**: `string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintDescription](ue_ue.BaseWidgetBlueprint.md#blueprintdescription)

___

### BlueprintDisplayName

• **BlueprintDisplayName**: `string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintDisplayName](ue_ue.BaseWidgetBlueprint.md#blueprintdisplayname)

___

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintGuid](ue_ue.BaseWidgetBlueprint.md#blueprintguid)

___

### BlueprintSystemVersion

• **BlueprintSystemVersion**: `number`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintSystemVersion](ue_ue.BaseWidgetBlueprint.md#blueprintsystemversion)

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BlueprintType](ue_ue.BaseWidgetBlueprint.md#blueprinttype)

___

### BookmarkNodes

• **BookmarkNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPEditorBookmarkNode`](ue_ue.BPEditorBookmarkNode.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[BookmarkNodes](ue_ue.BaseWidgetBlueprint.md#bookmarknodes)

___

### Bookmarks

• **Bookmarks**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Bookmarks](ue_ue.BaseWidgetBlueprint.md#bookmarks)

___

### Breakpoints

• **Breakpoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Breakpoint`](ue_ue.Breakpoint.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Breakpoints](ue_ue.BaseWidgetBlueprint.md#breakpoints)

___

### CategorySorting

• **CategorySorting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CategorySorting](ue_ue.BaseWidgetBlueprint.md#categorysorting)

___

### CompileMode

• **CompileMode**: [`EBlueprintCompileMode`](../enums/ue_ue.EBlueprintCompileMode.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CompileMode](ue_ue.BaseWidgetBlueprint.md#compilemode)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ComponentClassOverrides](ue_ue.BaseWidgetBlueprint.md#componentclassoverrides)

___

### ComponentTemplateNameIndex

• **ComponentTemplateNameIndex**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ComponentTemplateNameIndex](ue_ue.BaseWidgetBlueprint.md#componenttemplatenameindex)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ComponentTemplates](ue_ue.BaseWidgetBlueprint.md#componenttemplates)

___

### CrcLastCompiledCDO

• **CrcLastCompiledCDO**: `number`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CrcLastCompiledCDO](ue_ue.BaseWidgetBlueprint.md#crclastcompiledcdo)

___

### CrcLastCompiledSignature

• **CrcLastCompiledSignature**: `number`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[CrcLastCompiledSignature](ue_ue.BaseWidgetBlueprint.md#crclastcompiledsignature)

___

### DelegateSignatureGraphs

• **DelegateSignatureGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[DelegateSignatureGraphs](ue_ue.BaseWidgetBlueprint.md#delegatesignaturegraphs)

___

### DeprecatedPinWatches

• **DeprecatedPinWatches**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[DeprecatedPinWatches](ue_ue.BaseWidgetBlueprint.md#deprecatedpinwatches)

___

### EstimatedTemplateSize

• **EstimatedTemplateSize**: `number`

___

### EventGraphs

• **EventGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[EventGraphs](ue_ue.BaseWidgetBlueprint.md#eventgraphs)

___

### Extensions

• **Extensions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintExtension`](ue_ue.BlueprintExtension.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Extensions](ue_ue.BaseWidgetBlueprint.md#extensions)

___

### FunctionGraphs

• **FunctionGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[FunctionGraphs](ue_ue.BaseWidgetBlueprint.md#functiongraphs)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GeneratedClass](ue_ue.BaseWidgetBlueprint.md#generatedclass)

___

### HideCategories

• **HideCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[HideCategories](ue_ue.BaseWidgetBlueprint.md#hidecategories)

___

### ImplementedInterfaces

• **ImplementedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPInterfaceDescription`](ue_ue.BPInterfaceDescription.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ImplementedInterfaces](ue_ue.BaseWidgetBlueprint.md#implementedinterfaces)

___

### InclusiveWidgets

• **InclusiveWidgets**: `number`

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[InheritableComponentHandler](ue_ue.BaseWidgetBlueprint.md#inheritablecomponenthandler)

___

### IntermediateGeneratedGraphs

• **IntermediateGeneratedGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[IntermediateGeneratedGraphs](ue_ue.BaseWidgetBlueprint.md#intermediategeneratedgraphs)

___

### LastEditedDocuments

• **LastEditedDocuments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditedDocumentInfo`](ue_ue.EditedDocumentInfo.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[LastEditedDocuments](ue_ue.BaseWidgetBlueprint.md#lastediteddocuments)

___

### MacroGraphs

• **MacroGraphs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[MacroGraphs](ue_ue.BaseWidgetBlueprint.md#macrographs)

___

### NativizationFlag

• **NativizationFlag**: [`EBlueprintNativizationFlag`](../enums/ue_ue.EBlueprintNativizationFlag.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[NativizationFlag](ue_ue.BaseWidgetBlueprint.md#nativizationflag)

___

### NewVariables

• **NewVariables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableDescription`](ue_ue.BPVariableDescription.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[NewVariables](ue_ue.BaseWidgetBlueprint.md#newvariables)

___

### OldToNewComponentTemplateNames

• **OldToNewComponentTemplateNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[OldToNewComponentTemplateNames](ue_ue.BaseWidgetBlueprint.md#oldtonewcomponenttemplatenames)

___

### OriginalClass

• **OriginalClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[OriginalClass](ue_ue.BaseWidgetBlueprint.md#originalclass)

___

### PRIVATE\_CachedMacroInfo

• **PRIVATE\_CachedMacroInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EdGraph`](ue_ue.EdGraph.md), [`BlueprintMacroCosmeticInfo`](ue_ue.BlueprintMacroCosmeticInfo.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[PRIVATE_CachedMacroInfo](ue_ue.BaseWidgetBlueprint.md#private_cachedmacroinfo)

___

### PaletteCategory

• **PaletteCategory**: `string`

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ParentClass](ue_ue.BaseWidgetBlueprint.md#parentclass)

___

### PropertyBindings

• **PropertyBindings**: `number`

___

### SearchGuid

• **SearchGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[SearchGuid](ue_ue.BaseWidgetBlueprint.md#searchguid)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[SimpleConstructionScript](ue_ue.BaseWidgetBlueprint.md#simpleconstructionscript)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[SkeletonGeneratedClass](ue_ue.BaseWidgetBlueprint.md#skeletongeneratedclass)

___

### Status

• **Status**: [`EBlueprintStatus`](../enums/ue_ue.EBlueprintStatus.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Status](ue_ue.BaseWidgetBlueprint.md#status)

___

### SupportDynamicCreation

• **SupportDynamicCreation**: [`EWidgetSupportsDynamicCreation`](../enums/ue_ue.EWidgetSupportsDynamicCreation.md)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[ThumbnailInfo](ue_ue.BaseWidgetBlueprint.md#thumbnailinfo)

___

### TickFrequency

• **TickFrequency**: [`EWidgetTickFrequency`](../enums/ue_ue.EWidgetTickFrequency.md)

___

### TickPrediction

• **TickPrediction**: [`EWidgetCompileTimeTickPrediction`](../enums/ue_ue.EWidgetCompileTimeTickPrediction.md)

___

### TickPredictionReason

• **TickPredictionReason**: `string`

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[Timelines](ue_ue.BaseWidgetBlueprint.md#timelines)

___

### UbergraphPages

• **UbergraphPages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraph`](ue_ue.EdGraph.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[UbergraphPages](ue_ue.BaseWidgetBlueprint.md#ubergraphpages)

___

### WatchedPins

• **WatchedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPinReference`](ue_ue.EdGraphPinReference.md)\>

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[WatchedPins](ue_ue.BaseWidgetBlueprint.md#watchedpins)

___

### WidgetTree

• **WidgetTree**: [`WidgetTree`](ue_ue.WidgetTree.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[WidgetTree](ue_ue.BaseWidgetBlueprint.md#widgettree)

___

### \_\_tid\_BaseWidgetBlueprint\_\_

• **\_\_tid\_BaseWidgetBlueprint\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_BaseWidgetBlueprint__](ue_ue.BaseWidgetBlueprint.md#__tid_basewidgetblueprint__)

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_BlueprintCore__](ue_ue.BaseWidgetBlueprint.md#__tid_blueprintcore__)

___

### \_\_tid\_Blueprint\_\_

• **\_\_tid\_Blueprint\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_Blueprint__](ue_ue.BaseWidgetBlueprint.md#__tid_blueprint__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[__tid_Object__](ue_ue.BaseWidgetBlueprint.md#__tid_object__)

___

### \_\_tid\_WidgetBlueprint\_\_

• **\_\_tid\_WidgetBlueprint\_\_**: `boolean`

___

### bBeingCompiled

• **bBeingCompiled**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bBeingCompiled](ue_ue.BaseWidgetBlueprint.md#bbeingcompiled)

___

### bDeprecate

• **bDeprecate**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bDeprecate](ue_ue.BaseWidgetBlueprint.md#bdeprecate)

___

### bDisplayCompilePIEWarning

• **bDisplayCompilePIEWarning**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bDisplayCompilePIEWarning](ue_ue.BaseWidgetBlueprint.md#bdisplaycompilepiewarning)

___

### bDuplicatingReadOnly

• **bDuplicatingReadOnly**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bDuplicatingReadOnly](ue_ue.BaseWidgetBlueprint.md#bduplicatingreadonly)

___

### bForceFullEditor

• **bForceFullEditor**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bForceFullEditor](ue_ue.BaseWidgetBlueprint.md#bforcefulleditor)

___

### bForceSlowConstructionPath

• **bForceSlowConstructionPath**: `boolean`

___

### bGenerateAbstractClass

• **bGenerateAbstractClass**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bGenerateAbstractClass](ue_ue.BaseWidgetBlueprint.md#bgenerateabstractclass)

___

### bGenerateConstClass

• **bGenerateConstClass**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bGenerateConstClass](ue_ue.BaseWidgetBlueprint.md#bgenerateconstclass)

___

### bHasBeenRegenerated

• **bHasBeenRegenerated**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bHasBeenRegenerated](ue_ue.BaseWidgetBlueprint.md#bhasbeenregenerated)

___

### bIsNewlyCreated

• **bIsNewlyCreated**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bIsNewlyCreated](ue_ue.BaseWidgetBlueprint.md#bisnewlycreated)

___

### bIsRegeneratingOnLoad

• **bIsRegeneratingOnLoad**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bIsRegeneratingOnLoad](ue_ue.BaseWidgetBlueprint.md#bisregeneratingonload)

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bLegacyNeedToPurgeSkelRefs](ue_ue.BaseWidgetBlueprint.md#blegacyneedtopurgeskelrefs)

___

### bNativize

• **bNativize**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bNativize](ue_ue.BaseWidgetBlueprint.md#bnativize)

___

### bQueuedForCompilation

• **bQueuedForCompilation**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bQueuedForCompilation](ue_ue.BaseWidgetBlueprint.md#bqueuedforcompilation)

___

### bRecompileOnLoad

• **bRecompileOnLoad**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bRecompileOnLoad](ue_ue.BaseWidgetBlueprint.md#brecompileonload)

___

### bRunConstructionScriptInSequencer

• **bRunConstructionScriptInSequencer**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bRunConstructionScriptInSequencer](ue_ue.BaseWidgetBlueprint.md#brunconstructionscriptinsequencer)

___

### bRunConstructionScriptOnDrag

• **bRunConstructionScriptOnDrag**: `boolean`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[bRunConstructionScriptOnDrag](ue_ue.BaseWidgetBlueprint.md#brunconstructionscriptondrag)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetClass](ue_ue.BaseWidgetBlueprint.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetName](ue_ue.BaseWidgetBlueprint.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetOuter](ue_ue.BaseWidgetBlueprint.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[GetWorld](ue_ue.BaseWidgetBlueprint.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BaseWidgetBlueprint](ue_ue.BaseWidgetBlueprint.md).[StaticClass](ue_ue.BaseWidgetBlueprint.md#staticclass)
