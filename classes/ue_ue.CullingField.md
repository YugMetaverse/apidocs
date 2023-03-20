[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CullingField

# Class: CullingField

[ue/ue](../modules/ue_ue.md).CullingField

## Hierarchy

- [`FieldNodeBase`](ue_ue.FieldNodeBase.md)

  ↳ **`CullingField`**

## Table of contents

### Constructors

- [constructor](ue_ue.CullingField.md#constructor)

### Properties

- [AssetUserData](ue_ue.CullingField.md#assetuserdata)
- [ComponentTags](ue_ue.CullingField.md#componenttags)
- [CreationMethod](ue_ue.CullingField.md#creationmethod)
- [Culling](ue_ue.CullingField.md#culling)
- [Field](ue_ue.CullingField.md#field)
- [OnComponentActivated](ue_ue.CullingField.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.CullingField.md#oncomponentdeactivated)
- [Operation](ue_ue.CullingField.md#operation)
- [PrimaryComponentTick](ue_ue.CullingField.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.CullingField.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CullingField.md#__tid_actorcomponent__)
- [\_\_tid\_CullingField\_\_](ue_ue.CullingField.md#__tid_cullingfield__)
- [\_\_tid\_FieldNodeBase\_\_](ue_ue.CullingField.md#__tid_fieldnodebase__)
- [\_\_tid\_Object\_\_](ue_ue.CullingField.md#__tid_object__)
- [bAutoActivate](ue_ue.CullingField.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.CullingField.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.CullingField.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.CullingField.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.CullingField.md#binstancecomponent)
- [bIsActive](ue_ue.CullingField.md#bisactive)
- [bIsEditorOnly](ue_ue.CullingField.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CullingField.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.CullingField.md#bnetaddressable)
- [bReplicates](ue_ue.CullingField.md#breplicates)

### Methods

- [Activate](ue_ue.CullingField.md#activate)
- [AddTickPrerequisiteActor](ue_ue.CullingField.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CullingField.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.CullingField.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.CullingField.md#createdefaultsubobject)
- [Deactivate](ue_ue.CullingField.md#deactivate)
- [ExecuteUbergraph](ue_ue.CullingField.md#executeubergraph)
- [GetClass](ue_ue.CullingField.md#getclass)
- [GetComponentTickInterval](ue_ue.CullingField.md#getcomponenttickinterval)
- [GetName](ue_ue.CullingField.md#getname)
- [GetOuter](ue_ue.CullingField.md#getouter)
- [GetOwner](ue_ue.CullingField.md#getowner)
- [GetWorld](ue_ue.CullingField.md#getworld)
- [IsActive](ue_ue.CullingField.md#isactive)
- [IsBeingDestroyed](ue_ue.CullingField.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CullingField.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.CullingField.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.CullingField.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.CullingField.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CullingField.md#receiveendplay)
- [ReceiveTick](ue_ue.CullingField.md#receivetick)
- [RegisterComponent](ue_ue.CullingField.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.CullingField.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CullingField.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.CullingField.md#setactive)
- [SetAutoActivate](ue_ue.CullingField.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.CullingField.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CullingField.md#setcomponenttickinterval)
- [SetCullingField](ue_ue.CullingField.md#setcullingfield)
- [SetIsReplicated](ue_ue.CullingField.md#setisreplicated)
- [SetTickGroup](ue_ue.CullingField.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CullingField.md#settickablewhenpaused)
- [ToggleActive](ue_ue.CullingField.md#toggleactive)
- [Find](ue_ue.CullingField.md#find)
- [Load](ue_ue.CullingField.md#load)
- [StaticClass](ue_ue.CullingField.md#staticclass)

## Constructors

### constructor

• **new CullingField**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[constructor](ue_ue.FieldNodeBase.md#constructor)

#### Defined in

[ue/ue.d.ts:29036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29036)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[AssetUserData](ue_ue.FieldNodeBase.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ComponentTags](ue_ue.FieldNodeBase.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[CreationMethod](ue_ue.FieldNodeBase.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### Culling

• **Culling**: [`FieldNodeBase`](ue_ue.FieldNodeBase.md)

#### Defined in

[ue/ue.d.ts:29037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29037)

___

### Field

• **Field**: [`FieldNodeBase`](ue_ue.FieldNodeBase.md)

#### Defined in

[ue/ue.d.ts:29038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29038)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[OnComponentActivated](ue_ue.FieldNodeBase.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[OnComponentDeactivated](ue_ue.FieldNodeBase.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### Operation

• **Operation**: [`EFieldCullingOperationType`](../enums/ue_ue.EFieldCullingOperationType.md)

#### Defined in

[ue/ue.d.ts:29039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29039)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[PrimaryComponentTick](ue_ue.FieldNodeBase.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[UCSModifiedProperties](ue_ue.FieldNodeBase.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[__tid_ActorComponent__](ue_ue.FieldNodeBase.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_CullingField\_\_

• **\_\_tid\_CullingField\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29045)

___

### \_\_tid\_FieldNodeBase\_\_

• **\_\_tid\_FieldNodeBase\_\_**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[__tid_FieldNodeBase__](ue_ue.FieldNodeBase.md#__tid_fieldnodebase__)

#### Defined in

[ue/ue.d.ts:24500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24500)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[__tid_Object__](ue_ue.FieldNodeBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bAutoActivate](ue_ue.FieldNodeBase.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bCanEverAffectNavigation](ue_ue.FieldNodeBase.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bCreatedByConstructionScript](ue_ue.FieldNodeBase.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bEditableWhenInherited](ue_ue.FieldNodeBase.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bInstanceComponent](ue_ue.FieldNodeBase.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bIsActive](ue_ue.FieldNodeBase.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bIsEditorOnly](ue_ue.FieldNodeBase.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bIsVisualizationComponent](ue_ue.FieldNodeBase.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bNetAddressable](ue_ue.FieldNodeBase.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[bReplicates](ue_ue.FieldNodeBase.md#breplicates)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Activate](ue_ue.FieldNodeBase.md#activate)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[AddTickPrerequisiteActor](ue_ue.FieldNodeBase.md#addtickprerequisiteactor)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[AddTickPrerequisiteComponent](ue_ue.FieldNodeBase.md#addtickprerequisitecomponent)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ComponentHasTag](ue_ue.FieldNodeBase.md#componenthastag)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[CreateDefaultSubobject](ue_ue.FieldNodeBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Deactivate](ue_ue.FieldNodeBase.md#deactivate)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ExecuteUbergraph](ue_ue.FieldNodeBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetClass](ue_ue.FieldNodeBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetComponentTickInterval](ue_ue.FieldNodeBase.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetName](ue_ue.FieldNodeBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetOuter](ue_ue.FieldNodeBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetOwner](ue_ue.FieldNodeBase.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[GetWorld](ue_ue.FieldNodeBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[IsActive](ue_ue.FieldNodeBase.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[IsBeingDestroyed](ue_ue.FieldNodeBase.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[IsComponentTickEnabled](ue_ue.FieldNodeBase.md#iscomponenttickenabled)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[K2_DestroyComponent](ue_ue.FieldNodeBase.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[OnRep_IsActive](ue_ue.FieldNodeBase.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ReceiveBeginPlay](ue_ue.FieldNodeBase.md#receivebeginplay)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ReceiveEndPlay](ue_ue.FieldNodeBase.md#receiveendplay)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ReceiveTick](ue_ue.FieldNodeBase.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[RegisterComponent](ue_ue.FieldNodeBase.md#registercomponent)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[RemoveTickPrerequisiteActor](ue_ue.FieldNodeBase.md#removetickprerequisiteactor)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[RemoveTickPrerequisiteComponent](ue_ue.FieldNodeBase.md#removetickprerequisitecomponent)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetActive](ue_ue.FieldNodeBase.md#setactive)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetAutoActivate](ue_ue.FieldNodeBase.md#setautoactivate)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetComponentTickEnabled](ue_ue.FieldNodeBase.md#setcomponenttickenabled)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetComponentTickInterval](ue_ue.FieldNodeBase.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

___

### SetCullingField

▸ **SetCullingField**(`Culling`, `Field`, `Operation`): [`CullingField`](ue_ue.CullingField.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Culling` | [`$Nullable`](../modules/puerts.md#$nullable)<[`FieldNodeBase`](ue_ue.FieldNodeBase.md)\> |
| `Field` | [`$Nullable`](../modules/puerts.md#$nullable)<[`FieldNodeBase`](ue_ue.FieldNodeBase.md)\> |
| `Operation` | [`EFieldCullingOperationType`](../enums/ue_ue.EFieldCullingOperationType.md) |

#### Returns

[`CullingField`](ue_ue.CullingField.md)

#### Defined in

[ue/ue.d.ts:29040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29040)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetIsReplicated](ue_ue.FieldNodeBase.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetTickGroup](ue_ue.FieldNodeBase.md#settickgroup)

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

[FieldNodeBase](ue_ue.FieldNodeBase.md).[SetTickableWhenPaused](ue_ue.FieldNodeBase.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeBase](ue_ue.FieldNodeBase.md).[ToggleActive](ue_ue.FieldNodeBase.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CullingField`](ue_ue.CullingField.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CullingField`](ue_ue.CullingField.md)

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Find](ue_ue.FieldNodeBase.md#find)

#### Defined in

[ue/ue.d.ts:29042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29042)

___

### Load

▸ `Static` **Load**(`InName`): [`CullingField`](ue_ue.CullingField.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CullingField`](ue_ue.CullingField.md)

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[Load](ue_ue.FieldNodeBase.md#load)

#### Defined in

[ue/ue.d.ts:29043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29043)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FieldNodeBase](ue_ue.FieldNodeBase.md).[StaticClass](ue_ue.FieldNodeBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:29041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29041)
