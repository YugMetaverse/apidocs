[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextureStats

# Class: TextureStats

[ue/ue](../modules/ue_ue.md).TextureStats

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TextureStats`**

## Table of contents

### Constructors

- [constructor](ue_ue.TextureStats.md#constructor)

### Properties

- [Actors](ue_ue.TextureStats.md#actors)
- [CurrentDim](ue_ue.TextureStats.md#currentdim)
- [CurrentKB](ue_ue.TextureStats.md#currentkb)
- [Format](ue_ue.TextureStats.md#format)
- [FullyLoadedKB](ue_ue.TextureStats.md#fullyloadedkb)
- [Group](ue_ue.TextureStats.md#group)
- [LODBias](ue_ue.TextureStats.md#lodbias)
- [LastTimeRendered](ue_ue.TextureStats.md#lasttimerendered)
- [MaxDim](ue_ue.TextureStats.md#maxdim)
- [NumUses](ue_ue.TextureStats.md#numuses)
- [Path](ue_ue.TextureStats.md#path)
- [Texture](ue_ue.TextureStats.md#texture)
- [Type](ue_ue.TextureStats.md#type)
- [\_\_tid\_Object\_\_](ue_ue.TextureStats.md#__tid_object__)
- [\_\_tid\_TextureStats\_\_](ue_ue.TextureStats.md#__tid_texturestats__)

### Methods

- [CreateDefaultSubobject](ue_ue.TextureStats.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TextureStats.md#executeubergraph)
- [GetClass](ue_ue.TextureStats.md#getclass)
- [GetName](ue_ue.TextureStats.md#getname)
- [GetOuter](ue_ue.TextureStats.md#getouter)
- [GetWorld](ue_ue.TextureStats.md#getworld)
- [Find](ue_ue.TextureStats.md#find)
- [Load](ue_ue.TextureStats.md#load)
- [StaticClass](ue_ue.TextureStats.md#staticclass)

## Constructors

### constructor

• **new TextureStats**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:63317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63317)

## Properties

### Actors

• **Actors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>\>

#### Defined in

[ue/ue.d.ts:63319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63319)

___

### CurrentDim

• **CurrentDim**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:63322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63322)

___

### CurrentKB

• **CurrentKB**: `number`

#### Defined in

[ue/ue.d.ts:63326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63326)

___

### Format

• **Format**: [`EPixelFormat`](../enums/ue_ue.EPixelFormat.md)

#### Defined in

[ue/ue.d.ts:63323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63323)

___

### FullyLoadedKB

• **FullyLoadedKB**: `number`

#### Defined in

[ue/ue.d.ts:63327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63327)

___

### Group

• **Group**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

#### Defined in

[ue/ue.d.ts:63324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63324)

___

### LODBias

• **LODBias**: `number`

#### Defined in

[ue/ue.d.ts:63325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63325)

___

### LastTimeRendered

• **LastTimeRendered**: `number`

#### Defined in

[ue/ue.d.ts:63329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63329)

___

### MaxDim

• **MaxDim**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:63321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63321)

___

### NumUses

• **NumUses**: `number`

#### Defined in

[ue/ue.d.ts:63328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63328)

___

### Path

• **Path**: `string`

#### Defined in

[ue/ue.d.ts:63330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63330)

___

### Texture

• **Texture**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Texture`](ue_ue.Texture.md)\>

#### Defined in

[ue/ue.d.ts:63318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63318)

___

### Type

• **Type**: `string`

#### Defined in

[ue/ue.d.ts:63320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63320)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TextureStats\_\_

• **\_\_tid\_TextureStats\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63335)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextureStats`](ue_ue.TextureStats.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextureStats`](ue_ue.TextureStats.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:63332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63332)

___

### Load

▸ `Static` **Load**(`InName`): [`TextureStats`](ue_ue.TextureStats.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextureStats`](ue_ue.TextureStats.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:63333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63333)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:63331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63331)
