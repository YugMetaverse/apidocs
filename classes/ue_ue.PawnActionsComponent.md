[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnActionsComponent

# Class: PawnActionsComponent

[ue/ue](../modules/ue_ue.md).PawnActionsComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`PawnActionsComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PawnActionsComponent.md#constructor)

### Properties

- [ActionEvents](ue_ue.PawnActionsComponent.md#actionevents)
- [ActionStacks](ue_ue.PawnActionsComponent.md#actionstacks)
- [AssetUserData](ue_ue.PawnActionsComponent.md#assetuserdata)
- [ComponentTags](ue_ue.PawnActionsComponent.md#componenttags)
- [ControlledPawn](ue_ue.PawnActionsComponent.md#controlledpawn)
- [CreationMethod](ue_ue.PawnActionsComponent.md#creationmethod)
- [CurrentAction](ue_ue.PawnActionsComponent.md#currentaction)
- [OnComponentActivated](ue_ue.PawnActionsComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PawnActionsComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.PawnActionsComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.PawnActionsComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PawnActionsComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PawnActionsComponent.md#__tid_object__)
- [\_\_tid\_PawnActionsComponent\_\_](ue_ue.PawnActionsComponent.md#__tid_pawnactionscomponent__)
- [bAutoActivate](ue_ue.PawnActionsComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.PawnActionsComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.PawnActionsComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PawnActionsComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.PawnActionsComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PawnActionsComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PawnActionsComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PawnActionsComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PawnActionsComponent.md#bnetaddressable)
- [bReplicates](ue_ue.PawnActionsComponent.md#breplicates)

### Methods

- [Activate](ue_ue.PawnActionsComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PawnActionsComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PawnActionsComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PawnActionsComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PawnActionsComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PawnActionsComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.PawnActionsComponent.md#executeubergraph)
- [GetClass](ue_ue.PawnActionsComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PawnActionsComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.PawnActionsComponent.md#getname)
- [GetOuter](ue_ue.PawnActionsComponent.md#getouter)
- [GetOwner](ue_ue.PawnActionsComponent.md#getowner)
- [GetWorld](ue_ue.PawnActionsComponent.md#getworld)
- [IsActive](ue_ue.PawnActionsComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.PawnActionsComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PawnActionsComponent.md#iscomponenttickenabled)
- [K2\_AbortAction](ue_ue.PawnActionsComponent.md#k2_abortaction)
- [K2\_DestroyComponent](ue_ue.PawnActionsComponent.md#k2_destroycomponent)
- [K2\_ForceAbortAction](ue_ue.PawnActionsComponent.md#k2_forceabortaction)
- [K2\_PushAction](ue_ue.PawnActionsComponent.md#k2_pushaction)
- [OnRep\_IsActive](ue_ue.PawnActionsComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.PawnActionsComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PawnActionsComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PawnActionsComponent.md#receivetick)
- [RegisterComponent](ue_ue.PawnActionsComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PawnActionsComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PawnActionsComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.PawnActionsComponent.md#setactive)
- [SetAutoActivate](ue_ue.PawnActionsComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PawnActionsComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PawnActionsComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.PawnActionsComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.PawnActionsComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PawnActionsComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.PawnActionsComponent.md#toggleactive)
- [Find](ue_ue.PawnActionsComponent.md#find)
- [K2\_PerformAction](ue_ue.PawnActionsComponent.md#k2_performaction)
- [Load](ue_ue.PawnActionsComponent.md#load)
- [StaticClass](ue_ue.PawnActionsComponent.md#staticclass)

## Constructors

### constructor

• **new PawnActionsComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

## Properties

### ActionEvents

• **ActionEvents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PawnActionEvent`](ue_ue.PawnActionEvent.md)\>

___

### ActionStacks

• **ActionStacks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PawnActionStack`](ue_ue.PawnActionStack.md)\>

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

### ControlledPawn

• **ControlledPawn**: [`Pawn`](ue_ue.Pawn.md)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[CreationMethod](ue_ue.ActorComponent.md#creationmethod)

___

### CurrentAction

• **CurrentAction**: [`PawnAction`](ue_ue.PawnAction.md)

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

### \_\_tid\_PawnActionsComponent\_\_

• **\_\_tid\_PawnActionsComponent\_\_**: `boolean`

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

### K2\_AbortAction

▸ **K2_AbortAction**(`ActionToAbort`): [`EPawnActionAbortState`](../enums/ue_ue.EPawnActionAbortState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionToAbort` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PawnAction`](ue_ue.PawnAction.md)\> |

#### Returns

[`EPawnActionAbortState`](../enums/ue_ue.EPawnActionAbortState.md)

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

### K2\_ForceAbortAction

▸ **K2_ForceAbortAction**(`ActionToAbort`): [`EPawnActionAbortState`](../enums/ue_ue.EPawnActionAbortState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionToAbort` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PawnAction`](ue_ue.PawnAction.md)\> |

#### Returns

[`EPawnActionAbortState`](../enums/ue_ue.EPawnActionAbortState.md)

___

### K2\_PushAction

▸ **K2_PushAction**(`NewAction`, `Priority`, `Instigator?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PawnAction`](ue_ue.PawnAction.md)\> |
| `Priority` | [`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md) |
| `Instigator?` | [`Object`](ue_ue.Object.md) |

#### Returns

`boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### K2\_PerformAction

▸ `Static` **K2_PerformAction**(`Pawn`, `Action`, `Priority?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `Action` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PawnAction`](ue_ue.PawnAction.md)\> |
| `Priority?` | [`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md) |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
