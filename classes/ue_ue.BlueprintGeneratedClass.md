[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintGeneratedClass

# Class: BlueprintGeneratedClass

[ue/ue](../modules/ue_ue.md).BlueprintGeneratedClass

## Hierarchy

- [`Class`](ue_ue.Class.md)

  ↳ **`BlueprintGeneratedClass`**

  ↳↳ [`AnimBlueprintGeneratedClass`](ue_ue.AnimBlueprintGeneratedClass.md)

  ↳↳ [`JSGeneratedClass`](ue_ue.JSGeneratedClass.md)

  ↳↳ [`WidgetBlueprintGeneratedClass`](ue_ue.WidgetBlueprintGeneratedClass.md)

  ↳↳ [`TypeScriptGeneratedClass`](ue_ue.TypeScriptGeneratedClass.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintGeneratedClass.md#constructor)

### Properties

- [CalledFunctions](ue_ue.BlueprintGeneratedClass.md#calledfunctions)
- [ComponentClassOverrides](ue_ue.BlueprintGeneratedClass.md#componentclassoverrides)
- [ComponentTemplates](ue_ue.BlueprintGeneratedClass.md#componenttemplates)
- [CookedComponentInstancingData](ue_ue.BlueprintGeneratedClass.md#cookedcomponentinstancingdata)
- [DynamicBindingObjects](ue_ue.BlueprintGeneratedClass.md#dynamicbindingobjects)
- [FastCallPairs](ue_ue.BlueprintGeneratedClass.md#fastcallpairs)
- [InheritableComponentHandler](ue_ue.BlueprintGeneratedClass.md#inheritablecomponenthandler)
- [NumReplicatedProperties](ue_ue.BlueprintGeneratedClass.md#numreplicatedproperties)
- [OverridenArchetypeForCDO](ue_ue.BlueprintGeneratedClass.md#overridenarchetypeforcdo)
- [PropertyGuids](ue_ue.BlueprintGeneratedClass.md#propertyguids)
- [SimpleConstructionScript](ue_ue.BlueprintGeneratedClass.md#simpleconstructionscript)
- [Timelines](ue_ue.BlueprintGeneratedClass.md#timelines)
- [UberGraphFramePointerProperty](ue_ue.BlueprintGeneratedClass.md#ubergraphframepointerproperty)
- [UberGraphFunction](ue_ue.BlueprintGeneratedClass.md#ubergraphfunction)
- [\_\_tid\_BlueprintGeneratedClass\_\_](ue_ue.BlueprintGeneratedClass.md#__tid_blueprintgeneratedclass__)
- [\_\_tid\_Class\_\_](ue_ue.BlueprintGeneratedClass.md#__tid_class__)
- [\_\_tid\_Field\_\_](ue_ue.BlueprintGeneratedClass.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintGeneratedClass.md#__tid_object__)
- [\_\_tid\_Struct\_\_](ue_ue.BlueprintGeneratedClass.md#__tid_struct__)
- [bHasCookedComponentInstancingData](ue_ue.BlueprintGeneratedClass.md#bhascookedcomponentinstancingdata)
- [bHasNativizedParent](ue_ue.BlueprintGeneratedClass.md#bhasnativizedparent)
- [bIsSparseClassDataSerializable](ue_ue.BlueprintGeneratedClass.md#bissparseclassdataserializable)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintGeneratedClass.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintGeneratedClass.md#executeubergraph)
- [GetClass](ue_ue.BlueprintGeneratedClass.md#getclass)
- [GetName](ue_ue.BlueprintGeneratedClass.md#getname)
- [GetOuter](ue_ue.BlueprintGeneratedClass.md#getouter)
- [GetWorld](ue_ue.BlueprintGeneratedClass.md#getworld)
- [IsChildOf](ue_ue.BlueprintGeneratedClass.md#ischildof)
- [Find](ue_ue.BlueprintGeneratedClass.md#find)
- [Load](ue_ue.BlueprintGeneratedClass.md#load)
- [StaticClass](ue_ue.BlueprintGeneratedClass.md#staticclass)

## Constructors

### constructor

• **new BlueprintGeneratedClass**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Class](ue_ue.Class.md).[constructor](ue_ue.Class.md#constructor)

## Properties

### CalledFunctions

• **CalledFunctions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Function`](ue_ue.Function.md)\>

___

### ComponentClassOverrides

• **ComponentClassOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPComponentClassOverride`](ue_ue.BPComponentClassOverride.md)\>

___

### ComponentTemplates

• **ComponentTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### CookedComponentInstancingData

• **CookedComponentInstancingData**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`BlueprintCookedComponentInstancingData`](ue_ue.BlueprintCookedComponentInstancingData.md)\>

___

### DynamicBindingObjects

• **DynamicBindingObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)\>

___

### FastCallPairs

• **FastCallPairs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventGraphFastCallPair`](ue_ue.EventGraphFastCallPair.md)\>

___

### InheritableComponentHandler

• **InheritableComponentHandler**: [`InheritableComponentHandler`](ue_ue.InheritableComponentHandler.md)

___

### NumReplicatedProperties

• **NumReplicatedProperties**: `number`

___

### OverridenArchetypeForCDO

• **OverridenArchetypeForCDO**: [`Object`](ue_ue.Object.md)

___

### PropertyGuids

• **PropertyGuids**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Guid`](ue_ue_s.Guid.md)\>

___

### SimpleConstructionScript

• **SimpleConstructionScript**: [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

___

### Timelines

• **Timelines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineTemplate`](ue_ue.TimelineTemplate.md)\>

___

### UberGraphFramePointerProperty

• **UberGraphFramePointerProperty**: [`StructProperty`](ue_ue.StructProperty.md)

___

### UberGraphFunction

• **UberGraphFunction**: [`Function`](ue_ue.Function.md)

___

### \_\_tid\_BlueprintGeneratedClass\_\_

• **\_\_tid\_BlueprintGeneratedClass\_\_**: `boolean`

___

### \_\_tid\_Class\_\_

• **\_\_tid\_Class\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Class__](ue_ue.Class.md#__tid_class__)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Field__](ue_ue.Class.md#__tid_field__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Object__](ue_ue.Class.md#__tid_object__)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[Class](ue_ue.Class.md).[__tid_Struct__](ue_ue.Class.md#__tid_struct__)

___

### bHasCookedComponentInstancingData

• **bHasCookedComponentInstancingData**: `boolean`

___

### bHasNativizedParent

• **bHasNativizedParent**: `boolean`

___

### bIsSparseClassDataSerializable

• **bIsSparseClassDataSerializable**: `boolean`

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

[Class](ue_ue.Class.md).[CreateDefaultSubobject](ue_ue.Class.md#createdefaultsubobject)

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

[Class](ue_ue.Class.md).[ExecuteUbergraph](ue_ue.Class.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetClass](ue_ue.Class.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Class](ue_ue.Class.md).[GetName](ue_ue.Class.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetOuter](ue_ue.Class.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Class](ue_ue.Class.md).[GetWorld](ue_ue.Class.md#getworld)

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

[Class](ue_ue.Class.md).[IsChildOf](ue_ue.Class.md#ischildof)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

#### Overrides

[Class](ue_ue.Class.md).[Find](ue_ue.Class.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

#### Overrides

[Class](ue_ue.Class.md).[Load](ue_ue.Class.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Class](ue_ue.Class.md).[StaticClass](ue_ue.Class.md#staticclass)
