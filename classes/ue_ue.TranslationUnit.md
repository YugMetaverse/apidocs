[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TranslationUnit

# Class: TranslationUnit

[ue/ue](../modules/ue_ue.md).TranslationUnit

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TranslationUnit`**

## Table of contents

### Constructors

- [constructor](ue_ue.TranslationUnit.md#constructor)

### Properties

- [Contexts](ue_ue.TranslationUnit.md#contexts)
- [HasBeenReviewed](ue_ue.TranslationUnit.md#hasbeenreviewed)
- [Key](ue_ue.TranslationUnit.md#key)
- [LocresPath](ue_ue.TranslationUnit.md#locrespath)
- [Namespace](ue_ue.TranslationUnit.md#namespace)
- [Source](ue_ue.TranslationUnit.md#source)
- [Translation](ue_ue.TranslationUnit.md#translation)
- [TranslationBeforeImport](ue_ue.TranslationUnit.md#translationbeforeimport)
- [\_\_tid\_Object\_\_](ue_ue.TranslationUnit.md#__tid_object__)
- [\_\_tid\_TranslationUnit\_\_](ue_ue.TranslationUnit.md#__tid_translationunit__)

### Methods

- [CreateDefaultSubobject](ue_ue.TranslationUnit.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TranslationUnit.md#executeubergraph)
- [GetClass](ue_ue.TranslationUnit.md#getclass)
- [GetName](ue_ue.TranslationUnit.md#getname)
- [GetOuter](ue_ue.TranslationUnit.md#getouter)
- [GetWorld](ue_ue.TranslationUnit.md#getworld)
- [Find](ue_ue.TranslationUnit.md#find)
- [Load](ue_ue.TranslationUnit.md#load)
- [StaticClass](ue_ue.TranslationUnit.md#staticclass)

## Constructors

### constructor

• **new TranslationUnit**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:64180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64180)

## Properties

### Contexts

• **Contexts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TranslationContextInfo`](ue_ue.TranslationContextInfo.md)\>

#### Defined in

[ue/ue.d.ts:64185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64185)

___

### HasBeenReviewed

• **HasBeenReviewed**: `boolean`

#### Defined in

[ue/ue.d.ts:64186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64186)

___

### Key

• **Key**: `string`

#### Defined in

[ue/ue.d.ts:64182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64182)

___

### LocresPath

• **LocresPath**: `string`

#### Defined in

[ue/ue.d.ts:64188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64188)

___

### Namespace

• **Namespace**: `string`

#### Defined in

[ue/ue.d.ts:64181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64181)

___

### Source

• **Source**: `string`

#### Defined in

[ue/ue.d.ts:64183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64183)

___

### Translation

• **Translation**: `string`

#### Defined in

[ue/ue.d.ts:64184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64184)

___

### TranslationBeforeImport

• **TranslationBeforeImport**: `string`

#### Defined in

[ue/ue.d.ts:64187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64187)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TranslationUnit\_\_

• **\_\_tid\_TranslationUnit\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64193)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TranslationUnit`](ue_ue.TranslationUnit.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TranslationUnit`](ue_ue.TranslationUnit.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:64190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64190)

___

### Load

▸ `Static` **Load**(`InName`): [`TranslationUnit`](ue_ue.TranslationUnit.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TranslationUnit`](ue_ue.TranslationUnit.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:64191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64191)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:64189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64189)
