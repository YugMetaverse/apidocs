[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RadialIntMask

# Class: RadialIntMask

[ue/ue](../modules/ue_ue.md).RadialIntMask

## Hierarchy

- [`FieldNodeInt`](ue_ue.FieldNodeInt.md)

  ↳ **`RadialIntMask`**

## Table of contents

### Constructors

- [constructor](ue_ue.RadialIntMask.md#constructor)

### Properties

- [AssetUserData](ue_ue.RadialIntMask.md#assetuserdata)
- [ComponentTags](ue_ue.RadialIntMask.md#componenttags)
- [CreationMethod](ue_ue.RadialIntMask.md#creationmethod)
- [ExteriorValue](ue_ue.RadialIntMask.md#exteriorvalue)
- [InteriorValue](ue_ue.RadialIntMask.md#interiorvalue)
- [OnComponentActivated](ue_ue.RadialIntMask.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.RadialIntMask.md#oncomponentdeactivated)
- [Position](ue_ue.RadialIntMask.md#position)
- [PrimaryComponentTick](ue_ue.RadialIntMask.md#primarycomponenttick)
- [Radius](ue_ue.RadialIntMask.md#radius)
- [SetMaskCondition](ue_ue.RadialIntMask.md#setmaskcondition)
- [UCSModifiedProperties](ue_ue.RadialIntMask.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.RadialIntMask.md#__tid_actorcomponent__)
- [\_\_tid\_FieldNodeBase\_\_](ue_ue.RadialIntMask.md#__tid_fieldnodebase__)
- [\_\_tid\_FieldNodeInt\_\_](ue_ue.RadialIntMask.md#__tid_fieldnodeint__)
- [\_\_tid\_Object\_\_](ue_ue.RadialIntMask.md#__tid_object__)
- [\_\_tid\_RadialIntMask\_\_](ue_ue.RadialIntMask.md#__tid_radialintmask__)
- [bAutoActivate](ue_ue.RadialIntMask.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.RadialIntMask.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.RadialIntMask.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.RadialIntMask.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.RadialIntMask.md#binstancecomponent)
- [bIsActive](ue_ue.RadialIntMask.md#bisactive)
- [bIsEditorOnly](ue_ue.RadialIntMask.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.RadialIntMask.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.RadialIntMask.md#bnetaddressable)
- [bReplicates](ue_ue.RadialIntMask.md#breplicates)

### Methods

- [Activate](ue_ue.RadialIntMask.md#activate)
- [AddTickPrerequisiteActor](ue_ue.RadialIntMask.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.RadialIntMask.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.RadialIntMask.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.RadialIntMask.md#createdefaultsubobject)
- [Deactivate](ue_ue.RadialIntMask.md#deactivate)
- [ExecuteUbergraph](ue_ue.RadialIntMask.md#executeubergraph)
- [GetClass](ue_ue.RadialIntMask.md#getclass)
- [GetComponentTickInterval](ue_ue.RadialIntMask.md#getcomponenttickinterval)
- [GetName](ue_ue.RadialIntMask.md#getname)
- [GetOuter](ue_ue.RadialIntMask.md#getouter)
- [GetOwner](ue_ue.RadialIntMask.md#getowner)
- [GetWorld](ue_ue.RadialIntMask.md#getworld)
- [IsActive](ue_ue.RadialIntMask.md#isactive)
- [IsBeingDestroyed](ue_ue.RadialIntMask.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.RadialIntMask.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.RadialIntMask.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.RadialIntMask.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.RadialIntMask.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.RadialIntMask.md#receiveendplay)
- [ReceiveTick](ue_ue.RadialIntMask.md#receivetick)
- [RegisterComponent](ue_ue.RadialIntMask.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.RadialIntMask.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.RadialIntMask.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.RadialIntMask.md#setactive)
- [SetAutoActivate](ue_ue.RadialIntMask.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.RadialIntMask.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.RadialIntMask.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.RadialIntMask.md#setisreplicated)
- [SetRadialIntMask](ue_ue.RadialIntMask.md#setradialintmask)
- [SetTickGroup](ue_ue.RadialIntMask.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.RadialIntMask.md#settickablewhenpaused)
- [ToggleActive](ue_ue.RadialIntMask.md#toggleactive)
- [Find](ue_ue.RadialIntMask.md#find)
- [Load](ue_ue.RadialIntMask.md#load)
- [StaticClass](ue_ue.RadialIntMask.md#staticclass)

## Constructors

### constructor

• **new RadialIntMask**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FieldNodeInt](ue_ue.FieldNodeInt.md).[constructor](ue_ue.FieldNodeInt.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[AssetUserData](ue_ue.FieldNodeInt.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ComponentTags](ue_ue.FieldNodeInt.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[CreationMethod](ue_ue.FieldNodeInt.md#creationmethod)

___

### ExteriorValue

• **ExteriorValue**: `number`

___

### InteriorValue

• **InteriorValue**: `number`

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[OnComponentActivated](ue_ue.FieldNodeInt.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[OnComponentDeactivated](ue_ue.FieldNodeInt.md#oncomponentdeactivated)

___

### Position

• **Position**: [`Vector`](ue_ue_s.Vector.md)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[PrimaryComponentTick](ue_ue.FieldNodeInt.md#primarycomponenttick)

___

### Radius

• **Radius**: `number`

___

### SetMaskCondition

• **SetMaskCondition**: [`ESetMaskConditionType`](../enums/ue_ue.ESetMaskConditionType.md)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[UCSModifiedProperties](ue_ue.FieldNodeInt.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_ActorComponent__](ue_ue.FieldNodeInt.md#__tid_actorcomponent__)

___

### \_\_tid\_FieldNodeBase\_\_

• **\_\_tid\_FieldNodeBase\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_FieldNodeBase__](ue_ue.FieldNodeInt.md#__tid_fieldnodebase__)

___

### \_\_tid\_FieldNodeInt\_\_

• **\_\_tid\_FieldNodeInt\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_FieldNodeInt__](ue_ue.FieldNodeInt.md#__tid_fieldnodeint__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_Object__](ue_ue.FieldNodeInt.md#__tid_object__)

___

### \_\_tid\_RadialIntMask\_\_

• **\_\_tid\_RadialIntMask\_\_**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bAutoActivate](ue_ue.FieldNodeInt.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bCanEverAffectNavigation](ue_ue.FieldNodeInt.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bCreatedByConstructionScript](ue_ue.FieldNodeInt.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bEditableWhenInherited](ue_ue.FieldNodeInt.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bInstanceComponent](ue_ue.FieldNodeInt.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bIsActive](ue_ue.FieldNodeInt.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bIsEditorOnly](ue_ue.FieldNodeInt.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bIsVisualizationComponent](ue_ue.FieldNodeInt.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bNetAddressable](ue_ue.FieldNodeInt.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bReplicates](ue_ue.FieldNodeInt.md#breplicates)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[Activate](ue_ue.FieldNodeInt.md#activate)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[AddTickPrerequisiteActor](ue_ue.FieldNodeInt.md#addtickprerequisiteactor)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[AddTickPrerequisiteComponent](ue_ue.FieldNodeInt.md#addtickprerequisitecomponent)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ComponentHasTag](ue_ue.FieldNodeInt.md#componenthastag)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[CreateDefaultSubobject](ue_ue.FieldNodeInt.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[Deactivate](ue_ue.FieldNodeInt.md#deactivate)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ExecuteUbergraph](ue_ue.FieldNodeInt.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetClass](ue_ue.FieldNodeInt.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetComponentTickInterval](ue_ue.FieldNodeInt.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetName](ue_ue.FieldNodeInt.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetOuter](ue_ue.FieldNodeInt.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetOwner](ue_ue.FieldNodeInt.md#getowner)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetWorld](ue_ue.FieldNodeInt.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[IsActive](ue_ue.FieldNodeInt.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[IsBeingDestroyed](ue_ue.FieldNodeInt.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[IsComponentTickEnabled](ue_ue.FieldNodeInt.md#iscomponenttickenabled)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[K2_DestroyComponent](ue_ue.FieldNodeInt.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[OnRep_IsActive](ue_ue.FieldNodeInt.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ReceiveBeginPlay](ue_ue.FieldNodeInt.md#receivebeginplay)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ReceiveEndPlay](ue_ue.FieldNodeInt.md#receiveendplay)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ReceiveTick](ue_ue.FieldNodeInt.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[RegisterComponent](ue_ue.FieldNodeInt.md#registercomponent)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[RemoveTickPrerequisiteActor](ue_ue.FieldNodeInt.md#removetickprerequisiteactor)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[RemoveTickPrerequisiteComponent](ue_ue.FieldNodeInt.md#removetickprerequisitecomponent)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetActive](ue_ue.FieldNodeInt.md#setactive)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetAutoActivate](ue_ue.FieldNodeInt.md#setautoactivate)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetComponentTickEnabled](ue_ue.FieldNodeInt.md#setcomponenttickenabled)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetComponentTickInterval](ue_ue.FieldNodeInt.md#setcomponenttickinterval)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetIsReplicated](ue_ue.FieldNodeInt.md#setisreplicated)

___

### SetRadialIntMask

▸ **SetRadialIntMask**(`Radius`, `Position`, `InteriorValue`, `ExteriorValue`, `SetMaskConditionIn`): [`RadialIntMask`](ue_ue.RadialIntMask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Radius` | `number` |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |
| `InteriorValue` | `number` |
| `ExteriorValue` | `number` |
| `SetMaskConditionIn` | [`ESetMaskConditionType`](../enums/ue_ue.ESetMaskConditionType.md) |

#### Returns

[`RadialIntMask`](ue_ue.RadialIntMask.md)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetTickGroup](ue_ue.FieldNodeInt.md#settickgroup)

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

[FieldNodeInt](ue_ue.FieldNodeInt.md).[SetTickableWhenPaused](ue_ue.FieldNodeInt.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ToggleActive](ue_ue.FieldNodeInt.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RadialIntMask`](ue_ue.RadialIntMask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RadialIntMask`](ue_ue.RadialIntMask.md)

#### Overrides

[FieldNodeInt](ue_ue.FieldNodeInt.md).[Find](ue_ue.FieldNodeInt.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`RadialIntMask`](ue_ue.RadialIntMask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RadialIntMask`](ue_ue.RadialIntMask.md)

#### Overrides

[FieldNodeInt](ue_ue.FieldNodeInt.md).[Load](ue_ue.FieldNodeInt.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FieldNodeInt](ue_ue.FieldNodeInt.md).[StaticClass](ue_ue.FieldNodeInt.md#staticclass)
