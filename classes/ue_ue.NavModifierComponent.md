[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavModifierComponent

# Class: NavModifierComponent

[ue/ue](../modules/ue_ue.md).NavModifierComponent

## Hierarchy

- [`NavRelevantComponent`](ue_ue.NavRelevantComponent.md)

  ↳ **`NavModifierComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavModifierComponent.md#constructor)

### Properties

- [AreaClass](ue_ue.NavModifierComponent.md#areaclass)
- [AssetUserData](ue_ue.NavModifierComponent.md#assetuserdata)
- [CachedNavParent](ue_ue.NavModifierComponent.md#cachednavparent)
- [ComponentTags](ue_ue.NavModifierComponent.md#componenttags)
- [CreationMethod](ue_ue.NavModifierComponent.md#creationmethod)
- [FailsafeExtent](ue_ue.NavModifierComponent.md#failsafeextent)
- [OnComponentActivated](ue_ue.NavModifierComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.NavModifierComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.NavModifierComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.NavModifierComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.NavModifierComponent.md#__tid_actorcomponent__)
- [\_\_tid\_NavModifierComponent\_\_](ue_ue.NavModifierComponent.md#__tid_navmodifiercomponent__)
- [\_\_tid\_NavRelevantComponent\_\_](ue_ue.NavModifierComponent.md#__tid_navrelevantcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.NavModifierComponent.md#__tid_object__)
- [bAttachToOwnersRoot](ue_ue.NavModifierComponent.md#battachtoownersroot)
- [bAutoActivate](ue_ue.NavModifierComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.NavModifierComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.NavModifierComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.NavModifierComponent.md#beditablewheninherited)
- [bIncludeAgentHeight](ue_ue.NavModifierComponent.md#bincludeagentheight)
- [bInstanceComponent](ue_ue.NavModifierComponent.md#binstancecomponent)
- [bIsActive](ue_ue.NavModifierComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.NavModifierComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.NavModifierComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.NavModifierComponent.md#bnetaddressable)
- [bReplicates](ue_ue.NavModifierComponent.md#breplicates)

### Methods

- [Activate](ue_ue.NavModifierComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.NavModifierComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.NavModifierComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.NavModifierComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.NavModifierComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.NavModifierComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.NavModifierComponent.md#executeubergraph)
- [GetClass](ue_ue.NavModifierComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.NavModifierComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.NavModifierComponent.md#getname)
- [GetOuter](ue_ue.NavModifierComponent.md#getouter)
- [GetOwner](ue_ue.NavModifierComponent.md#getowner)
- [GetWorld](ue_ue.NavModifierComponent.md#getworld)
- [IsActive](ue_ue.NavModifierComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.NavModifierComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.NavModifierComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.NavModifierComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.NavModifierComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.NavModifierComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.NavModifierComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.NavModifierComponent.md#receivetick)
- [RegisterComponent](ue_ue.NavModifierComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.NavModifierComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.NavModifierComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.NavModifierComponent.md#setactive)
- [SetAreaClass](ue_ue.NavModifierComponent.md#setareaclass)
- [SetAutoActivate](ue_ue.NavModifierComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.NavModifierComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.NavModifierComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.NavModifierComponent.md#setisreplicated)
- [SetNavigationRelevancy](ue_ue.NavModifierComponent.md#setnavigationrelevancy)
- [SetTickGroup](ue_ue.NavModifierComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.NavModifierComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.NavModifierComponent.md#toggleactive)
- [Find](ue_ue.NavModifierComponent.md#find)
- [Load](ue_ue.NavModifierComponent.md#load)
- [StaticClass](ue_ue.NavModifierComponent.md#staticclass)

## Constructors

### constructor

• **new NavModifierComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[constructor](ue_ue.NavRelevantComponent.md#constructor)

## Properties

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[AssetUserData](ue_ue.NavRelevantComponent.md#assetuserdata)

___

### CachedNavParent

• **CachedNavParent**: [`Object`](ue_ue.Object.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[CachedNavParent](ue_ue.NavRelevantComponent.md#cachednavparent)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ComponentTags](ue_ue.NavRelevantComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[CreationMethod](ue_ue.NavRelevantComponent.md#creationmethod)

___

### FailsafeExtent

• **FailsafeExtent**: [`Vector`](ue_ue_s.Vector.md)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[OnComponentActivated](ue_ue.NavRelevantComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[OnComponentDeactivated](ue_ue.NavRelevantComponent.md#oncomponentdeactivated)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[PrimaryComponentTick](ue_ue.NavRelevantComponent.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[UCSModifiedProperties](ue_ue.NavRelevantComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[__tid_ActorComponent__](ue_ue.NavRelevantComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_NavModifierComponent\_\_

• **\_\_tid\_NavModifierComponent\_\_**: `boolean`

___

### \_\_tid\_NavRelevantComponent\_\_

• **\_\_tid\_NavRelevantComponent\_\_**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[__tid_NavRelevantComponent__](ue_ue.NavRelevantComponent.md#__tid_navrelevantcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[__tid_Object__](ue_ue.NavRelevantComponent.md#__tid_object__)

___

### bAttachToOwnersRoot

• **bAttachToOwnersRoot**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bAttachToOwnersRoot](ue_ue.NavRelevantComponent.md#battachtoownersroot)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bAutoActivate](ue_ue.NavRelevantComponent.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bCanEverAffectNavigation](ue_ue.NavRelevantComponent.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bCreatedByConstructionScript](ue_ue.NavRelevantComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bEditableWhenInherited](ue_ue.NavRelevantComponent.md#beditablewheninherited)

___

### bIncludeAgentHeight

• **bIncludeAgentHeight**: `boolean`

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bInstanceComponent](ue_ue.NavRelevantComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bIsActive](ue_ue.NavRelevantComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bIsEditorOnly](ue_ue.NavRelevantComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bIsVisualizationComponent](ue_ue.NavRelevantComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bNetAddressable](ue_ue.NavRelevantComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bReplicates](ue_ue.NavRelevantComponent.md#breplicates)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Activate](ue_ue.NavRelevantComponent.md#activate)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[AddTickPrerequisiteActor](ue_ue.NavRelevantComponent.md#addtickprerequisiteactor)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[AddTickPrerequisiteComponent](ue_ue.NavRelevantComponent.md#addtickprerequisitecomponent)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ComponentHasTag](ue_ue.NavRelevantComponent.md#componenthastag)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[CreateDefaultSubobject](ue_ue.NavRelevantComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Deactivate](ue_ue.NavRelevantComponent.md#deactivate)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ExecuteUbergraph](ue_ue.NavRelevantComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetClass](ue_ue.NavRelevantComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetComponentTickInterval](ue_ue.NavRelevantComponent.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetName](ue_ue.NavRelevantComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetOuter](ue_ue.NavRelevantComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetOwner](ue_ue.NavRelevantComponent.md#getowner)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetWorld](ue_ue.NavRelevantComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[IsActive](ue_ue.NavRelevantComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[IsBeingDestroyed](ue_ue.NavRelevantComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[IsComponentTickEnabled](ue_ue.NavRelevantComponent.md#iscomponenttickenabled)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[K2_DestroyComponent](ue_ue.NavRelevantComponent.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[OnRep_IsActive](ue_ue.NavRelevantComponent.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ReceiveBeginPlay](ue_ue.NavRelevantComponent.md#receivebeginplay)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ReceiveEndPlay](ue_ue.NavRelevantComponent.md#receiveendplay)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ReceiveTick](ue_ue.NavRelevantComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[RegisterComponent](ue_ue.NavRelevantComponent.md#registercomponent)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[RemoveTickPrerequisiteActor](ue_ue.NavRelevantComponent.md#removetickprerequisiteactor)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.NavRelevantComponent.md#removetickprerequisitecomponent)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetActive](ue_ue.NavRelevantComponent.md#setactive)

___

### SetAreaClass

▸ **SetAreaClass**(`NewAreaClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAreaClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetAutoActivate](ue_ue.NavRelevantComponent.md#setautoactivate)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetComponentTickEnabled](ue_ue.NavRelevantComponent.md#setcomponenttickenabled)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetComponentTickInterval](ue_ue.NavRelevantComponent.md#setcomponenttickinterval)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetIsReplicated](ue_ue.NavRelevantComponent.md#setisreplicated)

___

### SetNavigationRelevancy

▸ **SetNavigationRelevancy**(`bRelevant`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bRelevant` | `boolean` |

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetNavigationRelevancy](ue_ue.NavRelevantComponent.md#setnavigationrelevancy)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetTickGroup](ue_ue.NavRelevantComponent.md#settickgroup)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetTickableWhenPaused](ue_ue.NavRelevantComponent.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ToggleActive](ue_ue.NavRelevantComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Find](ue_ue.NavRelevantComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Load](ue_ue.NavRelevantComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[StaticClass](ue_ue.NavRelevantComponent.md#staticclass)
