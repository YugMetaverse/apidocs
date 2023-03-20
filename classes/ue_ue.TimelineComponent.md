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

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

___

### TheTimeline

• **TheTimeline**: [`Timeline`](ue_ue.Timeline.md)

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

### \_\_tid\_TimelineComponent\_\_

• **\_\_tid\_TimelineComponent\_\_**: `boolean`

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

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

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

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

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

### GetIgnoreTimeDilation

▸ **GetIgnoreTimeDilation**(): `boolean`

#### Returns

`boolean`

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

### GetPlayRate

▸ **GetPlayRate**(): `number`

#### Returns

`number`

___

### GetPlaybackPosition

▸ **GetPlaybackPosition**(): `number`

#### Returns

`number`

___

### GetTimelineLength

▸ **GetTimelineLength**(): `number`

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

### IsLooping

▸ **IsLooping**(): `boolean`

#### Returns

`boolean`

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

___

### IsReversing

▸ **IsReversing**(): `boolean`

#### Returns

`boolean`

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

### OnRep\_Timeline

▸ **OnRep_Timeline**(): `void`

#### Returns

`void`

___

### Play

▸ **Play**(): `void`

#### Returns

`void`

___

### PlayFromStart

▸ **PlayFromStart**(): `void`

#### Returns

`void`

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

### Reverse

▸ **Reverse**(): `void`

#### Returns

`void`

___

### ReverseFromEnd

▸ **ReverseFromEnd**(): `void`

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

### SetFloatCurve

▸ **SetFloatCurve**(`NewFloatCurve`, `FloatTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFloatCurve` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CurveFloat`](ue_ue.CurveFloat.md)\> |
| `FloatTrackName` | `string` |

#### Returns

`void`

___

### SetIgnoreTimeDilation

▸ **SetIgnoreTimeDilation**(`bNewIgnoreTimeDilation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewIgnoreTimeDilation` | `boolean` |

#### Returns

`void`

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

### SetLinearColorCurve

▸ **SetLinearColorCurve**(`NewLinearColorCurve`, `LinearColorTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLinearColorCurve` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CurveLinearColor`](ue_ue.CurveLinearColor.md)\> |
| `LinearColorTrackName` | `string` |

#### Returns

`void`

___

### SetLooping

▸ **SetLooping**(`bNewLooping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewLooping` | `boolean` |

#### Returns

`void`

___

### SetNewTime

▸ **SetNewTime**(`NewTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTime` | `number` |

#### Returns

`void`

___

### SetPlayRate

▸ **SetPlayRate**(`NewRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRate` | `number` |

#### Returns

`void`

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

### SetTimelineLength

▸ **SetTimelineLength**(`NewLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLength` | `number` |

#### Returns

`void`

___

### SetTimelineLengthMode

▸ **SetTimelineLengthMode**(`NewLengthMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLengthMode` | [`ETimelineLengthMode`](../enums/ue_ue.ETimelineLengthMode.md) |

#### Returns

`void`

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

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
