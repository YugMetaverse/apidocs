[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ChaosGameplayEventDispatcher

# Class: ChaosGameplayEventDispatcher

[ue/ue](../modules/ue_ue.md).ChaosGameplayEventDispatcher

## Hierarchy

- [`ChaosEventListenerComponent`](ue_ue.ChaosEventListenerComponent.md)

  ↳ **`ChaosGameplayEventDispatcher`**

## Table of contents

### Constructors

- [constructor](ue_ue.ChaosGameplayEventDispatcher.md#constructor)

### Properties

- [AssetUserData](ue_ue.ChaosGameplayEventDispatcher.md#assetuserdata)
- [BreakEventRegistrations](ue_ue.ChaosGameplayEventDispatcher.md#breakeventregistrations)
- [CollisionEventRegistrations](ue_ue.ChaosGameplayEventDispatcher.md#collisioneventregistrations)
- [ComponentTags](ue_ue.ChaosGameplayEventDispatcher.md#componenttags)
- [CreationMethod](ue_ue.ChaosGameplayEventDispatcher.md#creationmethod)
- [OnComponentActivated](ue_ue.ChaosGameplayEventDispatcher.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.ChaosGameplayEventDispatcher.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.ChaosGameplayEventDispatcher.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.ChaosGameplayEventDispatcher.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ChaosGameplayEventDispatcher.md#__tid_actorcomponent__)
- [\_\_tid\_ChaosEventListenerComponent\_\_](ue_ue.ChaosGameplayEventDispatcher.md#__tid_chaoseventlistenercomponent__)
- [\_\_tid\_ChaosGameplayEventDispatcher\_\_](ue_ue.ChaosGameplayEventDispatcher.md#__tid_chaosgameplayeventdispatcher__)
- [\_\_tid\_Object\_\_](ue_ue.ChaosGameplayEventDispatcher.md#__tid_object__)
- [bAutoActivate](ue_ue.ChaosGameplayEventDispatcher.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.ChaosGameplayEventDispatcher.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.ChaosGameplayEventDispatcher.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.ChaosGameplayEventDispatcher.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.ChaosGameplayEventDispatcher.md#binstancecomponent)
- [bIsActive](ue_ue.ChaosGameplayEventDispatcher.md#bisactive)
- [bIsEditorOnly](ue_ue.ChaosGameplayEventDispatcher.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ChaosGameplayEventDispatcher.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.ChaosGameplayEventDispatcher.md#bnetaddressable)
- [bReplicates](ue_ue.ChaosGameplayEventDispatcher.md#breplicates)

### Methods

- [Activate](ue_ue.ChaosGameplayEventDispatcher.md#activate)
- [AddTickPrerequisiteActor](ue_ue.ChaosGameplayEventDispatcher.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ChaosGameplayEventDispatcher.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.ChaosGameplayEventDispatcher.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.ChaosGameplayEventDispatcher.md#createdefaultsubobject)
- [Deactivate](ue_ue.ChaosGameplayEventDispatcher.md#deactivate)
- [ExecuteUbergraph](ue_ue.ChaosGameplayEventDispatcher.md#executeubergraph)
- [GetClass](ue_ue.ChaosGameplayEventDispatcher.md#getclass)
- [GetComponentTickInterval](ue_ue.ChaosGameplayEventDispatcher.md#getcomponenttickinterval)
- [GetName](ue_ue.ChaosGameplayEventDispatcher.md#getname)
- [GetOuter](ue_ue.ChaosGameplayEventDispatcher.md#getouter)
- [GetOwner](ue_ue.ChaosGameplayEventDispatcher.md#getowner)
- [GetWorld](ue_ue.ChaosGameplayEventDispatcher.md#getworld)
- [IsActive](ue_ue.ChaosGameplayEventDispatcher.md#isactive)
- [IsBeingDestroyed](ue_ue.ChaosGameplayEventDispatcher.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ChaosGameplayEventDispatcher.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.ChaosGameplayEventDispatcher.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.ChaosGameplayEventDispatcher.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.ChaosGameplayEventDispatcher.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ChaosGameplayEventDispatcher.md#receiveendplay)
- [ReceiveTick](ue_ue.ChaosGameplayEventDispatcher.md#receivetick)
- [RegisterComponent](ue_ue.ChaosGameplayEventDispatcher.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ChaosGameplayEventDispatcher.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ChaosGameplayEventDispatcher.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.ChaosGameplayEventDispatcher.md#setactive)
- [SetAutoActivate](ue_ue.ChaosGameplayEventDispatcher.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.ChaosGameplayEventDispatcher.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ChaosGameplayEventDispatcher.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.ChaosGameplayEventDispatcher.md#setisreplicated)
- [SetTickGroup](ue_ue.ChaosGameplayEventDispatcher.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ChaosGameplayEventDispatcher.md#settickablewhenpaused)
- [ToggleActive](ue_ue.ChaosGameplayEventDispatcher.md#toggleactive)
- [Find](ue_ue.ChaosGameplayEventDispatcher.md#find)
- [Load](ue_ue.ChaosGameplayEventDispatcher.md#load)
- [StaticClass](ue_ue.ChaosGameplayEventDispatcher.md#staticclass)

## Constructors

### constructor

• **new ChaosGameplayEventDispatcher**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[constructor](ue_ue.ChaosEventListenerComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:26460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26460)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[AssetUserData](ue_ue.ChaosEventListenerComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### BreakEventRegistrations

• **BreakEventRegistrations**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md), [`BreakEventCallbackWrapper`](ue_ue.BreakEventCallbackWrapper.md)\>

#### Defined in

[ue/ue.d.ts:26462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26462)

___

### CollisionEventRegistrations

• **CollisionEventRegistrations**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md), [`ChaosHandlerSet`](ue_ue.ChaosHandlerSet.md)\>

#### Defined in

[ue/ue.d.ts:26461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26461)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ComponentTags](ue_ue.ChaosEventListenerComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[CreationMethod](ue_ue.ChaosEventListenerComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[OnComponentActivated](ue_ue.ChaosEventListenerComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[OnComponentDeactivated](ue_ue.ChaosEventListenerComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[PrimaryComponentTick](ue_ue.ChaosEventListenerComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[UCSModifiedProperties](ue_ue.ChaosEventListenerComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[__tid_ActorComponent__](ue_ue.ChaosEventListenerComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_ChaosEventListenerComponent\_\_

• **\_\_tid\_ChaosEventListenerComponent\_\_**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[__tid_ChaosEventListenerComponent__](ue_ue.ChaosEventListenerComponent.md#__tid_chaoseventlistenercomponent__)

#### Defined in

[ue/ue.d.ts:26434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26434)

___

### \_\_tid\_ChaosGameplayEventDispatcher\_\_

• **\_\_tid\_ChaosGameplayEventDispatcher\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:26467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26467)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[__tid_Object__](ue_ue.ChaosEventListenerComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bAutoActivate](ue_ue.ChaosEventListenerComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bCanEverAffectNavigation](ue_ue.ChaosEventListenerComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bCreatedByConstructionScript](ue_ue.ChaosEventListenerComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bEditableWhenInherited](ue_ue.ChaosEventListenerComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bInstanceComponent](ue_ue.ChaosEventListenerComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bIsActive](ue_ue.ChaosEventListenerComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bIsEditorOnly](ue_ue.ChaosEventListenerComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bIsVisualizationComponent](ue_ue.ChaosEventListenerComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bNetAddressable](ue_ue.ChaosEventListenerComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[bReplicates](ue_ue.ChaosEventListenerComponent.md#breplicates)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[Activate](ue_ue.ChaosEventListenerComponent.md#activate)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[AddTickPrerequisiteActor](ue_ue.ChaosEventListenerComponent.md#addtickprerequisiteactor)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[AddTickPrerequisiteComponent](ue_ue.ChaosEventListenerComponent.md#addtickprerequisitecomponent)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ComponentHasTag](ue_ue.ChaosEventListenerComponent.md#componenthastag)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[CreateDefaultSubobject](ue_ue.ChaosEventListenerComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[Deactivate](ue_ue.ChaosEventListenerComponent.md#deactivate)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ExecuteUbergraph](ue_ue.ChaosEventListenerComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[GetClass](ue_ue.ChaosEventListenerComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[GetComponentTickInterval](ue_ue.ChaosEventListenerComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[GetName](ue_ue.ChaosEventListenerComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[GetOuter](ue_ue.ChaosEventListenerComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[GetOwner](ue_ue.ChaosEventListenerComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[GetWorld](ue_ue.ChaosEventListenerComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[IsActive](ue_ue.ChaosEventListenerComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[IsBeingDestroyed](ue_ue.ChaosEventListenerComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[IsComponentTickEnabled](ue_ue.ChaosEventListenerComponent.md#iscomponenttickenabled)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[K2_DestroyComponent](ue_ue.ChaosEventListenerComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[OnRep_IsActive](ue_ue.ChaosEventListenerComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ReceiveBeginPlay](ue_ue.ChaosEventListenerComponent.md#receivebeginplay)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ReceiveEndPlay](ue_ue.ChaosEventListenerComponent.md#receiveendplay)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ReceiveTick](ue_ue.ChaosEventListenerComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[RegisterComponent](ue_ue.ChaosEventListenerComponent.md#registercomponent)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ChaosEventListenerComponent.md#removetickprerequisiteactor)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ChaosEventListenerComponent.md#removetickprerequisitecomponent)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetActive](ue_ue.ChaosEventListenerComponent.md#setactive)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetAutoActivate](ue_ue.ChaosEventListenerComponent.md#setautoactivate)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetComponentTickEnabled](ue_ue.ChaosEventListenerComponent.md#setcomponenttickenabled)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetComponentTickInterval](ue_ue.ChaosEventListenerComponent.md#setcomponenttickinterval)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetIsReplicated](ue_ue.ChaosEventListenerComponent.md#setisreplicated)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetTickGroup](ue_ue.ChaosEventListenerComponent.md#settickgroup)

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

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[SetTickableWhenPaused](ue_ue.ChaosEventListenerComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[ToggleActive](ue_ue.ChaosEventListenerComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ChaosGameplayEventDispatcher`](ue_ue.ChaosGameplayEventDispatcher.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ChaosGameplayEventDispatcher`](ue_ue.ChaosGameplayEventDispatcher.md)

#### Overrides

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[Find](ue_ue.ChaosEventListenerComponent.md#find)

#### Defined in

[ue/ue.d.ts:26464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26464)

___

### Load

▸ `Static` **Load**(`InName`): [`ChaosGameplayEventDispatcher`](ue_ue.ChaosGameplayEventDispatcher.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ChaosGameplayEventDispatcher`](ue_ue.ChaosGameplayEventDispatcher.md)

#### Overrides

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[Load](ue_ue.ChaosEventListenerComponent.md#load)

#### Defined in

[ue/ue.d.ts:26465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26465)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ChaosEventListenerComponent](ue_ue.ChaosEventListenerComponent.md).[StaticClass](ue_ue.ChaosEventListenerComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:26463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L26463)
