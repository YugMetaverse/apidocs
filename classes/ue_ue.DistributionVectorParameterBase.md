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

#### Defined in

[ue/ue.d.ts:31075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31075)

## Properties

### Constant

• **Constant**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[Constant](ue_ue.DistributionVectorConstant.md#constant)

#### Defined in

[ue/ue.d.ts:31052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31052)

___

### LockedAxes

• **LockedAxes**: [`EDistributionVectorLockFlags`](../enums/ue_ue.EDistributionVectorLockFlags.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[LockedAxes](ue_ue.DistributionVectorConstant.md#lockedaxes)

#### Defined in

[ue/ue.d.ts:31054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31054)

___

### MaxInput

• **MaxInput**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:31078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31078)

___

### MaxOutput

• **MaxOutput**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:31080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31080)

___

### MinInput

• **MinInput**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:31077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31077)

___

### MinOutput

• **MinOutput**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:31079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31079)

___

### ParamModes

• **ParamModes**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`DistributionParamMode`](../enums/ue_ue.DistributionParamMode.md)\>

#### Defined in

[ue/ue.d.ts:31081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31081)

___

### ParameterName

• **ParameterName**: `string`

#### Defined in

[ue/ue.d.ts:31076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31076)

___

### \_\_tid\_DistributionVectorConstant\_\_

• **\_\_tid\_DistributionVectorConstant\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_DistributionVectorConstant__](ue_ue.DistributionVectorConstant.md#__tid_distributionvectorconstant__)

#### Defined in

[ue/ue.d.ts:31059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31059)

___

### \_\_tid\_DistributionVectorParameterBase\_\_

• **\_\_tid\_DistributionVectorParameterBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:31086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31086)

___

### \_\_tid\_DistributionVector\_\_

• **\_\_tid\_DistributionVector\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_DistributionVector__](ue_ue.DistributionVectorConstant.md#__tid_distributionvector__)

#### Defined in

[ue/ue.d.ts:7002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7002)

___

### \_\_tid\_Distribution\_\_

• **\_\_tid\_Distribution\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_Distribution__](ue_ue.DistributionVectorConstant.md#__tid_distribution__)

#### Defined in

[ue/ue.d.ts:6796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6796)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[__tid_Object__](ue_ue.DistributionVectorConstant.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bBakedDataSuccesfully

• **bBakedDataSuccesfully**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bBakedDataSuccesfully](ue_ue.DistributionVectorConstant.md#bbakeddatasuccesfully)

#### Defined in

[ue/ue.d.ts:6997](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6997)

___

### bCanBeBaked

• **bCanBeBaked**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bCanBeBaked](ue_ue.DistributionVectorConstant.md#bcanbebaked)

#### Defined in

[ue/ue.d.ts:6995](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6995)

___

### bIsDirty

• **bIsDirty**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bIsDirty](ue_ue.DistributionVectorConstant.md#bisdirty)

#### Defined in

[ue/ue.d.ts:6996](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6996)

___

### bLockAxes

• **bLockAxes**: `boolean`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[bLockAxes](ue_ue.DistributionVectorConstant.md#blockaxes)

#### Defined in

[ue/ue.d.ts:31053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31053)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetClass](ue_ue.DistributionVectorConstant.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetName](ue_ue.DistributionVectorConstant.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetOuter](ue_ue.DistributionVectorConstant.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[GetWorld](ue_ue.DistributionVectorConstant.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:31083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31083)

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

#### Defined in

[ue/ue.d.ts:31084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31084)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DistributionVectorConstant](ue_ue.DistributionVectorConstant.md).[StaticClass](ue_ue.DistributionVectorConstant.md#staticclass)

#### Defined in

[ue/ue.d.ts:31082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L31082)
