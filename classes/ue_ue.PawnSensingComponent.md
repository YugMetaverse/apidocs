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

#### Defined in

[ue/ue.d.ts:57015](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57015)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AssetUserData](ue_ue.ActorComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ComponentTags](ue_ue.ActorComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[CreationMethod](ue_ue.ActorComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### HearingMaxSoundAge

• **HearingMaxSoundAge**: `number`

#### Defined in

[ue/ue.d.ts:57020](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57020)

___

### HearingThreshold

• **HearingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:57016](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57016)

___

### LOSHearingThreshold

• **LOSHearingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:57017](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57017)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentActivated](ue_ue.ActorComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentDeactivated](ue_ue.ActorComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OnHearNoise

• **OnHearNoise**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Instigator`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\>, `Location`: [`Vector`](ue_ue_s.Vector.md), `Volume`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:57026](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57026)

___

### OnSeePawn

• **OnSeePawn**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Pawn`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:57025](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57025)

___

### PeripheralVisionAngle

• **PeripheralVisionAngle**: `number`

#### Defined in

[ue/ue.d.ts:57027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57027)

___

### PeripheralVisionCosine

• **PeripheralVisionCosine**: `number`

#### Defined in

[ue/ue.d.ts:57028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57028)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### SensingInterval

• **SensingInterval**: `number`

#### Defined in

[ue/ue.d.ts:57019](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57019)

___

### SightRadius

• **SightRadius**: `number`

#### Defined in

[ue/ue.d.ts:57018](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57018)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_ActorComponent__](ue_ue.ActorComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_Object__](ue_ue.ActorComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnSensingComponent\_\_

• **\_\_tid\_PawnSensingComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57040)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bAutoActivate](ue_ue.ActorComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCanEverAffectNavigation](ue_ue.ActorComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCreatedByConstructionScript](ue_ue.ActorComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bEditableWhenInherited](ue_ue.ActorComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bEnableSensingUpdates

• **bEnableSensingUpdates**: `boolean`

#### Defined in

[ue/ue.d.ts:57021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57021)

___

### bHearNoises

• **bHearNoises**: `boolean`

#### Defined in

[ue/ue.d.ts:57024](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57024)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bInstanceComponent](ue_ue.ActorComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsActive](ue_ue.ActorComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsEditorOnly](ue_ue.ActorComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsVisualizationComponent](ue_ue.ActorComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bNetAddressable](ue_ue.ActorComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bOnlySensePlayers

• **bOnlySensePlayers**: `boolean`

#### Defined in

[ue/ue.d.ts:57022](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57022)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bSeePawns

• **bSeePawns**: `boolean`

#### Defined in

[ue/ue.d.ts:57023](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57023)

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

[ActorComponent](ue_ue.ActorComponent.md).[AddTickPrerequisiteActor](ue_ue.ActorComponent.md#addtickprerequisiteactor)

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

[ActorComponent](ue_ue.ActorComponent.md).[AddTickPrerequisiteComponent](ue_ue.ActorComponent.md#addtickprerequisitecomponent)

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

[ActorComponent](ue_ue.ActorComponent.md).[ComponentHasTag](ue_ue.ActorComponent.md#componenthastag)

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

[ActorComponent](ue_ue.ActorComponent.md).[CreateDefaultSubobject](ue_ue.ActorComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[Deactivate](ue_ue.ActorComponent.md#deactivate)

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

[ActorComponent](ue_ue.ActorComponent.md).[ExecuteUbergraph](ue_ue.ActorComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetClass](ue_ue.ActorComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetComponentTickInterval](ue_ue.ActorComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetName](ue_ue.ActorComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOuter](ue_ue.ActorComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOwner](ue_ue.ActorComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetPeripheralVisionAngle

▸ **GetPeripheralVisionAngle**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:57029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57029)

___

### GetPeripheralVisionCosine

▸ **GetPeripheralVisionCosine**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:57030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57030)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetWorld](ue_ue.ActorComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:57031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57031)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsActive](ue_ue.ActorComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsBeingDestroyed](ue_ue.ActorComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsComponentTickEnabled](ue_ue.ActorComponent.md#iscomponenttickenabled)

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

[ActorComponent](ue_ue.ActorComponent.md).[K2_DestroyComponent](ue_ue.ActorComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnRep_IsActive](ue_ue.ActorComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveBeginPlay](ue_ue.ActorComponent.md#receivebeginplay)

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

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveEndPlay](ue_ue.ActorComponent.md#receiveendplay)

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

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveTick](ue_ue.ActorComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[RegisterComponent](ue_ue.ActorComponent.md#registercomponent)

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

[ActorComponent](ue_ue.ActorComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ActorComponent.md#removetickprerequisiteactor)

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

[ActorComponent](ue_ue.ActorComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ActorComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### SeePawnDelegate\_\_DelegateSignature

▸ **SeePawnDelegate__DelegateSignature**(`Pawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57032)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetAutoActivate](ue_ue.ActorComponent.md#setautoactivate)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetComponentTickEnabled](ue_ue.ActorComponent.md#setcomponenttickenabled)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetComponentTickInterval](ue_ue.ActorComponent.md#setcomponenttickinterval)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetIsReplicated](ue_ue.ActorComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

___

### SetPeripheralVisionAngle

▸ **SetPeripheralVisionAngle**(`NewPeripheralVisionAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPeripheralVisionAngle` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57033)

___

### SetSensingInterval

▸ **SetSensingInterval**(`NewSensingInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSensingInterval` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57034)

___

### SetSensingUpdatesEnabled

▸ **SetSensingUpdatesEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57035)

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

[ActorComponent](ue_ue.ActorComponent.md).[SetTickableWhenPaused](ue_ue.ActorComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:57037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57037)

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

#### Defined in

[ue/ue.d.ts:57038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57038)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:57036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57036)
