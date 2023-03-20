[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARTrackableNotifyComponent

# Class: ARTrackableNotifyComponent

[ue/ue](../modules/ue_ue.md).ARTrackableNotifyComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`ARTrackableNotifyComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARTrackableNotifyComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.ARTrackableNotifyComponent.md#assetuserdata)
- [ComponentTags](ue_ue.ARTrackableNotifyComponent.md#componenttags)
- [CreationMethod](ue_ue.ARTrackableNotifyComponent.md#creationmethod)
- [OnAddTrackedEnvProbe](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedenvprobe)
- [OnAddTrackedFace](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedface)
- [OnAddTrackedGeometry](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedgeometry)
- [OnAddTrackedImage](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedimage)
- [OnAddTrackedObject](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedobject)
- [OnAddTrackedPlane](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedplane)
- [OnAddTrackedPoint](ue_ue.ARTrackableNotifyComponent.md#onaddtrackedpoint)
- [OnComponentActivated](ue_ue.ARTrackableNotifyComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.ARTrackableNotifyComponent.md#oncomponentdeactivated)
- [OnRemoveTrackedEnvProbe](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedenvprobe)
- [OnRemoveTrackedFace](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedface)
- [OnRemoveTrackedGeometry](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedgeometry)
- [OnRemoveTrackedImage](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedimage)
- [OnRemoveTrackedObject](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedobject)
- [OnRemoveTrackedPlane](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedplane)
- [OnRemoveTrackedPoint](ue_ue.ARTrackableNotifyComponent.md#onremovetrackedpoint)
- [OnUpdateTrackedEnvProbe](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedenvprobe)
- [OnUpdateTrackedFace](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedface)
- [OnUpdateTrackedGeometry](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedgeometry)
- [OnUpdateTrackedImage](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedimage)
- [OnUpdateTrackedObject](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedobject)
- [OnUpdateTrackedPlane](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedplane)
- [OnUpdateTrackedPoint](ue_ue.ARTrackableNotifyComponent.md#onupdatetrackedpoint)
- [PrimaryComponentTick](ue_ue.ARTrackableNotifyComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.ARTrackableNotifyComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ARTrackableNotifyComponent\_\_](ue_ue.ARTrackableNotifyComponent.md#__tid_artrackablenotifycomponent__)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ARTrackableNotifyComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.ARTrackableNotifyComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.ARTrackableNotifyComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.ARTrackableNotifyComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.ARTrackableNotifyComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.ARTrackableNotifyComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.ARTrackableNotifyComponent.md#binstancecomponent)
- [bIsActive](ue_ue.ARTrackableNotifyComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.ARTrackableNotifyComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ARTrackableNotifyComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.ARTrackableNotifyComponent.md#bnetaddressable)
- [bReplicates](ue_ue.ARTrackableNotifyComponent.md#breplicates)

### Methods

- [Activate](ue_ue.ARTrackableNotifyComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.ARTrackableNotifyComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ARTrackableNotifyComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.ARTrackableNotifyComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.ARTrackableNotifyComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.ARTrackableNotifyComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.ARTrackableNotifyComponent.md#executeubergraph)
- [GetClass](ue_ue.ARTrackableNotifyComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.ARTrackableNotifyComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.ARTrackableNotifyComponent.md#getname)
- [GetOuter](ue_ue.ARTrackableNotifyComponent.md#getouter)
- [GetOwner](ue_ue.ARTrackableNotifyComponent.md#getowner)
- [GetWorld](ue_ue.ARTrackableNotifyComponent.md#getworld)
- [IsActive](ue_ue.ARTrackableNotifyComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.ARTrackableNotifyComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ARTrackableNotifyComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.ARTrackableNotifyComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.ARTrackableNotifyComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.ARTrackableNotifyComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ARTrackableNotifyComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.ARTrackableNotifyComponent.md#receivetick)
- [RegisterComponent](ue_ue.ARTrackableNotifyComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ARTrackableNotifyComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ARTrackableNotifyComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.ARTrackableNotifyComponent.md#setactive)
- [SetAutoActivate](ue_ue.ARTrackableNotifyComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.ARTrackableNotifyComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ARTrackableNotifyComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.ARTrackableNotifyComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.ARTrackableNotifyComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ARTrackableNotifyComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.ARTrackableNotifyComponent.md#toggleactive)
- [Find](ue_ue.ARTrackableNotifyComponent.md#find)
- [Load](ue_ue.ARTrackableNotifyComponent.md#load)
- [StaticClass](ue_ue.ARTrackableNotifyComponent.md#staticclass)

## Constructors

### constructor

• **new ARTrackableNotifyComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### OnAddTrackedEnvProbe

• **OnAddTrackedEnvProbe**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedEnvProbe`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AREnvironmentCaptureProbe`](ue_ue.AREnvironmentCaptureProbe.md)\>) => `void`\>

___

### OnAddTrackedFace

• **OnAddTrackedFace**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedFace`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)\>) => `void`\>

___

### OnAddTrackedGeometry

• **OnAddTrackedGeometry**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedGeometry`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)\>) => `void`\>

___

### OnAddTrackedImage

• **OnAddTrackedImage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedImage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedImage`](ue_ue.ARTrackedImage.md)\>) => `void`\>

___

### OnAddTrackedObject

• **OnAddTrackedObject**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedObject`](ue_ue.ARTrackedObject.md)\>) => `void`\>

___

### OnAddTrackedPlane

• **OnAddTrackedPlane**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedPlane`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)\>) => `void`\>

___

### OnAddTrackedPoint

• **OnAddTrackedPoint**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedPoint`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedPoint`](ue_ue.ARTrackedPoint.md)\>) => `void`\>

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

### OnRemoveTrackedEnvProbe

• **OnRemoveTrackedEnvProbe**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedEnvProbe`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AREnvironmentCaptureProbe`](ue_ue.AREnvironmentCaptureProbe.md)\>) => `void`\>

___

### OnRemoveTrackedFace

• **OnRemoveTrackedFace**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedFace`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)\>) => `void`\>

___

### OnRemoveTrackedGeometry

• **OnRemoveTrackedGeometry**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedGeometry`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)\>) => `void`\>

___

### OnRemoveTrackedImage

• **OnRemoveTrackedImage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedImage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedImage`](ue_ue.ARTrackedImage.md)\>) => `void`\>

___

### OnRemoveTrackedObject

• **OnRemoveTrackedObject**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedObject`](ue_ue.ARTrackedObject.md)\>) => `void`\>

___

### OnRemoveTrackedPlane

• **OnRemoveTrackedPlane**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedPlane`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)\>) => `void`\>

___

### OnRemoveTrackedPoint

• **OnRemoveTrackedPoint**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedPoint`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedPoint`](ue_ue.ARTrackedPoint.md)\>) => `void`\>

___

### OnUpdateTrackedEnvProbe

• **OnUpdateTrackedEnvProbe**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedEnvProbe`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AREnvironmentCaptureProbe`](ue_ue.AREnvironmentCaptureProbe.md)\>) => `void`\>

___

### OnUpdateTrackedFace

• **OnUpdateTrackedFace**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedFace`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARFaceGeometry`](ue_ue.ARFaceGeometry.md)\>) => `void`\>

___

### OnUpdateTrackedGeometry

• **OnUpdateTrackedGeometry**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedGeometry`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)\>) => `void`\>

___

### OnUpdateTrackedImage

• **OnUpdateTrackedImage**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedImage`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedImage`](ue_ue.ARTrackedImage.md)\>) => `void`\>

___

### OnUpdateTrackedObject

• **OnUpdateTrackedObject**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedObject`](ue_ue.ARTrackedObject.md)\>) => `void`\>

___

### OnUpdateTrackedPlane

• **OnUpdateTrackedPlane**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedPlane`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)\>) => `void`\>

___

### OnUpdateTrackedPoint

• **OnUpdateTrackedPoint**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`TrackedPoint`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedPoint`](ue_ue.ARTrackedPoint.md)\>) => `void`\>

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ARTrackableNotifyComponent\_\_

• **\_\_tid\_ARTrackableNotifyComponent\_\_**: `boolean`

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

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARTrackableNotifyComponent`](ue_ue.ARTrackableNotifyComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARTrackableNotifyComponent`](ue_ue.ARTrackableNotifyComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARTrackableNotifyComponent`](ue_ue.ARTrackableNotifyComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARTrackableNotifyComponent`](ue_ue.ARTrackableNotifyComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)
