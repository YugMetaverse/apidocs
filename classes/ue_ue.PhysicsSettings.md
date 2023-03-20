[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicsSettings

# Class: PhysicsSettings

[ue/ue](../modules/ue_ue.md).PhysicsSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`PhysicsSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicsSettings.md#constructor)

### Properties

- [AnimPhysicsMinDeltaTime](ue_ue.PhysicsSettings.md#animphysicsmindeltatime)
- [BounceThresholdVelocity](ue_ue.PhysicsSettings.md#bouncethresholdvelocity)
- [ChaosSettings](ue_ue.PhysicsSettings.md#chaossettings)
- [ContactOffsetMultiplier](ue_ue.PhysicsSettings.md#contactoffsetmultiplier)
- [DefaultBroadphaseSettings](ue_ue.PhysicsSettings.md#defaultbroadphasesettings)
- [DefaultDegreesOfFreedom](ue_ue.PhysicsSettings.md#defaultdegreesoffreedom)
- [DefaultFluidFriction](ue_ue.PhysicsSettings.md#defaultfluidfriction)
- [DefaultGravityZ](ue_ue.PhysicsSettings.md#defaultgravityz)
- [DefaultShapeComplexity](ue_ue.PhysicsSettings.md#defaultshapecomplexity)
- [DefaultTerminalVelocity](ue_ue.PhysicsSettings.md#defaultterminalvelocity)
- [FrictionCombineMode](ue_ue.PhysicsSettings.md#frictioncombinemode)
- [InitialAverageFrameRate](ue_ue.PhysicsSettings.md#initialaverageframerate)
- [LockedAxis](ue_ue.PhysicsSettings.md#lockedaxis)
- [MaxAngularVelocity](ue_ue.PhysicsSettings.md#maxangularvelocity)
- [MaxContactOffset](ue_ue.PhysicsSettings.md#maxcontactoffset)
- [MaxDepenetrationVelocity](ue_ue.PhysicsSettings.md#maxdepenetrationvelocity)
- [MaxPhysicsDeltaTime](ue_ue.PhysicsSettings.md#maxphysicsdeltatime)
- [MaxSubstepDeltaTime](ue_ue.PhysicsSettings.md#maxsubstepdeltatime)
- [MaxSubsteps](ue_ue.PhysicsSettings.md#maxsubsteps)
- [MinContactOffset](ue_ue.PhysicsSettings.md#mincontactoffset)
- [PhysXTreeRebuildRate](ue_ue.PhysicsSettings.md#physxtreerebuildrate)
- [PhysicErrorCorrection](ue_ue.PhysicsSettings.md#physicerrorcorrection)
- [PhysicalSurfaces](ue_ue.PhysicsSettings.md#physicalsurfaces)
- [RagdollAggregateThreshold](ue_ue.PhysicsSettings.md#ragdollaggregatethreshold)
- [RestitutionCombineMode](ue_ue.PhysicsSettings.md#restitutioncombinemode)
- [SimulateScratchMemorySize](ue_ue.PhysicsSettings.md#simulatescratchmemorysize)
- [SyncSceneSmoothingFactor](ue_ue.PhysicsSettings.md#syncscenesmoothingfactor)
- [TriangleMeshTriangleMinAreaThreshold](ue_ue.PhysicsSettings.md#trianglemeshtriangleminareathreshold)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.PhysicsSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.PhysicsSettings.md#__tid_object__)
- [\_\_tid\_PhysicsSettings\_\_](ue_ue.PhysicsSettings.md#__tid_physicssettings__)
- [bDefaultHasComplexCollision](ue_ue.PhysicsSettings.md#bdefaulthascomplexcollision)
- [bDisableActiveActors](ue_ue.PhysicsSettings.md#bdisableactiveactors)
- [bDisableCCD](ue_ue.PhysicsSettings.md#bdisableccd)
- [bDisableKinematicKinematicPairs](ue_ue.PhysicsSettings.md#bdisablekinematickinematicpairs)
- [bDisableKinematicStaticPairs](ue_ue.PhysicsSettings.md#bdisablekinematicstaticpairs)
- [bEnable2DPhysics](ue_ue.PhysicsSettings.md#benable2dphysics)
- [bEnableEnhancedDeterminism](ue_ue.PhysicsSettings.md#benableenhanceddeterminism)
- [bEnablePCM](ue_ue.PhysicsSettings.md#benablepcm)
- [bEnableShapeSharing](ue_ue.PhysicsSettings.md#benableshapesharing)
- [bEnableStabilization](ue_ue.PhysicsSettings.md#benablestabilization)
- [bSimulateAnimPhysicsAfterReset](ue_ue.PhysicsSettings.md#bsimulateanimphysicsafterreset)
- [bSimulateSkeletalMeshOnDedicatedServer](ue_ue.PhysicsSettings.md#bsimulateskeletalmeshondedicatedserver)
- [bSubstepping](ue_ue.PhysicsSettings.md#bsubstepping)
- [bSubsteppingAsync](ue_ue.PhysicsSettings.md#bsubsteppingasync)
- [bSupportUVFromHitResults](ue_ue.PhysicsSettings.md#bsupportuvfromhitresults)
- [bSuppressFaceRemapTable](ue_ue.PhysicsSettings.md#bsuppressfaceremaptable)
- [bWarnMissingLocks](ue_ue.PhysicsSettings.md#bwarnmissinglocks)

### Methods

- [CreateDefaultSubobject](ue_ue.PhysicsSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PhysicsSettings.md#executeubergraph)
- [GetClass](ue_ue.PhysicsSettings.md#getclass)
- [GetName](ue_ue.PhysicsSettings.md#getname)
- [GetOuter](ue_ue.PhysicsSettings.md#getouter)
- [GetWorld](ue_ue.PhysicsSettings.md#getworld)
- [Find](ue_ue.PhysicsSettings.md#find)
- [Load](ue_ue.PhysicsSettings.md#load)
- [StaticClass](ue_ue.PhysicsSettings.md#staticclass)

## Constructors

### constructor

• **new PhysicsSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### AnimPhysicsMinDeltaTime

• **AnimPhysicsMinDeltaTime**: `number`

___

### BounceThresholdVelocity

• **BounceThresholdVelocity**: `number`

___

### ChaosSettings

• **ChaosSettings**: [`ChaosPhysicsSettings`](ue_ue.ChaosPhysicsSettings.md)

___

### ContactOffsetMultiplier

• **ContactOffsetMultiplier**: `number`

___

### DefaultBroadphaseSettings

• **DefaultBroadphaseSettings**: [`BroadphaseSettings`](ue_ue.BroadphaseSettings.md)

___

### DefaultDegreesOfFreedom

• **DefaultDegreesOfFreedom**: [`ESettingsDOF`](../enums/ue_ue.ESettingsDOF.md)

___

### DefaultFluidFriction

• **DefaultFluidFriction**: `number`

___

### DefaultGravityZ

• **DefaultGravityZ**: `number`

___

### DefaultShapeComplexity

• **DefaultShapeComplexity**: [`ECollisionTraceFlag`](../enums/ue_ue.ECollisionTraceFlag.md)

___

### DefaultTerminalVelocity

• **DefaultTerminalVelocity**: `number`

___

### FrictionCombineMode

• **FrictionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

___

### InitialAverageFrameRate

• **InitialAverageFrameRate**: `number`

___

### LockedAxis

• **LockedAxis**: [`ESettingsLockedAxis`](../enums/ue_ue.ESettingsLockedAxis.md)

___

### MaxAngularVelocity

• **MaxAngularVelocity**: `number`

___

### MaxContactOffset

• **MaxContactOffset**: `number`

___

### MaxDepenetrationVelocity

• **MaxDepenetrationVelocity**: `number`

___

### MaxPhysicsDeltaTime

• **MaxPhysicsDeltaTime**: `number`

___

### MaxSubstepDeltaTime

• **MaxSubstepDeltaTime**: `number`

___

### MaxSubsteps

• **MaxSubsteps**: `number`

___

### MinContactOffset

• **MinContactOffset**: `number`

___

### PhysXTreeRebuildRate

• **PhysXTreeRebuildRate**: `number`

___

### PhysicErrorCorrection

• **PhysicErrorCorrection**: [`RigidBodyErrorCorrection`](ue_ue.RigidBodyErrorCorrection.md)

___

### PhysicalSurfaces

• **PhysicalSurfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicalSurfaceName`](ue_ue.PhysicalSurfaceName.md)\>

___

### RagdollAggregateThreshold

• **RagdollAggregateThreshold**: `number`

___

### RestitutionCombineMode

• **RestitutionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

___

### SimulateScratchMemorySize

• **SimulateScratchMemorySize**: `number`

___

### SyncSceneSmoothingFactor

• **SyncSceneSmoothingFactor**: `number`

___

### TriangleMeshTriangleMinAreaThreshold

• **TriangleMeshTriangleMinAreaThreshold**: `number`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### \_\_tid\_PhysicsSettings\_\_

• **\_\_tid\_PhysicsSettings\_\_**: `boolean`

___

### bDefaultHasComplexCollision

• **bDefaultHasComplexCollision**: `boolean`

___

### bDisableActiveActors

• **bDisableActiveActors**: `boolean`

___

### bDisableCCD

• **bDisableCCD**: `boolean`

___

### bDisableKinematicKinematicPairs

• **bDisableKinematicKinematicPairs**: `boolean`

___

### bDisableKinematicStaticPairs

• **bDisableKinematicStaticPairs**: `boolean`

___

### bEnable2DPhysics

• **bEnable2DPhysics**: `boolean`

___

### bEnableEnhancedDeterminism

• **bEnableEnhancedDeterminism**: `boolean`

___

### bEnablePCM

• **bEnablePCM**: `boolean`

___

### bEnableShapeSharing

• **bEnableShapeSharing**: `boolean`

___

### bEnableStabilization

• **bEnableStabilization**: `boolean`

___

### bSimulateAnimPhysicsAfterReset

• **bSimulateAnimPhysicsAfterReset**: `boolean`

___

### bSimulateSkeletalMeshOnDedicatedServer

• **bSimulateSkeletalMeshOnDedicatedServer**: `boolean`

___

### bSubstepping

• **bSubstepping**: `boolean`

___

### bSubsteppingAsync

• **bSubsteppingAsync**: `boolean`

___

### bSupportUVFromHitResults

• **bSupportUVFromHitResults**: `boolean`

___

### bSuppressFaceRemapTable

• **bSuppressFaceRemapTable**: `boolean`

___

### bWarnMissingLocks

• **bWarnMissingLocks**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicsSettings`](ue_ue.PhysicsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicsSettings`](ue_ue.PhysicsSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicsSettings`](ue_ue.PhysicsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicsSettings`](ue_ue.PhysicsSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
