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

#### Defined in

[ue/ue.d.ts:7086](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7086)

## Properties

### ConvertedModules

• **ConvertedModules**: `boolean`

#### Defined in

[ue/ue.d.ts:7092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7092)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Defined in

[ue/ue.d.ts:7098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7098)

___

### DetailModeBitmask

• **DetailModeBitmask**: `number`

#### Defined in

[ue/ue.d.ts:7104](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7104)

___

### DetailModeDisplay

• **DetailModeDisplay**: `string`

#### Defined in

[ue/ue.d.ts:7105](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7105)

___

### EmitterEditorColor

• **EmitterEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:7099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7099)

___

### EmitterName

• **EmitterName**: `string`

#### Defined in

[ue/ue.d.ts:7087](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7087)

___

### EmitterRenderMode

• **EmitterRenderMode**: [`EEmitterRenderMode`](../enums/ue_ue.EEmitterRenderMode.md)

#### Defined in

[ue/ue.d.ts:7089](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7089)

___

### InitialAllocationCount

• **InitialAllocationCount**: `number`

#### Defined in

[ue/ue.d.ts:7102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7102)

___

### LODLevels

• **LODLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleLODLevel`](ue_ue.ParticleLODLevel.md)\>

#### Defined in

[ue/ue.d.ts:7100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7100)

___

### PeakActiveParticles

• **PeakActiveParticles**: `number`

#### Defined in

[ue/ue.d.ts:7101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7101)

___

### QualityLevelSpawnRateScale

• **QualityLevelSpawnRateScale**: `number`

#### Defined in

[ue/ue.d.ts:7103](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7103)

___

### SignificanceLevel

• **SignificanceLevel**: [`EParticleSignificanceLevel`](../enums/ue_ue.EParticleSignificanceLevel.md)

#### Defined in

[ue/ue.d.ts:7090](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7090)

___

### SubUVDataOffset

• **SubUVDataOffset**: `number`

#### Defined in

[ue/ue.d.ts:7088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7088)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleEmitter\_\_

• **\_\_tid\_ParticleEmitter\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7110](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7110)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Defined in

[ue/ue.d.ts:7097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7097)

___

### bCookedOut

• **bCookedOut**: `boolean`

#### Defined in

[ue/ue.d.ts:7094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7094)

___

### bDisableWhenInsignficant

• **bDisableWhenInsignficant**: `boolean`

#### Defined in

[ue/ue.d.ts:7096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7096)

___

### bDisabledLODsKeepEmitterAlive

• **bDisabledLODsKeepEmitterAlive**: `boolean`

#### Defined in

[ue/ue.d.ts:7095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7095)

___

### bIsSoloing

• **bIsSoloing**: `boolean`

#### Defined in

[ue/ue.d.ts:7093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7093)

___

### bUseLegacySpawningBehavior

• **bUseLegacySpawningBehavior**: `boolean`

#### Defined in

[ue/ue.d.ts:7091](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7091)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:7107](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7107)

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

#### Defined in

[ue/ue.d.ts:7108](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7108)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:7106](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7106)
