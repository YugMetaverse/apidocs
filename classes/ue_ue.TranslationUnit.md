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

## Properties

### Contexts

• **Contexts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TranslationContextInfo`](ue_ue.TranslationContextInfo.md)\>

___

### HasBeenReviewed

• **HasBeenReviewed**: `boolean`

___

### Key

• **Key**: `string`

___

### LocresPath

• **LocresPath**: `string`

___

### Namespace

• **Namespace**: `string`

___

### Source

• **Source**: `string`

___

### Translation

• **Translation**: `string`

___

### TranslationBeforeImport

• **TranslationBeforeImport**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TranslationUnit\_\_

• **\_\_tid\_TranslationUnit\_\_**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
