[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SimpleWheeledVehicleMovementComponent

# Class: SimpleWheeledVehicleMovementComponent

[ue/ue](../modules/ue_ue.md).SimpleWheeledVehicleMovementComponent

## Hierarchy

- [`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

  ↳ **`SimpleWheeledVehicleMovementComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.SimpleWheeledVehicleMovementComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.SimpleWheeledVehicleMovementComponent.md#assetuserdata)
- [AvoidanceConsiderationRadius](ue_ue.SimpleWheeledVehicleMovementComponent.md#avoidanceconsiderationradius)
- [AvoidanceGroup](ue_ue.SimpleWheeledVehicleMovementComponent.md#avoidancegroup)
- [AvoidanceUID](ue_ue.SimpleWheeledVehicleMovementComponent.md#avoidanceuid)
- [AvoidanceWeight](ue_ue.SimpleWheeledVehicleMovementComponent.md#avoidanceweight)
- [BrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#brakeinput)
- [BrakeInputRate](ue_ue.SimpleWheeledVehicleMovementComponent.md#brakeinputrate)
- [ChassisHeight](ue_ue.SimpleWheeledVehicleMovementComponent.md#chassisheight)
- [ChassisWidth](ue_ue.SimpleWheeledVehicleMovementComponent.md#chassiswidth)
- [ComponentTags](ue_ue.SimpleWheeledVehicleMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.SimpleWheeledVehicleMovementComponent.md#creationmethod)
- [DebugDragMagnitude](ue_ue.SimpleWheeledVehicleMovementComponent.md#debugdragmagnitude)
- [DragArea](ue_ue.SimpleWheeledVehicleMovementComponent.md#dragarea)
- [DragCoefficient](ue_ue.SimpleWheeledVehicleMovementComponent.md#dragcoefficient)
- [EstimatedMaxEngineSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#estimatedmaxenginespeed)
- [FixedPathBrakingDistance](ue_ue.SimpleWheeledVehicleMovementComponent.md#fixedpathbrakingdistance)
- [GroupsToAvoid](ue_ue.SimpleWheeledVehicleMovementComponent.md#groupstoavoid)
- [GroupsToIgnore](ue_ue.SimpleWheeledVehicleMovementComponent.md#groupstoignore)
- [HandbrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#handbrakeinput)
- [HandbrakeInputRate](ue_ue.SimpleWheeledVehicleMovementComponent.md#handbrakeinputrate)
- [HighForwardSpeedSubStepCount](ue_ue.SimpleWheeledVehicleMovementComponent.md#highforwardspeedsubstepcount)
- [IdleBrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#idlebrakeinput)
- [InertiaTensorScale](ue_ue.SimpleWheeledVehicleMovementComponent.md#inertiatensorscale)
- [LowForwardSpeedSubStepCount](ue_ue.SimpleWheeledVehicleMovementComponent.md#lowforwardspeedsubstepcount)
- [Mass](ue_ue.SimpleWheeledVehicleMovementComponent.md#mass)
- [MaxEngineRPM](ue_ue.SimpleWheeledVehicleMovementComponent.md#maxenginerpm)
- [MaxNormalizedTireLoad](ue_ue.SimpleWheeledVehicleMovementComponent.md#maxnormalizedtireload)
- [MaxNormalizedTireLoadFiltered](ue_ue.SimpleWheeledVehicleMovementComponent.md#maxnormalizedtireloadfiltered)
- [MinNormalizedTireLoad](ue_ue.SimpleWheeledVehicleMovementComponent.md#minnormalizedtireload)
- [MinNormalizedTireLoadFiltered](ue_ue.SimpleWheeledVehicleMovementComponent.md#minnormalizedtireloadfiltered)
- [MovementState](ue_ue.SimpleWheeledVehicleMovementComponent.md#movementstate)
- [NavAgentProps](ue_ue.SimpleWheeledVehicleMovementComponent.md#navagentprops)
- [OnComponentActivated](ue_ue.SimpleWheeledVehicleMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.SimpleWheeledVehicleMovementComponent.md#oncomponentdeactivated)
- [OverrideController](ue_ue.SimpleWheeledVehicleMovementComponent.md#overridecontroller)
- [PathFollowingComp](ue_ue.SimpleWheeledVehicleMovementComponent.md#pathfollowingcomp)
- [PawnOwner](ue_ue.SimpleWheeledVehicleMovementComponent.md#pawnowner)
- [PendingLaunchVelocity](ue_ue.SimpleWheeledVehicleMovementComponent.md#pendinglaunchvelocity)
- [PlaneConstraintAxisSetting](ue_ue.SimpleWheeledVehicleMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.SimpleWheeledVehicleMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.SimpleWheeledVehicleMovementComponent.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.SimpleWheeledVehicleMovementComponent.md#primarycomponenttick)
- [RVOAvoidanceHeight](ue_ue.SimpleWheeledVehicleMovementComponent.md#rvoavoidanceheight)
- [RVOAvoidanceRadius](ue_ue.SimpleWheeledVehicleMovementComponent.md#rvoavoidanceradius)
- [RVOSteeringStep](ue_ue.SimpleWheeledVehicleMovementComponent.md#rvosteeringstep)
- [RVOThrottleStep](ue_ue.SimpleWheeledVehicleMovementComponent.md#rvothrottlestep)
- [RawBrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#rawbrakeinput)
- [RawSteeringInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#rawsteeringinput)
- [RawThrottleInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#rawthrottleinput)
- [ReplicatedState](ue_ue.SimpleWheeledVehicleMovementComponent.md#replicatedstate)
- [SteeringInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#steeringinput)
- [SteeringInputRate](ue_ue.SimpleWheeledVehicleMovementComponent.md#steeringinputrate)
- [StopThreshold](ue_ue.SimpleWheeledVehicleMovementComponent.md#stopthreshold)
- [ThresholdLongitudinalSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#thresholdlongitudinalspeed)
- [ThrottleInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#throttleinput)
- [ThrottleInputRate](ue_ue.SimpleWheeledVehicleMovementComponent.md#throttleinputrate)
- [UCSModifiedProperties](ue_ue.SimpleWheeledVehicleMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.SimpleWheeledVehicleMovementComponent.md#updatedprimitive)
- [Velocity](ue_ue.SimpleWheeledVehicleMovementComponent.md#velocity)
- [WheelSetups](ue_ue.SimpleWheeledVehicleMovementComponent.md#wheelsetups)
- [Wheels](ue_ue.SimpleWheeledVehicleMovementComponent.md#wheels)
- [WrongDirectionThreshold](ue_ue.SimpleWheeledVehicleMovementComponent.md#wrongdirectionthreshold)
- [\_\_tid\_ActorComponent\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_pawnmovementcomponent__)
- [\_\_tid\_SimpleWheeledVehicleMovementComponent\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_simplewheeledvehiclemovementcomponent__)
- [\_\_tid\_WheeledVehicleMovementComponent\_\_](ue_ue.SimpleWheeledVehicleMovementComponent.md#__tid_wheeledvehiclemovementcomponent__)
- [bAutoActivate](ue_ue.SimpleWheeledVehicleMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.SimpleWheeledVehicleMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.SimpleWheeledVehicleMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.SimpleWheeledVehicleMovementComponent.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.SimpleWheeledVehicleMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.SimpleWheeledVehicleMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.SimpleWheeledVehicleMovementComponent.md#bcreatedbyconstructionscript)
- [bDeprecatedSpringOffsetMode](ue_ue.SimpleWheeledVehicleMovementComponent.md#bdeprecatedspringoffsetmode)
- [bEditableWhenInherited](ue_ue.SimpleWheeledVehicleMovementComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.SimpleWheeledVehicleMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.SimpleWheeledVehicleMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.SimpleWheeledVehicleMovementComponent.md#bnetaddressable)
- [bRawGearDownInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#brawgeardowninput)
- [bRawGearUpInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#brawgearupinput)
- [bRawHandbrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#brawhandbrakeinput)
- [bReplicates](ue_ue.SimpleWheeledVehicleMovementComponent.md#breplicates)
- [bReverseAsBrake](ue_ue.SimpleWheeledVehicleMovementComponent.md#breverseasbrake)
- [bSnapToPlaneAtStart](ue_ue.SimpleWheeledVehicleMovementComponent.md#bsnaptoplaneatstart)
- [bTickBeforeOwner](ue_ue.SimpleWheeledVehicleMovementComponent.md#btickbeforeowner)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.SimpleWheeledVehicleMovementComponent.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.SimpleWheeledVehicleMovementComponent.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.SimpleWheeledVehicleMovementComponent.md#buseaccelerationforpaths)
- [bUseFixedBrakingDistanceForPaths](ue_ue.SimpleWheeledVehicleMovementComponent.md#busefixedbrakingdistanceforpaths)
- [bUseRVOAvoidance](ue_ue.SimpleWheeledVehicleMovementComponent.md#buservoavoidance)
- [bWasAvoidanceUpdated](ue_ue.SimpleWheeledVehicleMovementComponent.md#bwasavoidanceupdated)

### Methods

- [Activate](ue_ue.SimpleWheeledVehicleMovementComponent.md#activate)
- [AddInputVector](ue_ue.SimpleWheeledVehicleMovementComponent.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.SimpleWheeledVehicleMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.SimpleWheeledVehicleMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.SimpleWheeledVehicleMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.SimpleWheeledVehicleMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.SimpleWheeledVehicleMovementComponent.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.SimpleWheeledVehicleMovementComponent.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.SimpleWheeledVehicleMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.SimpleWheeledVehicleMovementComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.SimpleWheeledVehicleMovementComponent.md#executeubergraph)
- [GetClass](ue_ue.SimpleWheeledVehicleMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.SimpleWheeledVehicleMovementComponent.md#getcomponenttickinterval)
- [GetCurrentGear](ue_ue.SimpleWheeledVehicleMovementComponent.md#getcurrentgear)
- [GetEngineMaxRotationSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#getenginemaxrotationspeed)
- [GetEngineRotationSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#getenginerotationspeed)
- [GetForwardSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#getforwardspeed)
- [GetGravityZ](ue_ue.SimpleWheeledVehicleMovementComponent.md#getgravityz)
- [GetLastInputVector](ue_ue.SimpleWheeledVehicleMovementComponent.md#getlastinputvector)
- [GetMaxSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#getmaxspeed)
- [GetName](ue_ue.SimpleWheeledVehicleMovementComponent.md#getname)
- [GetOuter](ue_ue.SimpleWheeledVehicleMovementComponent.md#getouter)
- [GetOwner](ue_ue.SimpleWheeledVehicleMovementComponent.md#getowner)
- [GetPawnOwner](ue_ue.SimpleWheeledVehicleMovementComponent.md#getpawnowner)
- [GetPendingInputVector](ue_ue.SimpleWheeledVehicleMovementComponent.md#getpendinginputvector)
- [GetPhysicsVolume](ue_ue.SimpleWheeledVehicleMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.SimpleWheeledVehicleMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.SimpleWheeledVehicleMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.SimpleWheeledVehicleMovementComponent.md#getplaneconstraintorigin)
- [GetTargetGear](ue_ue.SimpleWheeledVehicleMovementComponent.md#gettargetgear)
- [GetUseAutoGears](ue_ue.SimpleWheeledVehicleMovementComponent.md#getuseautogears)
- [GetWorld](ue_ue.SimpleWheeledVehicleMovementComponent.md#getworld)
- [IsActive](ue_ue.SimpleWheeledVehicleMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.SimpleWheeledVehicleMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.SimpleWheeledVehicleMovementComponent.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.SimpleWheeledVehicleMovementComponent.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.SimpleWheeledVehicleMovementComponent.md#isfalling)
- [IsFlying](ue_ue.SimpleWheeledVehicleMovementComponent.md#isflying)
- [IsMoveInputIgnored](ue_ue.SimpleWheeledVehicleMovementComponent.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.SimpleWheeledVehicleMovementComponent.md#ismovingonground)
- [IsSwimming](ue_ue.SimpleWheeledVehicleMovementComponent.md#isswimming)
- [K2\_DestroyComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#k2_destroycomponent)
- [K2\_GetInputVector](ue_ue.SimpleWheeledVehicleMovementComponent.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.SimpleWheeledVehicleMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.SimpleWheeledVehicleMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.SimpleWheeledVehicleMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.SimpleWheeledVehicleMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.SimpleWheeledVehicleMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.SimpleWheeledVehicleMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.SimpleWheeledVehicleMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.SimpleWheeledVehicleMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#removetickprerequisitecomponent)
- [ServerUpdateState](ue_ue.SimpleWheeledVehicleMovementComponent.md#serverupdatestate)
- [SetActive](ue_ue.SimpleWheeledVehicleMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.SimpleWheeledVehicleMovementComponent.md#setautoactivate)
- [SetAvoidanceEnabled](ue_ue.SimpleWheeledVehicleMovementComponent.md#setavoidanceenabled)
- [SetAvoidanceGroup](ue_ue.SimpleWheeledVehicleMovementComponent.md#setavoidancegroup)
- [SetAvoidanceGroupMask](ue_ue.SimpleWheeledVehicleMovementComponent.md#setavoidancegroupmask)
- [SetBrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#setbrakeinput)
- [SetBrakeTorque](ue_ue.SimpleWheeledVehicleMovementComponent.md#setbraketorque)
- [SetComponentTickEnabled](ue_ue.SimpleWheeledVehicleMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.SimpleWheeledVehicleMovementComponent.md#setcomponenttickinterval)
- [SetDriveTorque](ue_ue.SimpleWheeledVehicleMovementComponent.md#setdrivetorque)
- [SetGearDown](ue_ue.SimpleWheeledVehicleMovementComponent.md#setgeardown)
- [SetGearUp](ue_ue.SimpleWheeledVehicleMovementComponent.md#setgearup)
- [SetGroupsToAvoid](ue_ue.SimpleWheeledVehicleMovementComponent.md#setgroupstoavoid)
- [SetGroupsToAvoidMask](ue_ue.SimpleWheeledVehicleMovementComponent.md#setgroupstoavoidmask)
- [SetGroupsToIgnore](ue_ue.SimpleWheeledVehicleMovementComponent.md#setgroupstoignore)
- [SetGroupsToIgnoreMask](ue_ue.SimpleWheeledVehicleMovementComponent.md#setgroupstoignoremask)
- [SetHandbrakeInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#sethandbrakeinput)
- [SetIsReplicated](ue_ue.SimpleWheeledVehicleMovementComponent.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.SimpleWheeledVehicleMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.SimpleWheeledVehicleMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.SimpleWheeledVehicleMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.SimpleWheeledVehicleMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.SimpleWheeledVehicleMovementComponent.md#setplaneconstraintorigin)
- [SetSteerAngle](ue_ue.SimpleWheeledVehicleMovementComponent.md#setsteerangle)
- [SetSteeringInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#setsteeringinput)
- [SetTargetGear](ue_ue.SimpleWheeledVehicleMovementComponent.md#settargetgear)
- [SetThrottleInput](ue_ue.SimpleWheeledVehicleMovementComponent.md#setthrottleinput)
- [SetTickGroup](ue_ue.SimpleWheeledVehicleMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SimpleWheeledVehicleMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.SimpleWheeledVehicleMovementComponent.md#setupdatedcomponent)
- [SetUseAutoGears](ue_ue.SimpleWheeledVehicleMovementComponent.md#setuseautogears)
- [SnapUpdatedComponentToPlane](ue_ue.SimpleWheeledVehicleMovementComponent.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.SimpleWheeledVehicleMovementComponent.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.SimpleWheeledVehicleMovementComponent.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.SimpleWheeledVehicleMovementComponent.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.SimpleWheeledVehicleMovementComponent.md#toggleactive)
- [Find](ue_ue.SimpleWheeledVehicleMovementComponent.md#find)
- [Load](ue_ue.SimpleWheeledVehicleMovementComponent.md#load)
- [StaticClass](ue_ue.SimpleWheeledVehicleMovementComponent.md#staticclass)

## Constructors

### constructor

• **new SimpleWheeledVehicleMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[constructor](ue_ue.WheeledVehicleMovementComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:60592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60592)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AssetUserData](ue_ue.WheeledVehicleMovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceConsiderationRadius](ue_ue.WheeledVehicleMovementComponent.md#avoidanceconsiderationradius)

#### Defined in

[ue/ue.d.ts:60537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60537)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceGroup](ue_ue.WheeledVehicleMovementComponent.md#avoidancegroup)

#### Defined in

[ue/ue.d.ts:60541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60541)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceUID](ue_ue.WheeledVehicleMovementComponent.md#avoidanceuid)

#### Defined in

[ue/ue.d.ts:60540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60540)

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceWeight](ue_ue.WheeledVehicleMovementComponent.md#avoidanceweight)

#### Defined in

[ue/ue.d.ts:60544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60544)

___

### BrakeInput

• **BrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[BrakeInput](ue_ue.WheeledVehicleMovementComponent.md#brakeinput)

#### Defined in

[ue/ue.d.ts:60552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60552)

___

### BrakeInputRate

• **BrakeInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[BrakeInputRate](ue_ue.WheeledVehicleMovementComponent.md#brakeinputrate)

#### Defined in

[ue/ue.d.ts:60558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60558)

___

### ChassisHeight

• **ChassisHeight**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ChassisHeight](ue_ue.WheeledVehicleMovementComponent.md#chassisheight)

#### Defined in

[ue/ue.d.ts:60521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60521)

___

### ChassisWidth

• **ChassisWidth**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ChassisWidth](ue_ue.WheeledVehicleMovementComponent.md#chassiswidth)

#### Defined in

[ue/ue.d.ts:60520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60520)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ComponentTags](ue_ue.WheeledVehicleMovementComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[CreationMethod](ue_ue.WheeledVehicleMovementComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### DebugDragMagnitude

• **DebugDragMagnitude**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[DebugDragMagnitude](ue_ue.WheeledVehicleMovementComponent.md#debugdragmagnitude)

#### Defined in

[ue/ue.d.ts:60525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60525)

___

### DragArea

• **DragArea**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[DragArea](ue_ue.WheeledVehicleMovementComponent.md#dragarea)

#### Defined in

[ue/ue.d.ts:60522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60522)

___

### DragCoefficient

• **DragCoefficient**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[DragCoefficient](ue_ue.WheeledVehicleMovementComponent.md#dragcoefficient)

#### Defined in

[ue/ue.d.ts:60519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60519)

___

### EstimatedMaxEngineSpeed

• **EstimatedMaxEngineSpeed**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[EstimatedMaxEngineSpeed](ue_ue.WheeledVehicleMovementComponent.md#estimatedmaxenginespeed)

#### Defined in

[ue/ue.d.ts:60523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60523)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[FixedPathBrakingDistance](ue_ue.WheeledVehicleMovementComponent.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5468)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GroupsToAvoid](ue_ue.WheeledVehicleMovementComponent.md#groupstoavoid)

#### Defined in

[ue/ue.d.ts:60542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60542)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GroupsToIgnore](ue_ue.WheeledVehicleMovementComponent.md#groupstoignore)

#### Defined in

[ue/ue.d.ts:60543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60543)

___

### HandbrakeInput

• **HandbrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[HandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#handbrakeinput)

#### Defined in

[ue/ue.d.ts:60553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60553)

___

### HandbrakeInputRate

• **HandbrakeInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[HandbrakeInputRate](ue_ue.WheeledVehicleMovementComponent.md#handbrakeinputrate)

#### Defined in

[ue/ue.d.ts:60559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60559)

___

### HighForwardSpeedSubStepCount

• **HighForwardSpeedSubStepCount**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[HighForwardSpeedSubStepCount](ue_ue.WheeledVehicleMovementComponent.md#highforwardspeedsubstepcount)

#### Defined in

[ue/ue.d.ts:60533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60533)

___

### IdleBrakeInput

• **IdleBrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IdleBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#idlebrakeinput)

#### Defined in

[ue/ue.d.ts:60554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60554)

___

### InertiaTensorScale

• **InertiaTensorScale**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[InertiaTensorScale](ue_ue.WheeledVehicleMovementComponent.md#inertiatensorscale)

#### Defined in

[ue/ue.d.ts:60526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60526)

___

### LowForwardSpeedSubStepCount

• **LowForwardSpeedSubStepCount**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[LowForwardSpeedSubStepCount](ue_ue.WheeledVehicleMovementComponent.md#lowforwardspeedsubstepcount)

#### Defined in

[ue/ue.d.ts:60532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60532)

___

### Mass

• **Mass**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Mass](ue_ue.WheeledVehicleMovementComponent.md#mass)

#### Defined in

[ue/ue.d.ts:60517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60517)

___

### MaxEngineRPM

• **MaxEngineRPM**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MaxEngineRPM](ue_ue.WheeledVehicleMovementComponent.md#maxenginerpm)

#### Defined in

[ue/ue.d.ts:60524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60524)

___

### MaxNormalizedTireLoad

• **MaxNormalizedTireLoad**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MaxNormalizedTireLoad](ue_ue.WheeledVehicleMovementComponent.md#maxnormalizedtireload)

#### Defined in

[ue/ue.d.ts:60529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60529)

___

### MaxNormalizedTireLoadFiltered

• **MaxNormalizedTireLoadFiltered**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MaxNormalizedTireLoadFiltered](ue_ue.WheeledVehicleMovementComponent.md#maxnormalizedtireloadfiltered)

#### Defined in

[ue/ue.d.ts:60530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60530)

___

### MinNormalizedTireLoad

• **MinNormalizedTireLoad**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MinNormalizedTireLoad](ue_ue.WheeledVehicleMovementComponent.md#minnormalizedtireload)

#### Defined in

[ue/ue.d.ts:60527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60527)

___

### MinNormalizedTireLoadFiltered

• **MinNormalizedTireLoadFiltered**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MinNormalizedTireLoadFiltered](ue_ue.WheeledVehicleMovementComponent.md#minnormalizedtireloadfiltered)

#### Defined in

[ue/ue.d.ts:60528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60528)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MovementState](ue_ue.WheeledVehicleMovementComponent.md#movementstate)

#### Defined in

[ue/ue.d.ts:5472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5472)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[NavAgentProps](ue_ue.WheeledVehicleMovementComponent.md#navagentprops)

#### Defined in

[ue/ue.d.ts:5467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5467)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OnComponentActivated](ue_ue.WheeledVehicleMovementComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OnComponentDeactivated](ue_ue.WheeledVehicleMovementComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OverrideController

• **OverrideController**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OverrideController](ue_ue.WheeledVehicleMovementComponent.md#overridecontroller)

#### Defined in

[ue/ue.d.ts:60561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60561)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PathFollowingComp](ue_ue.WheeledVehicleMovementComponent.md#pathfollowingcomp)

#### Defined in

[ue/ue.d.ts:5473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5473)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PawnOwner](ue_ue.WheeledVehicleMovementComponent.md#pawnowner)

#### Defined in

[ue/ue.d.ts:5490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5490)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PendingLaunchVelocity](ue_ue.WheeledVehicleMovementComponent.md#pendinglaunchvelocity)

#### Defined in

[ue/ue.d.ts:60545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60545)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5394)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PrimaryComponentTick](ue_ue.WheeledVehicleMovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### RVOAvoidanceHeight

• **RVOAvoidanceHeight**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOAvoidanceHeight](ue_ue.WheeledVehicleMovementComponent.md#rvoavoidanceheight)

#### Defined in

[ue/ue.d.ts:60536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60536)

___

### RVOAvoidanceRadius

• **RVOAvoidanceRadius**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOAvoidanceRadius](ue_ue.WheeledVehicleMovementComponent.md#rvoavoidanceradius)

#### Defined in

[ue/ue.d.ts:60535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60535)

___

### RVOSteeringStep

• **RVOSteeringStep**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOSteeringStep](ue_ue.WheeledVehicleMovementComponent.md#rvosteeringstep)

#### Defined in

[ue/ue.d.ts:60538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60538)

___

### RVOThrottleStep

• **RVOThrottleStep**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOThrottleStep](ue_ue.WheeledVehicleMovementComponent.md#rvothrottlestep)

#### Defined in

[ue/ue.d.ts:60539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60539)

___

### RawBrakeInput

• **RawBrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RawBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#rawbrakeinput)

#### Defined in

[ue/ue.d.ts:60549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60549)

___

### RawSteeringInput

• **RawSteeringInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RawSteeringInput](ue_ue.WheeledVehicleMovementComponent.md#rawsteeringinput)

#### Defined in

[ue/ue.d.ts:60547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60547)

___

### RawThrottleInput

• **RawThrottleInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RawThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#rawthrottleinput)

#### Defined in

[ue/ue.d.ts:60548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60548)

___

### ReplicatedState

• **ReplicatedState**: [`ReplicatedVehicleState`](ue_ue.ReplicatedVehicleState.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ReplicatedState](ue_ue.WheeledVehicleMovementComponent.md#replicatedstate)

#### Defined in

[ue/ue.d.ts:60546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60546)

___

### SteeringInput

• **SteeringInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SteeringInput](ue_ue.WheeledVehicleMovementComponent.md#steeringinput)

#### Defined in

[ue/ue.d.ts:60550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60550)

___

### SteeringInputRate

• **SteeringInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SteeringInputRate](ue_ue.WheeledVehicleMovementComponent.md#steeringinputrate)

#### Defined in

[ue/ue.d.ts:60560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60560)

___

### StopThreshold

• **StopThreshold**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopThreshold](ue_ue.WheeledVehicleMovementComponent.md#stopthreshold)

#### Defined in

[ue/ue.d.ts:60555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60555)

___

### ThresholdLongitudinalSpeed

• **ThresholdLongitudinalSpeed**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ThresholdLongitudinalSpeed](ue_ue.WheeledVehicleMovementComponent.md#thresholdlongitudinalspeed)

#### Defined in

[ue/ue.d.ts:60531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60531)

___

### ThrottleInput

• **ThrottleInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#throttleinput)

#### Defined in

[ue/ue.d.ts:60551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60551)

___

### ThrottleInputRate

• **ThrottleInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ThrottleInputRate](ue_ue.WheeledVehicleMovementComponent.md#throttleinputrate)

#### Defined in

[ue/ue.d.ts:60557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60557)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[UCSModifiedProperties](ue_ue.WheeledVehicleMovementComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[UpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[UpdatedPrimitive](ue_ue.WheeledVehicleMovementComponent.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5391)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Velocity](ue_ue.WheeledVehicleMovementComponent.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5392)

___

### WheelSetups

• **WheelSetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WheelSetup`](ue_ue.WheelSetup.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[WheelSetups](ue_ue.WheeledVehicleMovementComponent.md#wheelsetups)

#### Defined in

[ue/ue.d.ts:60518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60518)

___

### Wheels

• **Wheels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VehicleWheel`](ue_ue.VehicleWheel.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Wheels](ue_ue.WheeledVehicleMovementComponent.md#wheels)

#### Defined in

[ue/ue.d.ts:60534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60534)

___

### WrongDirectionThreshold

• **WrongDirectionThreshold**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[WrongDirectionThreshold](ue_ue.WheeledVehicleMovementComponent.md#wrongdirectionthreshold)

#### Defined in

[ue/ue.d.ts:60556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60556)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_ActorComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_MovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5430)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_navmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5485)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_Object__](ue_ue.WheeledVehicleMovementComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_pawnmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5502)

___

### \_\_tid\_SimpleWheeledVehicleMovementComponent\_\_

• **\_\_tid\_SimpleWheeledVehicleMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60600)

___

### \_\_tid\_WheeledVehicleMovementComponent\_\_

• **\_\_tid\_WheeledVehicleMovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_WheeledVehicleMovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_wheeledvehiclemovementcomponent__)

#### Defined in

[ue/ue.d.ts:60588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60588)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoActivate](ue_ue.WheeledVehicleMovementComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.WheeledVehicleMovementComponent.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.WheeledVehicleMovementComponent.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5396)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bCanEverAffectNavigation](ue_ue.WheeledVehicleMovementComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.WheeledVehicleMovementComponent.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bConstrainToPlane](ue_ue.WheeledVehicleMovementComponent.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bCreatedByConstructionScript](ue_ue.WheeledVehicleMovementComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bDeprecatedSpringOffsetMode

• **bDeprecatedSpringOffsetMode**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bDeprecatedSpringOffsetMode](ue_ue.WheeledVehicleMovementComponent.md#bdeprecatedspringoffsetmode)

#### Defined in

[ue/ue.d.ts:60510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60510)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bEditableWhenInherited](ue_ue.WheeledVehicleMovementComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bInstanceComponent](ue_ue.WheeledVehicleMovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bIsActive](ue_ue.WheeledVehicleMovementComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bIsEditorOnly](ue_ue.WheeledVehicleMovementComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bIsVisualizationComponent](ue_ue.WheeledVehicleMovementComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bNetAddressable](ue_ue.WheeledVehicleMovementComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bRawGearDownInput

• **bRawGearDownInput**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bRawGearDownInput](ue_ue.WheeledVehicleMovementComponent.md#brawgeardowninput)

#### Defined in

[ue/ue.d.ts:60515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60515)

___

### bRawGearUpInput

• **bRawGearUpInput**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bRawGearUpInput](ue_ue.WheeledVehicleMovementComponent.md#brawgearupinput)

#### Defined in

[ue/ue.d.ts:60514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60514)

___

### bRawHandbrakeInput

• **bRawHandbrakeInput**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bRawHandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#brawhandbrakeinput)

#### Defined in

[ue/ue.d.ts:60513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60513)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bReplicates](ue_ue.WheeledVehicleMovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bReverseAsBrake

• **bReverseAsBrake**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bReverseAsBrake](ue_ue.WheeledVehicleMovementComponent.md#breverseasbrake)

#### Defined in

[ue/ue.d.ts:60511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60511)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.WheeledVehicleMovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5400)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bTickBeforeOwner](ue_ue.WheeledVehicleMovementComponent.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5397)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.WheeledVehicleMovementComponent.md#bupdatenavagentwithownerscollision)

#### Defined in

[ue/ue.d.ts:5469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5469)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.WheeledVehicleMovementComponent.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5395)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUseAccelerationForPaths](ue_ue.WheeledVehicleMovementComponent.md#buseaccelerationforpaths)

#### Defined in

[ue/ue.d.ts:5470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5470)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.WheeledVehicleMovementComponent.md#busefixedbrakingdistanceforpaths)

#### Defined in

[ue/ue.d.ts:5471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5471)

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUseRVOAvoidance](ue_ue.WheeledVehicleMovementComponent.md#buservoavoidance)

#### Defined in

[ue/ue.d.ts:60512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60512)

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bWasAvoidanceUpdated](ue_ue.WheeledVehicleMovementComponent.md#bwasavoidanceupdated)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Activate](ue_ue.WheeledVehicleMovementComponent.md#activate)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AddInputVector](ue_ue.WheeledVehicleMovementComponent.md#addinputvector)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AddTickPrerequisiteActor](ue_ue.WheeledVehicleMovementComponent.md#addtickprerequisiteactor)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.WheeledVehicleMovementComponent.md#addtickprerequisitecomponent)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ComponentHasTag](ue_ue.WheeledVehicleMovementComponent.md#componenthastag)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ConstrainDirectionToPlane](ue_ue.WheeledVehicleMovementComponent.md#constraindirectiontoplane)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ConstrainLocationToPlane](ue_ue.WheeledVehicleMovementComponent.md#constrainlocationtoplane)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ConstrainNormalToPlane](ue_ue.WheeledVehicleMovementComponent.md#constrainnormaltoplane)

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5406)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ConsumeInputVector](ue_ue.WheeledVehicleMovementComponent.md#consumeinputvector)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[CreateDefaultSubobject](ue_ue.WheeledVehicleMovementComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Deactivate](ue_ue.WheeledVehicleMovementComponent.md#deactivate)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ExecuteUbergraph](ue_ue.WheeledVehicleMovementComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetClass](ue_ue.WheeledVehicleMovementComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetComponentTickInterval](ue_ue.WheeledVehicleMovementComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetCurrentGear

▸ **GetCurrentGear**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetCurrentGear](ue_ue.WheeledVehicleMovementComponent.md#getcurrentgear)

#### Defined in

[ue/ue.d.ts:60562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60562)

___

### GetEngineMaxRotationSpeed

▸ **GetEngineMaxRotationSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetEngineMaxRotationSpeed](ue_ue.WheeledVehicleMovementComponent.md#getenginemaxrotationspeed)

#### Defined in

[ue/ue.d.ts:60563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60563)

___

### GetEngineRotationSpeed

▸ **GetEngineRotationSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetEngineRotationSpeed](ue_ue.WheeledVehicleMovementComponent.md#getenginerotationspeed)

#### Defined in

[ue/ue.d.ts:60564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60564)

___

### GetForwardSpeed

▸ **GetForwardSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetForwardSpeed](ue_ue.WheeledVehicleMovementComponent.md#getforwardspeed)

#### Defined in

[ue/ue.d.ts:60565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60565)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetGravityZ](ue_ue.WheeledVehicleMovementComponent.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5407)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetLastInputVector](ue_ue.WheeledVehicleMovementComponent.md#getlastinputvector)

#### Defined in

[ue/ue.d.ts:5493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5493)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5408)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetName](ue_ue.WheeledVehicleMovementComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetOuter](ue_ue.WheeledVehicleMovementComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetOwner](ue_ue.WheeledVehicleMovementComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPawnOwner](ue_ue.WheeledVehicleMovementComponent.md#getpawnowner)

#### Defined in

[ue/ue.d.ts:5494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5494)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPendingInputVector](ue_ue.WheeledVehicleMovementComponent.md#getpendinginputvector)

#### Defined in

[ue/ue.d.ts:5495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5495)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPhysicsVolume](ue_ue.WheeledVehicleMovementComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5412)

___

### GetTargetGear

▸ **GetTargetGear**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetTargetGear](ue_ue.WheeledVehicleMovementComponent.md#gettargetgear)

#### Defined in

[ue/ue.d.ts:60566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60566)

___

### GetUseAutoGears

▸ **GetUseAutoGears**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetUseAutoGears](ue_ue.WheeledVehicleMovementComponent.md#getuseautogears)

#### Defined in

[ue/ue.d.ts:60567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60567)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetWorld](ue_ue.WheeledVehicleMovementComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsActive](ue_ue.WheeledVehicleMovementComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsBeingDestroyed](ue_ue.WheeledVehicleMovementComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsComponentTickEnabled](ue_ue.WheeledVehicleMovementComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsCrouching](ue_ue.WheeledVehicleMovementComponent.md#iscrouching)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsExceedingMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#isexceedingmaxspeed)

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5413)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsFalling](ue_ue.WheeledVehicleMovementComponent.md#isfalling)

#### Defined in

[ue/ue.d.ts:5475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5475)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsFlying](ue_ue.WheeledVehicleMovementComponent.md#isflying)

#### Defined in

[ue/ue.d.ts:5476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5476)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsMoveInputIgnored](ue_ue.WheeledVehicleMovementComponent.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:5496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5496)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsMovingOnGround](ue_ue.WheeledVehicleMovementComponent.md#ismovingonground)

#### Defined in

[ue/ue.d.ts:5477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5477)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsSwimming](ue_ue.WheeledVehicleMovementComponent.md#isswimming)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_DestroyComponent](ue_ue.WheeledVehicleMovementComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_GetInputVector](ue_ue.WheeledVehicleMovementComponent.md#k2_getinputvector)

#### Defined in

[ue/ue.d.ts:5497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5497)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.WheeledVehicleMovementComponent.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#k2_getmodifiedmaxspeed)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_MoveUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#k2_moveupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5416)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OnRep_IsActive](ue_ue.WheeledVehicleMovementComponent.md#onrep_isactive)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PhysicsVolumeChanged](ue_ue.WheeledVehicleMovementComponent.md#physicsvolumechanged)

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ReceiveBeginPlay](ue_ue.WheeledVehicleMovementComponent.md#receivebeginplay)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ReceiveEndPlay](ue_ue.WheeledVehicleMovementComponent.md#receiveendplay)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ReceiveTick](ue_ue.WheeledVehicleMovementComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RegisterComponent](ue_ue.WheeledVehicleMovementComponent.md#registercomponent)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.WheeledVehicleMovementComponent.md#removetickprerequisiteactor)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.WheeledVehicleMovementComponent.md#removetickprerequisitecomponent)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ServerUpdateState](ue_ue.WheeledVehicleMovementComponent.md#serverupdatestate)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetActive](ue_ue.WheeledVehicleMovementComponent.md#setactive)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetAutoActivate](ue_ue.WheeledVehicleMovementComponent.md#setautoactivate)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetAvoidanceEnabled](ue_ue.WheeledVehicleMovementComponent.md#setavoidanceenabled)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetAvoidanceGroup](ue_ue.WheeledVehicleMovementComponent.md#setavoidancegroup)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetAvoidanceGroupMask](ue_ue.WheeledVehicleMovementComponent.md#setavoidancegroupmask)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#setbrakeinput)

#### Defined in

[ue/ue.d.ts:60572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60572)

___

### SetBrakeTorque

▸ **SetBrakeTorque**(`BrakeTorque`, `WheelIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BrakeTorque` | `number` |
| `WheelIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60593)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetComponentTickEnabled](ue_ue.WheeledVehicleMovementComponent.md#setcomponenttickenabled)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetComponentTickInterval](ue_ue.WheeledVehicleMovementComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

___

### SetDriveTorque

▸ **SetDriveTorque**(`DriveTorque`, `WheelIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DriveTorque` | `number` |
| `WheelIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60594)

___

### SetGearDown

▸ **SetGearDown**(`bNewGearDown`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewGearDown` | `boolean` |

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetGearDown](ue_ue.WheeledVehicleMovementComponent.md#setgeardown)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetGearUp](ue_ue.WheeledVehicleMovementComponent.md#setgearup)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetGroupsToAvoid](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoavoid)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetGroupsToAvoidMask](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoavoidmask)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetGroupsToIgnore](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoignore)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetGroupsToIgnoreMask](ue_ue.WheeledVehicleMovementComponent.md#setgroupstoignoremask)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetHandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#sethandbrakeinput)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetIsReplicated](ue_ue.WheeledVehicleMovementComponent.md#setisreplicated)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetPlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintaxissetting)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetPlaneConstraintEnabled](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintenabled)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetPlaneConstraintFromVectors](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintfromvectors)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetPlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintnormal)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetPlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#setplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5422)

___

### SetSteerAngle

▸ **SetSteerAngle**(`SteerAngle`, `WheelIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SteerAngle` | `number` |
| `WheelIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:60595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60595)

___

### SetSteeringInput

▸ **SetSteeringInput**(`Steering`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Steering` | `number` |

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetSteeringInput](ue_ue.WheeledVehicleMovementComponent.md#setsteeringinput)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetTargetGear](ue_ue.WheeledVehicleMovementComponent.md#settargetgear)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#setthrottleinput)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetTickGroup](ue_ue.WheeledVehicleMovementComponent.md#settickgroup)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetTickableWhenPaused](ue_ue.WheeledVehicleMovementComponent.md#settickablewhenpaused)

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

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#setupdatedcomponent)

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

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SetUseAutoGears](ue_ue.WheeledVehicleMovementComponent.md#setuseautogears)

#### Defined in

[ue/ue.d.ts:60583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60583)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.WheeledVehicleMovementComponent.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5424)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopActiveMovement](ue_ue.WheeledVehicleMovementComponent.md#stopactivemovement)

#### Defined in

[ue/ue.d.ts:5479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5479)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopMovementImmediately](ue_ue.WheeledVehicleMovementComponent.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5425)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopMovementKeepPathing](ue_ue.WheeledVehicleMovementComponent.md#stopmovementkeeppathing)

#### Defined in

[ue/ue.d.ts:5480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5480)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ToggleActive](ue_ue.WheeledVehicleMovementComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SimpleWheeledVehicleMovementComponent`](ue_ue.SimpleWheeledVehicleMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SimpleWheeledVehicleMovementComponent`](ue_ue.SimpleWheeledVehicleMovementComponent.md)

#### Overrides

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Find](ue_ue.WheeledVehicleMovementComponent.md#find)

#### Defined in

[ue/ue.d.ts:60597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60597)

___

### Load

▸ `Static` **Load**(`InName`): [`SimpleWheeledVehicleMovementComponent`](ue_ue.SimpleWheeledVehicleMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SimpleWheeledVehicleMovementComponent`](ue_ue.SimpleWheeledVehicleMovementComponent.md)

#### Overrides

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Load](ue_ue.WheeledVehicleMovementComponent.md#load)

#### Defined in

[ue/ue.d.ts:60598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60598)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StaticClass](ue_ue.WheeledVehicleMovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:60596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60596)
