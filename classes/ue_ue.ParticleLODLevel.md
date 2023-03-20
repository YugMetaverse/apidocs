[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleLODLevel

# Class: ParticleLODLevel

[ue/ue](../modules/ue_ue.md).ParticleLODLevel

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ParticleLODLevel`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleLODLevel.md#constructor)

### Properties

- [ConvertedModules](ue_ue.ParticleLODLevel.md#convertedmodules)
- [EventGenerator](ue_ue.ParticleLODLevel.md#eventgenerator)
- [EventReceiverModules](ue_ue.ParticleLODLevel.md#eventreceivermodules)
- [Level](ue_ue.ParticleLODLevel.md#level)
- [Modules](ue_ue.ParticleLODLevel.md#modules)
- [OrbitModules](ue_ue.ParticleLODLevel.md#orbitmodules)
- [PeakActiveParticles](ue_ue.ParticleLODLevel.md#peakactiveparticles)
- [RequiredModule](ue_ue.ParticleLODLevel.md#requiredmodule)
- [SpawnModule](ue_ue.ParticleLODLevel.md#spawnmodule)
- [SpawnModules](ue_ue.ParticleLODLevel.md#spawnmodules)
- [SpawningModules](ue_ue.ParticleLODLevel.md#spawningmodules)
- [TypeDataModule](ue_ue.ParticleLODLevel.md#typedatamodule)
- [UpdateModules](ue_ue.ParticleLODLevel.md#updatemodules)
- [\_\_tid\_Object\_\_](ue_ue.ParticleLODLevel.md#__tid_object__)
- [\_\_tid\_ParticleLODLevel\_\_](ue_ue.ParticleLODLevel.md#__tid_particlelodlevel__)
- [bEnabled](ue_ue.ParticleLODLevel.md#benabled)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleLODLevel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleLODLevel.md#executeubergraph)
- [GetClass](ue_ue.ParticleLODLevel.md#getclass)
- [GetName](ue_ue.ParticleLODLevel.md#getname)
- [GetOuter](ue_ue.ParticleLODLevel.md#getouter)
- [GetWorld](ue_ue.ParticleLODLevel.md#getworld)
- [Find](ue_ue.ParticleLODLevel.md#find)
- [Load](ue_ue.ParticleLODLevel.md#load)
- [StaticClass](ue_ue.ParticleLODLevel.md#staticclass)

## Constructors

### constructor

• **new ParticleLODLevel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ConvertedModules

• **ConvertedModules**: `boolean`

___

### EventGenerator

• **EventGenerator**: [`ParticleModuleEventGenerator`](ue_ue.ParticleModuleEventGenerator.md)

___

### EventReceiverModules

• **EventReceiverModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModuleEventReceiverBase`](ue_ue.ParticleModuleEventReceiverBase.md)\>

___

### Level

• **Level**: `number`

___

### Modules

• **Modules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModule`](ue_ue.ParticleModule.md)\>

___

### OrbitModules

• **OrbitModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModuleOrbit`](ue_ue.ParticleModuleOrbit.md)\>

___

### PeakActiveParticles

• **PeakActiveParticles**: `number`

___

### RequiredModule

• **RequiredModule**: [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

___

### SpawnModule

• **SpawnModule**: [`ParticleModuleSpawn`](ue_ue.ParticleModuleSpawn.md)

___

### SpawnModules

• **SpawnModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModule`](ue_ue.ParticleModule.md)\>

___

### SpawningModules

• **SpawningModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModuleSpawnBase`](ue_ue.ParticleModuleSpawnBase.md)\>

___

### TypeDataModule

• **TypeDataModule**: [`ParticleModuleTypeDataBase`](ue_ue.ParticleModuleTypeDataBase.md)

___

### UpdateModules

• **UpdateModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModule`](ue_ue.ParticleModule.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ParticleLODLevel\_\_

• **\_\_tid\_ParticleLODLevel\_\_**: `boolean`

___

### bEnabled

• **bEnabled**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleLODLevel`](ue_ue.ParticleLODLevel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleLODLevel`](ue_ue.ParticleLODLevel.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleLODLevel`](ue_ue.ParticleLODLevel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleLODLevel`](ue_ue.ParticleLODLevel.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
