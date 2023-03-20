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

#### Defined in

[ue/ue.d.ts:14999](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14999)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AssetUserData](ue_ue.ActorComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### BlackboardAsset

• **BlackboardAsset**: [`BlackboardData`](ue_ue.BlackboardData.md)

#### Defined in

[ue/ue.d.ts:15001](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15001)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Defined in

[ue/ue.d.ts:15000](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15000)

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

### KeyInstances

• **KeyInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)\>

#### Defined in

[ue/ue.d.ts:15002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15002)

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

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

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

### \_\_tid\_BlackboardComponent\_\_

• **\_\_tid\_BlackboardComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15031)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_Object__](ue_ue.ActorComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

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

### ClearValue

▸ **ClearValue**(`KeyName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15003](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15003)

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

### GetLocationFromEntry

▸ **GetLocationFromEntry**(`KeyName`, `ResultLocation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `ResultLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15004](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15004)

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

### GetRotationFromEntry

▸ **GetRotationFromEntry**(`KeyName`, `ResultRotation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `ResultRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15005](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15005)

___

### GetValueAsBool

▸ **GetValueAsBool**(`KeyName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15006](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15006)

___

### GetValueAsClass

▸ **GetValueAsClass**(`KeyName`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:15007](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15007)

___

### GetValueAsEnum

▸ **GetValueAsEnum**(`KeyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:15008](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15008)

___

### GetValueAsFloat

▸ **GetValueAsFloat**(`KeyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:15009](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15009)

___

### GetValueAsInt

▸ **GetValueAsInt**(`KeyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:15010](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15010)

___

### GetValueAsName

▸ **GetValueAsName**(`KeyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:15011](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15011)

___

### GetValueAsObject

▸ **GetValueAsObject**(`KeyName`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:15012](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15012)

___

### GetValueAsRotator

▸ **GetValueAsRotator**(`KeyName`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:15013](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15013)

___

### GetValueAsString

▸ **GetValueAsString**(`KeyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:15014](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15014)

___

### GetValueAsVector

▸ **GetValueAsVector**(`KeyName`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:15015](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15015)

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

### IsVectorValueSet

▸ **IsVectorValueSet**(`KeyName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15016](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15016)

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

### SetValueAsBool

▸ **SetValueAsBool**(`KeyName`, `BoolValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyName` | `string` |
| `BoolValue` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15017](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15017)

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

#### Defined in

[ue/ue.d.ts:15018](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15018)

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

#### Defined in

[ue/ue.d.ts:15019](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15019)

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

#### Defined in

[ue/ue.d.ts:15020](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15020)

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

#### Defined in

[ue/ue.d.ts:15021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15021)

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

#### Defined in

[ue/ue.d.ts:15022](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15022)

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

#### Defined in

[ue/ue.d.ts:15023](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15023)

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

#### Defined in

[ue/ue.d.ts:15024](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15024)

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

#### Defined in

[ue/ue.d.ts:15025](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15025)

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

#### Defined in

[ue/ue.d.ts:15026](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15026)

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

#### Defined in

[ue/ue.d.ts:15028](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15028)

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

#### Defined in

[ue/ue.d.ts:15029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15029)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:15027](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15027)
