[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EngineSubsystem

# Class: EngineSubsystem

[ue/ue](../modules/ue_ue.md).EngineSubsystem

## Hierarchy

- [`DynamicSubsystem`](ue_ue.DynamicSubsystem.md)

  ↳ **`EngineSubsystem`**

  ↳↳ [`AssetTagsSubsystem`](ue_ue.AssetTagsSubsystem.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EngineSubsystem.md#constructor)

### Properties

- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.EngineSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EngineSubsystem\_\_](ue_ue.EngineSubsystem.md#__tid_enginesubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.EngineSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.EngineSubsystem.md#__tid_subsystem__)

### Methods

- [CreateDefaultSubobject](ue_ue.EngineSubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EngineSubsystem.md#executeubergraph)
- [GetClass](ue_ue.EngineSubsystem.md#getclass)
- [GetName](ue_ue.EngineSubsystem.md#getname)
- [GetOuter](ue_ue.EngineSubsystem.md#getouter)
- [GetWorld](ue_ue.EngineSubsystem.md#getworld)
- [Find](ue_ue.EngineSubsystem.md#find)
- [Load](ue_ue.EngineSubsystem.md#load)
- [StaticClass](ue_ue.EngineSubsystem.md#staticclass)

## Constructors

### constructor

• **new EngineSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[constructor](ue_ue.DynamicSubsystem.md#constructor)

## Properties

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.DynamicSubsystem.md#__tid_dynamicsubsystem__)

___

### \_\_tid\_EngineSubsystem\_\_

• **\_\_tid\_EngineSubsystem\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[__tid_Object__](ue_ue.DynamicSubsystem.md#__tid_object__)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[__tid_Subsystem__](ue_ue.DynamicSubsystem.md#__tid_subsystem__)

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

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[CreateDefaultSubobject](ue_ue.DynamicSubsystem.md#createdefaultsubobject)

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

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[ExecuteUbergraph](ue_ue.DynamicSubsystem.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetClass](ue_ue.DynamicSubsystem.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetName](ue_ue.DynamicSubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetOuter](ue_ue.DynamicSubsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetWorld](ue_ue.DynamicSubsystem.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[Find](ue_ue.DynamicSubsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[Load](ue_ue.DynamicSubsystem.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[StaticClass](ue_ue.DynamicSubsystem.md#staticclass)
