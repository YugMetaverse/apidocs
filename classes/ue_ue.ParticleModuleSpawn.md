[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleSpawn

# Class: ParticleModuleSpawn

[ue/ue](../modules/ue_ue.md).ParticleModuleSpawn

## Hierarchy

- [`ParticleModuleSpawnBase`](ue_ue.ParticleModuleSpawnBase.md)

  ↳ **`ParticleModuleSpawn`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleSpawn.md#constructor)

### Properties

- [BurstList](ue_ue.ParticleModuleSpawn.md#burstlist)
- [BurstScale](ue_ue.ParticleModuleSpawn.md#burstscale)
- [LODDuplicate](ue_ue.ParticleModuleSpawn.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleSpawn.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleSpawn.md#moduleeditorcolor)
- [ParticleBurstMethod](ue_ue.ParticleModuleSpawn.md#particleburstmethod)
- [Rate](ue_ue.ParticleModuleSpawn.md#rate)
- [RateScale](ue_ue.ParticleModuleSpawn.md#ratescale)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleSpawn.md#__tid_object__)
- [\_\_tid\_ParticleModuleSpawnBase\_\_](ue_ue.ParticleModuleSpawn.md#__tid_particlemodulespawnbase__)
- [\_\_tid\_ParticleModuleSpawn\_\_](ue_ue.ParticleModuleSpawn.md#__tid_particlemodulespawn__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleSpawn.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleSpawn.md#b3ddrawmode)
- [bApplyGlobalSpawnRateScale](ue_ue.ParticleModuleSpawn.md#bapplyglobalspawnratescale)
- [bCurvesAsColor](ue_ue.ParticleModuleSpawn.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleSpawn.md#beditable)
- [bEnabled](ue_ue.ParticleModuleSpawn.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleSpawn.md#bfinalupdatemodule)
- [bProcessBurstList](ue_ue.ParticleModuleSpawn.md#bprocessburstlist)
- [bProcessSpawnRate](ue_ue.ParticleModuleSpawn.md#bprocessspawnrate)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleSpawn.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleSpawn.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleSpawn.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleSpawn.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleSpawn.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleSpawn.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleSpawn.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleSpawn.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleSpawn.md#getclass)
- [GetName](ue_ue.ParticleModuleSpawn.md#getname)
- [GetOuter](ue_ue.ParticleModuleSpawn.md#getouter)
- [GetWorld](ue_ue.ParticleModuleSpawn.md#getworld)
- [Find](ue_ue.ParticleModuleSpawn.md#find)
- [Load](ue_ue.ParticleModuleSpawn.md#load)
- [StaticClass](ue_ue.ParticleModuleSpawn.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleSpawn**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[constructor](ue_ue.ParticleModuleSpawnBase.md#constructor)

#### Defined in

[ue/ue.d.ts:6919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6919)

## Properties

### BurstList

• **BurstList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleBurst`](ue_ue.ParticleBurst.md)\>

#### Defined in

[ue/ue.d.ts:6923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6923)

___

### BurstScale

• **BurstScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:6924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6924)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[LODDuplicate](ue_ue.ParticleModuleSpawnBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[LODValidity](ue_ue.ParticleModuleSpawnBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[ModuleEditorColor](ue_ue.ParticleModuleSpawnBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### ParticleBurstMethod

• **ParticleBurstMethod**: [`EParticleBurstMethod`](../enums/ue_ue.EParticleBurstMethod.md)

#### Defined in

[ue/ue.d.ts:6922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6922)

___

### Rate

• **Rate**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:6920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6920)

___

### RateScale

• **RateScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:6921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6921)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[__tid_Object__](ue_ue.ParticleModuleSpawnBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleSpawnBase\_\_

• **\_\_tid\_ParticleModuleSpawnBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[__tid_ParticleModuleSpawnBase__](ue_ue.ParticleModuleSpawnBase.md#__tid_particlemodulespawnbase__)

#### Defined in

[ue/ue.d.ts:6915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6915)

___

### \_\_tid\_ParticleModuleSpawn\_\_

• **\_\_tid\_ParticleModuleSpawn\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6930)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleSpawnBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[b3DDrawMode](ue_ue.ParticleModuleSpawnBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bApplyGlobalSpawnRateScale

• **bApplyGlobalSpawnRateScale**: `boolean`

#### Defined in

[ue/ue.d.ts:6925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6925)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bCurvesAsColor](ue_ue.ParticleModuleSpawnBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bEditable](ue_ue.ParticleModuleSpawnBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bEnabled](ue_ue.ParticleModuleSpawnBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleSpawnBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bProcessBurstList

• **bProcessBurstList**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bProcessBurstList](ue_ue.ParticleModuleSpawnBase.md#bprocessburstlist)

#### Defined in

[ue/ue.d.ts:6910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6910)

___

### bProcessSpawnRate

• **bProcessSpawnRate**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bProcessSpawnRate](ue_ue.ParticleModuleSpawnBase.md#bprocessspawnrate)

#### Defined in

[ue/ue.d.ts:6909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6909)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleSpawnBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bSpawnModule](ue_ue.ParticleModuleSpawnBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleSpawnBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleSpawnBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleSpawnBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bUpdateModule](ue_ue.ParticleModuleSpawnBase.md#bupdatemodule)

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

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleSpawnBase.md#createdefaultsubobject)

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

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleSpawnBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetClass](ue_ue.ParticleModuleSpawnBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetName](ue_ue.ParticleModuleSpawnBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetOuter](ue_ue.ParticleModuleSpawnBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetWorld](ue_ue.ParticleModuleSpawnBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

#### Overrides

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[Find](ue_ue.ParticleModuleSpawnBase.md#find)

#### Defined in

[ue/ue.d.ts:6927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6927)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

#### Overrides

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[Load](ue_ue.ParticleModuleSpawnBase.md#load)

#### Defined in

[ue/ue.d.ts:6928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6928)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[StaticClass](ue_ue.ParticleModuleSpawnBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:6926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6926)
