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

## Properties

### AudioQualityLevel

• **AudioQualityLevel**: `number`

___

### DesiredScreenHeight

• **DesiredScreenHeight**: `number`

___

### DesiredScreenWidth

• **DesiredScreenWidth**: `number`

___

### FrameRateLimit

• **FrameRateLimit**: `number`

___

### FullscreenMode

• **FullscreenMode**: `number`

___

### HDRDisplayOutputNits

• **HDRDisplayOutputNits**: `number`

___

### LastCPUBenchmarkResult

• **LastCPUBenchmarkResult**: `number`

___

### LastCPUBenchmarkSteps

• **LastCPUBenchmarkSteps**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### LastConfirmedAudioQualityLevel

• **LastConfirmedAudioQualityLevel**: `number`

___

### LastConfirmedFullscreenMode

• **LastConfirmedFullscreenMode**: `number`

___

### LastGPUBenchmarkMultiplier

• **LastGPUBenchmarkMultiplier**: `number`

___

### LastGPUBenchmarkResult

• **LastGPUBenchmarkResult**: `number`

___

### LastGPUBenchmarkSteps

• **LastGPUBenchmarkSteps**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### LastRecommendedScreenHeight

• **LastRecommendedScreenHeight**: `number`

___

### LastRecommendedScreenWidth

• **LastRecommendedScreenWidth**: `number`

___

### LastUserConfirmedDesiredScreenHeight

• **LastUserConfirmedDesiredScreenHeight**: `number`

___

### LastUserConfirmedDesiredScreenWidth

• **LastUserConfirmedDesiredScreenWidth**: `number`

___

### LastUserConfirmedResolutionSizeX

• **LastUserConfirmedResolutionSizeX**: `number`

___

### LastUserConfirmedResolutionSizeY

• **LastUserConfirmedResolutionSizeY**: `number`

___

### OnGameUserSettingsUINeedsUpdate

• **OnGameUserSettingsUINeedsUpdate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### PreferredFullscreenMode

• **PreferredFullscreenMode**: `number`

___

### ResolutionSizeX

• **ResolutionSizeX**: `number`

___

### ResolutionSizeY

• **ResolutionSizeY**: `number`

___

### Version

• **Version**: `number`

___

### WindowPosX

• **WindowPosX**: `number`

___

### WindowPosY

• **WindowPosY**: `number`

___

### \_\_tid\_GameUserSettings\_\_

• **\_\_tid\_GameUserSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bUseDesiredScreenHeight

• **bUseDesiredScreenHeight**: `boolean`

___

### bUseDynamicResolution

• **bUseDynamicResolution**: `boolean`

___

### bUseHDRDisplayOutput

• **bUseHDRDisplayOutput**: `boolean`

___

### bUseVSync

• **bUseVSync**: `boolean`

## Methods

### ApplyHardwareBenchmarkResults

▸ **ApplyHardwareBenchmarkResults**(): `void`

#### Returns

`void`

___

### ApplyNonResolutionSettings

▸ **ApplyNonResolutionSettings**(): `void`

#### Returns

`void`

___

### ApplyResolutionSettings

▸ **ApplyResolutionSettings**(`bCheckForCommandLineOverrides`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bCheckForCommandLineOverrides` | `boolean` |

#### Returns

`void`

___

### ApplySettings

▸ **ApplySettings**(`bCheckForCommandLineOverrides`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bCheckForCommandLineOverrides` | `boolean` |

#### Returns

`void`

___

### ConfirmVideoMode

▸ **ConfirmVideoMode**(): `void`

#### Returns

`void`

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

### GetAntiAliasingQuality

▸ **GetAntiAliasingQuality**(): `number`

#### Returns

`number`

___

### GetAudioQualityLevel

▸ **GetAudioQualityLevel**(): `number`

#### Returns

`number`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetCurrentHDRDisplayNits

▸ **GetCurrentHDRDisplayNits**(): `number`

#### Returns

`number`

___

### GetDefaultResolutionScale

▸ **GetDefaultResolutionScale**(): `number`

#### Returns

`number`

___

### GetDesktopResolution

▸ **GetDesktopResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### GetFoliageQuality

▸ **GetFoliageQuality**(): `number`

#### Returns

`number`

___

### GetFrameRateLimit

▸ **GetFrameRateLimit**(): `number`

#### Returns

`number`

___

### GetFullscreenMode

▸ **GetFullscreenMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

___

### GetLastConfirmedFullscreenMode

▸ **GetLastConfirmedFullscreenMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

___

### GetLastConfirmedScreenResolution

▸ **GetLastConfirmedScreenResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

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

### GetOverallScalabilityLevel

▸ **GetOverallScalabilityLevel**(): `number`

#### Returns

`number`

___

### GetPostProcessingQuality

▸ **GetPostProcessingQuality**(): `number`

#### Returns

`number`

___

### GetPreferredFullscreenMode

▸ **GetPreferredFullscreenMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

___

### GetRecommendedResolutionScale

▸ **GetRecommendedResolutionScale**(): `number`

#### Returns

`number`

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

___

### GetResolutionScaleNormalized

▸ **GetResolutionScaleNormalized**(): `number`

#### Returns

`number`

___

### GetScreenResolution

▸ **GetScreenResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### GetShadingQuality

▸ **GetShadingQuality**(): `number`

#### Returns

`number`

___

### GetShadowQuality

▸ **GetShadowQuality**(): `number`

#### Returns

`number`

___

### GetTextureQuality

▸ **GetTextureQuality**(): `number`

#### Returns

`number`

___

### GetViewDistanceQuality

▸ **GetViewDistanceQuality**(): `number`

#### Returns

`number`

___

### GetVisualEffectQuality

▸ **GetVisualEffectQuality**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsDirty

▸ **IsDirty**(): `boolean`

#### Returns

`boolean`

___

### IsDynamicResolutionDirty

▸ **IsDynamicResolutionDirty**(): `boolean`

#### Returns

`boolean`

___

### IsDynamicResolutionEnabled

▸ **IsDynamicResolutionEnabled**(): `boolean`

#### Returns

`boolean`

___

### IsFullscreenModeDirty

▸ **IsFullscreenModeDirty**(): `boolean`

#### Returns

`boolean`

___

### IsHDREnabled

▸ **IsHDREnabled**(): `boolean`

#### Returns

`boolean`

___

### IsScreenResolutionDirty

▸ **IsScreenResolutionDirty**(): `boolean`

#### Returns

`boolean`

___

### IsVSyncDirty

▸ **IsVSyncDirty**(): `boolean`

#### Returns

`boolean`

___

### IsVSyncEnabled

▸ **IsVSyncEnabled**(): `boolean`

#### Returns

`boolean`

___

### LoadSettings

▸ **LoadSettings**(`bForceReload?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bForceReload?` | `boolean` |

#### Returns

`void`

___

### ResetToCurrentSettings

▸ **ResetToCurrentSettings**(): `void`

#### Returns

`void`

___

### RevertVideoMode

▸ **RevertVideoMode**(): `void`

#### Returns

`void`

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

___

### SaveSettings

▸ **SaveSettings**(): `void`

#### Returns

`void`

___

### SetAntiAliasingQuality

▸ **SetAntiAliasingQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetAudioQualityLevel

▸ **SetAudioQualityLevel**(`QualityLevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QualityLevel` | `number` |

#### Returns

`void`

___

### SetBenchmarkFallbackValues

▸ **SetBenchmarkFallbackValues**(): `void`

#### Returns

`void`

___

### SetDynamicResolutionEnabled

▸ **SetDynamicResolutionEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

___

### SetFoliageQuality

▸ **SetFoliageQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetFrameRateLimit

▸ **SetFrameRateLimit**(`NewLimit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLimit` | `number` |

#### Returns

`void`

___

### SetFullscreenMode

▸ **SetFullscreenMode**(`InFullscreenMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFullscreenMode` | [`EWindowMode`](../enums/ue_ue.EWindowMode.md) |

#### Returns

`void`

___

### SetOverallScalabilityLevel

▸ **SetOverallScalabilityLevel**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetPostProcessingQuality

▸ **SetPostProcessingQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetResolutionScaleNormalized

▸ **SetResolutionScaleNormalized**(`NewScaleNormalized`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScaleNormalized` | `number` |

#### Returns

`void`

___

### SetResolutionScaleValue

▸ **SetResolutionScaleValue**(`NewScaleValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScaleValue` | `number` |

#### Returns

`void`

___

### SetResolutionScaleValueEx

▸ **SetResolutionScaleValueEx**(`NewScaleValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScaleValue` | `number` |

#### Returns

`void`

___

### SetScreenResolution

▸ **SetScreenResolution**(`Resolution`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Resolution` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

`void`

___

### SetShadingQuality

▸ **SetShadingQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetShadowQuality

▸ **SetShadowQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetTextureQuality

▸ **SetTextureQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetToDefaults

▸ **SetToDefaults**(): `void`

#### Returns

`void`

___

### SetVSyncEnabled

▸ **SetVSyncEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

___

### SetViewDistanceQuality

▸ **SetViewDistanceQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SetVisualEffectQuality

▸ **SetVisualEffectQuality**(`Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`void`

___

### SupportsHDRDisplayOutput

▸ **SupportsHDRDisplayOutput**(): `boolean`

#### Returns

`boolean`

___

### ValidateSettings

▸ **ValidateSettings**(): `void`

#### Returns

`void`

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

___

### GetDefaultResolution

▸ `Static` **GetDefaultResolution**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### GetDefaultWindowMode

▸ `Static` **GetDefaultWindowMode**(): [`EWindowMode`](../enums/ue_ue.EWindowMode.md)

#### Returns

[`EWindowMode`](../enums/ue_ue.EWindowMode.md)

___

### GetDefaultWindowPosition

▸ `Static` **GetDefaultWindowPosition**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### GetGameUserSettings

▸ `Static` **GetGameUserSettings**(): [`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Returns

[`GameUserSettings`](ue_ue.GameUserSettings.md)

___

### GetSyncInterval

▸ `Static` **GetSyncInterval**(): `number`

#### Returns

`number`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
