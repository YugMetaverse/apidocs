[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleSourceMovement

# Class: ParticleModuleSourceMovement

[ue/ue](../modules/ue_ue.md).ParticleModuleSourceMovement

## Hierarchy

- [`ParticleModuleLocationBase`](ue_ue.ParticleModuleLocationBase.md)

  ↳ **`ParticleModuleSourceMovement`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleSourceMovement.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleSourceMovement.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleSourceMovement.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleSourceMovement.md#moduleeditorcolor)
- [SourceMovementScale](ue_ue.ParticleModuleSourceMovement.md#sourcemovementscale)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_object__)
- [\_\_tid\_ParticleModuleLocationBase\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_particlemodulelocationbase__)
- [\_\_tid\_ParticleModuleSourceMovement\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_particlemodulesourcemovement__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleSourceMovement.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleSourceMovement.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleSourceMovement.md#beditable)
- [bEnabled](ue_ue.ParticleModuleSourceMovement.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleSourceMovement.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleSourceMovement.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleSourceMovement.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleSourceMovement.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleSourceMovement.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleSourceMovement.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleSourceMovement.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleSourceMovement.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleSourceMovement.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleSourceMovement.md#getclass)
- [GetName](ue_ue.ParticleModuleSourceMovement.md#getname)
- [GetOuter](ue_ue.ParticleModuleSourceMovement.md#getouter)
- [GetWorld](ue_ue.ParticleModuleSourceMovement.md#getworld)
- [Find](ue_ue.ParticleModuleSourceMovement.md#find)
- [Load](ue_ue.ParticleModuleSourceMovement.md#load)
- [StaticClass](ue_ue.ParticleModuleSourceMovement.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleSourceMovement**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[constructor](ue_ue.ParticleModuleLocationBase.md#constructor)

#### Defined in

[ue/ue.d.ts:56287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56287)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[LODDuplicate](ue_ue.ParticleModuleLocationBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[LODValidity](ue_ue.ParticleModuleLocationBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[ModuleEditorColor](ue_ue.ParticleModuleLocationBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### SourceMovementScale

• **SourceMovementScale**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:56288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56288)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[__tid_Object__](ue_ue.ParticleModuleLocationBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleLocationBase\_\_

• **\_\_tid\_ParticleModuleLocationBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[__tid_ParticleModuleLocationBase__](ue_ue.ParticleModuleLocationBase.md#__tid_particlemodulelocationbase__)

#### Defined in

[ue/ue.d.ts:55767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55767)

___

### \_\_tid\_ParticleModuleSourceMovement\_\_

• **\_\_tid\_ParticleModuleSourceMovement\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56293)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleLocationBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[b3DDrawMode](ue_ue.ParticleModuleLocationBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bCurvesAsColor](ue_ue.ParticleModuleLocationBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bEditable](ue_ue.ParticleModuleLocationBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bEnabled](ue_ue.ParticleModuleLocationBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleLocationBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleLocationBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bSpawnModule](ue_ue.ParticleModuleLocationBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleLocationBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleLocationBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleLocationBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bUpdateModule](ue_ue.ParticleModuleLocationBase.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6737)

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

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleLocationBase.md#createdefaultsubobject)

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

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleLocationBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetClass](ue_ue.ParticleModuleLocationBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetName](ue_ue.ParticleModuleLocationBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetOuter](ue_ue.ParticleModuleLocationBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetWorld](ue_ue.ParticleModuleLocationBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[Find](ue_ue.ParticleModuleLocationBase.md#find)

#### Defined in

[ue/ue.d.ts:56290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56290)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[Load](ue_ue.ParticleModuleLocationBase.md#load)

#### Defined in

[ue/ue.d.ts:56291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56291)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[StaticClass](ue_ue.ParticleModuleLocationBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:56289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56289)