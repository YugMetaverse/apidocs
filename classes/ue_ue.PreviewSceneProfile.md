[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PreviewSceneProfile

# Class: PreviewSceneProfile

[ue/ue](../modules/ue_ue.md).PreviewSceneProfile

## Table of contents

### Constructors

- [constructor](ue_ue.PreviewSceneProfile.md#constructor)

### Properties

- [DirectionalLightColor](ue_ue.PreviewSceneProfile.md#directionallightcolor)
- [DirectionalLightIntensity](ue_ue.PreviewSceneProfile.md#directionallightintensity)
- [DirectionalLightRotation](ue_ue.PreviewSceneProfile.md#directionallightrotation)
- [EnvironmentColor](ue_ue.PreviewSceneProfile.md#environmentcolor)
- [EnvironmentCubeMap](ue_ue.PreviewSceneProfile.md#environmentcubemap)
- [EnvironmentCubeMapPath](ue_ue.PreviewSceneProfile.md#environmentcubemappath)
- [EnvironmentIntensity](ue_ue.PreviewSceneProfile.md#environmentintensity)
- [LightingRigRotation](ue_ue.PreviewSceneProfile.md#lightingrigrotation)
- [PostProcessingSettings](ue_ue.PreviewSceneProfile.md#postprocessingsettings)
- [ProfileName](ue_ue.PreviewSceneProfile.md#profilename)
- [RotationSpeed](ue_ue.PreviewSceneProfile.md#rotationspeed)
- [SkyLightIntensity](ue_ue.PreviewSceneProfile.md#skylightintensity)
- [\_\_tid\_PreviewSceneProfile\_\_](ue_ue.PreviewSceneProfile.md#__tid_previewsceneprofile__)
- [bPostProcessingEnabled](ue_ue.PreviewSceneProfile.md#bpostprocessingenabled)
- [bRotateLightingRig](ue_ue.PreviewSceneProfile.md#brotatelightingrig)
- [bSharedProfile](ue_ue.PreviewSceneProfile.md#bsharedprofile)
- [bShowEnvironment](ue_ue.PreviewSceneProfile.md#bshowenvironment)
- [bShowFloor](ue_ue.PreviewSceneProfile.md#bshowfloor)
- [bUseSkyLighting](ue_ue.PreviewSceneProfile.md#buseskylighting)

### Methods

- [StaticClass](ue_ue.PreviewSceneProfile.md#staticclass)
- [StaticStruct](ue_ue.PreviewSceneProfile.md#staticstruct)

## Constructors

### constructor

• **new PreviewSceneProfile**()

#### Defined in

[ue/ue.d.ts:22010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22010)

• **new PreviewSceneProfile**(`ProfileName`, `bSharedProfile`, `bUseSkyLighting`, `DirectionalLightIntensity`, `DirectionalLightColor`, `SkyLightIntensity`, `bRotateLightingRig`, `bShowEnvironment`, `bShowFloor`, `EnvironmentColor`, `EnvironmentIntensity`, `EnvironmentCubeMap`, `EnvironmentCubeMapPath`, `bPostProcessingEnabled`, `PostProcessingSettings`, `LightingRigRotation`, `RotationSpeed`, `DirectionalLightRotation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProfileName` | `string` |
| `bSharedProfile` | `boolean` |
| `bUseSkyLighting` | `boolean` |
| `DirectionalLightIntensity` | `number` |
| `DirectionalLightColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `SkyLightIntensity` | `number` |
| `bRotateLightingRig` | `boolean` |
| `bShowEnvironment` | `boolean` |
| `bShowFloor` | `boolean` |
| `EnvironmentColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `EnvironmentIntensity` | `number` |
| `EnvironmentCubeMap` | [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`TextureCube`](ue_ue.TextureCube.md)\> |
| `EnvironmentCubeMapPath` | `string` |
| `bPostProcessingEnabled` | `boolean` |
| `PostProcessingSettings` | [`PostProcessSettings`](ue_ue.PostProcessSettings.md) |
| `LightingRigRotation` | `number` |
| `RotationSpeed` | `number` |
| `DirectionalLightRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Defined in

[ue/ue.d.ts:22011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22011)

## Properties

### DirectionalLightColor

• **DirectionalLightColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:22016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22016)

___

### DirectionalLightIntensity

• **DirectionalLightIntensity**: `number`

#### Defined in

[ue/ue.d.ts:22015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22015)

___

### DirectionalLightRotation

• **DirectionalLightRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:22029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22029)

___

### EnvironmentColor

• **EnvironmentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:22021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22021)

___

### EnvironmentCubeMap

• **EnvironmentCubeMap**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`TextureCube`](ue_ue.TextureCube.md)\>

#### Defined in

[ue/ue.d.ts:22023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22023)

___

### EnvironmentCubeMapPath

• **EnvironmentCubeMapPath**: `string`

#### Defined in

[ue/ue.d.ts:22024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22024)

___

### EnvironmentIntensity

• **EnvironmentIntensity**: `number`

#### Defined in

[ue/ue.d.ts:22022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22022)

___

### LightingRigRotation

• **LightingRigRotation**: `number`

#### Defined in

[ue/ue.d.ts:22027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22027)

___

### PostProcessingSettings

• **PostProcessingSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

#### Defined in

[ue/ue.d.ts:22026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22026)

___

### ProfileName

• **ProfileName**: `string`

#### Defined in

[ue/ue.d.ts:22012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22012)

___

### RotationSpeed

• **RotationSpeed**: `number`

#### Defined in

[ue/ue.d.ts:22028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22028)

___

### SkyLightIntensity

• **SkyLightIntensity**: `number`

#### Defined in

[ue/ue.d.ts:22017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22017)

___

### \_\_tid\_PreviewSceneProfile\_\_

• `Private` **\_\_tid\_PreviewSceneProfile\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22035)

___

### bPostProcessingEnabled

• **bPostProcessingEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:22025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22025)

___

### bRotateLightingRig

• **bRotateLightingRig**: `boolean`

#### Defined in

[ue/ue.d.ts:22018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22018)

___

### bSharedProfile

• **bSharedProfile**: `boolean`

#### Defined in

[ue/ue.d.ts:22013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22013)

___

### bShowEnvironment

• **bShowEnvironment**: `boolean`

#### Defined in

[ue/ue.d.ts:22019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22019)

___

### bShowFloor

• **bShowFloor**: `boolean`

#### Defined in

[ue/ue.d.ts:22020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22020)

___

### bUseSkyLighting

• **bUseSkyLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:22014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22014)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:22033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22033)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:22034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22034)
