[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RawDistributionVector

# Class: RawDistributionVector

[ue/ue](../modules/ue_ue.md).RawDistributionVector

## Hierarchy

- [`RawDistribution`](ue_ue.RawDistribution.md)

  ↳ **`RawDistributionVector`**

## Table of contents

### Constructors

- [constructor](ue_ue.RawDistributionVector.md#constructor)

### Properties

- [Distribution](ue_ue.RawDistributionVector.md#distribution)
- [MaxValue](ue_ue.RawDistributionVector.md#maxvalue)
- [MaxValueVec](ue_ue.RawDistributionVector.md#maxvaluevec)
- [MinValue](ue_ue.RawDistributionVector.md#minvalue)
- [MinValueVec](ue_ue.RawDistributionVector.md#minvaluevec)
- [Table](ue_ue.RawDistributionVector.md#table)
- [\_\_tid\_RawDistributionVector\_\_](ue_ue.RawDistributionVector.md#__tid_rawdistributionvector__)

### Methods

- [StaticClass](ue_ue.RawDistributionVector.md#staticclass)
- [StaticStruct](ue_ue.RawDistributionVector.md#staticstruct)

## Constructors

### constructor

• **new RawDistributionVector**()

#### Overrides

[RawDistribution](ue_ue.RawDistribution.md).[constructor](ue_ue.RawDistribution.md#constructor)

• **new RawDistributionVector**(`MinValue`, `MaxValue`, `MinValueVec`, `MaxValueVec`, `Distribution`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MinValue` | `number` |
| `MaxValue` | `number` |
| `MinValueVec` | [`Vector`](ue_ue_s.Vector.md) |
| `MaxValueVec` | [`Vector`](ue_ue_s.Vector.md) |
| `Distribution` | [`DistributionVector`](ue_ue.DistributionVector.md) |

#### Overrides

[RawDistribution](ue_ue.RawDistribution.md).[constructor](ue_ue.RawDistribution.md#constructor)

## Properties

### Distribution

• **Distribution**: [`DistributionVector`](ue_ue.DistributionVector.md)

___

### MaxValue

• **MaxValue**: `number`

___

### MaxValueVec

• **MaxValueVec**: [`Vector`](ue_ue_s.Vector.md)

___

### MinValue

• **MinValue**: `number`

___

### MinValueVec

• **MinValueVec**: [`Vector`](ue_ue_s.Vector.md)

___

### Table

• **Table**: [`DistributionLookupTable`](ue_ue.DistributionLookupTable.md)

#### Inherited from

[RawDistribution](ue_ue.RawDistribution.md).[Table](ue_ue.RawDistribution.md#table)

___

### \_\_tid\_RawDistributionVector\_\_

• `Private` **\_\_tid\_RawDistributionVector\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[RawDistribution](ue_ue.RawDistribution.md).[StaticClass](ue_ue.RawDistribution.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[RawDistribution](ue_ue.RawDistribution.md).[StaticStruct](ue_ue.RawDistribution.md#staticstruct)
