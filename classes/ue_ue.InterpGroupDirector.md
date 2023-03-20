[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpGroupDirector

# Class: InterpGroupDirector

[ue/ue](../modules/ue_ue.md).InterpGroupDirector

## Hierarchy

- [`InterpGroup`](ue_ue.InterpGroup.md)

  ↳ **`InterpGroupDirector`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpGroupDirector.md#constructor)

### Properties

- [GroupColor](ue_ue.InterpGroupDirector.md#groupcolor)
- [GroupName](ue_ue.InterpGroupDirector.md#groupname)
- [InterpTracks](ue_ue.InterpGroupDirector.md#interptracks)
- [\_\_tid\_InterpGroupDirector\_\_](ue_ue.InterpGroupDirector.md#__tid_interpgroupdirector__)
- [\_\_tid\_InterpGroup\_\_](ue_ue.InterpGroupDirector.md#__tid_interpgroup__)
- [\_\_tid\_Object\_\_](ue_ue.InterpGroupDirector.md#__tid_object__)
- [bCollapsed](ue_ue.InterpGroupDirector.md#bcollapsed)
- [bIsFolder](ue_ue.InterpGroupDirector.md#bisfolder)
- [bIsParented](ue_ue.InterpGroupDirector.md#bisparented)
- [bIsSelected](ue_ue.InterpGroupDirector.md#bisselected)
- [bVisible](ue_ue.InterpGroupDirector.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpGroupDirector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpGroupDirector.md#executeubergraph)
- [GetClass](ue_ue.InterpGroupDirector.md#getclass)
- [GetName](ue_ue.InterpGroupDirector.md#getname)
- [GetOuter](ue_ue.InterpGroupDirector.md#getouter)
- [GetWorld](ue_ue.InterpGroupDirector.md#getworld)
- [Find](ue_ue.InterpGroupDirector.md#find)
- [Load](ue_ue.InterpGroupDirector.md#load)
- [StaticClass](ue_ue.InterpGroupDirector.md#staticclass)

## Constructors

### constructor

• **new InterpGroupDirector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[constructor](ue_ue.InterpGroup.md#constructor)

#### Defined in

[ue/ue.d.ts:12993](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12993)

## Properties

### GroupColor

• **GroupColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GroupColor](ue_ue.InterpGroup.md#groupcolor)

#### Defined in

[ue/ue.d.ts:7510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7510)

___

### GroupName

• **GroupName**: `string`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GroupName](ue_ue.InterpGroup.md#groupname)

#### Defined in

[ue/ue.d.ts:7509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7509)

___

### InterpTracks

• **InterpTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[InterpTracks](ue_ue.InterpGroup.md#interptracks)

#### Defined in

[ue/ue.d.ts:7508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7508)

___

### \_\_tid\_InterpGroupDirector\_\_

• **\_\_tid\_InterpGroupDirector\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:12998](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12998)

___

### \_\_tid\_InterpGroup\_\_

• **\_\_tid\_InterpGroup\_\_**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[__tid_InterpGroup__](ue_ue.InterpGroup.md#__tid_interpgroup__)

#### Defined in

[ue/ue.d.ts:7520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7520)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[__tid_Object__](ue_ue.InterpGroup.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bCollapsed](ue_ue.InterpGroup.md#bcollapsed)

#### Defined in

[ue/ue.d.ts:7511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7511)

___

### bIsFolder

• **bIsFolder**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bIsFolder](ue_ue.InterpGroup.md#bisfolder)

#### Defined in

[ue/ue.d.ts:7513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7513)

___

### bIsParented

• **bIsParented**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bIsParented](ue_ue.InterpGroup.md#bisparented)

#### Defined in

[ue/ue.d.ts:7514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7514)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bIsSelected](ue_ue.InterpGroup.md#bisselected)

#### Defined in

[ue/ue.d.ts:7515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7515)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[bVisible](ue_ue.InterpGroup.md#bvisible)

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

[InterpGroup](ue_ue.InterpGroup.md).[CreateDefaultSubobject](ue_ue.InterpGroup.md#createdefaultsubobject)

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

[InterpGroup](ue_ue.InterpGroup.md).[ExecuteUbergraph](ue_ue.InterpGroup.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetClass](ue_ue.InterpGroup.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetName](ue_ue.InterpGroup.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetOuter](ue_ue.InterpGroup.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpGroup](ue_ue.InterpGroup.md).[GetWorld](ue_ue.InterpGroup.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[Find](ue_ue.InterpGroup.md#find)

#### Defined in

[ue/ue.d.ts:12995](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12995)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[Load](ue_ue.InterpGroup.md#load)

#### Defined in

[ue/ue.d.ts:12996](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12996)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpGroup](ue_ue.InterpGroup.md).[StaticClass](ue_ue.InterpGroup.md#staticclass)

#### Defined in

[ue/ue.d.ts:12994](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12994)
