[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HierarchicalLODSetup

# Class: HierarchicalLODSetup

[ue/ue](../modules/ue_ue.md).HierarchicalLODSetup

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`HierarchicalLODSetup`**

## Table of contents

### Constructors

- [constructor](ue_ue.HierarchicalLODSetup.md#constructor)

### Properties

- [HierarchicalLODSetup](ue_ue.HierarchicalLODSetup.md#hierarchicallodsetup)
- [OverrideBaseMaterial](ue_ue.HierarchicalLODSetup.md#overridebasematerial)
- [\_\_tid\_HierarchicalLODSetup\_\_](ue_ue.HierarchicalLODSetup.md#__tid_hierarchicallodsetup__)
- [\_\_tid\_Object\_\_](ue_ue.HierarchicalLODSetup.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.HierarchicalLODSetup.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.HierarchicalLODSetup.md#executeubergraph)
- [GetClass](ue_ue.HierarchicalLODSetup.md#getclass)
- [GetName](ue_ue.HierarchicalLODSetup.md#getname)
- [GetOuter](ue_ue.HierarchicalLODSetup.md#getouter)
- [GetWorld](ue_ue.HierarchicalLODSetup.md#getworld)
- [Find](ue_ue.HierarchicalLODSetup.md#find)
- [Load](ue_ue.HierarchicalLODSetup.md#load)
- [StaticClass](ue_ue.HierarchicalLODSetup.md#staticclass)

## Constructors

### constructor

• **new HierarchicalLODSetup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### HierarchicalLODSetup

• **HierarchicalLODSetup**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`HierarchicalSimplification`](ue_ue.HierarchicalSimplification.md)\>

___

### OverrideBaseMaterial

• **OverrideBaseMaterial**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### \_\_tid\_HierarchicalLODSetup\_\_

• **\_\_tid\_HierarchicalLODSetup\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`HierarchicalLODSetup`](ue_ue.HierarchicalLODSetup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`HierarchicalLODSetup`](ue_ue.HierarchicalLODSetup.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`HierarchicalLODSetup`](ue_ue.HierarchicalLODSetup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`HierarchicalLODSetup`](ue_ue.HierarchicalLODSetup.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
