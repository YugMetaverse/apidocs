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

## Properties

### BlueprintComponentDataCookingMethod

• **BlueprintComponentDataCookingMethod**: [`EBlueprintComponentDataCookingMethod`](../enums/ue_ue.EBlueprintComponentDataCookingMethod.md)

___

### ClassesExcludedOnDedicatedClient

• **ClassesExcludedOnDedicatedClient**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ClassesExcludedOnDedicatedServer

• **ClassesExcludedOnDedicatedServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### CookProgressDisplayMode

• **CookProgressDisplayMode**: [`ECookProgressDisplayMode`](../enums/ue_ue.ECookProgressDisplayMode.md)

___

### DefaultASTCQualityBySize

• **DefaultASTCQualityBySize**: `number`

___

### DefaultASTCQualityBySpeed

• **DefaultASTCQualityBySpeed**: `number`

___

### DefaultPVRTCQuality

• **DefaultPVRTCQuality**: `number`

___

### ModulesExcludedOnDedicatedClient

• **ModulesExcludedOnDedicatedClient**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ModulesExcludedOnDedicatedServer

• **ModulesExcludedOnDedicatedServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### VersionedIntRValues

• **VersionedIntRValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_CookerSettings\_\_

• **\_\_tid\_CookerSettings\_\_**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bAllowCookedDataInEditorBuilds

• **bAllowCookedDataInEditorBuilds**: `boolean`

___

### bCompileBlueprintsInDevelopmentMode

• **bCompileBlueprintsInDevelopmentMode**: `boolean`

___

### bCookBlueprintComponentTemplateData

• **bCookBlueprintComponentTemplateData**: `boolean`

___

### bCookOnTheFlyForLaunchOn

• **bCookOnTheFlyForLaunchOn**: `boolean`

___

### bEnableBuildDDCInBackground

• **bEnableBuildDDCInBackground**: `boolean`

___

### bEnableCookOnTheSide

• **bEnableCookOnTheSide**: `boolean`

___

### bIgnoreIniSettingsOutOfDateForIteration

• **bIgnoreIniSettingsOutOfDateForIteration**: `boolean`

___

### bIgnoreScriptPackagesOutOfDateForIteration

• **bIgnoreScriptPackagesOutOfDateForIteration**: `boolean`

___

### bIterativeCookingForFileCookContent

• **bIterativeCookingForFileCookContent**: `boolean`

___

### bIterativeCookingForLaunchOn

• **bIterativeCookingForLaunchOn**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
