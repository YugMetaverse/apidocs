[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DynamicBlueprintBinding

# Class: DynamicBlueprintBinding

[ue/ue](../modules/ue_ue.md).DynamicBlueprintBinding

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DynamicBlueprintBinding`**

  ↳↳ [`ComponentDelegateBinding`](ue_ue.ComponentDelegateBinding.md)

  ↳↳ [`InputDelegateBinding`](ue_ue.InputDelegateBinding.md)

  ↳↳ [`WidgetAnimationDelegateBinding`](ue_ue.WidgetAnimationDelegateBinding.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DynamicBlueprintBinding.md#constructor)

### Properties

- [\_\_tid\_DynamicBlueprintBinding\_\_](ue_ue.DynamicBlueprintBinding.md#__tid_dynamicblueprintbinding__)
- [\_\_tid\_Object\_\_](ue_ue.DynamicBlueprintBinding.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DynamicBlueprintBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DynamicBlueprintBinding.md#executeubergraph)
- [GetClass](ue_ue.DynamicBlueprintBinding.md#getclass)
- [GetName](ue_ue.DynamicBlueprintBinding.md#getname)
- [GetOuter](ue_ue.DynamicBlueprintBinding.md#getouter)
- [GetWorld](ue_ue.DynamicBlueprintBinding.md#getworld)
- [Find](ue_ue.DynamicBlueprintBinding.md#find)
- [Load](ue_ue.DynamicBlueprintBinding.md#load)
- [StaticClass](ue_ue.DynamicBlueprintBinding.md#staticclass)

## Constructors

### constructor

• **new DynamicBlueprintBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_DynamicBlueprintBinding\_\_

• **\_\_tid\_DynamicBlueprintBinding\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
