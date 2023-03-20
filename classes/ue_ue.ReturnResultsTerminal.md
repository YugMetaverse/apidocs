[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReturnResultsTerminal

# Class: ReturnResultsTerminal

[ue/ue](../modules/ue_ue.md).ReturnResultsTerminal

## Hierarchy

- [`FieldNodeBase`](ue_ue.FieldNodeBase.md)

  ↳ **`ReturnResultsTerminal`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReturnResultsTerminal.md#constructor)

### Properties

- [AssetUserData](ue_ue.ReturnResultsTerminal.md#assetuserdata)
- [ComponentTags](ue_ue.ReturnResultsTerminal.md#componenttags)
- [CreationMethod](ue_ue.ReturnResultsTerminal.md#creationmethod)
- [OnComponentActivated](ue_ue.ReturnResultsTerminal.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.ReturnResultsTerminal.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.ReturnResultsTerminal.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.ReturnResultsTerminal.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ReturnResultsTerminal.md#__tid_actorcomponent__)
- [\_\_tid\_FieldNodeBase\_\_](ue_ue.ReturnResultsTerminal.md#__tid_fieldnodebase__)
- [\_\_tid\_Object\_\_](ue_ue.ReturnResultsTerminal.md#__tid_object__)
- [\_\_tid\_ReturnResultsTerminal\_\_](ue_ue.ReturnResultsTerminal.md#__tid_returnresultsterminal__)
- [bAutoActivate](ue_ue.ReturnResultsTerminal.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.ReturnResultsTerminal.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.ReturnResultsTerminal.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.ReturnResultsTerminal.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.ReturnResultsTerminal.md#binstancecomponent)
- [bIsActive](ue_ue.ReturnResultsTerminal.md#bisactive)
- [bIsEditorOnly](ue_ue.ReturnResultsTerminal.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ReturnResultsTerminal.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.ReturnResultsTerminal.md#bnetaddressable)
- [bReplicates](ue_ue.ReturnResultsTerminal.md#breplicates)

### Methods

- [Activate](ue_ue.ReturnResultsTerminal.md#activate)
- [AddTickPrerequisiteActor](ue_ue.ReturnResultsTerminal.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ReturnResultsTerminal.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.ReturnResultsTerminal.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.ReturnResultsTerminal.md#createdefaultsubobject)
- [Deactivate](ue_ue.ReturnResultsTerminal.md#deactivate)
- [ExecuteUbergraph](ue_ue.ReturnResultsTerminal.md#executeubergraph)
- [GetClass](ue_ue.ReturnResultsTerminal.md#getclass)
- [GetComponentTickInterval](ue_ue.ReturnResultsTerminal.md#getcomponenttickinterval)
- [GetName](ue_ue.ReturnResultsTerminal.md#getname)
- [GetOuter](ue_ue.ReturnResultsTerminal.md#getouter)
- [GetOwner](ue_ue.ReturnResultsTerminal.md#getowner)
- [GetWorld](ue_ue.ReturnResultsTerminal.md#getworld)
- [IsActive](ue_ue.ReturnResultsTerminal.md#isactive)
- [IsBeingDestroyed](ue_ue.ReturnResultsTerminal.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ReturnResultsTerminal.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.ReturnResultsTerminal.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.ReturnResultsTerminal.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.ReturnResultsTerminal.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ReturnResultsTerminal.md#receiveendplay)
- [ReceiveTick](ue_ue.ReturnResultsTerminal.md#receivetick)
- [RegisterComponent](ue_ue.ReturnResultsTerminal.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ReturnResultsTerminal.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ReturnResultsTerminal.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.ReturnResultsTerminal.md#setactive)
- [SetAutoActivate](ue_ue.ReturnResultsTerminal.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.ReturnResultsTerminal.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ReturnResultsTerminal.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.ReturnResultsTerminal.md#setisreplicated)
- [SetReturnResultsTerminal](ue_ue.ReturnResultsTerminal.md#setreturnresultsterminal)
- [SetTickGroup](ue_ue.ReturnResultsTerminal.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ReturnResultsTerminal.md#settickablewhenpaused)
- [ToggleActive](ue_ue.ReturnResultsTerminal.md#toggleactive)
- [Find](ue_ue.ReturnResultsTerminal.md#find)
- [Load](ue_ue.ReturnResultsTerminal.md#load)
- [StaticClass](ue_ue.ReturnResultsTerminal.md#staticclass)

## Constructors

### constructor

• **new ReturnResultsTerminal**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[constructor](ue_ue.FieldNodeBase.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[AssetUserData](ue_ue.FieldNodeBase.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ComponentTags](ue_ue.FieldNodeBase.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[CreationMethod](ue_ue.FieldNodeBase.md#creationmethod)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[OnComponentActivated](ue_ue.FieldNodeBase.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[OnComponentDeactivated](ue_ue.FieldNodeBase.md#oncomponentdeactivated)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[PrimaryComponentTick](ue_ue.FieldNodeBase.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[UCSModifiedProperties](ue_ue.FieldNodeBase.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[__tid_ActorComponent__](ue_ue.FieldNodeBase.md#__tid_actorcomponent__)

___

### \_\_tid\_FieldNodeBase\_\_

• **\_\_tid\_FieldNodeBase\_\_**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[__tid_FieldNodeBase__](ue_ue.FieldNodeBase.md#__tid_fieldnodebase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[__tid_Object__](ue_ue.FieldNodeBase.md#__tid_object__)

___

### \_\_tid\_ReturnResultsTerminal\_\_

• **\_\_tid\_ReturnResultsTerminal\_\_**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bAutoActivate](ue_ue.FieldNodeBase.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bCanEverAffectNavigation](ue_ue.FieldNodeBase.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bCreatedByConstructionScript](ue_ue.FieldNodeBase.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bEditableWhenInherited](ue_ue.FieldNodeBase.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bInstanceComponent](ue_ue.FieldNodeBase.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bIsActive](ue_ue.FieldNodeBase.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bIsEditorOnly](ue_ue.FieldNodeBase.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bIsVisualizationComponent](ue_ue.FieldNodeBase.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bNetAddressable](ue_ue.FieldNodeBase.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bReplicates](ue_ue.FieldNodeBase.md#breplicates)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Activate](ue_ue.FieldNodeBase.md#activate)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[AddTickPrerequisiteActor](ue_ue.FieldNodeBase.md#addtickprerequisiteactor)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[AddTickPrerequisiteComponent](ue_ue.FieldNodeBase.md#addtickprerequisitecomponent)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ComponentHasTag](ue_ue.FieldNodeBase.md#componenthastag)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[CreateDefaultSubobject](ue_ue.FieldNodeBase.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Deactivate](ue_ue.FieldNodeBase.md#deactivate)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ExecuteUbergraph](ue_ue.FieldNodeBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetClass](ue_ue.FieldNodeBase.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetComponentTickInterval](ue_ue.FieldNodeBase.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetName](ue_ue.FieldNodeBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetOuter](ue_ue.FieldNodeBase.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetOwner](ue_ue.FieldNodeBase.md#getowner)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetWorld](ue_ue.FieldNodeBase.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[IsActive](ue_ue.FieldNodeBase.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[IsBeingDestroyed](ue_ue.FieldNodeBase.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[IsComponentTickEnabled](ue_ue.FieldNodeBase.md#iscomponenttickenabled)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[K2_DestroyComponent](ue_ue.FieldNodeBase.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[OnRep_IsActive](ue_ue.FieldNodeBase.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ReceiveBeginPlay](ue_ue.FieldNodeBase.md#receivebeginplay)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ReceiveEndPlay](ue_ue.FieldNodeBase.md#receiveendplay)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ReceiveTick](ue_ue.FieldNodeBase.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[RegisterComponent](ue_ue.FieldNodeBase.md#registercomponent)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[RemoveTickPrerequisiteActor](ue_ue.FieldNodeBase.md#removetickprerequisiteactor)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[RemoveTickPrerequisiteComponent](ue_ue.FieldNodeBase.md#removetickprerequisitecomponent)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetActive](ue_ue.FieldNodeBase.md#setactive)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetAutoActivate](ue_ue.FieldNodeBase.md#setautoactivate)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetComponentTickEnabled](ue_ue.FieldNodeBase.md#setcomponenttickenabled)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetComponentTickInterval](ue_ue.FieldNodeBase.md#setcomponenttickinterval)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetIsReplicated](ue_ue.FieldNodeBase.md#setisreplicated)

___

### SetReturnResultsTerminal

▸ **SetReturnResultsTerminal**(): [`ReturnResultsTerminal`](ue_ue.ReturnResultsTerminal.md)

#### Returns

[`ReturnResultsTerminal`](ue_ue.ReturnResultsTerminal.md)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetTickGroup](ue_ue.FieldNodeBase.md#settickgroup)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetTickableWhenPaused](ue_ue.FieldNodeBase.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ToggleActive](ue_ue.FieldNodeBase.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReturnResultsTerminal`](ue_ue.ReturnResultsTerminal.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReturnResultsTerminal`](ue_ue.ReturnResultsTerminal.md)

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Find](ue_ue.FieldNodeBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReturnResultsTerminal`](ue_ue.ReturnResultsTerminal.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReturnResultsTerminal`](ue_ue.ReturnResultsTerminal.md)

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Load](ue_ue.FieldNodeBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[StaticClass](ue_ue.FieldNodeBase.md#staticclass)
