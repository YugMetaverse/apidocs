[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InputDelegateBinding

# Class: InputDelegateBinding

[ue/ue](../modules/ue_ue.md).InputDelegateBinding

## Hierarchy

- [`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)

  ↳ **`InputDelegateBinding`**

  ↳↳ [`InputActionDelegateBinding`](ue_ue.InputActionDelegateBinding.md)

  ↳↳ [`InputAxisDelegateBinding`](ue_ue.InputAxisDelegateBinding.md)

  ↳↳ [`InputAxisKeyDelegateBinding`](ue_ue.InputAxisKeyDelegateBinding.md)

  ↳↳ [`InputKeyDelegateBinding`](ue_ue.InputKeyDelegateBinding.md)

  ↳↳ [`InputTouchDelegateBinding`](ue_ue.InputTouchDelegateBinding.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InputDelegateBinding.md#constructor)

### Properties

- [\_\_tid\_DynamicBlueprintBinding\_\_](ue_ue.InputDelegateBinding.md#__tid_dynamicblueprintbinding__)
- [\_\_tid\_InputDelegateBinding\_\_](ue_ue.InputDelegateBinding.md#__tid_inputdelegatebinding__)
- [\_\_tid\_Object\_\_](ue_ue.InputDelegateBinding.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InputDelegateBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InputDelegateBinding.md#executeubergraph)
- [GetClass](ue_ue.InputDelegateBinding.md#getclass)
- [GetName](ue_ue.InputDelegateBinding.md#getname)
- [GetOuter](ue_ue.InputDelegateBinding.md#getouter)
- [GetWorld](ue_ue.InputDelegateBinding.md#getworld)
- [Find](ue_ue.InputDelegateBinding.md#find)
- [Load](ue_ue.InputDelegateBinding.md#load)
- [StaticClass](ue_ue.InputDelegateBinding.md#staticclass)

## Constructors

### constructor

• **new InputDelegateBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[constructor](ue_ue.DynamicBlueprintBinding.md#constructor)

## Properties

### \_\_tid\_DynamicBlueprintBinding\_\_

• **\_\_tid\_DynamicBlueprintBinding\_\_**: `boolean`

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[__tid_DynamicBlueprintBinding__](ue_ue.DynamicBlueprintBinding.md#__tid_dynamicblueprintbinding__)

___

### \_\_tid\_InputDelegateBinding\_\_

• **\_\_tid\_InputDelegateBinding\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[__tid_Object__](ue_ue.DynamicBlueprintBinding.md#__tid_object__)

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

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[CreateDefaultSubobject](ue_ue.DynamicBlueprintBinding.md#createdefaultsubobject)

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

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[ExecuteUbergraph](ue_ue.DynamicBlueprintBinding.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetClass](ue_ue.DynamicBlueprintBinding.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetName](ue_ue.DynamicBlueprintBinding.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetOuter](ue_ue.DynamicBlueprintBinding.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetWorld](ue_ue.DynamicBlueprintBinding.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InputDelegateBinding`](ue_ue.InputDelegateBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InputDelegateBinding`](ue_ue.InputDelegateBinding.md)

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[Find](ue_ue.DynamicBlueprintBinding.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InputDelegateBinding`](ue_ue.InputDelegateBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InputDelegateBinding`](ue_ue.InputDelegateBinding.md)

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[Load](ue_ue.DynamicBlueprintBinding.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[StaticClass](ue_ue.DynamicBlueprintBinding.md#staticclass)
