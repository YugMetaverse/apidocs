[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FloatingPawnMovement

# Class: FloatingPawnMovement

[ue/ue](../modules/ue_ue.md).FloatingPawnMovement

## Hierarchy

- [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

  ↳ **`FloatingPawnMovement`**

  ↳↳ [`SpectatorPawnMovement`](ue_ue.SpectatorPawnMovement.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FloatingPawnMovement.md#constructor)

### Properties

- [Acceleration](ue_ue.FloatingPawnMovement.md#acceleration)
- [AssetUserData](ue_ue.FloatingPawnMovement.md#assetuserdata)
- [ComponentTags](ue_ue.FloatingPawnMovement.md#componenttags)
- [CreationMethod](ue_ue.FloatingPawnMovement.md#creationmethod)
- [Deceleration](ue_ue.FloatingPawnMovement.md#deceleration)
- [FixedPathBrakingDistance](ue_ue.FloatingPawnMovement.md#fixedpathbrakingdistance)
- [MaxSpeed](ue_ue.FloatingPawnMovement.md#maxspeed)
- [MovementState](ue_ue.FloatingPawnMovement.md#movementstate)
- [NavAgentProps](ue_ue.FloatingPawnMovement.md#navagentprops)
- [OnComponentActivated](ue_ue.FloatingPawnMovement.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.FloatingPawnMovement.md#oncomponentdeactivated)
- [PathFollowingComp](ue_ue.FloatingPawnMovement.md#pathfollowingcomp)
- [PawnOwner](ue_ue.FloatingPawnMovement.md#pawnowner)
- [PlaneConstraintAxisSetting](ue_ue.FloatingPawnMovement.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.FloatingPawnMovement.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.FloatingPawnMovement.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.FloatingPawnMovement.md#primarycomponenttick)
- [TurningBoost](ue_ue.FloatingPawnMovement.md#turningboost)
- [UCSModifiedProperties](ue_ue.FloatingPawnMovement.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.FloatingPawnMovement.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.FloatingPawnMovement.md#updatedprimitive)
- [Velocity](ue_ue.FloatingPawnMovement.md#velocity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.FloatingPawnMovement.md#__tid_actorcomponent__)
- [\_\_tid\_FloatingPawnMovement\_\_](ue_ue.FloatingPawnMovement.md#__tid_floatingpawnmovement__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.FloatingPawnMovement.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.FloatingPawnMovement.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.FloatingPawnMovement.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.FloatingPawnMovement.md#__tid_pawnmovementcomponent__)
- [bAutoActivate](ue_ue.FloatingPawnMovement.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.FloatingPawnMovement.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.FloatingPawnMovement.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.FloatingPawnMovement.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.FloatingPawnMovement.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.FloatingPawnMovement.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.FloatingPawnMovement.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.FloatingPawnMovement.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.FloatingPawnMovement.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.FloatingPawnMovement.md#binstancecomponent)
- [bIsActive](ue_ue.FloatingPawnMovement.md#bisactive)
- [bIsEditorOnly](ue_ue.FloatingPawnMovement.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.FloatingPawnMovement.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.FloatingPawnMovement.md#bnetaddressable)
- [bPositionCorrected](ue_ue.FloatingPawnMovement.md#bpositioncorrected)
- [bReplicates](ue_ue.FloatingPawnMovement.md#breplicates)
- [bSnapToPlaneAtStart](ue_ue.FloatingPawnMovement.md#bsnaptoplaneatstart)
- [bTickBeforeOwner](ue_ue.FloatingPawnMovement.md#btickbeforeowner)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.FloatingPawnMovement.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.FloatingPawnMovement.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.FloatingPawnMovement.md#buseaccelerationforpaths)
- [bUseFixedBrakingDistanceForPaths](ue_ue.FloatingPawnMovement.md#busefixedbrakingdistanceforpaths)

### Methods

- [Activate](ue_ue.FloatingPawnMovement.md#activate)
- [AddInputVector](ue_ue.FloatingPawnMovement.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.FloatingPawnMovement.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.FloatingPawnMovement.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.FloatingPawnMovement.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.FloatingPawnMovement.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.FloatingPawnMovement.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.FloatingPawnMovement.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.FloatingPawnMovement.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.FloatingPawnMovement.md#createdefaultsubobject)
- [Deactivate](ue_ue.FloatingPawnMovement.md#deactivate)
- [ExecuteUbergraph](ue_ue.FloatingPawnMovement.md#executeubergraph)
- [GetClass](ue_ue.FloatingPawnMovement.md#getclass)
- [GetComponentTickInterval](ue_ue.FloatingPawnMovement.md#getcomponenttickinterval)
- [GetGravityZ](ue_ue.FloatingPawnMovement.md#getgravityz)
- [GetLastInputVector](ue_ue.FloatingPawnMovement.md#getlastinputvector)
- [GetMaxSpeed](ue_ue.FloatingPawnMovement.md#getmaxspeed)
- [GetName](ue_ue.FloatingPawnMovement.md#getname)
- [GetOuter](ue_ue.FloatingPawnMovement.md#getouter)
- [GetOwner](ue_ue.FloatingPawnMovement.md#getowner)
- [GetPawnOwner](ue_ue.FloatingPawnMovement.md#getpawnowner)
- [GetPendingInputVector](ue_ue.FloatingPawnMovement.md#getpendinginputvector)
- [GetPhysicsVolume](ue_ue.FloatingPawnMovement.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.FloatingPawnMovement.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.FloatingPawnMovement.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.FloatingPawnMovement.md#getplaneconstraintorigin)
- [GetWorld](ue_ue.FloatingPawnMovement.md#getworld)
- [IsActive](ue_ue.FloatingPawnMovement.md#isactive)
- [IsBeingDestroyed](ue_ue.FloatingPawnMovement.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.FloatingPawnMovement.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.FloatingPawnMovement.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.FloatingPawnMovement.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.FloatingPawnMovement.md#isfalling)
- [IsFlying](ue_ue.FloatingPawnMovement.md#isflying)
- [IsMoveInputIgnored](ue_ue.FloatingPawnMovement.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.FloatingPawnMovement.md#ismovingonground)
- [IsSwimming](ue_ue.FloatingPawnMovement.md#isswimming)
- [K2\_DestroyComponent](ue_ue.FloatingPawnMovement.md#k2_destroycomponent)
- [K2\_GetInputVector](ue_ue.FloatingPawnMovement.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.FloatingPawnMovement.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.FloatingPawnMovement.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.FloatingPawnMovement.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.FloatingPawnMovement.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.FloatingPawnMovement.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.FloatingPawnMovement.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.FloatingPawnMovement.md#receiveendplay)
- [ReceiveTick](ue_ue.FloatingPawnMovement.md#receivetick)
- [RegisterComponent](ue_ue.FloatingPawnMovement.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.FloatingPawnMovement.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.FloatingPawnMovement.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.FloatingPawnMovement.md#setactive)
- [SetAutoActivate](ue_ue.FloatingPawnMovement.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.FloatingPawnMovement.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.FloatingPawnMovement.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.FloatingPawnMovement.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.FloatingPawnMovement.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.FloatingPawnMovement.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.FloatingPawnMovement.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.FloatingPawnMovement.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.FloatingPawnMovement.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.FloatingPawnMovement.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.FloatingPawnMovement.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.FloatingPawnMovement.md#setupdatedcomponent)
- [SnapUpdatedComponentToPlane](ue_ue.FloatingPawnMovement.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.FloatingPawnMovement.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.FloatingPawnMovement.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.FloatingPawnMovement.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.FloatingPawnMovement.md#toggleactive)
- [Find](ue_ue.FloatingPawnMovement.md#find)
- [Load](ue_ue.FloatingPawnMovement.md#load)
- [StaticClass](ue_ue.FloatingPawnMovement.md#staticclass)

## Constructors

### constructor

• **new FloatingPawnMovement**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[constructor](ue_ue.PawnMovementComponent.md#constructor)

## Properties

### Acceleration

• **Acceleration**: `number`

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AssetUserData](ue_ue.PawnMovementComponent.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ComponentTags](ue_ue.PawnMovementComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[CreationMethod](ue_ue.PawnMovementComponent.md#creationmethod)

___

### Deceleration

• **Deceleration**: `number`

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[FixedPathBrakingDistance](ue_ue.PawnMovementComponent.md#fixedpathbrakingdistance)

___

### MaxSpeed

• **MaxSpeed**: `number`

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[MovementState](ue_ue.PawnMovementComponent.md#movementstate)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[NavAgentProps](ue_ue.PawnMovementComponent.md#navagentprops)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentActivated](ue_ue.PawnMovementComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentDeactivated](ue_ue.PawnMovementComponent.md#oncomponentdeactivated)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PathFollowingComp](ue_ue.PawnMovementComponent.md#pathfollowingcomp)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PawnOwner](ue_ue.PawnMovementComponent.md#pawnowner)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#planeconstraintaxissetting)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintNormal](ue_ue.PawnMovementComponent.md#planeconstraintnormal)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#planeconstraintorigin)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PrimaryComponentTick](ue_ue.PawnMovementComponent.md#primarycomponenttick)

___

### TurningBoost

• **TurningBoost**: `number`

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UCSModifiedProperties](ue_ue.PawnMovementComponent.md#ucsmodifiedproperties)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedComponent](ue_ue.PawnMovementComponent.md#updatedcomponent)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedPrimitive](ue_ue.PawnMovementComponent.md#updatedprimitive)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Velocity](ue_ue.PawnMovementComponent.md#velocity)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_ActorComponent__](ue_ue.PawnMovementComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_FloatingPawnMovement\_\_

• **\_\_tid\_FloatingPawnMovement\_\_**: `boolean`

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_MovementComponent__](ue_ue.PawnMovementComponent.md#__tid_movementcomponent__)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_navmovementcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_Object__](ue_ue.PawnMovementComponent.md#__tid_object__)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_pawnmovementcomponent__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoActivate](ue_ue.PawnMovementComponent.md#bautoactivate)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.PawnMovementComponent.md#bautoregisterphysicsvolumeupdates)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.PawnMovementComponent.md#bautoregisterupdatedcomponent)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.PawnMovementComponent.md#bautoupdatetickregistration)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCanEverAffectNavigation](ue_ue.PawnMovementComponent.md#bcaneveraffectnavigation)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.PawnMovementComponent.md#bcomponentshouldupdatephysicsvolume)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bConstrainToPlane](ue_ue.PawnMovementComponent.md#bconstraintoplane)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCreatedByConstructionScript](ue_ue.PawnMovementComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bEditableWhenInherited](ue_ue.PawnMovementComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bInstanceComponent](ue_ue.PawnMovementComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsActive](ue_ue.PawnMovementComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsEditorOnly](ue_ue.PawnMovementComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsVisualizationComponent](ue_ue.PawnMovementComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bNetAddressable](ue_ue.PawnMovementComponent.md#bnetaddressable)

___

### bPositionCorrected

• **bPositionCorrected**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bReplicates](ue_ue.PawnMovementComponent.md#breplicates)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.PawnMovementComponent.md#bsnaptoplaneatstart)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bTickBeforeOwner](ue_ue.PawnMovementComponent.md#btickbeforeowner)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.PawnMovementComponent.md#bupdatenavagentwithownerscollision)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.PawnMovementComponent.md#bupdateonlyifrendered)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseAccelerationForPaths](ue_ue.PawnMovementComponent.md#buseaccelerationforpaths)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.PawnMovementComponent.md#busefixedbrakingdistanceforpaths)

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

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConsumeInputVector](ue_ue.PawnMovementComponent.md#consumeinputvector)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Deactivate](ue_ue.PawnMovementComponent.md#deactivate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetClass](ue_ue.PawnMovementComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetComponentTickInterval](ue_ue.PawnMovementComponent.md#getcomponenttickinterval)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetGravityZ](ue_ue.PawnMovementComponent.md#getgravityz)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetLastInputVector](ue_ue.PawnMovementComponent.md#getlastinputvector)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetMaxSpeed](ue_ue.PawnMovementComponent.md#getmaxspeed)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetName](ue_ue.PawnMovementComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOuter](ue_ue.PawnMovementComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOwner](ue_ue.PawnMovementComponent.md#getowner)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPawnOwner](ue_ue.PawnMovementComponent.md#getpawnowner)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPendingInputVector](ue_ue.PawnMovementComponent.md#getpendinginputvector)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPhysicsVolume](ue_ue.PawnMovementComponent.md#getphysicsvolume)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#getplaneconstraintaxissetting)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#getplaneconstraintnormal)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#getplaneconstraintorigin)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetWorld](ue_ue.PawnMovementComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsActive](ue_ue.PawnMovementComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsBeingDestroyed](ue_ue.PawnMovementComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsComponentTickEnabled](ue_ue.PawnMovementComponent.md#iscomponenttickenabled)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsCrouching](ue_ue.PawnMovementComponent.md#iscrouching)

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

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFalling](ue_ue.PawnMovementComponent.md#isfalling)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFlying](ue_ue.PawnMovementComponent.md#isflying)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMoveInputIgnored](ue_ue.PawnMovementComponent.md#ismoveinputignored)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMovingOnGround](ue_ue.PawnMovementComponent.md#ismovingonground)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsSwimming](ue_ue.PawnMovementComponent.md#isswimming)

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

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetInputVector](ue_ue.PawnMovementComponent.md#k2_getinputvector)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.PawnMovementComponent.md#k2_getmaxspeedmodifier)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.PawnMovementComponent.md#k2_getmodifiedmaxspeed)

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

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnRep_IsActive](ue_ue.PawnMovementComponent.md#onrep_isactive)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveBeginPlay](ue_ue.PawnMovementComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RegisterComponent](ue_ue.PawnMovementComponent.md#registercomponent)

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

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.PawnMovementComponent.md#snapupdatedcomponenttoplane)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopActiveMovement](ue_ue.PawnMovementComponent.md#stopactivemovement)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementImmediately](ue_ue.PawnMovementComponent.md#stopmovementimmediately)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementKeepPathing](ue_ue.PawnMovementComponent.md#stopmovementkeeppathing)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ToggleActive](ue_ue.PawnMovementComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FloatingPawnMovement`](ue_ue.FloatingPawnMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FloatingPawnMovement`](ue_ue.FloatingPawnMovement.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Find](ue_ue.PawnMovementComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FloatingPawnMovement`](ue_ue.FloatingPawnMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FloatingPawnMovement`](ue_ue.FloatingPawnMovement.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Load](ue_ue.PawnMovementComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StaticClass](ue_ue.PawnMovementComponent.md#staticclass)
