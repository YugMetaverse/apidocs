[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DistributionFloat

# Class: DistributionFloat

[ue/ue](../modules/ue_ue.md).DistributionFloat

## Hierarchy

- [`Distribution`](ue_ue.Distribution.md)

  ↳ **`DistributionFloat`**

  ↳↳ [`DistributionFloatConstant`](ue_ue.DistributionFloatConstant.md)

  ↳↳ [`DistributionFloatConstantCurve`](ue_ue.DistributionFloatConstantCurve.md)

  ↳↳ [`DistributionFloatUniform`](ue_ue.DistributionFloatUniform.md)

  ↳↳ [`DistributionFloatUniformCurve`](ue_ue.DistributionFloatUniformCurve.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DistributionFloat.md#constructor)

### Properties

- [\_\_tid\_DistributionFloat\_\_](ue_ue.DistributionFloat.md#__tid_distributionfloat__)
- [\_\_tid\_Distribution\_\_](ue_ue.DistributionFloat.md#__tid_distribution__)
- [\_\_tid\_Object\_\_](ue_ue.DistributionFloat.md#__tid_object__)
- [bBakedDataSuccesfully](ue_ue.DistributionFloat.md#bbakeddatasuccesfully)
- [bCanBeBaked](ue_ue.DistributionFloat.md#bcanbebaked)

### Methods

- [CreateDefaultSubobject](ue_ue.DistributionFloat.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DistributionFloat.md#executeubergraph)
- [GetClass](ue_ue.DistributionFloat.md#getclass)
- [GetName](ue_ue.DistributionFloat.md#getname)
- [GetOuter](ue_ue.DistributionFloat.md#getouter)
- [GetWorld](ue_ue.DistributionFloat.md#getworld)
- [Find](ue_ue.DistributionFloat.md#find)
- [Load](ue_ue.DistributionFloat.md#load)
- [StaticClass](ue_ue.DistributionFloat.md#staticclass)

## Constructors

### constructor

• **new DistributionFloat**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Distribution](ue_ue.Distribution.md).[constructor](ue_ue.Distribution.md#constructor)

## Properties

### \_\_tid\_DistributionFloat\_\_

• **\_\_tid\_DistributionFloat\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DistributionFloat`](ue_ue.DistributionFloat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DistributionFloat`](ue_ue.DistributionFloat.md)

#### Overrides

[Distribution](ue_ue.Distribution.md).[Find](ue_ue.Distribution.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DistributionFloat`](ue_ue.DistributionFloat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DistributionFloat`](ue_ue.DistributionFloat.md)

#### Overrides

[Distribution](ue_ue.Distribution.md).[Load](ue_ue.Distribution.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Distribution](ue_ue.Distribution.md).[StaticClass](ue_ue.Distribution.md#staticclass)
