[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTrackedPose

# Class: ARTrackedPose

[ue/ue](../modules/ue_ue.md).ARTrackedPose

## Hierarchy

- [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

  ↳ **`ARTrackedPose`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARTrackedPose.md#constructor)

### Properties

- [DebugName](ue_ue.ARTrackedPose.md#debugname)
- [LastUpdateFrameNumber](ue_ue.ARTrackedPose.md#lastupdateframenumber)
- [LocalToAlignedTrackingTransform](ue_ue.ARTrackedPose.md#localtoalignedtrackingtransform)
- [LocalToTrackingTransform](ue_ue.ARTrackedPose.md#localtotrackingtransform)
- [ObjectClassification](ue_ue.ARTrackedPose.md#objectclassification)
- [TrackingState](ue_ue.ARTrackedPose.md#trackingstate)
- [UnderlyingMesh](ue_ue.ARTrackedPose.md#underlyingmesh)
- [UniqueId](ue_ue.ARTrackedPose.md#uniqueid)
- [\_\_tid\_ARTrackedGeometry\_\_](ue_ue.ARTrackedPose.md#__tid_artrackedgeometry__)
- [\_\_tid\_ARTrackedPose\_\_](ue_ue.ARTrackedPose.md#__tid_artrackedpose__)
- [\_\_tid\_Object\_\_](ue_ue.ARTrackedPose.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTrackedPose.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTrackedPose.md#executeubergraph)
- [GetClass](ue_ue.ARTrackedPose.md#getclass)
- [GetDebugName](ue_ue.ARTrackedPose.md#getdebugname)
- [GetLastUpdateFrameNumber](ue_ue.ARTrackedPose.md#getlastupdateframenumber)
- [GetLastUpdateTimestamp](ue_ue.ARTrackedPose.md#getlastupdatetimestamp)
- [GetLocalToTrackingTransform](ue_ue.ARTrackedPose.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARTrackedPose.md#getlocaltoworldtransform)
- [GetName](ue_ue.ARTrackedPose.md#getname)
- [GetObjectClassification](ue_ue.ARTrackedPose.md#getobjectclassification)
- [GetOuter](ue_ue.ARTrackedPose.md#getouter)
- [GetTrackedPoseData](ue_ue.ARTrackedPose.md#gettrackedposedata)
- [GetTrackingState](ue_ue.ARTrackedPose.md#gettrackingstate)
- [GetUnderlyingMesh](ue_ue.ARTrackedPose.md#getunderlyingmesh)
- [GetWorld](ue_ue.ARTrackedPose.md#getworld)
- [IsTracked](ue_ue.ARTrackedPose.md#istracked)
- [Find](ue_ue.ARTrackedPose.md#find)
- [Load](ue_ue.ARTrackedPose.md#load)
- [StaticClass](ue_ue.ARTrackedPose.md#staticclass)

## Constructors

### constructor

• **new ARTrackedPose**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[constructor](ue_ue.ARTrackedGeometry.md#constructor)

## Properties

### DebugName

• **DebugName**: `string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[DebugName](ue_ue.ARTrackedGeometry.md#debugname)

___

### LastUpdateFrameNumber

• **LastUpdateFrameNumber**: `number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#lastupdateframenumber)

___

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LocalToAlignedTrackingTransform](ue_ue.ARTrackedGeometry.md#localtoalignedtrackingtransform)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#localtotrackingtransform)

___

### ObjectClassification

• **ObjectClassification**: [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[ObjectClassification](ue_ue.ARTrackedGeometry.md#objectclassification)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[TrackingState](ue_ue.ARTrackedGeometry.md#trackingstate)

___

### UnderlyingMesh

• **UnderlyingMesh**: [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[UnderlyingMesh](ue_ue.ARTrackedGeometry.md#underlyingmesh)

___

### UniqueId

• **UniqueId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[UniqueId](ue_ue.ARTrackedGeometry.md#uniqueid)

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_ARTrackedGeometry__](ue_ue.ARTrackedGeometry.md#__tid_artrackedgeometry__)

___

### \_\_tid\_ARTrackedPose\_\_

• **\_\_tid\_ARTrackedPose\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_Object__](ue_ue.ARTrackedGeometry.md#__tid_object__)

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

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[CreateDefaultSubobject](ue_ue.ARTrackedGeometry.md#createdefaultsubobject)

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

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[ExecuteUbergraph](ue_ue.ARTrackedGeometry.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetClass](ue_ue.ARTrackedGeometry.md#getclass)

___

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetDebugName](ue_ue.ARTrackedGeometry.md#getdebugname)

___

### GetLastUpdateFrameNumber

▸ **GetLastUpdateFrameNumber**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#getlastupdateframenumber)

___

### GetLastUpdateTimestamp

▸ **GetLastUpdateTimestamp**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLastUpdateTimestamp](ue_ue.ARTrackedGeometry.md#getlastupdatetimestamp)

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#getlocaltotrackingtransform)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLocalToWorldTransform](ue_ue.ARTrackedGeometry.md#getlocaltoworldtransform)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetName](ue_ue.ARTrackedGeometry.md#getname)

___

### GetObjectClassification

▸ **GetObjectClassification**(): [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Returns

[`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetObjectClassification](ue_ue.ARTrackedGeometry.md#getobjectclassification)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetOuter](ue_ue.ARTrackedGeometry.md#getouter)

___

### GetTrackedPoseData

▸ **GetTrackedPoseData**(): [`ARPose3D`](ue_ue.ARPose3D.md)

#### Returns

[`ARPose3D`](ue_ue.ARPose3D.md)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetTrackingState](ue_ue.ARTrackedGeometry.md#gettrackingstate)

___

### GetUnderlyingMesh

▸ **GetUnderlyingMesh**(): [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Returns

[`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetUnderlyingMesh](ue_ue.ARTrackedGeometry.md#getunderlyingmesh)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetWorld](ue_ue.ARTrackedGeometry.md#getworld)

___

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[IsTracked](ue_ue.ARTrackedGeometry.md#istracked)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTrackedPose`](ue_ue.ARTrackedPose.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTrackedPose`](ue_ue.ARTrackedPose.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[Find](ue_ue.ARTrackedGeometry.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTrackedPose`](ue_ue.ARTrackedPose.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTrackedPose`](ue_ue.ARTrackedPose.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[Load](ue_ue.ARTrackedGeometry.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[StaticClass](ue_ue.ARTrackedGeometry.md#staticclass)
