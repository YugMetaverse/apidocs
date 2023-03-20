[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyBinding

# Class: PropertyBinding

[ue/ue](../modules/ue_ue.md).PropertyBinding

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PropertyBinding`**

  ↳↳ [`BoolBinding`](ue_ue.BoolBinding.md)

  ↳↳ [`BrushBinding`](ue_ue.BrushBinding.md)

  ↳↳ [`CheckedStateBinding`](ue_ue.CheckedStateBinding.md)

  ↳↳ [`ColorBinding`](ue_ue.ColorBinding.md)

  ↳↳ [`FloatBinding`](ue_ue.FloatBinding.md)

  ↳↳ [`Int32Binding`](ue_ue.Int32Binding.md)

  ↳↳ [`MouseCursorBinding`](ue_ue.MouseCursorBinding.md)

  ↳↳ [`TextBinding`](ue_ue.TextBinding.md)

  ↳↳ [`VisibilityBinding`](ue_ue.VisibilityBinding.md)

  ↳↳ [`WidgetBinding`](ue_ue.WidgetBinding.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyBinding.md#constructor)

### Properties

- [DestinationProperty](ue_ue.PropertyBinding.md#destinationproperty)
- [SourceObject](ue_ue.PropertyBinding.md#sourceobject)
- [SourcePath](ue_ue.PropertyBinding.md#sourcepath)
- [\_\_tid\_Object\_\_](ue_ue.PropertyBinding.md#__tid_object__)
- [\_\_tid\_PropertyBinding\_\_](ue_ue.PropertyBinding.md#__tid_propertybinding__)

### Methods

- [CreateDefaultSubobject](ue_ue.PropertyBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PropertyBinding.md#executeubergraph)
- [GetClass](ue_ue.PropertyBinding.md#getclass)
- [GetName](ue_ue.PropertyBinding.md#getname)
- [GetOuter](ue_ue.PropertyBinding.md#getouter)
- [GetWorld](ue_ue.PropertyBinding.md#getworld)
- [Find](ue_ue.PropertyBinding.md#find)
- [Load](ue_ue.PropertyBinding.md#load)
- [StaticClass](ue_ue.PropertyBinding.md#staticclass)

## Constructors

### constructor

• **new PropertyBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:10814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10814)

## Properties

### DestinationProperty

• **DestinationProperty**: `string`

#### Defined in

[ue/ue.d.ts:10817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10817)

___

### SourceObject

• **SourceObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:10815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10815)

___

### SourcePath

• **SourcePath**: [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md)

#### Defined in

[ue/ue.d.ts:10816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10816)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyBinding\_\_

• **\_\_tid\_PropertyBinding\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10822)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PropertyBinding`](ue_ue.PropertyBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PropertyBinding`](ue_ue.PropertyBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:10819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10819)

___

### Load

▸ `Static` **Load**(`InName`): [`PropertyBinding`](ue_ue.PropertyBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PropertyBinding`](ue_ue.PropertyBinding.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:10820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10820)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10818)
