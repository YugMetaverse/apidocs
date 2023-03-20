[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ComponentDelegateBinding

# Class: ComponentDelegateBinding

[ue/ue](../modules/ue_ue.md).ComponentDelegateBinding

## Hierarchy

- [`DynamicBlueprintBinding`](ue_ue.DynamicBlueprintBinding.md)

  ↳ **`ComponentDelegateBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.ComponentDelegateBinding.md#constructor)

### Properties

- [ComponentDelegateBindings](ue_ue.ComponentDelegateBinding.md#componentdelegatebindings)
- [\_\_tid\_ComponentDelegateBinding\_\_](ue_ue.ComponentDelegateBinding.md#__tid_componentdelegatebinding__)
- [\_\_tid\_DynamicBlueprintBinding\_\_](ue_ue.ComponentDelegateBinding.md#__tid_dynamicblueprintbinding__)
- [\_\_tid\_Object\_\_](ue_ue.ComponentDelegateBinding.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ComponentDelegateBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ComponentDelegateBinding.md#executeubergraph)
- [GetClass](ue_ue.ComponentDelegateBinding.md#getclass)
- [GetName](ue_ue.ComponentDelegateBinding.md#getname)
- [GetOuter](ue_ue.ComponentDelegateBinding.md#getouter)
- [GetWorld](ue_ue.ComponentDelegateBinding.md#getworld)
- [Find](ue_ue.ComponentDelegateBinding.md#find)
- [Load](ue_ue.ComponentDelegateBinding.md#load)
- [StaticClass](ue_ue.ComponentDelegateBinding.md#staticclass)

## Constructors

### constructor

• **new ComponentDelegateBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[constructor](ue_ue.DynamicBlueprintBinding.md#constructor)

#### Defined in

[ue/ue.d.ts:28385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28385)

## Properties

### ComponentDelegateBindings

• **ComponentDelegateBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintComponentDelegateBinding`](ue_ue.BlueprintComponentDelegateBinding.md)\>

#### Defined in

[ue/ue.d.ts:28386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28386)

___

### \_\_tid\_ComponentDelegateBinding\_\_

• **\_\_tid\_ComponentDelegateBinding\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28391)

___

### \_\_tid\_DynamicBlueprintBinding\_\_

• **\_\_tid\_DynamicBlueprintBinding\_\_**: `boolean`

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[__tid_DynamicBlueprintBinding__](ue_ue.DynamicBlueprintBinding.md#__tid_dynamicblueprintbinding__)

#### Defined in

[ue/ue.d.ts:4757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4757)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[__tid_Object__](ue_ue.DynamicBlueprintBinding.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[ExecuteUbergraph](ue_ue.DynamicBlueprintBinding.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetClass](ue_ue.DynamicBlueprintBinding.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetName](ue_ue.DynamicBlueprintBinding.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetOuter](ue_ue.DynamicBlueprintBinding.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[GetWorld](ue_ue.DynamicBlueprintBinding.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ComponentDelegateBinding`](ue_ue.ComponentDelegateBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ComponentDelegateBinding`](ue_ue.ComponentDelegateBinding.md)

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[Find](ue_ue.DynamicBlueprintBinding.md#find)

#### Defined in

[ue/ue.d.ts:28388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28388)

___

### Load

▸ `Static` **Load**(`InName`): [`ComponentDelegateBinding`](ue_ue.ComponentDelegateBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ComponentDelegateBinding`](ue_ue.ComponentDelegateBinding.md)

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[Load](ue_ue.DynamicBlueprintBinding.md#load)

#### Defined in

[ue/ue.d.ts:28389](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28389)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DynamicBlueprintBinding](ue_ue.DynamicBlueprintBinding.md).[StaticClass](ue_ue.DynamicBlueprintBinding.md#staticclass)

#### Defined in

[ue/ue.d.ts:28387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28387)