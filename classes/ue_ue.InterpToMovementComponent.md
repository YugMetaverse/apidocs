[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpToMovementComponent

# Class: InterpToMovementComponent

[ue/ue](../modules/ue_ue.md).InterpToMovementComponent

## Hierarchy

- [`MovementComponent`](ue_ue.MovementComponent.md)

  ↳ **`InterpToMovementComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpToMovementComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.InterpToMovementComponent.md#assetuserdata)
- [BehaviourType](ue_ue.InterpToMovementComponent.md#behaviourtype)
- [ComponentTags](ue_ue.InterpToMovementComponent.md#componenttags)
- [ControlPoints](ue_ue.InterpToMovementComponent.md#controlpoints)
- [CreationMethod](ue_ue.InterpToMovementComponent.md#creationmethod)
- [Duration](ue_ue.InterpToMovementComponent.md#duration)
- [MaxSimulationIterations](ue_ue.InterpToMovementComponent.md#maxsimulationiterations)
- [MaxSimulationTimeStep](ue_ue.InterpToMovementComponent.md#maxsimulationtimestep)
- [OnComponentActivated](ue_ue.InterpToMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.InterpToMovementComponent.md#oncomponentdeactivated)
- [OnInterpToReverse](ue_ue.InterpToMovementComponent.md#oninterptoreverse)
- [OnInterpToStop](ue_ue.InterpToMovementComponent.md#oninterptostop)
- [OnResetDelegate](ue_ue.InterpToMovementComponent.md#onresetdelegate)
- [OnWaitBeginDelegate](ue_ue.InterpToMovementComponent.md#onwaitbegindelegate)
- [OnWaitEndDelegate](ue_ue.InterpToMovementComponent.md#onwaitenddelegate)
- [PlaneConstraintAxisSetting](ue_ue.InterpToMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.InterpToMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.InterpToMovementComponent.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.InterpToMovementComponent.md#primarycomponenttick)
- [TeleportType](ue_ue.InterpToMovementComponent.md#teleporttype)
- [UCSModifiedProperties](ue_ue.InterpToMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.InterpToMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.InterpToMovementComponent.md#updatedprimitive)
- [Velocity](ue_ue.InterpToMovementComponent.md#velocity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.InterpToMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_InterpToMovementComponent\_\_](ue_ue.InterpToMovementComponent.md#__tid_interptomovementcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.InterpToMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.InterpToMovementComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.InterpToMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.InterpToMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.InterpToMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.InterpToMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.InterpToMovementComponent.md#bcaneveraffectnavigation)
- [bCheckIfStillInWorld](ue_ue.InterpToMovementComponent.md#bcheckifstillinworld)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.InterpToMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.InterpToMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.InterpToMovementComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.InterpToMovementComponent.md#beditablewheninherited)
- [bForceSubStepping](ue_ue.InterpToMovementComponent.md#bforcesubstepping)
- [bInstanceComponent](ue_ue.InterpToMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.InterpToMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.InterpToMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.InterpToMovementComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.InterpToMovementComponent.md#bnetaddressable)
- [bPauseOnImpact](ue_ue.InterpToMovementComponent.md#bpauseonimpact)
- [bReplicates](ue_ue.InterpToMovementComponent.md#breplicates)
- [bSnapToPlaneAtStart](ue_ue.InterpToMovementComponent.md#bsnaptoplaneatstart)
- [bSweep](ue_ue.InterpToMovementComponent.md#bsweep)
- [bTickBeforeOwner](ue_ue.InterpToMovementComponent.md#btickbeforeowner)
- [bUpdateOnlyIfRendered](ue_ue.InterpToMovementComponent.md#bupdateonlyifrendered)

### Methods

- [Activate](ue_ue.InterpToMovementComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.InterpToMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.InterpToMovementComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.InterpToMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.InterpToMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.InterpToMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.InterpToMovementComponent.md#constrainnormaltoplane)
- [CreateDefaultSubobject](ue_ue.InterpToMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.InterpToMovementComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.InterpToMovementComponent.md#executeubergraph)
- [FinaliseControlPoints](ue_ue.InterpToMovementComponent.md#finalisecontrolpoints)
- [GetClass](ue_ue.InterpToMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.InterpToMovementComponent.md#getcomponenttickinterval)
- [GetGravityZ](ue_ue.InterpToMovementComponent.md#getgravityz)
- [GetMaxSpeed](ue_ue.InterpToMovementComponent.md#getmaxspeed)
- [GetName](ue_ue.InterpToMovementComponent.md#getname)
- [GetOuter](ue_ue.InterpToMovementComponent.md#getouter)
- [GetOwner](ue_ue.InterpToMovementComponent.md#getowner)
- [GetPhysicsVolume](ue_ue.InterpToMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.InterpToMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.InterpToMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.InterpToMovementComponent.md#getplaneconstraintorigin)
- [GetWorld](ue_ue.InterpToMovementComponent.md#getworld)
- [IsActive](ue_ue.InterpToMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.InterpToMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.InterpToMovementComponent.md#iscomponenttickenabled)
- [IsExceedingMaxSpeed](ue_ue.InterpToMovementComponent.md#isexceedingmaxspeed)
- [K2\_DestroyComponent](ue_ue.InterpToMovementComponent.md#k2_destroycomponent)
- [K2\_GetMaxSpeedModifier](ue_ue.InterpToMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.InterpToMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.InterpToMovementComponent.md#k2_moveupdatedcomponent)
- [OnInterpToResetDelegate\_\_DelegateSignature](ue_ue.InterpToMovementComponent.md#oninterptoresetdelegate__delegatesignature)
- [OnInterpToReverseDelegate\_\_DelegateSignature](ue_ue.InterpToMovementComponent.md#oninterptoreversedelegate__delegatesignature)
- [OnInterpToStopDelegate\_\_DelegateSignature](ue_ue.InterpToMovementComponent.md#oninterptostopdelegate__delegatesignature)
- [OnInterpToWaitBeginDelegate\_\_DelegateSignature](ue_ue.InterpToMovementComponent.md#oninterptowaitbegindelegate__delegatesignature)
- [OnInterpToWaitEndDelegate\_\_DelegateSignature](ue_ue.InterpToMovementComponent.md#oninterptowaitenddelegate__delegatesignature)
- [OnRep\_IsActive](ue_ue.InterpToMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.InterpToMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.InterpToMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.InterpToMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.InterpToMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.InterpToMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.InterpToMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.InterpToMovementComponent.md#removetickprerequisitecomponent)
- [RestartMovement](ue_ue.InterpToMovementComponent.md#restartmovement)
- [SetActive](ue_ue.InterpToMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.InterpToMovementComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.InterpToMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.InterpToMovementComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.InterpToMovementComponent.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.InterpToMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.InterpToMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.InterpToMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.InterpToMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.InterpToMovementComponent.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.InterpToMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.InterpToMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.InterpToMovementComponent.md#setupdatedcomponent)
- [SnapUpdatedComponentToPlane](ue_ue.InterpToMovementComponent.md#snapupdatedcomponenttoplane)
- [StopMovementImmediately](ue_ue.InterpToMovementComponent.md#stopmovementimmediately)
- [StopSimulating](ue_ue.InterpToMovementComponent.md#stopsimulating)
- [ToggleActive](ue_ue.InterpToMovementComponent.md#toggleactive)
- [Find](ue_ue.InterpToMovementComponent.md#find)
- [Load](ue_ue.InterpToMovementComponent.md#load)
- [StaticClass](ue_ue.InterpToMovementComponent.md#staticclass)

## Constructors

### constructor

• **new InterpToMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### BehaviourType

• **BehaviourType**: [`EInterpToBehaviourType`](../enums/ue_ue.EInterpToBehaviourType.md)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[ComponentTags](ue_ue.MovementComponent.md#componenttags)

___

### ControlPoints

• **ControlPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpControlPoint`](ue_ue.InterpControlPoint.md)\>

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[CreationMethod](ue_ue.MovementComponent.md#creationmethod)

___

### Duration

• **Duration**: `number`

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

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

### OnInterpToReverse

• **OnInterpToReverse**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `Time`: `number`) => `void`\>

___

### OnInterpToStop

• **OnInterpToStop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `Time`: `number`) => `void`\>

___

### OnResetDelegate

• **OnResetDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `Time`: `number`) => `void`\>

___

### OnWaitBeginDelegate

• **OnWaitBeginDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `Time`: `number`) => `void`\>

___

### OnWaitEndDelegate

• **OnWaitEndDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ImpactResult`: [`HitResult`](ue_ue.HitResult.md), `Time`: `number`) => `void`\>

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

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PrimaryComponentTick](ue_ue.MovementComponent.md#primarycomponenttick)

___

### TeleportType

• **TeleportType**: [`ETeleportType`](../enums/ue_ue.ETeleportType.md)

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

### \_\_tid\_InterpToMovementComponent\_\_

• **\_\_tid\_InterpToMovementComponent\_\_**: `boolean`

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

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bCanEverAffectNavigation](ue_ue.MovementComponent.md#bcaneveraffectnavigation)

___

### bCheckIfStillInWorld

• **bCheckIfStillInWorld**: `boolean`

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

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bInstanceComponent](ue_ue.MovementComponent.md#binstancecomponent)

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

### bPauseOnImpact

• **bPauseOnImpact**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bReplicates](ue_ue.MovementComponent.md#breplicates)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bSnapToPlaneAtStart](ue_ue.MovementComponent.md#bsnaptoplaneatstart)

___

### bSweep

• **bSweep**: `boolean`

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

### FinaliseControlPoints

▸ **FinaliseControlPoints**(): `void`

#### Returns

`void`

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

### OnInterpToResetDelegate\_\_DelegateSignature

▸ **OnInterpToResetDelegate__DelegateSignature**(`ImpactResult`, `Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |
| `Time` | `number` |

#### Returns

`void`

___

### OnInterpToReverseDelegate\_\_DelegateSignature

▸ **OnInterpToReverseDelegate__DelegateSignature**(`ImpactResult`, `Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |
| `Time` | `number` |

#### Returns

`void`

___

### OnInterpToStopDelegate\_\_DelegateSignature

▸ **OnInterpToStopDelegate__DelegateSignature**(`ImpactResult`, `Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |
| `Time` | `number` |

#### Returns

`void`

___

### OnInterpToWaitBeginDelegate\_\_DelegateSignature

▸ **OnInterpToWaitBeginDelegate__DelegateSignature**(`ImpactResult`, `Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |
| `Time` | `number` |

#### Returns

`void`

___

### OnInterpToWaitEndDelegate\_\_DelegateSignature

▸ **OnInterpToWaitEndDelegate__DelegateSignature**(`ImpactResult`, `Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImpactResult` | [`HitResult`](ue_ue.HitResult.md) |
| `Time` | `number` |

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

### RestartMovement

▸ **RestartMovement**(`InitialDirection?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InitialDirection?` | `number` |

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpToMovementComponent`](ue_ue.InterpToMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpToMovementComponent`](ue_ue.InterpToMovementComponent.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[Find](ue_ue.MovementComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpToMovementComponent`](ue_ue.InterpToMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpToMovementComponent`](ue_ue.InterpToMovementComponent.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[Load](ue_ue.MovementComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[StaticClass](ue_ue.MovementComponent.md#staticclass)
