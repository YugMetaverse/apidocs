[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SpectatorPawnMovement

# Class: SpectatorPawnMovement

[ue/ue](../modules/ue_ue.md).SpectatorPawnMovement

## Hierarchy

- [`FloatingPawnMovement`](ue_ue.FloatingPawnMovement.md)

  ↳ **`SpectatorPawnMovement`**

## Table of contents

### Constructors

- [constructor](ue_ue.SpectatorPawnMovement.md#constructor)

### Properties

- [Acceleration](ue_ue.SpectatorPawnMovement.md#acceleration)
- [AssetUserData](ue_ue.SpectatorPawnMovement.md#assetuserdata)
- [ComponentTags](ue_ue.SpectatorPawnMovement.md#componenttags)
- [CreationMethod](ue_ue.SpectatorPawnMovement.md#creationmethod)
- [Deceleration](ue_ue.SpectatorPawnMovement.md#deceleration)
- [FixedPathBrakingDistance](ue_ue.SpectatorPawnMovement.md#fixedpathbrakingdistance)
- [MaxSpeed](ue_ue.SpectatorPawnMovement.md#maxspeed)
- [MovementState](ue_ue.SpectatorPawnMovement.md#movementstate)
- [NavAgentProps](ue_ue.SpectatorPawnMovement.md#navagentprops)
- [OnComponentActivated](ue_ue.SpectatorPawnMovement.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.SpectatorPawnMovement.md#oncomponentdeactivated)
- [PathFollowingComp](ue_ue.SpectatorPawnMovement.md#pathfollowingcomp)
- [PawnOwner](ue_ue.SpectatorPawnMovement.md#pawnowner)
- [PlaneConstraintAxisSetting](ue_ue.SpectatorPawnMovement.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.SpectatorPawnMovement.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.SpectatorPawnMovement.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.SpectatorPawnMovement.md#primarycomponenttick)
- [TurningBoost](ue_ue.SpectatorPawnMovement.md#turningboost)
- [UCSModifiedProperties](ue_ue.SpectatorPawnMovement.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.SpectatorPawnMovement.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.SpectatorPawnMovement.md#updatedprimitive)
- [Velocity](ue_ue.SpectatorPawnMovement.md#velocity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.SpectatorPawnMovement.md#__tid_actorcomponent__)
- [\_\_tid\_FloatingPawnMovement\_\_](ue_ue.SpectatorPawnMovement.md#__tid_floatingpawnmovement__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.SpectatorPawnMovement.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.SpectatorPawnMovement.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.SpectatorPawnMovement.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.SpectatorPawnMovement.md#__tid_pawnmovementcomponent__)
- [\_\_tid\_SpectatorPawnMovement\_\_](ue_ue.SpectatorPawnMovement.md#__tid_spectatorpawnmovement__)
- [bAutoActivate](ue_ue.SpectatorPawnMovement.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.SpectatorPawnMovement.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.SpectatorPawnMovement.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.SpectatorPawnMovement.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.SpectatorPawnMovement.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.SpectatorPawnMovement.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.SpectatorPawnMovement.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.SpectatorPawnMovement.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.SpectatorPawnMovement.md#beditablewheninherited)
- [bIgnoreTimeDilation](ue_ue.SpectatorPawnMovement.md#bignoretimedilation)
- [bInstanceComponent](ue_ue.SpectatorPawnMovement.md#binstancecomponent)
- [bIsActive](ue_ue.SpectatorPawnMovement.md#bisactive)
- [bIsEditorOnly](ue_ue.SpectatorPawnMovement.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.SpectatorPawnMovement.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.SpectatorPawnMovement.md#bnetaddressable)
- [bPositionCorrected](ue_ue.SpectatorPawnMovement.md#bpositioncorrected)
- [bReplicates](ue_ue.SpectatorPawnMovement.md#breplicates)
- [bSnapToPlaneAtStart](ue_ue.SpectatorPawnMovement.md#bsnaptoplaneatstart)
- [bTickBeforeOwner](ue_ue.SpectatorPawnMovement.md#btickbeforeowner)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.SpectatorPawnMovement.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.SpectatorPawnMovement.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.SpectatorPawnMovement.md#buseaccelerationforpaths)
- [bUseFixedBrakingDistanceForPaths](ue_ue.SpectatorPawnMovement.md#busefixedbrakingdistanceforpaths)

### Methods

- [Activate](ue_ue.SpectatorPawnMovement.md#activate)
- [AddInputVector](ue_ue.SpectatorPawnMovement.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.SpectatorPawnMovement.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SpectatorPawnMovement.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.SpectatorPawnMovement.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.SpectatorPawnMovement.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.SpectatorPawnMovement.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.SpectatorPawnMovement.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.SpectatorPawnMovement.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.SpectatorPawnMovement.md#createdefaultsubobject)
- [Deactivate](ue_ue.SpectatorPawnMovement.md#deactivate)
- [ExecuteUbergraph](ue_ue.SpectatorPawnMovement.md#executeubergraph)
- [GetClass](ue_ue.SpectatorPawnMovement.md#getclass)
- [GetComponentTickInterval](ue_ue.SpectatorPawnMovement.md#getcomponenttickinterval)
- [GetGravityZ](ue_ue.SpectatorPawnMovement.md#getgravityz)
- [GetLastInputVector](ue_ue.SpectatorPawnMovement.md#getlastinputvector)
- [GetMaxSpeed](ue_ue.SpectatorPawnMovement.md#getmaxspeed)
- [GetName](ue_ue.SpectatorPawnMovement.md#getname)
- [GetOuter](ue_ue.SpectatorPawnMovement.md#getouter)
- [GetOwner](ue_ue.SpectatorPawnMovement.md#getowner)
- [GetPawnOwner](ue_ue.SpectatorPawnMovement.md#getpawnowner)
- [GetPendingInputVector](ue_ue.SpectatorPawnMovement.md#getpendinginputvector)
- [GetPhysicsVolume](ue_ue.SpectatorPawnMovement.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.SpectatorPawnMovement.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.SpectatorPawnMovement.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.SpectatorPawnMovement.md#getplaneconstraintorigin)
- [GetWorld](ue_ue.SpectatorPawnMovement.md#getworld)
- [IsActive](ue_ue.SpectatorPawnMovement.md#isactive)
- [IsBeingDestroyed](ue_ue.SpectatorPawnMovement.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.SpectatorPawnMovement.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.SpectatorPawnMovement.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.SpectatorPawnMovement.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.SpectatorPawnMovement.md#isfalling)
- [IsFlying](ue_ue.SpectatorPawnMovement.md#isflying)
- [IsMoveInputIgnored](ue_ue.SpectatorPawnMovement.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.SpectatorPawnMovement.md#ismovingonground)
- [IsSwimming](ue_ue.SpectatorPawnMovement.md#isswimming)
- [K2\_DestroyComponent](ue_ue.SpectatorPawnMovement.md#k2_destroycomponent)
- [K2\_GetInputVector](ue_ue.SpectatorPawnMovement.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.SpectatorPawnMovement.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.SpectatorPawnMovement.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.SpectatorPawnMovement.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.SpectatorPawnMovement.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.SpectatorPawnMovement.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.SpectatorPawnMovement.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.SpectatorPawnMovement.md#receiveendplay)
- [ReceiveTick](ue_ue.SpectatorPawnMovement.md#receivetick)
- [RegisterComponent](ue_ue.SpectatorPawnMovement.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.SpectatorPawnMovement.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SpectatorPawnMovement.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.SpectatorPawnMovement.md#setactive)
- [SetAutoActivate](ue_ue.SpectatorPawnMovement.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.SpectatorPawnMovement.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.SpectatorPawnMovement.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.SpectatorPawnMovement.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.SpectatorPawnMovement.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.SpectatorPawnMovement.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.SpectatorPawnMovement.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.SpectatorPawnMovement.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.SpectatorPawnMovement.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.SpectatorPawnMovement.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SpectatorPawnMovement.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.SpectatorPawnMovement.md#setupdatedcomponent)
- [SnapUpdatedComponentToPlane](ue_ue.SpectatorPawnMovement.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.SpectatorPawnMovement.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.SpectatorPawnMovement.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.SpectatorPawnMovement.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.SpectatorPawnMovement.md#toggleactive)
- [Find](ue_ue.SpectatorPawnMovement.md#find)
- [Load](ue_ue.SpectatorPawnMovement.md#load)
- [StaticClass](ue_ue.SpectatorPawnMovement.md#staticclass)

## Constructors

### constructor

• **new SpectatorPawnMovement**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[constructor](ue_ue.FloatingPawnMovement.md#constructor)

#### Defined in

[ue/ue.d.ts:61841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61841)

## Properties

### Acceleration

• **Acceleration**: `number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Acceleration](ue_ue.FloatingPawnMovement.md#acceleration)

#### Defined in

[ue/ue.d.ts:35707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35707)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[AssetUserData](ue_ue.FloatingPawnMovement.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ComponentTags](ue_ue.FloatingPawnMovement.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[CreationMethod](ue_ue.FloatingPawnMovement.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### Deceleration

• **Deceleration**: `number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Deceleration](ue_ue.FloatingPawnMovement.md#deceleration)

#### Defined in

[ue/ue.d.ts:35708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35708)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[FixedPathBrakingDistance](ue_ue.FloatingPawnMovement.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5468)

___

### MaxSpeed

• **MaxSpeed**: `number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[MaxSpeed](ue_ue.FloatingPawnMovement.md#maxspeed)

#### Defined in

[ue/ue.d.ts:35706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35706)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[MovementState](ue_ue.FloatingPawnMovement.md#movementstate)

#### Defined in

[ue/ue.d.ts:5472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5472)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[NavAgentProps](ue_ue.FloatingPawnMovement.md#navagentprops)

#### Defined in

[ue/ue.d.ts:5467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5467)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[OnComponentActivated](ue_ue.FloatingPawnMovement.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[OnComponentDeactivated](ue_ue.FloatingPawnMovement.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PathFollowingComp](ue_ue.FloatingPawnMovement.md#pathfollowingcomp)

#### Defined in

[ue/ue.d.ts:5473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5473)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PawnOwner](ue_ue.FloatingPawnMovement.md#pawnowner)

#### Defined in

[ue/ue.d.ts:5490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5490)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PlaneConstraintAxisSetting](ue_ue.FloatingPawnMovement.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PlaneConstraintNormal](ue_ue.FloatingPawnMovement.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PlaneConstraintOrigin](ue_ue.FloatingPawnMovement.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5394)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PrimaryComponentTick](ue_ue.FloatingPawnMovement.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### TurningBoost

• **TurningBoost**: `number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[TurningBoost](ue_ue.FloatingPawnMovement.md#turningboost)

#### Defined in

[ue/ue.d.ts:35709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35709)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[UCSModifiedProperties](ue_ue.FloatingPawnMovement.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[UpdatedComponent](ue_ue.FloatingPawnMovement.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[UpdatedPrimitive](ue_ue.FloatingPawnMovement.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5391)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Velocity](ue_ue.FloatingPawnMovement.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5392)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[__tid_ActorComponent__](ue_ue.FloatingPawnMovement.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_FloatingPawnMovement\_\_

• **\_\_tid\_FloatingPawnMovement\_\_**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[__tid_FloatingPawnMovement__](ue_ue.FloatingPawnMovement.md#__tid_floatingpawnmovement__)

#### Defined in

[ue/ue.d.ts:35715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35715)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[__tid_MovementComponent__](ue_ue.FloatingPawnMovement.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5430)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[__tid_NavMovementComponent__](ue_ue.FloatingPawnMovement.md#__tid_navmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5485)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[__tid_Object__](ue_ue.FloatingPawnMovement.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[__tid_PawnMovementComponent__](ue_ue.FloatingPawnMovement.md#__tid_pawnmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5502)

___

### \_\_tid\_SpectatorPawnMovement\_\_

• **\_\_tid\_SpectatorPawnMovement\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61847](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61847)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bAutoActivate](ue_ue.FloatingPawnMovement.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.FloatingPawnMovement.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bAutoRegisterUpdatedComponent](ue_ue.FloatingPawnMovement.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bAutoUpdateTickRegistration](ue_ue.FloatingPawnMovement.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5396)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bCanEverAffectNavigation](ue_ue.FloatingPawnMovement.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.FloatingPawnMovement.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bConstrainToPlane](ue_ue.FloatingPawnMovement.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bCreatedByConstructionScript](ue_ue.FloatingPawnMovement.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bEditableWhenInherited](ue_ue.FloatingPawnMovement.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

#### Defined in

[ue/ue.d.ts:61842](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61842)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bInstanceComponent](ue_ue.FloatingPawnMovement.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bIsActive](ue_ue.FloatingPawnMovement.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bIsEditorOnly](ue_ue.FloatingPawnMovement.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bIsVisualizationComponent](ue_ue.FloatingPawnMovement.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bNetAddressable](ue_ue.FloatingPawnMovement.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bPositionCorrected

• **bPositionCorrected**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bPositionCorrected](ue_ue.FloatingPawnMovement.md#bpositioncorrected)

#### Defined in

[ue/ue.d.ts:35710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35710)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bReplicates](ue_ue.FloatingPawnMovement.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bSnapToPlaneAtStart](ue_ue.FloatingPawnMovement.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5400)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bTickBeforeOwner](ue_ue.FloatingPawnMovement.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5397)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.FloatingPawnMovement.md#bupdatenavagentwithownerscollision)

#### Defined in

[ue/ue.d.ts:5469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5469)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bUpdateOnlyIfRendered](ue_ue.FloatingPawnMovement.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5395)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bUseAccelerationForPaths](ue_ue.FloatingPawnMovement.md#buseaccelerationforpaths)

#### Defined in

[ue/ue.d.ts:5470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5470)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[bUseFixedBrakingDistanceForPaths](ue_ue.FloatingPawnMovement.md#busefixedbrakingdistanceforpaths)

#### Defined in

[ue/ue.d.ts:5471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5471)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Activate](ue_ue.FloatingPawnMovement.md#activate)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[AddInputVector](ue_ue.FloatingPawnMovement.md#addinputvector)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[AddTickPrerequisiteActor](ue_ue.FloatingPawnMovement.md#addtickprerequisiteactor)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[AddTickPrerequisiteComponent](ue_ue.FloatingPawnMovement.md#addtickprerequisitecomponent)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ComponentHasTag](ue_ue.FloatingPawnMovement.md#componenthastag)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ConstrainDirectionToPlane](ue_ue.FloatingPawnMovement.md#constraindirectiontoplane)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ConstrainLocationToPlane](ue_ue.FloatingPawnMovement.md#constrainlocationtoplane)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ConstrainNormalToPlane](ue_ue.FloatingPawnMovement.md#constrainnormaltoplane)

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5406)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ConsumeInputVector](ue_ue.FloatingPawnMovement.md#consumeinputvector)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[CreateDefaultSubobject](ue_ue.FloatingPawnMovement.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Deactivate](ue_ue.FloatingPawnMovement.md#deactivate)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ExecuteUbergraph](ue_ue.FloatingPawnMovement.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetClass](ue_ue.FloatingPawnMovement.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetComponentTickInterval](ue_ue.FloatingPawnMovement.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetGravityZ](ue_ue.FloatingPawnMovement.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5407)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetLastInputVector](ue_ue.FloatingPawnMovement.md#getlastinputvector)

#### Defined in

[ue/ue.d.ts:5493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5493)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetMaxSpeed](ue_ue.FloatingPawnMovement.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5408)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetName](ue_ue.FloatingPawnMovement.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetOuter](ue_ue.FloatingPawnMovement.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetOwner](ue_ue.FloatingPawnMovement.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetPawnOwner](ue_ue.FloatingPawnMovement.md#getpawnowner)

#### Defined in

[ue/ue.d.ts:5494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5494)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetPendingInputVector](ue_ue.FloatingPawnMovement.md#getpendinginputvector)

#### Defined in

[ue/ue.d.ts:5495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5495)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetPhysicsVolume](ue_ue.FloatingPawnMovement.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetPlaneConstraintAxisSetting](ue_ue.FloatingPawnMovement.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetPlaneConstraintNormal](ue_ue.FloatingPawnMovement.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetPlaneConstraintOrigin](ue_ue.FloatingPawnMovement.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5412)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[GetWorld](ue_ue.FloatingPawnMovement.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsActive](ue_ue.FloatingPawnMovement.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsBeingDestroyed](ue_ue.FloatingPawnMovement.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsComponentTickEnabled](ue_ue.FloatingPawnMovement.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsCrouching](ue_ue.FloatingPawnMovement.md#iscrouching)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsExceedingMaxSpeed](ue_ue.FloatingPawnMovement.md#isexceedingmaxspeed)

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5413)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsFalling](ue_ue.FloatingPawnMovement.md#isfalling)

#### Defined in

[ue/ue.d.ts:5475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5475)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsFlying](ue_ue.FloatingPawnMovement.md#isflying)

#### Defined in

[ue/ue.d.ts:5476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5476)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsMoveInputIgnored](ue_ue.FloatingPawnMovement.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:5496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5496)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsMovingOnGround](ue_ue.FloatingPawnMovement.md#ismovingonground)

#### Defined in

[ue/ue.d.ts:5477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5477)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[IsSwimming](ue_ue.FloatingPawnMovement.md#isswimming)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[K2_DestroyComponent](ue_ue.FloatingPawnMovement.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[K2_GetInputVector](ue_ue.FloatingPawnMovement.md#k2_getinputvector)

#### Defined in

[ue/ue.d.ts:5497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5497)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[K2_GetMaxSpeedModifier](ue_ue.FloatingPawnMovement.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[K2_GetModifiedMaxSpeed](ue_ue.FloatingPawnMovement.md#k2_getmodifiedmaxspeed)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[K2_MoveUpdatedComponent](ue_ue.FloatingPawnMovement.md#k2_moveupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5416)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[OnRep_IsActive](ue_ue.FloatingPawnMovement.md#onrep_isactive)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[PhysicsVolumeChanged](ue_ue.FloatingPawnMovement.md#physicsvolumechanged)

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ReceiveBeginPlay](ue_ue.FloatingPawnMovement.md#receivebeginplay)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ReceiveEndPlay](ue_ue.FloatingPawnMovement.md#receiveendplay)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ReceiveTick](ue_ue.FloatingPawnMovement.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[RegisterComponent](ue_ue.FloatingPawnMovement.md#registercomponent)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[RemoveTickPrerequisiteActor](ue_ue.FloatingPawnMovement.md#removetickprerequisiteactor)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[RemoveTickPrerequisiteComponent](ue_ue.FloatingPawnMovement.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetActive](ue_ue.FloatingPawnMovement.md#setactive)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetAutoActivate](ue_ue.FloatingPawnMovement.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetComponentTickEnabled](ue_ue.FloatingPawnMovement.md#setcomponenttickenabled)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetComponentTickInterval](ue_ue.FloatingPawnMovement.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetIsReplicated](ue_ue.FloatingPawnMovement.md#setisreplicated)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetPlaneConstraintAxisSetting](ue_ue.FloatingPawnMovement.md#setplaneconstraintaxissetting)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetPlaneConstraintEnabled](ue_ue.FloatingPawnMovement.md#setplaneconstraintenabled)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetPlaneConstraintFromVectors](ue_ue.FloatingPawnMovement.md#setplaneconstraintfromvectors)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetPlaneConstraintNormal](ue_ue.FloatingPawnMovement.md#setplaneconstraintnormal)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetPlaneConstraintOrigin](ue_ue.FloatingPawnMovement.md#setplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5422)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetTickGroup](ue_ue.FloatingPawnMovement.md#settickgroup)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetTickableWhenPaused](ue_ue.FloatingPawnMovement.md#settickablewhenpaused)

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

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SetUpdatedComponent](ue_ue.FloatingPawnMovement.md#setupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5423)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[SnapUpdatedComponentToPlane](ue_ue.FloatingPawnMovement.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5424)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[StopActiveMovement](ue_ue.FloatingPawnMovement.md#stopactivemovement)

#### Defined in

[ue/ue.d.ts:5479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5479)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[StopMovementImmediately](ue_ue.FloatingPawnMovement.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5425)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[StopMovementKeepPathing](ue_ue.FloatingPawnMovement.md#stopmovementkeeppathing)

#### Defined in

[ue/ue.d.ts:5480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5480)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[ToggleActive](ue_ue.FloatingPawnMovement.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SpectatorPawnMovement`](ue_ue.SpectatorPawnMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SpectatorPawnMovement`](ue_ue.SpectatorPawnMovement.md)

#### Overrides

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Find](ue_ue.FloatingPawnMovement.md#find)

#### Defined in

[ue/ue.d.ts:61844](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61844)

___

### Load

▸ `Static` **Load**(`InName`): [`SpectatorPawnMovement`](ue_ue.SpectatorPawnMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SpectatorPawnMovement`](ue_ue.SpectatorPawnMovement.md)

#### Overrides

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[Load](ue_ue.FloatingPawnMovement.md#load)

#### Defined in

[ue/ue.d.ts:61845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61845)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FloatingPawnMovement](ue_ue.FloatingPawnMovement.md).[StaticClass](ue_ue.FloatingPawnMovement.md#staticclass)

#### Defined in

[ue/ue.d.ts:61843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61843)
