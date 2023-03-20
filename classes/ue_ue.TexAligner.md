[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TexAligner

# Class: TexAligner

[ue/ue](../modules/ue_ue.md).TexAligner

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TexAligner`**

  ↳↳ [`TexAlignerBox`](ue_ue.TexAlignerBox.md)

  ↳↳ [`TexAlignerDefault`](ue_ue.TexAlignerDefault.md)

  ↳↳ [`TexAlignerFit`](ue_ue.TexAlignerFit.md)

  ↳↳ [`TexAlignerPlanar`](ue_ue.TexAlignerPlanar.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TexAligner.md#constructor)

### Properties

- [DefTexAlign](ue_ue.TexAligner.md#deftexalign)
- [Desc](ue_ue.TexAligner.md#desc)
- [TAxis](ue_ue.TexAligner.md#taxis)
- [UTile](ue_ue.TexAligner.md#utile)
- [VTile](ue_ue.TexAligner.md#vtile)
- [\_\_tid\_Object\_\_](ue_ue.TexAligner.md#__tid_object__)
- [\_\_tid\_TexAligner\_\_](ue_ue.TexAligner.md#__tid_texaligner__)

### Methods

- [CreateDefaultSubobject](ue_ue.TexAligner.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TexAligner.md#executeubergraph)
- [GetClass](ue_ue.TexAligner.md#getclass)
- [GetName](ue_ue.TexAligner.md#getname)
- [GetOuter](ue_ue.TexAligner.md#getouter)
- [GetWorld](ue_ue.TexAligner.md#getworld)
- [Find](ue_ue.TexAligner.md#find)
- [Load](ue_ue.TexAligner.md#load)
- [StaticClass](ue_ue.TexAligner.md#staticclass)

## Constructors

### constructor

• **new TexAligner**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DefTexAlign

• **DefTexAlign**: [`ETexAlign`](../enums/ue_ue.ETexAlign.md)

___

### Desc

• **Desc**: `string`

___

### TAxis

• **TAxis**: `number`

___

### UTile

• **UTile**: `number`

___

### VTile

• **VTile**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TexAligner\_\_

• **\_\_tid\_TexAligner\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TexAligner`](ue_ue.TexAligner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TexAligner`](ue_ue.TexAligner.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TexAligner`](ue_ue.TexAligner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TexAligner`](ue_ue.TexAligner.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
