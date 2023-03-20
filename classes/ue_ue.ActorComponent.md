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

#### Defined in

[ue/ue.d.ts:288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L288)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

## Methods

### Activate

▸ **Activate**(`bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReset?` | `boolean` |

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L333)

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

#### Defined in

[ue/ue.d.ts:334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L334)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L332)
