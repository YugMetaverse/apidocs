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

#### Defined in

[ue/ue.d.ts:9404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9404)

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

#### Defined in

[ue/ue.d.ts:9405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9405)

## Properties

### AbsorptionMethod

• **AbsorptionMethod**: [`EAirAbsorptionMethod`](../enums/ue_ue.EAirAbsorptionMethod.md)

#### Defined in

[ue/ue.d.ts:9418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9418)

___

### AttenuationShape

• **AttenuationShape**: [`EAttenuationShape`](../enums/ue_ue.EAttenuationShape.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[AttenuationShape](ue_ue.BaseAttenuationSettings.md#attenuationshape)

#### Defined in

[ue/ue.d.ts:9344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9344)

___

### AttenuationShapeExtents

• **AttenuationShapeExtents**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[AttenuationShapeExtents](ue_ue.BaseAttenuationSettings.md#attenuationshapeextents)

#### Defined in

[ue/ue.d.ts:9346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9346)

___

### BinauralRadius

• **BinauralRadius**: `number`

#### Defined in

[ue/ue.d.ts:9417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9417)

___

### ConeOffset

• **ConeOffset**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[ConeOffset](ue_ue.BaseAttenuationSettings.md#coneoffset)

#### Defined in

[ue/ue.d.ts:9347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9347)

___

### CustomAttenuationCurve

• **CustomAttenuationCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[CustomAttenuationCurve](ue_ue.BaseAttenuationSettings.md#customattenuationcurve)

#### Defined in

[ue/ue.d.ts:9349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9349)

___

### CustomHighpassAirAbsorptionCurve

• **CustomHighpassAirAbsorptionCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:9430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9430)

___

### CustomLowpassAirAbsorptionCurve

• **CustomLowpassAirAbsorptionCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:9429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9429)

___

### CustomReverbSendCurve

• **CustomReverbSendCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:9455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9455)

___

### DistanceAlgorithm

• **DistanceAlgorithm**: [`EAttenuationDistanceModel`](../enums/ue_ue.EAttenuationDistanceModel.md)

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[DistanceAlgorithm](ue_ue.BaseAttenuationSettings.md#distancealgorithm)

#### Defined in

[ue/ue.d.ts:9343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9343)

___

### DistanceType

• **DistanceType**: [`ESoundDistanceCalc`](../enums/ue_ue.ESoundDistanceCalc.md)

#### Defined in

[ue/ue.d.ts:9421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9421)

___

### FalloffDistance

• **FalloffDistance**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[FalloffDistance](ue_ue.BaseAttenuationSettings.md#falloffdistance)

#### Defined in

[ue/ue.d.ts:9348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9348)

___

### FocusAttackInterpSpeed

• **FocusAttackInterpSpeed**: `number`

#### Defined in

[ue/ue.d.ts:9443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9443)

___

### FocusAzimuth

• **FocusAzimuth**: `number`

#### Defined in

[ue/ue.d.ts:9435](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9435)

___

### FocusDistanceScale

• **FocusDistanceScale**: `number`

#### Defined in

[ue/ue.d.ts:9437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9437)

___

### FocusPriorityScale

• **FocusPriorityScale**: `number`

#### Defined in

[ue/ue.d.ts:9439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9439)

___

### FocusReleaseInterpSpeed

• **FocusReleaseInterpSpeed**: `number`

#### Defined in

[ue/ue.d.ts:9444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9444)

___

### FocusVolumeAttenuation

• **FocusVolumeAttenuation**: `number`

#### Defined in

[ue/ue.d.ts:9441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9441)

___

### HPFFrequencyAtMax

• **HPFFrequencyAtMax**: `number`

#### Defined in

[ue/ue.d.ts:9434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9434)

___

### HPFFrequencyAtMin

• **HPFFrequencyAtMin**: `number`

#### Defined in

[ue/ue.d.ts:9433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9433)

___

### LPFFrequencyAtMax

• **LPFFrequencyAtMax**: `number`

#### Defined in

[ue/ue.d.ts:9432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9432)

___

### LPFFrequencyAtMin

• **LPFFrequencyAtMin**: `number`

#### Defined in

[ue/ue.d.ts:9431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9431)

___

### LPFRadiusMax

• **LPFRadiusMax**: `number`

#### Defined in

[ue/ue.d.ts:9428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9428)

___

### LPFRadiusMin

• **LPFRadiusMin**: `number`

#### Defined in

[ue/ue.d.ts:9427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9427)

___

### ManualReverbSendLevel

• **ManualReverbSendLevel**: `number`

#### Defined in

[ue/ue.d.ts:9454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9454)

___

### NonFocusAzimuth

• **NonFocusAzimuth**: `number`

#### Defined in

[ue/ue.d.ts:9436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9436)

___

### NonFocusDistanceScale

• **NonFocusDistanceScale**: `number`

#### Defined in

[ue/ue.d.ts:9438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9438)

___

### NonFocusPriorityScale

• **NonFocusPriorityScale**: `number`

#### Defined in

[ue/ue.d.ts:9440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9440)

___

### NonFocusVolumeAttenuation

• **NonFocusVolumeAttenuation**: `number`

#### Defined in

[ue/ue.d.ts:9442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9442)

___

### OcclusionInterpolationTime

• **OcclusionInterpolationTime**: `number`

#### Defined in

[ue/ue.d.ts:9447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9447)

___

### OcclusionLowPassFilterFrequency

• **OcclusionLowPassFilterFrequency**: `number`

#### Defined in

[ue/ue.d.ts:9445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9445)

___

### OcclusionPluginSettings

• **OcclusionPluginSettings**: [`OcclusionPluginSourceSettingsBase`](ue_ue.OcclusionPluginSourceSettingsBase.md)

#### Defined in

[ue/ue.d.ts:9448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9448)

___

### OcclusionTraceChannel

• **OcclusionTraceChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:9419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9419)

___

### OcclusionVolumeAttenuation

• **OcclusionVolumeAttenuation**: `number`

#### Defined in

[ue/ue.d.ts:9446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9446)

___

### OmniRadius

• **OmniRadius**: `number`

#### Defined in

[ue/ue.d.ts:9422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9422)

___

### PluginSettings

• **PluginSettings**: [`SoundAttenuationPluginSettings`](ue_ue.SoundAttenuationPluginSettings.md)

#### Defined in

[ue/ue.d.ts:9456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9456)

___

### RadiusMax

• **RadiusMax**: `number`

#### Defined in

[ue/ue.d.ts:9426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9426)

___

### RadiusMin

• **RadiusMin**: `number`

#### Defined in

[ue/ue.d.ts:9425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9425)

___

### ReverbDistanceMax

• **ReverbDistanceMax**: `number`

#### Defined in

[ue/ue.d.ts:9453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9453)

___

### ReverbDistanceMin

• **ReverbDistanceMin**: `number`

#### Defined in

[ue/ue.d.ts:9452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9452)

___

### ReverbPluginSettings

• **ReverbPluginSettings**: [`ReverbPluginSourceSettingsBase`](ue_ue.ReverbPluginSourceSettingsBase.md)

#### Defined in

[ue/ue.d.ts:9449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9449)

___

### ReverbSendMethod

• **ReverbSendMethod**: [`EReverbSendMethod`](../enums/ue_ue.EReverbSendMethod.md)

#### Defined in

[ue/ue.d.ts:9420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9420)

___

### ReverbWetLevelMax

• **ReverbWetLevelMax**: `number`

#### Defined in

[ue/ue.d.ts:9451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9451)

___

### ReverbWetLevelMin

• **ReverbWetLevelMin**: `number`

#### Defined in

[ue/ue.d.ts:9450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9450)

___

### SpatializationAlgorithm

• **SpatializationAlgorithm**: [`ESoundSpatializationAlgorithm`](../enums/ue_ue.ESoundSpatializationAlgorithm.md)

#### Defined in

[ue/ue.d.ts:9416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9416)

___

### SpatializationPluginSettings

• **SpatializationPluginSettings**: [`SpatializationPluginSourceSettingsBase`](ue_ue.SpatializationPluginSourceSettingsBase.md)

#### Defined in

[ue/ue.d.ts:9424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9424)

___

### StereoSpread

• **StereoSpread**: `number`

#### Defined in

[ue/ue.d.ts:9423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9423)

___

### \_\_tid\_SoundAttenuationSettings\_\_

• `Private` **\_\_tid\_SoundAttenuationSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9462)

___

### bApplyNormalizationToStereoSounds

• **bApplyNormalizationToStereoSounds**: `boolean`

#### Defined in

[ue/ue.d.ts:9414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9414)

___

### bAttenuate

• **bAttenuate**: `boolean`

#### Defined in

[ue/ue.d.ts:9406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9406)

___

### bAttenuateWithLPF

• **bAttenuateWithLPF**: `boolean`

#### Defined in

[ue/ue.d.ts:9408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9408)

___

### bEnableFocusInterpolation

• **bEnableFocusInterpolation**: `boolean`

#### Defined in

[ue/ue.d.ts:9410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9410)

___

### bEnableListenerFocus

• **bEnableListenerFocus**: `boolean`

#### Defined in

[ue/ue.d.ts:9409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9409)

___

### bEnableLogFrequencyScaling

• **bEnableLogFrequencyScaling**: `boolean`

#### Defined in

[ue/ue.d.ts:9415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9415)

___

### bEnableOcclusion

• **bEnableOcclusion**: `boolean`

#### Defined in

[ue/ue.d.ts:9411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9411)

___

### bEnableReverbSend

• **bEnableReverbSend**: `boolean`

#### Defined in

[ue/ue.d.ts:9413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9413)

___

### bSpatialize

• **bSpatialize**: `boolean`

#### Defined in

[ue/ue.d.ts:9407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9407)

___

### bUseComplexCollisionForOcclusion

• **bUseComplexCollisionForOcclusion**: `boolean`

#### Defined in

[ue/ue.d.ts:9412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9412)

___

### dBAttenuationAtMax

• **dBAttenuationAtMax**: `number`

#### Inherited from

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[dBAttenuationAtMax](ue_ue.BaseAttenuationSettings.md#dbattenuationatmax)

#### Defined in

[ue/ue.d.ts:9345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9345)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[StaticClass](ue_ue.BaseAttenuationSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:9460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9460)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[BaseAttenuationSettings](ue_ue.BaseAttenuationSettings.md).[StaticStruct](ue_ue.BaseAttenuationSettings.md#staticstruct)

#### Defined in

[ue/ue.d.ts:9461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9461)
