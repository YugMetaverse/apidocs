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

#### Defined in

[ue/ue.d.ts:21206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21206)

## Properties

### BlendShapes

• **BlendShapes**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md), `number`\>

#### Defined in

[ue/ue.d.ts:21209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21209)

___

### DebugName

• **DebugName**: `string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[DebugName](ue_ue.ARTrackedGeometry.md#debugname)

#### Defined in

[ue/ue.d.ts:20867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20867)

___

### LastUpdateFrameNumber

• **LastUpdateFrameNumber**: `number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#lastupdateframenumber)

#### Defined in

[ue/ue.d.ts:20866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20866)

___

### LocalToAlignedTrackingTransform

• **LocalToAlignedTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LocalToAlignedTrackingTransform](ue_ue.ARTrackedGeometry.md#localtoalignedtrackingtransform)

#### Defined in

[ue/ue.d.ts:20862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20862)

___

### LocalToTrackingTransform

• **LocalToTrackingTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[LocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#localtotrackingtransform)

#### Defined in

[ue/ue.d.ts:20861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20861)

___

### LookAtTarget

• **LookAtTarget**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:21207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21207)

___

### ObjectClassification

• **ObjectClassification**: [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[ObjectClassification](ue_ue.ARTrackedGeometry.md#objectclassification)

#### Defined in

[ue/ue.d.ts:20865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20865)

___

### TrackingState

• **TrackingState**: [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[TrackingState](ue_ue.ARTrackedGeometry.md#trackingstate)

#### Defined in

[ue/ue.d.ts:20863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20863)

___

### UnderlyingMesh

• **UnderlyingMesh**: [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[UnderlyingMesh](ue_ue.ARTrackedGeometry.md#underlyingmesh)

#### Defined in

[ue/ue.d.ts:20864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20864)

___

### UniqueId

• **UniqueId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[UniqueId](ue_ue.ARTrackedGeometry.md#uniqueid)

#### Defined in

[ue/ue.d.ts:20860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20860)

___

### \_\_tid\_ARFaceGeometry\_\_

• **\_\_tid\_ARFaceGeometry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21218)

___

### \_\_tid\_ARTrackedGeometry\_\_

• **\_\_tid\_ARTrackedGeometry\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_ARTrackedGeometry__](ue_ue.ARTrackedGeometry.md#__tid_artrackedgeometry__)

#### Defined in

[ue/ue.d.ts:20881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20881)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[__tid_Object__](ue_ue.ARTrackedGeometry.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsTracked

• **bIsTracked**: `boolean`

#### Defined in

[ue/ue.d.ts:21208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21208)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBlendShapeValue

▸ **GetBlendShapeValue**(`BlendShape`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BlendShape` | [`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:21211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21211)

___

### GetBlendShapes

▸ **GetBlendShapes**(): [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md), `number`\>

#### Returns

[`TMap`](../interfaces/ue_puerts.TMap.md)<[`EARFaceBlendShape`](../enums/ue_ue.EARFaceBlendShape.md), `number`\>

#### Defined in

[ue/ue.d.ts:21210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21210)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetClass](ue_ue.ARTrackedGeometry.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetDebugName

▸ **GetDebugName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetDebugName](ue_ue.ARTrackedGeometry.md#getdebugname)

#### Defined in

[ue/ue.d.ts:20868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20868)

___

### GetLastUpdateFrameNumber

▸ **GetLastUpdateFrameNumber**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLastUpdateFrameNumber](ue_ue.ARTrackedGeometry.md#getlastupdateframenumber)

#### Defined in

[ue/ue.d.ts:20869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20869)

___

### GetLastUpdateTimestamp

▸ **GetLastUpdateTimestamp**(): `number`

#### Returns

`number`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLastUpdateTimestamp](ue_ue.ARTrackedGeometry.md#getlastupdatetimestamp)

#### Defined in

[ue/ue.d.ts:20870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20870)

___

### GetLocalSpaceEyeTransform

▸ **GetLocalSpaceEyeTransform**(`Eye`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Eye` | [`EAREye`](../enums/ue_ue.EAREye.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:21212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21212)

___

### GetLocalToTrackingTransform

▸ **GetLocalToTrackingTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLocalToTrackingTransform](ue_ue.ARTrackedGeometry.md#getlocaltotrackingtransform)

#### Defined in

[ue/ue.d.ts:20871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20871)

___

### GetLocalToWorldTransform

▸ **GetLocalToWorldTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetLocalToWorldTransform](ue_ue.ARTrackedGeometry.md#getlocaltoworldtransform)

#### Defined in

[ue/ue.d.ts:20872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20872)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetName](ue_ue.ARTrackedGeometry.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetObjectClassification

▸ **GetObjectClassification**(): [`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Returns

[`EARObjectClassification`](../enums/ue_ue.EARObjectClassification.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetObjectClassification](ue_ue.ARTrackedGeometry.md#getobjectclassification)

#### Defined in

[ue/ue.d.ts:20873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20873)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetOuter](ue_ue.ARTrackedGeometry.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetTrackingState

▸ **GetTrackingState**(): [`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Returns

[`EARTrackingState`](../enums/ue_ue.EARTrackingState.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetTrackingState](ue_ue.ARTrackedGeometry.md#gettrackingstate)

#### Defined in

[ue/ue.d.ts:20874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20874)

___

### GetUnderlyingMesh

▸ **GetUnderlyingMesh**(): [`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Returns

[`MRMeshComponent`](ue_ue.MRMeshComponent.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetUnderlyingMesh](ue_ue.ARTrackedGeometry.md#getunderlyingmesh)

#### Defined in

[ue/ue.d.ts:20875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20875)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[GetWorld](ue_ue.ARTrackedGeometry.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### GetWorldSpaceEyeTransform

▸ **GetWorldSpaceEyeTransform**(`Eye`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Eye` | [`EAREye`](../enums/ue_ue.EAREye.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:21213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21213)

___

### IsTracked

▸ **IsTracked**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[IsTracked](ue_ue.ARTrackedGeometry.md#istracked)

#### Defined in

[ue/ue.d.ts:20876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20876)

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

#### Defined in

[ue/ue.d.ts:21215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21215)

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

#### Defined in

[ue/ue.d.ts:21216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21216)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARTrackedGeometry](ue_ue.ARTrackedGeometry.md).[StaticClass](ue_ue.ARTrackedGeometry.md#staticclass)

#### Defined in

[ue/ue.d.ts:21214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21214)
