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

#### Defined in

[ue/ue.d.ts:46503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46503)

## Properties

### AppPrivileges

• **AppPrivileges**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ELuminPrivilege`](../enums/ue_ue.ELuminPrivilege.md)\>

#### Defined in

[ue/ue.d.ts:46516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46516)

___

### ApplicationDisplayName

• **ApplicationDisplayName**: `string`

#### Defined in

[ue/ue.d.ts:46505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46505)

___

### Certificate

• **Certificate**: [`FilePath`](ue_ue.FilePath.md)

#### Defined in

[ue/ue.d.ts:46511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46511)

___

### ExtraComponentElements

• **ExtraComponentElements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LuminComponentElement`](ue_ue.LuminComponentElement.md)\>

#### Defined in

[ue/ue.d.ts:46518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46518)

___

### ExtraComponentSubElements

• **ExtraComponentSubElements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LuminComponentSubElement`](ue_ue.LuminComponentSubElement.md)\>

#### Defined in

[ue/ue.d.ts:46517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46517)

___

### FrameTimingHint

• **FrameTimingHint**: [`ELuminFrameTimingHint`](../enums/ue_ue.ELuminFrameTimingHint.md)

#### Defined in

[ue/ue.d.ts:46507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46507)

___

### IconModelPath

• **IconModelPath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:46512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46512)

___

### IconPortalPath

• **IconPortalPath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:46513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46513)

___

### MinimumAPILevel

• **MinimumAPILevel**: `number`

#### Defined in

[ue/ue.d.ts:46515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46515)

___

### OcclusionPlugin

• **OcclusionPlugin**: `string`

#### Defined in

[ue/ue.d.ts:46521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46521)

___

### PackageName

• **PackageName**: `string`

#### Defined in

[ue/ue.d.ts:46504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46504)

___

### ReverbPlugin

• **ReverbPlugin**: `string`

#### Defined in

[ue/ue.d.ts:46520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46520)

___

### SoundCueCookQualityIndex

• **SoundCueCookQualityIndex**: `number`

#### Defined in

[ue/ue.d.ts:46522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46522)

___

### SpatializationPlugin

• **SpatializationPlugin**: `string`

#### Defined in

[ue/ue.d.ts:46519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46519)

___

### VersionCode

• **VersionCode**: `number`

#### Defined in

[ue/ue.d.ts:46514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46514)

___

### VulkanValidationLayerLibs

• **VulkanValidationLayerLibs**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:46524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46524)

___

### \_\_tid\_LuminRuntimeSettings\_\_

• **\_\_tid\_LuminRuntimeSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46530)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bFrameVignette

• **bFrameVignette**: `boolean`

#### Defined in

[ue/ue.d.ts:46525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46525)

___

### bIsScreensApp

• **bIsScreensApp**: `boolean`

#### Defined in

[ue/ue.d.ts:46506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46506)

___

### bProtectedContent

• **bProtectedContent**: `boolean`

#### Defined in

[ue/ue.d.ts:46508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46508)

___

### bRemoveDebugInfo

• **bRemoveDebugInfo**: `boolean`

#### Defined in

[ue/ue.d.ts:46523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46523)

___

### bUseMobileRendering

• **bUseMobileRendering**: `boolean`

#### Defined in

[ue/ue.d.ts:46509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46509)

___

### bUseVulkan

• **bUseVulkan**: `boolean`

#### Defined in

[ue/ue.d.ts:46510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46510)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:46527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46527)

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

#### Defined in

[ue/ue.d.ts:46528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46528)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:46526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46526)
