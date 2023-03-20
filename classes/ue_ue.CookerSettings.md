[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CookerSettings

# Class: CookerSettings

[ue/ue](../modules/ue_ue.md).CookerSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`CookerSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.CookerSettings.md#constructor)

### Properties

- [BlueprintComponentDataCookingMethod](ue_ue.CookerSettings.md#blueprintcomponentdatacookingmethod)
- [ClassesExcludedOnDedicatedClient](ue_ue.CookerSettings.md#classesexcludedondedicatedclient)
- [ClassesExcludedOnDedicatedServer](ue_ue.CookerSettings.md#classesexcludedondedicatedserver)
- [CookProgressDisplayMode](ue_ue.CookerSettings.md#cookprogressdisplaymode)
- [DefaultASTCQualityBySize](ue_ue.CookerSettings.md#defaultastcqualitybysize)
- [DefaultASTCQualityBySpeed](ue_ue.CookerSettings.md#defaultastcqualitybyspeed)
- [DefaultPVRTCQuality](ue_ue.CookerSettings.md#defaultpvrtcquality)
- [ModulesExcludedOnDedicatedClient](ue_ue.CookerSettings.md#modulesexcludedondedicatedclient)
- [ModulesExcludedOnDedicatedServer](ue_ue.CookerSettings.md#modulesexcludedondedicatedserver)
- [VersionedIntRValues](ue_ue.CookerSettings.md#versionedintrvalues)
- [\_\_tid\_CookerSettings\_\_](ue_ue.CookerSettings.md#__tid_cookersettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.CookerSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.CookerSettings.md#__tid_object__)
- [bAllowCookedDataInEditorBuilds](ue_ue.CookerSettings.md#ballowcookeddataineditorbuilds)
- [bCompileBlueprintsInDevelopmentMode](ue_ue.CookerSettings.md#bcompileblueprintsindevelopmentmode)
- [bCookBlueprintComponentTemplateData](ue_ue.CookerSettings.md#bcookblueprintcomponenttemplatedata)
- [bCookOnTheFlyForLaunchOn](ue_ue.CookerSettings.md#bcookontheflyforlaunchon)
- [bEnableBuildDDCInBackground](ue_ue.CookerSettings.md#benablebuildddcinbackground)
- [bEnableCookOnTheSide](ue_ue.CookerSettings.md#benablecookontheside)
- [bIgnoreIniSettingsOutOfDateForIteration](ue_ue.CookerSettings.md#bignoreinisettingsoutofdateforiteration)
- [bIgnoreScriptPackagesOutOfDateForIteration](ue_ue.CookerSettings.md#bignorescriptpackagesoutofdateforiteration)
- [bIterativeCookingForFileCookContent](ue_ue.CookerSettings.md#biterativecookingforfilecookcontent)
- [bIterativeCookingForLaunchOn](ue_ue.CookerSettings.md#biterativecookingforlaunchon)

### Methods

- [CreateDefaultSubobject](ue_ue.CookerSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CookerSettings.md#executeubergraph)
- [GetClass](ue_ue.CookerSettings.md#getclass)
- [GetName](ue_ue.CookerSettings.md#getname)
- [GetOuter](ue_ue.CookerSettings.md#getouter)
- [GetWorld](ue_ue.CookerSettings.md#getworld)
- [Find](ue_ue.CookerSettings.md#find)
- [Load](ue_ue.CookerSettings.md#load)
- [StaticClass](ue_ue.CookerSettings.md#staticclass)

## Constructors

### constructor

• **new CookerSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:28754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28754)

## Properties

### BlueprintComponentDataCookingMethod

• **BlueprintComponentDataCookingMethod**: [`EBlueprintComponentDataCookingMethod`](../enums/ue_ue.EBlueprintComponentDataCookingMethod.md)

#### Defined in

[ue/ue.d.ts:28764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28764)

___

### ClassesExcludedOnDedicatedClient

• **ClassesExcludedOnDedicatedClient**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:28767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28767)

___

### ClassesExcludedOnDedicatedServer

• **ClassesExcludedOnDedicatedServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:28765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28765)

___

### CookProgressDisplayMode

• **CookProgressDisplayMode**: [`ECookProgressDisplayMode`](../enums/ue_ue.ECookProgressDisplayMode.md)

#### Defined in

[ue/ue.d.ts:28760](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28760)

___

### DefaultASTCQualityBySize

• **DefaultASTCQualityBySize**: `number`

#### Defined in

[ue/ue.d.ts:28772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28772)

___

### DefaultASTCQualityBySpeed

• **DefaultASTCQualityBySpeed**: `number`

#### Defined in

[ue/ue.d.ts:28771](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28771)

___

### DefaultPVRTCQuality

• **DefaultPVRTCQuality**: `number`

#### Defined in

[ue/ue.d.ts:28770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28770)

___

### ModulesExcludedOnDedicatedClient

• **ModulesExcludedOnDedicatedClient**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:28768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28768)

___

### ModulesExcludedOnDedicatedServer

• **ModulesExcludedOnDedicatedServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:28766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28766)

___

### VersionedIntRValues

• **VersionedIntRValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:28769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28769)

___

### \_\_tid\_CookerSettings\_\_

• **\_\_tid\_CookerSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28779](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28779)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAllowCookedDataInEditorBuilds

• **bAllowCookedDataInEditorBuilds**: `boolean`

#### Defined in

[ue/ue.d.ts:28773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28773)

___

### bCompileBlueprintsInDevelopmentMode

• **bCompileBlueprintsInDevelopmentMode**: `boolean`

#### Defined in

[ue/ue.d.ts:28763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28763)

___

### bCookBlueprintComponentTemplateData

• **bCookBlueprintComponentTemplateData**: `boolean`

#### Defined in

[ue/ue.d.ts:28774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28774)

___

### bCookOnTheFlyForLaunchOn

• **bCookOnTheFlyForLaunchOn**: `boolean`

#### Defined in

[ue/ue.d.ts:28759](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28759)

___

### bEnableBuildDDCInBackground

• **bEnableBuildDDCInBackground**: `boolean`

#### Defined in

[ue/ue.d.ts:28756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28756)

___

### bEnableCookOnTheSide

• **bEnableCookOnTheSide**: `boolean`

#### Defined in

[ue/ue.d.ts:28755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28755)

___

### bIgnoreIniSettingsOutOfDateForIteration

• **bIgnoreIniSettingsOutOfDateForIteration**: `boolean`

#### Defined in

[ue/ue.d.ts:28761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28761)

___

### bIgnoreScriptPackagesOutOfDateForIteration

• **bIgnoreScriptPackagesOutOfDateForIteration**: `boolean`

#### Defined in

[ue/ue.d.ts:28762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28762)

___

### bIterativeCookingForFileCookContent

• **bIterativeCookingForFileCookContent**: `boolean`

#### Defined in

[ue/ue.d.ts:28758](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28758)

___

### bIterativeCookingForLaunchOn

• **bIterativeCookingForLaunchOn**: `boolean`

#### Defined in

[ue/ue.d.ts:28757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28757)

## Methods

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CookerSettings`](ue_ue.CookerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CookerSettings`](ue_ue.CookerSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

#### Defined in

[ue/ue.d.ts:28776](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28776)

___

### Load

▸ `Static` **Load**(`InName`): [`CookerSettings`](ue_ue.CookerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CookerSettings`](ue_ue.CookerSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

#### Defined in

[ue/ue.d.ts:28777](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28777)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:28775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28775)
