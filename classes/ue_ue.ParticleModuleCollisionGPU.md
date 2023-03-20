[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleCollisionGPU

# Class: ParticleModuleCollisionGPU

[ue/ue](../modules/ue_ue.md).ParticleModuleCollisionGPU

## Hierarchy

- [`ParticleModuleCollisionBase`](ue_ue.ParticleModuleCollisionBase.md)

  ↳ **`ParticleModuleCollisionGPU`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleCollisionGPU.md#constructor)

### Properties

- [CollisionMode](ue_ue.ParticleModuleCollisionGPU.md#collisionmode)
- [Friction](ue_ue.ParticleModuleCollisionGPU.md#friction)
- [LODDuplicate](ue_ue.ParticleModuleCollisionGPU.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleCollisionGPU.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleCollisionGPU.md#moduleeditorcolor)
- [RadiusBias](ue_ue.ParticleModuleCollisionGPU.md#radiusbias)
- [RadiusScale](ue_ue.ParticleModuleCollisionGPU.md#radiusscale)
- [RandomDistribution](ue_ue.ParticleModuleCollisionGPU.md#randomdistribution)
- [RandomSpread](ue_ue.ParticleModuleCollisionGPU.md#randomspread)
- [Resilience](ue_ue.ParticleModuleCollisionGPU.md#resilience)
- [ResilienceScaleOverLife](ue_ue.ParticleModuleCollisionGPU.md#resiliencescaleoverlife)
- [Response](ue_ue.ParticleModuleCollisionGPU.md#response)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleCollisionGPU.md#__tid_object__)
- [\_\_tid\_ParticleModuleCollisionBase\_\_](ue_ue.ParticleModuleCollisionGPU.md#__tid_particlemodulecollisionbase__)
- [\_\_tid\_ParticleModuleCollisionGPU\_\_](ue_ue.ParticleModuleCollisionGPU.md#__tid_particlemodulecollisiongpu__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleCollisionGPU.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleCollisionGPU.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleCollisionGPU.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleCollisionGPU.md#beditable)
- [bEnabled](ue_ue.ParticleModuleCollisionGPU.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleCollisionGPU.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleCollisionGPU.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleCollisionGPU.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleCollisionGPU.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleCollisionGPU.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleCollisionGPU.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleCollisionGPU.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleCollisionGPU.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleCollisionGPU.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleCollisionGPU.md#getclass)
- [GetName](ue_ue.ParticleModuleCollisionGPU.md#getname)
- [GetOuter](ue_ue.ParticleModuleCollisionGPU.md#getouter)
- [GetWorld](ue_ue.ParticleModuleCollisionGPU.md#getworld)
- [Find](ue_ue.ParticleModuleCollisionGPU.md#find)
- [Load](ue_ue.ParticleModuleCollisionGPU.md#load)
- [StaticClass](ue_ue.ParticleModuleCollisionGPU.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleCollisionGPU**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[constructor](ue_ue.ParticleModuleCollisionBase.md#constructor)

## Properties

### CollisionMode

• **CollisionMode**: [`EParticleCollisionMode`](../enums/ue_ue.EParticleCollisionMode.md)

___

### Friction

• **Friction**: `number`

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[LODDuplicate](ue_ue.ParticleModuleCollisionBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[LODValidity](ue_ue.ParticleModuleCollisionBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[ModuleEditorColor](ue_ue.ParticleModuleCollisionBase.md#moduleeditorcolor)

___

### RadiusBias

• **RadiusBias**: `number`

___

### RadiusScale

• **RadiusScale**: `number`

___

### RandomDistribution

• **RandomDistribution**: `number`

___

### RandomSpread

• **RandomSpread**: `number`

___

### Resilience

• **Resilience**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### ResilienceScaleOverLife

• **ResilienceScaleOverLife**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### Response

• **Response**: [`EParticleCollisionResponse`](../enums/ue_ue.EParticleCollisionResponse.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[__tid_Object__](ue_ue.ParticleModuleCollisionBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleCollisionBase\_\_

• **\_\_tid\_ParticleModuleCollisionBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[__tid_ParticleModuleCollisionBase__](ue_ue.ParticleModuleCollisionBase.md#__tid_particlemodulecollisionbase__)

___

### \_\_tid\_ParticleModuleCollisionGPU\_\_

• **\_\_tid\_ParticleModuleCollisionGPU\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleCollisionBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[b3DDrawMode](ue_ue.ParticleModuleCollisionBase.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bCurvesAsColor](ue_ue.ParticleModuleCollisionBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bEditable](ue_ue.ParticleModuleCollisionBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bEnabled](ue_ue.ParticleModuleCollisionBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleCollisionBase.md#bfinalupdatemodule)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleCollisionBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bSpawnModule](ue_ue.ParticleModuleCollisionBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleCollisionBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleCollisionBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleCollisionBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bUpdateModule](ue_ue.ParticleModuleCollisionBase.md#bupdatemodule)

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

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleCollisionBase.md#createdefaultsubobject)

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

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleCollisionBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetClass](ue_ue.ParticleModuleCollisionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetName](ue_ue.ParticleModuleCollisionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetOuter](ue_ue.ParticleModuleCollisionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetWorld](ue_ue.ParticleModuleCollisionBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleCollisionGPU`](ue_ue.ParticleModuleCollisionGPU.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleCollisionGPU`](ue_ue.ParticleModuleCollisionGPU.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[Find](ue_ue.ParticleModuleCollisionBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleCollisionGPU`](ue_ue.ParticleModuleCollisionGPU.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleCollisionGPU`](ue_ue.ParticleModuleCollisionGPU.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[Load](ue_ue.ParticleModuleCollisionBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[StaticClass](ue_ue.ParticleModuleCollisionBase.md#staticclass)
