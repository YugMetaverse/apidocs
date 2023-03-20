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

#### Defined in

[ue/ue.d.ts:46400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46400)

## Properties

### ApplicationHasEnteredForegroundDelegate

• **ApplicationHasEnteredForegroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationHasEnteredForegroundDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationhasenteredforegrounddelegate)

#### Defined in

[ue/ue.d.ts:20648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20648)

___

### ApplicationHasReactivatedDelegate

• **ApplicationHasReactivatedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationHasReactivatedDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationhasreactivateddelegate)

#### Defined in

[ue/ue.d.ts:20646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20646)

___

### ApplicationReceivedStartupArgumentsDelegate

• **ApplicationReceivedStartupArgumentsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`StartupArguments`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationReceivedStartupArgumentsDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationreceivedstartupargumentsdelegate)

#### Defined in

[ue/ue.d.ts:20651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20651)

___

### ApplicationShouldUnloadResourcesDelegate

• **ApplicationShouldUnloadResourcesDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationShouldUnloadResourcesDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationshouldunloadresourcesdelegate)

#### Defined in

[ue/ue.d.ts:20650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20650)

___

### ApplicationWillDeactivateDelegate

• **ApplicationWillDeactivateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationWillDeactivateDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationwilldeactivatedelegate)

#### Defined in

[ue/ue.d.ts:20645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20645)

___

### ApplicationWillEnterBackgroundDelegate

• **ApplicationWillEnterBackgroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationWillEnterBackgroundDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationwillenterbackgrounddelegate)

#### Defined in

[ue/ue.d.ts:20647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20647)

___

### ApplicationWillTerminateDelegate

• **ApplicationWillTerminateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationWillTerminateDelegate](ue_ue.ApplicationLifecycleComponent.md#applicationwillterminatedelegate)

#### Defined in

[ue/ue.d.ts:20649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20649)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[AssetUserData](ue_ue.ApplicationLifecycleComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ComponentTags](ue_ue.ApplicationLifecycleComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[CreationMethod](ue_ue.ApplicationLifecycleComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### DeviceHasReactivatedDelegate

• **DeviceHasReactivatedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:46401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46401)

___

### DeviceWillEnterRealityModeDelegate

• **DeviceWillEnterRealityModeDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:46402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46402)

___

### DeviceWillGoInStandbyDelegate

• **DeviceWillGoInStandbyDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:46403](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46403)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnComponentActivated](ue_ue.ApplicationLifecycleComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnComponentDeactivated](ue_ue.ApplicationLifecycleComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### OnLowPowerModeDelegate

• **OnLowPowerModeDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`bInLowPowerMode`: `boolean`) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnLowPowerModeDelegate](ue_ue.ApplicationLifecycleComponent.md#onlowpowermodedelegate)

#### Defined in

[ue/ue.d.ts:20653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20653)

___

### OnTemperatureChangeDelegate

• **OnTemperatureChangeDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Severity`: [`ETemperatureSeverityType`](../enums/ue_ue.ETemperatureSeverityType.md)) => `void`\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnTemperatureChangeDelegate](ue_ue.ApplicationLifecycleComponent.md#ontemperaturechangedelegate)

#### Defined in

[ue/ue.d.ts:20652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20652)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[PrimaryComponentTick](ue_ue.ApplicationLifecycleComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[UCSModifiedProperties](ue_ue.ApplicationLifecycleComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[__tid_ActorComponent__](ue_ue.ApplicationLifecycleComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_ApplicationLifecycleComponent\_\_

• **\_\_tid\_ApplicationLifecycleComponent\_\_**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[__tid_ApplicationLifecycleComponent__](ue_ue.ApplicationLifecycleComponent.md#__tid_applicationlifecyclecomponent__)

#### Defined in

[ue/ue.d.ts:20662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20662)

___

### \_\_tid\_LuminApplicationLifecycleComponent\_\_

• **\_\_tid\_LuminApplicationLifecycleComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46409)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[__tid_Object__](ue_ue.ApplicationLifecycleComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bAutoActivate](ue_ue.ApplicationLifecycleComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bCanEverAffectNavigation](ue_ue.ApplicationLifecycleComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bCreatedByConstructionScript](ue_ue.ApplicationLifecycleComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bEditableWhenInherited](ue_ue.ApplicationLifecycleComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bInstanceComponent](ue_ue.ApplicationLifecycleComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bIsActive](ue_ue.ApplicationLifecycleComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bIsEditorOnly](ue_ue.ApplicationLifecycleComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bIsVisualizationComponent](ue_ue.ApplicationLifecycleComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bNetAddressable](ue_ue.ApplicationLifecycleComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[bReplicates](ue_ue.ApplicationLifecycleComponent.md#breplicates)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[Activate](ue_ue.ApplicationLifecycleComponent.md#activate)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[AddTickPrerequisiteActor](ue_ue.ApplicationLifecycleComponent.md#addtickprerequisiteactor)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[AddTickPrerequisiteComponent](ue_ue.ApplicationLifecycleComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L308)

___

### ApplicationLifetimeDelegate\_\_DelegateSignature

▸ **ApplicationLifetimeDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ApplicationLifetimeDelegate__DelegateSignature](ue_ue.ApplicationLifecycleComponent.md#applicationlifetimedelegate__delegatesignature)

#### Defined in

[ue/ue.d.ts:20654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20654)

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

#### Defined in

[ue/ue.d.ts:20655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20655)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[CreateDefaultSubobject](ue_ue.ApplicationLifecycleComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[Deactivate](ue_ue.ApplicationLifecycleComponent.md#deactivate)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ExecuteUbergraph](ue_ue.ApplicationLifecycleComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetClass](ue_ue.ApplicationLifecycleComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetComponentTickInterval](ue_ue.ApplicationLifecycleComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetName](ue_ue.ApplicationLifecycleComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetOuter](ue_ue.ApplicationLifecycleComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetOwner](ue_ue.ApplicationLifecycleComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[GetWorld](ue_ue.ApplicationLifecycleComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[IsActive](ue_ue.ApplicationLifecycleComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[IsBeingDestroyed](ue_ue.ApplicationLifecycleComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[IsComponentTickEnabled](ue_ue.ApplicationLifecycleComponent.md#iscomponenttickenabled)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[K2_DestroyComponent](ue_ue.ApplicationLifecycleComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### LuminApplicationLifetimeDelegate\_\_DelegateSignature

▸ **LuminApplicationLifetimeDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:46404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46404)

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

#### Defined in

[ue/ue.d.ts:20656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20656)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[OnRep_IsActive](ue_ue.ApplicationLifecycleComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

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

#### Defined in

[ue/ue.d.ts:20657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20657)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ReceiveBeginPlay](ue_ue.ApplicationLifecycleComponent.md#receivebeginplay)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ReceiveEndPlay](ue_ue.ApplicationLifecycleComponent.md#receiveendplay)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ReceiveTick](ue_ue.ApplicationLifecycleComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[RegisterComponent](ue_ue.ApplicationLifecycleComponent.md#registercomponent)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ApplicationLifecycleComponent.md#removetickprerequisiteactor)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ApplicationLifecycleComponent.md#removetickprerequisitecomponent)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetActive](ue_ue.ApplicationLifecycleComponent.md#setactive)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetAutoActivate](ue_ue.ApplicationLifecycleComponent.md#setautoactivate)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetComponentTickEnabled](ue_ue.ApplicationLifecycleComponent.md#setcomponenttickenabled)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetComponentTickInterval](ue_ue.ApplicationLifecycleComponent.md#setcomponenttickinterval)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetIsReplicated](ue_ue.ApplicationLifecycleComponent.md#setisreplicated)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetTickGroup](ue_ue.ApplicationLifecycleComponent.md#settickgroup)

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

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[SetTickableWhenPaused](ue_ue.ApplicationLifecycleComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[ToggleActive](ue_ue.ApplicationLifecycleComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:46406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46406)

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

#### Defined in

[ue/ue.d.ts:46407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46407)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ApplicationLifecycleComponent](ue_ue.ApplicationLifecycleComponent.md).[StaticClass](ue_ue.ApplicationLifecycleComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:46405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46405)
