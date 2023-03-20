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

#### Defined in

[ue/ue.d.ts:778](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L778)

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

#### Defined in

[ue/ue.d.ts:779](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L779)

## Properties

### AngularDamping

• **AngularDamping**: `number`

#### Defined in

[ue/ue.d.ts:813](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L813)

___

### COMNudge

• **COMNudge**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L815)

___

### CollisionEnabled

• **CollisionEnabled**: [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

#### Defined in

[ue/ue.d.ts:781](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L781)

___

### CollisionProfileName

• **CollisionProfileName**: `string`

#### Defined in

[ue/ue.d.ts:806](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L806)

___

### CollisionResponses

• **CollisionResponses**: [`CollisionResponse`](ue_ue.CollisionResponse.md)

#### Defined in

[ue/ue.d.ts:809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L809)

___

### CustomDOFPlaneNormal

• **CustomDOFPlaneNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:814](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L814)

___

### CustomSleepThresholdMultiplier

• **CustomSleepThresholdMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:821](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L821)

___

### DOFMode

• **DOFMode**: [`EDOFMode`](../enums/ue_ue.EDOFMode.md)

#### Defined in

[ue/ue.d.ts:783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L783)

___

### InertiaTensorScale

• **InertiaTensorScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L817)

___

### LinearDamping

• **LinearDamping**: `number`

#### Defined in

[ue/ue.d.ts:812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L812)

___

### MassInKgOverride

• **MassInKgOverride**: `number`

#### Defined in

[ue/ue.d.ts:811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L811)

___

### MassScale

• **MassScale**: `number`

#### Defined in

[ue/ue.d.ts:816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L816)

___

### MaxAngularVelocity

• **MaxAngularVelocity**: `number`

#### Defined in

[ue/ue.d.ts:820](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L820)

___

### MaxDepenetrationVelocity

• **MaxDepenetrationVelocity**: `number`

#### Defined in

[ue/ue.d.ts:810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L810)

___

### ObjectType

• **ObjectType**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:780](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L780)

___

### PhysMaterialOverride

• **PhysMaterialOverride**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:819](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L819)

___

### PhysicsBlendWeight

• **PhysicsBlendWeight**: `number`

#### Defined in

[ue/ue.d.ts:823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L823)

___

### PositionSolverIterationCount

• **PositionSolverIterationCount**: `number`

#### Defined in

[ue/ue.d.ts:807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L807)

___

### ResponseToChannels

• **ResponseToChannels**: [`CollisionResponseContainer`](ue_ue.CollisionResponseContainer.md)

#### Defined in

[ue/ue.d.ts:805](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L805)

___

### SleepFamily

• **SleepFamily**: [`ESleepFamily`](../enums/ue_ue.ESleepFamily.md)

#### Defined in

[ue/ue.d.ts:782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L782)

___

### StabilizationThresholdMultiplier

• **StabilizationThresholdMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L822)

___

### VelocitySolverIterationCount

• **VelocitySolverIterationCount**: `number`

#### Defined in

[ue/ue.d.ts:808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L808)

___

### WalkableSlopeOverride

• **WalkableSlopeOverride**: [`WalkableSlopeOverride`](ue_ue.WalkableSlopeOverride.md)

#### Defined in

[ue/ue.d.ts:818](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L818)

___

### \_\_tid\_BodyInstance\_\_

• `Private` **\_\_tid\_BodyInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:829](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L829)

___

### bAutoWeld

• **bAutoWeld**: `boolean`

#### Defined in

[ue/ue.d.ts:789](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L789)

___

### bEnableGravity

• **bEnableGravity**: `boolean`

#### Defined in

[ue/ue.d.ts:788](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L788)

___

### bGenerateWakeEvents

• **bGenerateWakeEvents**: `boolean`

#### Defined in

[ue/ue.d.ts:791](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L791)

___

### bInterpolateWhenSubStepping

• **bInterpolateWhenSubStepping**: `boolean`

#### Defined in

[ue/ue.d.ts:804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L804)

___

### bLockRotation

• **bLockRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L794)

___

### bLockTranslation

• **bLockTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L793)

___

### bLockXRotation

• **bLockXRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L798)

___

### bLockXTranslation

• **bLockXTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:795](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L795)

___

### bLockYRotation

• **bLockYRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L799)

___

### bLockYTranslation

• **bLockYTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L796)

___

### bLockZRotation

• **bLockZRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:800](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L800)

___

### bLockZTranslation

• **bLockZTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L797)

___

### bNotifyRigidBodyCollision

• **bNotifyRigidBodyCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:785](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L785)

___

### bOverrideMass

• **bOverrideMass**: `boolean`

#### Defined in

[ue/ue.d.ts:787](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L787)

___

### bOverrideMaxAngularVelocity

• **bOverrideMaxAngularVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:801](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L801)

___

### bOverrideMaxDepenetrationVelocity

• **bOverrideMaxDepenetrationVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L802)

___

### bOverrideWalkableSlopeOnInstance

• **bOverrideWalkableSlopeOnInstance**: `boolean`

#### Defined in

[ue/ue.d.ts:803](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L803)

___

### bSimulatePhysics

• **bSimulatePhysics**: `boolean`

#### Defined in

[ue/ue.d.ts:786](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L786)

___

### bStartAwake

• **bStartAwake**: `boolean`

#### Defined in

[ue/ue.d.ts:790](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L790)

___

### bUpdateMassWhenScaleChanges

• **bUpdateMassWhenScaleChanges**: `boolean`

#### Defined in

[ue/ue.d.ts:792](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L792)

___

### bUseCCD

• **bUseCCD**: `boolean`

#### Defined in

[ue/ue.d.ts:784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L784)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:827](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L827)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:828](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L828)
