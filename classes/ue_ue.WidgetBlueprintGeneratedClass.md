[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetBlueprintGeneratedClass

# Class: WidgetBlueprintGeneratedClass

[ue/ue](../modules/ue_ue.md).WidgetBlueprintGeneratedClass

## Hierarchy

- [`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

  ↳ **`WidgetBlueprintGeneratedClass`**

  ↳↳ [`JSWidgetGeneratedClass`](ue_ue.JSWidgetGeneratedClass.md)

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetBlueprintGeneratedClass.md#constructor)

### Properties

- [Animations](ue_ue.WidgetBlueprintGeneratedClass.md#animations)
- [Bindings](ue_ue.WidgetBlueprintGeneratedClass.md#bindings)
- [CalledFunctions](ue_ue.WidgetBlueprintGeneratedClass.md#calledfunctions)
- [ComponentClassOverrides](ue_ue.WidgetBlueprintGeneratedClass.md#componentclassoverrides)
- [ComponentTemplates](ue_ue.WidgetBlueprintGeneratedClass.md#componenttemplates)
- [CookedComponentInstancingData](ue_ue.WidgetBlueprintGeneratedClass.md#cookedcomponentinstancingdata)
- [DynamicBindingObjects](ue_ue.WidgetBlueprintGeneratedClass.md#dynamicbindingobjects)
- [EditorTemplate](ue_ue.WidgetBlueprintGeneratedClass.md#editortemplate)
- [FastCallPairs](ue_ue.WidgetBlueprintGeneratedClass.md#fastcallpairs)
- [InheritableComponentHandler](ue_ue.WidgetBlueprintGeneratedClass.md#inheritablecomponenthandler)
- [NamedSlots](ue_ue.WidgetBlueprintGeneratedClass.md#namedslots)
- [NumReplicatedProperties](ue_ue.WidgetBlueprintGeneratedClass.md#numreplicatedproperties)
- [OverridenArchetypeForCDO](ue_ue.WidgetBlueprintGeneratedClass.md#overridenarchetypeforcdo)
- [PropertyGuids](ue_ue.WidgetBlueprintGeneratedClass.md#propertyguids)
- [SimpleConstructionScript](ue_ue.WidgetBlueprintGeneratedClass.md#simpleconstructionscript)
- [Template](ue_ue.WidgetBlueprintGeneratedClass.md#template)
- [TemplateAsset](ue_ue.WidgetBlueprintGeneratedClass.md#templateasset)
- [Timelines](ue_ue.WidgetBlueprintGeneratedClass.md#timelines)
- [UberGraphFramePointerProperty](ue_ue.WidgetBlueprintGeneratedClass.md#ubergraphframepointerproperty)
- [UberGraphFunction](ue_ue.WidgetBlueprintGeneratedClass.md#ubergraphfunction)
- [WidgetTree](ue_ue.WidgetBlueprintGeneratedClass.md#widgettree)
- [\_\_tid\_BlueprintGeneratedClass\_\_](ue_ue.WidgetBlueprintGeneratedClass.md#__tid_blueprintgeneratedclass__)
- [\_\_tid\_Class\_\_](ue_ue.WidgetBlueprintGeneratedClass.md#__tid_class__)
- [\_\_tid\_Field\_\_](ue_ue.WidgetBlueprintGeneratedClass.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.WidgetBlueprintGeneratedClass.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.WidgetBlueprintGeneratedClass.md#__tid_struct__)
- [\_\_tid\_WidgetBlueprintGeneratedClass\_\_](ue_ue.WidgetBlueprintGeneratedClass.md#__tid_widgetblueprintgeneratedclass__)
- [bAllowDynamicCreation](ue_ue.WidgetBlueprintGeneratedClass.md#ballowdynamiccreation)
- [bAllowTemplate](ue_ue.WidgetBlueprintGeneratedClass.md#ballowtemplate)
- [bCanCallPreConstruct](ue_ue.WidgetBlueprintGeneratedClass.md#bcancallpreconstruct)
- [bClassRequiresNativeTick](ue_ue.WidgetBlueprintGeneratedClass.md#bclassrequiresnativetick)
- [bCookSlowConstructionWidgetTree](ue_ue.WidgetBlueprintGeneratedClass.md#bcookslowconstructionwidgettree)
- [bCookedTemplate](ue_ue.WidgetBlueprintGeneratedClass.md#bcookedtemplate)
- [bHasCookedComponentInstancingData](ue_ue.WidgetBlueprintGeneratedClass.md#bhascookedcomponentinstancingdata)
- [bHasNativizedParent](ue_ue.WidgetBlueprintGeneratedClass.md#bhasnativizedparent)
- [bIsSparseClassDataSerializable](ue_ue.WidgetBlueprintGeneratedClass.md#bissparseclassdataserializable)
- [bTemplateInitialized](ue_ue.WidgetBlueprintGeneratedClass.md#btemplateinitialized)
- [bValidTemplate](ue_ue.WidgetBlueprintGeneratedClass.md#bvalidtemplate)

### Methods

- [CreateDefaultSubobject](ue_ue.WidgetBlueprintGeneratedClass.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WidgetBlueprintGeneratedClass.md#executeubergraph)
- [GetClass](ue_ue.WidgetBlueprintGeneratedClass.md#getclass)
- [GetName](ue_ue.WidgetBlueprintGeneratedClass.md#getname)
- [GetOuter](ue_ue.WidgetBlueprintGeneratedClass.md#getouter)
- [GetWorld](ue_ue.WidgetBlueprintGeneratedClass.md#getworld)
- [IsChildOf](ue_ue.WidgetBlueprintGeneratedClass.md#ischildof)
- [Find](ue_ue.WidgetBlueprintGeneratedClass.md#find)
- [Load](ue_ue.WidgetBlueprintGeneratedClass.md#load)
- [StaticClass](ue_ue.WidgetBlueprintGeneratedClass.md#staticclass)

## Constructors

### constructor

• **new WidgetBlueprintGeneratedClass**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[constructor](ue_ue.BlueprintGeneratedClass.md#constructor)

## Properties

### Animations

• **Animations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\>

___

### Bindings

• **Bindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateRuntimeBinding`](ue_ue.DelegateRuntimeBinding.md)\>

___

### CalledFunctions

• **CalledFunctions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Function`](ue_ue.Function.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[CalledFunctions](ue_ue.BlueprintGeneratedClass.md#calledfunctions)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[ComponentClassOverrides](ue_ue.BlueprintGeneratedClass.md#componentclassoverrides)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[ComponentTemplates](ue_ue.BlueprintGeneratedClass.md#componenttemplates)

___

### CookedComponentInstancingData

• **CookedComponentInstancingData**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`BlueprintCookedComponentInstancingData`](ue_ue.BlueprintCookedComponentInstancingData.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[CookedComponentInstancingData](ue_ue.BlueprintGeneratedClass.md#cookedcomponentinstancingdata)

___

### DynamicBindingObjects

• **DynamicBindingObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[DynamicBindingObjects](ue_ue.BlueprintGeneratedClass.md#dynamicbindingobjects)

___

### EditorTemplate

• **EditorTemplate**: [`UserWidget`](ue_ue.UserWidget.md)

___

### FastCallPairs

• **FastCallPairs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventGraphFastCallPair`](ue_ue.EventGraphFastCallPair.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[FastCallPairs](ue_ue.BlueprintGeneratedClass.md#fastcallpairs)

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[InheritableComponentHandler](ue_ue.BlueprintGeneratedClass.md#inheritablecomponenthandler)

___

### NamedSlots

• **NamedSlots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### NumReplicatedProperties

• **NumReplicatedProperties**: `number`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[NumReplicatedProperties](ue_ue.BlueprintGeneratedClass.md#numreplicatedproperties)

___

### OverridenArchetypeForCDO

• **OverridenArchetypeForCDO**: [`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[OverridenArchetypeForCDO](ue_ue.BlueprintGeneratedClass.md#overridenarchetypeforcdo)

___

### PropertyGuids

• **PropertyGuids**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[PropertyGuids](ue_ue.BlueprintGeneratedClass.md#propertyguids)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[SimpleConstructionScript](ue_ue.BlueprintGeneratedClass.md#simpleconstructionscript)

___

### Template

• **Template**: [`UserWidget`](ue_ue.UserWidget.md)

___

### TemplateAsset

• **TemplateAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`UserWidget`](ue_ue.UserWidget.md)\>

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[Timelines](ue_ue.BlueprintGeneratedClass.md#timelines)

___

### UberGraphFramePointerProperty

• **UberGraphFramePointerProperty**: [`StructProperty`](ue_ue.StructProperty.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[UberGraphFramePointerProperty](ue_ue.BlueprintGeneratedClass.md#ubergraphframepointerproperty)

___

### UberGraphFunction

• **UberGraphFunction**: [`Function`](ue_ue.Function.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[UberGraphFunction](ue_ue.BlueprintGeneratedClass.md#ubergraphfunction)

___

### WidgetTree

• **WidgetTree**: [`WidgetTree`](ue_ue.WidgetTree.md)

___

### \_\_tid\_BlueprintGeneratedClass\_\_

• **\_\_tid\_BlueprintGeneratedClass\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_BlueprintGeneratedClass__](ue_ue.BlueprintGeneratedClass.md#__tid_blueprintgeneratedclass__)

___

### \_\_tid\_Class\_\_

• **\_\_tid\_Class\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Class__](ue_ue.BlueprintGeneratedClass.md#__tid_class__)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Field__](ue_ue.BlueprintGeneratedClass.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Object__](ue_ue.BlueprintGeneratedClass.md#__tid_object__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Struct__](ue_ue.BlueprintGeneratedClass.md#__tid_struct__)

___

### \_\_tid\_WidgetBlueprintGeneratedClass\_\_

• **\_\_tid\_WidgetBlueprintGeneratedClass\_\_**: `boolean`

___

### bAllowDynamicCreation

• **bAllowDynamicCreation**: `boolean`

___

### bAllowTemplate

• **bAllowTemplate**: `boolean`

___

### bCanCallPreConstruct

• **bCanCallPreConstruct**: `boolean`

___

### bClassRequiresNativeTick

• **bClassRequiresNativeTick**: `boolean`

___

### bCookSlowConstructionWidgetTree

• **bCookSlowConstructionWidgetTree**: `boolean`

___

### bCookedTemplate

• **bCookedTemplate**: `boolean`

___

### bHasCookedComponentInstancingData

• **bHasCookedComponentInstancingData**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[bHasCookedComponentInstancingData](ue_ue.BlueprintGeneratedClass.md#bhascookedcomponentinstancingdata)

___

### bHasNativizedParent

• **bHasNativizedParent**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[bHasNativizedParent](ue_ue.BlueprintGeneratedClass.md#bhasnativizedparent)

___

### bIsSparseClassDataSerializable

• **bIsSparseClassDataSerializable**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[bIsSparseClassDataSerializable](ue_ue.BlueprintGeneratedClass.md#bissparseclassdataserializable)

___

### bTemplateInitialized

• **bTemplateInitialized**: `boolean`

___

### bValidTemplate

• **bValidTemplate**: `boolean`

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

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[CreateDefaultSubobject](ue_ue.BlueprintGeneratedClass.md#createdefaultsubobject)

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

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[ExecuteUbergraph](ue_ue.BlueprintGeneratedClass.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetClass](ue_ue.BlueprintGeneratedClass.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetName](ue_ue.BlueprintGeneratedClass.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetOuter](ue_ue.BlueprintGeneratedClass.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetWorld](ue_ue.BlueprintGeneratedClass.md#getworld)

___

### IsChildOf

▸ **IsChildOf**(`p0`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`Struct`](ue_ue.Struct.md) |

#### Returns

`boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[IsChildOf](ue_ue.BlueprintGeneratedClass.md#ischildof)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WidgetBlueprintGeneratedClass`](ue_ue.WidgetBlueprintGeneratedClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WidgetBlueprintGeneratedClass`](ue_ue.WidgetBlueprintGeneratedClass.md)

#### Overrides

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[Find](ue_ue.BlueprintGeneratedClass.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WidgetBlueprintGeneratedClass`](ue_ue.WidgetBlueprintGeneratedClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WidgetBlueprintGeneratedClass`](ue_ue.WidgetBlueprintGeneratedClass.md)

#### Overrides

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[Load](ue_ue.BlueprintGeneratedClass.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[StaticClass](ue_ue.BlueprintGeneratedClass.md#staticclass)
