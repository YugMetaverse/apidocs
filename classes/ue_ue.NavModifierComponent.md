[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavModifierComponent

# Class: NavModifierComponent

[ue/ue](../modules/ue_ue.md).NavModifierComponent

## Hierarchy

- [`NavRelevantComponent`](ue_ue.NavRelevantComponent.md)

  ↳ **`NavModifierComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavModifierComponent.md#constructor)

### Properties

- [AreaClass](ue_ue.NavModifierComponent.md#areaclass)
- [AssetUserData](ue_ue.NavModifierComponent.md#assetuserdata)
- [CachedNavParent](ue_ue.NavModifierComponent.md#cachednavparent)
- [ComponentTags](ue_ue.NavModifierComponent.md#componenttags)
- [CreationMethod](ue_ue.NavModifierComponent.md#creationmethod)
- [FailsafeExtent](ue_ue.NavModifierComponent.md#failsafeextent)
- [OnComponentActivated](ue_ue.NavModifierComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.NavModifierComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.NavModifierComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.NavModifierComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.NavModifierComponent.md#__tid_actorcomponent__)
- [\_\_tid\_NavModifierComponent\_\_](ue_ue.NavModifierComponent.md#__tid_navmodifiercomponent__)
- [\_\_tid\_NavRelevantComponent\_\_](ue_ue.NavModifierComponent.md#__tid_navrelevantcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.NavModifierComponent.md#__tid_object__)
- [bAttachToOwnersRoot](ue_ue.NavModifierComponent.md#battachtoownersroot)
- [bAutoActivate](ue_ue.NavModifierComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.NavModifierComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.NavModifierComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.NavModifierComponent.md#beditablewheninherited)
- [bIncludeAgentHeight](ue_ue.NavModifierComponent.md#bincludeagentheight)
- [bInstanceComponent](ue_ue.NavModifierComponent.md#binstancecomponent)
- [bIsActive](ue_ue.NavModifierComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.NavModifierComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.NavModifierComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.NavModifierComponent.md#bnetaddressable)
- [bReplicates](ue_ue.NavModifierComponent.md#breplicates)

### Methods

- [Activate](ue_ue.NavModifierComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.NavModifierComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.NavModifierComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.NavModifierComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.NavModifierComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.NavModifierComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.NavModifierComponent.md#executeubergraph)
- [GetClass](ue_ue.NavModifierComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.NavModifierComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.NavModifierComponent.md#getname)
- [GetOuter](ue_ue.NavModifierComponent.md#getouter)
- [GetOwner](ue_ue.NavModifierComponent.md#getowner)
- [GetWorld](ue_ue.NavModifierComponent.md#getworld)
- [IsActive](ue_ue.NavModifierComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.NavModifierComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.NavModifierComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.NavModifierComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.NavModifierComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.NavModifierComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.NavModifierComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.NavModifierComponent.md#receivetick)
- [RegisterComponent](ue_ue.NavModifierComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.NavModifierComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.NavModifierComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.NavModifierComponent.md#setactive)
- [SetAreaClass](ue_ue.NavModifierComponent.md#setareaclass)
- [SetAutoActivate](ue_ue.NavModifierComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.NavModifierComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.NavModifierComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.NavModifierComponent.md#setisreplicated)
- [SetNavigationRelevancy](ue_ue.NavModifierComponent.md#setnavigationrelevancy)
- [SetTickGroup](ue_ue.NavModifierComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.NavModifierComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.NavModifierComponent.md#toggleactive)
- [Find](ue_ue.NavModifierComponent.md#find)
- [Load](ue_ue.NavModifierComponent.md#load)
- [StaticClass](ue_ue.NavModifierComponent.md#staticclass)

## Constructors

### constructor

• **new NavModifierComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[constructor](ue_ue.NavRelevantComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:53371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53371)

## Properties

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:53372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53372)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[AssetUserData](ue_ue.NavRelevantComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### CachedNavParent

• **CachedNavParent**: [`Object`](ue_ue.Object.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[CachedNavParent](ue_ue.NavRelevantComponent.md#cachednavparent)

#### Defined in

[ue/ue.d.ts:53243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53243)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ComponentTags](ue_ue.NavRelevantComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[CreationMethod](ue_ue.NavRelevantComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### FailsafeExtent

• **FailsafeExtent**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:53373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53373)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[OnComponentActivated](ue_ue.NavRelevantComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[OnComponentDeactivated](ue_ue.NavRelevantComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[PrimaryComponentTick](ue_ue.NavRelevantComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[UCSModifiedProperties](ue_ue.NavRelevantComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[__tid_ActorComponent__](ue_ue.NavRelevantComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_NavModifierComponent\_\_

• **\_\_tid\_NavModifierComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:53380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53380)

___

### \_\_tid\_NavRelevantComponent\_\_

• **\_\_tid\_NavRelevantComponent\_\_**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[__tid_NavRelevantComponent__](ue_ue.NavRelevantComponent.md#__tid_navrelevantcomponent__)

#### Defined in

[ue/ue.d.ts:53249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53249)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[__tid_Object__](ue_ue.NavRelevantComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAttachToOwnersRoot

• **bAttachToOwnersRoot**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bAttachToOwnersRoot](ue_ue.NavRelevantComponent.md#battachtoownersroot)

#### Defined in

[ue/ue.d.ts:53242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53242)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bAutoActivate](ue_ue.NavRelevantComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bCanEverAffectNavigation](ue_ue.NavRelevantComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bCreatedByConstructionScript](ue_ue.NavRelevantComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bEditableWhenInherited](ue_ue.NavRelevantComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bIncludeAgentHeight

• **bIncludeAgentHeight**: `boolean`

#### Defined in

[ue/ue.d.ts:53374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53374)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bInstanceComponent](ue_ue.NavRelevantComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bIsActive](ue_ue.NavRelevantComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bIsEditorOnly](ue_ue.NavRelevantComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bIsVisualizationComponent](ue_ue.NavRelevantComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bNetAddressable](ue_ue.NavRelevantComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[bReplicates](ue_ue.NavRelevantComponent.md#breplicates)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Activate](ue_ue.NavRelevantComponent.md#activate)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[AddTickPrerequisiteActor](ue_ue.NavRelevantComponent.md#addtickprerequisiteactor)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[AddTickPrerequisiteComponent](ue_ue.NavRelevantComponent.md#addtickprerequisitecomponent)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ComponentHasTag](ue_ue.NavRelevantComponent.md#componenthastag)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[CreateDefaultSubobject](ue_ue.NavRelevantComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Deactivate](ue_ue.NavRelevantComponent.md#deactivate)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ExecuteUbergraph](ue_ue.NavRelevantComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetClass](ue_ue.NavRelevantComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetComponentTickInterval](ue_ue.NavRelevantComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetName](ue_ue.NavRelevantComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetOuter](ue_ue.NavRelevantComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetOwner](ue_ue.NavRelevantComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[GetWorld](ue_ue.NavRelevantComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[IsActive](ue_ue.NavRelevantComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[IsBeingDestroyed](ue_ue.NavRelevantComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[IsComponentTickEnabled](ue_ue.NavRelevantComponent.md#iscomponenttickenabled)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[K2_DestroyComponent](ue_ue.NavRelevantComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[OnRep_IsActive](ue_ue.NavRelevantComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ReceiveBeginPlay](ue_ue.NavRelevantComponent.md#receivebeginplay)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ReceiveEndPlay](ue_ue.NavRelevantComponent.md#receiveendplay)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ReceiveTick](ue_ue.NavRelevantComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[RegisterComponent](ue_ue.NavRelevantComponent.md#registercomponent)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[RemoveTickPrerequisiteActor](ue_ue.NavRelevantComponent.md#removetickprerequisiteactor)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.NavRelevantComponent.md#removetickprerequisitecomponent)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetActive](ue_ue.NavRelevantComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

___

### SetAreaClass

▸ **SetAreaClass**(`NewAreaClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAreaClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53375)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetAutoActivate](ue_ue.NavRelevantComponent.md#setautoactivate)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetComponentTickEnabled](ue_ue.NavRelevantComponent.md#setcomponenttickenabled)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetComponentTickInterval](ue_ue.NavRelevantComponent.md#setcomponenttickinterval)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetIsReplicated](ue_ue.NavRelevantComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

___

### SetNavigationRelevancy

▸ **SetNavigationRelevancy**(`bRelevant`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bRelevant` | `boolean` |

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetNavigationRelevancy](ue_ue.NavRelevantComponent.md#setnavigationrelevancy)

#### Defined in

[ue/ue.d.ts:53244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53244)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetTickGroup](ue_ue.NavRelevantComponent.md#settickgroup)

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

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[SetTickableWhenPaused](ue_ue.NavRelevantComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[ToggleActive](ue_ue.NavRelevantComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Find](ue_ue.NavRelevantComponent.md#find)

#### Defined in

[ue/ue.d.ts:53377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53377)

___

### Load

▸ `Static` **Load**(`InName`): [`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavModifierComponent`](ue_ue.NavModifierComponent.md)

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[Load](ue_ue.NavRelevantComponent.md#load)

#### Defined in

[ue/ue.d.ts:53378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53378)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavRelevantComponent](ue_ue.NavRelevantComponent.md).[StaticClass](ue_ue.NavRelevantComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:53376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53376)
