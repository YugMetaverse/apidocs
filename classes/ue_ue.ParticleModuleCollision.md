[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleCollision

# Class: ParticleModuleCollision

[ue/ue](../modules/ue_ue.md).ParticleModuleCollision

## Hierarchy

- [`ParticleModuleCollisionBase`](ue_ue.ParticleModuleCollisionBase.md)

  ↳ **`ParticleModuleCollision`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleCollision.md#constructor)

### Properties

- [CollisionCompletionOption](ue_ue.ParticleModuleCollision.md#collisioncompletionoption)
- [CollisionTypes](ue_ue.ParticleModuleCollision.md#collisiontypes)
- [DampingFactor](ue_ue.ParticleModuleCollision.md#dampingfactor)
- [DampingFactorRotation](ue_ue.ParticleModuleCollision.md#dampingfactorrotation)
- [DelayAmount](ue_ue.ParticleModuleCollision.md#delayamount)
- [DirScalar](ue_ue.ParticleModuleCollision.md#dirscalar)
- [LODDuplicate](ue_ue.ParticleModuleCollision.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleCollision.md#lodvalidity)
- [MaxCollisionDistance](ue_ue.ParticleModuleCollision.md#maxcollisiondistance)
- [MaxCollisions](ue_ue.ParticleModuleCollision.md#maxcollisions)
- [ModuleEditorColor](ue_ue.ParticleModuleCollision.md#moduleeditorcolor)
- [ParticleMass](ue_ue.ParticleModuleCollision.md#particlemass)
- [VerticalFudgeFactor](ue_ue.ParticleModuleCollision.md#verticalfudgefactor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleCollision.md#__tid_object__)
- [\_\_tid\_ParticleModuleCollisionBase\_\_](ue_ue.ParticleModuleCollision.md#__tid_particlemodulecollisionbase__)
- [\_\_tid\_ParticleModuleCollision\_\_](ue_ue.ParticleModuleCollision.md#__tid_particlemodulecollision__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleCollision.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleCollision.md#b3ddrawmode)
- [bApplyPhysics](ue_ue.ParticleModuleCollision.md#bapplyphysics)
- [bCollideOnlyIfVisible](ue_ue.ParticleModuleCollision.md#bcollideonlyifvisible)
- [bCurvesAsColor](ue_ue.ParticleModuleCollision.md#bcurvesascolor)
- [bDropDetail](ue_ue.ParticleModuleCollision.md#bdropdetail)
- [bEditable](ue_ue.ParticleModuleCollision.md#beditable)
- [bEnabled](ue_ue.ParticleModuleCollision.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleCollision.md#bfinalupdatemodule)
- [bIgnoreSourceActor](ue_ue.ParticleModuleCollision.md#bignoresourceactor)
- [bIgnoreTriggerVolumes](ue_ue.ParticleModuleCollision.md#bignoretriggervolumes)
- [bOnlyVerticalNormalsDecrementCount](ue_ue.ParticleModuleCollision.md#bonlyverticalnormalsdecrementcount)
- [bPawnsDoNotDecrementCount](ue_ue.ParticleModuleCollision.md#bpawnsdonotdecrementcount)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleCollision.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleCollision.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleCollision.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleCollision.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleCollision.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleCollision.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleCollision.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleCollision.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleCollision.md#getclass)
- [GetName](ue_ue.ParticleModuleCollision.md#getname)
- [GetOuter](ue_ue.ParticleModuleCollision.md#getouter)
- [GetWorld](ue_ue.ParticleModuleCollision.md#getworld)
- [Find](ue_ue.ParticleModuleCollision.md#find)
- [Load](ue_ue.ParticleModuleCollision.md#load)
- [StaticClass](ue_ue.ParticleModuleCollision.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleCollision**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[constructor](ue_ue.ParticleModuleCollisionBase.md#constructor)

## Properties

### CollisionCompletionOption

• **CollisionCompletionOption**: [`EParticleCollisionComplete`](../enums/ue_ue.EParticleCollisionComplete.md)

___

### CollisionTypes

• **CollisionTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\>

___

### DampingFactor

• **DampingFactor**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### DampingFactorRotation

• **DampingFactorRotation**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### DelayAmount

• **DelayAmount**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### DirScalar

• **DirScalar**: `number`

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

### MaxCollisionDistance

• **MaxCollisionDistance**: `number`

___

### MaxCollisions

• **MaxCollisions**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[ModuleEditorColor](ue_ue.ParticleModuleCollisionBase.md#moduleeditorcolor)

___

### ParticleMass

• **ParticleMass**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### VerticalFudgeFactor

• **VerticalFudgeFactor**: `number`

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

### \_\_tid\_ParticleModuleCollision\_\_

• **\_\_tid\_ParticleModuleCollision\_\_**: `boolean`

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

### bApplyPhysics

• **bApplyPhysics**: `boolean`

___

### bCollideOnlyIfVisible

• **bCollideOnlyIfVisible**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bCurvesAsColor](ue_ue.ParticleModuleCollisionBase.md#bcurvesascolor)

___

### bDropDetail

• **bDropDetail**: `boolean`

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

### bIgnoreSourceActor

• **bIgnoreSourceActor**: `boolean`

___

### bIgnoreTriggerVolumes

• **bIgnoreTriggerVolumes**: `boolean`

___

### bOnlyVerticalNormalsDecrementCount

• **bOnlyVerticalNormalsDecrementCount**: `boolean`

___

### bPawnsDoNotDecrementCount

• **bPawnsDoNotDecrementCount**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleCollision`](ue_ue.ParticleModuleCollision.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleCollision`](ue_ue.ParticleModuleCollision.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[Find](ue_ue.ParticleModuleCollisionBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleCollision`](ue_ue.ParticleModuleCollision.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleCollision`](ue_ue.ParticleModuleCollision.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[Load](ue_ue.ParticleModuleCollisionBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[StaticClass](ue_ue.ParticleModuleCollisionBase.md#staticclass)
