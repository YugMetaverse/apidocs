[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextBinding

# Class: TextBinding

[ue/ue](../modules/ue_ue.md).TextBinding

## Hierarchy

- [`PropertyBinding`](ue_ue.PropertyBinding.md)

  ↳ **`TextBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.TextBinding.md#constructor)

### Properties

- [DestinationProperty](ue_ue.TextBinding.md#destinationproperty)
- [SourceObject](ue_ue.TextBinding.md#sourceobject)
- [SourcePath](ue_ue.TextBinding.md#sourcepath)
- [\_\_tid\_Object\_\_](ue_ue.TextBinding.md#__tid_object__)
- [\_\_tid\_PropertyBinding\_\_](ue_ue.TextBinding.md#__tid_propertybinding__)
- [\_\_tid\_TextBinding\_\_](ue_ue.TextBinding.md#__tid_textbinding__)

### Methods

- [CreateDefaultSubobject](ue_ue.TextBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TextBinding.md#executeubergraph)
- [GetClass](ue_ue.TextBinding.md#getclass)
- [GetName](ue_ue.TextBinding.md#getname)
- [GetOuter](ue_ue.TextBinding.md#getouter)
- [GetStringValue](ue_ue.TextBinding.md#getstringvalue)
- [GetTextValue](ue_ue.TextBinding.md#gettextvalue)
- [GetWorld](ue_ue.TextBinding.md#getworld)
- [Find](ue_ue.TextBinding.md#find)
- [Load](ue_ue.TextBinding.md#load)
- [StaticClass](ue_ue.TextBinding.md#staticclass)

## Constructors

### constructor

• **new TextBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[constructor](ue_ue.PropertyBinding.md#constructor)

#### Defined in

[ue/ue.d.ts:63071](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63071)

## Properties

### DestinationProperty

• **DestinationProperty**: `string`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[DestinationProperty](ue_ue.PropertyBinding.md#destinationproperty)

#### Defined in

[ue/ue.d.ts:10817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10817)

___

### SourceObject

• **SourceObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[SourceObject](ue_ue.PropertyBinding.md#sourceobject)

#### Defined in

[ue/ue.d.ts:10815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10815)

___

### SourcePath

• **SourcePath**: [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[SourcePath](ue_ue.PropertyBinding.md#sourcepath)

#### Defined in

[ue/ue.d.ts:10816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10816)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[__tid_Object__](ue_ue.PropertyBinding.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyBinding\_\_

• **\_\_tid\_PropertyBinding\_\_**: `boolean`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[__tid_PropertyBinding__](ue_ue.PropertyBinding.md#__tid_propertybinding__)

#### Defined in

[ue/ue.d.ts:10822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10822)

___

### \_\_tid\_TextBinding\_\_

• **\_\_tid\_TextBinding\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63078](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63078)

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

[PropertyBinding](ue_ue.PropertyBinding.md).[ExecuteUbergraph](ue_ue.PropertyBinding.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetClass](ue_ue.PropertyBinding.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetName](ue_ue.PropertyBinding.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetOuter](ue_ue.PropertyBinding.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetStringValue

▸ **GetStringValue**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:63072](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63072)

___

### GetTextValue

▸ **GetTextValue**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:63073](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63073)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetWorld](ue_ue.PropertyBinding.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextBinding`](ue_ue.TextBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextBinding`](ue_ue.TextBinding.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[Find](ue_ue.PropertyBinding.md#find)

#### Defined in

[ue/ue.d.ts:63075](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63075)

___

### Load

▸ `Static` **Load**(`InName`): [`TextBinding`](ue_ue.TextBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextBinding`](ue_ue.TextBinding.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[Load](ue_ue.PropertyBinding.md#load)

#### Defined in

[ue/ue.d.ts:63076](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63076)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[StaticClass](ue_ue.PropertyBinding.md#staticclass)

#### Defined in

[ue/ue.d.ts:63074](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63074)
