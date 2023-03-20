[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleOrbit

# Class: ParticleModuleOrbit

[ue/ue](../modules/ue_ue.md).ParticleModuleOrbit

## Hierarchy

- [`ParticleModuleOrbitBase`](ue_ue.ParticleModuleOrbitBase.md)

  ↳ **`ParticleModuleOrbit`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleOrbit.md#constructor)

### Properties

- [ChainMode](ue_ue.ParticleModuleOrbit.md#chainmode)
- [LODDuplicate](ue_ue.ParticleModuleOrbit.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleOrbit.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleOrbit.md#moduleeditorcolor)
- [OffsetAmount](ue_ue.ParticleModuleOrbit.md#offsetamount)
- [OffsetOptions](ue_ue.ParticleModuleOrbit.md#offsetoptions)
- [RotationAmount](ue_ue.ParticleModuleOrbit.md#rotationamount)
- [RotationOptions](ue_ue.ParticleModuleOrbit.md#rotationoptions)
- [RotationRateAmount](ue_ue.ParticleModuleOrbit.md#rotationrateamount)
- [RotationRateOptions](ue_ue.ParticleModuleOrbit.md#rotationrateoptions)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleOrbit.md#__tid_object__)
- [\_\_tid\_ParticleModuleOrbitBase\_\_](ue_ue.ParticleModuleOrbit.md#__tid_particlemoduleorbitbase__)
- [\_\_tid\_ParticleModuleOrbit\_\_](ue_ue.ParticleModuleOrbit.md#__tid_particlemoduleorbit__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleOrbit.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleOrbit.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleOrbit.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleOrbit.md#beditable)
- [bEnabled](ue_ue.ParticleModuleOrbit.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleOrbit.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleOrbit.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleOrbit.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleOrbit.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleOrbit.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleOrbit.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleOrbit.md#bupdatemodule)
- [bUseEmitterTime](ue_ue.ParticleModuleOrbit.md#buseemittertime)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleOrbit.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleOrbit.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleOrbit.md#getclass)
- [GetName](ue_ue.ParticleModuleOrbit.md#getname)
- [GetOuter](ue_ue.ParticleModuleOrbit.md#getouter)
- [GetWorld](ue_ue.ParticleModuleOrbit.md#getworld)
- [Find](ue_ue.ParticleModuleOrbit.md#find)
- [Load](ue_ue.ParticleModuleOrbit.md#load)
- [StaticClass](ue_ue.ParticleModuleOrbit.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleOrbit**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[constructor](ue_ue.ParticleModuleOrbitBase.md#constructor)

#### Defined in

[ue/ue.d.ts:7036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7036)

## Properties

### ChainMode

• **ChainMode**: [`EOrbitChainMode`](../enums/ue_ue.EOrbitChainMode.md)

#### Defined in

[ue/ue.d.ts:7037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7037)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[LODDuplicate](ue_ue.ParticleModuleOrbitBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[LODValidity](ue_ue.ParticleModuleOrbitBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[ModuleEditorColor](ue_ue.ParticleModuleOrbitBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### OffsetAmount

• **OffsetAmount**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:7038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7038)

___

### OffsetOptions

• **OffsetOptions**: [`OrbitOptions`](ue_ue.OrbitOptions.md)

#### Defined in

[ue/ue.d.ts:7039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7039)

___

### RotationAmount

• **RotationAmount**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:7040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7040)

___

### RotationOptions

• **RotationOptions**: [`OrbitOptions`](ue_ue.OrbitOptions.md)

#### Defined in

[ue/ue.d.ts:7041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7041)

___

### RotationRateAmount

• **RotationRateAmount**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:7042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7042)

___

### RotationRateOptions

• **RotationRateOptions**: [`OrbitOptions`](ue_ue.OrbitOptions.md)

#### Defined in

[ue/ue.d.ts:7043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7043)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[__tid_Object__](ue_ue.ParticleModuleOrbitBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleOrbitBase\_\_

• **\_\_tid\_ParticleModuleOrbitBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[__tid_ParticleModuleOrbitBase__](ue_ue.ParticleModuleOrbitBase.md#__tid_particlemoduleorbitbase__)

#### Defined in

[ue/ue.d.ts:6989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6989)

___

### \_\_tid\_ParticleModuleOrbit\_\_

• **\_\_tid\_ParticleModuleOrbit\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7048)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleOrbitBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[b3DDrawMode](ue_ue.ParticleModuleOrbitBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bCurvesAsColor](ue_ue.ParticleModuleOrbitBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bEditable](ue_ue.ParticleModuleOrbitBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bEnabled](ue_ue.ParticleModuleOrbitBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleOrbitBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleOrbitBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bSpawnModule](ue_ue.ParticleModuleOrbitBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleOrbitBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleOrbitBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleOrbitBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bUpdateModule](ue_ue.ParticleModuleOrbitBase.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6737)

___

### bUseEmitterTime

• **bUseEmitterTime**: `boolean`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[bUseEmitterTime](ue_ue.ParticleModuleOrbitBase.md#buseemittertime)

#### Defined in

[ue/ue.d.ts:6984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6984)

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

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleOrbitBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleOrbitBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[GetClass](ue_ue.ParticleModuleOrbitBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[GetName](ue_ue.ParticleModuleOrbitBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[GetOuter](ue_ue.ParticleModuleOrbitBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[GetWorld](ue_ue.ParticleModuleOrbitBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleOrbit`](ue_ue.ParticleModuleOrbit.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleOrbit`](ue_ue.ParticleModuleOrbit.md)

#### Overrides

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[Find](ue_ue.ParticleModuleOrbitBase.md#find)

#### Defined in

[ue/ue.d.ts:7045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7045)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleOrbit`](ue_ue.ParticleModuleOrbit.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleOrbit`](ue_ue.ParticleModuleOrbit.md)

#### Overrides

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[Load](ue_ue.ParticleModuleOrbitBase.md#load)

#### Defined in

[ue/ue.d.ts:7046](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7046)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleOrbitBase](ue_ue.ParticleModuleOrbitBase.md).[StaticClass](ue_ue.ParticleModuleOrbitBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:7044](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7044)
