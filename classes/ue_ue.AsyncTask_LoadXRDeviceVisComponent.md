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

## Properties

### OnLoadFailure

• **OnLoadFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`LoadedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

___

### OnModelLoaded

• **OnModelLoaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`LoadedComponent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>) => `void`\>

___

### SpawnedComponent

• **SpawnedComponent**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### \_\_tid\_AsyncTask\_LoadXRDeviceVisComponent\_\_

• **\_\_tid\_AsyncTask\_LoadXRDeviceVisComponent\_\_**: `boolean`

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)
