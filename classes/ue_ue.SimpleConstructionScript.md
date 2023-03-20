[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SimpleConstructionScript

# Class: SimpleConstructionScript

[ue/ue](../modules/ue_ue.md).SimpleConstructionScript

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SimpleConstructionScript`**

## Table of contents

### Constructors

- [constructor](ue_ue.SimpleConstructionScript.md#constructor)

### Properties

- [ActorComponentNodes](ue_ue.SimpleConstructionScript.md#actorcomponentnodes)
- [AllNodes](ue_ue.SimpleConstructionScript.md#allnodes)
- [DefaultSceneRootNode](ue_ue.SimpleConstructionScript.md#defaultscenerootnode)
- [RootNode](ue_ue.SimpleConstructionScript.md#rootnode)
- [RootNodes](ue_ue.SimpleConstructionScript.md#rootnodes)
- [\_\_tid\_Object\_\_](ue_ue.SimpleConstructionScript.md#__tid_object__)
- [\_\_tid\_SimpleConstructionScript\_\_](ue_ue.SimpleConstructionScript.md#__tid_simpleconstructionscript__)

### Methods

- [CreateDefaultSubobject](ue_ue.SimpleConstructionScript.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SimpleConstructionScript.md#executeubergraph)
- [GetClass](ue_ue.SimpleConstructionScript.md#getclass)
- [GetName](ue_ue.SimpleConstructionScript.md#getname)
- [GetOuter](ue_ue.SimpleConstructionScript.md#getouter)
- [GetWorld](ue_ue.SimpleConstructionScript.md#getworld)
- [Find](ue_ue.SimpleConstructionScript.md#find)
- [Load](ue_ue.SimpleConstructionScript.md#load)
- [StaticClass](ue_ue.SimpleConstructionScript.md#staticclass)

## Constructors

### constructor

• **new SimpleConstructionScript**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActorComponentNodes

• **ActorComponentNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SCS_Node`](ue_ue.SCS_Node.md)\>

___

### AllNodes

• **AllNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SCS_Node`](ue_ue.SCS_Node.md)\>

___

### DefaultSceneRootNode

• **DefaultSceneRootNode**: [`SCS_Node`](ue_ue.SCS_Node.md)

___

### RootNode

• **RootNode**: [`SCS_Node`](ue_ue.SCS_Node.md)

___

### RootNodes

• **RootNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SCS_Node`](ue_ue.SCS_Node.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SimpleConstructionScript\_\_

• **\_\_tid\_SimpleConstructionScript\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SimpleConstructionScript`](ue_ue.SimpleConstructionScript.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
