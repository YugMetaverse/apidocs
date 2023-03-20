[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTasksComponent

# Class: GameplayTasksComponent

[ue/ue](../modules/ue_ue.md).GameplayTasksComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`GameplayTasksComponent`**

  ↳↳ [`MockGameplayTasksComponent`](ue_ue.MockGameplayTasksComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTasksComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.GameplayTasksComponent.md#assetuserdata)
- [ComponentTags](ue_ue.GameplayTasksComponent.md#componenttags)
- [CreationMethod](ue_ue.GameplayTasksComponent.md#creationmethod)
- [KnownTasks](ue_ue.GameplayTasksComponent.md#knowntasks)
- [OnClaimedResourcesChange](ue_ue.GameplayTasksComponent.md#onclaimedresourceschange)
- [OnComponentActivated](ue_ue.GameplayTasksComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.GameplayTasksComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.GameplayTasksComponent.md#primarycomponenttick)
- [SimulatedTasks](ue_ue.GameplayTasksComponent.md#simulatedtasks)
- [TaskPriorityQueue](ue_ue.GameplayTasksComponent.md#taskpriorityqueue)
- [TickingTasks](ue_ue.GameplayTasksComponent.md#tickingtasks)
- [UCSModifiedProperties](ue_ue.GameplayTasksComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.GameplayTasksComponent.md#__tid_actorcomponent__)
- [\_\_tid\_GameplayTasksComponent\_\_](ue_ue.GameplayTasksComponent.md#__tid_gameplaytaskscomponent__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTasksComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.GameplayTasksComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.GameplayTasksComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.GameplayTasksComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.GameplayTasksComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.GameplayTasksComponent.md#binstancecomponent)
- [bIsActive](ue_ue.GameplayTasksComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.GameplayTasksComponent.md#biseditoronly)
- [bIsNetDirty](ue_ue.GameplayTasksComponent.md#bisnetdirty)
- [bIsVisualizationComponent](ue_ue.GameplayTasksComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.GameplayTasksComponent.md#bnetaddressable)
- [bReplicates](ue_ue.GameplayTasksComponent.md#breplicates)

### Methods

- [Activate](ue_ue.GameplayTasksComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.GameplayTasksComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.GameplayTasksComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.GameplayTasksComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.GameplayTasksComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.GameplayTasksComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.GameplayTasksComponent.md#executeubergraph)
- [GetClass](ue_ue.GameplayTasksComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.GameplayTasksComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.GameplayTasksComponent.md#getname)
- [GetOuter](ue_ue.GameplayTasksComponent.md#getouter)
- [GetOwner](ue_ue.GameplayTasksComponent.md#getowner)
- [GetWorld](ue_ue.GameplayTasksComponent.md#getworld)
- [IsActive](ue_ue.GameplayTasksComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.GameplayTasksComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.GameplayTasksComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.GameplayTasksComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.GameplayTasksComponent.md#onrep_isactive)
- [OnRep\_SimulatedTasks](ue_ue.GameplayTasksComponent.md#onrep_simulatedtasks)
- [ReceiveBeginPlay](ue_ue.GameplayTasksComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.GameplayTasksComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.GameplayTasksComponent.md#receivetick)
- [RegisterComponent](ue_ue.GameplayTasksComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.GameplayTasksComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.GameplayTasksComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.GameplayTasksComponent.md#setactive)
- [SetAutoActivate](ue_ue.GameplayTasksComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.GameplayTasksComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.GameplayTasksComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.GameplayTasksComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.GameplayTasksComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.GameplayTasksComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.GameplayTasksComponent.md#toggleactive)
- [Find](ue_ue.GameplayTasksComponent.md#find)
- [K2\_RunGameplayTask](ue_ue.GameplayTasksComponent.md#k2_rungameplaytask)
- [Load](ue_ue.GameplayTasksComponent.md#load)
- [StaticClass](ue_ue.GameplayTasksComponent.md#staticclass)

## Constructors

### constructor

• **new GameplayTasksComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

## Properties

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

### KnownTasks

• **KnownTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

___

### OnClaimedResourcesChange

• **OnClaimedResourcesChange**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewlyClaimed`: [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md), `FreshlyReleased`: [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md)) => `void`\>

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

### SimulatedTasks

• **SimulatedTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

___

### TaskPriorityQueue

• **TaskPriorityQueue**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

___

### TickingTasks

• **TickingTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

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

### \_\_tid\_GameplayTasksComponent\_\_

• **\_\_tid\_GameplayTasksComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_Object__](ue_ue.ActorComponent.md#__tid_object__)

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

### bIsNetDirty

• **bIsNetDirty**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetWorld](ue_ue.ActorComponent.md#getworld)

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

### OnRep\_SimulatedTasks

▸ **OnRep_SimulatedTasks**(): `void`

#### Returns

`void`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### K2\_RunGameplayTask

▸ `Static` **K2_RunGameplayTask**(`TaskOwner`, `Task`, `Priority`, `AdditionalRequiredResources`, `AdditionalClaimedResources`): [`EGameplayTaskRunResult`](../enums/ue_ue.EGameplayTaskRunResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TaskOwner` | [`GameplayTaskOwnerInterface`](ue_ue.GameplayTaskOwnerInterface.md) |
| `Task` | [`$Nullable`](../modules/puerts.md#$nullable)<[`GameplayTask`](ue_ue.GameplayTask.md)\> |
| `Priority` | `number` |
| `AdditionalRequiredResources` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\> |
| `AdditionalClaimedResources` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`EGameplayTaskRunResult`](../enums/ue_ue.EGameplayTaskRunResult.md)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
