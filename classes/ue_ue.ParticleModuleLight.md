[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleLight

# Class: ParticleModuleLight

[ue/ue](../modules/ue_ue.md).ParticleModuleLight

## Hierarchy

- [`ParticleModuleLightBase`](ue_ue.ParticleModuleLightBase.md)

  ↳ **`ParticleModuleLight`**

  ↳↳ [`ParticleModuleLight_Seeded`](ue_ue.ParticleModuleLight_Seeded.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleLight.md#constructor)

### Properties

- [BrightnessOverLife](ue_ue.ParticleModuleLight.md#brightnessoverlife)
- [ColorScaleOverLife](ue_ue.ParticleModuleLight.md#colorscaleoverlife)
- [LODDuplicate](ue_ue.ParticleModuleLight.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleLight.md#lodvalidity)
- [LightExponent](ue_ue.ParticleModuleLight.md#lightexponent)
- [LightingChannels](ue_ue.ParticleModuleLight.md#lightingchannels)
- [ModuleEditorColor](ue_ue.ParticleModuleLight.md#moduleeditorcolor)
- [RadiusScale](ue_ue.ParticleModuleLight.md#radiusscale)
- [SpawnFraction](ue_ue.ParticleModuleLight.md#spawnfraction)
- [VolumetricScatteringIntensity](ue_ue.ParticleModuleLight.md#volumetricscatteringintensity)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleLight.md#__tid_object__)
- [\_\_tid\_ParticleModuleLightBase\_\_](ue_ue.ParticleModuleLight.md#__tid_particlemodulelightbase__)
- [\_\_tid\_ParticleModuleLight\_\_](ue_ue.ParticleModuleLight.md#__tid_particlemodulelight__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleLight.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleLight.md#b3ddrawmode)
- [bAffectsTranslucency](ue_ue.ParticleModuleLight.md#baffectstranslucency)
- [bCurvesAsColor](ue_ue.ParticleModuleLight.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleLight.md#beditable)
- [bEnabled](ue_ue.ParticleModuleLight.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleLight.md#bfinalupdatemodule)
- [bHighQualityLights](ue_ue.ParticleModuleLight.md#bhighqualitylights)
- [bPreviewLightRadius](ue_ue.ParticleModuleLight.md#bpreviewlightradius)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleLight.md#brequiresloopingnotification)
- [bShadowCastingLights](ue_ue.ParticleModuleLight.md#bshadowcastinglights)
- [bSpawnModule](ue_ue.ParticleModuleLight.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleLight.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleLight.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleLight.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleLight.md#bupdatemodule)
- [bUseInverseSquaredFalloff](ue_ue.ParticleModuleLight.md#buseinversesquaredfalloff)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleLight.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleLight.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleLight.md#getclass)
- [GetName](ue_ue.ParticleModuleLight.md#getname)
- [GetOuter](ue_ue.ParticleModuleLight.md#getouter)
- [GetWorld](ue_ue.ParticleModuleLight.md#getworld)
- [Find](ue_ue.ParticleModuleLight.md#find)
- [Load](ue_ue.ParticleModuleLight.md#load)
- [StaticClass](ue_ue.ParticleModuleLight.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleLight**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[constructor](ue_ue.ParticleModuleLightBase.md#constructor)

## Properties

### BrightnessOverLife

• **BrightnessOverLife**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### ColorScaleOverLife

• **ColorScaleOverLife**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[LODDuplicate](ue_ue.ParticleModuleLightBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[LODValidity](ue_ue.ParticleModuleLightBase.md#lodvalidity)

___

### LightExponent

• **LightExponent**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[ModuleEditorColor](ue_ue.ParticleModuleLightBase.md#moduleeditorcolor)

___

### RadiusScale

• **RadiusScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### SpawnFraction

• **SpawnFraction**: `number`

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[__tid_Object__](ue_ue.ParticleModuleLightBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleLightBase\_\_

• **\_\_tid\_ParticleModuleLightBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[__tid_ParticleModuleLightBase__](ue_ue.ParticleModuleLightBase.md#__tid_particlemodulelightbase__)

___

### \_\_tid\_ParticleModuleLight\_\_

• **\_\_tid\_ParticleModuleLight\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleLightBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[b3DDrawMode](ue_ue.ParticleModuleLightBase.md#b3ddrawmode)

___

### bAffectsTranslucency

• **bAffectsTranslucency**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bCurvesAsColor](ue_ue.ParticleModuleLightBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bEditable](ue_ue.ParticleModuleLightBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bEnabled](ue_ue.ParticleModuleLightBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleLightBase.md#bfinalupdatemodule)

___

### bHighQualityLights

• **bHighQualityLights**: `boolean`

___

### bPreviewLightRadius

• **bPreviewLightRadius**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleLightBase.md#brequiresloopingnotification)

___

### bShadowCastingLights

• **bShadowCastingLights**: `boolean`

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bSpawnModule](ue_ue.ParticleModuleLightBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleLightBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleLightBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleLightBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bUpdateModule](ue_ue.ParticleModuleLightBase.md#bupdatemodule)

___

### bUseInverseSquaredFalloff

• **bUseInverseSquaredFalloff**: `boolean`

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

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleLightBase.md#createdefaultsubobject)

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

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleLightBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetClass](ue_ue.ParticleModuleLightBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetName](ue_ue.ParticleModuleLightBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetOuter](ue_ue.ParticleModuleLightBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetWorld](ue_ue.ParticleModuleLightBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleLight`](ue_ue.ParticleModuleLight.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleLight`](ue_ue.ParticleModuleLight.md)

#### Overrides

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[Find](ue_ue.ParticleModuleLightBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleLight`](ue_ue.ParticleModuleLight.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleLight`](ue_ue.ParticleModuleLight.md)

#### Overrides

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[Load](ue_ue.ParticleModuleLightBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[StaticClass](ue_ue.ParticleModuleLightBase.md#staticclass)
