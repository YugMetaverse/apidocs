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

## Properties

### DebugName

• **DebugName**: `string`

___

### LastUpdateFrameNumber

• **LastUpdateFrameNumber**: `number`

___

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### ObjectClassification

• **ObjectClassification**: [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

___

### UnderlyingMesh

• **UnderlyingMesh**: [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

___

### UniqueId

• **UniqueId**: [`Guid`](ue_ue_s.Guid.md)

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

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

### GetLastUpdateFrameNumber

▸ **GetLastUpdateFrameNumber**(): `number`

#### Returns

`number`

___

### GetLastUpdateTimestamp

▸ **GetLastUpdateTimestamp**(): `number`

#### Returns

`number`

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

### GetObjectClassification

▸ **GetObjectClassification**(): [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Returns

[`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

___

### GetUnderlyingMesh

▸ **GetUnderlyingMesh**(): [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Returns

[`MRMeshComponent`](ue_ue.MRMeshComponent.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
