[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BoolBinding

# Class: BoolBinding

[ue/ue](../modules/ue_ue.md).BoolBinding

## Hierarchy

- [`PropertyBinding`](ue_ue.PropertyBinding.md)

  ↳ **`BoolBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.BoolBinding.md#constructor)

### Properties

- [DestinationProperty](ue_ue.BoolBinding.md#destinationproperty)
- [SourceObject](ue_ue.BoolBinding.md#sourceobject)
- [SourcePath](ue_ue.BoolBinding.md#sourcepath)
- [\_\_tid\_BoolBinding\_\_](ue_ue.BoolBinding.md#__tid_boolbinding__)
- [\_\_tid\_Object\_\_](ue_ue.BoolBinding.md#__tid_object__)
- [\_\_tid\_PropertyBinding\_\_](ue_ue.BoolBinding.md#__tid_propertybinding__)

### Methods

- [CreateDefaultSubobject](ue_ue.BoolBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BoolBinding.md#executeubergraph)
- [GetClass](ue_ue.BoolBinding.md#getclass)
- [GetName](ue_ue.BoolBinding.md#getname)
- [GetOuter](ue_ue.BoolBinding.md#getouter)
- [GetValue](ue_ue.BoolBinding.md#getvalue)
- [GetWorld](ue_ue.BoolBinding.md#getworld)
- [Find](ue_ue.BoolBinding.md#find)
- [Load](ue_ue.BoolBinding.md#load)
- [StaticClass](ue_ue.BoolBinding.md#staticclass)

## Constructors

### constructor

• **new BoolBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[constructor](ue_ue.PropertyBinding.md#constructor)

## Properties

### DestinationProperty

• **DestinationProperty**: `string`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[DestinationProperty](ue_ue.PropertyBinding.md#destinationproperty)

___

### SourceObject

• **SourceObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[SourceObject](ue_ue.PropertyBinding.md#sourceobject)

___

### SourcePath

• **SourcePath**: [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[SourcePath](ue_ue.PropertyBinding.md#sourcepath)

___

### \_\_tid\_BoolBinding\_\_

• **\_\_tid\_BoolBinding\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[__tid_Object__](ue_ue.PropertyBinding.md#__tid_object__)

___

### \_\_tid\_PropertyBinding\_\_

• **\_\_tid\_PropertyBinding\_\_**: `boolean`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[__tid_PropertyBinding__](ue_ue.PropertyBinding.md#__tid_propertybinding__)

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

[PropertyBinding](ue_ue.PropertyBinding.md).[CreateDefaultSubobject](ue_ue.PropertyBinding.md#createdefaultsubobject)

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

[PropertyBinding](ue_ue.PropertyBinding.md).[ExecuteUbergraph](ue_ue.PropertyBinding.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetClass](ue_ue.PropertyBinding.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetName](ue_ue.PropertyBinding.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetOuter](ue_ue.PropertyBinding.md#getouter)

___

### GetValue

▸ **GetValue**(): `boolean`

#### Returns

`boolean`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetWorld](ue_ue.PropertyBinding.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BoolBinding`](ue_ue.BoolBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BoolBinding`](ue_ue.BoolBinding.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[Find](ue_ue.PropertyBinding.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BoolBinding`](ue_ue.BoolBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BoolBinding`](ue_ue.BoolBinding.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[Load](ue_ue.PropertyBinding.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[StaticClass](ue_ue.PropertyBinding.md#staticclass)
