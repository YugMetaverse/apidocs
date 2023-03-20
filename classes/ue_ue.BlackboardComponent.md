[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlackboardComponent

# Class: BlackboardComponent

[ue/ue](../modules/ue_ue.md).BlackboardComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`BlackboardComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlackboardComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.BlackboardComponent.md#assetuserdata)
- [BlackboardAsset](ue_ue.BlackboardComponent.md#blackboardasset)
- [BrainComp](ue_ue.BlackboardComponent.md#braincomp)
- [ComponentTags](ue_ue.BlackboardComponent.md#componenttags)
- [CreationMethod](ue_ue.BlackboardComponent.md#creationmethod)
- [KeyInstances](ue_ue.BlackboardComponent.md#keyinstances)
- [OnComponentActivated](ue_ue.BlackboardComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.BlackboardComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.BlackboardComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.BlackboardComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.BlackboardComponent.md#__tid_actorcomponent__)
- [\_\_tid\_BlackboardComponent\_\_](ue_ue.BlackboardComponent.md#__tid_blackboardcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.BlackboardComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.BlackboardComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.BlackboardComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.BlackboardComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.BlackboardComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.BlackboardComponent.md#binstancecomponent)
- [bIsActive](ue_ue.BlackboardComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.BlackboardComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.BlackboardComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.BlackboardComponent.md#bnetaddressable)
- [bReplicates](ue_ue.BlackboardComponent.md#breplicates)

### Methods

- [Activate](ue_ue.BlackboardComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.BlackboardComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.BlackboardComponent.md#addtickprerequisitecomponent)
- [ClearValue](ue_ue.BlackboardComponent.md#clearvalue)
- [ComponentHasTag](ue_ue.BlackboardComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.BlackboardComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.BlackboardComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.BlackboardComponent.md#executeubergraph)
- [GetClass](ue_ue.BlackboardComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.BlackboardComponent.md#getcomponenttickinterval)
- [GetLocationFromEntry](ue_ue.BlackboardComponent.md#getlocationfromentry)
- [GetName](ue_ue.BlackboardComponent.md#getname)
- [GetOuter](ue_ue.BlackboardComponent.md#getouter)
- [GetOwner](ue_ue.BlackboardComponent.md#getowner)
- [GetRotationFromEntry](ue_ue.BlackboardComponent.md#getrotationfromentry)
- [GetValueAsBool](ue_ue.BlackboardComponent.md#getvalueasbool)
- [GetValueAsClass](ue_ue.BlackboardComponent.md#getvalueasclass)
- [GetValueAsEnum](ue_ue.BlackboardComponent.md#getvalueasenum)
- [GetValueAsFloat](ue_ue.BlackboardComponent.md#getvalueasfloat)
- [GetValueAsInt](ue_ue.BlackboardComponent.md#getvalueasint)
- [GetValueAsName](ue_ue.BlackboardComponent.md#getvalueasname)
- [GetValueAsObject](ue_ue.BlackboardComponent.md#getvalueasobject)
- [GetValueAsRotator](ue_ue.BlackboardComponent.md#getvalueasrotator)
- [GetValueAsString](ue_ue.BlackboardComponent.md#getvalueasstring)
- [GetValueAsVector](ue_ue.BlackboardComponent.md#getvalueasvector)
- [GetWorld](ue_ue.BlackboardComponent.md#getworld)
- [IsActive](ue_ue.BlackboardComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.BlackboardComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.BlackboardComponent.md#iscomponenttickenabled)
- [IsVectorValueSet](ue_ue.BlackboardComponent.md#isvectorvalueset)
- [K2\_DestroyComponent](ue_ue.BlackboardComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.BlackboardComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.BlackboardComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.BlackboardComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.BlackboardComponent.md#receivetick)
- [RegisterComponent](ue_ue.BlackboardComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.BlackboardComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.BlackboardComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.BlackboardComponent.md#setactive)
- [SetAutoActivate](ue_ue.BlackboardComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.BlackboardComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.BlackboardComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.BlackboardComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.BlackboardComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.BlackboardComponent.md#settickablewhenpaused)
- [SetValueAsBool](ue_ue.BlackboardComponent.md#setvalueasbool)
- [SetValueAsClass](ue_ue.BlackboardComponent.md#setvalueasclass)
- [SetValueAsEnum](ue_ue.BlackboardComponent.md#setvalueasenum)
- [SetValueAsFloat](ue_ue.BlackboardComponent.md#setvalueasfloat)
- [SetValueAsInt](ue_ue.BlackboardComponent.md#setvalueasint)
- [SetValueAsName](ue_ue.BlackboardComponent.md#setvalueasname)
- [SetValueAsObject](ue_ue.BlackboardComponent.md#setvalueasobject)
- [SetValueAsRotator](ue_ue.BlackboardComponent.md#setvalueasrotator)
- [SetValueAsString](ue_ue.BlackboardComponent.md#setvalueasstring)
- [SetValueAsVector](ue_ue.BlackboardComponent.md#setvalueasvector)
- [ToggleActive](ue_ue.BlackboardComponent.md#toggleactive)
- [Find](ue_ue.BlackboardComponent.md#find)
- [Load](ue_ue.BlackboardComponent.md#load)
- [StaticClass](ue_ue.BlackboardComponent.md#staticclass)

## Constructors

### constructor

• **new BlackboardComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### BlackboardAsset

• **BlackboardAsset**: [`BlackboardData`](ue_ue.BlackboardData.md)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

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

### KeyInstances

• **KeyInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)\>

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

### \_\_tid\_BlackboardComponent\_\_

• **\_\_tid\_BlackboardComponent\_\_**: `boolean`

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

### ClearValue

▸ **ClearValue**(`KeyName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`void`

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

### GetLocationFromEntry

▸ **GetLocationFromEntry**(`KeyName`, `ResultLocation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `ResultLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

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

### GetRotationFromEntry

▸ **GetRotationFromEntry**(`KeyName`, `ResultRotation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `ResultRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`boolean`

___

### GetValueAsBool

▸ **GetValueAsBool**(`KeyName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`boolean`

___

### GetValueAsClass

▸ **GetValueAsClass**(`KeyName`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Class`](ue_ue.Class.md)

___

### GetValueAsEnum

▸ **GetValueAsEnum**(`KeyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`number`

___

### GetValueAsFloat

▸ **GetValueAsFloat**(`KeyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`number`

___

### GetValueAsInt

▸ **GetValueAsInt**(`KeyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`number`

___

### GetValueAsName

▸ **GetValueAsName**(`KeyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`string`

___

### GetValueAsObject

▸ **GetValueAsObject**(`KeyName`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Object`](ue_ue.Object.md)

___

### GetValueAsRotator

▸ **GetValueAsRotator**(`KeyName`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetValueAsString

▸ **GetValueAsString**(`KeyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`string`

___

### GetValueAsVector

▸ **GetValueAsVector**(`KeyName`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### IsVectorValueSet

▸ **IsVectorValueSet**(`KeyName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`boolean`

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

### SetValueAsBool

▸ **SetValueAsBool**(`KeyName`, `BoolValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `BoolValue` | `boolean` |

#### Returns

`void`

___

### SetValueAsClass

▸ **SetValueAsClass**(`KeyName`, `ClassValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `ClassValue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### SetValueAsEnum

▸ **SetValueAsEnum**(`KeyName`, `EnumValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `EnumValue` | `number` |

#### Returns

`void`

___

### SetValueAsFloat

▸ **SetValueAsFloat**(`KeyName`, `FloatValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `FloatValue` | `number` |

#### Returns

`void`

___

### SetValueAsInt

▸ **SetValueAsInt**(`KeyName`, `IntValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `IntValue` | `number` |

#### Returns

`void`

___

### SetValueAsName

▸ **SetValueAsName**(`KeyName`, `NameValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `NameValue` | `string` |

#### Returns

`void`

___

### SetValueAsObject

▸ **SetValueAsObject**(`KeyName`, `ObjectValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `ObjectValue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### SetValueAsRotator

▸ **SetValueAsRotator**(`KeyName`, `VectorValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `VectorValue` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### SetValueAsString

▸ **SetValueAsString**(`KeyName`, `StringValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `StringValue` | `string` |

#### Returns

`void`

___

### SetValueAsVector

▸ **SetValueAsVector**(`KeyName`, `VectorValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `VectorValue` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
