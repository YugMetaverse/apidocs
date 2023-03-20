[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Rig

# Class: Rig

[ue/ue](../modules/ue_ue.md).Rig

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Rig`**

## Table of contents

### Constructors

- [constructor](ue_ue.Rig.md#constructor)

### Properties

- [Nodes](ue_ue.Rig.md#nodes)
- [TransformBases](ue_ue.Rig.md#transformbases)
- [\_\_tid\_Object\_\_](ue_ue.Rig.md#__tid_object__)
- [\_\_tid\_Rig\_\_](ue_ue.Rig.md#__tid_rig__)

### Methods

- [CreateDefaultSubobject](ue_ue.Rig.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Rig.md#executeubergraph)
- [GetClass](ue_ue.Rig.md#getclass)
- [GetName](ue_ue.Rig.md#getname)
- [GetOuter](ue_ue.Rig.md#getouter)
- [GetWorld](ue_ue.Rig.md#getworld)
- [Find](ue_ue.Rig.md#find)
- [Load](ue_ue.Rig.md#load)
- [StaticClass](ue_ue.Rig.md#staticclass)

## Constructors

### constructor

• **new Rig**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Nodes

• **Nodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Node`](ue_ue.Node.md)\>

___

### TransformBases

• **TransformBases**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TransformBase`](ue_ue.TransformBase.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_Rig\_\_

• **\_\_tid\_Rig\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Rig`](ue_ue.Rig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Rig`](ue_ue.Rig.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Rig`](ue_ue.Rig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Rig`](ue_ue.Rig.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
