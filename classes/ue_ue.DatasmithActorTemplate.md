[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithActorTemplate

# Class: DatasmithActorTemplate

[ue/ue](../modules/ue_ue.md).DatasmithActorTemplate

## Hierarchy

- [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

  ↳ **`DatasmithActorTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithActorTemplate.md#constructor)

### Properties

- [Layers](ue_ue.DatasmithActorTemplate.md#layers)
- [Tags](ue_ue.DatasmithActorTemplate.md#tags)
- [\_\_tid\_DatasmithActorTemplate\_\_](ue_ue.DatasmithActorTemplate.md#__tid_datasmithactortemplate__)
- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithActorTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithActorTemplate.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithActorTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithActorTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithActorTemplate.md#getclass)
- [GetName](ue_ue.DatasmithActorTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithActorTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithActorTemplate.md#getworld)
- [Find](ue_ue.DatasmithActorTemplate.md#find)
- [Load](ue_ue.DatasmithActorTemplate.md#load)
- [StaticClass](ue_ue.DatasmithActorTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithActorTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

## Properties

### Layers

• **Layers**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### Tags

• **Tags**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### \_\_tid\_DatasmithActorTemplate\_\_

• **\_\_tid\_DatasmithActorTemplate\_\_**: `boolean`

___

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_DatasmithObjectTemplate__](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_Object__](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[CreateDefaultSubobject](ue_ue.DatasmithObjectTemplate.md#createdefaultsubobject)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetName](ue_ue.DatasmithObjectTemplate.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithActorTemplate`](ue_ue.DatasmithActorTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithActorTemplate`](ue_ue.DatasmithActorTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Find](ue_ue.DatasmithObjectTemplate.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithActorTemplate`](ue_ue.DatasmithActorTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithActorTemplate`](ue_ue.DatasmithActorTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Load](ue_ue.DatasmithObjectTemplate.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)
