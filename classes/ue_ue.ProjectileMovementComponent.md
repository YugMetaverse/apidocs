[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ProjectileMovementComponent

# Class: ProjectileMovementComponent

[ue/ue](../modules/ue_ue.md).ProjectileMovementComponent

## Hierarchy

- [`MovementComponent`](ue_ue.MovementComponent.md)

  ↳ **`ProjectileMovementComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.ProjectileMovementComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.ProjectileMovementComponent.md#assetuserdata)
- [BounceAdditionalIterations](ue_ue.ProjectileMovementComponent.md#bounceadditionaliterations)
- [BounceVelocityStopSimulatingThreshold](ue_ue.ProjectileMovementComponent.md#bouncevelocitystopsimulatingthreshold)
- [Bounciness](ue_ue.ProjectileMovementComponent.md#bounciness)
- [Buoyancy](ue_ue.ProjectileMovementComponent.md#buoyancy)
- [ComponentTags](ue_ue.ProjectileMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.ProjectileMovementComponent.md#creationmethod)
- [Friction](ue_ue.ProjectileMovementComponent.md#friction)
- [HomingAccelerationMagnitude](ue_ue.ProjectileMovementComponent.md#homingaccelerationmagnitude)
- [HomingTargetComponent](ue_ue.ProjectileMovementComponent.md#homingtargetcomponent)
- [InitialSpeed](ue_ue.ProjectileMovementComponent.md#initialspeed)
- [InterpLocationMaxLagDistance](ue_ue.ProjectileMovementComponent.md#interplocationmaxlagdistance)
- [InterpLocationSnapToTargetDistance](ue_ue.ProjectileMovementComponent.md#interplocationsnaptotargetdistance)
- [InterpLocationTime](ue_ue.ProjectileMovementComponent.md#interplocationtime)
- [InterpRotationTime](ue_ue.ProjectileMovementComponent.md#interprotationtime)
- [MaxSimulationIterations](ue_ue.ProjectileMovementComponent.md#maxsimulationiterations)
- [MaxSimulationTimeStep](ue_ue.ProjectileMovementComponent.md#maxsimulationtimestep)
- [MaxSpeed](ue_ue.ProjectileMovementComponent.md#maxspeed)
- [MinFrictionFraction](ue_ue.ProjectileMovementComponent.md#minfrictionfraction)
- [OnComponentActivated](ue_ue.ProjectileMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.ProjectileMovementComponent.md#oncomponentdeactivated)
- [OnProjectileBounce](ue_ue.ProjectileMovementComponent.md#onprojectilebounce)
- [OnProjectileStop](ue_ue.ProjectileMovementComponent.md#onprojectilestop)
- [PlaneConstraintAxisSetting](ue_ue.ProjectileMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.ProjectileMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.ProjectileMovementComponent.md#planeconstraintorigin)
- [PreviousHitNormal](ue_ue.ProjectileMovementComponent.md#previoushitnormal)
- [PreviousHitTime](ue_ue.ProjectileMovementComponent.md#previoushittime)
- [PrimaryComponentTick](ue_ue.ProjectileMovementComponent.md#primarycomponenttick)
- [ProjectileGravityScale](ue_ue.ProjectileMovementComponent.md#projectilegravityscale)
- [UCSModifiedProperties](ue_ue.ProjectileMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.ProjectileMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.ProjectileMovementComponent.md#updatedprimitive)
- [Velocity](ue_ue.ProjectileMovementComponent.md#velocity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ProjectileMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.ProjectileMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.ProjectileMovementComponent.md#__tid_object__)
- [\_\_tid\_ProjectileMovementComponent\_\_](ue_ue.ProjectileMovementComponent.md#__tid_projectilemovementcomponent__)
- [bAutoActivate](ue_ue.ProjectileMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.ProjectileMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.ProjectileMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.ProjectileMovementComponent.md#bautoupdatetickregistration)
- [bBounceAngleAffectsFriction](ue_ue.ProjectileMovementComponent.md#bbounceangleaffectsfriction)
- [bCanEverAffectNavigation](ue_ue.ProjectileMovementComponent.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.ProjectileMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.ProjectileMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.ProjectileMovementComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.ProjectileMovementComponent.md#beditablewheninherited)
- [bForceSubStepping](ue_ue.ProjectileMovementComponent.md#bforcesubstepping)
- [bInitialVelocityInLocalSpace](ue_ue.ProjectileMovementComponent.md#binitialvelocityinlocalspace)
- [bInstanceComponent](ue_ue.ProjectileMovementComponent.md#binstancecomponent)
- [bInterpMovement](ue_ue.ProjectileMovementComponent.md#binterpmovement)
- [bInterpRotation](ue_ue.ProjectileMovementComponent.md#binterprotation)
- [bIsActive](ue_ue.ProjectileMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.ProjectileMovementComponent.md#biseditoronly)
- [bIsHomingProjectile](ue_ue.ProjectileMovementComponent.md#bishomingprojectile)
- [bIsSliding](ue_ue.ProjectileMovementComponent.md#bissliding)
- [bIsVisualizationComponent](ue_ue.ProjectileMovementComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.ProjectileMovementComponent.md#bnetaddressable)
- [bReplicates](ue_ue.ProjectileMovementComponent.md#breplicates)
- [bRotationFollowsVelocity](ue_ue.ProjectileMovementComponent.md#brotationfollowsvelocity)
- [bRotationRemainsVertical](ue_ue.ProjectileMovementComponent.md#brotationremainsvertical)
- [bShouldBounce](ue_ue.ProjectileMovementComponent.md#bshouldbounce)
- [bSimulationEnabled](ue_ue.ProjectileMovementComponent.md#bsimulationenabled)
- [bSnapToPlaneAtStart](ue_ue.ProjectileMovementComponent.md#bsnaptoplaneatstart)
- [bSweepCollision](ue_ue.ProjectileMovementComponent.md#bsweepcollision)
- [bTickBeforeOwner](ue_ue.ProjectileMovementComponent.md#btickbeforeowner)
- [bUpdateOnlyIfRendered](ue_ue.ProjectileMovementComponent.md#bupdateonlyifrendered)

### Methods

- [Activate](ue_ue.ProjectileMovementComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.ProjectileMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ProjectileMovementComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.ProjectileMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.ProjectileMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.ProjectileMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.ProjectileMovementComponent.md#constrainnormaltoplane)
- [CreateDefaultSubobject](ue_ue.ProjectileMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.ProjectileMovementComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.ProjectileMovementComponent.md#executeubergraph)
- [GetClass](ue_ue.ProjectileMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.ProjectileMovementComponent.md#getcomponenttickinterval)
- [GetGravityZ](ue_ue.ProjectileMovementComponent.md#getgravityz)
- [GetMaxSpeed](ue_ue.ProjectileMovementComponent.md#getmaxspeed)
- [GetName](ue_ue.ProjectileMovementComponent.md#getname)
- [GetOuter](ue_ue.ProjectileMovementComponent.md#getouter)
- [GetOwner](ue_ue.ProjectileMovementComponent.md#getowner)
- [GetPhysicsVolume](ue_ue.ProjectileMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.ProjectileMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.ProjectileMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.ProjectileMovementComponent.md#getplaneconstraintorigin)
- [GetWorld](ue_ue.ProjectileMovementComponent.md#getworld)
- [IsActive](ue_ue.ProjectileMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.ProjectileMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ProjectileMovementComponent.md#iscomponenttickenabled)
- [IsExceedingMaxSpeed](ue_ue.ProjectileMovementComponent.md#isexceedingmaxspeed)
- [IsInterpolationComplete](ue_ue.ProjectileMovementComponent.md#isinterpolationcomplete)
- [IsVelocityUnderSimulationThreshold](ue_ue.ProjectileMovementComponent.md#isvelocityundersimulationthreshold)
- [K2\_DestroyComponent](ue_ue.ProjectileMovementComponent.md#k2_destroycomponent)
- [K2\_GetMaxSpeedModifier](ue_ue.ProjectileMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.ProjectileMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.ProjectileMovementComponent.md#k2_moveupdatedcomponent)
- [LimitVelocity](ue_ue.ProjectileMovementComponent.md#limitvelocity)
- [MoveInterpolationTarget](ue_ue.ProjectileMovementComponent.md#moveinterpolationtarget)
- [OnProjectileBounceDelegate\_\_DelegateSignature](ue_ue.ProjectileMovementComponent.md#onprojectilebouncedelegate__delegatesignature)
- [OnProjectileStopDelegate\_\_DelegateSignature](ue_ue.ProjectileMovementComponent.md#onprojectilestopdelegate__delegatesignature)
- [OnRep\_IsActive](ue_ue.ProjectileMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.ProjectileMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.ProjectileMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ProjectileMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.ProjectileMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.ProjectileMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ProjectileMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ProjectileMovementComponent.md#removetickprerequisitecomponent)
- [ResetInterpolation](ue_ue.ProjectileMovementComponent.md#resetinterpolation)
- [SetActive](ue_ue.ProjectileMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.ProjectileMovementComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.ProjectileMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ProjectileMovementComponent.md#setcomponenttickinterval)
- [SetInterpolatedComponent](ue_ue.ProjectileMovementComponent.md#setinterpolatedcomponent)
- [SetIsReplicated](ue_ue.ProjectileMovementComponent.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.ProjectileMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.ProjectileMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.ProjectileMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.ProjectileMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.ProjectileMovementComponent.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.ProjectileMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ProjectileMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.ProjectileMovementComponent.md#setupdatedcomponent)
- [SetVelocityInLocalSpace](ue_ue.ProjectileMovementComponent.md#setvelocityinlocalspace)
- [SnapUpdatedComponentToPlane](ue_ue.ProjectileMovementComponent.md#snapupdatedcomponenttoplane)
- [StopMovementImmediately](ue_ue.ProjectileMovementComponent.md#stopmovementimmediately)
- [StopSimulating](ue_ue.ProjectileMovementComponent.md#stopsimulating)
- [ToggleActive](ue_ue.ProjectileMovementComponent.md#toggleactive)
- [Find](ue_ue.ProjectileMovementComponent.md#find)
- [Load](ue_ue.ProjectileMovementComponent.md#load)
- [StaticClass](ue_ue.ProjectileMovementComponent.md#staticclass)

## Constructors

### constructor

• **new ProjectileMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[constructor](ue_ue.MovementComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[AssetUserData](ue_ue.MovementComponent.md#assetuserdata)

___

### BounceAdditionalIterations

• **BounceAdditionalIterations**: `number`

___

### BounceVelocityStopSimulatingThreshold

• **BounceVelocityStopSimulatingThreshold**: `number`

___

### Bounciness

• **Bounciness**: `number`

___

### Buoyancy

• **Buoyancy**: `number`

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ComponentTags](ue_ue.MovementComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[CreationMethod](ue_ue.MovementComponent.md#creationmethod)

___

### Friction

• **Friction**: `number`

___

### HomingAccelerationMagnitude

• **HomingAccelerationMagnitude**: `number`

___

### HomingTargetComponent

• **HomingTargetComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

___

### InitialSpeed

• **InitialSpeed**: `number`

___

### InterpLocationMaxLagDistance

• **InterpLocationMaxLagDistance**: `number`

___

### InterpLocationSnapToTargetDistance

• **InterpLocationSnapToTargetDistance**: `number`

___

### InterpLocationTime

• **InterpLocationTime**: `number`

___

### InterpRotationTime

• **InterpRotationTime**: `number`

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

___

### MaxSpeed

• **MaxSpeed**: `number`

___

### MinFrictionFraction

• **MinFrictionFraction**: `number`

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[OnComponentActivated](ue_ue.MovementComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[OnComponentDeactivated](ue_ue.MovementComponent.md#oncomponentdeactivated)

___

### OnProjectileBounce

• **OnProjectileBounce**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `ImpactVelocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

___

### OnProjectileStop

• **OnProjectileStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.MovementComponent.md#planeconstraintaxissetting)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PlaneConstraintNormal](ue_ue.MovementComponent.md#planeconstraintnormal)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PlaneConstraintOrigin](ue_ue.MovementComponent.md#planeconstraintorigin)

___

### PreviousHitNormal

• **PreviousHitNormal**: [`Vector`](ue_ue_s.Vector.md)

___

### PreviousHitTime

• **PreviousHitTime**: `number`

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PrimaryComponentTick](ue_ue.MovementComponent.md#primarycomponenttick)

___

### ProjectileGravityScale

• **ProjectileGravityScale**: `number`

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[UCSModifiedProperties](ue_ue.MovementComponent.md#ucsmodifiedproperties)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[UpdatedComponent](ue_ue.MovementComponent.md#updatedcomponent)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[UpdatedPrimitive](ue_ue.MovementComponent.md#updatedprimitive)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[Velocity](ue_ue.MovementComponent.md#velocity)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[__tid_ActorComponent__](ue_ue.MovementComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[__tid_MovementComponent__](ue_ue.MovementComponent.md#__tid_movementcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[__tid_Object__](ue_ue.MovementComponent.md#__tid_object__)

___

### \_\_tid\_ProjectileMovementComponent\_\_

• **\_\_tid\_ProjectileMovementComponent\_\_**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoActivate](ue_ue.MovementComponent.md#bautoactivate)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.MovementComponent.md#bautoregisterphysicsvolumeupdates)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.MovementComponent.md#bautoregisterupdatedcomponent)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.MovementComponent.md#bautoupdatetickregistration)

___

### bBounceAngleAffectsFriction

• **bBounceAngleAffectsFriction**: `boolean`

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bCanEverAffectNavigation](ue_ue.MovementComponent.md#bcaneveraffectnavigation)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.MovementComponent.md#bcomponentshouldupdatephysicsvolume)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bConstrainToPlane](ue_ue.MovementComponent.md#bconstraintoplane)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bCreatedByConstructionScript](ue_ue.MovementComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bEditableWhenInherited](ue_ue.MovementComponent.md#beditablewheninherited)

___

### bForceSubStepping

• **bForceSubStepping**: `boolean`

___

### bInitialVelocityInLocalSpace

• **bInitialVelocityInLocalSpace**: `boolean`

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bInstanceComponent](ue_ue.MovementComponent.md#binstancecomponent)

___

### bInterpMovement

• **bInterpMovement**: `boolean`

___

### bInterpRotation

• **bInterpRotation**: `boolean`

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bIsActive](ue_ue.MovementComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bIsEditorOnly](ue_ue.MovementComponent.md#biseditoronly)

___

### bIsHomingProjectile

• **bIsHomingProjectile**: `boolean`

___

### bIsSliding

• **bIsSliding**: `boolean`

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bIsVisualizationComponent](ue_ue.MovementComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bNetAddressable](ue_ue.MovementComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bReplicates](ue_ue.MovementComponent.md#breplicates)

___

### bRotationFollowsVelocity

• **bRotationFollowsVelocity**: `boolean`

___

### bRotationRemainsVertical

• **bRotationRemainsVertical**: `boolean`

___

### bShouldBounce

• **bShouldBounce**: `boolean`

___

### bSimulationEnabled

• **bSimulationEnabled**: `boolean`

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bSnapToPlaneAtStart](ue_ue.MovementComponent.md#bsnaptoplaneatstart)

___

### bSweepCollision

• **bSweepCollision**: `boolean`

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bTickBeforeOwner](ue_ue.MovementComponent.md#btickbeforeowner)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.MovementComponent.md#bupdateonlyifrendered)

## Methods

### Activate

▸ **Activate**(`bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[Activate](ue_ue.MovementComponent.md#activate)

___

### AddTickPrerequisiteActor

▸ **AddTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[AddTickPrerequisiteActor](ue_ue.MovementComponent.md#addtickprerequisiteactor)

___

### AddTickPrerequisiteComponent

▸ **AddTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.MovementComponent.md#addtickprerequisitecomponent)

___

### ComponentHasTag

▸ **ComponentHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ComponentHasTag](ue_ue.MovementComponent.md#componenthastag)

___

### ConstrainDirectionToPlane

▸ **ConstrainDirectionToPlane**(`Direction`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ConstrainDirectionToPlane](ue_ue.MovementComponent.md#constraindirectiontoplane)

___

### ConstrainLocationToPlane

▸ **ConstrainLocationToPlane**(`Location`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ConstrainLocationToPlane](ue_ue.MovementComponent.md#constrainlocationtoplane)

___

### ConstrainNormalToPlane

▸ **ConstrainNormalToPlane**(`Normal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ConstrainNormalToPlane](ue_ue.MovementComponent.md#constrainnormaltoplane)

___

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

[MovementComponent](ue_ue.MovementComponent.md).[CreateDefaultSubobject](ue_ue.MovementComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[Deactivate](ue_ue.MovementComponent.md#deactivate)

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

[MovementComponent](ue_ue.MovementComponent.md).[ExecuteUbergraph](ue_ue.MovementComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetClass](ue_ue.MovementComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetComponentTickInterval](ue_ue.MovementComponent.md#getcomponenttickinterval)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetGravityZ](ue_ue.MovementComponent.md#getgravityz)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetMaxSpeed](ue_ue.MovementComponent.md#getmaxspeed)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetName](ue_ue.MovementComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetOuter](ue_ue.MovementComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetOwner](ue_ue.MovementComponent.md#getowner)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPhysicsVolume](ue_ue.MovementComponent.md#getphysicsvolume)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.MovementComponent.md#getplaneconstraintaxissetting)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPlaneConstraintNormal](ue_ue.MovementComponent.md#getplaneconstraintnormal)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.MovementComponent.md#getplaneconstraintorigin)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetWorld](ue_ue.MovementComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsActive](ue_ue.MovementComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsBeingDestroyed](ue_ue.MovementComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsComponentTickEnabled](ue_ue.MovementComponent.md#iscomponenttickenabled)

___

### IsExceedingMaxSpeed

▸ **IsExceedingMaxSpeed**(`MaxSpeed`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSpeed` | `number` |

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsExceedingMaxSpeed](ue_ue.MovementComponent.md#isexceedingmaxspeed)

___

### IsInterpolationComplete

▸ **IsInterpolationComplete**(): `boolean`

#### Returns

`boolean`

___

### IsVelocityUnderSimulationThreshold

▸ **IsVelocityUnderSimulationThreshold**(): `boolean`

#### Returns

`boolean`

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[K2_DestroyComponent](ue_ue.MovementComponent.md#k2_destroycomponent)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.MovementComponent.md#k2_getmaxspeedmodifier)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.MovementComponent.md#k2_getmodifiedmaxspeed)

___

### K2\_MoveUpdatedComponent

▸ **K2_MoveUpdatedComponent**(`Delta`, `NewRotation`, `OutHit`, `bSweep?`, `bTeleport?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Delta` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bSweep?` | `boolean` |
| `bTeleport?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[K2_MoveUpdatedComponent](ue_ue.MovementComponent.md#k2_moveupdatedcomponent)

___

### LimitVelocity

▸ **LimitVelocity**(`NewVelocity`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVelocity` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### MoveInterpolationTarget

▸ **MoveInterpolationTarget**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### OnProjectileBounceDelegate\_\_DelegateSignature

▸ **OnProjectileBounceDelegate__DelegateSignature**(`ImpactResult`, `ImpactVelocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |
| `ImpactVelocity` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### OnProjectileStopDelegate\_\_DelegateSignature

▸ **OnProjectileStopDelegate__DelegateSignature**(`ImpactResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[OnRep_IsActive](ue_ue.MovementComponent.md#onrep_isactive)

___

### PhysicsVolumeChanged

▸ **PhysicsVolumeChanged**(`NewVolume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVolume` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PhysicsVolumeChanged](ue_ue.MovementComponent.md#physicsvolumechanged)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ReceiveBeginPlay](ue_ue.MovementComponent.md#receivebeginplay)

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(`EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ReceiveEndPlay](ue_ue.MovementComponent.md#receiveendplay)

___

### ReceiveTick

▸ **ReceiveTick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ReceiveTick](ue_ue.MovementComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[RegisterComponent](ue_ue.MovementComponent.md#registercomponent)

___

### RemoveTickPrerequisiteActor

▸ **RemoveTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.MovementComponent.md#removetickprerequisiteactor)

___

### RemoveTickPrerequisiteComponent

▸ **RemoveTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.MovementComponent.md#removetickprerequisitecomponent)

___

### ResetInterpolation

▸ **ResetInterpolation**(): `void`

#### Returns

`void`

___

### SetActive

▸ **SetActive**(`bNewActive`, `bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewActive` | `boolean` |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetActive](ue_ue.MovementComponent.md#setactive)

___

### SetAutoActivate

▸ **SetAutoActivate**(`bNewAutoActivate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAutoActivate` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetAutoActivate](ue_ue.MovementComponent.md#setautoactivate)

___

### SetComponentTickEnabled

▸ **SetComponentTickEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetComponentTickEnabled](ue_ue.MovementComponent.md#setcomponenttickenabled)

___

### SetComponentTickInterval

▸ **SetComponentTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetComponentTickInterval](ue_ue.MovementComponent.md#setcomponenttickinterval)

___

### SetInterpolatedComponent

▸ **SetInterpolatedComponent**(`Component`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |

#### Returns

`void`

___

### SetIsReplicated

▸ **SetIsReplicated**(`ShouldReplicate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ShouldReplicate` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetIsReplicated](ue_ue.MovementComponent.md#setisreplicated)

___

### SetPlaneConstraintAxisSetting

▸ **SetPlaneConstraintAxisSetting**(`NewAxisSetting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAxisSetting` | [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md) |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetPlaneConstraintAxisSetting](ue_ue.MovementComponent.md#setplaneconstraintaxissetting)

___

### SetPlaneConstraintEnabled

▸ **SetPlaneConstraintEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetPlaneConstraintEnabled](ue_ue.MovementComponent.md#setplaneconstraintenabled)

___

### SetPlaneConstraintFromVectors

▸ **SetPlaneConstraintFromVectors**(`Forward`, `Up`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Forward` | [`Vector`](ue_ue_s.Vector.md) |
| `Up` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetPlaneConstraintFromVectors](ue_ue.MovementComponent.md#setplaneconstraintfromvectors)

___

### SetPlaneConstraintNormal

▸ **SetPlaneConstraintNormal**(`PlaneNormal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetPlaneConstraintNormal](ue_ue.MovementComponent.md#setplaneconstraintnormal)

___

### SetPlaneConstraintOrigin

▸ **SetPlaneConstraintOrigin**(`PlaneOrigin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlaneOrigin` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetPlaneConstraintOrigin](ue_ue.MovementComponent.md#setplaneconstraintorigin)

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetTickGroup](ue_ue.MovementComponent.md#settickgroup)

___

### SetTickableWhenPaused

▸ **SetTickableWhenPaused**(`bTickableWhenPaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTickableWhenPaused` | `boolean` |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetTickableWhenPaused](ue_ue.MovementComponent.md#settickablewhenpaused)

___

### SetUpdatedComponent

▸ **SetUpdatedComponent**(`NewUpdatedComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewUpdatedComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SetUpdatedComponent](ue_ue.MovementComponent.md#setupdatedcomponent)

___

### SetVelocityInLocalSpace

▸ **SetVelocityInLocalSpace**(`NewVelocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVelocity` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.MovementComponent.md#snapupdatedcomponenttoplane)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[StopMovementImmediately](ue_ue.MovementComponent.md#stopmovementimmediately)

___

### StopSimulating

▸ **StopSimulating**(`HitResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HitResult` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ToggleActive](ue_ue.MovementComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ProjectileMovementComponent`](ue_ue.ProjectileMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ProjectileMovementComponent`](ue_ue.ProjectileMovementComponent.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[Find](ue_ue.MovementComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ProjectileMovementComponent`](ue_ue.ProjectileMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ProjectileMovementComponent`](ue_ue.ProjectileMovementComponent.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[Load](ue_ue.MovementComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[StaticClass](ue_ue.MovementComponent.md#staticclass)
