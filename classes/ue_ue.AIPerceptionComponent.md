[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIPerceptionComponent

# Class: AIPerceptionComponent

[ue/ue](../modules/ue_ue.md).AIPerceptionComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`AIPerceptionComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.AIPerceptionComponent.md#constructor)

### Properties

- [AIOwner](ue_ue.AIPerceptionComponent.md#aiowner)
- [AssetUserData](ue_ue.AIPerceptionComponent.md#assetuserdata)
- [ComponentTags](ue_ue.AIPerceptionComponent.md#componenttags)
- [CreationMethod](ue_ue.AIPerceptionComponent.md#creationmethod)
- [DominantSense](ue_ue.AIPerceptionComponent.md#dominantsense)
- [OnComponentActivated](ue_ue.AIPerceptionComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.AIPerceptionComponent.md#oncomponentdeactivated)
- [OnPerceptionUpdated](ue_ue.AIPerceptionComponent.md#onperceptionupdated)
- [OnTargetPerceptionUpdated](ue_ue.AIPerceptionComponent.md#ontargetperceptionupdated)
- [PrimaryComponentTick](ue_ue.AIPerceptionComponent.md#primarycomponenttick)
- [SensesConfig](ue_ue.AIPerceptionComponent.md#sensesconfig)
- [UCSModifiedProperties](ue_ue.AIPerceptionComponent.md#ucsmodifiedproperties)
- [\_\_tid\_AIPerceptionComponent\_\_](ue_ue.AIPerceptionComponent.md#__tid_aiperceptioncomponent__)
- [\_\_tid\_ActorComponent\_\_](ue_ue.AIPerceptionComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.AIPerceptionComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.AIPerceptionComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.AIPerceptionComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.AIPerceptionComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.AIPerceptionComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.AIPerceptionComponent.md#binstancecomponent)
- [bIsActive](ue_ue.AIPerceptionComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.AIPerceptionComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.AIPerceptionComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.AIPerceptionComponent.md#bnetaddressable)
- [bReplicates](ue_ue.AIPerceptionComponent.md#breplicates)

### Methods

- [Activate](ue_ue.AIPerceptionComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.AIPerceptionComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.AIPerceptionComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.AIPerceptionComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.AIPerceptionComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.AIPerceptionComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.AIPerceptionComponent.md#executeubergraph)
- [GetActorsPerception](ue_ue.AIPerceptionComponent.md#getactorsperception)
- [GetClass](ue_ue.AIPerceptionComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.AIPerceptionComponent.md#getcomponenttickinterval)
- [GetCurrentlyPerceivedActors](ue_ue.AIPerceptionComponent.md#getcurrentlyperceivedactors)
- [GetKnownPerceivedActors](ue_ue.AIPerceptionComponent.md#getknownperceivedactors)
- [GetName](ue_ue.AIPerceptionComponent.md#getname)
- [GetOuter](ue_ue.AIPerceptionComponent.md#getouter)
- [GetOwner](ue_ue.AIPerceptionComponent.md#getowner)
- [GetPerceivedActors](ue_ue.AIPerceptionComponent.md#getperceivedactors)
- [GetPerceivedHostileActors](ue_ue.AIPerceptionComponent.md#getperceivedhostileactors)
- [GetWorld](ue_ue.AIPerceptionComponent.md#getworld)
- [IsActive](ue_ue.AIPerceptionComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.AIPerceptionComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.AIPerceptionComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.AIPerceptionComponent.md#k2_destroycomponent)
- [OnOwnerEndPlay](ue_ue.AIPerceptionComponent.md#onownerendplay)
- [OnRep\_IsActive](ue_ue.AIPerceptionComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.AIPerceptionComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.AIPerceptionComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.AIPerceptionComponent.md#receivetick)
- [RegisterComponent](ue_ue.AIPerceptionComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.AIPerceptionComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.AIPerceptionComponent.md#removetickprerequisitecomponent)
- [RequestStimuliListenerUpdate](ue_ue.AIPerceptionComponent.md#requeststimulilistenerupdate)
- [SetActive](ue_ue.AIPerceptionComponent.md#setactive)
- [SetAutoActivate](ue_ue.AIPerceptionComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.AIPerceptionComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.AIPerceptionComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.AIPerceptionComponent.md#setisreplicated)
- [SetSenseEnabled](ue_ue.AIPerceptionComponent.md#setsenseenabled)
- [SetTickGroup](ue_ue.AIPerceptionComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.AIPerceptionComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.AIPerceptionComponent.md#toggleactive)
- [Find](ue_ue.AIPerceptionComponent.md#find)
- [Load](ue_ue.AIPerceptionComponent.md#load)
- [StaticClass](ue_ue.AIPerceptionComponent.md#staticclass)

## Constructors

### constructor

• **new AIPerceptionComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

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

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[CreationMethod](ue_ue.ActorComponent.md#creationmethod)

___

### DominantSense

• **DominantSense**: [`Class`](ue_ue.Class.md)

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

### OnPerceptionUpdated

• **OnPerceptionUpdated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`UpdatedActors`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### OnTargetPerceptionUpdated

• **OnTargetPerceptionUpdated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Stimulus`: [`AIStimulus`](ue_ue.AIStimulus.md)) => `void`\>

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

___

### SensesConfig

• **SensesConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AISenseConfig`](ue_ue.AISenseConfig.md)\>

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_AIPerceptionComponent\_\_

• **\_\_tid\_AIPerceptionComponent\_\_**: `boolean`

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

### GetActorsPerception

▸ **GetActorsPerception**(`Actor`, `Info`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `Info` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ActorPerceptionBlueprintInfo`](ue_ue.ActorPerceptionBlueprintInfo.md)\> |

#### Returns

`boolean`

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

### GetCurrentlyPerceivedActors

▸ **GetCurrentlyPerceivedActors**(`SenseToUse`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SenseToUse` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

___

### GetKnownPerceivedActors

▸ **GetKnownPerceivedActors**(`SenseToUse`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SenseToUse` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

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

### GetPerceivedActors

▸ **GetPerceivedActors**(`SenseToUse`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SenseToUse` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

___

### GetPerceivedHostileActors

▸ **GetPerceivedHostileActors**(`OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

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

### OnOwnerEndPlay

▸ **OnOwnerEndPlay**(`Actor`, `EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

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

### RequestStimuliListenerUpdate

▸ **RequestStimuliListenerUpdate**(): `void`

#### Returns

`void`

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

### SetSenseEnabled

▸ **SetSenseEnabled**(`SenseClass`, `bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SenseClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `bEnable` | `boolean` |

#### Returns

`void`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
