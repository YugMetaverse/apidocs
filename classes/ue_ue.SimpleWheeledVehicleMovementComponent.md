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

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AssetUserData](ue_ue.WheeledVehicleMovementComponent.md#assetuserdata)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceConsiderationRadius](ue_ue.WheeledVehicleMovementComponent.md#avoidanceconsiderationradius)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceGroup](ue_ue.WheeledVehicleMovementComponent.md#avoidancegroup)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceUID](ue_ue.WheeledVehicleMovementComponent.md#avoidanceuid)

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[AvoidanceWeight](ue_ue.WheeledVehicleMovementComponent.md#avoidanceweight)

___

### BrakeInput

• **BrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[BrakeInput](ue_ue.WheeledVehicleMovementComponent.md#brakeinput)

___

### BrakeInputRate

• **BrakeInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[BrakeInputRate](ue_ue.WheeledVehicleMovementComponent.md#brakeinputrate)

___

### ChassisHeight

• **ChassisHeight**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ChassisHeight](ue_ue.WheeledVehicleMovementComponent.md#chassisheight)

___

### ChassisWidth

• **ChassisWidth**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ChassisWidth](ue_ue.WheeledVehicleMovementComponent.md#chassiswidth)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ComponentTags](ue_ue.WheeledVehicleMovementComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[CreationMethod](ue_ue.WheeledVehicleMovementComponent.md#creationmethod)

___

### DebugDragMagnitude

• **DebugDragMagnitude**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[DebugDragMagnitude](ue_ue.WheeledVehicleMovementComponent.md#debugdragmagnitude)

___

### DragArea

• **DragArea**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[DragArea](ue_ue.WheeledVehicleMovementComponent.md#dragarea)

___

### DragCoefficient

• **DragCoefficient**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[DragCoefficient](ue_ue.WheeledVehicleMovementComponent.md#dragcoefficient)

___

### EstimatedMaxEngineSpeed

• **EstimatedMaxEngineSpeed**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[EstimatedMaxEngineSpeed](ue_ue.WheeledVehicleMovementComponent.md#estimatedmaxenginespeed)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[FixedPathBrakingDistance](ue_ue.WheeledVehicleMovementComponent.md#fixedpathbrakingdistance)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GroupsToAvoid](ue_ue.WheeledVehicleMovementComponent.md#groupstoavoid)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GroupsToIgnore](ue_ue.WheeledVehicleMovementComponent.md#groupstoignore)

___

### HandbrakeInput

• **HandbrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[HandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#handbrakeinput)

___

### HandbrakeInputRate

• **HandbrakeInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[HandbrakeInputRate](ue_ue.WheeledVehicleMovementComponent.md#handbrakeinputrate)

___

### HighForwardSpeedSubStepCount

• **HighForwardSpeedSubStepCount**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[HighForwardSpeedSubStepCount](ue_ue.WheeledVehicleMovementComponent.md#highforwardspeedsubstepcount)

___

### IdleBrakeInput

• **IdleBrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IdleBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#idlebrakeinput)

___

### InertiaTensorScale

• **InertiaTensorScale**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[InertiaTensorScale](ue_ue.WheeledVehicleMovementComponent.md#inertiatensorscale)

___

### LowForwardSpeedSubStepCount

• **LowForwardSpeedSubStepCount**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[LowForwardSpeedSubStepCount](ue_ue.WheeledVehicleMovementComponent.md#lowforwardspeedsubstepcount)

___

### Mass

• **Mass**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Mass](ue_ue.WheeledVehicleMovementComponent.md#mass)

___

### MaxEngineRPM

• **MaxEngineRPM**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MaxEngineRPM](ue_ue.WheeledVehicleMovementComponent.md#maxenginerpm)

___

### MaxNormalizedTireLoad

• **MaxNormalizedTireLoad**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MaxNormalizedTireLoad](ue_ue.WheeledVehicleMovementComponent.md#maxnormalizedtireload)

___

### MaxNormalizedTireLoadFiltered

• **MaxNormalizedTireLoadFiltered**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MaxNormalizedTireLoadFiltered](ue_ue.WheeledVehicleMovementComponent.md#maxnormalizedtireloadfiltered)

___

### MinNormalizedTireLoad

• **MinNormalizedTireLoad**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MinNormalizedTireLoad](ue_ue.WheeledVehicleMovementComponent.md#minnormalizedtireload)

___

### MinNormalizedTireLoadFiltered

• **MinNormalizedTireLoadFiltered**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MinNormalizedTireLoadFiltered](ue_ue.WheeledVehicleMovementComponent.md#minnormalizedtireloadfiltered)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[MovementState](ue_ue.WheeledVehicleMovementComponent.md#movementstate)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[NavAgentProps](ue_ue.WheeledVehicleMovementComponent.md#navagentprops)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OnComponentActivated](ue_ue.WheeledVehicleMovementComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OnComponentDeactivated](ue_ue.WheeledVehicleMovementComponent.md#oncomponentdeactivated)

___

### OverrideController

• **OverrideController**: [`Controller`](ue_ue.Controller.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OverrideController](ue_ue.WheeledVehicleMovementComponent.md#overridecontroller)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PathFollowingComp](ue_ue.WheeledVehicleMovementComponent.md#pathfollowingcomp)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PawnOwner](ue_ue.WheeledVehicleMovementComponent.md#pawnowner)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PendingLaunchVelocity](ue_ue.WheeledVehicleMovementComponent.md#pendinglaunchvelocity)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintaxissetting)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintnormal)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#planeconstraintorigin)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[PrimaryComponentTick](ue_ue.WheeledVehicleMovementComponent.md#primarycomponenttick)

___

### RVOAvoidanceHeight

• **RVOAvoidanceHeight**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOAvoidanceHeight](ue_ue.WheeledVehicleMovementComponent.md#rvoavoidanceheight)

___

### RVOAvoidanceRadius

• **RVOAvoidanceRadius**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOAvoidanceRadius](ue_ue.WheeledVehicleMovementComponent.md#rvoavoidanceradius)

___

### RVOSteeringStep

• **RVOSteeringStep**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOSteeringStep](ue_ue.WheeledVehicleMovementComponent.md#rvosteeringstep)

___

### RVOThrottleStep

• **RVOThrottleStep**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RVOThrottleStep](ue_ue.WheeledVehicleMovementComponent.md#rvothrottlestep)

___

### RawBrakeInput

• **RawBrakeInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RawBrakeInput](ue_ue.WheeledVehicleMovementComponent.md#rawbrakeinput)

___

### RawSteeringInput

• **RawSteeringInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RawSteeringInput](ue_ue.WheeledVehicleMovementComponent.md#rawsteeringinput)

___

### RawThrottleInput

• **RawThrottleInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RawThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#rawthrottleinput)

___

### ReplicatedState

• **ReplicatedState**: [`ReplicatedVehicleState`](ue_ue.ReplicatedVehicleState.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ReplicatedState](ue_ue.WheeledVehicleMovementComponent.md#replicatedstate)

___

### SteeringInput

• **SteeringInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SteeringInput](ue_ue.WheeledVehicleMovementComponent.md#steeringinput)

___

### SteeringInputRate

• **SteeringInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SteeringInputRate](ue_ue.WheeledVehicleMovementComponent.md#steeringinputrate)

___

### StopThreshold

• **StopThreshold**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopThreshold](ue_ue.WheeledVehicleMovementComponent.md#stopthreshold)

___

### ThresholdLongitudinalSpeed

• **ThresholdLongitudinalSpeed**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ThresholdLongitudinalSpeed](ue_ue.WheeledVehicleMovementComponent.md#thresholdlongitudinalspeed)

___

### ThrottleInput

• **ThrottleInput**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ThrottleInput](ue_ue.WheeledVehicleMovementComponent.md#throttleinput)

___

### ThrottleInputRate

• **ThrottleInputRate**: [`VehicleInputRate`](ue_ue.VehicleInputRate.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ThrottleInputRate](ue_ue.WheeledVehicleMovementComponent.md#throttleinputrate)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[UCSModifiedProperties](ue_ue.WheeledVehicleMovementComponent.md#ucsmodifiedproperties)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[UpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#updatedcomponent)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[UpdatedPrimitive](ue_ue.WheeledVehicleMovementComponent.md#updatedprimitive)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Velocity](ue_ue.WheeledVehicleMovementComponent.md#velocity)

___

### WheelSetups

• **WheelSetups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WheelSetup`](ue_ue.WheelSetup.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[WheelSetups](ue_ue.WheeledVehicleMovementComponent.md#wheelsetups)

___

### Wheels

• **Wheels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VehicleWheel`](ue_ue.VehicleWheel.md)\>

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Wheels](ue_ue.WheeledVehicleMovementComponent.md#wheels)

___

### WrongDirectionThreshold

• **WrongDirectionThreshold**: `number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[WrongDirectionThreshold](ue_ue.WheeledVehicleMovementComponent.md#wrongdirectionthreshold)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_ActorComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_MovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_movementcomponent__)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_navmovementcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_Object__](ue_ue.WheeledVehicleMovementComponent.md#__tid_object__)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_pawnmovementcomponent__)

___

### \_\_tid\_SimpleWheeledVehicleMovementComponent\_\_

• **\_\_tid\_SimpleWheeledVehicleMovementComponent\_\_**: `boolean`

___

### \_\_tid\_WheeledVehicleMovementComponent\_\_

• **\_\_tid\_WheeledVehicleMovementComponent\_\_**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[__tid_WheeledVehicleMovementComponent__](ue_ue.WheeledVehicleMovementComponent.md#__tid_wheeledvehiclemovementcomponent__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoActivate](ue_ue.WheeledVehicleMovementComponent.md#bautoactivate)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.WheeledVehicleMovementComponent.md#bautoregisterphysicsvolumeupdates)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.WheeledVehicleMovementComponent.md#bautoregisterupdatedcomponent)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.WheeledVehicleMovementComponent.md#bautoupdatetickregistration)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bCanEverAffectNavigation](ue_ue.WheeledVehicleMovementComponent.md#bcaneveraffectnavigation)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.WheeledVehicleMovementComponent.md#bcomponentshouldupdatephysicsvolume)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bConstrainToPlane](ue_ue.WheeledVehicleMovementComponent.md#bconstraintoplane)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bCreatedByConstructionScript](ue_ue.WheeledVehicleMovementComponent.md#bcreatedbyconstructionscript)

___

### bDeprecatedSpringOffsetMode

• **bDeprecatedSpringOffsetMode**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bDeprecatedSpringOffsetMode](ue_ue.WheeledVehicleMovementComponent.md#bdeprecatedspringoffsetmode)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bEditableWhenInherited](ue_ue.WheeledVehicleMovementComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bInstanceComponent](ue_ue.WheeledVehicleMovementComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bIsActive](ue_ue.WheeledVehicleMovementComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bIsEditorOnly](ue_ue.WheeledVehicleMovementComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bIsVisualizationComponent](ue_ue.WheeledVehicleMovementComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bNetAddressable](ue_ue.WheeledVehicleMovementComponent.md#bnetaddressable)

___

### bRawGearDownInput

• **bRawGearDownInput**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bRawGearDownInput](ue_ue.WheeledVehicleMovementComponent.md#brawgeardowninput)

___

### bRawGearUpInput

• **bRawGearUpInput**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bRawGearUpInput](ue_ue.WheeledVehicleMovementComponent.md#brawgearupinput)

___

### bRawHandbrakeInput

• **bRawHandbrakeInput**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bRawHandbrakeInput](ue_ue.WheeledVehicleMovementComponent.md#brawhandbrakeinput)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bReplicates](ue_ue.WheeledVehicleMovementComponent.md#breplicates)

___

### bReverseAsBrake

• **bReverseAsBrake**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bReverseAsBrake](ue_ue.WheeledVehicleMovementComponent.md#breverseasbrake)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.WheeledVehicleMovementComponent.md#bsnaptoplaneatstart)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bTickBeforeOwner](ue_ue.WheeledVehicleMovementComponent.md#btickbeforeowner)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.WheeledVehicleMovementComponent.md#bupdatenavagentwithownerscollision)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.WheeledVehicleMovementComponent.md#bupdateonlyifrendered)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUseAccelerationForPaths](ue_ue.WheeledVehicleMovementComponent.md#buseaccelerationforpaths)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.WheeledVehicleMovementComponent.md#busefixedbrakingdistanceforpaths)

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bUseRVOAvoidance](ue_ue.WheeledVehicleMovementComponent.md#buservoavoidance)

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[bWasAvoidanceUpdated](ue_ue.WheeledVehicleMovementComponent.md#bwasavoidanceupdated)

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

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ConsumeInputVector](ue_ue.WheeledVehicleMovementComponent.md#consumeinputvector)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[Deactivate](ue_ue.WheeledVehicleMovementComponent.md#deactivate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetClass](ue_ue.WheeledVehicleMovementComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetComponentTickInterval](ue_ue.WheeledVehicleMovementComponent.md#getcomponenttickinterval)

___

### GetCurrentGear

▸ **GetCurrentGear**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetCurrentGear](ue_ue.WheeledVehicleMovementComponent.md#getcurrentgear)

___

### GetEngineMaxRotationSpeed

▸ **GetEngineMaxRotationSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetEngineMaxRotationSpeed](ue_ue.WheeledVehicleMovementComponent.md#getenginemaxrotationspeed)

___

### GetEngineRotationSpeed

▸ **GetEngineRotationSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetEngineRotationSpeed](ue_ue.WheeledVehicleMovementComponent.md#getenginerotationspeed)

___

### GetForwardSpeed

▸ **GetForwardSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetForwardSpeed](ue_ue.WheeledVehicleMovementComponent.md#getforwardspeed)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetGravityZ](ue_ue.WheeledVehicleMovementComponent.md#getgravityz)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetLastInputVector](ue_ue.WheeledVehicleMovementComponent.md#getlastinputvector)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#getmaxspeed)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetName](ue_ue.WheeledVehicleMovementComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetOuter](ue_ue.WheeledVehicleMovementComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetOwner](ue_ue.WheeledVehicleMovementComponent.md#getowner)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPawnOwner](ue_ue.WheeledVehicleMovementComponent.md#getpawnowner)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPendingInputVector](ue_ue.WheeledVehicleMovementComponent.md#getpendinginputvector)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPhysicsVolume](ue_ue.WheeledVehicleMovementComponent.md#getphysicsvolume)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintaxissetting)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintnormal)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.WheeledVehicleMovementComponent.md#getplaneconstraintorigin)

___

### GetTargetGear

▸ **GetTargetGear**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetTargetGear](ue_ue.WheeledVehicleMovementComponent.md#gettargetgear)

___

### GetUseAutoGears

▸ **GetUseAutoGears**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetUseAutoGears](ue_ue.WheeledVehicleMovementComponent.md#getuseautogears)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[GetWorld](ue_ue.WheeledVehicleMovementComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsActive](ue_ue.WheeledVehicleMovementComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsBeingDestroyed](ue_ue.WheeledVehicleMovementComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsComponentTickEnabled](ue_ue.WheeledVehicleMovementComponent.md#iscomponenttickenabled)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsCrouching](ue_ue.WheeledVehicleMovementComponent.md#iscrouching)

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

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsFalling](ue_ue.WheeledVehicleMovementComponent.md#isfalling)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsFlying](ue_ue.WheeledVehicleMovementComponent.md#isflying)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsMoveInputIgnored](ue_ue.WheeledVehicleMovementComponent.md#ismoveinputignored)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsMovingOnGround](ue_ue.WheeledVehicleMovementComponent.md#ismovingonground)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[IsSwimming](ue_ue.WheeledVehicleMovementComponent.md#isswimming)

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

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_GetInputVector](ue_ue.WheeledVehicleMovementComponent.md#k2_getinputvector)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.WheeledVehicleMovementComponent.md#k2_getmaxspeedmodifier)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.WheeledVehicleMovementComponent.md#k2_getmodifiedmaxspeed)

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

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[OnRep_IsActive](ue_ue.WheeledVehicleMovementComponent.md#onrep_isactive)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ReceiveBeginPlay](ue_ue.WheeledVehicleMovementComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[RegisterComponent](ue_ue.WheeledVehicleMovementComponent.md#registercomponent)

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

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.WheeledVehicleMovementComponent.md#snapupdatedcomponenttoplane)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopActiveMovement](ue_ue.WheeledVehicleMovementComponent.md#stopactivemovement)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopMovementImmediately](ue_ue.WheeledVehicleMovementComponent.md#stopmovementimmediately)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StopMovementKeepPathing](ue_ue.WheeledVehicleMovementComponent.md#stopmovementkeeppathing)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[ToggleActive](ue_ue.WheeledVehicleMovementComponent.md#toggleactive)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[WheeledVehicleMovementComponent](ue_ue.WheeledVehicleMovementComponent.md).[StaticClass](ue_ue.WheeledVehicleMovementComponent.md#staticclass)
