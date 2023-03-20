[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LuminRuntimeSettings

# Class: LuminRuntimeSettings

[ue/ue](../modules/ue_ue.md).LuminRuntimeSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LuminRuntimeSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.LuminRuntimeSettings.md#constructor)

### Properties

- [AppPrivileges](ue_ue.LuminRuntimeSettings.md#appprivileges)
- [ApplicationDisplayName](ue_ue.LuminRuntimeSettings.md#applicationdisplayname)
- [Certificate](ue_ue.LuminRuntimeSettings.md#certificate)
- [ExtraComponentElements](ue_ue.LuminRuntimeSettings.md#extracomponentelements)
- [ExtraComponentSubElements](ue_ue.LuminRuntimeSettings.md#extracomponentsubelements)
- [FrameTimingHint](ue_ue.LuminRuntimeSettings.md#frametiminghint)
- [IconModelPath](ue_ue.LuminRuntimeSettings.md#iconmodelpath)
- [IconPortalPath](ue_ue.LuminRuntimeSettings.md#iconportalpath)
- [MinimumAPILevel](ue_ue.LuminRuntimeSettings.md#minimumapilevel)
- [OcclusionPlugin](ue_ue.LuminRuntimeSettings.md#occlusionplugin)
- [PackageName](ue_ue.LuminRuntimeSettings.md#packagename)
- [ReverbPlugin](ue_ue.LuminRuntimeSettings.md#reverbplugin)
- [SoundCueCookQualityIndex](ue_ue.LuminRuntimeSettings.md#soundcuecookqualityindex)
- [SpatializationPlugin](ue_ue.LuminRuntimeSettings.md#spatializationplugin)
- [VersionCode](ue_ue.LuminRuntimeSettings.md#versioncode)
- [VulkanValidationLayerLibs](ue_ue.LuminRuntimeSettings.md#vulkanvalidationlayerlibs)
- [\_\_tid\_LuminRuntimeSettings\_\_](ue_ue.LuminRuntimeSettings.md#__tid_luminruntimesettings__)
- [\_\_tid\_Object\_\_](ue_ue.LuminRuntimeSettings.md#__tid_object__)
- [bFrameVignette](ue_ue.LuminRuntimeSettings.md#bframevignette)
- [bIsScreensApp](ue_ue.LuminRuntimeSettings.md#bisscreensapp)
- [bProtectedContent](ue_ue.LuminRuntimeSettings.md#bprotectedcontent)
- [bRemoveDebugInfo](ue_ue.LuminRuntimeSettings.md#bremovedebuginfo)
- [bUseMobileRendering](ue_ue.LuminRuntimeSettings.md#busemobilerendering)
- [bUseVulkan](ue_ue.LuminRuntimeSettings.md#busevulkan)

### Methods

- [CreateDefaultSubobject](ue_ue.LuminRuntimeSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LuminRuntimeSettings.md#executeubergraph)
- [GetClass](ue_ue.LuminRuntimeSettings.md#getclass)
- [GetName](ue_ue.LuminRuntimeSettings.md#getname)
- [GetOuter](ue_ue.LuminRuntimeSettings.md#getouter)
- [GetWorld](ue_ue.LuminRuntimeSettings.md#getworld)
- [Find](ue_ue.LuminRuntimeSettings.md#find)
- [Load](ue_ue.LuminRuntimeSettings.md#load)
- [StaticClass](ue_ue.LuminRuntimeSettings.md#staticclass)

## Constructors

### constructor

• **new LuminRuntimeSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AppPrivileges

• **AppPrivileges**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ELuminPrivilege`](../enums/ue_ue.ELuminPrivilege.md)\>

___

### ApplicationDisplayName

• **ApplicationDisplayName**: `string`

___

### Certificate

• **Certificate**: [`FilePath`](ue_ue.FilePath.md)

___

### ExtraComponentElements

• **ExtraComponentElements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LuminComponentElement`](ue_ue.LuminComponentElement.md)\>

___

### ExtraComponentSubElements

• **ExtraComponentSubElements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LuminComponentSubElement`](ue_ue.LuminComponentSubElement.md)\>

___

### FrameTimingHint

• **FrameTimingHint**: [`ELuminFrameTimingHint`](../enums/ue_ue.ELuminFrameTimingHint.md)

___

### IconModelPath

• **IconModelPath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### IconPortalPath

• **IconPortalPath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### MinimumAPILevel

• **MinimumAPILevel**: `number`

___

### OcclusionPlugin

• **OcclusionPlugin**: `string`

___

### PackageName

• **PackageName**: `string`

___

### ReverbPlugin

• **ReverbPlugin**: `string`

___

### SoundCueCookQualityIndex

• **SoundCueCookQualityIndex**: `number`

___

### SpatializationPlugin

• **SpatializationPlugin**: `string`

___

### VersionCode

• **VersionCode**: `number`

___

### VulkanValidationLayerLibs

• **VulkanValidationLayerLibs**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### \_\_tid\_LuminRuntimeSettings\_\_

• **\_\_tid\_LuminRuntimeSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bFrameVignette

• **bFrameVignette**: `boolean`

___

### bIsScreensApp

• **bIsScreensApp**: `boolean`

___

### bProtectedContent

• **bProtectedContent**: `boolean`

___

### bRemoveDebugInfo

• **bRemoveDebugInfo**: `boolean`

___

### bUseMobileRendering

• **bUseMobileRendering**: `boolean`

___

### bUseVulkan

• **bUseVulkan**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LuminRuntimeSettings`](ue_ue.LuminRuntimeSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LuminRuntimeSettings`](ue_ue.LuminRuntimeSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LuminRuntimeSettings`](ue_ue.LuminRuntimeSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LuminRuntimeSettings`](ue_ue.LuminRuntimeSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
