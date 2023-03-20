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

## Properties

### BurstList

• **BurstList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleBurst`](ue_ue.ParticleBurst.md)\>

___

### BurstScale

• **BurstScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[LODDuplicate](ue_ue.ParticleModuleSpawnBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[LODValidity](ue_ue.ParticleModuleSpawnBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[ModuleEditorColor](ue_ue.ParticleModuleSpawnBase.md#moduleeditorcolor)

___

### ParticleBurstMethod

• **ParticleBurstMethod**: [`EParticleBurstMethod`](../enums/ue_ue.EParticleBurstMethod.md)

___

### Rate

• **Rate**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### RateScale

• **RateScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[__tid_Object__](ue_ue.ParticleModuleSpawnBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleSpawnBase\_\_

• **\_\_tid\_ParticleModuleSpawnBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[__tid_ParticleModuleSpawnBase__](ue_ue.ParticleModuleSpawnBase.md#__tid_particlemodulespawnbase__)

___

### \_\_tid\_ParticleModuleSpawn\_\_

• **\_\_tid\_ParticleModuleSpawn\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleSpawnBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[b3DDrawMode](ue_ue.ParticleModuleSpawnBase.md#b3ddrawmode)

___

### bApplyGlobalSpawnRateScale

• **bApplyGlobalSpawnRateScale**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bCurvesAsColor](ue_ue.ParticleModuleSpawnBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bEditable](ue_ue.ParticleModuleSpawnBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bEnabled](ue_ue.ParticleModuleSpawnBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleSpawnBase.md#bfinalupdatemodule)

___

### bProcessBurstList

• **bProcessBurstList**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bProcessBurstList](ue_ue.ParticleModuleSpawnBase.md#bprocessburstlist)

___

### bProcessSpawnRate

• **bProcessSpawnRate**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bProcessSpawnRate](ue_ue.ParticleModuleSpawnBase.md#bprocessspawnrate)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleSpawnBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bSpawnModule](ue_ue.ParticleModuleSpawnBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleSpawnBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleSpawnBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleSpawnBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[bUpdateModule](ue_ue.ParticleModuleSpawnBase.md#bupdatemodule)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetClass](ue_ue.ParticleModuleSpawnBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetName](ue_ue.ParticleModuleSpawnBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetOuter](ue_ue.ParticleModuleSpawnBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[GetWorld](ue_ue.ParticleModuleSpawnBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleSpawnBase](ue_ue.ParticleModuleSpawnBase.md).[StaticClass](ue_ue.ParticleModuleSpawnBase.md#staticclass)
