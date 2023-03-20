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

#### Defined in

[ue/ue.d.ts:40674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40674)

## Properties

### Animations

• **Animations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\>

#### Defined in

[ue/ue.d.ts:40685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40685)

___

### Bindings

• **Bindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateRuntimeBinding`](ue_ue.DelegateRuntimeBinding.md)\>

#### Defined in

[ue/ue.d.ts:40684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40684)

___

### CalledFunctions

• **CalledFunctions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Function`](ue_ue.Function.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[CalledFunctions](ue_ue.BlueprintGeneratedClass.md#calledfunctions)

#### Defined in

[ue/ue.d.ts:4817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4817)

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[ComponentClassOverrides](ue_ue.BlueprintGeneratedClass.md#componentclassoverrides)

#### Defined in

[ue/ue.d.ts:4809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4809)

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[ComponentTemplates](ue_ue.BlueprintGeneratedClass.md#componenttemplates)

#### Defined in

[ue/ue.d.ts:4807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4807)

___

### CookedComponentInstancingData

• **CookedComponentInstancingData**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`BlueprintCookedComponentInstancingData`](ue_ue.BlueprintCookedComponentInstancingData.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[CookedComponentInstancingData](ue_ue.BlueprintGeneratedClass.md#cookedcomponentinstancingdata)

#### Defined in

[ue/ue.d.ts:4818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4818)

___

### DynamicBindingObjects

• **DynamicBindingObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[DynamicBindingObjects](ue_ue.BlueprintGeneratedClass.md#dynamicbindingobjects)

#### Defined in

[ue/ue.d.ts:4806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4806)

___

### EditorTemplate

• **EditorTemplate**: [`UserWidget`](ue_ue.UserWidget.md)

#### Defined in

[ue/ue.d.ts:40689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40689)

___

### FastCallPairs

• **FastCallPairs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventGraphFastCallPair`](ue_ue.EventGraphFastCallPair.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[FastCallPairs](ue_ue.BlueprintGeneratedClass.md#fastcallpairs)

#### Defined in

[ue/ue.d.ts:4814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4814)

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[InheritableComponentHandler](ue_ue.BlueprintGeneratedClass.md#inheritablecomponenthandler)

#### Defined in

[ue/ue.d.ts:4811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4811)

___

### NamedSlots

• **NamedSlots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:40686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40686)

___

### NumReplicatedProperties

• **NumReplicatedProperties**: `number`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[NumReplicatedProperties](ue_ue.BlueprintGeneratedClass.md#numreplicatedproperties)

#### Defined in

[ue/ue.d.ts:4802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4802)

___

### OverridenArchetypeForCDO

• **OverridenArchetypeForCDO**: [`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[OverridenArchetypeForCDO](ue_ue.BlueprintGeneratedClass.md#overridenarchetypeforcdo)

#### Defined in

[ue/ue.d.ts:4815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4815)

___

### PropertyGuids

• **PropertyGuids**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[PropertyGuids](ue_ue.BlueprintGeneratedClass.md#propertyguids)

#### Defined in

[ue/ue.d.ts:4816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4816)

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[SimpleConstructionScript](ue_ue.BlueprintGeneratedClass.md#simpleconstructionscript)

#### Defined in

[ue/ue.d.ts:4810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4810)

___

### Template

• **Template**: [`UserWidget`](ue_ue.UserWidget.md)

#### Defined in

[ue/ue.d.ts:40688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40688)

___

### TemplateAsset

• **TemplateAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`UserWidget`](ue_ue.UserWidget.md)\>

#### Defined in

[ue/ue.d.ts:40687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40687)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[Timelines](ue_ue.BlueprintGeneratedClass.md#timelines)

#### Defined in

[ue/ue.d.ts:4808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4808)

___

### UberGraphFramePointerProperty

• **UberGraphFramePointerProperty**: [`StructProperty`](ue_ue.StructProperty.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[UberGraphFramePointerProperty](ue_ue.BlueprintGeneratedClass.md#ubergraphframepointerproperty)

#### Defined in

[ue/ue.d.ts:4812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4812)

___

### UberGraphFunction

• **UberGraphFunction**: [`Function`](ue_ue.Function.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[UberGraphFunction](ue_ue.BlueprintGeneratedClass.md#ubergraphfunction)

#### Defined in

[ue/ue.d.ts:4813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4813)

___

### WidgetTree

• **WidgetTree**: [`WidgetTree`](ue_ue.WidgetTree.md)

#### Defined in

[ue/ue.d.ts:40675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40675)

___

### \_\_tid\_BlueprintGeneratedClass\_\_

• **\_\_tid\_BlueprintGeneratedClass\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_BlueprintGeneratedClass__](ue_ue.BlueprintGeneratedClass.md#__tid_blueprintgeneratedclass__)

#### Defined in

[ue/ue.d.ts:4823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4823)

___

### \_\_tid\_Class\_\_

• **\_\_tid\_Class\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Class__](ue_ue.BlueprintGeneratedClass.md#__tid_class__)

#### Defined in

[ue/ue.d.ts:719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L719)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Field__](ue_ue.BlueprintGeneratedClass.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L700)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Object__](ue_ue.BlueprintGeneratedClass.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[__tid_Struct__](ue_ue.BlueprintGeneratedClass.md#__tid_struct__)

#### Defined in

[ue/ue.d.ts:710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L710)

___

### \_\_tid\_WidgetBlueprintGeneratedClass\_\_

• **\_\_tid\_WidgetBlueprintGeneratedClass\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:40694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40694)

___

### bAllowDynamicCreation

• **bAllowDynamicCreation**: `boolean`

#### Defined in

[ue/ue.d.ts:40679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40679)

___

### bAllowTemplate

• **bAllowTemplate**: `boolean`

#### Defined in

[ue/ue.d.ts:40678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40678)

___

### bCanCallPreConstruct

• **bCanCallPreConstruct**: `boolean`

#### Defined in

[ue/ue.d.ts:40677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40677)

___

### bClassRequiresNativeTick

• **bClassRequiresNativeTick**: `boolean`

#### Defined in

[ue/ue.d.ts:40683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40683)

___

### bCookSlowConstructionWidgetTree

• **bCookSlowConstructionWidgetTree**: `boolean`

#### Defined in

[ue/ue.d.ts:40676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40676)

___

### bCookedTemplate

• **bCookedTemplate**: `boolean`

#### Defined in

[ue/ue.d.ts:40682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40682)

___

### bHasCookedComponentInstancingData

• **bHasCookedComponentInstancingData**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[bHasCookedComponentInstancingData](ue_ue.BlueprintGeneratedClass.md#bhascookedcomponentinstancingdata)

#### Defined in

[ue/ue.d.ts:4804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4804)

___

### bHasNativizedParent

• **bHasNativizedParent**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[bHasNativizedParent](ue_ue.BlueprintGeneratedClass.md#bhasnativizedparent)

#### Defined in

[ue/ue.d.ts:4803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4803)

___

### bIsSparseClassDataSerializable

• **bIsSparseClassDataSerializable**: `boolean`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[bIsSparseClassDataSerializable](ue_ue.BlueprintGeneratedClass.md#bissparseclassdataserializable)

#### Defined in

[ue/ue.d.ts:4805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L4805)

___

### bTemplateInitialized

• **bTemplateInitialized**: `boolean`

#### Defined in

[ue/ue.d.ts:40681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40681)

___

### bValidTemplate

• **bValidTemplate**: `boolean`

#### Defined in

[ue/ue.d.ts:40680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40680)

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

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[ExecuteUbergraph](ue_ue.BlueprintGeneratedClass.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetClass](ue_ue.BlueprintGeneratedClass.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetName](ue_ue.BlueprintGeneratedClass.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetOuter](ue_ue.BlueprintGeneratedClass.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[GetWorld](ue_ue.BlueprintGeneratedClass.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L705)

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

#### Defined in

[ue/ue.d.ts:40691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40691)

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

#### Defined in

[ue/ue.d.ts:40692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40692)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintGeneratedClass](ue_ue.BlueprintGeneratedClass.md).[StaticClass](ue_ue.BlueprintGeneratedClass.md#staticclass)

#### Defined in

[ue/ue.d.ts:40690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40690)
