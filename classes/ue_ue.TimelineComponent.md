[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimelineComponent

# Class: TimelineComponent

[ue/ue](../modules/ue_ue.md).TimelineComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`TimelineComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.TimelineComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.TimelineComponent.md#assetuserdata)
- [ComponentTags](ue_ue.TimelineComponent.md#componenttags)
- [CreationMethod](ue_ue.TimelineComponent.md#creationmethod)
- [OnComponentActivated](ue_ue.TimelineComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.TimelineComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.TimelineComponent.md#primarycomponenttick)
- [TheTimeline](ue_ue.TimelineComponent.md#thetimeline)
- [UCSModifiedProperties](ue_ue.TimelineComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.TimelineComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.TimelineComponent.md#__tid_object__)
- [\_\_tid\_TimelineComponent\_\_](ue_ue.TimelineComponent.md#__tid_timelinecomponent__)
- [bAutoActivate](ue_ue.TimelineComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.TimelineComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.TimelineComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.TimelineComponent.md#beditablewheninherited)
- [bIgnoreTimeDilation](ue_ue.TimelineComponent.md#bignoretimedilation)
- [bInstanceComponent](ue_ue.TimelineComponent.md#binstancecomponent)
- [bIsActive](ue_ue.TimelineComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.TimelineComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.TimelineComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.TimelineComponent.md#bnetaddressable)
- [bReplicates](ue_ue.TimelineComponent.md#breplicates)

### Methods

- [Activate](ue_ue.TimelineComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.TimelineComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.TimelineComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.TimelineComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.TimelineComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.TimelineComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.TimelineComponent.md#executeubergraph)
- [GetClass](ue_ue.TimelineComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.TimelineComponent.md#getcomponenttickinterval)
- [GetIgnoreTimeDilation](ue_ue.TimelineComponent.md#getignoretimedilation)
- [GetName](ue_ue.TimelineComponent.md#getname)
- [GetOuter](ue_ue.TimelineComponent.md#getouter)
- [GetOwner](ue_ue.TimelineComponent.md#getowner)
- [GetPlayRate](ue_ue.TimelineComponent.md#getplayrate)
- [GetPlaybackPosition](ue_ue.TimelineComponent.md#getplaybackposition)
- [GetTimelineLength](ue_ue.TimelineComponent.md#gettimelinelength)
- [GetWorld](ue_ue.TimelineComponent.md#getworld)
- [IsActive](ue_ue.TimelineComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.TimelineComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.TimelineComponent.md#iscomponenttickenabled)
- [IsLooping](ue_ue.TimelineComponent.md#islooping)
- [IsPlaying](ue_ue.TimelineComponent.md#isplaying)
- [IsReversing](ue_ue.TimelineComponent.md#isreversing)
- [K2\_DestroyComponent](ue_ue.TimelineComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.TimelineComponent.md#onrep_isactive)
- [OnRep\_Timeline](ue_ue.TimelineComponent.md#onrep_timeline)
- [Play](ue_ue.TimelineComponent.md#play)
- [PlayFromStart](ue_ue.TimelineComponent.md#playfromstart)
- [ReceiveBeginPlay](ue_ue.TimelineComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.TimelineComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.TimelineComponent.md#receivetick)
- [RegisterComponent](ue_ue.TimelineComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.TimelineComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.TimelineComponent.md#removetickprerequisitecomponent)
- [Reverse](ue_ue.TimelineComponent.md#reverse)
- [ReverseFromEnd](ue_ue.TimelineComponent.md#reversefromend)
- [SetActive](ue_ue.TimelineComponent.md#setactive)
- [SetAutoActivate](ue_ue.TimelineComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.TimelineComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.TimelineComponent.md#setcomponenttickinterval)
- [SetFloatCurve](ue_ue.TimelineComponent.md#setfloatcurve)
- [SetIgnoreTimeDilation](ue_ue.TimelineComponent.md#setignoretimedilation)
- [SetIsReplicated](ue_ue.TimelineComponent.md#setisreplicated)
- [SetLinearColorCurve](ue_ue.TimelineComponent.md#setlinearcolorcurve)
- [SetLooping](ue_ue.TimelineComponent.md#setlooping)
- [SetNewTime](ue_ue.TimelineComponent.md#setnewtime)
- [SetPlayRate](ue_ue.TimelineComponent.md#setplayrate)
- [SetPlaybackPosition](ue_ue.TimelineComponent.md#setplaybackposition)
- [SetTickGroup](ue_ue.TimelineComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.TimelineComponent.md#settickablewhenpaused)
- [SetTimelineLength](ue_ue.TimelineComponent.md#settimelinelength)
- [SetTimelineLengthMode](ue_ue.TimelineComponent.md#settimelinelengthmode)
- [SetVectorCurve](ue_ue.TimelineComponent.md#setvectorcurve)
- [Stop](ue_ue.TimelineComponent.md#stop)
- [ToggleActive](ue_ue.TimelineComponent.md#toggleactive)
- [Find](ue_ue.TimelineComponent.md#find)
- [Load](ue_ue.TimelineComponent.md#load)
- [StaticClass](ue_ue.TimelineComponent.md#staticclass)

## Constructors

### constructor

• **new TimelineComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:63628](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63628)

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

### TheTimeline

• **TheTimeline**: [`Timeline`](ue_ue.Timeline.md)

#### Defined in

[ue/ue.d.ts:63629](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63629)

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

### \_\_tid\_TimelineComponent\_\_

• **\_\_tid\_TimelineComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63658)

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

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

#### Defined in

[ue/ue.d.ts:63630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63630)

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

### GetIgnoreTimeDilation

▸ **GetIgnoreTimeDilation**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:63631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63631)

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

### GetPlayRate

▸ **GetPlayRate**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:63633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63633)

___

### GetPlaybackPosition

▸ **GetPlaybackPosition**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:63632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63632)

___

### GetTimelineLength

▸ **GetTimelineLength**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:63634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63634)

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

### IsLooping

▸ **IsLooping**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:63635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63635)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:63636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63636)

___

### IsReversing

▸ **IsReversing**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:63637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63637)

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

### OnRep\_Timeline

▸ **OnRep_Timeline**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63638)

___

### Play

▸ **Play**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63639)

___

### PlayFromStart

▸ **PlayFromStart**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63640)

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

### Reverse

▸ **Reverse**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63641)

___

### ReverseFromEnd

▸ **ReverseFromEnd**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63642)

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

### SetFloatCurve

▸ **SetFloatCurve**(`NewFloatCurve`, `FloatTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFloatCurve` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CurveFloat`](ue_ue.CurveFloat.md)\> |
| `FloatTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63643)

___

### SetIgnoreTimeDilation

▸ **SetIgnoreTimeDilation**(`bNewIgnoreTimeDilation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewIgnoreTimeDilation` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63644)

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

### SetLinearColorCurve

▸ **SetLinearColorCurve**(`NewLinearColorCurve`, `LinearColorTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLinearColorCurve` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CurveLinearColor`](ue_ue.CurveLinearColor.md)\> |
| `LinearColorTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63645)

___

### SetLooping

▸ **SetLooping**(`bNewLooping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewLooping` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63646)

___

### SetNewTime

▸ **SetNewTime**(`NewTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTime` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63647)

___

### SetPlayRate

▸ **SetPlayRate**(`NewRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRate` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63649)

___

### SetPlaybackPosition

▸ **SetPlaybackPosition**(`NewPosition`, `bFireEvents`, `bFireUpdate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPosition` | `number` |
| `bFireEvents` | `boolean` |
| `bFireUpdate?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63648)

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

### SetTimelineLength

▸ **SetTimelineLength**(`NewLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLength` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63650)

___

### SetTimelineLengthMode

▸ **SetTimelineLengthMode**(`NewLengthMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLengthMode` | [`ETimelineLengthMode`](../enums/ue_ue.ETimelineLengthMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63651)

___

### SetVectorCurve

▸ **SetVectorCurve**(`NewVectorCurve`, `VectorTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVectorCurve` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CurveVector`](ue_ue.CurveVector.md)\> |
| `VectorTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63652)

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63653)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TimelineComponent`](ue_ue.TimelineComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TimelineComponent`](ue_ue.TimelineComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

#### Defined in

[ue/ue.d.ts:63655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63655)

___

### Load

▸ `Static` **Load**(`InName`): [`TimelineComponent`](ue_ue.TimelineComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TimelineComponent`](ue_ue.TimelineComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

#### Defined in

[ue/ue.d.ts:63656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63656)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:63654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63654)
