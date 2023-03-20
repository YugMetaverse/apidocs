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

#### Defined in

[ue/ue.d.ts:21028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21028)

## Properties

### Center

• **Center**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:21030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21030)

___

### DebugName

• **DebugName**: `string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[DebugName](ue_ue.ARTrackedGeometry.md#debugname)

#### Defined in

[ue/ue.d.ts:20867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20867)

___

### Extent

• **Extent**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:21031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21031)

___

### LastUpdateFrameNumber

• **LastUpdateFrameNumber**: `number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#lastupdateframenumber)

#### Defined in

[ue/ue.d.ts:20866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20866)

___

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LocalToAlignedTrackingTransform](ue_ue.ARTrackedGeometry.md#localtoalignedtrackingtransform)

#### Defined in

[ue/ue.d.ts:20862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20862)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#localtotrackingtransform)

#### Defined in

[ue/ue.d.ts:20861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20861)

___

### ObjectClassification

• **ObjectClassification**: [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[ObjectClassification](ue_ue.ARTrackedGeometry.md#objectclassification)

#### Defined in

[ue/ue.d.ts:20865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20865)

___

### Orientation

• **Orientation**: [`EARPlaneOrientation`](../enums/ue_ue.EARPlaneOrientation.md)

#### Defined in

[ue/ue.d.ts:21029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21029)

___

### SubsumedBy

• **SubsumedBy**: [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Defined in

[ue/ue.d.ts:21032](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21032)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[TrackingState](ue_ue.ARTrackedGeometry.md#trackingstate)

#### Defined in

[ue/ue.d.ts:20863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20863)

___

### UnderlyingMesh

• **UnderlyingMesh**: [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[UnderlyingMesh](ue_ue.ARTrackedGeometry.md#underlyingmesh)

#### Defined in

[ue/ue.d.ts:20864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20864)

___

### UniqueId

• **UniqueId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[UniqueId](ue_ue.ARTrackedGeometry.md#uniqueid)

#### Defined in

[ue/ue.d.ts:20860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20860)

___

### \_\_tid\_ARPlaneGeometry\_\_

• **\_\_tid\_ARPlaneGeometry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21042)

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_ARTrackedGeometry__](ue_ue.ARTrackedGeometry.md#__tid_artrackedgeometry__)

#### Defined in

[ue/ue.d.ts:20881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20881)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_Object__](ue_ue.ARTrackedGeometry.md#__tid_object__)

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

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[CreateDefaultSubobject](ue_ue.ARTrackedGeometry.md#createdefaultsubobject)

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

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[ExecuteUbergraph](ue_ue.ARTrackedGeometry.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetBoundaryPolygonInLocalSpace

▸ **GetBoundaryPolygonInLocalSpace**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:21033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21033)

___

### GetCenter

▸ **GetCenter**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:21034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21034)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetClass](ue_ue.ARTrackedGeometry.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetDebugName](ue_ue.ARTrackedGeometry.md#getdebugname)

#### Defined in

[ue/ue.d.ts:20868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20868)

___

### GetExtent

▸ **GetExtent**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:21035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21035)

___

### GetLastUpdateFrameNumber

▸ **GetLastUpdateFrameNumber**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#getlastupdateframenumber)

#### Defined in

[ue/ue.d.ts:20869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20869)

___

### GetLastUpdateTimestamp

▸ **GetLastUpdateTimestamp**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLastUpdateTimestamp](ue_ue.ARTrackedGeometry.md#getlastupdatetimestamp)

#### Defined in

[ue/ue.d.ts:20870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20870)

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#getlocaltotrackingtransform)

#### Defined in

[ue/ue.d.ts:20871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20871)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLocalToWorldTransform](ue_ue.ARTrackedGeometry.md#getlocaltoworldtransform)

#### Defined in

[ue/ue.d.ts:20872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20872)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetName](ue_ue.ARTrackedGeometry.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetObjectClassification

▸ **GetObjectClassification**(): [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Returns

[`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetObjectClassification](ue_ue.ARTrackedGeometry.md#getobjectclassification)

#### Defined in

[ue/ue.d.ts:20873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20873)

___

### GetOrientation

▸ **GetOrientation**(): [`EARPlaneOrientation`](../enums/ue_ue.EARPlaneOrientation.md)

#### Returns

[`EARPlaneOrientation`](../enums/ue_ue.EARPlaneOrientation.md)

#### Defined in

[ue/ue.d.ts:21036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21036)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetOuter](ue_ue.ARTrackedGeometry.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetSubsumedBy

▸ **GetSubsumedBy**(): [`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Returns

[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)

#### Defined in

[ue/ue.d.ts:21037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21037)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetTrackingState](ue_ue.ARTrackedGeometry.md#gettrackingstate)

#### Defined in

[ue/ue.d.ts:20874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20874)

___

### GetUnderlyingMesh

▸ **GetUnderlyingMesh**(): [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Returns

[`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetUnderlyingMesh](ue_ue.ARTrackedGeometry.md#getunderlyingmesh)

#### Defined in

[ue/ue.d.ts:20875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20875)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetWorld](ue_ue.ARTrackedGeometry.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[IsTracked](ue_ue.ARTrackedGeometry.md#istracked)

#### Defined in

[ue/ue.d.ts:20876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20876)

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

#### Defined in

[ue/ue.d.ts:21039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21039)

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

#### Defined in

[ue/ue.d.ts:21040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21040)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[StaticClass](ue_ue.ARTrackedGeometry.md#staticclass)

#### Defined in

[ue/ue.d.ts:21038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21038)
