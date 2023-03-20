[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpGroup

# Class: InterpGroup

[ue/ue](../modules/ue_ue.md).InterpGroup

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InterpGroup`**

  ↳↳ [`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

  ↳↳ [`InterpGroupCamera`](ue_ue.InterpGroupCamera.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InterpGroup.md#constructor)

### Properties

- [GroupColor](ue_ue.InterpGroup.md#groupcolor)
- [GroupName](ue_ue.InterpGroup.md#groupname)
- [InterpTracks](ue_ue.InterpGroup.md#interptracks)
- [\_\_tid\_InterpGroup\_\_](ue_ue.InterpGroup.md#__tid_interpgroup__)
- [\_\_tid\_Object\_\_](ue_ue.InterpGroup.md#__tid_object__)
- [bCollapsed](ue_ue.InterpGroup.md#bcollapsed)
- [bIsFolder](ue_ue.InterpGroup.md#bisfolder)
- [bIsParented](ue_ue.InterpGroup.md#bisparented)
- [bIsSelected](ue_ue.InterpGroup.md#bisselected)
- [bVisible](ue_ue.InterpGroup.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpGroup.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpGroup.md#executeubergraph)
- [GetClass](ue_ue.InterpGroup.md#getclass)
- [GetName](ue_ue.InterpGroup.md#getname)
- [GetOuter](ue_ue.InterpGroup.md#getouter)
- [GetWorld](ue_ue.InterpGroup.md#getworld)
- [Find](ue_ue.InterpGroup.md#find)
- [Load](ue_ue.InterpGroup.md#load)
- [StaticClass](ue_ue.InterpGroup.md#staticclass)

## Constructors

### constructor

• **new InterpGroup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:7507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7507)

## Properties

### GroupColor

• **GroupColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:7510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7510)

___

### GroupName

• **GroupName**: `string`

#### Defined in

[ue/ue.d.ts:7509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7509)

___

### InterpTracks

• **InterpTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Defined in

[ue/ue.d.ts:7508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7508)

___

### \_\_tid\_InterpGroup\_\_

• **\_\_tid\_InterpGroup\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7520)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Defined in

[ue/ue.d.ts:7511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7511)

___

### bIsFolder

• **bIsFolder**: `boolean`

#### Defined in

[ue/ue.d.ts:7513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7513)

___

### bIsParented

• **bIsParented**: `boolean`

#### Defined in

[ue/ue.d.ts:7514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7514)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Defined in

[ue/ue.d.ts:7515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7515)

___

### bVisible

• **bVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:7512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7512)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpGroup`](ue_ue.InterpGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpGroup`](ue_ue.InterpGroup.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:7517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7517)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpGroup`](ue_ue.InterpGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpGroup`](ue_ue.InterpGroup.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:7518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7518)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:7516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7516)
