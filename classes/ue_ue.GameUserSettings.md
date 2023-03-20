[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameUserSettings

# Class: GameUserSettings

[ue/ue](../modules/ue_ue.md).GameUserSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GameUserSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameUserSettings.md#constructor)

### Properties

- [AudioQualityLevel](ue_ue.GameUserSettings.md#audioqualitylevel)
- [DesiredScreenHeight](ue_ue.GameUserSettings.md#desiredscreenheight)
- [DesiredScreenWidth](ue_ue.GameUserSettings.md#desiredscreenwidth)
- [FrameRateLimit](ue_ue.GameUserSettings.md#frameratelimit)
- [FullscreenMode](ue_ue.GameUserSettings.md#fullscreenmode)
- [HDRDisplayOutputNits](ue_ue.GameUserSettings.md#hdrdisplayoutputnits)
- [LastCPUBenchmarkResult](ue_ue.GameUserSettings.md#lastcpubenchmarkresult)
- [LastCPUBenchmarkSteps](ue_ue.GameUserSettings.md#lastcpubenchmarksteps)
- [LastConfirmedAudioQualityLevel](ue_ue.GameUserSettings.md#lastconfirmedaudioqualitylevel)
- [LastConfirmedFullscreenMode](ue_ue.GameUserSettings.md#lastconfirmedfullscreenmode)
- [LastGPUBenchmarkMultiplier](ue_ue.GameUserSettings.md#lastgpubenchmarkmultiplier)
- [LastGPUBenchmarkResult](ue_ue.GameUserSettings.md#lastgpubenchmarkresult)
- [LastGPUBenchmarkSteps](ue_ue.GameUserSettings.md#lastgpubenchmarksteps)
- [LastRecommendedScreenHeight](ue_ue.GameUserSettings.md#lastrecommendedscreenheight)
- [LastRecommendedScreenWidth](ue_ue.GameUserSettings.md#lastrecommendedscreenwidth)
- [LastUserConfirmedDesiredScreenHeight](ue_ue.GameUserSettings.md#lastuserconfirmeddesiredscreenheight)
- [LastUserConfirmedDesiredScreenWidth](ue_ue.GameUserSettings.md#lastuserconfirmeddesiredscreenwidth)
- [LastUserConfirmedResolutionSizeX](ue_ue.GameUserSettings.md#lastuserconfirmedresolutionsizex)
- [LastUserConfirmedResolutionSizeY](ue_ue.GameUserSettings.md#lastuserconfirmedresolutionsizey)
- [OnGameUserSettingsUINeedsUpdate](ue_ue.GameUserSettings.md#ongameusersettingsuineedsupdate)
- [PreferredFullscreenMode](ue_ue.GameUserSettings.md#preferredfullscreenmode)
- [ResolutionSizeX](ue_ue.GameUserSettings.md#resolutionsizex)
- [ResolutionSizeY](ue_ue.GameUserSettings.md#resolutionsizey)
- [Version](ue_ue.GameUserSettings.md#version)
- [WindowPosX](ue_ue.GameUserSettings.md#windowposx)
- [WindowPosY](ue_ue.GameUserSettings.md#windowposy)
- [\_\_tid\_GameUserSettings\_\_](ue_ue.GameUserSettings.md#__tid_gameusersettings__)
- [\_\_tid\_Object\_\_](ue_ue.GameUserSettings.md#__tid_object__)
- [bUseDesiredScreenHeight](ue_ue.GameUserSettings.md#busedesiredscreenheight)
- [bUseDynamicResolution](ue_ue.GameUserSettings.md#busedynamicresolution)
- [bUseHDRDisplayOutput](ue_ue.GameUserSettings.md#busehdrdisplayoutput)
- [bUseVSync](ue_ue.GameUserSettings.md#busevsync)

### Methods

- [ApplyHardwareBenchmarkResults](ue_ue.GameUserSettings.md#applyhardwarebenchmarkresults)
- [ApplyNonResolutionSettings](ue_ue.GameUserSettings.md#applynonresolutionsettings)
- [ApplyResolutionSettings](ue_ue.GameUserSettings.md#applyresolutionsettings)
- [ApplySettings](ue_ue.GameUserSettings.md#applysettings)
- [ConfirmVideoMode](ue_ue.GameUserSettings.md#confirmvideomode)
- [CreateDefaultSubobject](ue_ue.GameUserSettings.md#createdefaultsubobject)
- [EnableHDRDisplayOutput](ue_ue.GameUserSettings.md#enablehdrdisplayoutput)
- [ExecuteUbergraph](ue_ue.GameUserSettings.md#executeubergraph)
- [GetAntiAliasingQuality](ue_ue.GameUserSettings.md#getantialiasingquality)
- [GetAudioQualityLevel](ue_ue.GameUserSettings.md#getaudioqualitylevel)
- [GetClass](ue_ue.GameUserSettings.md#getclass)
- [GetCurrentHDRDisplayNits](ue_ue.GameUserSettings.md#getcurrenthdrdisplaynits)
- [GetDefaultResolutionScale](ue_ue.GameUserSettings.md#getdefaultresolutionscale)
- [GetDesktopResolution](ue_ue.GameUserSettings.md#getdesktopresolution)
- [GetFoliageQuality](ue_ue.GameUserSettings.md#getfoliagequality)
- [GetFrameRateLimit](ue_ue.GameUserSettings.md#getframeratelimit)
- [GetFullscreenMode](ue_ue.GameUserSettings.md#getfullscreenmode)
- [GetLastConfirmedFullscreenMode](ue_ue.GameUserSettings.md#getlastconfirmedfullscreenmode)
- [GetLastConfirmedScreenResolution](ue_ue.GameUserSettings.md#getlastconfirmedscreenresolution)
- [GetName](ue_ue.GameUserSettings.md#getname)
- [GetOuter](ue_ue.GameUserSettings.md#getouter)
- [GetOverallScalabilityLevel](ue_ue.GameUserSettings.md#getoverallscalabilitylevel)
- [GetPostProcessingQuality](ue_ue.GameUserSettings.md#getpostprocessingquality)
- [GetPreferredFullscreenMode](ue_ue.GameUserSettings.md#getpreferredfullscreenmode)
- [GetRecommendedResolutionScale](ue_ue.GameUserSettings.md#getrecommendedresolutionscale)
- [GetResolutionScaleInformation](ue_ue.GameUserSettings.md#getresolutionscaleinformation)
- [GetResolutionScaleInformationEx](ue_ue.GameUserSettings.md#getresolutionscaleinformationex)
- [GetResolutionScaleNormalized](ue_ue.GameUserSettings.md#getresolutionscalenormalized)
- [GetScreenResolution](ue_ue.GameUserSettings.md#getscreenresolution)
- [GetShadingQuality](ue_ue.GameUserSettings.md#getshadingquality)
- [GetShadowQuality](ue_ue.GameUserSettings.md#getshadowquality)
- [GetTextureQuality](ue_ue.GameUserSettings.md#gettexturequality)
- [GetViewDistanceQuality](ue_ue.GameUserSettings.md#getviewdistancequality)
- [GetVisualEffectQuality](ue_ue.GameUserSettings.md#getvisualeffectquality)
- [GetWorld](ue_ue.GameUserSettings.md#getworld)
- [IsDirty](ue_ue.GameUserSettings.md#isdirty)
- [IsDynamicResolutionDirty](ue_ue.GameUserSettings.md#isdynamicresolutiondirty)
- [IsDynamicResolutionEnabled](ue_ue.GameUserSettings.md#isdynamicresolutionenabled)
- [IsFullscreenModeDirty](ue_ue.GameUserSettings.md#isfullscreenmodedirty)
- [IsHDREnabled](ue_ue.GameUserSettings.md#ishdrenabled)
- [IsScreenResolutionDirty](ue_ue.GameUserSettings.md#isscreenresolutiondirty)
- [IsVSyncDirty](ue_ue.GameUserSettings.md#isvsyncdirty)
- [IsVSyncEnabled](ue_ue.GameUserSettings.md#isvsyncenabled)
- [LoadSettings](ue_ue.GameUserSettings.md#loadsettings)
- [ResetToCurrentSettings](ue_ue.GameUserSettings.md#resettocurrentsettings)
- [RevertVideoMode](ue_ue.GameUserSettings.md#revertvideomode)
- [RunHardwareBenchmark](ue_ue.GameUserSettings.md#runhardwarebenchmark)
- [SaveSettings](ue_ue.GameUserSettings.md#savesettings)
- [SetAntiAliasingQuality](ue_ue.GameUserSettings.md#setantialiasingquality)
- [SetAudioQualityLevel](ue_ue.GameUserSettings.md#setaudioqualitylevel)
- [SetBenchmarkFallbackValues](ue_ue.GameUserSettings.md#setbenchmarkfallbackvalues)
- [SetDynamicResolutionEnabled](ue_ue.GameUserSettings.md#setdynamicresolutionenabled)
- [SetFoliageQuality](ue_ue.GameUserSettings.md#setfoliagequality)
- [SetFrameRateLimit](ue_ue.GameUserSettings.md#setframeratelimit)
- [SetFullscreenMode](ue_ue.GameUserSettings.md#setfullscreenmode)
- [SetOverallScalabilityLevel](ue_ue.GameUserSettings.md#setoverallscalabilitylevel)
- [SetPostProcessingQuality](ue_ue.GameUserSettings.md#setpostprocessingquality)
- [SetResolutionScaleNormalized](ue_ue.GameUserSettings.md#setresolutionscalenormalized)
- [SetResolutionScaleValue](ue_ue.GameUserSettings.md#setresolutionscalevalue)
- [SetResolutionScaleValueEx](ue_ue.GameUserSettings.md#setresolutionscalevalueex)
- [SetScreenResolution](ue_ue.GameUserSettings.md#setscreenresolution)
- [SetShadingQuality](ue_ue.GameUserSettings.md#setshadingquality)
- [SetShadowQuality](ue_ue.GameUserSettings.md#setshadowquality)
- [SetTextureQuality](ue_ue.GameUserSettings.md#settexturequality)
- [SetToDefaults](ue_ue.GameUserSettings.md#settodefaults)
- [SetVSyncEnabled](ue_ue.GameUserSettings.md#setvsyncenabled)
- [SetViewDistanceQuality](ue_ue.GameUserSettings.md#setviewdistancequality)
- [SetVisualEffectQuality](ue_ue.GameUserSettings.md#setvisualeffectquality)
- [SupportsHDRDisplayOutput](ue_ue.GameUserSettings.md#supportshdrdisplayoutput)
- [ValidateSettings](ue_ue.GameUserSettings.md#validatesettings)
- [Find](ue_ue.GameUserSettings.md#find)
- [GetDefaultResolution](ue_ue.GameUserSettings.md#getdefaultresolution)
- [GetDefaultWindowMode](ue_ue.GameUserSettings.md#getdefaultwindowmode)
- [GetDefaultWindowPosition](ue_ue.GameUserSettings.md#getdefaultwindowposition)
- [GetGameUserSettings](ue_ue.GameUserSettings.md#getgameusersettings)
- [GetSyncInterval](ue_ue.GameUserSettings.md#getsyncinterval)
- [Load](ue_ue.GameUserSettings.md#load)
- [StaticClass](ue_ue.GameUserSettings.md#staticclass)

## Constructors

### constructor

• **new GameUserSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:32404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32404)

## Properties

### AudioQualityLevel

• **AudioQualityLevel**: `number`

#### Defined in

[ue/ue.d.ts:32417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32417)

___

### DesiredScreenHeight

• **DesiredScreenHeight**: `number`

#### Defined in

[ue/ue.d.ts:32422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32422)

___

### DesiredScreenWidth

• **DesiredScreenWidth**: `number`

#### Defined in

[ue/ue.d.ts:32420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32420)

___

### FrameRateLimit

• **FrameRateLimit**: `number`

#### Defined in

[ue/ue.d.ts:32419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32419)

___

### FullscreenMode

• **FullscreenMode**: `number`

#### Defined in

[ue/ue.d.ts:32413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32413)

___

### HDRDisplayOutputNits

• **HDRDisplayOutputNits**: `number`

#### Defined in

[ue/ue.d.ts:32433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32433)

___

### LastCPUBenchmarkResult

• **LastCPUBenchmarkResult**: `number`

#### Defined in

[ue/ue.d.ts:32427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32427)

___

### LastCPUBenchmarkSteps

• **LastCPUBenchmarkSteps**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:32429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32429)

___

### LastConfirmedAudioQualityLevel

• **LastConfirmedAudioQualityLevel**: `number`

#### Defined in

[ue/ue.d.ts:32418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32418)

___

### LastConfirmedFullscreenMode

• **LastConfirmedFullscreenMode**: `number`

#### Defined in

[ue/ue.d.ts:32414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32414)

___

### LastGPUBenchmarkMultiplier

• **LastGPUBenchmarkMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:32431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32431)

___

### LastGPUBenchmarkResult

• **LastGPUBenchmarkResult**: `number`

#### Defined in

[ue/ue.d.ts:32428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32428)

___

### LastGPUBenchmarkSteps

• **LastGPUBenchmarkSteps**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:32430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32430)

___

### LastRecommendedScreenHeight

• **LastRecommendedScreenHeight**: `number`

#### Defined in

[ue/ue.d.ts:32426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32426)

___

### LastRecommendedScreenWidth

• **LastRecommendedScreenWidth**: `number`

#### Defined in

[ue/ue.d.ts:32425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32425)

___

### LastUserConfirmedDesiredScreenHeight

• **LastUserConfirmedDesiredScreenHeight**: `number`

#### Defined in

[ue/ue.d.ts:32424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32424)

___

### LastUserConfirmedDesiredScreenWidth

• **LastUserConfirmedDesiredScreenWidth**: `number`

#### Defined in

[ue/ue.d.ts:32423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32423)

___

### LastUserConfirmedResolutionSizeX

• **LastUserConfirmedResolutionSizeX**: `number`

#### Defined in

[ue/ue.d.ts:32409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32409)

___

### LastUserConfirmedResolutionSizeY

• **LastUserConfirmedResolutionSizeY**: `number`

#### Defined in

[ue/ue.d.ts:32410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32410)

___

### OnGameUserSettingsUINeedsUpdate

• **OnGameUserSettingsUINeedsUpdate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:32434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32434)

___

### PreferredFullscreenMode

• **PreferredFullscreenMode**: `number`

#### Defined in

[ue/ue.d.ts:32415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32415)

___

### ResolutionSizeX

• **ResolutionSizeX**: `number`

#### Defined in

[ue/ue.d.ts:32407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32407)

___

### ResolutionSizeY

• **ResolutionSizeY**: `number`

#### Defined in

[ue/ue.d.ts:32408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32408)

___

### Version

• **Version**: `number`

#### Defined in

[ue/ue.d.ts:32416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32416)

___

### WindowPosX

• **WindowPosX**: `number`

#### Defined in

[ue/ue.d.ts:32411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32411)

___

### WindowPosY

• **WindowPosY**: `number`

#### Defined in

[ue/ue.d.ts:32412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32412)

___

### \_\_tid\_GameUserSettings\_\_

• **\_\_tid\_GameUserSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:32508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32508)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bUseDesiredScreenHeight

• **bUseDesiredScreenHeight**: `boolean`

#### Defined in

[ue/ue.d.ts:32421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32421)

___

### bUseDynamicResolution

• **bUseDynamicResolution**: `boolean`

#### Defined in

[ue/ue.d.ts:32406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32406)

___

### bUseHDRDisplayOutput

• **bUseHDRDisplayOutput**: `boolean`

#### Defined in

[ue/ue.d.ts:32432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32432)

___

### bUseVSync

• **bUseVSync**: `boolean`

#### Defined in

[ue/ue.d.ts:32405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32405)

## Methods

### ApplyHardwareBenchmarkResults

▸ **ApplyHardwareBenchmarkResults**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32435](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32435)

___

### ApplyNonResolutionSettings

▸ **ApplyNonResolutionSettings**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32436)

___

### ApplyResolutionSettings

▸ **ApplyResolutionSettings**(`bCheckForCommandLineOverrides`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bCheckForCommandLineOverrides` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32437)

___

### ApplySettings

▸ **ApplySettings**(`bCheckForCommandLineOverrides`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bCheckForCommandLineOverrides` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32438)

___

### ConfirmVideoMode

▸ **ConfirmVideoMode**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32439)

___

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### EnableHDRDisplayOutput

▸ **EnableHDRDisplayOutput**(`bEnable`, `DisplayNits?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |
| `DisplayNits?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32440)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetAntiAliasingQuality

▸ **GetAntiAliasingQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32441)

___

### GetAudioQualityLevel

▸ **GetAudioQualityLevel**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32442)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetCurrentHDRDisplayNits

▸ **GetCurrentHDRDisplayNits**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32443)

___

### GetDefaultResolutionScale

▸ **GetDefaultResolutionScale**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32444)

___

### GetDesktopResolution

▸ **GetDesktopResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:32445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32445)

___

### GetFoliageQuality

▸ **GetFoliageQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32446)

___

### GetFrameRateLimit

▸ **GetFrameRateLimit**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32447)

___

### GetFullscreenMode

▸ **GetFullscreenMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Defined in

[ue/ue.d.ts:32448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32448)

___

### GetLastConfirmedFullscreenMode

▸ **GetLastConfirmedFullscreenMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Defined in

[ue/ue.d.ts:32449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32449)

___

### GetLastConfirmedScreenResolution

▸ **GetLastConfirmedScreenResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:32450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32450)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOverallScalabilityLevel

▸ **GetOverallScalabilityLevel**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32451)

___

### GetPostProcessingQuality

▸ **GetPostProcessingQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32452)

___

### GetPreferredFullscreenMode

▸ **GetPreferredFullscreenMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Defined in

[ue/ue.d.ts:32453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32453)

___

### GetRecommendedResolutionScale

▸ **GetRecommendedResolutionScale**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32454)

___

### GetResolutionScaleInformation

▸ **GetResolutionScaleInformation**(`CurrentScaleNormalized`, `CurrentScaleValue`, `MinScaleValue`, `MaxScaleValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurrentScaleNormalized` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `CurrentScaleValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `MinScaleValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `MaxScaleValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32455)

___

### GetResolutionScaleInformationEx

▸ **GetResolutionScaleInformationEx**(`CurrentScaleNormalized`, `CurrentScaleValue`, `MinScaleValue`, `MaxScaleValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurrentScaleNormalized` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `CurrentScaleValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `MinScaleValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `MaxScaleValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32456)

___

### GetResolutionScaleNormalized

▸ **GetResolutionScaleNormalized**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32457](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32457)

___

### GetScreenResolution

▸ **GetScreenResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:32458](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32458)

___

### GetShadingQuality

▸ **GetShadingQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32459)

___

### GetShadowQuality

▸ **GetShadowQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32460)

___

### GetTextureQuality

▸ **GetTextureQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32461)

___

### GetViewDistanceQuality

▸ **GetViewDistanceQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32462)

___

### GetVisualEffectQuality

▸ **GetVisualEffectQuality**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32463)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsDirty

▸ **IsDirty**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32464](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32464)

___

### IsDynamicResolutionDirty

▸ **IsDynamicResolutionDirty**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32465)

___

### IsDynamicResolutionEnabled

▸ **IsDynamicResolutionEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32466)

___

### IsFullscreenModeDirty

▸ **IsFullscreenModeDirty**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32467)

___

### IsHDREnabled

▸ **IsHDREnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32468)

___

### IsScreenResolutionDirty

▸ **IsScreenResolutionDirty**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32469](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32469)

___

### IsVSyncDirty

▸ **IsVSyncDirty**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32470)

___

### IsVSyncEnabled

▸ **IsVSyncEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32471)

___

### LoadSettings

▸ **LoadSettings**(`bForceReload?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bForceReload?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32472)

___

### ResetToCurrentSettings

▸ **ResetToCurrentSettings**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32473)

___

### RevertVideoMode

▸ **RevertVideoMode**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32474)

___

### RunHardwareBenchmark

▸ **RunHardwareBenchmark**(`WorkScale?`, `CPUMultiplier?`, `GPUMultiplier?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorkScale?` | `number` |
| `CPUMultiplier?` | `number` |
| `GPUMultiplier?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32475)

___

### SaveSettings

▸ **SaveSettings**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32476)

___

### SetAntiAliasingQuality

▸ **SetAntiAliasingQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32477)

___

### SetAudioQualityLevel

▸ **SetAudioQualityLevel**(`QualityLevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QualityLevel` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32478)

___

### SetBenchmarkFallbackValues

▸ **SetBenchmarkFallbackValues**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32479)

___

### SetDynamicResolutionEnabled

▸ **SetDynamicResolutionEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32480)

___

### SetFoliageQuality

▸ **SetFoliageQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32481)

___

### SetFrameRateLimit

▸ **SetFrameRateLimit**(`NewLimit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLimit` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32482)

___

### SetFullscreenMode

▸ **SetFullscreenMode**(`InFullscreenMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFullscreenMode` | [`EWindowMode`](../enums/ue_ue.EWindowMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32483)

___

### SetOverallScalabilityLevel

▸ **SetOverallScalabilityLevel**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32484)

___

### SetPostProcessingQuality

▸ **SetPostProcessingQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32485)

___

### SetResolutionScaleNormalized

▸ **SetResolutionScaleNormalized**(`NewScaleNormalized`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScaleNormalized` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32486)

___

### SetResolutionScaleValue

▸ **SetResolutionScaleValue**(`NewScaleValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScaleValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32487)

___

### SetResolutionScaleValueEx

▸ **SetResolutionScaleValueEx**(`NewScaleValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScaleValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32488)

___

### SetScreenResolution

▸ **SetScreenResolution**(`Resolution`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Resolution` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32489)

___

### SetShadingQuality

▸ **SetShadingQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32490)

___

### SetShadowQuality

▸ **SetShadowQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32491)

___

### SetTextureQuality

▸ **SetTextureQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32492)

___

### SetToDefaults

▸ **SetToDefaults**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32493)

___

### SetVSyncEnabled

▸ **SetVSyncEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32496)

___

### SetViewDistanceQuality

▸ **SetViewDistanceQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32494)

___

### SetVisualEffectQuality

▸ **SetVisualEffectQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32495)

___

### SupportsHDRDisplayOutput

▸ **SupportsHDRDisplayOutput**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32497)

___

### ValidateSettings

▸ **ValidateSettings**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32498)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:32505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32505)

___

### GetDefaultResolution

▸ `Static` **GetDefaultResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:32499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32499)

___

### GetDefaultWindowMode

▸ `Static` **GetDefaultWindowMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Defined in

[ue/ue.d.ts:32500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32500)

___

### GetDefaultWindowPosition

▸ `Static` **GetDefaultWindowPosition**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:32501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32501)

___

### GetGameUserSettings

▸ `Static` **GetGameUserSettings**(): [`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Returns

[`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Defined in

[ue/ue.d.ts:32502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32502)

___

### GetSyncInterval

▸ `Static` **GetSyncInterval**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32503)

___

### Load

▸ `Static` **Load**(`InName`): [`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:32506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32506)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:32504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32504)
