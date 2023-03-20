[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BoxFalloff

# Class: BoxFalloff

[ue/ue](../modules/ue_ue.md).BoxFalloff

## Hierarchy

- [`FieldNodeFloat`](ue_ue.FieldNodeFloat.md)

  ↳ **`BoxFalloff`**

## Table of contents

### Constructors

- [constructor](ue_ue.BoxFalloff.md#constructor)

### Properties

- [AssetUserData](ue_ue.BoxFalloff.md#assetuserdata)
- [ComponentTags](ue_ue.BoxFalloff.md#componenttags)
- [CreationMethod](ue_ue.BoxFalloff.md#creationmethod)
- [Default](ue_ue.BoxFalloff.md#default)
- [Falloff](ue_ue.BoxFalloff.md#falloff)
- [Magnitude](ue_ue.BoxFalloff.md#magnitude)
- [MaxRange](ue_ue.BoxFalloff.md#maxrange)
- [MinRange](ue_ue.BoxFalloff.md#minrange)
- [OnComponentActivated](ue_ue.BoxFalloff.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.BoxFalloff.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.BoxFalloff.md#primarycomponenttick)
- [Transform](ue_ue.BoxFalloff.md#transform)
- [UCSModifiedProperties](ue_ue.BoxFalloff.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.BoxFalloff.md#__tid_actorcomponent__)
- [\_\_tid\_BoxFalloff\_\_](ue_ue.BoxFalloff.md#__tid_boxfalloff__)
- [\_\_tid\_FieldNodeBase\_\_](ue_ue.BoxFalloff.md#__tid_fieldnodebase__)
- [\_\_tid\_FieldNodeFloat\_\_](ue_ue.BoxFalloff.md#__tid_fieldnodefloat__)
- [\_\_tid\_Object\_\_](ue_ue.BoxFalloff.md#__tid_object__)
- [bAutoActivate](ue_ue.BoxFalloff.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.BoxFalloff.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.BoxFalloff.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.BoxFalloff.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.BoxFalloff.md#binstancecomponent)
- [bIsActive](ue_ue.BoxFalloff.md#bisactive)
- [bIsEditorOnly](ue_ue.BoxFalloff.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.BoxFalloff.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.BoxFalloff.md#bnetaddressable)
- [bReplicates](ue_ue.BoxFalloff.md#breplicates)

### Methods

- [Activate](ue_ue.BoxFalloff.md#activate)
- [AddTickPrerequisiteActor](ue_ue.BoxFalloff.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.BoxFalloff.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.BoxFalloff.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.BoxFalloff.md#createdefaultsubobject)
- [Deactivate](ue_ue.BoxFalloff.md#deactivate)
- [ExecuteUbergraph](ue_ue.BoxFalloff.md#executeubergraph)
- [GetClass](ue_ue.BoxFalloff.md#getclass)
- [GetComponentTickInterval](ue_ue.BoxFalloff.md#getcomponenttickinterval)
- [GetName](ue_ue.BoxFalloff.md#getname)
- [GetOuter](ue_ue.BoxFalloff.md#getouter)
- [GetOwner](ue_ue.BoxFalloff.md#getowner)
- [GetWorld](ue_ue.BoxFalloff.md#getworld)
- [IsActive](ue_ue.BoxFalloff.md#isactive)
- [IsBeingDestroyed](ue_ue.BoxFalloff.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.BoxFalloff.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.BoxFalloff.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.BoxFalloff.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.BoxFalloff.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.BoxFalloff.md#receiveendplay)
- [ReceiveTick](ue_ue.BoxFalloff.md#receivetick)
- [RegisterComponent](ue_ue.BoxFalloff.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.BoxFalloff.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.BoxFalloff.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.BoxFalloff.md#setactive)
- [SetAutoActivate](ue_ue.BoxFalloff.md#setautoactivate)
- [SetBoxFalloff](ue_ue.BoxFalloff.md#setboxfalloff)
- [SetComponentTickEnabled](ue_ue.BoxFalloff.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.BoxFalloff.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.BoxFalloff.md#setisreplicated)
- [SetTickGroup](ue_ue.BoxFalloff.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.BoxFalloff.md#settickablewhenpaused)
- [ToggleActive](ue_ue.BoxFalloff.md#toggleactive)
- [Find](ue_ue.BoxFalloff.md#find)
- [Load](ue_ue.BoxFalloff.md#load)
- [StaticClass](ue_ue.BoxFalloff.md#staticclass)

## Constructors

### constructor

• **new BoxFalloff**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[constructor](ue_ue.FieldNodeFloat.md#constructor)

#### Defined in

[ue/ue.d.ts:24514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24514)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[AssetUserData](ue_ue.FieldNodeFloat.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ComponentTags](ue_ue.FieldNodeFloat.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[CreationMethod](ue_ue.FieldNodeFloat.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### Default

• **Default**: `number`

#### Defined in

[ue/ue.d.ts:24518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24518)

___

### Falloff

• **Falloff**: [`EFieldFalloffType`](../enums/ue_ue.EFieldFalloffType.md)

#### Defined in

[ue/ue.d.ts:24520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24520)

___

### Magnitude

• **Magnitude**: `number`

#### Defined in

[ue/ue.d.ts:24515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24515)

___

### MaxRange

• **MaxRange**: `number`

#### Defined in

[ue/ue.d.ts:24517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24517)

___

### MinRange

• **MinRange**: `number`

#### Defined in

[ue/ue.d.ts:24516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24516)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[OnComponentActivated](ue_ue.FieldNodeFloat.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[OnComponentDeactivated](ue_ue.FieldNodeFloat.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[PrimaryComponentTick](ue_ue.FieldNodeFloat.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### Transform

• **Transform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:24519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24519)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[UCSModifiedProperties](ue_ue.FieldNodeFloat.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_ActorComponent__](ue_ue.FieldNodeFloat.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_BoxFalloff\_\_

• **\_\_tid\_BoxFalloff\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24526)

___

### \_\_tid\_FieldNodeBase\_\_

• **\_\_tid\_FieldNodeBase\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_FieldNodeBase__](ue_ue.FieldNodeFloat.md#__tid_fieldnodebase__)

#### Defined in

[ue/ue.d.ts:24500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24500)

___

### \_\_tid\_FieldNodeFloat\_\_

• **\_\_tid\_FieldNodeFloat\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_FieldNodeFloat__](ue_ue.FieldNodeFloat.md#__tid_fieldnodefloat__)

#### Defined in

[ue/ue.d.ts:24509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24509)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[__tid_Object__](ue_ue.FieldNodeFloat.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bAutoActivate](ue_ue.FieldNodeFloat.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bCanEverAffectNavigation](ue_ue.FieldNodeFloat.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bCreatedByConstructionScript](ue_ue.FieldNodeFloat.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bEditableWhenInherited](ue_ue.FieldNodeFloat.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bInstanceComponent](ue_ue.FieldNodeFloat.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bIsActive](ue_ue.FieldNodeFloat.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bIsEditorOnly](ue_ue.FieldNodeFloat.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bIsVisualizationComponent](ue_ue.FieldNodeFloat.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bNetAddressable](ue_ue.FieldNodeFloat.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[bReplicates](ue_ue.FieldNodeFloat.md#breplicates)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Activate](ue_ue.FieldNodeFloat.md#activate)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[AddTickPrerequisiteActor](ue_ue.FieldNodeFloat.md#addtickprerequisiteactor)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[AddTickPrerequisiteComponent](ue_ue.FieldNodeFloat.md#addtickprerequisitecomponent)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ComponentHasTag](ue_ue.FieldNodeFloat.md#componenthastag)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[CreateDefaultSubobject](ue_ue.FieldNodeFloat.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Deactivate](ue_ue.FieldNodeFloat.md#deactivate)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ExecuteUbergraph](ue_ue.FieldNodeFloat.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetClass](ue_ue.FieldNodeFloat.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetComponentTickInterval](ue_ue.FieldNodeFloat.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetName](ue_ue.FieldNodeFloat.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetOuter](ue_ue.FieldNodeFloat.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetOwner](ue_ue.FieldNodeFloat.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[GetWorld](ue_ue.FieldNodeFloat.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[IsActive](ue_ue.FieldNodeFloat.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[IsBeingDestroyed](ue_ue.FieldNodeFloat.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[IsComponentTickEnabled](ue_ue.FieldNodeFloat.md#iscomponenttickenabled)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[K2_DestroyComponent](ue_ue.FieldNodeFloat.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[OnRep_IsActive](ue_ue.FieldNodeFloat.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ReceiveBeginPlay](ue_ue.FieldNodeFloat.md#receivebeginplay)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ReceiveEndPlay](ue_ue.FieldNodeFloat.md#receiveendplay)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ReceiveTick](ue_ue.FieldNodeFloat.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[RegisterComponent](ue_ue.FieldNodeFloat.md#registercomponent)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[RemoveTickPrerequisiteActor](ue_ue.FieldNodeFloat.md#removetickprerequisiteactor)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[RemoveTickPrerequisiteComponent](ue_ue.FieldNodeFloat.md#removetickprerequisitecomponent)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetActive](ue_ue.FieldNodeFloat.md#setactive)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetAutoActivate](ue_ue.FieldNodeFloat.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

___

### SetBoxFalloff

▸ **SetBoxFalloff**(`Magnitude`, `MinRange`, `MaxRange`, `Default`, `Transform`, `Falloff`): [`BoxFalloff`](ue_ue.BoxFalloff.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Magnitude` | `number` |
| `MinRange` | `number` |
| `MaxRange` | `number` |
| `Default` | `number` |
| `Transform` | [`Transform`](ue_ue_s.Transform.md) |
| `Falloff` | [`EFieldFalloffType`](../enums/ue_ue.EFieldFalloffType.md) |

#### Returns

[`BoxFalloff`](ue_ue.BoxFalloff.md)

#### Defined in

[ue/ue.d.ts:24521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24521)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetComponentTickInterval](ue_ue.FieldNodeFloat.md#setcomponenttickinterval)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetIsReplicated](ue_ue.FieldNodeFloat.md#setisreplicated)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetTickGroup](ue_ue.FieldNodeFloat.md#settickgroup)

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

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[SetTickableWhenPaused](ue_ue.FieldNodeFloat.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[ToggleActive](ue_ue.FieldNodeFloat.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BoxFalloff`](ue_ue.BoxFalloff.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BoxFalloff`](ue_ue.BoxFalloff.md)

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Find](ue_ue.FieldNodeFloat.md#find)

#### Defined in

[ue/ue.d.ts:24523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24523)

___

### Load

▸ `Static` **Load**(`InName`): [`BoxFalloff`](ue_ue.BoxFalloff.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BoxFalloff`](ue_ue.BoxFalloff.md)

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[Load](ue_ue.FieldNodeFloat.md#load)

#### Defined in

[ue/ue.d.ts:24524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24524)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FieldNodeFloat](ue_ue.FieldNodeFloat.md).[StaticClass](ue_ue.FieldNodeFloat.md#staticclass)

#### Defined in

[ue/ue.d.ts:24522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24522)
