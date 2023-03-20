[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RadialFalloff

# Class: RadialFalloff

[ue/ue](../modules/ue_ue.md).RadialFalloff

## Hierarchy

- [`FieldNodeFloat`](ue_ue.FieldNodeFloat.md)

  ↳ **`RadialFalloff`**

## Table of contents

### Constructors

- [constructor](ue_ue.RadialFalloff.md#constructor)

### Properties

- [AssetUserData](ue_ue.RadialFalloff.md#assetuserdata)
- [ComponentTags](ue_ue.RadialFalloff.md#componenttags)
- [CreationMethod](ue_ue.RadialFalloff.md#creationmethod)
- [Default](ue_ue.RadialFalloff.md#default)
- [Falloff](ue_ue.RadialFalloff.md#falloff)
- [Magnitude](ue_ue.RadialFalloff.md#magnitude)
- [MaxRange](ue_ue.RadialFalloff.md#maxrange)
- [MinRange](ue_ue.RadialFalloff.md#minrange)
- [OnComponentActivated](ue_ue.RadialFalloff.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.RadialFalloff.md#oncomponentdeactivated)
- [Position](ue_ue.RadialFalloff.md#position)
- [PrimaryComponentTick](ue_ue.RadialFalloff.md#primarycomponenttick)
- [Radius](ue_ue.RadialFalloff.md#radius)
- [UCSModifiedProperties](ue_ue.RadialFalloff.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.RadialFalloff.md#__tid_actorcomponent__)
- [\_\_tid\_FieldNodeBase\_\_](ue_ue.RadialFalloff.md#__tid_fieldnodebase__)
- [\_\_tid\_FieldNodeFloat\_\_](ue_ue.RadialFalloff.md#__tid_fieldnodefloat__)
- [\_\_tid\_Object\_\_](ue_ue.RadialFalloff.md#__tid_object__)
- [\_\_tid\_RadialFalloff\_\_](ue_ue.RadialFalloff.md#__tid_radialfalloff__)
- [bAutoActivate](ue_ue.RadialFalloff.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.RadialFalloff.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.RadialFalloff.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.RadialFalloff.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.RadialFalloff.md#binstancecomponent)
- [bIsActive](ue_ue.RadialFalloff.md#bisactive)
- [bIsEditorOnly](ue_ue.RadialFalloff.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.RadialFalloff.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.RadialFalloff.md#bnetaddressable)
- [bReplicates](ue_ue.RadialFalloff.md#breplicates)

### Methods

- [Activate](ue_ue.RadialFalloff.md#activate)
- [AddTickPrerequisiteActor](ue_ue.RadialFalloff.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.RadialFalloff.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.RadialFalloff.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.RadialFalloff.md#createdefaultsubobject)
- [Deactivate](ue_ue.RadialFalloff.md#deactivate)
- [ExecuteUbergraph](ue_ue.RadialFalloff.md#executeubergraph)
- [GetClass](ue_ue.RadialFalloff.md#getclass)
- [GetComponentTickInterval](ue_ue.RadialFalloff.md#getcomponenttickinterval)
- [GetName](ue_ue.RadialFalloff.md#getname)
- [GetOuter](ue_ue.RadialFalloff.md#getouter)
- [GetOwner](ue_ue.RadialFalloff.md#getowner)
- [GetWorld](ue_ue.RadialFalloff.md#getworld)
- [IsActive](ue_ue.RadialFalloff.md#isactive)
- [IsBeingDestroyed](ue_ue.RadialFalloff.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.RadialFalloff.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.RadialFalloff.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.RadialFalloff.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.RadialFalloff.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.RadialFalloff.md#receiveendplay)
- [ReceiveTick](ue_ue.RadialFalloff.md#receivetick)
- [RegisterComponent](ue_ue.RadialFalloff.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.RadialFalloff.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.RadialFalloff.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.RadialFalloff.md#setactive)
- [SetAutoActivate](ue_ue.RadialFalloff.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.RadialFalloff.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.RadialFalloff.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.RadialFalloff.md#setisreplicated)
- [SetRadialFalloff](ue_ue.RadialFalloff.md#setradialfalloff)
- [SetTickGroup](ue_ue.RadialFalloff.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.RadialFalloff.md#settickablewhenpaused)
- [ToggleActive](ue_ue.RadialFalloff.md#toggleactive)
- [Find](ue_ue.RadialFalloff.md#find)
- [Load](ue_ue.RadialFalloff.md#load)
- [StaticClass](ue_ue.RadialFalloff.md#staticclass)

## Constructors

### constructor

• **new RadialFalloff**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[constructor](ue_ue.FieldNodeFloat.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[AssetUserData](ue_ue.FieldNodeFloat.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ComponentTags](ue_ue.FieldNodeFloat.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[CreationMethod](ue_ue.FieldNodeFloat.md#creationmethod)

___

### Default

• **Default**: `number`

___

### Falloff

• **Falloff**: [`EFieldFalloffType`](../enums/ue_ue.EFieldFalloffType.md)

___

### Magnitude

• **Magnitude**: `number`

___

### MaxRange

• **MaxRange**: `number`

___

### MinRange

• **MinRange**: `number`

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[OnComponentActivated](ue_ue.FieldNodeFloat.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[OnComponentDeactivated](ue_ue.FieldNodeFloat.md#oncomponentdeactivated)

___

### Position

• **Position**: [`Vector`](ue_ue_s.Vector.md)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[PrimaryComponentTick](ue_ue.FieldNodeFloat.md#primarycomponenttick)

___

### Radius

• **Radius**: `number`

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[UCSModifiedProperties](ue_ue.FieldNodeFloat.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_ActorComponent__](ue_ue.FieldNodeFloat.md#__tid_actorcomponent__)

___

### \_\_tid\_FieldNodeBase\_\_

• **\_\_tid\_FieldNodeBase\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_FieldNodeBase__](ue_ue.FieldNodeFloat.md#__tid_fieldnodebase__)

___

### \_\_tid\_FieldNodeFloat\_\_

• **\_\_tid\_FieldNodeFloat\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_FieldNodeFloat__](ue_ue.FieldNodeFloat.md#__tid_fieldnodefloat__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_Object__](ue_ue.FieldNodeFloat.md#__tid_object__)

___

### \_\_tid\_RadialFalloff\_\_

• **\_\_tid\_RadialFalloff\_\_**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bAutoActivate](ue_ue.FieldNodeFloat.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bCanEverAffectNavigation](ue_ue.FieldNodeFloat.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bCreatedByConstructionScript](ue_ue.FieldNodeFloat.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bEditableWhenInherited](ue_ue.FieldNodeFloat.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bInstanceComponent](ue_ue.FieldNodeFloat.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bIsActive](ue_ue.FieldNodeFloat.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bIsEditorOnly](ue_ue.FieldNodeFloat.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bIsVisualizationComponent](ue_ue.FieldNodeFloat.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bNetAddressable](ue_ue.FieldNodeFloat.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bReplicates](ue_ue.FieldNodeFloat.md#breplicates)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Activate](ue_ue.FieldNodeFloat.md#activate)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[AddTickPrerequisiteActor](ue_ue.FieldNodeFloat.md#addtickprerequisiteactor)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[AddTickPrerequisiteComponent](ue_ue.FieldNodeFloat.md#addtickprerequisitecomponent)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ComponentHasTag](ue_ue.FieldNodeFloat.md#componenthastag)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[CreateDefaultSubobject](ue_ue.FieldNodeFloat.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Deactivate](ue_ue.FieldNodeFloat.md#deactivate)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ExecuteUbergraph](ue_ue.FieldNodeFloat.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetClass](ue_ue.FieldNodeFloat.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetComponentTickInterval](ue_ue.FieldNodeFloat.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetName](ue_ue.FieldNodeFloat.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetOuter](ue_ue.FieldNodeFloat.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetOwner](ue_ue.FieldNodeFloat.md#getowner)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetWorld](ue_ue.FieldNodeFloat.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[IsActive](ue_ue.FieldNodeFloat.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[IsBeingDestroyed](ue_ue.FieldNodeFloat.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[IsComponentTickEnabled](ue_ue.FieldNodeFloat.md#iscomponenttickenabled)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[K2_DestroyComponent](ue_ue.FieldNodeFloat.md#k2_destroycomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[OnRep_IsActive](ue_ue.FieldNodeFloat.md#onrep_isactive)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ReceiveBeginPlay](ue_ue.FieldNodeFloat.md#receivebeginplay)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ReceiveEndPlay](ue_ue.FieldNodeFloat.md#receiveendplay)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ReceiveTick](ue_ue.FieldNodeFloat.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[RegisterComponent](ue_ue.FieldNodeFloat.md#registercomponent)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[RemoveTickPrerequisiteActor](ue_ue.FieldNodeFloat.md#removetickprerequisiteactor)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[RemoveTickPrerequisiteComponent](ue_ue.FieldNodeFloat.md#removetickprerequisitecomponent)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetActive](ue_ue.FieldNodeFloat.md#setactive)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetAutoActivate](ue_ue.FieldNodeFloat.md#setautoactivate)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetComponentTickEnabled](ue_ue.FieldNodeFloat.md#setcomponenttickenabled)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetComponentTickInterval](ue_ue.FieldNodeFloat.md#setcomponenttickinterval)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetIsReplicated](ue_ue.FieldNodeFloat.md#setisreplicated)

___

### SetRadialFalloff

▸ **SetRadialFalloff**(`Magnitude`, `MinRange`, `MaxRange`, `Default`, `Radius`, `Position`, `Falloff`): [`RadialFalloff`](ue_ue.RadialFalloff.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Magnitude` | `number` |
| `MinRange` | `number` |
| `MaxRange` | `number` |
| `Default` | `number` |
| `Radius` | `number` |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |
| `Falloff` | [`EFieldFalloffType`](../enums/ue_ue.EFieldFalloffType.md) |

#### Returns

[`RadialFalloff`](ue_ue.RadialFalloff.md)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetTickGroup](ue_ue.FieldNodeFloat.md#settickgroup)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetTickableWhenPaused](ue_ue.FieldNodeFloat.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ToggleActive](ue_ue.FieldNodeFloat.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RadialFalloff`](ue_ue.RadialFalloff.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RadialFalloff`](ue_ue.RadialFalloff.md)

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Find](ue_ue.FieldNodeFloat.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`RadialFalloff`](ue_ue.RadialFalloff.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RadialFalloff`](ue_ue.RadialFalloff.md)

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Load](ue_ue.FieldNodeFloat.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[StaticClass](ue_ue.FieldNodeFloat.md#staticclass)
