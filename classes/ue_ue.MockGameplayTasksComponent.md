[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MockGameplayTasksComponent

# Class: MockGameplayTasksComponent

[ue/ue](../modules/ue_ue.md).MockGameplayTasksComponent

## Hierarchy

- [`GameplayTasksComponent`](ue_ue.GameplayTasksComponent.md)

  ↳ **`MockGameplayTasksComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.MockGameplayTasksComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.MockGameplayTasksComponent.md#assetuserdata)
- [ComponentTags](ue_ue.MockGameplayTasksComponent.md#componenttags)
- [CreationMethod](ue_ue.MockGameplayTasksComponent.md#creationmethod)
- [KnownTasks](ue_ue.MockGameplayTasksComponent.md#knowntasks)
- [OnClaimedResourcesChange](ue_ue.MockGameplayTasksComponent.md#onclaimedresourceschange)
- [OnComponentActivated](ue_ue.MockGameplayTasksComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.MockGameplayTasksComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.MockGameplayTasksComponent.md#primarycomponenttick)
- [SimulatedTasks](ue_ue.MockGameplayTasksComponent.md#simulatedtasks)
- [TaskPriorityQueue](ue_ue.MockGameplayTasksComponent.md#taskpriorityqueue)
- [TickingTasks](ue_ue.MockGameplayTasksComponent.md#tickingtasks)
- [UCSModifiedProperties](ue_ue.MockGameplayTasksComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.MockGameplayTasksComponent.md#__tid_actorcomponent__)
- [\_\_tid\_GameplayTasksComponent\_\_](ue_ue.MockGameplayTasksComponent.md#__tid_gameplaytaskscomponent__)
- [\_\_tid\_MockGameplayTasksComponent\_\_](ue_ue.MockGameplayTasksComponent.md#__tid_mockgameplaytaskscomponent__)
- [\_\_tid\_Object\_\_](ue_ue.MockGameplayTasksComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.MockGameplayTasksComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.MockGameplayTasksComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.MockGameplayTasksComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.MockGameplayTasksComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.MockGameplayTasksComponent.md#binstancecomponent)
- [bIsActive](ue_ue.MockGameplayTasksComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.MockGameplayTasksComponent.md#biseditoronly)
- [bIsNetDirty](ue_ue.MockGameplayTasksComponent.md#bisnetdirty)
- [bIsVisualizationComponent](ue_ue.MockGameplayTasksComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.MockGameplayTasksComponent.md#bnetaddressable)
- [bReplicates](ue_ue.MockGameplayTasksComponent.md#breplicates)

### Methods

- [Activate](ue_ue.MockGameplayTasksComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.MockGameplayTasksComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.MockGameplayTasksComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.MockGameplayTasksComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.MockGameplayTasksComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.MockGameplayTasksComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.MockGameplayTasksComponent.md#executeubergraph)
- [GetClass](ue_ue.MockGameplayTasksComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.MockGameplayTasksComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.MockGameplayTasksComponent.md#getname)
- [GetOuter](ue_ue.MockGameplayTasksComponent.md#getouter)
- [GetOwner](ue_ue.MockGameplayTasksComponent.md#getowner)
- [GetWorld](ue_ue.MockGameplayTasksComponent.md#getworld)
- [IsActive](ue_ue.MockGameplayTasksComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.MockGameplayTasksComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.MockGameplayTasksComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.MockGameplayTasksComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.MockGameplayTasksComponent.md#onrep_isactive)
- [OnRep\_SimulatedTasks](ue_ue.MockGameplayTasksComponent.md#onrep_simulatedtasks)
- [ReceiveBeginPlay](ue_ue.MockGameplayTasksComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.MockGameplayTasksComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.MockGameplayTasksComponent.md#receivetick)
- [RegisterComponent](ue_ue.MockGameplayTasksComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.MockGameplayTasksComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.MockGameplayTasksComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.MockGameplayTasksComponent.md#setactive)
- [SetAutoActivate](ue_ue.MockGameplayTasksComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.MockGameplayTasksComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.MockGameplayTasksComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.MockGameplayTasksComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.MockGameplayTasksComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.MockGameplayTasksComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.MockGameplayTasksComponent.md#toggleactive)
- [Find](ue_ue.MockGameplayTasksComponent.md#find)
- [K2\_RunGameplayTask](ue_ue.MockGameplayTasksComponent.md#k2_rungameplaytask)
- [Load](ue_ue.MockGameplayTasksComponent.md#load)
- [StaticClass](ue_ue.MockGameplayTasksComponent.md#staticclass)

## Constructors

### constructor

• **new MockGameplayTasksComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[constructor](ue_ue.GameplayTasksComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[AssetUserData](ue_ue.GameplayTasksComponent.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ComponentTags](ue_ue.GameplayTasksComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[CreationMethod](ue_ue.GameplayTasksComponent.md#creationmethod)

___

### KnownTasks

• **KnownTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[KnownTasks](ue_ue.GameplayTasksComponent.md#knowntasks)

___

### OnClaimedResourcesChange

• **OnClaimedResourcesChange**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewlyClaimed`: [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md), `FreshlyReleased`: [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md)) => `void`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnClaimedResourcesChange](ue_ue.GameplayTasksComponent.md#onclaimedresourceschange)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnComponentActivated](ue_ue.GameplayTasksComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnComponentDeactivated](ue_ue.GameplayTasksComponent.md#oncomponentdeactivated)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[PrimaryComponentTick](ue_ue.GameplayTasksComponent.md#primarycomponenttick)

___

### SimulatedTasks

• **SimulatedTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SimulatedTasks](ue_ue.GameplayTasksComponent.md#simulatedtasks)

___

### TaskPriorityQueue

• **TaskPriorityQueue**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[TaskPriorityQueue](ue_ue.GameplayTasksComponent.md#taskpriorityqueue)

___

### TickingTasks

• **TickingTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[TickingTasks](ue_ue.GameplayTasksComponent.md#tickingtasks)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[UCSModifiedProperties](ue_ue.GameplayTasksComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[__tid_ActorComponent__](ue_ue.GameplayTasksComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_GameplayTasksComponent\_\_

• **\_\_tid\_GameplayTasksComponent\_\_**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[__tid_GameplayTasksComponent__](ue_ue.GameplayTasksComponent.md#__tid_gameplaytaskscomponent__)

___

### \_\_tid\_MockGameplayTasksComponent\_\_

• **\_\_tid\_MockGameplayTasksComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[__tid_Object__](ue_ue.GameplayTasksComponent.md#__tid_object__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bAutoActivate](ue_ue.GameplayTasksComponent.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bCanEverAffectNavigation](ue_ue.GameplayTasksComponent.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bCreatedByConstructionScript](ue_ue.GameplayTasksComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bEditableWhenInherited](ue_ue.GameplayTasksComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bInstanceComponent](ue_ue.GameplayTasksComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsActive](ue_ue.GameplayTasksComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsEditorOnly](ue_ue.GameplayTasksComponent.md#biseditoronly)

___

### bIsNetDirty

• **bIsNetDirty**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsNetDirty](ue_ue.GameplayTasksComponent.md#bisnetdirty)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsVisualizationComponent](ue_ue.GameplayTasksComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bNetAddressable](ue_ue.GameplayTasksComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bReplicates](ue_ue.GameplayTasksComponent.md#breplicates)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[Activate](ue_ue.GameplayTasksComponent.md#activate)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[AddTickPrerequisiteActor](ue_ue.GameplayTasksComponent.md#addtickprerequisiteactor)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[AddTickPrerequisiteComponent](ue_ue.GameplayTasksComponent.md#addtickprerequisitecomponent)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ComponentHasTag](ue_ue.GameplayTasksComponent.md#componenthastag)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[CreateDefaultSubobject](ue_ue.GameplayTasksComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[Deactivate](ue_ue.GameplayTasksComponent.md#deactivate)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ExecuteUbergraph](ue_ue.GameplayTasksComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetClass](ue_ue.GameplayTasksComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetComponentTickInterval](ue_ue.GameplayTasksComponent.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetName](ue_ue.GameplayTasksComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetOuter](ue_ue.GameplayTasksComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetOwner](ue_ue.GameplayTasksComponent.md#getowner)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetWorld](ue_ue.GameplayTasksComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[IsActive](ue_ue.GameplayTasksComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[IsBeingDestroyed](ue_ue.GameplayTasksComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[IsComponentTickEnabled](ue_ue.GameplayTasksComponent.md#iscomponenttickenabled)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[K2_DestroyComponent](ue_ue.GameplayTasksComponent.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnRep_IsActive](ue_ue.GameplayTasksComponent.md#onrep_isactive)

___

### OnRep\_SimulatedTasks

▸ **OnRep_SimulatedTasks**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnRep_SimulatedTasks](ue_ue.GameplayTasksComponent.md#onrep_simulatedtasks)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ReceiveBeginPlay](ue_ue.GameplayTasksComponent.md#receivebeginplay)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ReceiveEndPlay](ue_ue.GameplayTasksComponent.md#receiveendplay)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ReceiveTick](ue_ue.GameplayTasksComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[RegisterComponent](ue_ue.GameplayTasksComponent.md#registercomponent)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[RemoveTickPrerequisiteActor](ue_ue.GameplayTasksComponent.md#removetickprerequisiteactor)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.GameplayTasksComponent.md#removetickprerequisitecomponent)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetActive](ue_ue.GameplayTasksComponent.md#setactive)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetAutoActivate](ue_ue.GameplayTasksComponent.md#setautoactivate)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetComponentTickEnabled](ue_ue.GameplayTasksComponent.md#setcomponenttickenabled)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetComponentTickInterval](ue_ue.GameplayTasksComponent.md#setcomponenttickinterval)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetIsReplicated](ue_ue.GameplayTasksComponent.md#setisreplicated)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetTickGroup](ue_ue.GameplayTasksComponent.md#settickgroup)

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

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SetTickableWhenPaused](ue_ue.GameplayTasksComponent.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ToggleActive](ue_ue.GameplayTasksComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MockGameplayTasksComponent`](ue_ue.MockGameplayTasksComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MockGameplayTasksComponent`](ue_ue.MockGameplayTasksComponent.md)

#### Overrides

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[Find](ue_ue.GameplayTasksComponent.md#find)

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

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[K2_RunGameplayTask](ue_ue.GameplayTasksComponent.md#k2_rungameplaytask)

___

### Load

▸ `Static` **Load**(`InName`): [`MockGameplayTasksComponent`](ue_ue.MockGameplayTasksComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MockGameplayTasksComponent`](ue_ue.MockGameplayTasksComponent.md)

#### Overrides

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[Load](ue_ue.GameplayTasksComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[StaticClass](ue_ue.GameplayTasksComponent.md#staticclass)
