[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DistributionVectorParameterBase

# Class: DistributionVectorParameterBase

[ue/ue](../modules/ue_ue.md).DistributionVectorParameterBase

## Hierarchy

- [`DistributionVectorConstant`](ue_ue.DistributionVectorConstant.md)

  ↳ **`DistributionVectorParameterBase`**

  ↳↳ [`DistributionVectorParticleParameter`](ue_ue.DistributionVectorParticleParameter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DistributionVectorParameterBase.md#constructor)

### Properties

- [Constant](ue_ue.DistributionVectorParameterBase.md#constant)
- [LockedAxes](ue_ue.DistributionVectorParameterBase.md#lockedaxes)
- [MaxInput](ue_ue.DistributionVectorParameterBase.md#maxinput)
- [MaxOutput](ue_ue.DistributionVectorParameterBase.md#maxoutput)
- [MinInput](ue_ue.DistributionVectorParameterBase.md#mininput)
- [MinOutput](ue_ue.DistributionVectorParameterBase.md#minoutput)
- [ParamModes](ue_ue.DistributionVectorParameterBase.md#parammodes)
- [ParameterName](ue_ue.DistributionVectorParameterBase.md#parametername)
- [\_\_tid\_DistributionVectorConstant\_\_](ue_ue.DistributionVectorParameterBase.md#__tid_distributionvectorconstant__)
- [\_\_tid\_DistributionVectorParameterBase\_\_](ue_ue.DistributionVectorParameterBase.md#__tid_distributionvectorparameterbase__)
- [\_\_tid\_DistributionVector\_\_](ue_ue.DistributionVectorParameterBase.md#__tid_distributionvector__)
- [\_\_tid\_Distribution\_\_](ue_ue.DistributionVectorParameterBase.md#__tid_distribution__)
- [\_\_tid\_Object\_\_](ue_ue.DistributionVectorParameterBase.md#__tid_object__)
- [bBakedDataSuccesfully](ue_ue.DistributionVectorParameterBase.md#bbakeddatasuccesfully)
- [bCanBeBaked](ue_ue.DistributionVectorParameterBase.md#bcanbebaked)
- [bIsDirty](ue_ue.DistributionVectorParameterBase.md#bisdirty)
- [bLockAxes](ue_ue.DistributionVectorParameterBase.md#blockaxes)

### Methods

- [CreateDefaultSubobject](ue_ue.DistributionVectorParameterBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DistributionVectorParameterBase.md#executeubergraph)
- [GetClass](ue_ue.DistributionVectorParameterBase.md#getclass)
- [GetName](ue_ue.DistributionVectorParameterBase.md#getname)
- [GetOuter](ue_ue.DistributionVectorParameterBase.md#getouter)
- [GetWorld](ue_ue.DistributionVectorParameterBase.md#getworld)
- [Find](ue_ue.DistributionVectorParameterBase.md#find)
- [Load](ue_ue.DistributionVectorParameterBase.md#load)
- [StaticClass](ue_ue.DistributionVectorParameterBase.md#staticclass)

## Constructors

### constructor

• **new DistributionVectorParameterBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[constructor](ue_ue.DistributionVectorConstant.md#constructor)

## Properties

### Constant

• **Constant**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[Constant](ue_ue.DistributionVectorConstant.md#constant)

___

### LockedAxes

• **LockedAxes**: [`EDistributionVectorLockFlags`](../enums/ue_ue.EDistributionVectorLockFlags.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[LockedAxes](ue_ue.DistributionVectorConstant.md#lockedaxes)

___

### MaxInput

• **MaxInput**: [`Vector`](ue_ue_s.Vector.md)

___

### MaxOutput

• **MaxOutput**: [`Vector`](ue_ue_s.Vector.md)

___

### MinInput

• **MinInput**: [`Vector`](ue_ue_s.Vector.md)

___

### MinOutput

• **MinOutput**: [`Vector`](ue_ue_s.Vector.md)

___

### ParamModes

• **ParamModes**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`DistributionParamMode`](../enums/ue_ue.DistributionParamMode.md)\>

___

### ParameterName

• **ParameterName**: `string`

___

### \_\_tid\_DistributionVectorConstant\_\_

• **\_\_tid\_DistributionVectorConstant\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_DistributionVectorConstant__](ue_ue.DistributionVectorConstant.md#__tid_distributionvectorconstant__)

___

### \_\_tid\_DistributionVectorParameterBase\_\_

• **\_\_tid\_DistributionVectorParameterBase\_\_**: `boolean`

___

### \_\_tid\_DistributionVector\_\_

• **\_\_tid\_DistributionVector\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_DistributionVector__](ue_ue.DistributionVectorConstant.md#__tid_distributionvector__)

___

### \_\_tid\_Distribution\_\_

• **\_\_tid\_Distribution\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_Distribution__](ue_ue.DistributionVectorConstant.md#__tid_distribution__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_Object__](ue_ue.DistributionVectorConstant.md#__tid_object__)

___

### bBakedDataSuccesfully

• **bBakedDataSuccesfully**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bBakedDataSuccesfully](ue_ue.DistributionVectorConstant.md#bbakeddatasuccesfully)

___

### bCanBeBaked

• **bCanBeBaked**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bCanBeBaked](ue_ue.DistributionVectorConstant.md#bcanbebaked)

___

### bIsDirty

• **bIsDirty**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bIsDirty](ue_ue.DistributionVectorConstant.md#bisdirty)

___

### bLockAxes

• **bLockAxes**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bLockAxes](ue_ue.DistributionVectorConstant.md#blockaxes)

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

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[CreateDefaultSubobject](ue_ue.DistributionVectorConstant.md#createdefaultsubobject)

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

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[ExecuteUbergraph](ue_ue.DistributionVectorConstant.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetClass](ue_ue.DistributionVectorConstant.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetName](ue_ue.DistributionVectorConstant.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetOuter](ue_ue.DistributionVectorConstant.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetWorld](ue_ue.DistributionVectorConstant.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DistributionVectorParameterBase`](ue_ue.DistributionVectorParameterBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DistributionVectorParameterBase`](ue_ue.DistributionVectorParameterBase.md)

#### Overrides

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[Find](ue_ue.DistributionVectorConstant.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DistributionVectorParameterBase`](ue_ue.DistributionVectorParameterBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DistributionVectorParameterBase`](ue_ue.DistributionVectorParameterBase.md)

#### Overrides

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[Load](ue_ue.DistributionVectorConstant.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[StaticClass](ue_ue.DistributionVectorConstant.md#staticclass)
