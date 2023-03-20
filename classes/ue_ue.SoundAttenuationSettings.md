[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundAttenuationSettings

# Class: SoundAttenuationSettings

[ue/ue](../modules/ue_ue.md).SoundAttenuationSettings

## Hierarchy

- [`BaseAttenuationSettings`](ue_ue.BaseAttenuationSettings.md)

  ↳ **`SoundAttenuationSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundAttenuationSettings.md#constructor)

### Properties

- [AbsorptionMethod](ue_ue.SoundAttenuationSettings.md#absorptionmethod)
- [AttenuationShape](ue_ue.SoundAttenuationSettings.md#attenuationshape)
- [AttenuationShapeExtents](ue_ue.SoundAttenuationSettings.md#attenuationshapeextents)
- [BinauralRadius](ue_ue.SoundAttenuationSettings.md#binauralradius)
- [ConeOffset](ue_ue.SoundAttenuationSettings.md#coneoffset)
- [CustomAttenuationCurve](ue_ue.SoundAttenuationSettings.md#customattenuationcurve)
- [CustomHighpassAirAbsorptionCurve](ue_ue.SoundAttenuationSettings.md#customhighpassairabsorptioncurve)
- [CustomLowpassAirAbsorptionCurve](ue_ue.SoundAttenuationSettings.md#customlowpassairabsorptioncurve)
- [CustomReverbSendCurve](ue_ue.SoundAttenuationSettings.md#customreverbsendcurve)
- [DistanceAlgorithm](ue_ue.SoundAttenuationSettings.md#distancealgorithm)
- [DistanceType](ue_ue.SoundAttenuationSettings.md#distancetype)
- [FalloffDistance](ue_ue.SoundAttenuationSettings.md#falloffdistance)
- [FocusAttackInterpSpeed](ue_ue.SoundAttenuationSettings.md#focusattackinterpspeed)
- [FocusAzimuth](ue_ue.SoundAttenuationSettings.md#focusazimuth)
- [FocusDistanceScale](ue_ue.SoundAttenuationSettings.md#focusdistancescale)
- [FocusPriorityScale](ue_ue.SoundAttenuationSettings.md#focuspriorityscale)
- [FocusReleaseInterpSpeed](ue_ue.SoundAttenuationSettings.md#focusreleaseinterpspeed)
- [FocusVolumeAttenuation](ue_ue.SoundAttenuationSettings.md#focusvolumeattenuation)
- [HPFFrequencyAtMax](ue_ue.SoundAttenuationSettings.md#hpffrequencyatmax)
- [HPFFrequencyAtMin](ue_ue.SoundAttenuationSettings.md#hpffrequencyatmin)
- [LPFFrequencyAtMax](ue_ue.SoundAttenuationSettings.md#lpffrequencyatmax)
- [LPFFrequencyAtMin](ue_ue.SoundAttenuationSettings.md#lpffrequencyatmin)
- [LPFRadiusMax](ue_ue.SoundAttenuationSettings.md#lpfradiusmax)
- [LPFRadiusMin](ue_ue.SoundAttenuationSettings.md#lpfradiusmin)
- [ManualReverbSendLevel](ue_ue.SoundAttenuationSettings.md#manualreverbsendlevel)
- [NonFocusAzimuth](ue_ue.SoundAttenuationSettings.md#nonfocusazimuth)
- [NonFocusDistanceScale](ue_ue.SoundAttenuationSettings.md#nonfocusdistancescale)
- [NonFocusPriorityScale](ue_ue.SoundAttenuationSettings.md#nonfocuspriorityscale)
- [NonFocusVolumeAttenuation](ue_ue.SoundAttenuationSettings.md#nonfocusvolumeattenuation)
- [OcclusionInterpolationTime](ue_ue.SoundAttenuationSettings.md#occlusioninterpolationtime)
- [OcclusionLowPassFilterFrequency](ue_ue.SoundAttenuationSettings.md#occlusionlowpassfilterfrequency)
- [OcclusionPluginSettings](ue_ue.SoundAttenuationSettings.md#occlusionpluginsettings)
- [OcclusionTraceChannel](ue_ue.SoundAttenuationSettings.md#occlusiontracechannel)
- [OcclusionVolumeAttenuation](ue_ue.SoundAttenuationSettings.md#occlusionvolumeattenuation)
- [OmniRadius](ue_ue.SoundAttenuationSettings.md#omniradius)
- [PluginSettings](ue_ue.SoundAttenuationSettings.md#pluginsettings)
- [RadiusMax](ue_ue.SoundAttenuationSettings.md#radiusmax)
- [RadiusMin](ue_ue.SoundAttenuationSettings.md#radiusmin)
- [ReverbDistanceMax](ue_ue.SoundAttenuationSettings.md#reverbdistancemax)
- [ReverbDistanceMin](ue_ue.SoundAttenuationSettings.md#reverbdistancemin)
- [ReverbPluginSettings](ue_ue.SoundAttenuationSettings.md#reverbpluginsettings)
- [ReverbSendMethod](ue_ue.SoundAttenuationSettings.md#reverbsendmethod)
- [ReverbWetLevelMax](ue_ue.SoundAttenuationSettings.md#reverbwetlevelmax)
- [ReverbWetLevelMin](ue_ue.SoundAttenuationSettings.md#reverbwetlevelmin)
- [SpatializationAlgorithm](ue_ue.SoundAttenuationSettings.md#spatializationalgorithm)
- [SpatializationPluginSettings](ue_ue.SoundAttenuationSettings.md#spatializationpluginsettings)
- [StereoSpread](ue_ue.SoundAttenuationSettings.md#stereospread)
- [\_\_tid\_SoundAttenuationSettings\_\_](ue_ue.SoundAttenuationSettings.md#__tid_soundattenuationsettings__)
- [bApplyNormalizationToStereoSounds](ue_ue.SoundAttenuationSettings.md#bapplynormalizationtostereosounds)
- [bAttenuate](ue_ue.SoundAttenuationSettings.md#battenuate)
- [bAttenuateWithLPF](ue_ue.SoundAttenuationSettings.md#battenuatewithlpf)
- [bEnableFocusInterpolation](ue_ue.SoundAttenuationSettings.md#benablefocusinterpolation)
- [bEnableListenerFocus](ue_ue.SoundAttenuationSettings.md#benablelistenerfocus)
- [bEnableLogFrequencyScaling](ue_ue.SoundAttenuationSettings.md#benablelogfrequencyscaling)
- [bEnableOcclusion](ue_ue.SoundAttenuationSettings.md#benableocclusion)
- [bEnableReverbSend](ue_ue.SoundAttenuationSettings.md#benablereverbsend)
- [bSpatialize](ue_ue.SoundAttenuationSettings.md#bspatialize)
- [bUseComplexCollisionForOcclusion](ue_ue.SoundAttenuationSettings.md#busecomplexcollisionforocclusion)
- [dBAttenuationAtMax](ue_ue.SoundAttenuationSettings.md#dbattenuationatmax)

### Methods

- [StaticClass](ue_ue.SoundAttenuationSettings.md#staticclass)
- [StaticStruct](ue_ue.SoundAttenuationSettings.md#staticstruct)

## Constructors

### constructor

• **new SoundAttenuationSettings**()

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[constructor](ue_ue.BaseAttenuationSettings.md#constructor)

• **new SoundAttenuationSettings**(`bAttenuate`, `bSpatialize`, `bAttenuateWithLPF`, `bEnableListenerFocus`, `bEnableFocusInterpolation`, `bEnableOcclusion`, `bUseComplexCollisionForOcclusion`, `bEnableReverbSend`, `bApplyNormalizationToStereoSounds`, `bEnableLogFrequencyScaling`, `SpatializationAlgorithm`, `BinauralRadius`, `AbsorptionMethod`, `OcclusionTraceChannel`, `ReverbSendMethod`, `DistanceType`, `OmniRadius`, `StereoSpread`, `SpatializationPluginSettings`, `RadiusMin`, `RadiusMax`, `LPFRadiusMin`, `LPFRadiusMax`, `CustomLowpassAirAbsorptionCurve`, `CustomHighpassAirAbsorptionCurve`, `LPFFrequencyAtMin`, `LPFFrequencyAtMax`, `HPFFrequencyAtMin`, `HPFFrequencyAtMax`, `FocusAzimuth`, `NonFocusAzimuth`, `FocusDistanceScale`, `NonFocusDistanceScale`, `FocusPriorityScale`, `NonFocusPriorityScale`, `FocusVolumeAttenuation`, `NonFocusVolumeAttenuation`, `FocusAttackInterpSpeed`, `FocusReleaseInterpSpeed`, `OcclusionLowPassFilterFrequency`, `OcclusionVolumeAttenuation`, `OcclusionInterpolationTime`, `OcclusionPluginSettings`, `ReverbPluginSettings`, `ReverbWetLevelMin`, `ReverbWetLevelMax`, `ReverbDistanceMin`, `ReverbDistanceMax`, `ManualReverbSendLevel`, `CustomReverbSendCurve`, `PluginSettings`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bAttenuate` | `boolean` |
| `bSpatialize` | `boolean` |
| `bAttenuateWithLPF` | `boolean` |
| `bEnableListenerFocus` | `boolean` |
| `bEnableFocusInterpolation` | `boolean` |
| `bEnableOcclusion` | `boolean` |
| `bUseComplexCollisionForOcclusion` | `boolean` |
| `bEnableReverbSend` | `boolean` |
| `bApplyNormalizationToStereoSounds` | `boolean` |
| `bEnableLogFrequencyScaling` | `boolean` |
| `SpatializationAlgorithm` | [`ESoundSpatializationAlgorithm`](../enums/ue_ue.ESoundSpatializationAlgorithm.md) |
| `BinauralRadius` | `number` |
| `AbsorptionMethod` | [`EAirAbsorptionMethod`](../enums/ue_ue.EAirAbsorptionMethod.md) |
| `OcclusionTraceChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `ReverbSendMethod` | [`EReverbSendMethod`](../enums/ue_ue.EReverbSendMethod.md) |
| `DistanceType` | [`ESoundDistanceCalc`](../enums/ue_ue.ESoundDistanceCalc.md) |
| `OmniRadius` | `number` |
| `StereoSpread` | `number` |
| `SpatializationPluginSettings` | [`SpatializationPluginSourceSettingsBase`](ue_ue.SpatializationPluginSourceSettingsBase.md) |
| `RadiusMin` | `number` |
| `RadiusMax` | `number` |
| `LPFRadiusMin` | `number` |
| `LPFRadiusMax` | `number` |
| `CustomLowpassAirAbsorptionCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |
| `CustomHighpassAirAbsorptionCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |
| `LPFFrequencyAtMin` | `number` |
| `LPFFrequencyAtMax` | `number` |
| `HPFFrequencyAtMin` | `number` |
| `HPFFrequencyAtMax` | `number` |
| `FocusAzimuth` | `number` |
| `NonFocusAzimuth` | `number` |
| `FocusDistanceScale` | `number` |
| `NonFocusDistanceScale` | `number` |
| `FocusPriorityScale` | `number` |
| `NonFocusPriorityScale` | `number` |
| `FocusVolumeAttenuation` | `number` |
| `NonFocusVolumeAttenuation` | `number` |
| `FocusAttackInterpSpeed` | `number` |
| `FocusReleaseInterpSpeed` | `number` |
| `OcclusionLowPassFilterFrequency` | `number` |
| `OcclusionVolumeAttenuation` | `number` |
| `OcclusionInterpolationTime` | `number` |
| `OcclusionPluginSettings` | [`OcclusionPluginSourceSettingsBase`](ue_ue.OcclusionPluginSourceSettingsBase.md) |
| `ReverbPluginSettings` | [`ReverbPluginSourceSettingsBase`](ue_ue.ReverbPluginSourceSettingsBase.md) |
| `ReverbWetLevelMin` | `number` |
| `ReverbWetLevelMax` | `number` |
| `ReverbDistanceMin` | `number` |
| `ReverbDistanceMax` | `number` |
| `ManualReverbSendLevel` | `number` |
| `CustomReverbSendCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |
| `PluginSettings` | [`SoundAttenuationPluginSettings`](ue_ue.SoundAttenuationPluginSettings.md) |

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[constructor](ue_ue.BaseAttenuationSettings.md#constructor)

## Properties

### AbsorptionMethod

• **AbsorptionMethod**: [`EAirAbsorptionMethod`](../enums/ue_ue.EAirAbsorptionMethod.md)

___

### AttenuationShape

• **AttenuationShape**: [`EAttenuationShape`](../enums/ue_ue.EAttenuationShape.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[AttenuationShape](ue_ue.BaseAttenuationSettings.md#attenuationshape)

___

### AttenuationShapeExtents

• **AttenuationShapeExtents**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[AttenuationShapeExtents](ue_ue.BaseAttenuationSettings.md#attenuationshapeextents)

___

### BinauralRadius

• **BinauralRadius**: `number`

___

### ConeOffset

• **ConeOffset**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[ConeOffset](ue_ue.BaseAttenuationSettings.md#coneoffset)

___

### CustomAttenuationCurve

• **CustomAttenuationCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[CustomAttenuationCurve](ue_ue.BaseAttenuationSettings.md#customattenuationcurve)

___

### CustomHighpassAirAbsorptionCurve

• **CustomHighpassAirAbsorptionCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### CustomLowpassAirAbsorptionCurve

• **CustomLowpassAirAbsorptionCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### CustomReverbSendCurve

• **CustomReverbSendCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### DistanceAlgorithm

• **DistanceAlgorithm**: [`EAttenuationDistanceModel`](../enums/ue_ue.EAttenuationDistanceModel.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[DistanceAlgorithm](ue_ue.BaseAttenuationSettings.md#distancealgorithm)

___

### DistanceType

• **DistanceType**: [`ESoundDistanceCalc`](../enums/ue_ue.ESoundDistanceCalc.md)

___

### FalloffDistance

• **FalloffDistance**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[FalloffDistance](ue_ue.BaseAttenuationSettings.md#falloffdistance)

___

### FocusAttackInterpSpeed

• **FocusAttackInterpSpeed**: `number`

___

### FocusAzimuth

• **FocusAzimuth**: `number`

___

### FocusDistanceScale

• **FocusDistanceScale**: `number`

___

### FocusPriorityScale

• **FocusPriorityScale**: `number`

___

### FocusReleaseInterpSpeed

• **FocusReleaseInterpSpeed**: `number`

___

### FocusVolumeAttenuation

• **FocusVolumeAttenuation**: `number`

___

### HPFFrequencyAtMax

• **HPFFrequencyAtMax**: `number`

___

### HPFFrequencyAtMin

• **HPFFrequencyAtMin**: `number`

___

### LPFFrequencyAtMax

• **LPFFrequencyAtMax**: `number`

___

### LPFFrequencyAtMin

• **LPFFrequencyAtMin**: `number`

___

### LPFRadiusMax

• **LPFRadiusMax**: `number`

___

### LPFRadiusMin

• **LPFRadiusMin**: `number`

___

### ManualReverbSendLevel

• **ManualReverbSendLevel**: `number`

___

### NonFocusAzimuth

• **NonFocusAzimuth**: `number`

___

### NonFocusDistanceScale

• **NonFocusDistanceScale**: `number`

___

### NonFocusPriorityScale

• **NonFocusPriorityScale**: `number`

___

### NonFocusVolumeAttenuation

• **NonFocusVolumeAttenuation**: `number`

___

### OcclusionInterpolationTime

• **OcclusionInterpolationTime**: `number`

___

### OcclusionLowPassFilterFrequency

• **OcclusionLowPassFilterFrequency**: `number`

___

### OcclusionPluginSettings

• **OcclusionPluginSettings**: [`OcclusionPluginSourceSettingsBase`](ue_ue.OcclusionPluginSourceSettingsBase.md)

___

### OcclusionTraceChannel

• **OcclusionTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### OcclusionVolumeAttenuation

• **OcclusionVolumeAttenuation**: `number`

___

### OmniRadius

• **OmniRadius**: `number`

___

### PluginSettings

• **PluginSettings**: [`SoundAttenuationPluginSettings`](ue_ue.SoundAttenuationPluginSettings.md)

___

### RadiusMax

• **RadiusMax**: `number`

___

### RadiusMin

• **RadiusMin**: `number`

___

### ReverbDistanceMax

• **ReverbDistanceMax**: `number`

___

### ReverbDistanceMin

• **ReverbDistanceMin**: `number`

___

### ReverbPluginSettings

• **ReverbPluginSettings**: [`ReverbPluginSourceSettingsBase`](ue_ue.ReverbPluginSourceSettingsBase.md)

___

### ReverbSendMethod

• **ReverbSendMethod**: [`EReverbSendMethod`](../enums/ue_ue.EReverbSendMethod.md)

___

### ReverbWetLevelMax

• **ReverbWetLevelMax**: `number`

___

### ReverbWetLevelMin

• **ReverbWetLevelMin**: `number`

___

### SpatializationAlgorithm

• **SpatializationAlgorithm**: [`ESoundSpatializationAlgorithm`](../enums/ue_ue.ESoundSpatializationAlgorithm.md)

___

### SpatializationPluginSettings

• **SpatializationPluginSettings**: [`SpatializationPluginSourceSettingsBase`](ue_ue.SpatializationPluginSourceSettingsBase.md)

___

### StereoSpread

• **StereoSpread**: `number`

___

### \_\_tid\_SoundAttenuationSettings\_\_

• `Private` **\_\_tid\_SoundAttenuationSettings\_\_**: `boolean`

___

### bApplyNormalizationToStereoSounds

• **bApplyNormalizationToStereoSounds**: `boolean`

___

### bAttenuate

• **bAttenuate**: `boolean`

___

### bAttenuateWithLPF

• **bAttenuateWithLPF**: `boolean`

___

### bEnableFocusInterpolation

• **bEnableFocusInterpolation**: `boolean`

___

### bEnableListenerFocus

• **bEnableListenerFocus**: `boolean`

___

### bEnableLogFrequencyScaling

• **bEnableLogFrequencyScaling**: `boolean`

___

### bEnableOcclusion

• **bEnableOcclusion**: `boolean`

___

### bEnableReverbSend

• **bEnableReverbSend**: `boolean`

___

### bSpatialize

• **bSpatialize**: `boolean`

___

### bUseComplexCollisionForOcclusion

• **bUseComplexCollisionForOcclusion**: `boolean`

___

### dBAttenuationAtMax

• **dBAttenuationAtMax**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[dBAttenuationAtMax](ue_ue.BaseAttenuationSettings.md#dbattenuationatmax)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[StaticClass](ue_ue.BaseAttenuationSettings.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[StaticStruct](ue_ue.BaseAttenuationSettings.md#staticstruct)
