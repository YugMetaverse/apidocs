[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTraceResultLibrary

# Class: ARTraceResultLibrary

[ue/ue](../modules/ue_ue.md).ARTraceResultLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`ARTraceResultLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARTraceResultLibrary.md#constructor)

### Properties

- [\_\_tid\_ARTraceResultLibrary\_\_](ue_ue.ARTraceResultLibrary.md#__tid_artraceresultlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.ARTraceResultLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.ARTraceResultLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTraceResultLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTraceResultLibrary.md#executeubergraph)
- [GetClass](ue_ue.ARTraceResultLibrary.md#getclass)
- [GetName](ue_ue.ARTraceResultLibrary.md#getname)
- [GetOuter](ue_ue.ARTraceResultLibrary.md#getouter)
- [GetWorld](ue_ue.ARTraceResultLibrary.md#getworld)
- [Find](ue_ue.ARTraceResultLibrary.md#find)
- [GetDistanceFromCamera](ue_ue.ARTraceResultLibrary.md#getdistancefromcamera)
- [GetLocalToTrackingTransform](ue_ue.ARTraceResultLibrary.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARTraceResultLibrary.md#getlocaltoworldtransform)
- [GetTraceChannel](ue_ue.ARTraceResultLibrary.md#gettracechannel)
- [GetTrackedGeometry](ue_ue.ARTraceResultLibrary.md#gettrackedgeometry)
- [Load](ue_ue.ARTraceResultLibrary.md#load)
- [StaticClass](ue_ue.ARTraceResultLibrary.md#staticclass)

## Constructors

### constructor

• **new ARTraceResultLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_ARTraceResultLibrary\_\_

• **\_\_tid\_ARTraceResultLibrary\_\_**: `boolean`

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTraceResultLibrary`](ue_ue.ARTraceResultLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTraceResultLibrary`](ue_ue.ARTraceResultLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetDistanceFromCamera

▸ `Static` **GetDistanceFromCamera**(`TraceResult`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceResult` | [`ARTraceResult`](ue_ue.ARTraceResult.md) |

#### Returns

`number`

___

### GetLocalToTrackingTransform

▸ `Static` **GetLocalToTrackingTransform**(`TraceResult`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceResult` | [`ARTraceResult`](ue_ue.ARTraceResult.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetLocalToWorldTransform

▸ `Static` **GetLocalToWorldTransform**(`TraceResult`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceResult` | [`ARTraceResult`](ue_ue.ARTraceResult.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetTraceChannel

▸ `Static` **GetTraceChannel**(`TraceResult`): [`EARLineTraceChannels`](../enums/ue_ue.EARLineTraceChannels.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceResult` | [`ARTraceResult`](ue_ue.ARTraceResult.md) |

#### Returns

[`EARLineTraceChannels`](../enums/ue_ue.EARLineTraceChannels.md)

___

### GetTrackedGeometry

▸ `Static` **GetTrackedGeometry**(`TraceResult`): [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TraceResult` | [`ARTraceResult`](ue_ue.ARTraceResult.md) |

#### Returns

[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTraceResultLibrary`](ue_ue.ARTraceResultLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTraceResultLibrary`](ue_ue.ARTraceResultLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
