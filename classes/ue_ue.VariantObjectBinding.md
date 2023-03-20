[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VariantObjectBinding

# Class: VariantObjectBinding

[ue/ue](../modules/ue_ue.md).VariantObjectBinding

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`VariantObjectBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.VariantObjectBinding.md#constructor)

### Properties

- [CapturedProperties](ue_ue.VariantObjectBinding.md#capturedproperties)
- [FunctionCallers](ue_ue.VariantObjectBinding.md#functioncallers)
- [LazyObjectPtr](ue_ue.VariantObjectBinding.md#lazyobjectptr)
- [ObjectPtr](ue_ue.VariantObjectBinding.md#objectptr)
- [\_\_tid\_Object\_\_](ue_ue.VariantObjectBinding.md#__tid_object__)
- [\_\_tid\_VariantObjectBinding\_\_](ue_ue.VariantObjectBinding.md#__tid_variantobjectbinding__)

### Methods

- [CreateDefaultSubobject](ue_ue.VariantObjectBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VariantObjectBinding.md#executeubergraph)
- [GetClass](ue_ue.VariantObjectBinding.md#getclass)
- [GetName](ue_ue.VariantObjectBinding.md#getname)
- [GetOuter](ue_ue.VariantObjectBinding.md#getouter)
- [GetWorld](ue_ue.VariantObjectBinding.md#getworld)
- [Find](ue_ue.VariantObjectBinding.md#find)
- [Load](ue_ue.VariantObjectBinding.md#load)
- [StaticClass](ue_ue.VariantObjectBinding.md#staticclass)

## Constructors

### constructor

• **new VariantObjectBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### CapturedProperties

• **CapturedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyValue`](ue_ue.PropertyValue.md)\>

___

### FunctionCallers

• **FunctionCallers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FunctionCaller`](ue_ue.FunctionCaller.md)\>

___

### LazyObjectPtr

• **LazyObjectPtr**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### ObjectPtr

• **ObjectPtr**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_VariantObjectBinding\_\_

• **\_\_tid\_VariantObjectBinding\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VariantObjectBinding`](ue_ue.VariantObjectBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VariantObjectBinding`](ue_ue.VariantObjectBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VariantObjectBinding`](ue_ue.VariantObjectBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VariantObjectBinding`](ue_ue.VariantObjectBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
