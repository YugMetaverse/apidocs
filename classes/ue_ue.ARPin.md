[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARPin

# Class: ARPin

[ue/ue](../modules/ue_ue.md).ARPin

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ARPin`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARPin.md#constructor)

### Properties

- [LocalToAlignedTrackingTransform](ue_ue.ARPin.md#localtoalignedtrackingtransform)
- [LocalToTrackingTransform](ue_ue.ARPin.md#localtotrackingtransform)
- [OnARTrackingStateChanged](ue_ue.ARPin.md#onartrackingstatechanged)
- [OnARTransformUpdated](ue_ue.ARPin.md#onartransformupdated)
- [PinnedComponent](ue_ue.ARPin.md#pinnedcomponent)
- [TrackedGeometry](ue_ue.ARPin.md#trackedgeometry)
- [TrackingState](ue_ue.ARPin.md#trackingstate)
- [\_\_tid\_ARPin\_\_](ue_ue.ARPin.md#__tid_arpin__)
- [\_\_tid\_Object\_\_](ue_ue.ARPin.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARPin.md#createdefaultsubobject)
- [DebugDraw](ue_ue.ARPin.md#debugdraw)
- [ExecuteUbergraph](ue_ue.ARPin.md#executeubergraph)
- [GetClass](ue_ue.ARPin.md#getclass)
- [GetDebugName](ue_ue.ARPin.md#getdebugname)
- [GetLocalToTrackingTransform](ue_ue.ARPin.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARPin.md#getlocaltoworldtransform)
- [GetName](ue_ue.ARPin.md#getname)
- [GetOuter](ue_ue.ARPin.md#getouter)
- [GetPinnedComponent](ue_ue.ARPin.md#getpinnedcomponent)
- [GetTrackedGeometry](ue_ue.ARPin.md#gettrackedgeometry)
- [GetTrackingState](ue_ue.ARPin.md#gettrackingstate)
- [GetWorld](ue_ue.ARPin.md#getworld)
- [Find](ue_ue.ARPin.md#find)
- [Load](ue_ue.ARPin.md#load)
- [StaticClass](ue_ue.ARPin.md#staticclass)

## Constructors

### constructor

• **new ARPin**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### OnARTrackingStateChanged

• **OnARTrackingStateChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewTrackingState`: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)) => `void`\>

___

### OnARTransformUpdated

• **OnARTransformUpdated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OldToNewTransform`: [`Transform`](ue_ue_s.Transform.md)) => `void`\>

___

### PinnedComponent

• **PinnedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### TrackedGeometry

• **TrackedGeometry**: [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

___

### \_\_tid\_ARPin\_\_

• **\_\_tid\_ARPin\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

___

### DebugDraw

▸ **DebugDraw**(`World`, `Color`, `Scale`, `PersistForSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `World` | [`$Nullable`](../modules/puerts.md#$nullable)<[`World`](ue_ue.World.md)\> |
| `Color` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Scale` | `number` |
| `PersistForSeconds` | `number` |

#### Returns

`void`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetPinnedComponent

▸ **GetPinnedComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

___

### GetTrackedGeometry

▸ **GetTrackedGeometry**(): [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Returns

[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARPin`](ue_ue.ARPin.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARPin`](ue_ue.ARPin.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARPin`](ue_ue.ARPin.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARPin`](ue_ue.ARPin.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
