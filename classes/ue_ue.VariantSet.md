[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VariantSet

# Class: VariantSet

[ue/ue](../modules/ue_ue.md).VariantSet

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`VariantSet`**

## Table of contents

### Constructors

- [constructor](ue_ue.VariantSet.md#constructor)

### Properties

- [DisplayText](ue_ue.VariantSet.md#displaytext)
- [Variants](ue_ue.VariantSet.md#variants)
- [\_\_tid\_Object\_\_](ue_ue.VariantSet.md#__tid_object__)
- [\_\_tid\_VariantSet\_\_](ue_ue.VariantSet.md#__tid_variantset__)
- [bExpanded](ue_ue.VariantSet.md#bexpanded)

### Methods

- [CreateDefaultSubobject](ue_ue.VariantSet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VariantSet.md#executeubergraph)
- [GetClass](ue_ue.VariantSet.md#getclass)
- [GetDisplayText](ue_ue.VariantSet.md#getdisplaytext)
- [GetName](ue_ue.VariantSet.md#getname)
- [GetNumVariants](ue_ue.VariantSet.md#getnumvariants)
- [GetOuter](ue_ue.VariantSet.md#getouter)
- [GetVariant](ue_ue.VariantSet.md#getvariant)
- [GetVariantByName](ue_ue.VariantSet.md#getvariantbyname)
- [GetWorld](ue_ue.VariantSet.md#getworld)
- [SetDisplayText](ue_ue.VariantSet.md#setdisplaytext)
- [Find](ue_ue.VariantSet.md#find)
- [Load](ue_ue.VariantSet.md#load)
- [StaticClass](ue_ue.VariantSet.md#staticclass)

## Constructors

### constructor

• **new VariantSet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DisplayText

• **DisplayText**: `string`

___

### Variants

• **Variants**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Variant`](ue_ue.Variant.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_VariantSet\_\_

• **\_\_tid\_VariantSet\_\_**: `boolean`

___

### bExpanded

• **bExpanded**: `boolean`

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

### GetDisplayText

▸ **GetDisplayText**(): `string`

#### Returns

`string`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetNumVariants

▸ **GetNumVariants**(): `number`

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetVariant

▸ **GetVariant**(`VariantIndex`): [`Variant`](ue_ue.Variant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VariantIndex` | `number` |

#### Returns

[`Variant`](ue_ue.Variant.md)

___

### GetVariantByName

▸ **GetVariantByName**(`VariantName`): [`Variant`](ue_ue.Variant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VariantName` | `string` |

#### Returns

[`Variant`](ue_ue.Variant.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### SetDisplayText

▸ **SetDisplayText**(`NewDisplayText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDisplayText` | `string` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VariantSet`](ue_ue.VariantSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VariantSet`](ue_ue.VariantSet.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VariantSet`](ue_ue.VariantSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VariantSet`](ue_ue.VariantSet.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
