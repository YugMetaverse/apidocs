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

#### Defined in

[ue/ue.d.ts:55731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55731)

## Properties

### BrightnessOverLife

• **BrightnessOverLife**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55737)

___

### ColorScaleOverLife

• **ColorScaleOverLife**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55736)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[LODDuplicate](ue_ue.ParticleModuleLightBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[LODValidity](ue_ue.ParticleModuleLightBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6748)

___

### LightExponent

• **LightExponent**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55739)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Defined in

[ue/ue.d.ts:55740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55740)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[ModuleEditorColor](ue_ue.ParticleModuleLightBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6749)

___

### RadiusScale

• **RadiusScale**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55738)

___

### SpawnFraction

• **SpawnFraction**: `number`

#### Defined in

[ue/ue.d.ts:55735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55735)

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

#### Defined in

[ue/ue.d.ts:55741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55741)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[__tid_Object__](ue_ue.ParticleModuleLightBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleLightBase\_\_

• **\_\_tid\_ParticleModuleLightBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[__tid_ParticleModuleLightBase__](ue_ue.ParticleModuleLightBase.md#__tid_particlemodulelightbase__)

#### Defined in

[ue/ue.d.ts:55727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55727)

___

### \_\_tid\_ParticleModuleLight\_\_

• **\_\_tid\_ParticleModuleLight\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:55748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55748)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleLightBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[b3DDrawMode](ue_ue.ParticleModuleLightBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6741)

___

### bAffectsTranslucency

• **bAffectsTranslucency**: `boolean`

#### Defined in

[ue/ue.d.ts:55733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55733)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bCurvesAsColor](ue_ue.ParticleModuleLightBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bEditable](ue_ue.ParticleModuleLightBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bEnabled](ue_ue.ParticleModuleLightBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleLightBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6738)

___

### bHighQualityLights

• **bHighQualityLights**: `boolean`

#### Defined in

[ue/ue.d.ts:55742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55742)

___

### bPreviewLightRadius

• **bPreviewLightRadius**: `boolean`

#### Defined in

[ue/ue.d.ts:55734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55734)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleLightBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6747)

___

### bShadowCastingLights

• **bShadowCastingLights**: `boolean`

#### Defined in

[ue/ue.d.ts:55743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55743)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bSpawnModule](ue_ue.ParticleModuleLightBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleLightBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleLightBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleLightBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[bUpdateModule](ue_ue.ParticleModuleLightBase.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6737)

___

### bUseInverseSquaredFalloff

• **bUseInverseSquaredFalloff**: `boolean`

#### Defined in

[ue/ue.d.ts:55732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55732)

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

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleLightBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetClass](ue_ue.ParticleModuleLightBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetName](ue_ue.ParticleModuleLightBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetOuter](ue_ue.ParticleModuleLightBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[GetWorld](ue_ue.ParticleModuleLightBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:55745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55745)

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

#### Defined in

[ue/ue.d.ts:55746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55746)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleLightBase](ue_ue.ParticleModuleLightBase.md).[StaticClass](ue_ue.ParticleModuleLightBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:55744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L55744)
