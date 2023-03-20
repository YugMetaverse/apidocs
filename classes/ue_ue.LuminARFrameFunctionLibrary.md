[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LuminARFrameFunctionLibrary

# Class: LuminARFrameFunctionLibrary

[ue/ue](../modules/ue_ue.md).LuminARFrameFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`LuminARFrameFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.LuminARFrameFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.LuminARFrameFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_LuminARFrameFunctionLibrary\_\_](ue_ue.LuminARFrameFunctionLibrary.md#__tid_luminarframefunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.LuminARFrameFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LuminARFrameFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LuminARFrameFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.LuminARFrameFunctionLibrary.md#getclass)
- [GetName](ue_ue.LuminARFrameFunctionLibrary.md#getname)
- [GetOuter](ue_ue.LuminARFrameFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.LuminARFrameFunctionLibrary.md#getworld)
- [Find](ue_ue.LuminARFrameFunctionLibrary.md#find)
- [GetLightEstimation](ue_ue.LuminARFrameFunctionLibrary.md#getlightestimation)
- [GetTrackingState](ue_ue.LuminARFrameFunctionLibrary.md#gettrackingstate)
- [Load](ue_ue.LuminARFrameFunctionLibrary.md#load)
- [LuminARLineTrace](ue_ue.LuminARFrameFunctionLibrary.md#luminarlinetrace)
- [StaticClass](ue_ue.LuminARFrameFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new LuminARFrameFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_LuminARFrameFunctionLibrary\_\_

• **\_\_tid\_LuminARFrameFunctionLibrary\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LuminARFrameFunctionLibrary`](ue_ue.LuminARFrameFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LuminARFrameFunctionLibrary`](ue_ue.LuminARFrameFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetLightEstimation

▸ `Static` **GetLightEstimation**(`OutLightEstimate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutLightEstimate` | [`$Ref`](../interfaces/puerts._Ref.md)<[`LuminARLightEstimate`](ue_ue.LuminARLightEstimate.md)\> |

#### Returns

`void`

___

### GetTrackingState

▸ `Static` **GetTrackingState**(): [`ELuminARTrackingState`](../enums/ue_ue.ELuminARTrackingState.md)

#### Returns

[`ELuminARTrackingState`](../enums/ue_ue.ELuminARTrackingState.md)

___

### Load

▸ `Static` **Load**(`InName`): [`LuminARFrameFunctionLibrary`](ue_ue.LuminARFrameFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LuminARFrameFunctionLibrary`](ue_ue.LuminARFrameFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### LuminARLineTrace

▸ `Static` **LuminARLineTrace**(`WorldContextObject`, `ScreenPosition`, `TraceChannels`, `OutHitResults`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `TraceChannels` | [`TSet`](../interfaces/ue_puerts.TSet.md)<[`ELuminARLineTraceChannel`](../enums/ue_ue.ELuminARLineTraceChannel.md)\> |
| `OutHitResults` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTraceResult`](ue_ue.ARTraceResult.md)\>\> |

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
