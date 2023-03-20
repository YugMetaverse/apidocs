[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AsyncTask\_LoadXRDeviceVisComponent

# Class: AsyncTask\_LoadXRDeviceVisComponent

[ue/ue](../modules/ue_ue.md).AsyncTask_LoadXRDeviceVisComponent

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`AsyncTask_LoadXRDeviceVisComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#constructor)

### Properties

- [OnLoadFailure](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#onloadfailure)
- [OnModelLoaded](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#onmodelloaded)
- [SpawnedComponent](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#spawnedcomponent)
- [\_\_tid\_AsyncTask\_LoadXRDeviceVisComponent\_\_](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#__tid_asynctask_loadxrdeviceviscomponent__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#__tid_object__)

### Methods

- [Activate](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#activate)
- [CreateDefaultSubobject](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#executeubergraph)
- [GetClass](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#getclass)
- [GetName](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#getname)
- [GetOuter](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#getouter)
- [GetWorld](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#getworld)
- [AddDeviceVisualizationComponentAsync](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#adddevicevisualizationcomponentasync)
- [AddNamedDeviceVisualizationComponentAsync](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#addnameddevicevisualizationcomponentasync)
- [Find](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#find)
- [Load](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#load)
- [StaticClass](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md#staticclass)

## Constructors

### constructor

• **new AsyncTask_LoadXRDeviceVisComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:22160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22160)

## Properties

### OnLoadFailure

• **OnLoadFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`LoadedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:22162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22162)

___

### OnModelLoaded

• **OnModelLoaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`LoadedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:22161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22161)

___

### SpawnedComponent

• **SpawnedComponent**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:22163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22163)

___

### \_\_tid\_AsyncTask\_LoadXRDeviceVisComponent\_\_

• **\_\_tid\_AsyncTask\_LoadXRDeviceVisComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22170)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

#### Defined in

[ue/ue.d.ts:20667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20667)

___

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[CreateDefaultSubobject](ue_ue.BlueprintAsyncActionBase.md#createdefaultsubobject)

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[ExecuteUbergraph](ue_ue.BlueprintAsyncActionBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### AddDeviceVisualizationComponentAsync

▸ `Static` **AddDeviceVisualizationComponentAsync**(`Target`, `XRDeviceId`, `bManualAttachment`, `RelativeTransform`, `NewComponent`): [`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `XRDeviceId` | [`XRDeviceId`](ue_ue.XRDeviceId.md) |
| `bManualAttachment` | `boolean` |
| `RelativeTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `NewComponent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

[`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Defined in

[ue/ue.d.ts:22164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22164)

___

### AddNamedDeviceVisualizationComponentAsync

▸ `Static` **AddNamedDeviceVisualizationComponentAsync**(`Target`, `SystemName`, `DeviceName`, `bManualAttachment`, `RelativeTransform`, `XRDeviceId`, `NewComponent`): [`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SystemName` | `string` |
| `DeviceName` | `string` |
| `bManualAttachment` | `boolean` |
| `RelativeTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `XRDeviceId` | [`$Ref`](../interfaces/puerts._Ref.md)<[`XRDeviceId`](ue_ue.XRDeviceId.md)\> |
| `NewComponent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

[`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Defined in

[ue/ue.d.ts:22165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22165)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

#### Defined in

[ue/ue.d.ts:22167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22167)

___

### Load

▸ `Static` **Load**(`InName`): [`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AsyncTask_LoadXRDeviceVisComponent`](ue_ue.AsyncTask_LoadXRDeviceVisComponent.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

#### Defined in

[ue/ue.d.ts:22168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22168)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:22166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22166)
