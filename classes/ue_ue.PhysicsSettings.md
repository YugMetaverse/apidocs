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

#### Defined in

[ue/ue.d.ts:57605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57605)

## Properties

### AnimPhysicsMinDeltaTime

• **AnimPhysicsMinDeltaTime**: `number`

#### Defined in

[ue/ue.d.ts:57638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57638)

___

### BounceThresholdVelocity

• **BounceThresholdVelocity**: `number`

#### Defined in

[ue/ue.d.ts:57620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57620)

___

### ChaosSettings

• **ChaosSettings**: [`ChaosPhysicsSettings`](ue_ue.ChaosPhysicsSettings.md)

#### Defined in

[ue/ue.d.ts:57650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57650)

___

### ContactOffsetMultiplier

• **ContactOffsetMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:57625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57625)

___

### DefaultBroadphaseSettings

• **DefaultBroadphaseSettings**: [`BroadphaseSettings`](ue_ue.BroadphaseSettings.md)

#### Defined in

[ue/ue.d.ts:57649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57649)

___

### DefaultDegreesOfFreedom

• **DefaultDegreesOfFreedom**: [`ESettingsDOF`](../enums/ue_ue.ESettingsDOF.md)

#### Defined in

[ue/ue.d.ts:57619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57619)

___

### DefaultFluidFriction

• **DefaultFluidFriction**: `number`

#### Defined in

[ue/ue.d.ts:57608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57608)

___

### DefaultGravityZ

• **DefaultGravityZ**: `number`

#### Defined in

[ue/ue.d.ts:57606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57606)

___

### DefaultShapeComplexity

• **DefaultShapeComplexity**: [`ECollisionTraceFlag`](../enums/ue_ue.ECollisionTraceFlag.md)

#### Defined in

[ue/ue.d.ts:57629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57629)

___

### DefaultTerminalVelocity

• **DefaultTerminalVelocity**: `number`

#### Defined in

[ue/ue.d.ts:57607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57607)

___

### FrictionCombineMode

• **FrictionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

#### Defined in

[ue/ue.d.ts:57621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57621)

___

### InitialAverageFrameRate

• **InitialAverageFrameRate**: `number`

#### Defined in

[ue/ue.d.ts:57646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57646)

___

### LockedAxis

• **LockedAxis**: [`ESettingsLockedAxis`](../enums/ue_ue.ESettingsLockedAxis.md)

#### Defined in

[ue/ue.d.ts:57618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57618)

___

### MaxAngularVelocity

• **MaxAngularVelocity**: `number`

#### Defined in

[ue/ue.d.ts:57623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57623)

___

### MaxContactOffset

• **MaxContactOffset**: `number`

#### Defined in

[ue/ue.d.ts:57627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57627)

___

### MaxDepenetrationVelocity

• **MaxDepenetrationVelocity**: `number`

#### Defined in

[ue/ue.d.ts:57624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57624)

___

### MaxPhysicsDeltaTime

• **MaxPhysicsDeltaTime**: `number`

#### Defined in

[ue/ue.d.ts:57640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57640)

___

### MaxSubstepDeltaTime

• **MaxSubstepDeltaTime**: `number`

#### Defined in

[ue/ue.d.ts:57643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57643)

___

### MaxSubsteps

• **MaxSubsteps**: `number`

#### Defined in

[ue/ue.d.ts:57644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57644)

___

### MinContactOffset

• **MinContactOffset**: `number`

#### Defined in

[ue/ue.d.ts:57626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57626)

___

### PhysXTreeRebuildRate

• **PhysXTreeRebuildRate**: `number`

#### Defined in

[ue/ue.d.ts:57647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57647)

___

### PhysicErrorCorrection

• **PhysicErrorCorrection**: [`RigidBodyErrorCorrection`](ue_ue.RigidBodyErrorCorrection.md)

#### Defined in

[ue/ue.d.ts:57617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57617)

___

### PhysicalSurfaces

• **PhysicalSurfaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicalSurfaceName`](ue_ue.PhysicalSurfaceName.md)\>

#### Defined in

[ue/ue.d.ts:57648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57648)

___

### RagdollAggregateThreshold

• **RagdollAggregateThreshold**: `number`

#### Defined in

[ue/ue.d.ts:57610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57610)

___

### RestitutionCombineMode

• **RestitutionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

#### Defined in

[ue/ue.d.ts:57622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57622)

___

### SimulateScratchMemorySize

• **SimulateScratchMemorySize**: `number`

#### Defined in

[ue/ue.d.ts:57609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57609)

___

### SyncSceneSmoothingFactor

• **SyncSceneSmoothingFactor**: `number`

#### Defined in

[ue/ue.d.ts:57645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57645)

___

### TriangleMeshTriangleMinAreaThreshold

• **TriangleMeshTriangleMinAreaThreshold**: `number`

#### Defined in

[ue/ue.d.ts:57611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57611)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PhysicsSettings\_\_

• **\_\_tid\_PhysicsSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57655)

___

### bDefaultHasComplexCollision

• **bDefaultHasComplexCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:57630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57630)

___

### bDisableActiveActors

• **bDisableActiveActors**: `boolean`

#### Defined in

[ue/ue.d.ts:57633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57633)

___

### bDisableCCD

• **bDisableCCD**: `boolean`

#### Defined in

[ue/ue.d.ts:57636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57636)

___

### bDisableKinematicKinematicPairs

• **bDisableKinematicKinematicPairs**: `boolean`

#### Defined in

[ue/ue.d.ts:57635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57635)

___

### bDisableKinematicStaticPairs

• **bDisableKinematicStaticPairs**: `boolean`

#### Defined in

[ue/ue.d.ts:57634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57634)

___

### bEnable2DPhysics

• **bEnable2DPhysics**: `boolean`

#### Defined in

[ue/ue.d.ts:57616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57616)

___

### bEnableEnhancedDeterminism

• **bEnableEnhancedDeterminism**: `boolean`

#### Defined in

[ue/ue.d.ts:57637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57637)

___

### bEnablePCM

• **bEnablePCM**: `boolean`

#### Defined in

[ue/ue.d.ts:57613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57613)

___

### bEnableShapeSharing

• **bEnableShapeSharing**: `boolean`

#### Defined in

[ue/ue.d.ts:57612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57612)

___

### bEnableStabilization

• **bEnableStabilization**: `boolean`

#### Defined in

[ue/ue.d.ts:57614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57614)

___

### bSimulateAnimPhysicsAfterReset

• **bSimulateAnimPhysicsAfterReset**: `boolean`

#### Defined in

[ue/ue.d.ts:57639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57639)

___

### bSimulateSkeletalMeshOnDedicatedServer

• **bSimulateSkeletalMeshOnDedicatedServer**: `boolean`

#### Defined in

[ue/ue.d.ts:57628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57628)

___

### bSubstepping

• **bSubstepping**: `boolean`

#### Defined in

[ue/ue.d.ts:57641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57641)

___

### bSubsteppingAsync

• **bSubsteppingAsync**: `boolean`

#### Defined in

[ue/ue.d.ts:57642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57642)

___

### bSupportUVFromHitResults

• **bSupportUVFromHitResults**: `boolean`

#### Defined in

[ue/ue.d.ts:57632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57632)

___

### bSuppressFaceRemapTable

• **bSuppressFaceRemapTable**: `boolean`

#### Defined in

[ue/ue.d.ts:57631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57631)

___

### bWarnMissingLocks

• **bWarnMissingLocks**: `boolean`

#### Defined in

[ue/ue.d.ts:57615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57615)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:57652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57652)

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

#### Defined in

[ue/ue.d.ts:57653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57653)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:57651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57651)
