[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VisibilityBinding

# Class: VisibilityBinding

[ue/ue](../modules/ue_ue.md).VisibilityBinding

## Hierarchy

- [`PropertyBinding`](ue_ue.PropertyBinding.md)

  ↳ **`VisibilityBinding`**

## Table of contents

### Constructors

- [constructor](ue_ue.VisibilityBinding.md#constructor)

### Properties

- [DestinationProperty](ue_ue.VisibilityBinding.md#destinationproperty)
- [SourceObject](ue_ue.VisibilityBinding.md#sourceobject)
- [SourcePath](ue_ue.VisibilityBinding.md#sourcepath)
- [\_\_tid\_Object\_\_](ue_ue.VisibilityBinding.md#__tid_object__)
- [\_\_tid\_PropertyBinding\_\_](ue_ue.VisibilityBinding.md#__tid_propertybinding__)
- [\_\_tid\_VisibilityBinding\_\_](ue_ue.VisibilityBinding.md#__tid_visibilitybinding__)

### Methods

- [CreateDefaultSubobject](ue_ue.VisibilityBinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VisibilityBinding.md#executeubergraph)
- [GetClass](ue_ue.VisibilityBinding.md#getclass)
- [GetName](ue_ue.VisibilityBinding.md#getname)
- [GetOuter](ue_ue.VisibilityBinding.md#getouter)
- [GetValue](ue_ue.VisibilityBinding.md#getvalue)
- [GetWorld](ue_ue.VisibilityBinding.md#getworld)
- [Find](ue_ue.VisibilityBinding.md#find)
- [Load](ue_ue.VisibilityBinding.md#load)
- [StaticClass](ue_ue.VisibilityBinding.md#staticclass)

## Constructors

### constructor

• **new VisibilityBinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[constructor](ue_ue.PropertyBinding.md#constructor)

#### Defined in

[ue/ue.d.ts:65273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65273)

## Properties

### DestinationProperty

• **DestinationProperty**: `string`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[DestinationProperty](ue_ue.PropertyBinding.md#destinationproperty)

#### Defined in

[ue/ue.d.ts:10817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10817)

___

### SourceObject

• **SourceObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[SourceObject](ue_ue.PropertyBinding.md#sourceobject)

#### Defined in

[ue/ue.d.ts:10815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10815)

___

### SourcePath

• **SourcePath**: [`DynamicPropertyPath`](ue_ue.DynamicPropertyPath.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[SourcePath](ue_ue.PropertyBinding.md#sourcepath)

#### Defined in

[ue/ue.d.ts:10816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10816)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[__tid_Object__](ue_ue.PropertyBinding.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyBinding\_\_

• **\_\_tid\_PropertyBinding\_\_**: `boolean`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[__tid_PropertyBinding__](ue_ue.PropertyBinding.md#__tid_propertybinding__)

#### Defined in

[ue/ue.d.ts:10822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10822)

___

### \_\_tid\_VisibilityBinding\_\_

• **\_\_tid\_VisibilityBinding\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65279)

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

[PropertyBinding](ue_ue.PropertyBinding.md).[ExecuteUbergraph](ue_ue.PropertyBinding.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetClass](ue_ue.PropertyBinding.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetName](ue_ue.PropertyBinding.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetOuter](ue_ue.PropertyBinding.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetValue

▸ **GetValue**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Defined in

[ue/ue.d.ts:65274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65274)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PropertyBinding](ue_ue.PropertyBinding.md).[GetWorld](ue_ue.PropertyBinding.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VisibilityBinding`](ue_ue.VisibilityBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VisibilityBinding`](ue_ue.VisibilityBinding.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[Find](ue_ue.PropertyBinding.md#find)

#### Defined in

[ue/ue.d.ts:65276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65276)

___

### Load

▸ `Static` **Load**(`InName`): [`VisibilityBinding`](ue_ue.VisibilityBinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VisibilityBinding`](ue_ue.VisibilityBinding.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[Load](ue_ue.PropertyBinding.md#load)

#### Defined in

[ue/ue.d.ts:65277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65277)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PropertyBinding](ue_ue.PropertyBinding.md).[StaticClass](ue_ue.PropertyBinding.md#staticclass)

#### Defined in

[ue/ue.d.ts:65275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65275)
