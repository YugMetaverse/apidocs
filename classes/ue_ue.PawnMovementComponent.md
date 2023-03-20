[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnMovementComponent

# Class: PawnMovementComponent

[ue/ue](../modules/ue_ue.md).PawnMovementComponent

## Hierarchy

- [`NavMovementComponent`](ue_ue.NavMovementComponent.md)

  ↳ **`PawnMovementComponent`**

  ↳↳ [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

  ↳↳ [`FloatingPawnMovement`](ue_ue.FloatingPawnMovement.md)

  ↳↳ [`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PawnMovementComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.PawnMovementComponent.md#assetuserdata)
- [ComponentTags](ue_ue.PawnMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.PawnMovementComponent.md#creationmethod)
- [FixedPathBrakingDistance](ue_ue.PawnMovementComponent.md#fixedpathbrakingdistance)
- [MovementState](ue_ue.PawnMovementComponent.md#movementstate)
- [NavAgentProps](ue_ue.PawnMovementComponent.md#navagentprops)
- [OnComponentActivated](ue_ue.PawnMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PawnMovementComponent.md#oncomponentdeactivated)
- [PathFollowingComp](ue_ue.PawnMovementComponent.md#pathfollowingcomp)
- [PawnOwner](ue_ue.PawnMovementComponent.md#pawnowner)
- [PlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.PawnMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.PawnMovementComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.PawnMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.PawnMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.PawnMovementComponent.md#updatedprimitive)
- [Velocity](ue_ue.PawnMovementComponent.md#velocity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PawnMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.PawnMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.PawnMovementComponent.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PawnMovementComponent.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.PawnMovementComponent.md#__tid_pawnmovementcomponent__)
- [bAutoActivate](ue_ue.PawnMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.PawnMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.PawnMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.PawnMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.PawnMovementComponent.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.PawnMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.PawnMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.PawnMovementComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PawnMovementComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.PawnMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PawnMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PawnMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PawnMovementComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PawnMovementComponent.md#bnetaddressable)
- [bReplicates](ue_ue.PawnMovementComponent.md#breplicates)
- [bSnapToPlaneAtStart](ue_ue.PawnMovementComponent.md#bsnaptoplaneatstart)
- [bTickBeforeOwner](ue_ue.PawnMovementComponent.md#btickbeforeowner)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.PawnMovementComponent.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.PawnMovementComponent.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.PawnMovementComponent.md#buseaccelerationforpaths)
- [bUseFixedBrakingDistanceForPaths](ue_ue.PawnMovementComponent.md#busefixedbrakingdistanceforpaths)

### Methods

- [Activate](ue_ue.PawnMovementComponent.md#activate)
- [AddInputVector](ue_ue.PawnMovementComponent.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.PawnMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PawnMovementComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PawnMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.PawnMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.PawnMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.PawnMovementComponent.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.PawnMovementComponent.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.PawnMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PawnMovementComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.PawnMovementComponent.md#executeubergraph)
- [GetClass](ue_ue.PawnMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PawnMovementComponent.md#getcomponenttickinterval)
- [GetGravityZ](ue_ue.PawnMovementComponent.md#getgravityz)
- [GetLastInputVector](ue_ue.PawnMovementComponent.md#getlastinputvector)
- [GetMaxSpeed](ue_ue.PawnMovementComponent.md#getmaxspeed)
- [GetName](ue_ue.PawnMovementComponent.md#getname)
- [GetOuter](ue_ue.PawnMovementComponent.md#getouter)
- [GetOwner](ue_ue.PawnMovementComponent.md#getowner)
- [GetPawnOwner](ue_ue.PawnMovementComponent.md#getpawnowner)
- [GetPendingInputVector](ue_ue.PawnMovementComponent.md#getpendinginputvector)
- [GetPhysicsVolume](ue_ue.PawnMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#getplaneconstraintorigin)
- [GetWorld](ue_ue.PawnMovementComponent.md#getworld)
- [IsActive](ue_ue.PawnMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.PawnMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PawnMovementComponent.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.PawnMovementComponent.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.PawnMovementComponent.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.PawnMovementComponent.md#isfalling)
- [IsFlying](ue_ue.PawnMovementComponent.md#isflying)
- [IsMoveInputIgnored](ue_ue.PawnMovementComponent.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.PawnMovementComponent.md#ismovingonground)
- [IsSwimming](ue_ue.PawnMovementComponent.md#isswimming)
- [K2\_DestroyComponent](ue_ue.PawnMovementComponent.md#k2_destroycomponent)
- [K2\_GetInputVector](ue_ue.PawnMovementComponent.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.PawnMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.PawnMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.PawnMovementComponent.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.PawnMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.PawnMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.PawnMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PawnMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PawnMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.PawnMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PawnMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PawnMovementComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.PawnMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.PawnMovementComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PawnMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PawnMovementComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.PawnMovementComponent.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.PawnMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.PawnMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.PawnMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PawnMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.PawnMovementComponent.md#setupdatedcomponent)
- [SnapUpdatedComponentToPlane](ue_ue.PawnMovementComponent.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.PawnMovementComponent.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.PawnMovementComponent.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.PawnMovementComponent.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.PawnMovementComponent.md#toggleactive)
- [Find](ue_ue.PawnMovementComponent.md#find)
- [Load](ue_ue.PawnMovementComponent.md#load)
- [StaticClass](ue_ue.PawnMovementComponent.md#staticclass)

## Constructors

### constructor

• **new PawnMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavMovementComponent](ue_ue.NavMovementComponent.md).[constructor](ue_ue.NavMovementComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:5489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5489)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[AssetUserData](ue_ue.NavMovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ComponentTags](ue_ue.NavMovementComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[CreationMethod](ue_ue.NavMovementComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[FixedPathBrakingDistance](ue_ue.NavMovementComponent.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5468)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[MovementState](ue_ue.NavMovementComponent.md#movementstate)

#### Defined in

[ue/ue.d.ts:5472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5472)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[NavAgentProps](ue_ue.NavMovementComponent.md#navagentprops)

#### Defined in

[ue/ue.d.ts:5467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5467)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[OnComponentActivated](ue_ue.NavMovementComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[OnComponentDeactivated](ue_ue.NavMovementComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[PathFollowingComp](ue_ue.NavMovementComponent.md#pathfollowingcomp)

#### Defined in

[ue/ue.d.ts:5473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5473)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Defined in

[ue/ue.d.ts:5490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5490)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.NavMovementComponent.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[PlaneConstraintNormal](ue_ue.NavMovementComponent.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[PlaneConstraintOrigin](ue_ue.NavMovementComponent.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5394)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[PrimaryComponentTick](ue_ue.NavMovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[UCSModifiedProperties](ue_ue.NavMovementComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[UpdatedComponent](ue_ue.NavMovementComponent.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[UpdatedPrimitive](ue_ue.NavMovementComponent.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5391)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[Velocity](ue_ue.NavMovementComponent.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5392)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[__tid_ActorComponent__](ue_ue.NavMovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[__tid_MovementComponent__](ue_ue.NavMovementComponent.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5430)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.NavMovementComponent.md#__tid_navmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5485)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[__tid_Object__](ue_ue.NavMovementComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:5502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5502)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bAutoActivate](ue_ue.NavMovementComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.NavMovementComponent.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.NavMovementComponent.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.NavMovementComponent.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5396)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bCanEverAffectNavigation](ue_ue.NavMovementComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.NavMovementComponent.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bConstrainToPlane](ue_ue.NavMovementComponent.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bCreatedByConstructionScript](ue_ue.NavMovementComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bEditableWhenInherited](ue_ue.NavMovementComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bInstanceComponent](ue_ue.NavMovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bIsActive](ue_ue.NavMovementComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bIsEditorOnly](ue_ue.NavMovementComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bIsVisualizationComponent](ue_ue.NavMovementComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bNetAddressable](ue_ue.NavMovementComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bReplicates](ue_ue.NavMovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.NavMovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5400)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bTickBeforeOwner](ue_ue.NavMovementComponent.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5397)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.NavMovementComponent.md#bupdatenavagentwithownerscollision)

#### Defined in

[ue/ue.d.ts:5469](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5469)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.NavMovementComponent.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5395)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bUseAccelerationForPaths](ue_ue.NavMovementComponent.md#buseaccelerationforpaths)

#### Defined in

[ue/ue.d.ts:5470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5470)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.NavMovementComponent.md#busefixedbrakingdistanceforpaths)

#### Defined in

[ue/ue.d.ts:5471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5471)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[Activate](ue_ue.NavMovementComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

#### Defined in

[ue/ue.d.ts:5491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5491)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[AddTickPrerequisiteActor](ue_ue.NavMovementComponent.md#addtickprerequisiteactor)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.NavMovementComponent.md#addtickprerequisitecomponent)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ComponentHasTag](ue_ue.NavMovementComponent.md#componenthastag)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ConstrainDirectionToPlane](ue_ue.NavMovementComponent.md#constraindirectiontoplane)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ConstrainLocationToPlane](ue_ue.NavMovementComponent.md#constrainlocationtoplane)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ConstrainNormalToPlane](ue_ue.NavMovementComponent.md#constrainnormaltoplane)

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5406)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5492)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[CreateDefaultSubobject](ue_ue.NavMovementComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[Deactivate](ue_ue.NavMovementComponent.md#deactivate)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ExecuteUbergraph](ue_ue.NavMovementComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetClass](ue_ue.NavMovementComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetComponentTickInterval](ue_ue.NavMovementComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetGravityZ](ue_ue.NavMovementComponent.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5407)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5493)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetMaxSpeed](ue_ue.NavMovementComponent.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5408)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetName](ue_ue.NavMovementComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetOuter](ue_ue.NavMovementComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetOwner](ue_ue.NavMovementComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Defined in

[ue/ue.d.ts:5494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5494)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5495)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetPhysicsVolume](ue_ue.NavMovementComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.NavMovementComponent.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.NavMovementComponent.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.NavMovementComponent.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5412)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[GetWorld](ue_ue.NavMovementComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsActive](ue_ue.NavMovementComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsBeingDestroyed](ue_ue.NavMovementComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsComponentTickEnabled](ue_ue.NavMovementComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsCrouching](ue_ue.NavMovementComponent.md#iscrouching)

#### Defined in

[ue/ue.d.ts:5474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5474)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsExceedingMaxSpeed](ue_ue.NavMovementComponent.md#isexceedingmaxspeed)

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5413)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsFalling](ue_ue.NavMovementComponent.md#isfalling)

#### Defined in

[ue/ue.d.ts:5475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5475)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsFlying](ue_ue.NavMovementComponent.md#isflying)

#### Defined in

[ue/ue.d.ts:5476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5476)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:5496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5496)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsMovingOnGround](ue_ue.NavMovementComponent.md#ismovingonground)

#### Defined in

[ue/ue.d.ts:5477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5477)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[IsSwimming](ue_ue.NavMovementComponent.md#isswimming)

#### Defined in

[ue/ue.d.ts:5478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5478)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[K2_DestroyComponent](ue_ue.NavMovementComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5497)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.NavMovementComponent.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.NavMovementComponent.md#k2_getmodifiedmaxspeed)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[K2_MoveUpdatedComponent](ue_ue.NavMovementComponent.md#k2_moveupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5416)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[OnRep_IsActive](ue_ue.NavMovementComponent.md#onrep_isactive)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[PhysicsVolumeChanged](ue_ue.NavMovementComponent.md#physicsvolumechanged)

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ReceiveBeginPlay](ue_ue.NavMovementComponent.md#receivebeginplay)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ReceiveEndPlay](ue_ue.NavMovementComponent.md#receiveendplay)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ReceiveTick](ue_ue.NavMovementComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[RegisterComponent](ue_ue.NavMovementComponent.md#registercomponent)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.NavMovementComponent.md#removetickprerequisiteactor)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.NavMovementComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetActive](ue_ue.NavMovementComponent.md#setactive)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetAutoActivate](ue_ue.NavMovementComponent.md#setautoactivate)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetComponentTickEnabled](ue_ue.NavMovementComponent.md#setcomponenttickenabled)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetComponentTickInterval](ue_ue.NavMovementComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetIsReplicated](ue_ue.NavMovementComponent.md#setisreplicated)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetPlaneConstraintAxisSetting](ue_ue.NavMovementComponent.md#setplaneconstraintaxissetting)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetPlaneConstraintEnabled](ue_ue.NavMovementComponent.md#setplaneconstraintenabled)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetPlaneConstraintFromVectors](ue_ue.NavMovementComponent.md#setplaneconstraintfromvectors)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetPlaneConstraintNormal](ue_ue.NavMovementComponent.md#setplaneconstraintnormal)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetPlaneConstraintOrigin](ue_ue.NavMovementComponent.md#setplaneconstraintorigin)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetTickGroup](ue_ue.NavMovementComponent.md#settickgroup)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetTickableWhenPaused](ue_ue.NavMovementComponent.md#settickablewhenpaused)

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

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SetUpdatedComponent](ue_ue.NavMovementComponent.md#setupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5423)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.NavMovementComponent.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5424)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[StopActiveMovement](ue_ue.NavMovementComponent.md#stopactivemovement)

#### Defined in

[ue/ue.d.ts:5479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5479)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[StopMovementImmediately](ue_ue.NavMovementComponent.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5425)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[StopMovementKeepPathing](ue_ue.NavMovementComponent.md#stopmovementkeeppathing)

#### Defined in

[ue/ue.d.ts:5480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5480)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[NavMovementComponent](ue_ue.NavMovementComponent.md).[ToggleActive](ue_ue.NavMovementComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Overrides

[NavMovementComponent](ue_ue.NavMovementComponent.md).[Find](ue_ue.NavMovementComponent.md#find)

#### Defined in

[ue/ue.d.ts:5499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5499)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

#### Overrides

[NavMovementComponent](ue_ue.NavMovementComponent.md).[Load](ue_ue.NavMovementComponent.md#load)

#### Defined in

[ue/ue.d.ts:5500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5500)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavMovementComponent](ue_ue.NavMovementComponent.md).[StaticClass](ue_ue.NavMovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:5498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5498)
