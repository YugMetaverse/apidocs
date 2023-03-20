[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpGroupCamera

# Class: InterpGroupCamera

[ue/ue](../modules/ue_ue.md).InterpGroupCamera

## Hierarchy

- [`InterpGroup`](ue_ue.InterpGroup.md)

  ↳ **`InterpGroupCamera`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpGroupCamera.md#constructor)

### Properties

- [CameraAnimInst](ue_ue.InterpGroupCamera.md#cameraaniminst)
- [CompressTolerance](ue_ue.InterpGroupCamera.md#compresstolerance)
- [GroupColor](ue_ue.InterpGroupCamera.md#groupcolor)
- [GroupName](ue_ue.InterpGroupCamera.md#groupname)
- [InterpTracks](ue_ue.InterpGroupCamera.md#interptracks)
- [Target](ue_ue.InterpGroupCamera.md#target)
- [\_\_tid\_InterpGroupCamera\_\_](ue_ue.InterpGroupCamera.md#__tid_interpgroupcamera__)
- [\_\_tid\_InterpGroup\_\_](ue_ue.InterpGroupCamera.md#__tid_interpgroup__)
- [\_\_tid\_Object\_\_](ue_ue.InterpGroupCamera.md#__tid_object__)
- [bCollapsed](ue_ue.InterpGroupCamera.md#bcollapsed)
- [bIsFolder](ue_ue.InterpGroupCamera.md#bisfolder)
- [bIsParented](ue_ue.InterpGroupCamera.md#bisparented)
- [bIsSelected](ue_ue.InterpGroupCamera.md#bisselected)
- [bVisible](ue_ue.InterpGroupCamera.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpGroupCamera.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpGroupCamera.md#executeubergraph)
- [GetClass](ue_ue.InterpGroupCamera.md#getclass)
- [GetName](ue_ue.InterpGroupCamera.md#getname)
- [GetOuter](ue_ue.InterpGroupCamera.md#getouter)
- [GetWorld](ue_ue.InterpGroupCamera.md#getworld)
- [Find](ue_ue.InterpGroupCamera.md#find)
- [Load](ue_ue.InterpGroupCamera.md#load)
- [StaticClass](ue_ue.InterpGroupCamera.md#staticclass)

## Constructors

### constructor

• **new InterpGroupCamera**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[constructor](ue_ue.InterpGroup.md#constructor)

#### Defined in

[ue/ue.d.ts:39684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39684)

## Properties

### CameraAnimInst

• **CameraAnimInst**: [`CameraAnim`](ue_ue.CameraAnim.md)

#### Defined in

[ue/ue.d.ts:39685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39685)

___

### CompressTolerance

• **CompressTolerance**: `number`

#### Defined in

[ue/ue.d.ts:39687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39687)

___

### GroupColor

• **GroupColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GroupColor](ue_ue.InterpGroup.md#groupcolor)

#### Defined in

[ue/ue.d.ts:7510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7510)

___

### GroupName

• **GroupName**: `string`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GroupName](ue_ue.InterpGroup.md#groupname)

#### Defined in

[ue/ue.d.ts:7509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7509)

___

### InterpTracks

• **InterpTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[InterpTracks](ue_ue.InterpGroup.md#interptracks)

#### Defined in

[ue/ue.d.ts:7508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7508)

___

### Target

• **Target**: [`CameraPreviewInfo`](ue_ue.CameraPreviewInfo.md)

#### Defined in

[ue/ue.d.ts:39686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39686)

___

### \_\_tid\_InterpGroupCamera\_\_

• **\_\_tid\_InterpGroupCamera\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39692)

___

### \_\_tid\_InterpGroup\_\_

• **\_\_tid\_InterpGroup\_\_**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[__tid_InterpGroup__](ue_ue.InterpGroup.md#__tid_interpgroup__)

#### Defined in

[ue/ue.d.ts:7520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7520)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[__tid_Object__](ue_ue.InterpGroup.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bCollapsed](ue_ue.InterpGroup.md#bcollapsed)

#### Defined in

[ue/ue.d.ts:7511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7511)

___

### bIsFolder

• **bIsFolder**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bIsFolder](ue_ue.InterpGroup.md#bisfolder)

#### Defined in

[ue/ue.d.ts:7513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7513)

___

### bIsParented

• **bIsParented**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bIsParented](ue_ue.InterpGroup.md#bisparented)

#### Defined in

[ue/ue.d.ts:7514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7514)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bIsSelected](ue_ue.InterpGroup.md#bisselected)

#### Defined in

[ue/ue.d.ts:7515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7515)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bVisible](ue_ue.InterpGroup.md#bvisible)

#### Defined in

[ue/ue.d.ts:7512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7512)

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

[InterpGroup](ue_ue.InterpGroup.md).[CreateDefaultSubobject](ue_ue.InterpGroup.md#createdefaultsubobject)

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

[InterpGroup](ue_ue.InterpGroup.md).[ExecuteUbergraph](ue_ue.InterpGroup.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetClass](ue_ue.InterpGroup.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetName](ue_ue.InterpGroup.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetOuter](ue_ue.InterpGroup.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetWorld](ue_ue.InterpGroup.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpGroupCamera`](ue_ue.InterpGroupCamera.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpGroupCamera`](ue_ue.InterpGroupCamera.md)

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[Find](ue_ue.InterpGroup.md#find)

#### Defined in

[ue/ue.d.ts:39689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39689)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpGroupCamera`](ue_ue.InterpGroupCamera.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpGroupCamera`](ue_ue.InterpGroupCamera.md)

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[Load](ue_ue.InterpGroup.md#load)

#### Defined in

[ue/ue.d.ts:39690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39690)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[StaticClass](ue_ue.InterpGroup.md#staticclass)

#### Defined in

[ue/ue.d.ts:39688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39688)
