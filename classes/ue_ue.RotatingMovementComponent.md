[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RotatingMovementComponent

# Class: RotatingMovementComponent

[ue/ue](../modules/ue_ue.md).RotatingMovementComponent

## Hierarchy

- [`MovementComponent`](ue_ue.MovementComponent.md)

  ↳ **`RotatingMovementComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.RotatingMovementComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.RotatingMovementComponent.md#assetuserdata)
- [ComponentTags](ue_ue.RotatingMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.RotatingMovementComponent.md#creationmethod)
- [OnComponentActivated](ue_ue.RotatingMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.RotatingMovementComponent.md#oncomponentdeactivated)
- [PivotTranslation](ue_ue.RotatingMovementComponent.md#pivottranslation)
- [PlaneConstraintAxisSetting](ue_ue.RotatingMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.RotatingMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.RotatingMovementComponent.md#planeconstraintorigin)
- [PrimaryComponentTick](ue_ue.RotatingMovementComponent.md#primarycomponenttick)
- [RotationRate](ue_ue.RotatingMovementComponent.md#rotationrate)
- [UCSModifiedProperties](ue_ue.RotatingMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.RotatingMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.RotatingMovementComponent.md#updatedprimitive)
- [Velocity](ue_ue.RotatingMovementComponent.md#velocity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.RotatingMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.RotatingMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.RotatingMovementComponent.md#__tid_object__)
- [\_\_tid\_RotatingMovementComponent\_\_](ue_ue.RotatingMovementComponent.md#__tid_rotatingmovementcomponent__)
- [bAutoActivate](ue_ue.RotatingMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.RotatingMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.RotatingMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.RotatingMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.RotatingMovementComponent.md#bcaneveraffectnavigation)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.RotatingMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.RotatingMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.RotatingMovementComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.RotatingMovementComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.RotatingMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.RotatingMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.RotatingMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.RotatingMovementComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.RotatingMovementComponent.md#bnetaddressable)
- [bReplicates](ue_ue.RotatingMovementComponent.md#breplicates)
- [bRotationInLocalSpace](ue_ue.RotatingMovementComponent.md#brotationinlocalspace)
- [bSnapToPlaneAtStart](ue_ue.RotatingMovementComponent.md#bsnaptoplaneatstart)
- [bTickBeforeOwner](ue_ue.RotatingMovementComponent.md#btickbeforeowner)
- [bUpdateOnlyIfRendered](ue_ue.RotatingMovementComponent.md#bupdateonlyifrendered)

### Methods

- [Activate](ue_ue.RotatingMovementComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.RotatingMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.RotatingMovementComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.RotatingMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.RotatingMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.RotatingMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.RotatingMovementComponent.md#constrainnormaltoplane)
- [CreateDefaultSubobject](ue_ue.RotatingMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.RotatingMovementComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.RotatingMovementComponent.md#executeubergraph)
- [GetClass](ue_ue.RotatingMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.RotatingMovementComponent.md#getcomponenttickinterval)
- [GetGravityZ](ue_ue.RotatingMovementComponent.md#getgravityz)
- [GetMaxSpeed](ue_ue.RotatingMovementComponent.md#getmaxspeed)
- [GetName](ue_ue.RotatingMovementComponent.md#getname)
- [GetOuter](ue_ue.RotatingMovementComponent.md#getouter)
- [GetOwner](ue_ue.RotatingMovementComponent.md#getowner)
- [GetPhysicsVolume](ue_ue.RotatingMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.RotatingMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.RotatingMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.RotatingMovementComponent.md#getplaneconstraintorigin)
- [GetWorld](ue_ue.RotatingMovementComponent.md#getworld)
- [IsActive](ue_ue.RotatingMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.RotatingMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.RotatingMovementComponent.md#iscomponenttickenabled)
- [IsExceedingMaxSpeed](ue_ue.RotatingMovementComponent.md#isexceedingmaxspeed)
- [K2\_DestroyComponent](ue_ue.RotatingMovementComponent.md#k2_destroycomponent)
- [K2\_GetMaxSpeedModifier](ue_ue.RotatingMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxSpeed](ue_ue.RotatingMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_MoveUpdatedComponent](ue_ue.RotatingMovementComponent.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.RotatingMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.RotatingMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.RotatingMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.RotatingMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.RotatingMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.RotatingMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.RotatingMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.RotatingMovementComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.RotatingMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.RotatingMovementComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.RotatingMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.RotatingMovementComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.RotatingMovementComponent.md#setisreplicated)
- [SetPlaneConstraintAxisSetting](ue_ue.RotatingMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.RotatingMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.RotatingMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.RotatingMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.RotatingMovementComponent.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.RotatingMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.RotatingMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.RotatingMovementComponent.md#setupdatedcomponent)
- [SnapUpdatedComponentToPlane](ue_ue.RotatingMovementComponent.md#snapupdatedcomponenttoplane)
- [StopMovementImmediately](ue_ue.RotatingMovementComponent.md#stopmovementimmediately)
- [ToggleActive](ue_ue.RotatingMovementComponent.md#toggleactive)
- [Find](ue_ue.RotatingMovementComponent.md#find)
- [Load](ue_ue.RotatingMovementComponent.md#load)
- [StaticClass](ue_ue.RotatingMovementComponent.md#staticclass)

## Constructors

### constructor

• **new RotatingMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[constructor](ue_ue.MovementComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:59695](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59695)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[AssetUserData](ue_ue.MovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

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

### PivotTranslation

• **PivotTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:59697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59697)

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

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[PrimaryComponentTick](ue_ue.MovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### RotationRate

• **RotationRate**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:59696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59696)

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

### \_\_tid\_RotatingMovementComponent\_\_

• **\_\_tid\_RotatingMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59703](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59703)

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

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bInstanceComponent](ue_ue.MovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

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

### bRotationInLocalSpace

• **bRotationInLocalSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:59698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59698)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[MovementComponent](ue_ue.MovementComponent.md).[bSnapToPlaneAtStart](ue_ue.MovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L5400)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RotatingMovementComponent`](ue_ue.RotatingMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RotatingMovementComponent`](ue_ue.RotatingMovementComponent.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[Find](ue_ue.MovementComponent.md#find)

#### Defined in

[ue/ue.d.ts:59700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59700)

___

### Load

▸ `Static` **Load**(`InName`): [`RotatingMovementComponent`](ue_ue.RotatingMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RotatingMovementComponent`](ue_ue.RotatingMovementComponent.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[Load](ue_ue.MovementComponent.md#load)

#### Defined in

[ue/ue.d.ts:59701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59701)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovementComponent](ue_ue.MovementComponent.md).[StaticClass](ue_ue.MovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:59699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59699)
