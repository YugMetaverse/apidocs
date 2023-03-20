[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LuminApplicationLifecycleComponent

# Class: LuminApplicationLifecycleComponent

[ue/ue](../modules/ue_ue.md).LuminApplicationLifecycleComponent

## Hierarchy

- [`ApplicationLifecycleComponent`](ue_ue.ApplicationLifecycleComponent.md)

  ↳ **`LuminApplicationLifecycleComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.LuminApplicationLifecycleComponent.md#constructor)

### Properties

- [ApplicationHasEnteredForegroundDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationhasenteredforegrounddelegate)
- [ApplicationHasReactivatedDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationhasreactivateddelegate)
- [ApplicationReceivedStartupArgumentsDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationreceivedstartupargumentsdelegate)
- [ApplicationShouldUnloadResourcesDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationshouldunloadresourcesdelegate)
- [ApplicationWillDeactivateDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationwilldeactivatedelegate)
- [ApplicationWillEnterBackgroundDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationwillenterbackgrounddelegate)
- [ApplicationWillTerminateDelegate](ue_ue.LuminApplicationLifecycleComponent.md#applicationwillterminatedelegate)
- [AssetUserData](ue_ue.LuminApplicationLifecycleComponent.md#assetuserdata)
- [ComponentTags](ue_ue.LuminApplicationLifecycleComponent.md#componenttags)
- [CreationMethod](ue_ue.LuminApplicationLifecycleComponent.md#creationmethod)
- [DeviceHasReactivatedDelegate](ue_ue.LuminApplicationLifecycleComponent.md#devicehasreactivateddelegate)
- [DeviceWillEnterRealityModeDelegate](ue_ue.LuminApplicationLifecycleComponent.md#devicewillenterrealitymodedelegate)
- [DeviceWillGoInStandbyDelegate](ue_ue.LuminApplicationLifecycleComponent.md#devicewillgoinstandbydelegate)
- [OnComponentActivated](ue_ue.LuminApplicationLifecycleComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.LuminApplicationLifecycleComponent.md#oncomponentdeactivated)
- [OnLowPowerModeDelegate](ue_ue.LuminApplicationLifecycleComponent.md#onlowpowermodedelegate)
- [OnTemperatureChangeDelegate](ue_ue.LuminApplicationLifecycleComponent.md#ontemperaturechangedelegate)
- [PrimaryComponentTick](ue_ue.LuminApplicationLifecycleComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.LuminApplicationLifecycleComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.LuminApplicationLifecycleComponent.md#__tid_actorcomponent__)
- [\_\_tid\_ApplicationLifecycleComponent\_\_](ue_ue.LuminApplicationLifecycleComponent.md#__tid_applicationlifecyclecomponent__)
- [\_\_tid\_LuminApplicationLifecycleComponent\_\_](ue_ue.LuminApplicationLifecycleComponent.md#__tid_luminapplicationlifecyclecomponent__)
- [\_\_tid\_Object\_\_](ue_ue.LuminApplicationLifecycleComponent.md#__tid_object__)
- [bAutoActivate](ue_ue.LuminApplicationLifecycleComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.LuminApplicationLifecycleComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.LuminApplicationLifecycleComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.LuminApplicationLifecycleComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.LuminApplicationLifecycleComponent.md#binstancecomponent)
- [bIsActive](ue_ue.LuminApplicationLifecycleComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.LuminApplicationLifecycleComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.LuminApplicationLifecycleComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.LuminApplicationLifecycleComponent.md#bnetaddressable)
- [bReplicates](ue_ue.LuminApplicationLifecycleComponent.md#breplicates)

### Methods

- [Activate](ue_ue.LuminApplicationLifecycleComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.LuminApplicationLifecycleComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.LuminApplicationLifecycleComponent.md#addtickprerequisitecomponent)
- [ApplicationLifetimeDelegate\_\_DelegateSignature](ue_ue.LuminApplicationLifecycleComponent.md#applicationlifetimedelegate__delegatesignature)
- [ApplicationStartupArgumentsDelegate\_\_DelegateSignature](ue_ue.LuminApplicationLifecycleComponent.md#applicationstartupargumentsdelegate__delegatesignature)
- [ComponentHasTag](ue_ue.LuminApplicationLifecycleComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.LuminApplicationLifecycleComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.LuminApplicationLifecycleComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.LuminApplicationLifecycleComponent.md#executeubergraph)
- [GetClass](ue_ue.LuminApplicationLifecycleComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.LuminApplicationLifecycleComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.LuminApplicationLifecycleComponent.md#getname)
- [GetOuter](ue_ue.LuminApplicationLifecycleComponent.md#getouter)
- [GetOwner](ue_ue.LuminApplicationLifecycleComponent.md#getowner)
- [GetWorld](ue_ue.LuminApplicationLifecycleComponent.md#getworld)
- [IsActive](ue_ue.LuminApplicationLifecycleComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.LuminApplicationLifecycleComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.LuminApplicationLifecycleComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.LuminApplicationLifecycleComponent.md#k2_destroycomponent)
- [LuminApplicationLifetimeDelegate\_\_DelegateSignature](ue_ue.LuminApplicationLifecycleComponent.md#luminapplicationlifetimedelegate__delegatesignature)
- [OnLowPowerModeDelegate\_\_DelegateSignature](ue_ue.LuminApplicationLifecycleComponent.md#onlowpowermodedelegate__delegatesignature)
- [OnRep\_IsActive](ue_ue.LuminApplicationLifecycleComponent.md#onrep_isactive)
- [OnTemperatureChangeDelegate\_\_DelegateSignature](ue_ue.LuminApplicationLifecycleComponent.md#ontemperaturechangedelegate__delegatesignature)
- [ReceiveBeginPlay](ue_ue.LuminApplicationLifecycleComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.LuminApplicationLifecycleComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.LuminApplicationLifecycleComponent.md#receivetick)
- [RegisterComponent](ue_ue.LuminApplicationLifecycleComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.LuminApplicationLifecycleComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.LuminApplicationLifecycleComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.LuminApplicationLifecycleComponent.md#setactive)
- [SetAutoActivate](ue_ue.LuminApplicationLifecycleComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.LuminApplicationLifecycleComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.LuminApplicationLifecycleComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.LuminApplicationLifecycleComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.LuminApplicationLifecycleComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.LuminApplicationLifecycleComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.LuminApplicationLifecycleComponent.md#toggleactive)
- [Find](ue_ue.LuminApplicationLifecycleComponent.md#find)
- [Load](ue_ue.LuminApplicationLifecycleComponent.md#load)
- [StaticClass](ue_ue.LuminApplicationLifecycleComponent.md#staticclass)

## Constructors

### constructor

• **new LuminApplicationLifecycleComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[constructor](ue_ue.ApplicationLifecycleComponent.md#constructor)

## Properties

### ApplicationHasEnteredForegroundDelegate

• **ApplicationHasEnteredForegroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationHasEnteredForegroundDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationhasenteredforegrounddelegate)

___

### ApplicationHasReactivatedDelegate

• **ApplicationHasReactivatedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationHasReactivatedDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationhasreactivateddelegate)

___

### ApplicationReceivedStartupArgumentsDelegate

• **ApplicationReceivedStartupArgumentsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`StartupArguments`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationReceivedStartupArgumentsDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationreceivedstartupargumentsdelegate)

___

### ApplicationShouldUnloadResourcesDelegate

• **ApplicationShouldUnloadResourcesDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationShouldUnloadResourcesDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationshouldunloadresourcesdelegate)

___

### ApplicationWillDeactivateDelegate

• **ApplicationWillDeactivateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationWillDeactivateDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationwilldeactivatedelegate)

___

### ApplicationWillEnterBackgroundDelegate

• **ApplicationWillEnterBackgroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationWillEnterBackgroundDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationwillenterbackgrounddelegate)

___

### ApplicationWillTerminateDelegate

• **ApplicationWillTerminateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationWillTerminateDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationwillterminatedelegate)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[AssetUserData](ue_ue.ApplicationLifecycleComponent.md#assetuserdata)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ComponentTags](ue_ue.ApplicationLifecycleComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[CreationMethod](ue_ue.ApplicationLifecycleComponent.md#creationmethod)

___

### DeviceHasReactivatedDelegate

• **DeviceHasReactivatedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### DeviceWillEnterRealityModeDelegate

• **DeviceWillEnterRealityModeDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### DeviceWillGoInStandbyDelegate

• **DeviceWillGoInStandbyDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnComponentActivated](ue_ue.ApplicationLifecycleComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnComponentDeactivated](ue_ue.ApplicationLifecycleComponent.md#oncomponentdeactivated)

___

### OnLowPowerModeDelegate

• **OnLowPowerModeDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`bInLowPowerMode`: `boolean`) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnLowPowerModeDelegate](ue_ue.ApplicationLifecycleComponent.md#onlowpowermodedelegate)

___

### OnTemperatureChangeDelegate

• **OnTemperatureChangeDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Severity`: [`ETemperatureSeverityType`](../enums/ue_ue.ETemperatureSeverityType.md)) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnTemperatureChangeDelegate](ue_ue.ApplicationLifecycleComponent.md#ontemperaturechangedelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[PrimaryComponentTick](ue_ue.ApplicationLifecycleComponent.md#primarycomponenttick)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[UCSModifiedProperties](ue_ue.ApplicationLifecycleComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[__tid_ActorComponent__](ue_ue.ApplicationLifecycleComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_ApplicationLifecycleComponent\_\_

• **\_\_tid\_ApplicationLifecycleComponent\_\_**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[__tid_ApplicationLifecycleComponent__](ue_ue.ApplicationLifecycleComponent.md#__tid_applicationlifecyclecomponent__)

___

### \_\_tid\_LuminApplicationLifecycleComponent\_\_

• **\_\_tid\_LuminApplicationLifecycleComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[__tid_Object__](ue_ue.ApplicationLifecycleComponent.md#__tid_object__)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bAutoActivate](ue_ue.ApplicationLifecycleComponent.md#bautoactivate)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bCanEverAffectNavigation](ue_ue.ApplicationLifecycleComponent.md#bcaneveraffectnavigation)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bCreatedByConstructionScript](ue_ue.ApplicationLifecycleComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bEditableWhenInherited](ue_ue.ApplicationLifecycleComponent.md#beditablewheninherited)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bInstanceComponent](ue_ue.ApplicationLifecycleComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bIsActive](ue_ue.ApplicationLifecycleComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bIsEditorOnly](ue_ue.ApplicationLifecycleComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bIsVisualizationComponent](ue_ue.ApplicationLifecycleComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bNetAddressable](ue_ue.ApplicationLifecycleComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bReplicates](ue_ue.ApplicationLifecycleComponent.md#breplicates)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[Activate](ue_ue.ApplicationLifecycleComponent.md#activate)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[AddTickPrerequisiteActor](ue_ue.ApplicationLifecycleComponent.md#addtickprerequisiteactor)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[AddTickPrerequisiteComponent](ue_ue.ApplicationLifecycleComponent.md#addtickprerequisitecomponent)

___

### ApplicationLifetimeDelegate\_\_DelegateSignature

▸ **ApplicationLifetimeDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationLifetimeDelegate__DelegateSignature](ue_ue.ApplicationLifecycleComponent.md#applicationlifetimedelegate__delegatesignature)

___

### ApplicationStartupArgumentsDelegate\_\_DelegateSignature

▸ **ApplicationStartupArgumentsDelegate__DelegateSignature**(`StartupArguments`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartupArguments` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationStartupArgumentsDelegate__DelegateSignature](ue_ue.ApplicationLifecycleComponent.md#applicationstartupargumentsdelegate__delegatesignature)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ComponentHasTag](ue_ue.ApplicationLifecycleComponent.md#componenthastag)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[CreateDefaultSubobject](ue_ue.ApplicationLifecycleComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[Deactivate](ue_ue.ApplicationLifecycleComponent.md#deactivate)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ExecuteUbergraph](ue_ue.ApplicationLifecycleComponent.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetClass](ue_ue.ApplicationLifecycleComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetComponentTickInterval](ue_ue.ApplicationLifecycleComponent.md#getcomponenttickinterval)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetName](ue_ue.ApplicationLifecycleComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetOuter](ue_ue.ApplicationLifecycleComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetOwner](ue_ue.ApplicationLifecycleComponent.md#getowner)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetWorld](ue_ue.ApplicationLifecycleComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[IsActive](ue_ue.ApplicationLifecycleComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[IsBeingDestroyed](ue_ue.ApplicationLifecycleComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[IsComponentTickEnabled](ue_ue.ApplicationLifecycleComponent.md#iscomponenttickenabled)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[K2_DestroyComponent](ue_ue.ApplicationLifecycleComponent.md#k2_destroycomponent)

___

### LuminApplicationLifetimeDelegate\_\_DelegateSignature

▸ **LuminApplicationLifetimeDelegate__DelegateSignature**(): `void`

#### Returns

`void`

___

### OnLowPowerModeDelegate\_\_DelegateSignature

▸ **OnLowPowerModeDelegate__DelegateSignature**(`bInLowPowerMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInLowPowerMode` | `boolean` |

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnLowPowerModeDelegate__DelegateSignature](ue_ue.ApplicationLifecycleComponent.md#onlowpowermodedelegate__delegatesignature)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnRep_IsActive](ue_ue.ApplicationLifecycleComponent.md#onrep_isactive)

___

### OnTemperatureChangeDelegate\_\_DelegateSignature

▸ **OnTemperatureChangeDelegate__DelegateSignature**(`Severity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Severity` | [`ETemperatureSeverityType`](../enums/ue_ue.ETemperatureSeverityType.md) |

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnTemperatureChangeDelegate__DelegateSignature](ue_ue.ApplicationLifecycleComponent.md#ontemperaturechangedelegate__delegatesignature)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ReceiveBeginPlay](ue_ue.ApplicationLifecycleComponent.md#receivebeginplay)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ReceiveEndPlay](ue_ue.ApplicationLifecycleComponent.md#receiveendplay)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ReceiveTick](ue_ue.ApplicationLifecycleComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[RegisterComponent](ue_ue.ApplicationLifecycleComponent.md#registercomponent)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ApplicationLifecycleComponent.md#removetickprerequisiteactor)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ApplicationLifecycleComponent.md#removetickprerequisitecomponent)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetActive](ue_ue.ApplicationLifecycleComponent.md#setactive)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetAutoActivate](ue_ue.ApplicationLifecycleComponent.md#setautoactivate)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetComponentTickEnabled](ue_ue.ApplicationLifecycleComponent.md#setcomponenttickenabled)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetComponentTickInterval](ue_ue.ApplicationLifecycleComponent.md#setcomponenttickinterval)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetIsReplicated](ue_ue.ApplicationLifecycleComponent.md#setisreplicated)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetTickGroup](ue_ue.ApplicationLifecycleComponent.md#settickgroup)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetTickableWhenPaused](ue_ue.ApplicationLifecycleComponent.md#settickablewhenpaused)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ToggleActive](ue_ue.ApplicationLifecycleComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LuminApplicationLifecycleComponent`](ue_ue.LuminApplicationLifecycleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LuminApplicationLifecycleComponent`](ue_ue.LuminApplicationLifecycleComponent.md)

#### Overrides

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[Find](ue_ue.ApplicationLifecycleComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LuminApplicationLifecycleComponent`](ue_ue.LuminApplicationLifecycleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LuminApplicationLifecycleComponent`](ue_ue.LuminApplicationLifecycleComponent.md)

#### Overrides

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[Load](ue_ue.ApplicationLifecycleComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[StaticClass](ue_ue.ApplicationLifecycleComponent.md#staticclass)
