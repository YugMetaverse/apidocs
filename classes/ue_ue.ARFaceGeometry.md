[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARFaceGeometry

# Class: ARFaceGeometry

[ue/ue](../modules/ue_ue.md).ARFaceGeometry

## Hierarchy

- [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)

  ↳ **`ARFaceGeometry`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARFaceGeometry.md#constructor)

### Properties

- [BlendShapes](ue_ue.ARFaceGeometry.md#blendshapes)
- [DebugName](ue_ue.ARFaceGeometry.md#debugname)
- [LastUpdateFrameNumber](ue_ue.ARFaceGeometry.md#lastupdateframenumber)
- [LocalToAlignedTrackingTransform](ue_ue.ARFaceGeometry.md#localtoalignedtrackingtransform)
- [LocalToTrackingTransform](ue_ue.ARFaceGeometry.md#localtotrackingtransform)
- [LookAtTarget](ue_ue.ARFaceGeometry.md#lookattarget)
- [ObjectClassification](ue_ue.ARFaceGeometry.md#objectclassification)
- [TrackingState](ue_ue.ARFaceGeometry.md#trackingstate)
- [UnderlyingMesh](ue_ue.ARFaceGeometry.md#underlyingmesh)
- [UniqueId](ue_ue.ARFaceGeometry.md#uniqueid)
- [\_\_tid\_ARFaceGeometry\_\_](ue_ue.ARFaceGeometry.md#__tid_arfacegeometry__)
- [\_\_tid\_ARTrackedGeometry\_\_](ue_ue.ARFaceGeometry.md#__tid_artrackedgeometry__)
- [\_\_tid\_Object\_\_](ue_ue.ARFaceGeometry.md#__tid_object__)
- [bIsTracked](ue_ue.ARFaceGeometry.md#bistracked)

### Methods

- [CreateDefaultSubobject](ue_ue.ARFaceGeometry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARFaceGeometry.md#executeubergraph)
- [GetBlendShapeValue](ue_ue.ARFaceGeometry.md#getblendshapevalue)
- [GetBlendShapes](ue_ue.ARFaceGeometry.md#getblendshapes)
- [GetClass](ue_ue.ARFaceGeometry.md#getclass)
- [GetDebugName](ue_ue.ARFaceGeometry.md#getdebugname)
- [GetLastUpdateFrameNumber](ue_ue.ARFaceGeometry.md#getlastupdateframenumber)
- [GetLastUpdateTimestamp](ue_ue.ARFaceGeometry.md#getlastupdatetimestamp)
- [GetLocalSpaceEyeTransform](ue_ue.ARFaceGeometry.md#getlocalspaceeyetransform)
- [GetLocalToTrackingTransform](ue_ue.ARFaceGeometry.md#getlocaltotrackingtransform)
- [GetLocalToWorldTransform](ue_ue.ARFaceGeometry.md#getlocaltoworldtransform)
- [GetName](ue_ue.ARFaceGeometry.md#getname)
- [GetObjectClassification](ue_ue.ARFaceGeometry.md#getobjectclassification)
- [GetOuter](ue_ue.ARFaceGeometry.md#getouter)
- [GetTrackingState](ue_ue.ARFaceGeometry.md#gettrackingstate)
- [GetUnderlyingMesh](ue_ue.ARFaceGeometry.md#getunderlyingmesh)
- [GetWorld](ue_ue.ARFaceGeometry.md#getworld)
- [GetWorldSpaceEyeTransform](ue_ue.ARFaceGeometry.md#getworldspaceeyetransform)
- [IsTracked](ue_ue.ARFaceGeometry.md#istracked)
- [Find](ue_ue.ARFaceGeometry.md#find)
- [Load](ue_ue.ARFaceGeometry.md#load)
- [StaticClass](ue_ue.ARFaceGeometry.md#staticclass)

## Constructors

### constructor

• **new ARFaceGeometry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[constructor](ue_ue.ARTrackedGeometry.md#constructor)

## Properties

### BlendShapes

• **BlendShapes**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md), `number`\>

___

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

### LookAtTarget

• **LookAtTarget**: [`Vector`](ue_ue_s.Vector.md)

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

### \_\_tid\_ARFaceGeometry\_\_

• **\_\_tid\_ARFaceGeometry\_\_**: `boolean`

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

___

### bIsTracked

• **bIsTracked**: `boolean`

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

### GetBlendShapeValue

▸ **GetBlendShapeValue**(`BlendShape`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BlendShape` | [`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md) |

#### Returns

`number`

___

### GetBlendShapes

▸ **GetBlendShapes**(): [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md), `number`\>

#### Returns

[`TMap`](../interfaces/ue_puerts.TMap.md)<[`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md), `number`\>

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

### GetLocalSpaceEyeTransform

▸ **GetLocalSpaceEyeTransform**(`Eye`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Eye` | [`EAREye`](../enums/ue_ue.EAREye.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

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

### GetWorldSpaceEyeTransform

▸ **GetWorldSpaceEyeTransform**(`Eye`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Eye` | [`EAREye`](../enums/ue_ue.EAREye.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[IsTracked](ue_ue.ARTrackedGeometry.md#istracked)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[Find](ue_ue.ARTrackedGeometry.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[Load](ue_ue.ARTrackedGeometry.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[StaticClass](ue_ue.ARTrackedGeometry.md#staticclass)
