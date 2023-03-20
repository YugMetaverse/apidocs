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

## Properties

### Actors

• **Actors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>\>

___

### CurrentDim

• **CurrentDim**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### CurrentKB

• **CurrentKB**: `number`

___

### Format

• **Format**: [`EPixelFormat`](../enums/ue_ue.EPixelFormat.md)

___

### FullyLoadedKB

• **FullyLoadedKB**: `number`

___

### Group

• **Group**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

___

### LODBias

• **LODBias**: `number`

___

### LastTimeRendered

• **LastTimeRendered**: `number`

___

### MaxDim

• **MaxDim**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### NumUses

• **NumUses**: `number`

___

### Path

• **Path**: `string`

___

### Texture

• **Texture**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Texture`](ue_ue.Texture.md)\>

___

### Type

• **Type**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TextureStats\_\_

• **\_\_tid\_TextureStats\_\_**: `boolean`

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

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
