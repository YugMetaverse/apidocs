[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARPlaneGeometry

# Class: ARPlaneGeometry

[ue/ue](../modules/ue_ue.md).ARPlaneGeometry

## Hierarchy

- [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

  ↳ **`ARPlaneGeometry`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARPlaneGeometry.md#constructor)

### Properties

- [Center](ue_ue.ARPlaneGeometry.md#center)
- [DebugName](ue_ue.ARPlaneGeometry.md#debugname)
- [Extent](ue_ue.ARPlaneGeometry.md#extent)
- [LastUpdateFrameNumber](ue_ue.ARPlaneGeometry.md#lastupdateframenumber)
- [LocalToAlignedTrackingTransform](ue_ue.ARPlaneGeometry.md#localtoalignedtrackingtransform)
- [LocalToTrackingTransform](ue_ue.ARPlaneGeometry.md#localtotrackingtransform)
- [ObjectClassification](ue_ue.ARPlaneGeometry.md#objectclassification)
- [Orientation](ue_ue.ARPlaneGeometry.md#orientation)
- [SubsumedBy](ue_ue.ARPlaneGeometry.md#subsumedby)
- [TrackingState](ue_ue.ARPlaneGeometry.md#trackingstate)
- [UnderlyingMesh](ue_ue.ARPlaneGeometry.md#underlyingmesh)
- [UniqueId](ue_ue.ARPlaneGeometry.md#uniqueid)
- [\_\_tid\_ARPlaneGeometry\_\_](ue_ue.ARPlaneGeometry.md#__tid_arplanegeometry__)
- [\_\_tid\_ARTrackedGeometry\_\_](ue_ue.ARPlaneGeometry.md#__tid_artrackedgeometry__)
- [\_\_tid\_Object\_\_](ue_ue.ARPlaneGeometry.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARPlaneGeometry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARPlaneGeometry.md#executeubergraph)
- [GetBoundaryPolygonInLocalSpace](ue_ue.ARPlaneGeometry.md#getboundarypolygoninlocalspace)
- [GetCenter](ue_ue.ARPlaneGeometry.md#getcenter)
- [GetClass](ue_ue.ARPlaneGeometry.md#getclass)
- [GetDebugName](ue_ue.ARPlaneGeometry.md#getdebugname)
- [GetExtent](ue_ue.ARPlaneGeometry.md#getextent)
- [GetLastUpdateFrameNumber](ue_ue.ARPlaneGeometry.md#getlastupdateframenumber)
- [GetLastUpdateTimestamp](ue_ue.ARPlaneGeometry.md#getlastupdatetimestamp)
- [GetLocalToTrackingTransform](ue_ue.ARPlaneGeometry.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARPlaneGeometry.md#getlocaltoworldtransform)
- [GetName](ue_ue.ARPlaneGeometry.md#getname)
- [GetObjectClassification](ue_ue.ARPlaneGeometry.md#getobjectclassification)
- [GetOrientation](ue_ue.ARPlaneGeometry.md#getorientation)
- [GetOuter](ue_ue.ARPlaneGeometry.md#getouter)
- [GetSubsumedBy](ue_ue.ARPlaneGeometry.md#getsubsumedby)
- [GetTrackingState](ue_ue.ARPlaneGeometry.md#gettrackingstate)
- [GetUnderlyingMesh](ue_ue.ARPlaneGeometry.md#getunderlyingmesh)
- [GetWorld](ue_ue.ARPlaneGeometry.md#getworld)
- [IsTracked](ue_ue.ARPlaneGeometry.md#istracked)
- [Find](ue_ue.ARPlaneGeometry.md#find)
- [Load](ue_ue.ARPlaneGeometry.md#load)
- [StaticClass](ue_ue.ARPlaneGeometry.md#staticclass)

## Constructors

### constructor

• **new ARPlaneGeometry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[constructor](ue_ue.ARTrackedGeometry.md#constructor)

## Properties

### Center

• **Center**: [`Vector`](ue_ue_s.Vector.md)

___

### DebugName

• **DebugName**: `string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[DebugName](ue_ue.ARTrackedGeometry.md#debugname)

___

### Extent

• **Extent**: [`Vector`](ue_ue_s.Vector.md)

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

### Orientation

• **Orientation**: [`EARPlaneOrientation`](../enums/ue_ue.EARPlaneOrientation.md)

___

### SubsumedBy

• **SubsumedBy**: [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

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

### \_\_tid\_ARPlaneGeometry\_\_

• **\_\_tid\_ARPlaneGeometry\_\_**: `boolean`

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_ARTrackedGeometry__](ue_ue.ARTrackedGeometry.md#__tid_artrackedgeometry__)

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

### GetBoundaryPolygonInLocalSpace

▸ **GetBoundaryPolygonInLocalSpace**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### GetCenter

▸ **GetCenter**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### GetExtent

▸ **GetExtent**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### GetOrientation

▸ **GetOrientation**(): [`EARPlaneOrientation`](../enums/ue_ue.EARPlaneOrientation.md)

#### Returns

[`EARPlaneOrientation`](../enums/ue_ue.EARPlaneOrientation.md)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetOuter](ue_ue.ARTrackedGeometry.md#getouter)

___

### GetSubsumedBy

▸ **GetSubsumedBy**(): [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Returns

[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[Find](ue_ue.ARTrackedGeometry.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[Load](ue_ue.ARTrackedGeometry.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[StaticClass](ue_ue.ARTrackedGeometry.md#staticclass)
