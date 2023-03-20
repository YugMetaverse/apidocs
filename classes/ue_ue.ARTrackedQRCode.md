[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTrackedQRCode

# Class: ARTrackedQRCode

[ue/ue](../modules/ue_ue.md).ARTrackedQRCode

## Hierarchy

- [`ARTrackedImage`](ue_ue.ARTrackedImage.md)

  ↳ **`ARTrackedQRCode`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARTrackedQRCode.md#constructor)

### Properties

- [DebugName](ue_ue.ARTrackedQRCode.md#debugname)
- [DetectedImage](ue_ue.ARTrackedQRCode.md#detectedimage)
- [EstimatedSize](ue_ue.ARTrackedQRCode.md#estimatedsize)
- [LastUpdateFrameNumber](ue_ue.ARTrackedQRCode.md#lastupdateframenumber)
- [LocalToAlignedTrackingTransform](ue_ue.ARTrackedQRCode.md#localtoalignedtrackingtransform)
- [LocalToTrackingTransform](ue_ue.ARTrackedQRCode.md#localtotrackingtransform)
- [ObjectClassification](ue_ue.ARTrackedQRCode.md#objectclassification)
- [QRCode](ue_ue.ARTrackedQRCode.md#qrcode)
- [TrackingState](ue_ue.ARTrackedQRCode.md#trackingstate)
- [UnderlyingMesh](ue_ue.ARTrackedQRCode.md#underlyingmesh)
- [UniqueId](ue_ue.ARTrackedQRCode.md#uniqueid)
- [Version](ue_ue.ARTrackedQRCode.md#version)
- [\_\_tid\_ARTrackedGeometry\_\_](ue_ue.ARTrackedQRCode.md#__tid_artrackedgeometry__)
- [\_\_tid\_ARTrackedImage\_\_](ue_ue.ARTrackedQRCode.md#__tid_artrackedimage__)
- [\_\_tid\_ARTrackedQRCode\_\_](ue_ue.ARTrackedQRCode.md#__tid_artrackedqrcode__)
- [\_\_tid\_Object\_\_](ue_ue.ARTrackedQRCode.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARTrackedQRCode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARTrackedQRCode.md#executeubergraph)
- [GetClass](ue_ue.ARTrackedQRCode.md#getclass)
- [GetDebugName](ue_ue.ARTrackedQRCode.md#getdebugname)
- [GetDetectedImage](ue_ue.ARTrackedQRCode.md#getdetectedimage)
- [GetEstimateSize](ue_ue.ARTrackedQRCode.md#getestimatesize)
- [GetLastUpdateFrameNumber](ue_ue.ARTrackedQRCode.md#getlastupdateframenumber)
- [GetLastUpdateTimestamp](ue_ue.ARTrackedQRCode.md#getlastupdatetimestamp)
- [GetLocalToTrackingTransform](ue_ue.ARTrackedQRCode.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARTrackedQRCode.md#getlocaltoworldtransform)
- [GetName](ue_ue.ARTrackedQRCode.md#getname)
- [GetObjectClassification](ue_ue.ARTrackedQRCode.md#getobjectclassification)
- [GetOuter](ue_ue.ARTrackedQRCode.md#getouter)
- [GetTrackingState](ue_ue.ARTrackedQRCode.md#gettrackingstate)
- [GetUnderlyingMesh](ue_ue.ARTrackedQRCode.md#getunderlyingmesh)
- [GetWorld](ue_ue.ARTrackedQRCode.md#getworld)
- [IsTracked](ue_ue.ARTrackedQRCode.md#istracked)
- [Find](ue_ue.ARTrackedQRCode.md#find)
- [Load](ue_ue.ARTrackedQRCode.md#load)
- [StaticClass](ue_ue.ARTrackedQRCode.md#staticclass)

## Constructors

### constructor

• **new ARTrackedQRCode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARTrackedImage](ue_ue.ARTrackedImage.md).[constructor](ue_ue.ARTrackedImage.md#constructor)

## Properties

### DebugName

• **DebugName**: `string`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[DebugName](ue_ue.ARTrackedImage.md#debugname)

___

### DetectedImage

• **DetectedImage**: [`ARCandidateImage`](ue_ue.ARCandidateImage.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[DetectedImage](ue_ue.ARTrackedImage.md#detectedimage)

___

### EstimatedSize

• **EstimatedSize**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[EstimatedSize](ue_ue.ARTrackedImage.md#estimatedsize)

___

### LastUpdateFrameNumber

• **LastUpdateFrameNumber**: `number`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[LastUpdateFrameNumber](ue_ue.ARTrackedImage.md#lastupdateframenumber)

___

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[LocalToAlignedTrackingTransform](ue_ue.ARTrackedImage.md#localtoalignedtrackingtransform)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[LocalToTrackingTransform](ue_ue.ARTrackedImage.md#localtotrackingtransform)

___

### ObjectClassification

• **ObjectClassification**: [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[ObjectClassification](ue_ue.ARTrackedImage.md#objectclassification)

___

### QRCode

• **QRCode**: `string`

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[TrackingState](ue_ue.ARTrackedImage.md#trackingstate)

___

### UnderlyingMesh

• **UnderlyingMesh**: [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[UnderlyingMesh](ue_ue.ARTrackedImage.md#underlyingmesh)

___

### UniqueId

• **UniqueId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[UniqueId](ue_ue.ARTrackedImage.md#uniqueid)

___

### Version

• **Version**: `number`

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[__tid_ARTrackedGeometry__](ue_ue.ARTrackedImage.md#__tid_artrackedgeometry__)

___

### \_\_tid\_ARTrackedImage\_\_

• **\_\_tid\_ARTrackedImage\_\_**: `boolean`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[__tid_ARTrackedImage__](ue_ue.ARTrackedImage.md#__tid_artrackedimage__)

___

### \_\_tid\_ARTrackedQRCode\_\_

• **\_\_tid\_ARTrackedQRCode\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[__tid_Object__](ue_ue.ARTrackedImage.md#__tid_object__)

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

[ARTrackedImage](ue_ue.ARTrackedImage.md).[CreateDefaultSubobject](ue_ue.ARTrackedImage.md#createdefaultsubobject)

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

[ARTrackedImage](ue_ue.ARTrackedImage.md).[ExecuteUbergraph](ue_ue.ARTrackedImage.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetClass](ue_ue.ARTrackedImage.md#getclass)

___

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetDebugName](ue_ue.ARTrackedImage.md#getdebugname)

___

### GetDetectedImage

▸ **GetDetectedImage**(): [`ARCandidateImage`](ue_ue.ARCandidateImage.md)

#### Returns

[`ARCandidateImage`](ue_ue.ARCandidateImage.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetDetectedImage](ue_ue.ARTrackedImage.md#getdetectedimage)

___

### GetEstimateSize

▸ **GetEstimateSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetEstimateSize](ue_ue.ARTrackedImage.md#getestimatesize)

___

### GetLastUpdateFrameNumber

▸ **GetLastUpdateFrameNumber**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetLastUpdateFrameNumber](ue_ue.ARTrackedImage.md#getlastupdateframenumber)

___

### GetLastUpdateTimestamp

▸ **GetLastUpdateTimestamp**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetLastUpdateTimestamp](ue_ue.ARTrackedImage.md#getlastupdatetimestamp)

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetLocalToTrackingTransform](ue_ue.ARTrackedImage.md#getlocaltotrackingtransform)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetLocalToWorldTransform](ue_ue.ARTrackedImage.md#getlocaltoworldtransform)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetName](ue_ue.ARTrackedImage.md#getname)

___

### GetObjectClassification

▸ **GetObjectClassification**(): [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Returns

[`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetObjectClassification](ue_ue.ARTrackedImage.md#getobjectclassification)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetOuter](ue_ue.ARTrackedImage.md#getouter)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetTrackingState](ue_ue.ARTrackedImage.md#gettrackingstate)

___

### GetUnderlyingMesh

▸ **GetUnderlyingMesh**(): [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Returns

[`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetUnderlyingMesh](ue_ue.ARTrackedImage.md#getunderlyingmesh)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[GetWorld](ue_ue.ARTrackedImage.md#getworld)

___

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ARTrackedImage](ue_ue.ARTrackedImage.md).[IsTracked](ue_ue.ARTrackedImage.md#istracked)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTrackedQRCode`](ue_ue.ARTrackedQRCode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTrackedQRCode`](ue_ue.ARTrackedQRCode.md)

#### Overrides

[ARTrackedImage](ue_ue.ARTrackedImage.md).[Find](ue_ue.ARTrackedImage.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTrackedQRCode`](ue_ue.ARTrackedQRCode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTrackedQRCode`](ue_ue.ARTrackedQRCode.md)

#### Overrides

[ARTrackedImage](ue_ue.ARTrackedImage.md).[Load](ue_ue.ARTrackedImage.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTrackedImage](ue_ue.ARTrackedImage.md).[StaticClass](ue_ue.ARTrackedImage.md#staticclass)
