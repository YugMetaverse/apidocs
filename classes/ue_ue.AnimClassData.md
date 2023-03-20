[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimClassData

# Class: AnimClassData

[ue/ue](../modules/ue_ue.md).AnimClassData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimClassData`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimClassData.md#constructor)

### Properties

- [AnimBlueprintFunctions](ue_ue.AnimClassData.md#animblueprintfunctions)
- [AnimNodeProperties](ue_ue.AnimClassData.md#animnodeproperties)
- [AnimNotifies](ue_ue.AnimClassData.md#animnotifies)
- [BakedStateMachines](ue_ue.AnimClassData.md#bakedstatemachines)
- [DynamicResetNodeProperties](ue_ue.AnimClassData.md#dynamicresetnodeproperties)
- [EvaluateGraphExposedInputs](ue_ue.AnimClassData.md#evaluategraphexposedinputs)
- [GraphBlendOptions](ue_ue.AnimClassData.md#graphblendoptions)
- [GraphNameAssetPlayers](ue_ue.AnimClassData.md#graphnameassetplayers)
- [InitializationNodeProperties](ue_ue.AnimClassData.md#initializationnodeproperties)
- [LinkedAnimGraphNodeProperties](ue_ue.AnimClassData.md#linkedanimgraphnodeproperties)
- [LinkedAnimLayerNodeProperties](ue_ue.AnimClassData.md#linkedanimlayernodeproperties)
- [OrderedSavedPoseIndicesMap](ue_ue.AnimClassData.md#orderedsavedposeindicesmap)
- [PreUpdateNodeProperties](ue_ue.AnimClassData.md#preupdatenodeproperties)
- [StateMachineNodeProperties](ue_ue.AnimClassData.md#statemachinenodeproperties)
- [SyncGroupNames](ue_ue.AnimClassData.md#syncgroupnames)
- [TargetSkeleton](ue_ue.AnimClassData.md#targetskeleton)
- [\_\_tid\_AnimClassData\_\_](ue_ue.AnimClassData.md#__tid_animclassdata__)
- [\_\_tid\_Object\_\_](ue_ue.AnimClassData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimClassData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimClassData.md#executeubergraph)
- [GetClass](ue_ue.AnimClassData.md#getclass)
- [GetName](ue_ue.AnimClassData.md#getname)
- [GetOuter](ue_ue.AnimClassData.md#getouter)
- [GetWorld](ue_ue.AnimClassData.md#getworld)
- [Find](ue_ue.AnimClassData.md#find)
- [Load](ue_ue.AnimClassData.md#load)
- [StaticClass](ue_ue.AnimClassData.md#staticclass)

## Constructors

### constructor

• **new AnimClassData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:17318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17318)

## Properties

### AnimBlueprintFunctions

• **AnimBlueprintFunctions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimBlueprintFunction`](ue_ue.AnimBlueprintFunction.md)\>

#### Defined in

[ue/ue.d.ts:17323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17323)

___

### AnimNodeProperties

• **AnimNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17324)

___

### AnimNotifies

• **AnimNotifies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>

#### Defined in

[ue/ue.d.ts:17321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17321)

___

### BakedStateMachines

• **BakedStateMachines**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BakedAnimationStateMachine`](ue_ue.BakedAnimationStateMachine.md)\>

#### Defined in

[ue/ue.d.ts:17319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17319)

___

### DynamicResetNodeProperties

• **DynamicResetNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17328)

___

### EvaluateGraphExposedInputs

• **EvaluateGraphExposedInputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExposedValueHandler`](ue_ue.ExposedValueHandler.md)\>

#### Defined in

[ue/ue.d.ts:17333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17333)

___

### GraphBlendOptions

• **GraphBlendOptions**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`AnimGraphBlendOptions`](ue_ue.AnimGraphBlendOptions.md)\>

#### Defined in

[ue/ue.d.ts:17334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17334)

___

### GraphNameAssetPlayers

• **GraphNameAssetPlayers**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`GraphAssetPlayerInformation`](ue_ue.GraphAssetPlayerInformation.md)\>

#### Defined in

[ue/ue.d.ts:17331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17331)

___

### InitializationNodeProperties

• **InitializationNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17330)

___

### LinkedAnimGraphNodeProperties

• **LinkedAnimGraphNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17325)

___

### LinkedAnimLayerNodeProperties

• **LinkedAnimLayerNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17326)

___

### OrderedSavedPoseIndicesMap

• **OrderedSavedPoseIndicesMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CachedPoseIndices`](ue_ue.CachedPoseIndices.md)\>

#### Defined in

[ue/ue.d.ts:17322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17322)

___

### PreUpdateNodeProperties

• **PreUpdateNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17327)

___

### StateMachineNodeProperties

• **StateMachineNodeProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructProperty`](ue_ue.StructProperty.md)\>

#### Defined in

[ue/ue.d.ts:17329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17329)

___

### SyncGroupNames

• **SyncGroupNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:17332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17332)

___

### TargetSkeleton

• **TargetSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Defined in

[ue/ue.d.ts:17320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17320)

___

### \_\_tid\_AnimClassData\_\_

• **\_\_tid\_AnimClassData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17339)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimClassData`](ue_ue.AnimClassData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimClassData`](ue_ue.AnimClassData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:17336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17336)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimClassData`](ue_ue.AnimClassData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimClassData`](ue_ue.AnimClassData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:17337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17337)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:17335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17335)
