[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NodeMappingProviderInterface

# Class: NodeMappingProviderInterface

[ue/ue](../modules/ue_ue.md).NodeMappingProviderInterface

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`NodeMappingProviderInterface`**

## Table of contents

### Constructors

- [constructor](ue_ue.NodeMappingProviderInterface.md#constructor)

### Properties

- [\_\_tid\_Interface\_\_](ue_ue.NodeMappingProviderInterface.md#__tid_interface__)
- [\_\_tid\_NodeMappingProviderInterface\_\_](ue_ue.NodeMappingProviderInterface.md#__tid_nodemappingproviderinterface__)
- [\_\_tid\_Object\_\_](ue_ue.NodeMappingProviderInterface.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NodeMappingProviderInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NodeMappingProviderInterface.md#executeubergraph)
- [GetClass](ue_ue.NodeMappingProviderInterface.md#getclass)
- [GetName](ue_ue.NodeMappingProviderInterface.md#getname)
- [GetOuter](ue_ue.NodeMappingProviderInterface.md#getouter)
- [GetWorld](ue_ue.NodeMappingProviderInterface.md#getworld)
- [Find](ue_ue.NodeMappingProviderInterface.md#find)
- [Load](ue_ue.NodeMappingProviderInterface.md#load)
- [StaticClass](ue_ue.NodeMappingProviderInterface.md#staticclass)

## Constructors

### constructor

• **new NodeMappingProviderInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

___

### \_\_tid\_NodeMappingProviderInterface\_\_

• **\_\_tid\_NodeMappingProviderInterface\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NodeMappingProviderInterface`](ue_ue.NodeMappingProviderInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NodeMappingProviderInterface`](ue_ue.NodeMappingProviderInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NodeMappingProviderInterface`](ue_ue.NodeMappingProviderInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NodeMappingProviderInterface`](ue_ue.NodeMappingProviderInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
