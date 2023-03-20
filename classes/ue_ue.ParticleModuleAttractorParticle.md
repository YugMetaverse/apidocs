[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleAttractorParticle

# Class: ParticleModuleAttractorParticle

[ue/ue](../modules/ue_ue.md).ParticleModuleAttractorParticle

## Hierarchy

- [`ParticleModuleAttractorBase`](ue_ue.ParticleModuleAttractorBase.md)

  ↳ **`ParticleModuleAttractorParticle`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleAttractorParticle.md#constructor)

### Properties

- [EmitterName](ue_ue.ParticleModuleAttractorParticle.md#emittername)
- [LODDuplicate](ue_ue.ParticleModuleAttractorParticle.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleAttractorParticle.md#lodvalidity)
- [LastSelIndex](ue_ue.ParticleModuleAttractorParticle.md#lastselindex)
- [ModuleEditorColor](ue_ue.ParticleModuleAttractorParticle.md#moduleeditorcolor)
- [Range](ue_ue.ParticleModuleAttractorParticle.md#range)
- [SelectionMethod](ue_ue.ParticleModuleAttractorParticle.md#selectionmethod)
- [Strength](ue_ue.ParticleModuleAttractorParticle.md#strength)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleAttractorParticle.md#__tid_object__)
- [\_\_tid\_ParticleModuleAttractorBase\_\_](ue_ue.ParticleModuleAttractorParticle.md#__tid_particlemoduleattractorbase__)
- [\_\_tid\_ParticleModuleAttractorParticle\_\_](ue_ue.ParticleModuleAttractorParticle.md#__tid_particlemoduleattractorparticle__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleAttractorParticle.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleAttractorParticle.md#b3ddrawmode)
- [bAffectBaseVelocity](ue_ue.ParticleModuleAttractorParticle.md#baffectbasevelocity)
- [bCurvesAsColor](ue_ue.ParticleModuleAttractorParticle.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleAttractorParticle.md#beditable)
- [bEnabled](ue_ue.ParticleModuleAttractorParticle.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleAttractorParticle.md#bfinalupdatemodule)
- [bInheritSourceVel](ue_ue.ParticleModuleAttractorParticle.md#binheritsourcevel)
- [bRenewSource](ue_ue.ParticleModuleAttractorParticle.md#brenewsource)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleAttractorParticle.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleAttractorParticle.md#bspawnmodule)
- [bStrengthByDistance](ue_ue.ParticleModuleAttractorParticle.md#bstrengthbydistance)
- [bSupported3DDrawMode](ue_ue.ParticleModuleAttractorParticle.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleAttractorParticle.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleAttractorParticle.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleAttractorParticle.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleAttractorParticle.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleAttractorParticle.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleAttractorParticle.md#getclass)
- [GetName](ue_ue.ParticleModuleAttractorParticle.md#getname)
- [GetOuter](ue_ue.ParticleModuleAttractorParticle.md#getouter)
- [GetWorld](ue_ue.ParticleModuleAttractorParticle.md#getworld)
- [Find](ue_ue.ParticleModuleAttractorParticle.md#find)
- [Load](ue_ue.ParticleModuleAttractorParticle.md#load)
- [StaticClass](ue_ue.ParticleModuleAttractorParticle.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleAttractorParticle**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[constructor](ue_ue.ParticleModuleAttractorBase.md#constructor)

## Properties

### EmitterName

• **EmitterName**: `string`

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[LODDuplicate](ue_ue.ParticleModuleAttractorBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[LODValidity](ue_ue.ParticleModuleAttractorBase.md#lodvalidity)

___

### LastSelIndex

• **LastSelIndex**: `number`

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[ModuleEditorColor](ue_ue.ParticleModuleAttractorBase.md#moduleeditorcolor)

___

### Range

• **Range**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### SelectionMethod

• **SelectionMethod**: [`EAttractorParticleSelectionMethod`](../enums/ue_ue.EAttractorParticleSelectionMethod.md)

___

### Strength

• **Strength**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[__tid_Object__](ue_ue.ParticleModuleAttractorBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleAttractorBase\_\_

• **\_\_tid\_ParticleModuleAttractorBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[__tid_ParticleModuleAttractorBase__](ue_ue.ParticleModuleAttractorBase.md#__tid_particlemoduleattractorbase__)

___

### \_\_tid\_ParticleModuleAttractorParticle\_\_

• **\_\_tid\_ParticleModuleAttractorParticle\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleAttractorBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[b3DDrawMode](ue_ue.ParticleModuleAttractorBase.md#b3ddrawmode)

___

### bAffectBaseVelocity

• **bAffectBaseVelocity**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bCurvesAsColor](ue_ue.ParticleModuleAttractorBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bEditable](ue_ue.ParticleModuleAttractorBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bEnabled](ue_ue.ParticleModuleAttractorBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleAttractorBase.md#bfinalupdatemodule)

___

### bInheritSourceVel

• **bInheritSourceVel**: `boolean`

___

### bRenewSource

• **bRenewSource**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleAttractorBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bSpawnModule](ue_ue.ParticleModuleAttractorBase.md#bspawnmodule)

___

### bStrengthByDistance

• **bStrengthByDistance**: `boolean`

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleAttractorBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleAttractorBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleAttractorBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[bUpdateModule](ue_ue.ParticleModuleAttractorBase.md#bupdatemodule)

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

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleAttractorBase.md#createdefaultsubobject)

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

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleAttractorBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[GetClass](ue_ue.ParticleModuleAttractorBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[GetName](ue_ue.ParticleModuleAttractorBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[GetOuter](ue_ue.ParticleModuleAttractorBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[GetWorld](ue_ue.ParticleModuleAttractorBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleAttractorParticle`](ue_ue.ParticleModuleAttractorParticle.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleAttractorParticle`](ue_ue.ParticleModuleAttractorParticle.md)

#### Overrides

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[Find](ue_ue.ParticleModuleAttractorBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleAttractorParticle`](ue_ue.ParticleModuleAttractorParticle.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleAttractorParticle`](ue_ue.ParticleModuleAttractorParticle.md)

#### Overrides

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[Load](ue_ue.ParticleModuleAttractorBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleAttractorBase](ue_ue.ParticleModuleAttractorBase.md).[StaticClass](ue_ue.ParticleModuleAttractorBase.md#staticclass)
