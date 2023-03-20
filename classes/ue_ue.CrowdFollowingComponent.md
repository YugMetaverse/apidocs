[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CrowdFollowingComponent

# Class: CrowdFollowingComponent

[ue/ue](../modules/ue_ue.md).CrowdFollowingComponent

## Hierarchy

- [`PathFollowingComponent`](ue_ue.PathFollowingComponent.md)

  ↳ **`CrowdFollowingComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.CrowdFollowingComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.CrowdFollowingComponent.md#assetuserdata)
- [AvoidanceGroup](ue_ue.CrowdFollowingComponent.md#avoidancegroup)
- [CharacterMovement](ue_ue.CrowdFollowingComponent.md#charactermovement)
- [ComponentTags](ue_ue.CrowdFollowingComponent.md#componenttags)
- [CreationMethod](ue_ue.CrowdFollowingComponent.md#creationmethod)
- [CrowdAgentMoveDirection](ue_ue.CrowdFollowingComponent.md#crowdagentmovedirection)
- [GroupsToAvoid](ue_ue.CrowdFollowingComponent.md#groupstoavoid)
- [GroupsToIgnore](ue_ue.CrowdFollowingComponent.md#groupstoignore)
- [MovementComp](ue_ue.CrowdFollowingComponent.md#movementcomp)
- [MyNavData](ue_ue.CrowdFollowingComponent.md#mynavdata)
- [OnComponentActivated](ue_ue.CrowdFollowingComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.CrowdFollowingComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.CrowdFollowingComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.CrowdFollowingComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CrowdFollowingComponent.md#__tid_actorcomponent__)
- [\_\_tid\_CrowdFollowingComponent\_\_](ue_ue.CrowdFollowingComponent.md#__tid_crowdfollowingcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.CrowdFollowingComponent.md#__tid_object__)
- [\_\_tid\_PathFollowingComponent\_\_](ue_ue.CrowdFollowingComponent.md#__tid_pathfollowingcomponent__)
- [bAutoActivate](ue_ue.CrowdFollowingComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.CrowdFollowingComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.CrowdFollowingComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.CrowdFollowingComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.CrowdFollowingComponent.md#binstancecomponent)
- [bIsActive](ue_ue.CrowdFollowingComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.CrowdFollowingComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CrowdFollowingComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.CrowdFollowingComponent.md#bnetaddressable)
- [bReplicates](ue_ue.CrowdFollowingComponent.md#breplicates)

### Methods

- [Activate](ue_ue.CrowdFollowingComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.CrowdFollowingComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CrowdFollowingComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.CrowdFollowingComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.CrowdFollowingComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.CrowdFollowingComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.CrowdFollowingComponent.md#executeubergraph)
- [GetClass](ue_ue.CrowdFollowingComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.CrowdFollowingComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.CrowdFollowingComponent.md#getname)
- [GetOuter](ue_ue.CrowdFollowingComponent.md#getouter)
- [GetOwner](ue_ue.CrowdFollowingComponent.md#getowner)
- [GetPathActionType](ue_ue.CrowdFollowingComponent.md#getpathactiontype)
- [GetPathDestination](ue_ue.CrowdFollowingComponent.md#getpathdestination)
- [GetWorld](ue_ue.CrowdFollowingComponent.md#getworld)
- [IsActive](ue_ue.CrowdFollowingComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.CrowdFollowingComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CrowdFollowingComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.CrowdFollowingComponent.md#k2_destroycomponent)
- [OnActorBump](ue_ue.CrowdFollowingComponent.md#onactorbump)
- [OnNavDataRegistered](ue_ue.CrowdFollowingComponent.md#onnavdataregistered)
- [OnRep\_IsActive](ue_ue.CrowdFollowingComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.CrowdFollowingComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CrowdFollowingComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.CrowdFollowingComponent.md#receivetick)
- [RegisterComponent](ue_ue.CrowdFollowingComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.CrowdFollowingComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CrowdFollowingComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.CrowdFollowingComponent.md#setactive)
- [SetAutoActivate](ue_ue.CrowdFollowingComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.CrowdFollowingComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CrowdFollowingComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.CrowdFollowingComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.CrowdFollowingComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CrowdFollowingComponent.md#settickablewhenpaused)
- [SuspendCrowdSteering](ue_ue.CrowdFollowingComponent.md#suspendcrowdsteering)
- [ToggleActive](ue_ue.CrowdFollowingComponent.md#toggleactive)
- [Find](ue_ue.CrowdFollowingComponent.md#find)
- [Load](ue_ue.CrowdFollowingComponent.md#load)
- [StaticClass](ue_ue.CrowdFollowingComponent.md#staticclass)

## Constructors

### constructor

• **new CrowdFollowingComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[constructor](ue_ue.PathFollowingComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:28848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28848)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[AssetUserData](ue_ue.PathFollowingComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:28851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28851)

___

### CharacterMovement

• **CharacterMovement**: [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Defined in

[ue/ue.d.ts:28849](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28849)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ComponentTags](ue_ue.PathFollowingComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[CreationMethod](ue_ue.PathFollowingComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### CrowdAgentMoveDirection

• **CrowdAgentMoveDirection**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:28850](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28850)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:28852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28852)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:28853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28853)

___

### MovementComp

• **MovementComp**: [`NavMovementComponent`](ue_ue.NavMovementComponent.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[MovementComp](ue_ue.PathFollowingComponent.md#movementcomp)

#### Defined in

[ue/ue.d.ts:14740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14740)

___

### MyNavData

• **MyNavData**: [`NavigationData`](ue_ue.NavigationData.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[MyNavData](ue_ue.PathFollowingComponent.md#mynavdata)

#### Defined in

[ue/ue.d.ts:14741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14741)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnComponentActivated](ue_ue.PathFollowingComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnComponentDeactivated](ue_ue.PathFollowingComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[PrimaryComponentTick](ue_ue.PathFollowingComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[UCSModifiedProperties](ue_ue.PathFollowingComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[__tid_ActorComponent__](ue_ue.PathFollowingComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_CrowdFollowingComponent\_\_

• **\_\_tid\_CrowdFollowingComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28859)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[__tid_Object__](ue_ue.PathFollowingComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PathFollowingComponent\_\_

• **\_\_tid\_PathFollowingComponent\_\_**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[__tid_PathFollowingComponent__](ue_ue.PathFollowingComponent.md#__tid_pathfollowingcomponent__)

#### Defined in

[ue/ue.d.ts:14750](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14750)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bAutoActivate](ue_ue.PathFollowingComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bCanEverAffectNavigation](ue_ue.PathFollowingComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bCreatedByConstructionScript](ue_ue.PathFollowingComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bEditableWhenInherited](ue_ue.PathFollowingComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bInstanceComponent](ue_ue.PathFollowingComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bIsActive](ue_ue.PathFollowingComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bIsEditorOnly](ue_ue.PathFollowingComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bIsVisualizationComponent](ue_ue.PathFollowingComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bNetAddressable](ue_ue.PathFollowingComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[bReplicates](ue_ue.PathFollowingComponent.md#breplicates)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Activate](ue_ue.PathFollowingComponent.md#activate)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[AddTickPrerequisiteActor](ue_ue.PathFollowingComponent.md#addtickprerequisiteactor)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[AddTickPrerequisiteComponent](ue_ue.PathFollowingComponent.md#addtickprerequisitecomponent)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ComponentHasTag](ue_ue.PathFollowingComponent.md#componenthastag)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[CreateDefaultSubobject](ue_ue.PathFollowingComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Deactivate](ue_ue.PathFollowingComponent.md#deactivate)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ExecuteUbergraph](ue_ue.PathFollowingComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetClass](ue_ue.PathFollowingComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetComponentTickInterval](ue_ue.PathFollowingComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetName](ue_ue.PathFollowingComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetOuter](ue_ue.PathFollowingComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetOwner](ue_ue.PathFollowingComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetPathActionType

▸ **GetPathActionType**(): [`EPathFollowingAction`](../enums/ue_ue.EPathFollowingAction.md)

#### Returns

[`EPathFollowingAction`](../enums/ue_ue.EPathFollowingAction.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetPathActionType](ue_ue.PathFollowingComponent.md#getpathactiontype)

#### Defined in

[ue/ue.d.ts:14742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14742)

___

### GetPathDestination

▸ **GetPathDestination**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetPathDestination](ue_ue.PathFollowingComponent.md#getpathdestination)

#### Defined in

[ue/ue.d.ts:14743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14743)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[GetWorld](ue_ue.PathFollowingComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[IsActive](ue_ue.PathFollowingComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[IsBeingDestroyed](ue_ue.PathFollowingComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[IsComponentTickEnabled](ue_ue.PathFollowingComponent.md#iscomponenttickenabled)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[K2_DestroyComponent](ue_ue.PathFollowingComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### OnActorBump

▸ **OnActorBump**(`SelfActor`, `OtherActor`, `NormalImpulse`, `Hit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SelfActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `OtherActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `NormalImpulse` | [`Vector`](ue_ue_s.Vector.md) |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnActorBump](ue_ue.PathFollowingComponent.md#onactorbump)

#### Defined in

[ue/ue.d.ts:14744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14744)

___

### OnNavDataRegistered

▸ **OnNavDataRegistered**(`NavData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NavData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationData`](ue_ue.NavigationData.md)\> |

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnNavDataRegistered](ue_ue.PathFollowingComponent.md#onnavdataregistered)

#### Defined in

[ue/ue.d.ts:14745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14745)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[OnRep_IsActive](ue_ue.PathFollowingComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ReceiveBeginPlay](ue_ue.PathFollowingComponent.md#receivebeginplay)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ReceiveEndPlay](ue_ue.PathFollowingComponent.md#receiveendplay)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ReceiveTick](ue_ue.PathFollowingComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[RegisterComponent](ue_ue.PathFollowingComponent.md#registercomponent)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[RemoveTickPrerequisiteActor](ue_ue.PathFollowingComponent.md#removetickprerequisiteactor)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.PathFollowingComponent.md#removetickprerequisitecomponent)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetActive](ue_ue.PathFollowingComponent.md#setactive)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetAutoActivate](ue_ue.PathFollowingComponent.md#setautoactivate)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetComponentTickEnabled](ue_ue.PathFollowingComponent.md#setcomponenttickenabled)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetComponentTickInterval](ue_ue.PathFollowingComponent.md#setcomponenttickinterval)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetIsReplicated](ue_ue.PathFollowingComponent.md#setisreplicated)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetTickGroup](ue_ue.PathFollowingComponent.md#settickgroup)

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

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[SetTickableWhenPaused](ue_ue.PathFollowingComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### SuspendCrowdSteering

▸ **SuspendCrowdSteering**(`bSuspend`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSuspend` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:28854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28854)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[ToggleActive](ue_ue.PathFollowingComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Find](ue_ue.PathFollowingComponent.md#find)

#### Defined in

[ue/ue.d.ts:28856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28856)

___

### Load

▸ `Static` **Load**(`InName`): [`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CrowdFollowingComponent`](ue_ue.CrowdFollowingComponent.md)

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[Load](ue_ue.PathFollowingComponent.md#load)

#### Defined in

[ue/ue.d.ts:28857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28857)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PathFollowingComponent](ue_ue.PathFollowingComponent.md).[StaticClass](ue_ue.PathFollowingComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:28855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28855)