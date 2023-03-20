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

#### Defined in

[ue/ue.d.ts:59045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59045)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[AssetUserData](ue_ue.FieldNodeInt.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ComponentTags](ue_ue.FieldNodeInt.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[CreationMethod](ue_ue.FieldNodeInt.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### ExteriorValue

• **ExteriorValue**: `number`

#### Defined in

[ue/ue.d.ts:59049](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59049)

___

### InteriorValue

• **InteriorValue**: `number`

#### Defined in

[ue/ue.d.ts:59048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59048)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[OnComponentActivated](ue_ue.FieldNodeInt.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[OnComponentDeactivated](ue_ue.FieldNodeInt.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### Position

• **Position**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:59047](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59047)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[PrimaryComponentTick](ue_ue.FieldNodeInt.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### Radius

• **Radius**: `number`

#### Defined in

[ue/ue.d.ts:59046](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59046)

___

### SetMaskCondition

• **SetMaskCondition**: [`ESetMaskConditionType`](../enums/ue_ue.ESetMaskConditionType.md)

#### Defined in

[ue/ue.d.ts:59050](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59050)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[UCSModifiedProperties](ue_ue.FieldNodeInt.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_ActorComponent__](ue_ue.FieldNodeInt.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_FieldNodeBase\_\_

• **\_\_tid\_FieldNodeBase\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_FieldNodeBase__](ue_ue.FieldNodeInt.md#__tid_fieldnodebase__)

#### Defined in

[ue/ue.d.ts:24500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24500)

___

### \_\_tid\_FieldNodeInt\_\_

• **\_\_tid\_FieldNodeInt\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_FieldNodeInt__](ue_ue.FieldNodeInt.md#__tid_fieldnodeint__)

#### Defined in

[ue/ue.d.ts:35482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35482)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[__tid_Object__](ue_ue.FieldNodeInt.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_RadialIntMask\_\_

• **\_\_tid\_RadialIntMask\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59056](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59056)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bAutoActivate](ue_ue.FieldNodeInt.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bCanEverAffectNavigation](ue_ue.FieldNodeInt.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bCreatedByConstructionScript](ue_ue.FieldNodeInt.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bEditableWhenInherited](ue_ue.FieldNodeInt.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bInstanceComponent](ue_ue.FieldNodeInt.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bIsActive](ue_ue.FieldNodeInt.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bIsEditorOnly](ue_ue.FieldNodeInt.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bIsVisualizationComponent](ue_ue.FieldNodeInt.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bNetAddressable](ue_ue.FieldNodeInt.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[bReplicates](ue_ue.FieldNodeInt.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

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

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L307)

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

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L308)

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

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[Deactivate](ue_ue.FieldNodeInt.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L310)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetClass](ue_ue.FieldNodeInt.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetComponentTickInterval](ue_ue.FieldNodeInt.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetName](ue_ue.FieldNodeInt.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetOuter](ue_ue.FieldNodeInt.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetOwner](ue_ue.FieldNodeInt.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[GetWorld](ue_ue.FieldNodeInt.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[IsActive](ue_ue.FieldNodeInt.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[IsBeingDestroyed](ue_ue.FieldNodeInt.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[IsComponentTickEnabled](ue_ue.FieldNodeInt.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

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

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[OnRep_IsActive](ue_ue.FieldNodeInt.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ReceiveBeginPlay](ue_ue.FieldNodeInt.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L318)

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

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L319)

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

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[RegisterComponent](ue_ue.FieldNodeInt.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

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

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L322)

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

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

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

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L324)

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

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

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

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L326)

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

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

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

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

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

#### Defined in

[ue/ue.d.ts:59051](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59051)

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

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L330)

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

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeInt](ue_ue.FieldNodeInt.md).[ToggleActive](ue_ue.FieldNodeInt.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:59053](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59053)

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

#### Defined in

[ue/ue.d.ts:59054](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59054)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FieldNodeInt](ue_ue.FieldNodeInt.md).[StaticClass](ue_ue.FieldNodeInt.md#staticclass)

#### Defined in

[ue/ue.d.ts:59052](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59052)