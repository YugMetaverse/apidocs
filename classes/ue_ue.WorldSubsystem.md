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

#### Defined in

[ue/ue.d.ts:62682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62682)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[__tid_Object__](ue_ue.Subsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[__tid_Subsystem__](ue_ue.Subsystem.md#__tid_subsystem__)

#### Defined in

[ue/ue.d.ts:21564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21564)

___

### \_\_tid\_WorldSubsystem\_\_

• **\_\_tid\_WorldSubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:62687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62687)

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

[Subsystem](ue_ue.Subsystem.md).[ExecuteUbergraph](ue_ue.Subsystem.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetClass](ue_ue.Subsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetName](ue_ue.Subsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetOuter](ue_ue.Subsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Subsystem](ue_ue.Subsystem.md).[GetWorld](ue_ue.Subsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:62684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62684)

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

#### Defined in

[ue/ue.d.ts:62685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62685)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Subsystem](ue_ue.Subsystem.md).[StaticClass](ue_ue.Subsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:62683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62683)
