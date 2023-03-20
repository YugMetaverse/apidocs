[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CrowdFollowingComponent

# Class: CrowdFollowingComponent

[ue/ue](../modules/ue_ue.md).CrowdFollowingComponent

## Hierarchy

- [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

  ↳ **`CrowdFollowingComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.CrowdFollowingComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.CrowdFollowingComponent.md#assetuserdata)
- [AvoidanceGroup](ue_ue.CrowdFollowingComponent.md#avoidancegroup)
- [CharacterMovement](ue_ue.CrowdFollowingComponent.md#charactermovement)
- [ComponentTags](ue_ue.CrowdFollowingComponent.md#componenttags)
- [CreationMethod](ue_ue.CrowdFollowingComponent.md#creationmethod)
- [CrowdAgentMoveDirection](ue_ue.CrowdFollowingComponent.md#crowdagentmovedirection)
- [GroupsToAvoid](ue_ue.CrowdFollowingComponent.md#groupstoavoid)
- [GroupsToIgnore](ue_ue.CrowdFollowingComponent.md#groupstoignore)
- [MovementComp](ue_ue.CrowdFollowingComponent.md#movementcomp)
- [MyNavData](ue_ue.CrowdFollowingComponent.md#mynavdata)
- [OnComponentActivated](ue_ue.CrowdFollowingComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.CrowdFollowingComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.CrowdFollowingComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.CrowdFollowingComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CrowdFollowingComponent.md#__tid_actorcomponent__)
- [\_\_tid\_CrowdFollowingComponent\_\_](ue_ue.CrowdFollowingComponent.md#__tid_crowdfollowingcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.CrowdFollowingComponent.md#__tid_object__)
- [\_\_tid\_PathFollowingComponent\_\_](ue_ue.CrowdFollowingComponent.md#__tid_pathfollowingcomponent__)
- [bAutoActivate](ue_ue.CrowdFollowingComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.CrowdFollowingComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.CrowdFollowingComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.CrowdFollowingComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.CrowdFollowingComponent.md#binstancecomponent)
- [bIsActive](ue_ue.CrowdFollowingComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.CrowdFollowingComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CrowdFollowingComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.CrowdFollowingComponent.md#bnetaddressable)
- [bReplicates](ue_ue.CrowdFollowingComponent.md#breplicates)

### Methods

- [Activate](ue_ue.CrowdFollowingComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.CrowdFollowingComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CrowdFollowingComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.CrowdFollowingComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.CrowdFollowingComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.CrowdFollowingComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.CrowdFollowingComponent.md#executeubergraph)
- [GetClass](ue_ue.CrowdFollowingComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.CrowdFollowingComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.CrowdFollowingComponent.md#getname)
- [GetOuter](ue_ue.CrowdFollowingComponent.md#getouter)
- [GetOwner](ue_ue.CrowdFollowingComponent.md#getowner)
- [GetPathActionType](ue_ue.CrowdFollowingComponent.md#getpathactiontype)
- [GetPathDestination](ue_ue.CrowdFollowingComponent.md#getpathdestination)
- [GetWorld](ue_ue.CrowdFollowingComponent.md#getworld)
- [IsActive](ue_ue.CrowdFollowingComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.CrowdFollowingComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CrowdFollowingComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.CrowdFollowingComponent.md#k2_destroycomponent)
- [OnActorBump](ue_ue.CrowdFollowingComponent.md#onactorbump)
- [OnNavDataRegistered](ue_ue.CrowdFollowingComponent.md#onnavdataregistered)
- [OnRep\_IsActive](ue_ue.CrowdFollowingComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.CrowdFollowingComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CrowdFollowingComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.CrowdFollowingComponent.md#receivetick)
- [RegisterComponent](ue_ue.CrowdFollowingComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.CrowdFollowingComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CrowdFollowingComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.CrowdFollowingComponent.md#setactive)
- [SetAutoActivate](ue_ue.CrowdFollowingComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.CrowdFollowingComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CrowdFollowingComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.CrowdFollowingComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.CrowdFollowingComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CrowdFollowingComponent.md#settickablewhenpaused)
- [SuspendCrowdSteering](ue_ue.CrowdFollowingComponent.md#suspendcrowdsteering)
- [ToggleActive](ue_ue.CrowdFollowingComponent.md#toggleactive)
- [Find](ue_ue.CrowdFollowingComponent.md#find)
- [Load](ue_ue.CrowdFollowingComponent.md#load)
- [StaticClass](ue_ue.CrowdFollowingComponent.md#staticclass)

## Constructors

### constructor

• **new CrowdFollowingComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[constructor](ue_ue.PathFollowingComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[AssetUserData](ue_ue.PathFollowingComponent.md#assetuserdata)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

___

### CharacterMovement

• **CharacterMovement**: [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ComponentTags](ue_ue.PathFollowingComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[CreationMethod](ue_ue.PathFollowingComponent.md#creationmethod)

___

### CrowdAgentMoveDirection

• **CrowdAgentMoveDirection**: [`Vector`](ue_ue_s.Vector.md)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

___

### MovementComp

• **MovementComp**: [`NavMovementComponent`](ue_ue.NavMovementComponent.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[MovementComp](ue_ue.PathFollowingComponent.md#movementcomp)

___

### MyNavData

• **MyNavData**: [`NavigationData`](ue_ue.NavigationData.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[MyNavData](ue_ue.PathFollowingComponent.md#mynavdata)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnComponentActivated](ue_ue.PathFollowingComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnComponentDeactivated](ue_ue.PathFollowingComponent.md#oncomponentdeactivated)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[PrimaryComponentTick](ue_ue.PathFollowingComponent.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[UCSModifiedProperties](ue_ue.PathFollowingComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[__tid_ActorComponent__](ue_ue.PathFollowingComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_CrowdFollowingComponent\_\_

• **\_\_tid\_CrowdFollowingComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[__tid_Object__](ue_ue.PathFollowingComponent.md#__tid_object__)

___

### \_\_tid\_PathFollowingComponent\_\_

• **\_\_tid\_PathFollowingComponent\_\_**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[__tid_PathFollowingComponent__](ue_ue.PathFollowingComponent.md#__tid_pathfollowingcomponent__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bAutoActivate](ue_ue.PathFollowingComponent.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bCanEverAffectNavigation](ue_ue.PathFollowingComponent.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bCreatedByConstructionScript](ue_ue.PathFollowingComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bEditableWhenInherited](ue_ue.PathFollowingComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bInstanceComponent](ue_ue.PathFollowingComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bIsActive](ue_ue.PathFollowingComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bIsEditorOnly](ue_ue.PathFollowingComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bIsVisualizationComponent](ue_ue.PathFollowingComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bNetAddressable](ue_ue.PathFollowingComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bReplicates](ue_ue.PathFollowingComponent.md#breplicates)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Activate](ue_ue.PathFollowingComponent.md#activate)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[AddTickPrerequisiteActor](ue_ue.PathFollowingComponent.md#addtickprerequisiteactor)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[AddTickPrerequisiteComponent](ue_ue.PathFollowingComponent.md#addtickprerequisitecomponent)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ComponentHasTag](ue_ue.PathFollowingComponent.md#componenthastag)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[CreateDefaultSubobject](ue_ue.PathFollowingComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Deactivate](ue_ue.PathFollowingComponent.md#deactivate)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ExecuteUbergraph](ue_ue.PathFollowingComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetClass](ue_ue.PathFollowingComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetComponentTickInterval](ue_ue.PathFollowingComponent.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetName](ue_ue.PathFollowingComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetOuter](ue_ue.PathFollowingComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetOwner](ue_ue.PathFollowingComponent.md#getowner)

___

### GetPathActionType

▸ **GetPathActionType**(): [`EPathFollowingAction`](../enums/ue_ue.EPathFollowingAction.md)

#### Returns

[`EPathFollowingAction`](../enums/ue_ue.EPathFollowingAction.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetPathActionType](ue_ue.PathFollowingComponent.md#getpathactiontype)

___

### GetPathDestination

▸ **GetPathDestination**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetPathDestination](ue_ue.PathFollowingComponent.md#getpathdestination)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetWorld](ue_ue.PathFollowingComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[IsActive](ue_ue.PathFollowingComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[IsBeingDestroyed](ue_ue.PathFollowingComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[IsComponentTickEnabled](ue_ue.PathFollowingComponent.md#iscomponenttickenabled)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[K2_DestroyComponent](ue_ue.PathFollowingComponent.md#k2_destroycomponent)

___

### OnActorBump

▸ **OnActorBump**(`SelfActor`, `OtherActor`, `NormalImpulse`, `Hit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SelfActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `NormalImpulse` | [`Vector`](ue_ue_s.Vector.md) |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnActorBump](ue_ue.PathFollowingComponent.md#onactorbump)

___

### OnNavDataRegistered

▸ **OnNavDataRegistered**(`NavData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NavData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationData`](ue_ue.NavigationData.md)\> |

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnNavDataRegistered](ue_ue.PathFollowingComponent.md#onnavdataregistered)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnRep_IsActive](ue_ue.PathFollowingComponent.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ReceiveBeginPlay](ue_ue.PathFollowingComponent.md#receivebeginplay)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ReceiveEndPlay](ue_ue.PathFollowingComponent.md#receiveendplay)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ReceiveTick](ue_ue.PathFollowingComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[RegisterComponent](ue_ue.PathFollowingComponent.md#registercomponent)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[RemoveTickPrerequisiteActor](ue_ue.PathFollowingComponent.md#removetickprerequisiteactor)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.PathFollowingComponent.md#removetickprerequisitecomponent)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetActive](ue_ue.PathFollowingComponent.md#setactive)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetAutoActivate](ue_ue.PathFollowingComponent.md#setautoactivate)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetComponentTickEnabled](ue_ue.PathFollowingComponent.md#setcomponenttickenabled)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetComponentTickInterval](ue_ue.PathFollowingComponent.md#setcomponenttickinterval)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetIsReplicated](ue_ue.PathFollowingComponent.md#setisreplicated)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetTickGroup](ue_ue.PathFollowingComponent.md#settickgroup)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetTickableWhenPaused](ue_ue.PathFollowingComponent.md#settickablewhenpaused)

___

### SuspendCrowdSteering

▸ **SuspendCrowdSteering**(`bSuspend`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSuspend` | `boolean` |

#### Returns

`void`

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ToggleActive](ue_ue.PathFollowingComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Find](ue_ue.PathFollowingComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Load](ue_ue.PathFollowingComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[StaticClass](ue_ue.PathFollowingComponent.md#staticclass)
