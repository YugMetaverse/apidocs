[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicsHandleComponent

# Class: PhysicsHandleComponent

[ue/ue](../modules/ue_ue.md).PhysicsHandleComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`PhysicsHandleComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicsHandleComponent.md#constructor)

### Properties

- [AngularDamping](ue_ue.PhysicsHandleComponent.md#angulardamping)
- [AngularStiffness](ue_ue.PhysicsHandleComponent.md#angularstiffness)
- [AssetUserData](ue_ue.PhysicsHandleComponent.md#assetuserdata)
- [ComponentTags](ue_ue.PhysicsHandleComponent.md#componenttags)
- [CreationMethod](ue_ue.PhysicsHandleComponent.md#creationmethod)
- [GrabbedComponent](ue_ue.PhysicsHandleComponent.md#grabbedcomponent)
- [InterpolationSpeed](ue_ue.PhysicsHandleComponent.md#interpolationspeed)
- [LinearDamping](ue_ue.PhysicsHandleComponent.md#lineardamping)
- [LinearStiffness](ue_ue.PhysicsHandleComponent.md#linearstiffness)
- [OnComponentActivated](ue_ue.PhysicsHandleComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PhysicsHandleComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.PhysicsHandleComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.PhysicsHandleComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PhysicsHandleComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PhysicsHandleComponent.md#__tid_object__)
- [\_\_tid\_PhysicsHandleComponent\_\_](ue_ue.PhysicsHandleComponent.md#__tid_physicshandlecomponent__)
- [bAutoActivate](ue_ue.PhysicsHandleComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.PhysicsHandleComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.PhysicsHandleComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PhysicsHandleComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.PhysicsHandleComponent.md#binstancecomponent)
- [bInterpolateTarget](ue_ue.PhysicsHandleComponent.md#binterpolatetarget)
- [bIsActive](ue_ue.PhysicsHandleComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PhysicsHandleComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PhysicsHandleComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PhysicsHandleComponent.md#bnetaddressable)
- [bReplicates](ue_ue.PhysicsHandleComponent.md#breplicates)
- [bSoftAngularConstraint](ue_ue.PhysicsHandleComponent.md#bsoftangularconstraint)
- [bSoftLinearConstraint](ue_ue.PhysicsHandleComponent.md#bsoftlinearconstraint)

### Methods

- [Activate](ue_ue.PhysicsHandleComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PhysicsHandleComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PhysicsHandleComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PhysicsHandleComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PhysicsHandleComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PhysicsHandleComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.PhysicsHandleComponent.md#executeubergraph)
- [GetClass](ue_ue.PhysicsHandleComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PhysicsHandleComponent.md#getcomponenttickinterval)
- [GetGrabbedComponent](ue_ue.PhysicsHandleComponent.md#getgrabbedcomponent)
- [GetName](ue_ue.PhysicsHandleComponent.md#getname)
- [GetOuter](ue_ue.PhysicsHandleComponent.md#getouter)
- [GetOwner](ue_ue.PhysicsHandleComponent.md#getowner)
- [GetTargetLocationAndRotation](ue_ue.PhysicsHandleComponent.md#gettargetlocationandrotation)
- [GetWorld](ue_ue.PhysicsHandleComponent.md#getworld)
- [GrabComponent](ue_ue.PhysicsHandleComponent.md#grabcomponent)
- [GrabComponentAtLocation](ue_ue.PhysicsHandleComponent.md#grabcomponentatlocation)
- [GrabComponentAtLocationWithRotation](ue_ue.PhysicsHandleComponent.md#grabcomponentatlocationwithrotation)
- [IsActive](ue_ue.PhysicsHandleComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.PhysicsHandleComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PhysicsHandleComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.PhysicsHandleComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.PhysicsHandleComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.PhysicsHandleComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PhysicsHandleComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PhysicsHandleComponent.md#receivetick)
- [RegisterComponent](ue_ue.PhysicsHandleComponent.md#registercomponent)
- [ReleaseComponent](ue_ue.PhysicsHandleComponent.md#releasecomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PhysicsHandleComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PhysicsHandleComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.PhysicsHandleComponent.md#setactive)
- [SetAngularDamping](ue_ue.PhysicsHandleComponent.md#setangulardamping)
- [SetAngularStiffness](ue_ue.PhysicsHandleComponent.md#setangularstiffness)
- [SetAutoActivate](ue_ue.PhysicsHandleComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PhysicsHandleComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PhysicsHandleComponent.md#setcomponenttickinterval)
- [SetInterpolationSpeed](ue_ue.PhysicsHandleComponent.md#setinterpolationspeed)
- [SetIsReplicated](ue_ue.PhysicsHandleComponent.md#setisreplicated)
- [SetLinearDamping](ue_ue.PhysicsHandleComponent.md#setlineardamping)
- [SetLinearStiffness](ue_ue.PhysicsHandleComponent.md#setlinearstiffness)
- [SetTargetLocation](ue_ue.PhysicsHandleComponent.md#settargetlocation)
- [SetTargetLocationAndRotation](ue_ue.PhysicsHandleComponent.md#settargetlocationandrotation)
- [SetTargetRotation](ue_ue.PhysicsHandleComponent.md#settargetrotation)
- [SetTickGroup](ue_ue.PhysicsHandleComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PhysicsHandleComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.PhysicsHandleComponent.md#toggleactive)
- [Find](ue_ue.PhysicsHandleComponent.md#find)
- [Load](ue_ue.PhysicsHandleComponent.md#load)
- [StaticClass](ue_ue.PhysicsHandleComponent.md#staticclass)

## Constructors

### constructor

• **new PhysicsHandleComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

## Properties

### AngularDamping

• **AngularDamping**: `number`

___

### AngularStiffness

• **AngularStiffness**: `number`

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AssetUserData](ue_ue.ActorComponent.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ComponentTags](ue_ue.ActorComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[CreationMethod](ue_ue.ActorComponent.md#creationmethod)

___

### GrabbedComponent

• **GrabbedComponent**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### InterpolationSpeed

• **InterpolationSpeed**: `number`

___

### LinearDamping

• **LinearDamping**: `number`

___

### LinearStiffness

• **LinearStiffness**: `number`

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentActivated](ue_ue.ActorComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentDeactivated](ue_ue.ActorComponent.md#oncomponentdeactivated)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_ActorComponent__](ue_ue.ActorComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_Object__](ue_ue.ActorComponent.md#__tid_object__)

___

### \_\_tid\_PhysicsHandleComponent\_\_

• **\_\_tid\_PhysicsHandleComponent\_\_**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bAutoActivate](ue_ue.ActorComponent.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCanEverAffectNavigation](ue_ue.ActorComponent.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCreatedByConstructionScript](ue_ue.ActorComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bEditableWhenInherited](ue_ue.ActorComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bInstanceComponent](ue_ue.ActorComponent.md#binstancecomponent)

___

### bInterpolateTarget

• **bInterpolateTarget**: `boolean`

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsActive](ue_ue.ActorComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsEditorOnly](ue_ue.ActorComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsVisualizationComponent](ue_ue.ActorComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bNetAddressable](ue_ue.ActorComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

___

### bSoftAngularConstraint

• **bSoftAngularConstraint**: `boolean`

___

### bSoftLinearConstraint

• **bSoftLinearConstraint**: `boolean`

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

[ActorComponent](ue_ue.ActorComponent.md).[Activate](ue_ue.ActorComponent.md#activate)

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

[ActorComponent](ue_ue.ActorComponent.md).[AddTickPrerequisiteActor](ue_ue.ActorComponent.md#addtickprerequisiteactor)

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

[ActorComponent](ue_ue.ActorComponent.md).[AddTickPrerequisiteComponent](ue_ue.ActorComponent.md#addtickprerequisitecomponent)

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

[ActorComponent](ue_ue.ActorComponent.md).[ComponentHasTag](ue_ue.ActorComponent.md#componenthastag)

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

[ActorComponent](ue_ue.ActorComponent.md).[CreateDefaultSubobject](ue_ue.ActorComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[Deactivate](ue_ue.ActorComponent.md#deactivate)

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

[ActorComponent](ue_ue.ActorComponent.md).[ExecuteUbergraph](ue_ue.ActorComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetClass](ue_ue.ActorComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetComponentTickInterval](ue_ue.ActorComponent.md#getcomponenttickinterval)

___

### GetGrabbedComponent

▸ **GetGrabbedComponent**(): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetName](ue_ue.ActorComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOuter](ue_ue.ActorComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOwner](ue_ue.ActorComponent.md#getowner)

___

### GetTargetLocationAndRotation

▸ **GetTargetLocationAndRotation**(`TargetLocation`, `TargetRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `TargetRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetWorld](ue_ue.ActorComponent.md#getworld)

___

### GrabComponent

▸ **GrabComponent**(`Component`, `InBoneName`, `GrabLocation`, `bConstrainRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `InBoneName` | `string` |
| `GrabLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bConstrainRotation` | `boolean` |

#### Returns

`void`

___

### GrabComponentAtLocation

▸ **GrabComponentAtLocation**(`Component`, `InBoneName`, `GrabLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `InBoneName` | `string` |
| `GrabLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### GrabComponentAtLocationWithRotation

▸ **GrabComponentAtLocationWithRotation**(`Component`, `InBoneName`, `Location`, `Rotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `InBoneName` | `string` |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsActive](ue_ue.ActorComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsBeingDestroyed](ue_ue.ActorComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsComponentTickEnabled](ue_ue.ActorComponent.md#iscomponenttickenabled)

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

[ActorComponent](ue_ue.ActorComponent.md).[K2_DestroyComponent](ue_ue.ActorComponent.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnRep_IsActive](ue_ue.ActorComponent.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveBeginPlay](ue_ue.ActorComponent.md#receivebeginplay)

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

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveEndPlay](ue_ue.ActorComponent.md#receiveendplay)

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

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveTick](ue_ue.ActorComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[RegisterComponent](ue_ue.ActorComponent.md#registercomponent)

___

### ReleaseComponent

▸ **ReleaseComponent**(): `void`

#### Returns

`void`

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

[ActorComponent](ue_ue.ActorComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ActorComponent.md#removetickprerequisiteactor)

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

[ActorComponent](ue_ue.ActorComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ActorComponent.md#removetickprerequisitecomponent)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetActive](ue_ue.ActorComponent.md#setactive)

___

### SetAngularDamping

▸ **SetAngularDamping**(`NewAngularDamping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngularDamping` | `number` |

#### Returns

`void`

___

### SetAngularStiffness

▸ **SetAngularStiffness**(`NewAngularStiffness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngularStiffness` | `number` |

#### Returns

`void`

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

[ActorComponent](ue_ue.ActorComponent.md).[SetAutoActivate](ue_ue.ActorComponent.md#setautoactivate)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetComponentTickEnabled](ue_ue.ActorComponent.md#setcomponenttickenabled)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetComponentTickInterval](ue_ue.ActorComponent.md#setcomponenttickinterval)

___

### SetInterpolationSpeed

▸ **SetInterpolationSpeed**(`NewInterpolationSpeed`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewInterpolationSpeed` | `number` |

#### Returns

`void`

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

[ActorComponent](ue_ue.ActorComponent.md).[SetIsReplicated](ue_ue.ActorComponent.md#setisreplicated)

___

### SetLinearDamping

▸ **SetLinearDamping**(`NewLinearDamping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLinearDamping` | `number` |

#### Returns

`void`

___

### SetLinearStiffness

▸ **SetLinearStiffness**(`NewLinearStiffness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLinearStiffness` | `number` |

#### Returns

`void`

___

### SetTargetLocation

▸ **SetTargetLocation**(`NewLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetTargetLocationAndRotation

▸ **SetTargetLocationAndRotation**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### SetTargetRotation

▸ **SetTargetRotation**(`NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

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

[ActorComponent](ue_ue.ActorComponent.md).[SetTickGroup](ue_ue.ActorComponent.md#settickgroup)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetTickableWhenPaused](ue_ue.ActorComponent.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
