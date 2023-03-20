[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NamedInterfaces

# Class: NamedInterfaces

[ue/ue](../modules/ue_ue.md).NamedInterfaces

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NamedInterfaces`**

## Table of contents

### Constructors

- [constructor](ue_ue.NamedInterfaces.md#constructor)

### Properties

- [NamedInterfaceDefs](ue_ue.NamedInterfaces.md#namedinterfacedefs)
- [NamedInterfaces](ue_ue.NamedInterfaces.md#namedinterfaces)
- [\_\_tid\_NamedInterfaces\_\_](ue_ue.NamedInterfaces.md#__tid_namedinterfaces__)
- [\_\_tid\_Object\_\_](ue_ue.NamedInterfaces.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NamedInterfaces.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NamedInterfaces.md#executeubergraph)
- [GetClass](ue_ue.NamedInterfaces.md#getclass)
- [GetName](ue_ue.NamedInterfaces.md#getname)
- [GetOuter](ue_ue.NamedInterfaces.md#getouter)
- [GetWorld](ue_ue.NamedInterfaces.md#getworld)
- [Find](ue_ue.NamedInterfaces.md#find)
- [Load](ue_ue.NamedInterfaces.md#load)
- [StaticClass](ue_ue.NamedInterfaces.md#staticclass)

## Constructors

### constructor

• **new NamedInterfaces**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### NamedInterfaceDefs

• **NamedInterfaceDefs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedInterfaceDef`](ue_ue.NamedInterfaceDef.md)\>

___

### NamedInterfaces

• **NamedInterfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedInterface`](ue_ue.NamedInterface.md)\>

___

### \_\_tid\_NamedInterfaces\_\_

• **\_\_tid\_NamedInterfaces\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NamedInterfaces`](ue_ue.NamedInterfaces.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NamedInterfaces`](ue_ue.NamedInterfaces.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NamedInterfaces`](ue_ue.NamedInterfaces.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NamedInterfaces`](ue_ue.NamedInterfaces.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
