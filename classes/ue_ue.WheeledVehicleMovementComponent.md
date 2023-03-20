[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WheeledVehicleMovementComponent

# Class: WheeledVehicleMovementComponent

[ue/ue](../modules/ue_ue.md).WheeledVehicleMovementComponent

## Hierarchy

- [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

  ↳ **`WheeledVehicleMovementComponent`**

  ↳↳ [`SimpleWheeledVehicleMovementComponent`](ue_ue.SimpleWheeledVehicleMovementComponent.md)

  ↳↳ [`WheeledVehicleMovementComponent4W`](ue_ue.WheeledVehicleMovementComponent4W.md)

## Table of contents

### Constructors

- [constructor](ue_ue.WheeledVehicleMovementComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.WheeledVehicleMovementComponent.md#assetuserdata)
- [AvoidanceConsiderationRadius](ue_ue.WheeledVehicleMovementComponent.md#avoidanceconsiderationradius)
- [AvoidanceGroup](ue_ue.WheeledVehicleMovementComponent.md#avoidancegroup)
- [AvoidanceUID](ue_ue.WheeledVehicleMovementComponent.md#avoidanceuid)
- [AvoidanceWeight](ue_ue.WheeledVehicleMovementComponent.md#avoidanceweight)
- [BrakeInput](ue_ue.WheeledVehicleMovementComponent.md#brakeinput)
- [BrakeInputRate](ue_ue.WheeledVehicleMovementComponent.md#brakeinputrate)
- [ChassisHeight](ue_ue.WheeledVehicleMovementComponent.md#chassisheight)
- [ChassisWidth](ue_ue.WheeledVehicleMovementComponent.md#chassiswidth)
- [ComponentTags](ue_ue.WheeledVehicleMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.WheeledVehicleMovementComponent.md#creationmethod)
- [DebugDragMagnitude](ue_ue.WheeledVehicleMovementComponent.md#debugdragmagnitude)
- [DragArea](ue_ue.WheeledVehicleMovementComponent.md#dragarea)
- [DragCoefficient](ue_ue.WheeledVehicleMovementComponent.md#dragcoefficient)
- [EstimatedMaxEngineSpeed](ue_ue.WheeledVehicleMovementComponent.md#estimatedmaxenginespeed)
- [FixedPathBrakingDistance](ue_ue.WheeledVehicleMovementComponent.md#fixedpathbrakingdistance)
- [GroupsToAvoid](ue_ue.WheeledVehicleMovementComponent.md#groupstoavoid)
- [GroupsToIgnore](ue_ue.WheeledVehicleMovementComponent.md#groupstoignore)
- [HandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#handbrakeinput)
- [HandbrakeInputRate](ue_ue.WheeledVehicleMovementComponent.md#handbrakeinputrate)
- [HighForwardSpeedSubStepCount](ue_ue.WheeledVehicleMovementComponent.md#highforwardspeedsubstepcount)
- [IdleBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#idlebrakeinput)
- [InertiaTensorScale](ue_ue.WheeledVehicleMovementComponent.md#inertiatensorscale)
- [LowForwardSpeedSubStepCount](ue_ue.WheeledVehicleMovementComponent.md#lowforwardspeedsubstepcount)
- [Mass](ue_ue.WheeledVehicleMovementComponent.md#mass)
- [MaxEngineRPM](ue_ue.WheeledVehicleMovementComponent.md#maxenginerpm)
- [MaxNormalizedTireLoad](ue_ue.WheeledVehicleMovementComponent.md#maxnormalizedtireload)
- [MaxNormalizedTireLoadFiltered](ue_ue.WheeledVehicleMovementComponent.md#maxnormalizedtireloadfiltered)
- [MinNormalizedTireLoad](ue_ue.WheeledVehicleMovementComponent.md#minnormalizedtireload)
- [MinNormalizedTireLoadFiltered](ue_ue.WheeledVehicleMovementComponent.md#minnormalizedtireloadfiltered)
- [MovementState](ue_ue.WheeledVehicleMovementComponent.md#movementstate)
- [NavAgentProps](ue_ue.WheeledVehicleMovementComponent.md#navagentprops)
- [OnComponentActivated](ue_ue.WheeledVehicleMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.WheeledVehicleMovementComponent.md#oncomponentdeactivated)
- [OverrideController](ue_ue.WheeledVehicleMovementComponent.md#overridecontroller)
- [PathFollowingComp](ue_ue.WheeledVehicleMovementComponent.md#pathfollowingcomp)
- [PawnOwner](ue_ue.WheeledVehicleMovementComponent.md#pawnowner)
- [PendingLaunchVelocity](ue_ue.WheeledVehicleMovementComponent.md#pendinglaunchvelocity)
- [PlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.WheeledVehicleMovementComponent.md#primarycomponenttick)
- [RVOAvoidanceHeight](ue_ue.WheeledVehicleMovementComponent.md#rvoavoidanceheight)
- [RVOAvoidanceRadius](ue_ue.WheeledVehicleMovementComponent.md#rvoavoidanceradius)
- [RVOSteeringStep](ue_ue.WheeledVehicleMovementComponent.md#rvosteeringstep)
- [RVOThrottleStep](ue_ue.WheeledVehicleMovementComponent.md#rvothrottlestep)
- [RawBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#rawbrakeinput)
- [RawSteeringInput](ue_ue.WheeledVehicleMovementComponent.md#rawsteeringinput)
- [RawThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#rawthrottleinput)
- [ReplicatedState](ue_ue.WheeledVehicleMovementComponent.md#replicatedstate)
- [SteeringInput](ue_ue.WheeledVehicleMovementComponent.md#steeringinput)
- [SteeringInputRate](ue_ue.WheeledVehicleMovementComponent.md#steeringinputrate)
- [StopThreshold](ue_ue.WheeledVehicleMovementComponent.md#stopthreshold)
- [ThresholdLongitudinalSpeed](ue_ue.WheeledVehicleMovementComponent.md#thresholdlongitudinalspeed)
- [ThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#throttleinput)
- [ThrottleInputRate](ue_ue.WheeledVehicleMovementComponent.md#throttleinputrate)
- [UCSModifiedProperties](ue_ue.WheeledVehicleMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.WheeledVehicleMovementComponent.md#updatedprimitive)
- [Velocity](ue_ue.WheeledVehicleMovementComponent.md#velocity)
- [WheelSetups](ue_ue.WheeledVehicleMovementComponent.md#wheelsetups)
- [Wheels](ue_ue.WheeledVehicleMovementComponent.md#wheels)
- [WrongDirectionThreshold](ue_ue.WheeledVehicleMovementComponent.md#wrongdirectionthreshold)
- [\_\_tid\_ActorComponent\_\_](ue_ue.WheeledVehicleMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.WheeledVehicleMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.WheeledVehicleMovementComponent.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.WheeledVehicleMovementComponent.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.WheeledVehicleMovementComponent.md#__tid_pawnmovementcomponent__)
- [\_\_tid\_WheeledVehicleMovementComponent\_\_](ue_ue.WheeledVehicleMovementComponent.md#__tid_wheeledvehiclemovementcomponent__)
- [bAutoActivate](ue_ue.WheeledVehicleMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.WheeledVehicleMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.WheeledVehicleMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.WheeledVehicleMovementComponent.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.WheeledVehicleMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.WheeledVehicleMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.WheeledVehicleMovementComponent.md#bcreatedbyconstructionscript)
- [bDeprecatedSpringOffsetMode](ue_ue.WheeledVehicleMovementComponent.md#bdeprecatedspringoffsetmode)
- [bEditableWhenInherited](ue_ue.WheeledVehicleMovementComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.WheeledVehicleMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.WheeledVehicleMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.WheeledVehicleMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.WheeledVehicleMovementComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.WheeledVehicleMovementComponent.md#bnetaddressable)
- [bRawGearDownInput](ue_ue.WheeledVehicleMovementComponent.md#brawgeardowninput)
- [bRawGearUpInput](ue_ue.WheeledVehicleMovementComponent.md#brawgearupinput)
- [bRawHandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#brawhandbrakeinput)
- [bReplicates](ue_ue.WheeledVehicleMovementComponent.md#breplicates)
- [bReverseAsBrake](ue_ue.WheeledVehicleMovementComponent.md#breverseasbrake)
- [bSnapToPlaneAtStart](ue_ue.WheeledVehicleMovementComponent.md#bsnaptoplaneatstart)
- [bTickBeforeOwner](ue_ue.WheeledVehicleMovementComponent.md#btickbeforeowner)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.WheeledVehicleMovementComponent.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.WheeledVehicleMovementComponent.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.WheeledVehicleMovementComponent.md#buseaccelerationforpaths)
- [bUseFixedBrakingDistanceForPaths](ue_ue.WheeledVehicleMovementComponent.md#busefixedbrakingdistanceforpaths)
- [bUseRVOAvoidance](ue_ue.WheeledVehicleMovementComponent.md#buservoavoidance)
- [bWasAvoidanceUpdated](ue_ue.WheeledVehicleMovementComponent.md#bwasavoidanceupdated)

### Methods

- [Activate](ue_ue.WheeledVehicleMovementComponent.md#activate)
- [AddInputVector](ue_ue.WheeledVehicleMovementComponent.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.WheeledVehicleMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.WheeledVehicleMovementComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.WheeledVehicleMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.WheeledVehicleMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.WheeledVehicleMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.WheeledVehicleMovementComponent.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.WheeledVehicleMovementComponent.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.WheeledVehicleMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.WheeledVehicleMovementComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.WheeledVehicleMovementComponent.md#executeubergraph)
- [GetClass](ue_ue.WheeledVehicleMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.WheeledVehicleMovementComponent.md#getcomponenttickinterval)
- [GetCurrentGear](ue_ue.WheeledVehicleMovementComponent.md#getcurrentgear)
- [GetEngineMaxRotationSpeed](ue_ue.WheeledVehicleMovementComponent.md#getenginemaxrotationspeed)
- [GetEngineRotationSpeed](ue_ue.WheeledVehicleMovementComponent.md#getenginerotationspeed)
- [GetForwardSpeed](ue_ue.WheeledVehicleMovementComponent.md#getforwardspeed)
- [GetGravityZ](ue_ue.WheeledVehicleMovementComponent.md#getgravityz)
- [GetLastInputVector](ue_ue.WheeledVehicleMovementComponent.md#getlastinputvector)
- [GetMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#getmaxspeed)
- [GetName](ue_ue.WheeledVehicleMovementComponent.md#getname)
- [GetOuter](ue_ue.WheeledVehicleMovementComponent.md#getouter)
- [GetOwner](ue_ue.WheeledVehicleMovementComponent.md#getowner)
- [GetPawnOwner](ue_ue.WheeledVehicleMovementComponent.md#getpawnowner)
- [GetPendingInputVector](ue_ue.WheeledVehicleMovementComponent.md#getpendinginputvector)
- [GetPhysicsVolume](ue_ue.WheeledVehicleMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintorigin)
- [GetTargetGear](ue_ue.WheeledVehicleMovementComponent.md#gettargetgear)
- [GetUseAutoGears](ue_ue.WheeledVehicleMovementComponent.md#getuseautogears)
- [GetWorld](ue_ue.WheeledVehicleMovementComponent.md#getworld)
- [IsActive](ue_ue.WheeledVehicleMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.WheeledVehicleMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.WheeledVehicleMovementComponent.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.WheeledVehicleMovementComponent.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.WheeledVehicleMovementComponent.md#isfalling)
- [IsFlying](ue_ue.WheeledVehicleMovementComponent.md#isflying)
- [IsMoveInputIgnored](ue_ue.WheeledVehicleMovementComponent.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.WheeledVehicleMovementComponent.md#ismovingonground)
- [IsSwimming](ue_ue.WheeledVehicleMovementComponent.md#isswimming)
- [K2\_DestroyComponent](ue_ue.WheeledVehicleMovementComponent.md#k2_destroycomponent)
- [K2\_GetInputVector](ue_ue.WheeledVehicleMovementComponent.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.WheeledVehicleMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.WheeledVehicleMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.WheeledVehicleMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.WheeledVehicleMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.WheeledVehicleMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.WheeledVehicleMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.WheeledVehicleMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.WheeledVehicleMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.WheeledVehicleMovementComponent.md#removetickprerequisitecomponent)
- [ServerUpdateState](ue_ue.WheeledVehicleMovementComponent.md#serverupdatestate)
- [SetActive](ue_ue.WheeledVehicleMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.WheeledVehicleMovementComponent.md#setautoactivate)
- [SetAvoidanceEnabled](ue_ue.WheeledVehicleMovementComponent.md#setavoidanceenabled)
- [SetAvoidanceGroup](ue_ue.WheeledVehicleMovementComponent.md#setavoidancegroup)
- [SetAvoidanceGroupMask](ue_ue.WheeledVehicleMovementComponent.md#setavoidancegroupmask)
- [SetBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#setbrakeinput)
- [SetComponentTickEnabled](ue_ue.WheeledVehicleMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.WheeledVehicleMovementComponent.md#setcomponenttickinterval)
- [SetGearDown](ue_ue.WheeledVehicleMovementComponent.md#setgeardown)
- [SetGearUp](ue_ue.WheeledVehicleMovementComponent.md#setgearup)
- [SetGroupsToAvoid](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoavoid)
- [SetGroupsToAvoidMask](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoavoidmask)
- [SetGroupsToIgnore](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoignore)
- [SetGroupsToIgnoreMask](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoignoremask)
- [SetHandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#sethandbrakeinput)
- [SetIsReplicated](ue_ue.WheeledVehicleMovementComponent.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintorigin)
- [SetSteeringInput](ue_ue.WheeledVehicleMovementComponent.md#setsteeringinput)
- [SetTargetGear](ue_ue.WheeledVehicleMovementComponent.md#settargetgear)
- [SetThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#setthrottleinput)
- [SetTickGroup](ue_ue.WheeledVehicleMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.WheeledVehicleMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#setupdatedcomponent)
- [SetUseAutoGears](ue_ue.WheeledVehicleMovementComponent.md#setuseautogears)
- [SnapUpdatedComponentToPlane](ue_ue.WheeledVehicleMovementComponent.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.WheeledVehicleMovementComponent.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.WheeledVehicleMovementComponent.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.WheeledVehicleMovementComponent.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.WheeledVehicleMovementComponent.md#toggleactive)
- [Find](ue_ue.WheeledVehicleMovementComponent.md#find)
- [Load](ue_ue.WheeledVehicleMovementComponent.md#load)
- [StaticClass](ue_ue.WheeledVehicleMovementComponent.md#staticclass)

## Constructors

### constructor

• **new WheeledVehicleMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[constructor](ue_ue.PawnMovementComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:60509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60509)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AssetUserData](ue_ue.PawnMovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

#### Defined in

[ue/ue.d.ts:60537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60537)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:60541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60541)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

#### Defined in

[ue/ue.d.ts:60540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60540)

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

#### Defined in

[ue/ue.d.ts:60544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60544)

___

### BrakeInput

• **BrakeInput**: `number`

#### Defined in

[ue/ue.d.ts:60552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60552)

___

### BrakeInputRate

• **BrakeInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Defined in

[ue/ue.d.ts:60558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60558)

___

### ChassisHeight

• **ChassisHeight**: `number`

#### Defined in

[ue/ue.d.ts:60521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60521)

___

### ChassisWidth

• **ChassisWidth**: `number`

#### Defined in

[ue/ue.d.ts:60520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60520)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ComponentTags](ue_ue.PawnMovementComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[CreationMethod](ue_ue.PawnMovementComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### DebugDragMagnitude

• **DebugDragMagnitude**: `number`

#### Defined in

[ue/ue.d.ts:60525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60525)

___

### DragArea

• **DragArea**: `number`

#### Defined in

[ue/ue.d.ts:60522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60522)

___

### DragCoefficient

• **DragCoefficient**: `number`

#### Defined in

[ue/ue.d.ts:60519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60519)

___

### EstimatedMaxEngineSpeed

• **EstimatedMaxEngineSpeed**: `number`

#### Defined in

[ue/ue.d.ts:60523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60523)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[FixedPathBrakingDistance](ue_ue.PawnMovementComponent.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5468)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:60542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60542)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:60543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60543)

___

### HandbrakeInput

• **HandbrakeInput**: `number`

#### Defined in

[ue/ue.d.ts:60553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60553)

___

### HandbrakeInputRate

• **HandbrakeInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Defined in

[ue/ue.d.ts:60559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60559)

___

### HighForwardSpeedSubStepCount

• **HighForwardSpeedSubStepCount**: `number`

#### Defined in

[ue/ue.d.ts:60533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60533)

___

### IdleBrakeInput

• **IdleBrakeInput**: `number`

#### Defined in

[ue/ue.d.ts:60554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60554)

___

### InertiaTensorScale

• **InertiaTensorScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:60526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60526)

___

### LowForwardSpeedSubStepCount

• **LowForwardSpeedSubStepCount**: `number`

#### Defined in

[ue/ue.d.ts:60532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60532)

___

### Mass

• **Mass**: `number`

#### Defined in

[ue/ue.d.ts:60517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60517)

___

### MaxEngineRPM

• **MaxEngineRPM**: `number`

#### Defined in

[ue/ue.d.ts:60524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60524)

___

### MaxNormalizedTireLoad

• **MaxNormalizedTireLoad**: `number`

#### Defined in

[ue/ue.d.ts:60529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60529)

___

### MaxNormalizedTireLoadFiltered

• **MaxNormalizedTireLoadFiltered**: `number`

#### Defined in

[ue/ue.d.ts:60530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60530)

___

### MinNormalizedTireLoad

• **MinNormalizedTireLoad**: `number`

#### Defined in

[ue/ue.d.ts:60527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60527)

___

### MinNormalizedTireLoadFiltered

• **MinNormalizedTireLoadFiltered**: `number`

#### Defined in

[ue/ue.d.ts:60528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60528)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[MovementState](ue_ue.PawnMovementComponent.md#movementstate)

#### Defined in

[ue/ue.d.ts:5472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5472)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[NavAgentProps](ue_ue.PawnMovementComponent.md#navagentprops)

#### Defined in

[ue/ue.d.ts:5467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5467)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentActivated](ue_ue.PawnMovementComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentDeactivated](ue_ue.PawnMovementComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OverrideController

• **OverrideController**: [`Controller`](ue_ue.Controller.md)

#### Defined in

[ue/ue.d.ts:60561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60561)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PathFollowingComp](ue_ue.PawnMovementComponent.md#pathfollowingcomp)

#### Defined in

[ue/ue.d.ts:5473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5473)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PawnOwner](ue_ue.PawnMovementComponent.md#pawnowner)

#### Defined in

[ue/ue.d.ts:5490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5490)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:60545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60545)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintNormal](ue_ue.PawnMovementComponent.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5394)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PrimaryComponentTick](ue_ue.PawnMovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### RVOAvoidanceHeight

• **RVOAvoidanceHeight**: `number`

#### Defined in

[ue/ue.d.ts:60536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60536)

___

### RVOAvoidanceRadius

• **RVOAvoidanceRadius**: `number`

#### Defined in

[ue/ue.d.ts:60535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60535)

___

### RVOSteeringStep

• **RVOSteeringStep**: `number`

#### Defined in

[ue/ue.d.ts:60538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60538)

___

### RVOThrottleStep

• **RVOThrottleStep**: `number`

#### Defined in

[ue/ue.d.ts:60539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60539)

___

### RawBrakeInput

• **RawBrakeInput**: `number`

#### Defined in

[ue/ue.d.ts:60549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60549)

___

### RawSteeringInput

• **RawSteeringInput**: `number`

#### Defined in

[ue/ue.d.ts:60547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60547)

___

### RawThrottleInput

• **RawThrottleInput**: `number`

#### Defined in

[ue/ue.d.ts:60548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60548)

___

### ReplicatedState

• **ReplicatedState**: [`ReplicatedVehicleState`](ue_ue.ReplicatedVehicleState.md)

#### Defined in

[ue/ue.d.ts:60546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60546)

___

### SteeringInput

• **SteeringInput**: `number`

#### Defined in

[ue/ue.d.ts:60550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60550)

___

### SteeringInputRate

• **SteeringInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Defined in

[ue/ue.d.ts:60560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60560)

___

### StopThreshold

• **StopThreshold**: `number`

#### Defined in

[ue/ue.d.ts:60555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60555)

___

### ThresholdLongitudinalSpeed

• **ThresholdLongitudinalSpeed**: `number`

#### Defined in

[ue/ue.d.ts:60531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60531)

___

### ThrottleInput

• **ThrottleInput**: `number`

#### Defined in

[ue/ue.d.ts:60551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60551)

___

### ThrottleInputRate

• **ThrottleInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Defined in

[ue/ue.d.ts:60557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60557)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UCSModifiedProperties](ue_ue.PawnMovementComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedComponent](ue_ue.PawnMovementComponent.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedPrimitive](ue_ue.PawnMovementComponent.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5391)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Velocity](ue_ue.PawnMovementComponent.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5392)

___

### WheelSetups

• **WheelSetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WheelSetup`](ue_ue.WheelSetup.md)\>

#### Defined in

[ue/ue.d.ts:60518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60518)

___

### Wheels

• **Wheels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VehicleWheel`](ue_ue.VehicleWheel.md)\>

#### Defined in

[ue/ue.d.ts:60534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60534)

___

### WrongDirectionThreshold

• **WrongDirectionThreshold**: `number`

#### Defined in

[ue/ue.d.ts:60556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60556)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_ActorComponent__](ue_ue.PawnMovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_MovementComponent__](ue_ue.PawnMovementComponent.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5430)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_navmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5485)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_Object__](ue_ue.PawnMovementComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_pawnmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5502)

___

### \_\_tid\_WheeledVehicleMovementComponent\_\_

• **\_\_tid\_WheeledVehicleMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60588)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoActivate](ue_ue.PawnMovementComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.PawnMovementComponent.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.PawnMovementComponent.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.PawnMovementComponent.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5396)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCanEverAffectNavigation](ue_ue.PawnMovementComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.PawnMovementComponent.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bConstrainToPlane](ue_ue.PawnMovementComponent.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCreatedByConstructionScript](ue_ue.PawnMovementComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bDeprecatedSpringOffsetMode

• **bDeprecatedSpringOffsetMode**: `boolean`

#### Defined in

[ue/ue.d.ts:60510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60510)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bEditableWhenInherited](ue_ue.PawnMovementComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bInstanceComponent](ue_ue.PawnMovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsActive](ue_ue.PawnMovementComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsEditorOnly](ue_ue.PawnMovementComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsVisualizationComponent](ue_ue.PawnMovementComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bNetAddressable](ue_ue.PawnMovementComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bRawGearDownInput

• **bRawGearDownInput**: `boolean`

#### Defined in

[ue/ue.d.ts:60515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60515)

___

### bRawGearUpInput

• **bRawGearUpInput**: `boolean`

#### Defined in

[ue/ue.d.ts:60514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60514)

___

### bRawHandbrakeInput

• **bRawHandbrakeInput**: `boolean`

#### Defined in

[ue/ue.d.ts:60513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60513)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bReplicates](ue_ue.PawnMovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bReverseAsBrake

• **bReverseAsBrake**: `boolean`

#### Defined in

[ue/ue.d.ts:60511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60511)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.PawnMovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5400)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bTickBeforeOwner](ue_ue.PawnMovementComponent.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5397)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.PawnMovementComponent.md#bupdatenavagentwithownerscollision)

#### Defined in

[ue/ue.d.ts:5469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5469)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.PawnMovementComponent.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5395)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseAccelerationForPaths](ue_ue.PawnMovementComponent.md#buseaccelerationforpaths)

#### Defined in

[ue/ue.d.ts:5470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5470)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.PawnMovementComponent.md#busefixedbrakingdistanceforpaths)

#### Defined in

[ue/ue.d.ts:5471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5471)

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

#### Defined in

[ue/ue.d.ts:60512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60512)

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

#### Defined in

[ue/ue.d.ts:60516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60516)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Activate](ue_ue.PawnMovementComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L306)

___

### AddInputVector

▸ **AddInputVector**(`WorldVector`, `bForce?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldVector` | [`Vector`](ue_ue_s.Vector.md) |
| `bForce?` | `boolean` |

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AddInputVector](ue_ue.PawnMovementComponent.md#addinputvector)

#### Defined in

[ue/ue.d.ts:5491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5491)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AddTickPrerequisiteActor](ue_ue.PawnMovementComponent.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L307)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.PawnMovementComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L308)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ComponentHasTag](ue_ue.PawnMovementComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConstrainDirectionToPlane](ue_ue.PawnMovementComponent.md#constraindirectiontoplane)

#### Defined in

[ue/ue.d.ts:5404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5404)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConstrainLocationToPlane](ue_ue.PawnMovementComponent.md#constrainlocationtoplane)

#### Defined in

[ue/ue.d.ts:5405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5405)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConstrainNormalToPlane](ue_ue.PawnMovementComponent.md#constrainnormaltoplane)

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5406)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConsumeInputVector](ue_ue.PawnMovementComponent.md#consumeinputvector)

#### Defined in

[ue/ue.d.ts:5492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5492)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[CreateDefaultSubobject](ue_ue.PawnMovementComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Deactivate](ue_ue.PawnMovementComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ExecuteUbergraph](ue_ue.PawnMovementComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetClass](ue_ue.PawnMovementComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetComponentTickInterval](ue_ue.PawnMovementComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetCurrentGear

▸ **GetCurrentGear**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60562)

___

### GetEngineMaxRotationSpeed

▸ **GetEngineMaxRotationSpeed**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60563)

___

### GetEngineRotationSpeed

▸ **GetEngineRotationSpeed**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60564)

___

### GetForwardSpeed

▸ **GetForwardSpeed**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60565)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetGravityZ](ue_ue.PawnMovementComponent.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5407)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetLastInputVector](ue_ue.PawnMovementComponent.md#getlastinputvector)

#### Defined in

[ue/ue.d.ts:5493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5493)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetMaxSpeed](ue_ue.PawnMovementComponent.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5408)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetName](ue_ue.PawnMovementComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOuter](ue_ue.PawnMovementComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOwner](ue_ue.PawnMovementComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPawnOwner](ue_ue.PawnMovementComponent.md#getpawnowner)

#### Defined in

[ue/ue.d.ts:5494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5494)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPendingInputVector](ue_ue.PawnMovementComponent.md#getpendinginputvector)

#### Defined in

[ue/ue.d.ts:5495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5495)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPhysicsVolume](ue_ue.PawnMovementComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5412)

___

### GetTargetGear

▸ **GetTargetGear**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60566)

___

### GetUseAutoGears

▸ **GetUseAutoGears**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:60567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60567)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetWorld](ue_ue.PawnMovementComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsActive](ue_ue.PawnMovementComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsBeingDestroyed](ue_ue.PawnMovementComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsComponentTickEnabled](ue_ue.PawnMovementComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsCrouching](ue_ue.PawnMovementComponent.md#iscrouching)

#### Defined in

[ue/ue.d.ts:5474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5474)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsExceedingMaxSpeed](ue_ue.PawnMovementComponent.md#isexceedingmaxspeed)

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5413)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFalling](ue_ue.PawnMovementComponent.md#isfalling)

#### Defined in

[ue/ue.d.ts:5475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5475)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFlying](ue_ue.PawnMovementComponent.md#isflying)

#### Defined in

[ue/ue.d.ts:5476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5476)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMoveInputIgnored](ue_ue.PawnMovementComponent.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:5496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5496)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMovingOnGround](ue_ue.PawnMovementComponent.md#ismovingonground)

#### Defined in

[ue/ue.d.ts:5477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5477)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsSwimming](ue_ue.PawnMovementComponent.md#isswimming)

#### Defined in

[ue/ue.d.ts:5478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5478)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_DestroyComponent](ue_ue.PawnMovementComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetInputVector](ue_ue.PawnMovementComponent.md#k2_getinputvector)

#### Defined in

[ue/ue.d.ts:5497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5497)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.PawnMovementComponent.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.PawnMovementComponent.md#k2_getmodifiedmaxspeed)

#### Defined in

[ue/ue.d.ts:5415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5415)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_MoveUpdatedComponent](ue_ue.PawnMovementComponent.md#k2_moveupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5416)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnRep_IsActive](ue_ue.PawnMovementComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PhysicsVolumeChanged](ue_ue.PawnMovementComponent.md#physicsvolumechanged)

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveBeginPlay](ue_ue.PawnMovementComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L318)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveEndPlay](ue_ue.PawnMovementComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L319)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveTick](ue_ue.PawnMovementComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RegisterComponent](ue_ue.PawnMovementComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L321)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.PawnMovementComponent.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L322)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.PawnMovementComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### ServerUpdateState

▸ **ServerUpdateState**(`InSteeringInput`, `InThrottleInput`, `InBrakeInput`, `InHandbrakeInput`, `CurrentGear`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSteeringInput` | `number` |
| `InThrottleInput` | `number` |
| `InBrakeInput` | `number` |
| `InHandbrakeInput` | `number` |
| `CurrentGear` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60568)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetActive](ue_ue.PawnMovementComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetAutoActivate](ue_ue.PawnMovementComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

___

### SetAvoidanceEnabled

▸ **SetAvoidanceEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60569)

___

### SetAvoidanceGroup

▸ **SetAvoidanceGroup**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60570)

___

### SetAvoidanceGroupMask

▸ **SetAvoidanceGroupMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60571)

___

### SetBrakeInput

▸ **SetBrakeInput**(`Brake`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Brake` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60572)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetComponentTickEnabled](ue_ue.PawnMovementComponent.md#setcomponenttickenabled)

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L326)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetComponentTickInterval](ue_ue.PawnMovementComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

___

### SetGearDown

▸ **SetGearDown**(`bNewGearDown`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewGearDown` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60573)

___

### SetGearUp

▸ **SetGearUp**(`bNewGearUp`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewGearUp` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60574)

___

### SetGroupsToAvoid

▸ **SetGroupsToAvoid**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60575)

___

### SetGroupsToAvoidMask

▸ **SetGroupsToAvoidMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60576)

___

### SetGroupsToIgnore

▸ **SetGroupsToIgnore**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60577)

___

### SetGroupsToIgnoreMask

▸ **SetGroupsToIgnoreMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60578)

___

### SetHandbrakeInput

▸ **SetHandbrakeInput**(`bNewHandbrake`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewHandbrake` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60579)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetIsReplicated](ue_ue.PawnMovementComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#setplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5418)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintEnabled](ue_ue.PawnMovementComponent.md#setplaneconstraintenabled)

#### Defined in

[ue/ue.d.ts:5419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5419)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintFromVectors](ue_ue.PawnMovementComponent.md#setplaneconstraintfromvectors)

#### Defined in

[ue/ue.d.ts:5420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5420)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#setplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5421)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#setplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5422)

___

### SetSteeringInput

▸ **SetSteeringInput**(`Steering`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Steering` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60580)

___

### SetTargetGear

▸ **SetTargetGear**(`GearNum`, `bImmediate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GearNum` | `number` |
| `bImmediate` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60581)

___

### SetThrottleInput

▸ **SetThrottleInput**(`Throttle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Throttle` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60582)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetTickGroup](ue_ue.PawnMovementComponent.md#settickgroup)

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L330)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetTickableWhenPaused](ue_ue.PawnMovementComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetUpdatedComponent](ue_ue.PawnMovementComponent.md#setupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5423)

___

### SetUseAutoGears

▸ **SetUseAutoGears**(`bUseAuto`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUseAuto` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60583)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.PawnMovementComponent.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5424)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopActiveMovement](ue_ue.PawnMovementComponent.md#stopactivemovement)

#### Defined in

[ue/ue.d.ts:5479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5479)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementImmediately](ue_ue.PawnMovementComponent.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5425)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementKeepPathing](ue_ue.PawnMovementComponent.md#stopmovementkeeppathing)

#### Defined in

[ue/ue.d.ts:5480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5480)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ToggleActive](ue_ue.PawnMovementComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Find](ue_ue.PawnMovementComponent.md#find)

#### Defined in

[ue/ue.d.ts:60585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60585)

___

### Load

▸ `Static` **Load**(`InName`): [`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Load](ue_ue.PawnMovementComponent.md#load)

#### Defined in

[ue/ue.d.ts:60586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60586)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StaticClass](ue_ue.PawnMovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:60584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60584)
