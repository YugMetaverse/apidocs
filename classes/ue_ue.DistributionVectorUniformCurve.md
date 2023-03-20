[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DistributionVectorUniformCurve

# Class: DistributionVectorUniformCurve

[ue/ue](../modules/ue_ue.md).DistributionVectorUniformCurve

## Hierarchy

- [`DistributionVector`](ue_ue.DistributionVector.md)

  ↳ **`DistributionVectorUniformCurve`**

## Table of contents

### Constructors

- [constructor](ue_ue.DistributionVectorUniformCurve.md#constructor)

### Properties

- [ConstantCurve](ue_ue.DistributionVectorUniformCurve.md#constantcurve)
- [LockedAxes](ue_ue.DistributionVectorUniformCurve.md#lockedaxes)
- [MirrorFlags](ue_ue.DistributionVectorUniformCurve.md#mirrorflags)
- [\_\_tid\_DistributionVectorUniformCurve\_\_](ue_ue.DistributionVectorUniformCurve.md#__tid_distributionvectoruniformcurve__)
- [\_\_tid\_DistributionVector\_\_](ue_ue.DistributionVectorUniformCurve.md#__tid_distributionvector__)
- [\_\_tid\_Distribution\_\_](ue_ue.DistributionVectorUniformCurve.md#__tid_distribution__)
- [\_\_tid\_Object\_\_](ue_ue.DistributionVectorUniformCurve.md#__tid_object__)
- [bBakedDataSuccesfully](ue_ue.DistributionVectorUniformCurve.md#bbakeddatasuccesfully)
- [bCanBeBaked](ue_ue.DistributionVectorUniformCurve.md#bcanbebaked)
- [bIsDirty](ue_ue.DistributionVectorUniformCurve.md#bisdirty)
- [bLockAxes1](ue_ue.DistributionVectorUniformCurve.md#blockaxes1)
- [bLockAxes2](ue_ue.DistributionVectorUniformCurve.md#blockaxes2)
- [bUseExtremes](ue_ue.DistributionVectorUniformCurve.md#buseextremes)

### Methods

- [CreateDefaultSubobject](ue_ue.DistributionVectorUniformCurve.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DistributionVectorUniformCurve.md#executeubergraph)
- [GetClass](ue_ue.DistributionVectorUniformCurve.md#getclass)
- [GetName](ue_ue.DistributionVectorUniformCurve.md#getname)
- [GetOuter](ue_ue.DistributionVectorUniformCurve.md#getouter)
- [GetWorld](ue_ue.DistributionVectorUniformCurve.md#getworld)
- [Find](ue_ue.DistributionVectorUniformCurve.md#find)
- [Load](ue_ue.DistributionVectorUniformCurve.md#load)
- [StaticClass](ue_ue.DistributionVectorUniformCurve.md#staticclass)

## Constructors

### constructor

• **new DistributionVectorUniformCurve**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[constructor](ue_ue.DistributionVector.md#constructor)

## Properties

### ConstantCurve

• **ConstantCurve**: [`InterpCurveTwoVectors`](ue_ue.InterpCurveTwoVectors.md)

___

### LockedAxes

• **LockedAxes**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`EDistributionVectorLockFlags`](../enums/ue_ue.EDistributionVectorLockFlags.md)\>

___

### MirrorFlags

• **MirrorFlags**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`EDistributionVectorMirrorFlags`](../enums/ue_ue.EDistributionVectorMirrorFlags.md)\>

___

### \_\_tid\_DistributionVectorUniformCurve\_\_

• **\_\_tid\_DistributionVectorUniformCurve\_\_**: `boolean`

___

### \_\_tid\_DistributionVector\_\_

• **\_\_tid\_DistributionVector\_\_**: `boolean`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[__tid_DistributionVector__](ue_ue.DistributionVector.md#__tid_distributionvector__)

___

### \_\_tid\_Distribution\_\_

• **\_\_tid\_Distribution\_\_**: `boolean`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[__tid_Distribution__](ue_ue.DistributionVector.md#__tid_distribution__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[__tid_Object__](ue_ue.DistributionVector.md#__tid_object__)

___

### bBakedDataSuccesfully

• **bBakedDataSuccesfully**: `boolean`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[bBakedDataSuccesfully](ue_ue.DistributionVector.md#bbakeddatasuccesfully)

___

### bCanBeBaked

• **bCanBeBaked**: `boolean`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[bCanBeBaked](ue_ue.DistributionVector.md#bcanbebaked)

___

### bIsDirty

• **bIsDirty**: `boolean`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[bIsDirty](ue_ue.DistributionVector.md#bisdirty)

___

### bLockAxes1

• **bLockAxes1**: `boolean`

___

### bLockAxes2

• **bLockAxes2**: `boolean`

___

### bUseExtremes

• **bUseExtremes**: `boolean`

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

[DistributionVector](ue_ue.DistributionVector.md).[CreateDefaultSubobject](ue_ue.DistributionVector.md#createdefaultsubobject)

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

[DistributionVector](ue_ue.DistributionVector.md).[ExecuteUbergraph](ue_ue.DistributionVector.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[GetClass](ue_ue.DistributionVector.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[GetName](ue_ue.DistributionVector.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[GetOuter](ue_ue.DistributionVector.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DistributionVector](ue_ue.DistributionVector.md).[GetWorld](ue_ue.DistributionVector.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DistributionVectorUniformCurve`](ue_ue.DistributionVectorUniformCurve.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DistributionVectorUniformCurve`](ue_ue.DistributionVectorUniformCurve.md)

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[Find](ue_ue.DistributionVector.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DistributionVectorUniformCurve`](ue_ue.DistributionVectorUniformCurve.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DistributionVectorUniformCurve`](ue_ue.DistributionVectorUniformCurve.md)

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[Load](ue_ue.DistributionVector.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[StaticClass](ue_ue.DistributionVector.md#staticclass)
