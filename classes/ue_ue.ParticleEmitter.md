[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleEmitter

# Class: ParticleEmitter

[ue/ue](../modules/ue_ue.md).ParticleEmitter

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ParticleEmitter`**

  ↳↳ [`ParticleSpriteEmitter`](ue_ue.ParticleSpriteEmitter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleEmitter.md#constructor)

### Properties

- [ConvertedModules](ue_ue.ParticleEmitter.md#convertedmodules)
- [DetailMode](ue_ue.ParticleEmitter.md#detailmode)
- [DetailModeBitmask](ue_ue.ParticleEmitter.md#detailmodebitmask)
- [DetailModeDisplay](ue_ue.ParticleEmitter.md#detailmodedisplay)
- [EmitterEditorColor](ue_ue.ParticleEmitter.md#emittereditorcolor)
- [EmitterName](ue_ue.ParticleEmitter.md#emittername)
- [EmitterRenderMode](ue_ue.ParticleEmitter.md#emitterrendermode)
- [InitialAllocationCount](ue_ue.ParticleEmitter.md#initialallocationcount)
- [LODLevels](ue_ue.ParticleEmitter.md#lodlevels)
- [PeakActiveParticles](ue_ue.ParticleEmitter.md#peakactiveparticles)
- [QualityLevelSpawnRateScale](ue_ue.ParticleEmitter.md#qualitylevelspawnratescale)
- [SignificanceLevel](ue_ue.ParticleEmitter.md#significancelevel)
- [SubUVDataOffset](ue_ue.ParticleEmitter.md#subuvdataoffset)
- [\_\_tid\_Object\_\_](ue_ue.ParticleEmitter.md#__tid_object__)
- [\_\_tid\_ParticleEmitter\_\_](ue_ue.ParticleEmitter.md#__tid_particleemitter__)
- [bCollapsed](ue_ue.ParticleEmitter.md#bcollapsed)
- [bCookedOut](ue_ue.ParticleEmitter.md#bcookedout)
- [bDisableWhenInsignficant](ue_ue.ParticleEmitter.md#bdisablewheninsignficant)
- [bDisabledLODsKeepEmitterAlive](ue_ue.ParticleEmitter.md#bdisabledlodskeepemitteralive)
- [bIsSoloing](ue_ue.ParticleEmitter.md#bissoloing)
- [bUseLegacySpawningBehavior](ue_ue.ParticleEmitter.md#buselegacyspawningbehavior)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleEmitter.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleEmitter.md#executeubergraph)
- [GetClass](ue_ue.ParticleEmitter.md#getclass)
- [GetName](ue_ue.ParticleEmitter.md#getname)
- [GetOuter](ue_ue.ParticleEmitter.md#getouter)
- [GetWorld](ue_ue.ParticleEmitter.md#getworld)
- [Find](ue_ue.ParticleEmitter.md#find)
- [Load](ue_ue.ParticleEmitter.md#load)
- [StaticClass](ue_ue.ParticleEmitter.md#staticclass)

## Constructors

### constructor

• **new ParticleEmitter**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

___

### DetailModeBitmask

• **DetailModeBitmask**: `number`

___

### DetailModeDisplay

• **DetailModeDisplay**: `string`

___

### EmitterEditorColor

• **EmitterEditorColor**: [`Color`](ue_ue_s.Color.md)

___

### EmitterName

• **EmitterName**: `string`

___

### EmitterRenderMode

• **EmitterRenderMode**: [`EEmitterRenderMode`](../enums/ue_ue.EEmitterRenderMode.md)

___

### InitialAllocationCount

• **InitialAllocationCount**: `number`

___

### LODLevels

• **LODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleLODLevel`](ue_ue.ParticleLODLevel.md)\>

___

### PeakActiveParticles

• **PeakActiveParticles**: `number`

___

### QualityLevelSpawnRateScale

• **QualityLevelSpawnRateScale**: `number`

___

### SignificanceLevel

• **SignificanceLevel**: [`EParticleSignificanceLevel`](../enums/ue_ue.EParticleSignificanceLevel.md)

___

### SubUVDataOffset

• **SubUVDataOffset**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ParticleEmitter\_\_

• **\_\_tid\_ParticleEmitter\_\_**: `boolean`

___

### bCollapsed

• **bCollapsed**: `boolean`

___

### bCookedOut

• **bCookedOut**: `boolean`

___

### bDisableWhenInsignficant

• **bDisableWhenInsignficant**: `boolean`

___

### bDisabledLODsKeepEmitterAlive

• **bDisabledLODsKeepEmitterAlive**: `boolean`

___

### bIsSoloing

• **bIsSoloing**: `boolean`

___

### bUseLegacySpawningBehavior

• **bUseLegacySpawningBehavior**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleEmitter`](ue_ue.ParticleEmitter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleEmitter`](ue_ue.ParticleEmitter.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleEmitter`](ue_ue.ParticleEmitter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleEmitter`](ue_ue.ParticleEmitter.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
