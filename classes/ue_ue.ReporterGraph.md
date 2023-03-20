[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReporterGraph

# Class: ReporterGraph

[ue/ue](../modules/ue_ue.md).ReporterGraph

## Hierarchy

- [`ReporterBase`](ue_ue.ReporterBase.md)

  ↳ **`ReporterGraph`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReporterGraph.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.ReporterGraph.md#__tid_object__)
- [\_\_tid\_ReporterBase\_\_](ue_ue.ReporterGraph.md#__tid_reporterbase__)
- [\_\_tid\_ReporterGraph\_\_](ue_ue.ReporterGraph.md#__tid_reportergraph__)

### Methods

- [CreateDefaultSubobject](ue_ue.ReporterGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReporterGraph.md#executeubergraph)
- [GetClass](ue_ue.ReporterGraph.md#getclass)
- [GetName](ue_ue.ReporterGraph.md#getname)
- [GetOuter](ue_ue.ReporterGraph.md#getouter)
- [GetWorld](ue_ue.ReporterGraph.md#getworld)
- [Find](ue_ue.ReporterGraph.md#find)
- [Load](ue_ue.ReporterGraph.md#load)
- [StaticClass](ue_ue.ReporterGraph.md#staticclass)

## Constructors

### constructor

• **new ReporterGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ReporterBase](ue_ue.ReporterBase.md).[constructor](ue_ue.ReporterBase.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ReporterBase](ue_ue.ReporterBase.md).[__tid_Object__](ue_ue.ReporterBase.md#__tid_object__)

___

### \_\_tid\_ReporterBase\_\_

• **\_\_tid\_ReporterBase\_\_**: `boolean`

#### Inherited from

[ReporterBase](ue_ue.ReporterBase.md).[__tid_ReporterBase__](ue_ue.ReporterBase.md#__tid_reporterbase__)

___

### \_\_tid\_ReporterGraph\_\_

• **\_\_tid\_ReporterGraph\_\_**: `boolean`

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

[ReporterBase](ue_ue.ReporterBase.md).[CreateDefaultSubobject](ue_ue.ReporterBase.md#createdefaultsubobject)

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

[ReporterBase](ue_ue.ReporterBase.md).[ExecuteUbergraph](ue_ue.ReporterBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ReporterBase](ue_ue.ReporterBase.md).[GetClass](ue_ue.ReporterBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ReporterBase](ue_ue.ReporterBase.md).[GetName](ue_ue.ReporterBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ReporterBase](ue_ue.ReporterBase.md).[GetOuter](ue_ue.ReporterBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ReporterBase](ue_ue.ReporterBase.md).[GetWorld](ue_ue.ReporterBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReporterGraph`](ue_ue.ReporterGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReporterGraph`](ue_ue.ReporterGraph.md)

#### Overrides

[ReporterBase](ue_ue.ReporterBase.md).[Find](ue_ue.ReporterBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReporterGraph`](ue_ue.ReporterGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReporterGraph`](ue_ue.ReporterGraph.md)

#### Overrides

[ReporterBase](ue_ue.ReporterBase.md).[Load](ue_ue.ReporterBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ReporterBase](ue_ue.ReporterBase.md).[StaticClass](ue_ue.ReporterBase.md#staticclass)
