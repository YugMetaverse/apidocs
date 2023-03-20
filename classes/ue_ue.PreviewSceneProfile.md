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

## Properties

### DirectionalLightColor

• **DirectionalLightColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### DirectionalLightIntensity

• **DirectionalLightIntensity**: `number`

___

### DirectionalLightRotation

• **DirectionalLightRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### EnvironmentColor

• **EnvironmentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### EnvironmentCubeMap

• **EnvironmentCubeMap**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`TextureCube`](ue_ue.TextureCube.md)\>

___

### EnvironmentCubeMapPath

• **EnvironmentCubeMapPath**: `string`

___

### EnvironmentIntensity

• **EnvironmentIntensity**: `number`

___

### LightingRigRotation

• **LightingRigRotation**: `number`

___

### PostProcessingSettings

• **PostProcessingSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

___

### ProfileName

• **ProfileName**: `string`

___

### RotationSpeed

• **RotationSpeed**: `number`

___

### SkyLightIntensity

• **SkyLightIntensity**: `number`

___

### \_\_tid\_PreviewSceneProfile\_\_

• `Private` **\_\_tid\_PreviewSceneProfile\_\_**: `boolean`

___

### bPostProcessingEnabled

• **bPostProcessingEnabled**: `boolean`

___

### bRotateLightingRig

• **bRotateLightingRig**: `boolean`

___

### bSharedProfile

• **bSharedProfile**: `boolean`

___

### bShowEnvironment

• **bShowEnvironment**: `boolean`

___

### bShowFloor

• **bShowFloor**: `boolean`

___

### bUseSkyLighting

• **bUseSkyLighting**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
