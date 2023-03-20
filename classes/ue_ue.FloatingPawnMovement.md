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

#### Defined in

[ue/ue.d.ts:35705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35705)

## Properties

### Acceleration

• **Acceleration**: `number`

#### Defined in

[ue/ue.d.ts:35707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35707)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AssetUserData](ue_ue.PawnMovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

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

### Deceleration

• **Deceleration**: `number`

#### Defined in

[ue/ue.d.ts:35708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35708)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[FixedPathBrakingDistance](ue_ue.PawnMovementComponent.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5468)

___

### MaxSpeed

• **MaxSpeed**: `number`

#### Defined in

[ue/ue.d.ts:35706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35706)

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

### TurningBoost

• **TurningBoost**: `number`

#### Defined in

[ue/ue.d.ts:35709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35709)

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

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_ActorComponent__](ue_ue.PawnMovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_FloatingPawnMovement\_\_

• **\_\_tid\_FloatingPawnMovement\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35715)

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

### bPositionCorrected

• **bPositionCorrected**: `boolean`

#### Defined in

[ue/ue.d.ts:35710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35710)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bReplicates](ue_ue.PawnMovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

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

#### Defined in

[ue/ue.d.ts:35712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35712)

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

#### Defined in

[ue/ue.d.ts:35713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35713)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StaticClass](ue_ue.PawnMovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:35711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35711)
