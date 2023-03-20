[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DistributionVector

# Class: DistributionVector

[ue/ue](../modules/ue_ue.md).DistributionVector

## Hierarchy

- [`Distribution`](ue_ue.Distribution.md)

  ↳ **`DistributionVector`**

  ↳↳ [`DistributionVectorConstant`](ue_ue.DistributionVectorConstant.md)

  ↳↳ [`DistributionVectorConstantCurve`](ue_ue.DistributionVectorConstantCurve.md)

  ↳↳ [`DistributionVectorUniform`](ue_ue.DistributionVectorUniform.md)

  ↳↳ [`DistributionVectorUniformCurve`](ue_ue.DistributionVectorUniformCurve.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DistributionVector.md#constructor)

### Properties

- [\_\_tid\_DistributionVector\_\_](ue_ue.DistributionVector.md#__tid_distributionvector__)
- [\_\_tid\_Distribution\_\_](ue_ue.DistributionVector.md#__tid_distribution__)
- [\_\_tid\_Object\_\_](ue_ue.DistributionVector.md#__tid_object__)
- [bBakedDataSuccesfully](ue_ue.DistributionVector.md#bbakeddatasuccesfully)
- [bCanBeBaked](ue_ue.DistributionVector.md#bcanbebaked)
- [bIsDirty](ue_ue.DistributionVector.md#bisdirty)

### Methods

- [CreateDefaultSubobject](ue_ue.DistributionVector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DistributionVector.md#executeubergraph)
- [GetClass](ue_ue.DistributionVector.md#getclass)
- [GetName](ue_ue.DistributionVector.md#getname)
- [GetOuter](ue_ue.DistributionVector.md#getouter)
- [GetWorld](ue_ue.DistributionVector.md#getworld)
- [Find](ue_ue.DistributionVector.md#find)
- [Load](ue_ue.DistributionVector.md#load)
- [StaticClass](ue_ue.DistributionVector.md#staticclass)

## Constructors

### constructor

• **new DistributionVector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Distribution](ue_ue.Distribution.md).[constructor](ue_ue.Distribution.md#constructor)

## Properties

### \_\_tid\_DistributionVector\_\_

• **\_\_tid\_DistributionVector\_\_**: `boolean`

___

### \_\_tid\_Distribution\_\_

• **\_\_tid\_Distribution\_\_**: `boolean`

#### Inherited from

[Distribution](ue_ue.Distribution.md).[__tid_Distribution__](ue_ue.Distribution.md#__tid_distribution__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Distribution](ue_ue.Distribution.md).[__tid_Object__](ue_ue.Distribution.md#__tid_object__)

___

### bBakedDataSuccesfully

• **bBakedDataSuccesfully**: `boolean`

___

### bCanBeBaked

• **bCanBeBaked**: `boolean`

___

### bIsDirty

• **bIsDirty**: `boolean`

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

[Distribution](ue_ue.Distribution.md).[CreateDefaultSubobject](ue_ue.Distribution.md#createdefaultsubobject)

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

[Distribution](ue_ue.Distribution.md).[ExecuteUbergraph](ue_ue.Distribution.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Distribution](ue_ue.Distribution.md).[GetClass](ue_ue.Distribution.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Distribution](ue_ue.Distribution.md).[GetName](ue_ue.Distribution.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Distribution](ue_ue.Distribution.md).[GetOuter](ue_ue.Distribution.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Distribution](ue_ue.Distribution.md).[GetWorld](ue_ue.Distribution.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DistributionVector`](ue_ue.DistributionVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DistributionVector`](ue_ue.DistributionVector.md)

#### Overrides

[Distribution](ue_ue.Distribution.md).[Find](ue_ue.Distribution.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DistributionVector`](ue_ue.DistributionVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DistributionVector`](ue_ue.DistributionVector.md)

#### Overrides

[Distribution](ue_ue.Distribution.md).[Load](ue_ue.Distribution.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Distribution](ue_ue.Distribution.md).[StaticClass](ue_ue.Distribution.md#staticclass)
