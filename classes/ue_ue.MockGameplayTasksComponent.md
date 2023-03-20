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

#### Defined in

[ue/ue.d.ts:50797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50797)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[AssetUserData](ue_ue.GameplayTasksComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ComponentTags](ue_ue.GameplayTasksComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[CreationMethod](ue_ue.GameplayTasksComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### KnownTasks

• **KnownTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[KnownTasks](ue_ue.GameplayTasksComponent.md#knowntasks)

#### Defined in

[ue/ue.d.ts:14926](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14926)

___

### OnClaimedResourcesChange

• **OnClaimedResourcesChange**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewlyClaimed`: [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md), `FreshlyReleased`: [`GameplayResourceSet`](ue_ue.GameplayResourceSet.md)) => `void`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnClaimedResourcesChange](ue_ue.GameplayTasksComponent.md#onclaimedresourceschange)

#### Defined in

[ue/ue.d.ts:14927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14927)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnComponentActivated](ue_ue.GameplayTasksComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnComponentDeactivated](ue_ue.GameplayTasksComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[PrimaryComponentTick](ue_ue.GameplayTasksComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### SimulatedTasks

• **SimulatedTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[SimulatedTasks](ue_ue.GameplayTasksComponent.md#simulatedtasks)

#### Defined in

[ue/ue.d.ts:14923](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14923)

___

### TaskPriorityQueue

• **TaskPriorityQueue**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[TaskPriorityQueue](ue_ue.GameplayTasksComponent.md#taskpriorityqueue)

#### Defined in

[ue/ue.d.ts:14924](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14924)

___

### TickingTasks

• **TickingTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTask`](ue_ue.GameplayTask.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[TickingTasks](ue_ue.GameplayTasksComponent.md#tickingtasks)

#### Defined in

[ue/ue.d.ts:14925](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14925)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[UCSModifiedProperties](ue_ue.GameplayTasksComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[__tid_ActorComponent__](ue_ue.GameplayTasksComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_GameplayTasksComponent\_\_

• **\_\_tid\_GameplayTasksComponent\_\_**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[__tid_GameplayTasksComponent__](ue_ue.GameplayTasksComponent.md#__tid_gameplaytaskscomponent__)

#### Defined in

[ue/ue.d.ts:14934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14934)

___

### \_\_tid\_MockGameplayTasksComponent\_\_

• **\_\_tid\_MockGameplayTasksComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50802)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[__tid_Object__](ue_ue.GameplayTasksComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bAutoActivate](ue_ue.GameplayTasksComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bCanEverAffectNavigation](ue_ue.GameplayTasksComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bCreatedByConstructionScript](ue_ue.GameplayTasksComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bEditableWhenInherited](ue_ue.GameplayTasksComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bInstanceComponent](ue_ue.GameplayTasksComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsActive](ue_ue.GameplayTasksComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsEditorOnly](ue_ue.GameplayTasksComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsNetDirty

• **bIsNetDirty**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsNetDirty](ue_ue.GameplayTasksComponent.md#bisnetdirty)

#### Defined in

[ue/ue.d.ts:14922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14922)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bIsVisualizationComponent](ue_ue.GameplayTasksComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bNetAddressable](ue_ue.GameplayTasksComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[bReplicates](ue_ue.GameplayTasksComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

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

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L306)

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

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L307)

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

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L308)

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

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[Deactivate](ue_ue.GameplayTasksComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetClass](ue_ue.GameplayTasksComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetComponentTickInterval](ue_ue.GameplayTasksComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetName](ue_ue.GameplayTasksComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetOuter](ue_ue.GameplayTasksComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetOwner](ue_ue.GameplayTasksComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[GetWorld](ue_ue.GameplayTasksComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[IsActive](ue_ue.GameplayTasksComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[IsBeingDestroyed](ue_ue.GameplayTasksComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[IsComponentTickEnabled](ue_ue.GameplayTasksComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

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

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnRep_IsActive](ue_ue.GameplayTasksComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### OnRep\_SimulatedTasks

▸ **OnRep_SimulatedTasks**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[OnRep_SimulatedTasks](ue_ue.GameplayTasksComponent.md#onrep_simulatedtasks)

#### Defined in

[ue/ue.d.ts:14928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14928)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ReceiveBeginPlay](ue_ue.GameplayTasksComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L318)

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

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L319)

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

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[RegisterComponent](ue_ue.GameplayTasksComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L321)

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

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L322)

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

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

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

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

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

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

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

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L326)

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

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

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

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

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

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L330)

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

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[ToggleActive](ue_ue.GameplayTasksComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:50799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50799)

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

#### Defined in

[ue/ue.d.ts:14929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14929)

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

#### Defined in

[ue/ue.d.ts:50800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50800)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTasksComponent](ue_ue.GameplayTasksComponent.md).[StaticClass](ue_ue.GameplayTasksComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:50798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50798)
