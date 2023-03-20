[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BodyInstance

# Class: BodyInstance

[ue/ue](../modules/ue_ue.md).BodyInstance

## Table of contents

### Constructors

- [constructor](ue_ue.BodyInstance.md#constructor)

### Properties

- [AngularDamping](ue_ue.BodyInstance.md#angulardamping)
- [COMNudge](ue_ue.BodyInstance.md#comnudge)
- [CollisionEnabled](ue_ue.BodyInstance.md#collisionenabled)
- [CollisionProfileName](ue_ue.BodyInstance.md#collisionprofilename)
- [CollisionResponses](ue_ue.BodyInstance.md#collisionresponses)
- [CustomDOFPlaneNormal](ue_ue.BodyInstance.md#customdofplanenormal)
- [CustomSleepThresholdMultiplier](ue_ue.BodyInstance.md#customsleepthresholdmultiplier)
- [DOFMode](ue_ue.BodyInstance.md#dofmode)
- [InertiaTensorScale](ue_ue.BodyInstance.md#inertiatensorscale)
- [LinearDamping](ue_ue.BodyInstance.md#lineardamping)
- [MassInKgOverride](ue_ue.BodyInstance.md#massinkgoverride)
- [MassScale](ue_ue.BodyInstance.md#massscale)
- [MaxAngularVelocity](ue_ue.BodyInstance.md#maxangularvelocity)
- [MaxDepenetrationVelocity](ue_ue.BodyInstance.md#maxdepenetrationvelocity)
- [ObjectType](ue_ue.BodyInstance.md#objecttype)
- [PhysMaterialOverride](ue_ue.BodyInstance.md#physmaterialoverride)
- [PhysicsBlendWeight](ue_ue.BodyInstance.md#physicsblendweight)
- [PositionSolverIterationCount](ue_ue.BodyInstance.md#positionsolveriterationcount)
- [ResponseToChannels](ue_ue.BodyInstance.md#responsetochannels)
- [SleepFamily](ue_ue.BodyInstance.md#sleepfamily)
- [StabilizationThresholdMultiplier](ue_ue.BodyInstance.md#stabilizationthresholdmultiplier)
- [VelocitySolverIterationCount](ue_ue.BodyInstance.md#velocitysolveriterationcount)
- [WalkableSlopeOverride](ue_ue.BodyInstance.md#walkableslopeoverride)
- [\_\_tid\_BodyInstance\_\_](ue_ue.BodyInstance.md#__tid_bodyinstance__)
- [bAutoWeld](ue_ue.BodyInstance.md#bautoweld)
- [bEnableGravity](ue_ue.BodyInstance.md#benablegravity)
- [bGenerateWakeEvents](ue_ue.BodyInstance.md#bgeneratewakeevents)
- [bInterpolateWhenSubStepping](ue_ue.BodyInstance.md#binterpolatewhensubstepping)
- [bLockRotation](ue_ue.BodyInstance.md#blockrotation)
- [bLockTranslation](ue_ue.BodyInstance.md#blocktranslation)
- [bLockXRotation](ue_ue.BodyInstance.md#blockxrotation)
- [bLockXTranslation](ue_ue.BodyInstance.md#blockxtranslation)
- [bLockYRotation](ue_ue.BodyInstance.md#blockyrotation)
- [bLockYTranslation](ue_ue.BodyInstance.md#blockytranslation)
- [bLockZRotation](ue_ue.BodyInstance.md#blockzrotation)
- [bLockZTranslation](ue_ue.BodyInstance.md#blockztranslation)
- [bNotifyRigidBodyCollision](ue_ue.BodyInstance.md#bnotifyrigidbodycollision)
- [bOverrideMass](ue_ue.BodyInstance.md#boverridemass)
- [bOverrideMaxAngularVelocity](ue_ue.BodyInstance.md#boverridemaxangularvelocity)
- [bOverrideMaxDepenetrationVelocity](ue_ue.BodyInstance.md#boverridemaxdepenetrationvelocity)
- [bOverrideWalkableSlopeOnInstance](ue_ue.BodyInstance.md#boverridewalkableslopeoninstance)
- [bSimulatePhysics](ue_ue.BodyInstance.md#bsimulatephysics)
- [bStartAwake](ue_ue.BodyInstance.md#bstartawake)
- [bUpdateMassWhenScaleChanges](ue_ue.BodyInstance.md#bupdatemasswhenscalechanges)
- [bUseCCD](ue_ue.BodyInstance.md#buseccd)

### Methods

- [StaticClass](ue_ue.BodyInstance.md#staticclass)
- [StaticStruct](ue_ue.BodyInstance.md#staticstruct)

## Constructors

### constructor

• **new BodyInstance**()

• **new BodyInstance**(`ObjectType`, `CollisionEnabled`, `SleepFamily`, `DOFMode`, `bUseCCD`, `bNotifyRigidBodyCollision`, `bSimulatePhysics`, `bOverrideMass`, `bEnableGravity`, `bAutoWeld`, `bStartAwake`, `bGenerateWakeEvents`, `bUpdateMassWhenScaleChanges`, `bLockTranslation`, `bLockRotation`, `bLockXTranslation`, `bLockYTranslation`, `bLockZTranslation`, `bLockXRotation`, `bLockYRotation`, `bLockZRotation`, `bOverrideMaxAngularVelocity`, `bOverrideMaxDepenetrationVelocity`, `bOverrideWalkableSlopeOnInstance`, `bInterpolateWhenSubStepping`, `ResponseToChannels`, `CollisionProfileName`, `PositionSolverIterationCount`, `VelocitySolverIterationCount`, `CollisionResponses`, `MaxDepenetrationVelocity`, `MassInKgOverride`, `LinearDamping`, `AngularDamping`, `CustomDOFPlaneNormal`, `COMNudge`, `MassScale`, `InertiaTensorScale`, `WalkableSlopeOverride`, `PhysMaterialOverride`, `MaxAngularVelocity`, `CustomSleepThresholdMultiplier`, `StabilizationThresholdMultiplier`, `PhysicsBlendWeight`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectType` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `CollisionEnabled` | [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md) |
| `SleepFamily` | [`ESleepFamily`](../enums/ue_ue.ESleepFamily.md) |
| `DOFMode` | [`EDOFMode`](../enums/ue_ue.EDOFMode.md) |
| `bUseCCD` | `boolean` |
| `bNotifyRigidBodyCollision` | `boolean` |
| `bSimulatePhysics` | `boolean` |
| `bOverrideMass` | `boolean` |
| `bEnableGravity` | `boolean` |
| `bAutoWeld` | `boolean` |
| `bStartAwake` | `boolean` |
| `bGenerateWakeEvents` | `boolean` |
| `bUpdateMassWhenScaleChanges` | `boolean` |
| `bLockTranslation` | `boolean` |
| `bLockRotation` | `boolean` |
| `bLockXTranslation` | `boolean` |
| `bLockYTranslation` | `boolean` |
| `bLockZTranslation` | `boolean` |
| `bLockXRotation` | `boolean` |
| `bLockYRotation` | `boolean` |
| `bLockZRotation` | `boolean` |
| `bOverrideMaxAngularVelocity` | `boolean` |
| `bOverrideMaxDepenetrationVelocity` | `boolean` |
| `bOverrideWalkableSlopeOnInstance` | `boolean` |
| `bInterpolateWhenSubStepping` | `boolean` |
| `ResponseToChannels` | [`CollisionResponseContainer`](ue_ue.CollisionResponseContainer.md) |
| `CollisionProfileName` | `string` |
| `PositionSolverIterationCount` | `number` |
| `VelocitySolverIterationCount` | `number` |
| `CollisionResponses` | [`CollisionResponse`](ue_ue.CollisionResponse.md) |
| `MaxDepenetrationVelocity` | `number` |
| `MassInKgOverride` | `number` |
| `LinearDamping` | `number` |
| `AngularDamping` | `number` |
| `CustomDOFPlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `COMNudge` | [`Vector`](ue_ue_s.Vector.md) |
| `MassScale` | `number` |
| `InertiaTensorScale` | [`Vector`](ue_ue_s.Vector.md) |
| `WalkableSlopeOverride` | [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md) |
| `PhysMaterialOverride` | [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md) |
| `MaxAngularVelocity` | `number` |
| `CustomSleepThresholdMultiplier` | `number` |
| `StabilizationThresholdMultiplier` | `number` |
| `PhysicsBlendWeight` | `number` |

## Properties

### AngularDamping

• **AngularDamping**: `number`

___

### COMNudge

• **COMNudge**: [`Vector`](ue_ue_s.Vector.md)

___

### CollisionEnabled

• **CollisionEnabled**: [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

___

### CollisionProfileName

• **CollisionProfileName**: `string`

___

### CollisionResponses

• **CollisionResponses**: [`CollisionResponse`](ue_ue.CollisionResponse.md)

___

### CustomDOFPlaneNormal

• **CustomDOFPlaneNormal**: [`Vector`](ue_ue_s.Vector.md)

___

### CustomSleepThresholdMultiplier

• **CustomSleepThresholdMultiplier**: `number`

___

### DOFMode

• **DOFMode**: [`EDOFMode`](../enums/ue_ue.EDOFMode.md)

___

### InertiaTensorScale

• **InertiaTensorScale**: [`Vector`](ue_ue_s.Vector.md)

___

### LinearDamping

• **LinearDamping**: `number`

___

### MassInKgOverride

• **MassInKgOverride**: `number`

___

### MassScale

• **MassScale**: `number`

___

### MaxAngularVelocity

• **MaxAngularVelocity**: `number`

___

### MaxDepenetrationVelocity

• **MaxDepenetrationVelocity**: `number`

___

### ObjectType

• **ObjectType**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### PhysMaterialOverride

• **PhysMaterialOverride**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

___

### PhysicsBlendWeight

• **PhysicsBlendWeight**: `number`

___

### PositionSolverIterationCount

• **PositionSolverIterationCount**: `number`

___

### ResponseToChannels

• **ResponseToChannels**: [`CollisionResponseContainer`](ue_ue.CollisionResponseContainer.md)

___

### SleepFamily

• **SleepFamily**: [`ESleepFamily`](../enums/ue_ue.ESleepFamily.md)

___

### StabilizationThresholdMultiplier

• **StabilizationThresholdMultiplier**: `number`

___

### VelocitySolverIterationCount

• **VelocitySolverIterationCount**: `number`

___

### WalkableSlopeOverride

• **WalkableSlopeOverride**: [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

___

### \_\_tid\_BodyInstance\_\_

• `Private` **\_\_tid\_BodyInstance\_\_**: `boolean`

___

### bAutoWeld

• **bAutoWeld**: `boolean`

___

### bEnableGravity

• **bEnableGravity**: `boolean`

___

### bGenerateWakeEvents

• **bGenerateWakeEvents**: `boolean`

___

### bInterpolateWhenSubStepping

• **bInterpolateWhenSubStepping**: `boolean`

___

### bLockRotation

• **bLockRotation**: `boolean`

___

### bLockTranslation

• **bLockTranslation**: `boolean`

___

### bLockXRotation

• **bLockXRotation**: `boolean`

___

### bLockXTranslation

• **bLockXTranslation**: `boolean`

___

### bLockYRotation

• **bLockYRotation**: `boolean`

___

### bLockYTranslation

• **bLockYTranslation**: `boolean`

___

### bLockZRotation

• **bLockZRotation**: `boolean`

___

### bLockZTranslation

• **bLockZTranslation**: `boolean`

___

### bNotifyRigidBodyCollision

• **bNotifyRigidBodyCollision**: `boolean`

___

### bOverrideMass

• **bOverrideMass**: `boolean`

___

### bOverrideMaxAngularVelocity

• **bOverrideMaxAngularVelocity**: `boolean`

___

### bOverrideMaxDepenetrationVelocity

• **bOverrideMaxDepenetrationVelocity**: `boolean`

___

### bOverrideWalkableSlopeOnInstance

• **bOverrideWalkableSlopeOnInstance**: `boolean`

___

### bSimulatePhysics

• **bSimulatePhysics**: `boolean`

___

### bStartAwake

• **bStartAwake**: `boolean`

___

### bUpdateMassWhenScaleChanges

• **bUpdateMassWhenScaleChanges**: `boolean`

___

### bUseCCD

• **bUseCCD**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
