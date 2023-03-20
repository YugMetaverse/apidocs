[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DistributionVectorUniform

# Class: DistributionVectorUniform

[ue/ue](../modules/ue_ue.md).DistributionVectorUniform

## Hierarchy

- [`DistributionVector`](ue_ue.DistributionVector.md)

  ↳ **`DistributionVectorUniform`**

## Table of contents

### Constructors

- [constructor](ue_ue.DistributionVectorUniform.md#constructor)

### Properties

- [LockedAxes](ue_ue.DistributionVectorUniform.md#lockedaxes)
- [Max](ue_ue.DistributionVectorUniform.md#max)
- [Min](ue_ue.DistributionVectorUniform.md#min)
- [MirrorFlags](ue_ue.DistributionVectorUniform.md#mirrorflags)
- [\_\_tid\_DistributionVectorUniform\_\_](ue_ue.DistributionVectorUniform.md#__tid_distributionvectoruniform__)
- [\_\_tid\_DistributionVector\_\_](ue_ue.DistributionVectorUniform.md#__tid_distributionvector__)
- [\_\_tid\_Distribution\_\_](ue_ue.DistributionVectorUniform.md#__tid_distribution__)
- [\_\_tid\_Object\_\_](ue_ue.DistributionVectorUniform.md#__tid_object__)
- [bBakedDataSuccesfully](ue_ue.DistributionVectorUniform.md#bbakeddatasuccesfully)
- [bCanBeBaked](ue_ue.DistributionVectorUniform.md#bcanbebaked)
- [bIsDirty](ue_ue.DistributionVectorUniform.md#bisdirty)
- [bLockAxes](ue_ue.DistributionVectorUniform.md#blockaxes)
- [bUseExtremes](ue_ue.DistributionVectorUniform.md#buseextremes)

### Methods

- [CreateDefaultSubobject](ue_ue.DistributionVectorUniform.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DistributionVectorUniform.md#executeubergraph)
- [GetClass](ue_ue.DistributionVectorUniform.md#getclass)
- [GetName](ue_ue.DistributionVectorUniform.md#getname)
- [GetOuter](ue_ue.DistributionVectorUniform.md#getouter)
- [GetWorld](ue_ue.DistributionVectorUniform.md#getworld)
- [Find](ue_ue.DistributionVectorUniform.md#find)
- [Load](ue_ue.DistributionVectorUniform.md#load)
- [StaticClass](ue_ue.DistributionVectorUniform.md#staticclass)

## Constructors

### constructor

• **new DistributionVectorUniform**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[constructor](ue_ue.DistributionVector.md#constructor)

## Properties

### LockedAxes

• **LockedAxes**: [`EDistributionVectorLockFlags`](../enums/ue_ue.EDistributionVectorLockFlags.md)

___

### Max

• **Max**: [`Vector`](ue_ue_s.Vector.md)

___

### Min

• **Min**: [`Vector`](ue_ue_s.Vector.md)

___

### MirrorFlags

• **MirrorFlags**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`EDistributionVectorMirrorFlags`](../enums/ue_ue.EDistributionVectorMirrorFlags.md)\>

___

### \_\_tid\_DistributionVectorUniform\_\_

• **\_\_tid\_DistributionVectorUniform\_\_**: `boolean`

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

### bLockAxes

• **bLockAxes**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DistributionVectorUniform`](ue_ue.DistributionVectorUniform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DistributionVectorUniform`](ue_ue.DistributionVectorUniform.md)

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[Find](ue_ue.DistributionVector.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DistributionVectorUniform`](ue_ue.DistributionVectorUniform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DistributionVectorUniform`](ue_ue.DistributionVectorUniform.md)

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[Load](ue_ue.DistributionVector.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DistributionVector](ue_ue.DistributionVector.md).[StaticClass](ue_ue.DistributionVector.md#staticclass)
