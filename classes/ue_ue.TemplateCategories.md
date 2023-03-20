[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TemplateCategories

# Class: TemplateCategories

[ue/ue](../modules/ue_ue.md).TemplateCategories

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TemplateCategories`**

## Table of contents

### Constructors

- [constructor](ue_ue.TemplateCategories.md#constructor)

### Properties

- [Categories](ue_ue.TemplateCategories.md#categories)
- [\_\_tid\_Object\_\_](ue_ue.TemplateCategories.md#__tid_object__)
- [\_\_tid\_TemplateCategories\_\_](ue_ue.TemplateCategories.md#__tid_templatecategories__)

### Methods

- [CreateDefaultSubobject](ue_ue.TemplateCategories.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TemplateCategories.md#executeubergraph)
- [GetClass](ue_ue.TemplateCategories.md#getclass)
- [GetName](ue_ue.TemplateCategories.md#getname)
- [GetOuter](ue_ue.TemplateCategories.md#getouter)
- [GetWorld](ue_ue.TemplateCategories.md#getworld)
- [Find](ue_ue.TemplateCategories.md#find)
- [Load](ue_ue.TemplateCategories.md#load)
- [StaticClass](ue_ue.TemplateCategories.md#staticclass)

## Constructors

### constructor

• **new TemplateCategories**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Categories

• **Categories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateCategoryDef`](ue_ue.TemplateCategoryDef.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TemplateCategories\_\_

• **\_\_tid\_TemplateCategories\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TemplateCategories`](ue_ue.TemplateCategories.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TemplateCategories`](ue_ue.TemplateCategories.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TemplateCategories`](ue_ue.TemplateCategories.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TemplateCategories`](ue_ue.TemplateCategories.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
