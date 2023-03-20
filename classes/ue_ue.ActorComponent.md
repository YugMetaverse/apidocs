[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorComponent

# Class: ActorComponent

[ue/ue](../modules/ue_ue.md).ActorComponent

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ActorComponent`**

  ↳↳ [`MovementComponent`](ue_ue.MovementComponent.md)

  ↳↳ [`InputComponent`](ue_ue.InputComponent.md)

  ↳↳ [`SceneComponent`](ue_ue.SceneComponent.md)

  ↳↳ [`ActorSequenceComponent`](ue_ue.ActorSequenceComponent.md)

  ↳↳ [`ViewportDragOperationComponent`](ue_ue.ViewportDragOperationComponent.md)

  ↳↳ [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

  ↳↳ [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

  ↳↳ [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

  ↳↳ [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

  ↳↳ [`BrainComponent`](ue_ue.BrainComponent.md)

  ↳↳ [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

  ↳↳ [`AIPerceptionStimuliSourceComponent`](ue_ue.AIPerceptionStimuliSourceComponent.md)

  ↳↳ [`ApplicationLifecycleComponent`](ue_ue.ApplicationLifecycleComponent.md)

  ↳↳ [`ARTrackableNotifyComponent`](ue_ue.ARTrackableNotifyComponent.md)

  ↳↳ [`FieldNodeBase`](ue_ue.FieldNodeBase.md)

  ↳↳ [`ChaosDebugDrawComponent`](ue_ue.ChaosDebugDrawComponent.md)

  ↳↳ [`ChaosEventListenerComponent`](ue_ue.ChaosEventListenerComponent.md)

  ↳↳ [`FieldSystemMetaData`](ue_ue.FieldSystemMetaData.md)

  ↳↳ [`GeometryCollectionDebugDrawComponent`](ue_ue.GeometryCollectionDebugDrawComponent.md)

  ↳↳ [`EditorUtilityActorComponent`](ue_ue.EditorUtilityActorComponent.md)

  ↳↳ [`InAppPurchaseComponent`](ue_ue.InAppPurchaseComponent.md)

  ↳↳ [`MagicLeapHandMeshingComponent`](ue_ue.MagicLeapHandMeshingComponent.md)

  ↳↳ [`VRNotificationsComponent`](ue_ue.VRNotificationsComponent.md)

  ↳↳ [`MagicLeapRaycastComponent`](ue_ue.MagicLeapRaycastComponent.md)

  ↳↳ [`MagicLeapTouchpadGesturesComponent`](ue_ue.MagicLeapTouchpadGesturesComponent.md)

  ↳↳ [`NavigationInvokerComponent`](ue_ue.NavigationInvokerComponent.md)

  ↳↳ [`NavRelevantComponent`](ue_ue.NavRelevantComponent.md)

  ↳↳ [`PawnNoiseEmitterComponent`](ue_ue.PawnNoiseEmitterComponent.md)

  ↳↳ [`PawnSensingComponent`](ue_ue.PawnSensingComponent.md)

  ↳↳ [`PhysicalAnimationComponent`](ue_ue.PhysicalAnimationComponent.md)

  ↳↳ [`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

  ↳↳ [`PlatformEventsComponent`](ue_ue.PlatformEventsComponent.md)

  ↳↳ [`ProceduralFoliageComponent`](ue_ue.ProceduralFoliageComponent.md)

  ↳↳ [`SkeletalMeshSimulationComponent`](ue_ue.SkeletalMeshSimulationComponent.md)

  ↳↳ [`StaticMeshSimulationComponent`](ue_ue.StaticMeshSimulationComponent.md)

  ↳↳ [`SteamVRChaperoneComponent`](ue_ue.SteamVRChaperoneComponent.md)

  ↳↳ [`SteamVRTrackingReferences`](ue_ue.SteamVRTrackingReferences.md)

  ↳↳ [`TimelineComponent`](ue_ue.TimelineComponent.md)

  ↳↳ [`VOIPTalker`](ue_ue.VOIPTalker.md)

  ↳↳ [`ActorComp_C`](ue_ue_bp.Game.ActorComp.ActorComp_C.md)

  ↳↳ [`MyTestActorComp_C`](ue_ue_bp.Game.Blueprints.TypeScript.MyTestActorComp.MyTestActorComp_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ActorComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.ActorComponent.md#assetuserdata)
- [ComponentTags](ue_ue.ActorComponent.md#componenttags)
- [CreationMethod](ue_ue.ActorComponent.md#creationmethod)
- [OnComponentActivated](ue_ue.ActorComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.ActorComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ActorComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.ActorComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.ActorComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.ActorComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.ActorComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.ActorComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.ActorComponent.md#binstancecomponent)
- [bIsActive](ue_ue.ActorComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.ActorComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ActorComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.ActorComponent.md#bnetaddressable)
- [bReplicates](ue_ue.ActorComponent.md#breplicates)

### Methods

- [Activate](ue_ue.ActorComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.ActorComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ActorComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.ActorComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.ActorComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.ActorComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.ActorComponent.md#executeubergraph)
- [GetClass](ue_ue.ActorComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.ActorComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.ActorComponent.md#getname)
- [GetOuter](ue_ue.ActorComponent.md#getouter)
- [GetOwner](ue_ue.ActorComponent.md#getowner)
- [GetWorld](ue_ue.ActorComponent.md#getworld)
- [IsActive](ue_ue.ActorComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.ActorComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ActorComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.ActorComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.ActorComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.ActorComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ActorComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.ActorComponent.md#receivetick)
- [RegisterComponent](ue_ue.ActorComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ActorComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ActorComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.ActorComponent.md#setactive)
- [SetAutoActivate](ue_ue.ActorComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.ActorComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ActorComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.ActorComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.ActorComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ActorComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.ActorComponent.md#toggleactive)
- [Find](ue_ue.ActorComponent.md#find)
- [Load](ue_ue.ActorComponent.md#load)
- [StaticClass](ue_ue.ActorComponent.md#staticclass)

## Constructors

### constructor

• **new ActorComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

___

### bIsActive

• **bIsActive**: `boolean`

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

___

### bNetAddressable

• **bNetAddressable**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

## Methods

### Activate

▸ **Activate**(`bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReset?` | `boolean` |

#### Returns

`void`

___

### AddTickPrerequisiteActor

▸ **AddTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### AddTickPrerequisiteComponent

▸ **AddTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

___

### ComponentHasTag

▸ **ComponentHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(`EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

___

### ReceiveTick

▸ **ReceiveTick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

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

___

### RemoveTickPrerequisiteComponent

▸ **RemoveTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

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

___

### SetAutoActivate

▸ **SetAutoActivate**(`bNewAutoActivate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAutoActivate` | `boolean` |

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

___

### SetComponentTickInterval

▸ **SetComponentTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

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

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

___

### SetTickableWhenPaused

▸ **SetTickableWhenPaused**(`bTickableWhenPaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTickableWhenPaused` | `boolean` |

#### Returns

`void`

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ActorComponent`](ue_ue.ActorComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ActorComponent`](ue_ue.ActorComponent.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ActorComponent`](ue_ue.ActorComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ActorComponent`](ue_ue.ActorComponent.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
