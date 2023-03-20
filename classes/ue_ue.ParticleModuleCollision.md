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

#### Defined in

[ue/ue.d.ts:55515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55515)

## Properties

### CollisionCompletionOption

• **CollisionCompletionOption**: [`EParticleCollisionComplete`](../enums/ue_ue.EParticleCollisionComplete.md)

#### Defined in

[ue/ue.d.ts:55519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55519)

___

### CollisionTypes

• **CollisionTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\>

#### Defined in

[ue/ue.d.ts:55520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55520)

___

### DampingFactor

• **DampingFactor**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55516)

___

### DampingFactorRotation

• **DampingFactorRotation**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55517)

___

### DelayAmount

• **DelayAmount**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55528)

___

### DirScalar

• **DirScalar**: `number`

#### Defined in

[ue/ue.d.ts:55524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55524)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[LODDuplicate](ue_ue.ParticleModuleCollisionBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[LODValidity](ue_ue.ParticleModuleCollisionBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6748)

___

### MaxCollisionDistance

• **MaxCollisionDistance**: `number`

#### Defined in

[ue/ue.d.ts:55532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55532)

___

### MaxCollisions

• **MaxCollisions**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55518)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[ModuleEditorColor](ue_ue.ParticleModuleCollisionBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6749)

___

### ParticleMass

• **ParticleMass**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55523)

___

### VerticalFudgeFactor

• **VerticalFudgeFactor**: `number`

#### Defined in

[ue/ue.d.ts:55527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55527)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[__tid_Object__](ue_ue.ParticleModuleCollisionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleCollisionBase\_\_

• **\_\_tid\_ParticleModuleCollisionBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[__tid_ParticleModuleCollisionBase__](ue_ue.ParticleModuleCollisionBase.md#__tid_particlemodulecollisionbase__)

#### Defined in

[ue/ue.d.ts:55511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55511)

___

### \_\_tid\_ParticleModuleCollision\_\_

• **\_\_tid\_ParticleModuleCollision\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:55537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55537)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleCollisionBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[b3DDrawMode](ue_ue.ParticleModuleCollisionBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6741)

___

### bApplyPhysics

• **bApplyPhysics**: `boolean`

#### Defined in

[ue/ue.d.ts:55521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55521)

___

### bCollideOnlyIfVisible

• **bCollideOnlyIfVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:55530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55530)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bCurvesAsColor](ue_ue.ParticleModuleCollisionBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6740)

___

### bDropDetail

• **bDropDetail**: `boolean`

#### Defined in

[ue/ue.d.ts:55529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55529)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bEditable](ue_ue.ParticleModuleCollisionBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bEnabled](ue_ue.ParticleModuleCollisionBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleCollisionBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6738)

___

### bIgnoreSourceActor

• **bIgnoreSourceActor**: `boolean`

#### Defined in

[ue/ue.d.ts:55531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55531)

___

### bIgnoreTriggerVolumes

• **bIgnoreTriggerVolumes**: `boolean`

#### Defined in

[ue/ue.d.ts:55522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55522)

___

### bOnlyVerticalNormalsDecrementCount

• **bOnlyVerticalNormalsDecrementCount**: `boolean`

#### Defined in

[ue/ue.d.ts:55526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55526)

___

### bPawnsDoNotDecrementCount

• **bPawnsDoNotDecrementCount**: `boolean`

#### Defined in

[ue/ue.d.ts:55525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55525)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleCollisionBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bSpawnModule](ue_ue.ParticleModuleCollisionBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleCollisionBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleCollisionBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleCollisionBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[bUpdateModule](ue_ue.ParticleModuleCollisionBase.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6737)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetClass](ue_ue.ParticleModuleCollisionBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetName](ue_ue.ParticleModuleCollisionBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetOuter](ue_ue.ParticleModuleCollisionBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[GetWorld](ue_ue.ParticleModuleCollisionBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:55534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55534)

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

#### Defined in

[ue/ue.d.ts:55535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55535)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleCollisionBase](ue_ue.ParticleModuleCollisionBase.md).[StaticClass](ue_ue.ParticleModuleCollisionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:55533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55533)
