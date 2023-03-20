[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WorldSubsystem

# Class: WorldSubsystem

[ue/ue](../modules/ue_ue.md).WorldSubsystem

## Hierarchy

- [`Subsystem`](ue_ue.Subsystem.md)

  ↳ **`WorldSubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.WorldSubsystem.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.WorldSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.WorldSubsystem.md#__tid_subsystem__)
- [\_\_tid\_WorldSubsystem\_\_](ue_ue.WorldSubsystem.md#__tid_worldsubsystem__)

### Methods

- [CreateDefaultSubobject](ue_ue.WorldSubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WorldSubsystem.md#executeubergraph)
- [GetClass](ue_ue.WorldSubsystem.md#getclass)
- [GetName](ue_ue.WorldSubsystem.md#getname)
- [GetOuter](ue_ue.WorldSubsystem.md#getouter)
- [GetWorld](ue_ue.WorldSubsystem.md#getworld)
- [Find](ue_ue.WorldSubsystem.md#find)
- [Load](ue_ue.WorldSubsystem.md#load)
- [StaticClass](ue_ue.WorldSubsystem.md#staticclass)

## Constructors

### constructor

• **new WorldSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Subsystem](ue_ue.Subsystem.md).[constructor](ue_ue.Subsystem.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[__tid_Object__](ue_ue.Subsystem.md#__tid_object__)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[__tid_Subsystem__](ue_ue.Subsystem.md#__tid_subsystem__)

___

### \_\_tid\_WorldSubsystem\_\_

• **\_\_tid\_WorldSubsystem\_\_**: `boolean`

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

[Subsystem](ue_ue.Subsystem.md).[CreateDefaultSubobject](ue_ue.Subsystem.md#createdefaultsubobject)

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

[Subsystem](ue_ue.Subsystem.md).[ExecuteUbergraph](ue_ue.Subsystem.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetClass](ue_ue.Subsystem.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetName](ue_ue.Subsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetOuter](ue_ue.Subsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetWorld](ue_ue.Subsystem.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WorldSubsystem`](ue_ue.WorldSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WorldSubsystem`](ue_ue.WorldSubsystem.md)

#### Overrides

[Subsystem](ue_ue.Subsystem.md).[Find](ue_ue.Subsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WorldSubsystem`](ue_ue.WorldSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WorldSubsystem`](ue_ue.WorldSubsystem.md)

#### Overrides

[Subsystem](ue_ue.Subsystem.md).[Load](ue_ue.Subsystem.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Subsystem](ue_ue.Subsystem.md).[StaticClass](ue_ue.Subsystem.md#staticclass)
