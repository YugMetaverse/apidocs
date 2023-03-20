[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BehaviorTreeComponent

# Class: BehaviorTreeComponent

[ue/ue](../modules/ue_ue.md).BehaviorTreeComponent

## Hierarchy

- [`BrainComponent`](ue_ue.BrainComponent.md)

  ↳ **`BehaviorTreeComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.BehaviorTreeComponent.md#constructor)

### Properties

- [AIOwner](ue_ue.BehaviorTreeComponent.md#aiowner)
- [AssetUserData](ue_ue.BehaviorTreeComponent.md#assetuserdata)
- [BlackboardComp](ue_ue.BehaviorTreeComponent.md#blackboardcomp)
- [ComponentTags](ue_ue.BehaviorTreeComponent.md#componenttags)
- [CreationMethod](ue_ue.BehaviorTreeComponent.md#creationmethod)
- [NodeInstances](ue_ue.BehaviorTreeComponent.md#nodeinstances)
- [OnComponentActivated](ue_ue.BehaviorTreeComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.BehaviorTreeComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.BehaviorTreeComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.BehaviorTreeComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.BehaviorTreeComponent.md#__tid_actorcomponent__)
- [\_\_tid\_BehaviorTreeComponent\_\_](ue_ue.BehaviorTreeComponent.md#__tid_behaviortreecomponent__)
- [\_\_tid\_BrainComponent\_\_](ue_ue.BehaviorTreeComponent.md#__tid_braincomponent__)
- [\_\_tid\_Object\_\_](ue_ue.BehaviorTreeComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.BehaviorTreeComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.BehaviorTreeComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.BehaviorTreeComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.BehaviorTreeComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.BehaviorTreeComponent.md#binstancecomponent)
- [bIsActive](ue_ue.BehaviorTreeComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.BehaviorTreeComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.BehaviorTreeComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.BehaviorTreeComponent.md#bnetaddressable)
- [bReplicates](ue_ue.BehaviorTreeComponent.md#breplicates)

### Methods

- [Activate](ue_ue.BehaviorTreeComponent.md#activate)
- [AddCooldownTagDuration](ue_ue.BehaviorTreeComponent.md#addcooldowntagduration)
- [AddTickPrerequisiteActor](ue_ue.BehaviorTreeComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.BehaviorTreeComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.BehaviorTreeComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.BehaviorTreeComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.BehaviorTreeComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.BehaviorTreeComponent.md#executeubergraph)
- [GetClass](ue_ue.BehaviorTreeComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.BehaviorTreeComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.BehaviorTreeComponent.md#getname)
- [GetOuter](ue_ue.BehaviorTreeComponent.md#getouter)
- [GetOwner](ue_ue.BehaviorTreeComponent.md#getowner)
- [GetTagCooldownEndTime](ue_ue.BehaviorTreeComponent.md#gettagcooldownendtime)
- [GetWorld](ue_ue.BehaviorTreeComponent.md#getworld)
- [IsActive](ue_ue.BehaviorTreeComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.BehaviorTreeComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.BehaviorTreeComponent.md#iscomponenttickenabled)
- [IsPaused](ue_ue.BehaviorTreeComponent.md#ispaused)
- [IsRunning](ue_ue.BehaviorTreeComponent.md#isrunning)
- [K2\_DestroyComponent](ue_ue.BehaviorTreeComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.BehaviorTreeComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.BehaviorTreeComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.BehaviorTreeComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.BehaviorTreeComponent.md#receivetick)
- [RegisterComponent](ue_ue.BehaviorTreeComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.BehaviorTreeComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.BehaviorTreeComponent.md#removetickprerequisitecomponent)
- [RestartLogic](ue_ue.BehaviorTreeComponent.md#restartlogic)
- [SetActive](ue_ue.BehaviorTreeComponent.md#setactive)
- [SetAutoActivate](ue_ue.BehaviorTreeComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.BehaviorTreeComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.BehaviorTreeComponent.md#setcomponenttickinterval)
- [SetDynamicSubtree](ue_ue.BehaviorTreeComponent.md#setdynamicsubtree)
- [SetIsReplicated](ue_ue.BehaviorTreeComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.BehaviorTreeComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.BehaviorTreeComponent.md#settickablewhenpaused)
- [StopLogic](ue_ue.BehaviorTreeComponent.md#stoplogic)
- [ToggleActive](ue_ue.BehaviorTreeComponent.md#toggleactive)
- [Find](ue_ue.BehaviorTreeComponent.md#find)
- [Load](ue_ue.BehaviorTreeComponent.md#load)
- [StaticClass](ue_ue.BehaviorTreeComponent.md#staticclass)

## Constructors

### constructor

• **new BehaviorTreeComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BrainComponent](ue_ue.BrainComponent.md).[constructor](ue_ue.BrainComponent.md#constructor)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[AIOwner](ue_ue.BrainComponent.md#aiowner)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[AssetUserData](ue_ue.BrainComponent.md#assetuserdata)

___

### BlackboardComp

• **BlackboardComp**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[BlackboardComp](ue_ue.BrainComponent.md#blackboardcomp)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[ComponentTags](ue_ue.BrainComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[CreationMethod](ue_ue.BrainComponent.md#creationmethod)

___

### NodeInstances

• **NodeInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTNode`](ue_ue.BTNode.md)\>

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[OnComponentActivated](ue_ue.BrainComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[OnComponentDeactivated](ue_ue.BrainComponent.md#oncomponentdeactivated)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[PrimaryComponentTick](ue_ue.BrainComponent.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[UCSModifiedProperties](ue_ue.BrainComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[__tid_ActorComponent__](ue_ue.BrainComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_BehaviorTreeComponent\_\_

• **\_\_tid\_BehaviorTreeComponent\_\_**: `boolean`

___

### \_\_tid\_BrainComponent\_\_

• **\_\_tid\_BrainComponent\_\_**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[__tid_BrainComponent__](ue_ue.BrainComponent.md#__tid_braincomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[__tid_Object__](ue_ue.BrainComponent.md#__tid_object__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bAutoActivate](ue_ue.BrainComponent.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bCanEverAffectNavigation](ue_ue.BrainComponent.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bCreatedByConstructionScript](ue_ue.BrainComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bEditableWhenInherited](ue_ue.BrainComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bInstanceComponent](ue_ue.BrainComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bIsActive](ue_ue.BrainComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bIsEditorOnly](ue_ue.BrainComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bIsVisualizationComponent](ue_ue.BrainComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bNetAddressable](ue_ue.BrainComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[bReplicates](ue_ue.BrainComponent.md#breplicates)

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

[BrainComponent](ue_ue.BrainComponent.md).[Activate](ue_ue.BrainComponent.md#activate)

___

### AddCooldownTagDuration

▸ **AddCooldownTagDuration**(`CooldownTag`, `CooldownDuration`, `bAddToExistingDuration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CooldownTag` | [`GameplayTag`](ue_ue.GameplayTag.md) |
| `CooldownDuration` | `number` |
| `bAddToExistingDuration` | `boolean` |

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

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[AddTickPrerequisiteActor](ue_ue.BrainComponent.md#addtickprerequisiteactor)

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

[BrainComponent](ue_ue.BrainComponent.md).[AddTickPrerequisiteComponent](ue_ue.BrainComponent.md#addtickprerequisitecomponent)

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

[BrainComponent](ue_ue.BrainComponent.md).[ComponentHasTag](ue_ue.BrainComponent.md#componenthastag)

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

[BrainComponent](ue_ue.BrainComponent.md).[CreateDefaultSubobject](ue_ue.BrainComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[Deactivate](ue_ue.BrainComponent.md#deactivate)

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

[BrainComponent](ue_ue.BrainComponent.md).[ExecuteUbergraph](ue_ue.BrainComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[GetClass](ue_ue.BrainComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[GetComponentTickInterval](ue_ue.BrainComponent.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[GetName](ue_ue.BrainComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[GetOuter](ue_ue.BrainComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[GetOwner](ue_ue.BrainComponent.md#getowner)

___

### GetTagCooldownEndTime

▸ **GetTagCooldownEndTime**(`CooldownTag`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CooldownTag` | [`GameplayTag`](ue_ue.GameplayTag.md) |

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[GetWorld](ue_ue.BrainComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[IsActive](ue_ue.BrainComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[IsBeingDestroyed](ue_ue.BrainComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[IsComponentTickEnabled](ue_ue.BrainComponent.md#iscomponenttickenabled)

___

### IsPaused

▸ **IsPaused**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[IsPaused](ue_ue.BrainComponent.md#ispaused)

___

### IsRunning

▸ **IsRunning**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[IsRunning](ue_ue.BrainComponent.md#isrunning)

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

[BrainComponent](ue_ue.BrainComponent.md).[K2_DestroyComponent](ue_ue.BrainComponent.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[OnRep_IsActive](ue_ue.BrainComponent.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[ReceiveBeginPlay](ue_ue.BrainComponent.md#receivebeginplay)

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

[BrainComponent](ue_ue.BrainComponent.md).[ReceiveEndPlay](ue_ue.BrainComponent.md#receiveendplay)

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

[BrainComponent](ue_ue.BrainComponent.md).[ReceiveTick](ue_ue.BrainComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[RegisterComponent](ue_ue.BrainComponent.md#registercomponent)

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

[BrainComponent](ue_ue.BrainComponent.md).[RemoveTickPrerequisiteActor](ue_ue.BrainComponent.md#removetickprerequisiteactor)

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

[BrainComponent](ue_ue.BrainComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.BrainComponent.md#removetickprerequisitecomponent)

___

### RestartLogic

▸ **RestartLogic**(): `void`

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[RestartLogic](ue_ue.BrainComponent.md#restartlogic)

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

[BrainComponent](ue_ue.BrainComponent.md).[SetActive](ue_ue.BrainComponent.md#setactive)

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

[BrainComponent](ue_ue.BrainComponent.md).[SetAutoActivate](ue_ue.BrainComponent.md#setautoactivate)

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

[BrainComponent](ue_ue.BrainComponent.md).[SetComponentTickEnabled](ue_ue.BrainComponent.md#setcomponenttickenabled)

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

[BrainComponent](ue_ue.BrainComponent.md).[SetComponentTickInterval](ue_ue.BrainComponent.md#setcomponenttickinterval)

___

### SetDynamicSubtree

▸ **SetDynamicSubtree**(`InjectTag`, `BehaviorAsset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InjectTag` | [`GameplayTag`](ue_ue.GameplayTag.md) |
| `BehaviorAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BehaviorTree`](ue_ue.BehaviorTree.md)\> |

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

[BrainComponent](ue_ue.BrainComponent.md).[SetIsReplicated](ue_ue.BrainComponent.md#setisreplicated)

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

[BrainComponent](ue_ue.BrainComponent.md).[SetTickGroup](ue_ue.BrainComponent.md#settickgroup)

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

[BrainComponent](ue_ue.BrainComponent.md).[SetTickableWhenPaused](ue_ue.BrainComponent.md#settickablewhenpaused)

___

### StopLogic

▸ **StopLogic**(`Reason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Reason` | `string` |

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[StopLogic](ue_ue.BrainComponent.md#stoplogic)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[BrainComponent](ue_ue.BrainComponent.md).[ToggleActive](ue_ue.BrainComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Overrides

[BrainComponent](ue_ue.BrainComponent.md).[Find](ue_ue.BrainComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Overrides

[BrainComponent](ue_ue.BrainComponent.md).[Load](ue_ue.BrainComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BrainComponent](ue_ue.BrainComponent.md).[StaticClass](ue_ue.BrainComponent.md#staticclass)
