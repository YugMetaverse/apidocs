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

#### Defined in

[ue/ue.d.ts:20885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20885)

## Properties

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20889)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20888)

___

### OnARTrackingStateChanged

• **OnARTrackingStateChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewTrackingState`: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:20891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20891)

___

### OnARTransformUpdated

• **OnARTransformUpdated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OldToNewTransform`: [`Transform`](ue_ue_s.Transform.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:20892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20892)

___

### PinnedComponent

• **PinnedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Defined in

[ue/ue.d.ts:20887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20887)

___

### TrackedGeometry

• **TrackedGeometry**: [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Defined in

[ue/ue.d.ts:20886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20886)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Defined in

[ue/ue.d.ts:20890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20890)

___

### \_\_tid\_ARPin\_\_

• **\_\_tid\_ARPin\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20904)

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

#### Defined in

[ue/ue.d.ts:20893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20893)

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

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:20894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20894)

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20895)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20896)

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

### GetPinnedComponent

▸ **GetPinnedComponent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Defined in

[ue/ue.d.ts:20897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20897)

___

### GetTrackedGeometry

▸ **GetTrackedGeometry**(): [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Returns

[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Defined in

[ue/ue.d.ts:20898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20898)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Defined in

[ue/ue.d.ts:20899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20899)

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

#### Defined in

[ue/ue.d.ts:20901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20901)

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

#### Defined in

[ue/ue.d.ts:20902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20902)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:20900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20900)
