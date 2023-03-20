[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnSensingComponent

# Class: PawnSensingComponent

[ue/ue](../modules/ue_ue.md).PawnSensingComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`PawnSensingComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PawnSensingComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.PawnSensingComponent.md#assetuserdata)
- [ComponentTags](ue_ue.PawnSensingComponent.md#componenttags)
- [CreationMethod](ue_ue.PawnSensingComponent.md#creationmethod)
- [HearingMaxSoundAge](ue_ue.PawnSensingComponent.md#hearingmaxsoundage)
- [HearingThreshold](ue_ue.PawnSensingComponent.md#hearingthreshold)
- [LOSHearingThreshold](ue_ue.PawnSensingComponent.md#loshearingthreshold)
- [OnComponentActivated](ue_ue.PawnSensingComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PawnSensingComponent.md#oncomponentdeactivated)
- [OnHearNoise](ue_ue.PawnSensingComponent.md#onhearnoise)
- [OnSeePawn](ue_ue.PawnSensingComponent.md#onseepawn)
- [PeripheralVisionAngle](ue_ue.PawnSensingComponent.md#peripheralvisionangle)
- [PeripheralVisionCosine](ue_ue.PawnSensingComponent.md#peripheralvisioncosine)
- [PrimaryComponentTick](ue_ue.PawnSensingComponent.md#primarycomponenttick)
- [SensingInterval](ue_ue.PawnSensingComponent.md#sensinginterval)
- [SightRadius](ue_ue.PawnSensingComponent.md#sightradius)
- [UCSModifiedProperties](ue_ue.PawnSensingComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PawnSensingComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PawnSensingComponent.md#__tid_object__)
- [\_\_tid\_PawnSensingComponent\_\_](ue_ue.PawnSensingComponent.md#__tid_pawnsensingcomponent__)
- [bAutoActivate](ue_ue.PawnSensingComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.PawnSensingComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.PawnSensingComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PawnSensingComponent.md#beditablewheninherited)
- [bEnableSensingUpdates](ue_ue.PawnSensingComponent.md#benablesensingupdates)
- [bHearNoises](ue_ue.PawnSensingComponent.md#bhearnoises)
- [bInstanceComponent](ue_ue.PawnSensingComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PawnSensingComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PawnSensingComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PawnSensingComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PawnSensingComponent.md#bnetaddressable)
- [bOnlySensePlayers](ue_ue.PawnSensingComponent.md#bonlysenseplayers)
- [bReplicates](ue_ue.PawnSensingComponent.md#breplicates)
- [bSeePawns](ue_ue.PawnSensingComponent.md#bseepawns)

### Methods

- [Activate](ue_ue.PawnSensingComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PawnSensingComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PawnSensingComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PawnSensingComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PawnSensingComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PawnSensingComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.PawnSensingComponent.md#executeubergraph)
- [GetClass](ue_ue.PawnSensingComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PawnSensingComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.PawnSensingComponent.md#getname)
- [GetOuter](ue_ue.PawnSensingComponent.md#getouter)
- [GetOwner](ue_ue.PawnSensingComponent.md#getowner)
- [GetPeripheralVisionAngle](ue_ue.PawnSensingComponent.md#getperipheralvisionangle)
- [GetPeripheralVisionCosine](ue_ue.PawnSensingComponent.md#getperipheralvisioncosine)
- [GetWorld](ue_ue.PawnSensingComponent.md#getworld)
- [HearNoiseDelegate\_\_DelegateSignature](ue_ue.PawnSensingComponent.md#hearnoisedelegate__delegatesignature)
- [IsActive](ue_ue.PawnSensingComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.PawnSensingComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PawnSensingComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.PawnSensingComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.PawnSensingComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.PawnSensingComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PawnSensingComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PawnSensingComponent.md#receivetick)
- [RegisterComponent](ue_ue.PawnSensingComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PawnSensingComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PawnSensingComponent.md#removetickprerequisitecomponent)
- [SeePawnDelegate\_\_DelegateSignature](ue_ue.PawnSensingComponent.md#seepawndelegate__delegatesignature)
- [SetActive](ue_ue.PawnSensingComponent.md#setactive)
- [SetAutoActivate](ue_ue.PawnSensingComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PawnSensingComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PawnSensingComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.PawnSensingComponent.md#setisreplicated)
- [SetPeripheralVisionAngle](ue_ue.PawnSensingComponent.md#setperipheralvisionangle)
- [SetSensingInterval](ue_ue.PawnSensingComponent.md#setsensinginterval)
- [SetSensingUpdatesEnabled](ue_ue.PawnSensingComponent.md#setsensingupdatesenabled)
- [SetTickGroup](ue_ue.PawnSensingComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PawnSensingComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.PawnSensingComponent.md#toggleactive)
- [Find](ue_ue.PawnSensingComponent.md#find)
- [Load](ue_ue.PawnSensingComponent.md#load)
- [StaticClass](ue_ue.PawnSensingComponent.md#staticclass)

## Constructors

### constructor

• **new PawnSensingComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### HearingMaxSoundAge

• **HearingMaxSoundAge**: `number`

___

### HearingThreshold

• **HearingThreshold**: `number`

___

### LOSHearingThreshold

• **LOSHearingThreshold**: `number`

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

### OnHearNoise

• **OnHearNoise**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Instigator`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\>, `Location`: [`Vector`](ue_ue_s.Vector.md), `Volume`: `number`) => `void`\>

___

### OnSeePawn

• **OnSeePawn**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Pawn`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\>) => `void`\>

___

### PeripheralVisionAngle

• **PeripheralVisionAngle**: `number`

___

### PeripheralVisionCosine

• **PeripheralVisionCosine**: `number`

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

___

### SensingInterval

• **SensingInterval**: `number`

___

### SightRadius

• **SightRadius**: `number`

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

### \_\_tid\_PawnSensingComponent\_\_

• **\_\_tid\_PawnSensingComponent\_\_**: `boolean`

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

### bEnableSensingUpdates

• **bEnableSensingUpdates**: `boolean`

___

### bHearNoises

• **bHearNoises**: `boolean`

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

### bOnlySensePlayers

• **bOnlySensePlayers**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

___

### bSeePawns

• **bSeePawns**: `boolean`

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

### GetPeripheralVisionAngle

▸ **GetPeripheralVisionAngle**(): `number`

#### Returns

`number`

___

### GetPeripheralVisionCosine

▸ **GetPeripheralVisionCosine**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetWorld](ue_ue.ActorComponent.md#getworld)

___

### HearNoiseDelegate\_\_DelegateSignature

▸ **HearNoiseDelegate__DelegateSignature**(`Instigator`, `Location`, `Volume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instigator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Volume` | `number` |

#### Returns

`void`

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

### SeePawnDelegate\_\_DelegateSignature

▸ **SeePawnDelegate__DelegateSignature**(`Pawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

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

### SetPeripheralVisionAngle

▸ **SetPeripheralVisionAngle**(`NewPeripheralVisionAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPeripheralVisionAngle` | `number` |

#### Returns

`void`

___

### SetSensingInterval

▸ **SetSensingInterval**(`NewSensingInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSensingInterval` | `number` |

#### Returns

`void`

___

### SetSensingUpdatesEnabled

▸ **SetSensingUpdatesEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnSensingComponent`](ue_ue.PawnSensingComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnSensingComponent`](ue_ue.PawnSensingComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnSensingComponent`](ue_ue.PawnSensingComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnSensingComponent`](ue_ue.PawnSensingComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
