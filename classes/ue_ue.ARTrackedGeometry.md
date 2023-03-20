[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTrackedGeometry

# Class: ARTrackedGeometry

[ue/ue](../modules/ue_ue.md).ARTrackedGeometry

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ARTrackedGeometry`**

  ↳↳ [`ARTrackedPose`](ue_ue.ARTrackedPose.md)

  ↳↳ [`ARTrackedPoint`](ue_ue.ARTrackedPoint.md)

  ↳↳ [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

  ↳↳ [`ARTrackedImage`](ue_ue.ARTrackedImage.md)

  ↳↳ [`AREnvironmentCaptureProbe`](ue_ue.AREnvironmentCaptureProbe.md)

  ↳↳ [`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)

  ↳↳ [`ARTrackedObject`](ue_ue.ARTrackedObject.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ARTrackedGeometry.md#constructor)

### Properties

- [DebugName](ue_ue.ARTrackedGeometry.md#debugname)
- [LastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#lastupdateframenumber)
- [LocalToAlignedTrackingTransform](ue_ue.ARTrackedGeometry.md#localtoalignedtrackingtransform)
- [LocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#localtotrackingtransform)
- [ObjectClassification](ue_ue.ARTrackedGeometry.md#objectclassification)
- [TrackingState](ue_ue.ARTrackedGeometry.md#trackingstate)
- [UnderlyingMesh](ue_ue.ARTrackedGeometry.md#underlyingmesh)
- [UniqueId](ue_ue.ARTrackedGeometry.md#uniqueid)
- [\_\_tid\_ARTrackedGeometry\_\_](ue_ue.ARTrackedGeometry.md#__tid_artrackedgeometry__)
- [\_\_tid\_Object\_\_](ue_ue.ARTrackedGeometry.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTrackedGeometry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTrackedGeometry.md#executeubergraph)
- [GetClass](ue_ue.ARTrackedGeometry.md#getclass)
- [GetDebugName](ue_ue.ARTrackedGeometry.md#getdebugname)
- [GetLastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#getlastupdateframenumber)
- [GetLastUpdateTimestamp](ue_ue.ARTrackedGeometry.md#getlastupdatetimestamp)
- [GetLocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARTrackedGeometry.md#getlocaltoworldtransform)
- [GetName](ue_ue.ARTrackedGeometry.md#getname)
- [GetObjectClassification](ue_ue.ARTrackedGeometry.md#getobjectclassification)
- [GetOuter](ue_ue.ARTrackedGeometry.md#getouter)
- [GetTrackingState](ue_ue.ARTrackedGeometry.md#gettrackingstate)
- [GetUnderlyingMesh](ue_ue.ARTrackedGeometry.md#getunderlyingmesh)
- [GetWorld](ue_ue.ARTrackedGeometry.md#getworld)
- [IsTracked](ue_ue.ARTrackedGeometry.md#istracked)
- [Find](ue_ue.ARTrackedGeometry.md#find)
- [Load](ue_ue.ARTrackedGeometry.md#load)
- [StaticClass](ue_ue.ARTrackedGeometry.md#staticclass)

## Constructors

### constructor

• **new ARTrackedGeometry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:20859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20859)

## Properties

### DebugName

• **DebugName**: `string`

#### Defined in

[ue/ue.d.ts:20867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20867)

___

### LastUpdateFrameNumber

• **LastUpdateFrameNumber**: `number`

#### Defined in

[ue/ue.d.ts:20866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20866)

___

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20862)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20861)

___

### ObjectClassification

• **ObjectClassification**: [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Defined in

[ue/ue.d.ts:20865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20865)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Defined in

[ue/ue.d.ts:20863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20863)

___

### UnderlyingMesh

• **UnderlyingMesh**: [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Defined in

[ue/ue.d.ts:20864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20864)

___

### UniqueId

• **UniqueId**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:20860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20860)

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20881)

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

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:20868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20868)

___

### GetLastUpdateFrameNumber

▸ **GetLastUpdateFrameNumber**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:20869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20869)

___

### GetLastUpdateTimestamp

▸ **GetLastUpdateTimestamp**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:20870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20870)

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20871)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:20872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20872)

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

### GetObjectClassification

▸ **GetObjectClassification**(): [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Returns

[`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Defined in

[ue/ue.d.ts:20873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20873)

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

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Defined in

[ue/ue.d.ts:20874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20874)

___

### GetUnderlyingMesh

▸ **GetUnderlyingMesh**(): [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Returns

[`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Defined in

[ue/ue.d.ts:20875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20875)

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

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:20876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20876)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:20878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20878)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:20879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20879)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:20877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20877)
