[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LocalizationTarget

# Class: LocalizationTarget

[ue/ue](../modules/ue_ue.md).LocalizationTarget

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LocalizationTarget`**

## Table of contents

### Constructors

- [constructor](ue_ue.LocalizationTarget.md#constructor)

### Properties

- [Settings](ue_ue.LocalizationTarget.md#settings)
- [\_\_tid\_LocalizationTarget\_\_](ue_ue.LocalizationTarget.md#__tid_localizationtarget__)
- [\_\_tid\_Object\_\_](ue_ue.LocalizationTarget.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LocalizationTarget.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LocalizationTarget.md#executeubergraph)
- [GetClass](ue_ue.LocalizationTarget.md#getclass)
- [GetName](ue_ue.LocalizationTarget.md#getname)
- [GetOuter](ue_ue.LocalizationTarget.md#getouter)
- [GetWorld](ue_ue.LocalizationTarget.md#getworld)
- [Find](ue_ue.LocalizationTarget.md#find)
- [Load](ue_ue.LocalizationTarget.md#load)
- [StaticClass](ue_ue.LocalizationTarget.md#staticclass)

## Constructors

### constructor

• **new LocalizationTarget**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:46198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46198)

## Properties

### Settings

• **Settings**: [`LocalizationTargetSettings`](ue_ue.LocalizationTargetSettings.md)

#### Defined in

[ue/ue.d.ts:46199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46199)

___

### \_\_tid\_LocalizationTarget\_\_

• **\_\_tid\_LocalizationTarget\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46204)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LocalizationTarget`](ue_ue.LocalizationTarget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LocalizationTarget`](ue_ue.LocalizationTarget.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:46201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46201)

___

### Load

▸ `Static` **Load**(`InName`): [`LocalizationTarget`](ue_ue.LocalizationTarget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LocalizationTarget`](ue_ue.LocalizationTarget.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:46202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46202)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:46200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46200)
