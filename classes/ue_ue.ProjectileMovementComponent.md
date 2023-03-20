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

#### Defined in

[ue/ue.d.ts:58592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58592)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[AssetUserData](ue_ue.MovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### BounceAdditionalIterations

• **BounceAdditionalIterations**: `number`

#### Defined in

[ue/ue.d.ts:58621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58621)

___

### BounceVelocityStopSimulatingThreshold

• **BounceVelocityStopSimulatingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:58613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58613)

___

### Bounciness

• **Bounciness**: `number`

#### Defined in

[ue/ue.d.ts:58611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58611)

___

### Buoyancy

• **Buoyancy**: `number`

#### Defined in

[ue/ue.d.ts:58610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58610)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ComponentTags](ue_ue.MovementComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[CreationMethod](ue_ue.MovementComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### Friction

• **Friction**: `number`

#### Defined in

[ue/ue.d.ts:58612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58612)

___

### HomingAccelerationMagnitude

• **HomingAccelerationMagnitude**: `number`

#### Defined in

[ue/ue.d.ts:58617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58617)

___

### HomingTargetComponent

• **HomingTargetComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Defined in

[ue/ue.d.ts:58618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58618)

___

### InitialSpeed

• **InitialSpeed**: `number`

#### Defined in

[ue/ue.d.ts:58593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58593)

___

### InterpLocationMaxLagDistance

• **InterpLocationMaxLagDistance**: `number`

#### Defined in

[ue/ue.d.ts:58624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58624)

___

### InterpLocationSnapToTargetDistance

• **InterpLocationSnapToTargetDistance**: `number`

#### Defined in

[ue/ue.d.ts:58625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58625)

___

### InterpLocationTime

• **InterpLocationTime**: `number`

#### Defined in

[ue/ue.d.ts:58622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58622)

___

### InterpRotationTime

• **InterpRotationTime**: `number`

#### Defined in

[ue/ue.d.ts:58623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58623)

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

#### Defined in

[ue/ue.d.ts:58620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58620)

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

#### Defined in

[ue/ue.d.ts:58619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58619)

___

### MaxSpeed

• **MaxSpeed**: `number`

#### Defined in

[ue/ue.d.ts:58594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58594)

___

### MinFrictionFraction

• **MinFrictionFraction**: `number`

#### Defined in

[ue/ue.d.ts:58614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58614)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[OnComponentActivated](ue_ue.MovementComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[OnComponentDeactivated](ue_ue.MovementComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### OnProjectileBounce

• **OnProjectileBounce**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `ImpactVelocity`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:58615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58615)

___

### OnProjectileStop

• **OnProjectileStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:58616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58616)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.MovementComponent.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PlaneConstraintNormal](ue_ue.MovementComponent.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PlaneConstraintOrigin](ue_ue.MovementComponent.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5394)

___

### PreviousHitNormal

• **PreviousHitNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:58608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58608)

___

### PreviousHitTime

• **PreviousHitTime**: `number`

#### Defined in

[ue/ue.d.ts:58607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58607)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PrimaryComponentTick](ue_ue.MovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### ProjectileGravityScale

• **ProjectileGravityScale**: `number`

#### Defined in

[ue/ue.d.ts:58609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58609)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[UCSModifiedProperties](ue_ue.MovementComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[UpdatedComponent](ue_ue.MovementComponent.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[UpdatedPrimitive](ue_ue.MovementComponent.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5391)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[Velocity](ue_ue.MovementComponent.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5392)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[__tid_ActorComponent__](ue_ue.MovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[__tid_MovementComponent__](ue_ue.MovementComponent.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5430)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[__tid_Object__](ue_ue.MovementComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ProjectileMovementComponent\_\_

• **\_\_tid\_ProjectileMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58640)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoActivate](ue_ue.MovementComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.MovementComponent.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.MovementComponent.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.MovementComponent.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5396)

___

### bBounceAngleAffectsFriction

• **bBounceAngleAffectsFriction**: `boolean`

#### Defined in

[ue/ue.d.ts:58603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58603)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bCanEverAffectNavigation](ue_ue.MovementComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.MovementComponent.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bConstrainToPlane](ue_ue.MovementComponent.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bCreatedByConstructionScript](ue_ue.MovementComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bEditableWhenInherited](ue_ue.MovementComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bForceSubStepping

• **bForceSubStepping**: `boolean`

#### Defined in

[ue/ue.d.ts:58599](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58599)

___

### bInitialVelocityInLocalSpace

• **bInitialVelocityInLocalSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:58598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58598)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bInstanceComponent](ue_ue.MovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bInterpMovement

• **bInterpMovement**: `boolean`

#### Defined in

[ue/ue.d.ts:58605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58605)

___

### bInterpRotation

• **bInterpRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:58606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58606)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bIsActive](ue_ue.MovementComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bIsEditorOnly](ue_ue.MovementComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsHomingProjectile

• **bIsHomingProjectile**: `boolean`

#### Defined in

[ue/ue.d.ts:58602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58602)

___

### bIsSliding

• **bIsSliding**: `boolean`

#### Defined in

[ue/ue.d.ts:58604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58604)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bIsVisualizationComponent](ue_ue.MovementComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bNetAddressable](ue_ue.MovementComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bReplicates](ue_ue.MovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bRotationFollowsVelocity

• **bRotationFollowsVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:58595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58595)

___

### bRotationRemainsVertical

• **bRotationRemainsVertical**: `boolean`

#### Defined in

[ue/ue.d.ts:58596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58596)

___

### bShouldBounce

• **bShouldBounce**: `boolean`

#### Defined in

[ue/ue.d.ts:58597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58597)

___

### bSimulationEnabled

• **bSimulationEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:58600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58600)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bSnapToPlaneAtStart](ue_ue.MovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5400)

___

### bSweepCollision

• **bSweepCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:58601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58601)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bTickBeforeOwner](ue_ue.MovementComponent.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5397)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.MovementComponent.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5395)

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

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L307)

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

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L308)

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

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

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

#### Defined in

[ue/ue.d.ts:5404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5404)

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

#### Defined in

[ue/ue.d.ts:5405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5405)

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

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5406)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[Deactivate](ue_ue.MovementComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L310)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetClass](ue_ue.MovementComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetComponentTickInterval](ue_ue.MovementComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetGravityZ](ue_ue.MovementComponent.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5407)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetMaxSpeed](ue_ue.MovementComponent.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5408)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetName](ue_ue.MovementComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetOuter](ue_ue.MovementComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetOwner](ue_ue.MovementComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPhysicsVolume](ue_ue.MovementComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.MovementComponent.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPlaneConstraintNormal](ue_ue.MovementComponent.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.MovementComponent.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5412)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[GetWorld](ue_ue.MovementComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsActive](ue_ue.MovementComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsBeingDestroyed](ue_ue.MovementComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[IsComponentTickEnabled](ue_ue.MovementComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

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

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5413)

___

### IsInterpolationComplete

▸ **IsInterpolationComplete**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:58626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58626)

___

### IsVelocityUnderSimulationThreshold

▸ **IsVelocityUnderSimulationThreshold**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:58627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58627)

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

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.MovementComponent.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.MovementComponent.md#k2_getmodifiedmaxspeed)

#### Defined in

[ue/ue.d.ts:5415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5415)

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

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5416)

___

### LimitVelocity

▸ **LimitVelocity**(`NewVelocity`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVelocity` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:58628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58628)

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

#### Defined in

[ue/ue.d.ts:58629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58629)

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

#### Defined in

[ue/ue.d.ts:58630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58630)

___

### OnProjectileStopDelegate\_\_DelegateSignature

▸ **OnProjectileStopDelegate__DelegateSignature**(`ImpactResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58631)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[OnRep_IsActive](ue_ue.MovementComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

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

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ReceiveBeginPlay](ue_ue.MovementComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L318)

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

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L319)

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

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[RegisterComponent](ue_ue.MovementComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

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

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L322)

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

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

___

### ResetInterpolation

▸ **ResetInterpolation**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58632)

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

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L324)

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

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

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

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L326)

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

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

___

### SetInterpolatedComponent

▸ **SetInterpolatedComponent**(`Component`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58633)

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

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

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

#### Defined in

[ue/ue.d.ts:5418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5418)

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

#### Defined in

[ue/ue.d.ts:5419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5419)

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

#### Defined in

[ue/ue.d.ts:5420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5420)

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

#### Defined in

[ue/ue.d.ts:5421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5421)

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

#### Defined in

[ue/ue.d.ts:5422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5422)

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

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L330)

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

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

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

#### Defined in

[ue/ue.d.ts:5423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5423)

___

### SetVelocityInLocalSpace

▸ **SetVelocityInLocalSpace**(`NewVelocity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVelocity` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58634)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.MovementComponent.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5424)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[StopMovementImmediately](ue_ue.MovementComponent.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5425)

___

### StopSimulating

▸ **StopSimulating**(`HitResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HitResult` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58635)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ToggleActive](ue_ue.MovementComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:58637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58637)

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

#### Defined in

[ue/ue.d.ts:58638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58638)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[StaticClass](ue_ue.MovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:58636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58636)
