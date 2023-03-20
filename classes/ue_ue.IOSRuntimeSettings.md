[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / IOSRuntimeSettings

# Class: IOSRuntimeSettings

[ue/ue](../modules/ue_ue.md).IOSRuntimeSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`IOSRuntimeSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.IOSRuntimeSettings.md#constructor)

### Properties

- [AdditionalLinkerFlags](ue_ue.IOSRuntimeSettings.md#additionallinkerflags)
- [AdditionalPlistData](ue_ue.IOSRuntimeSettings.md#additionalplistdata)
- [AdditionalShippingLinkerFlags](ue_ue.IOSRuntimeSettings.md#additionalshippinglinkerflags)
- [AudioCallbackBufferFrameSize](ue_ue.IOSRuntimeSettings.md#audiocallbackbufferframesize)
- [AudioMaxChannels](ue_ue.IOSRuntimeSettings.md#audiomaxchannels)
- [AudioNumBuffersToEnqueue](ue_ue.IOSRuntimeSettings.md#audionumbufferstoenqueue)
- [AudioNumSourceWorkers](ue_ue.IOSRuntimeSettings.md#audionumsourceworkers)
- [AudioSampleRate](ue_ue.IOSRuntimeSettings.md#audiosamplerate)
- [AutoStreamingThreshold](ue_ue.IOSRuntimeSettings.md#autostreamingthreshold)
- [BundleDisplayName](ue_ue.IOSRuntimeSettings.md#bundledisplayname)
- [BundleIdentifier](ue_ue.IOSRuntimeSettings.md#bundleidentifier)
- [BundleName](ue_ue.IOSRuntimeSettings.md#bundlename)
- [CacheSizeKB](ue_ue.IOSRuntimeSettings.md#cachesizekb)
- [ChunkSizeKB](ue_ue.IOSRuntimeSettings.md#chunksizekb)
- [CompressionOverrides](ue_ue.IOSRuntimeSettings.md#compressionoverrides)
- [CompressionQualityModifier](ue_ue.IOSRuntimeSettings.md#compressionqualitymodifier)
- [DeltaCopyInstallPath](ue_ue.IOSRuntimeSettings.md#deltacopyinstallpath)
- [EnableMathOptimisations](ue_ue.IOSRuntimeSettings.md#enablemathoptimisations)
- [EnableRemoteShaderCompile](ue_ue.IOSRuntimeSettings.md#enableremoteshadercompile)
- [FacebookAppID](ue_ue.IOSRuntimeSettings.md#facebookappid)
- [ForceFloats](ue_ue.IOSRuntimeSettings.md#forcefloats)
- [FrameRateLock](ue_ue.IOSRuntimeSettings.md#frameratelock)
- [HighSampleRate](ue_ue.IOSRuntimeSettings.md#highsamplerate)
- [IOSCloudKitSyncStrategy](ue_ue.IOSRuntimeSettings.md#ioscloudkitsyncstrategy)
- [IOSTeamID](ue_ue.IOSRuntimeSettings.md#iosteamid)
- [IndirectArgumentTier](ue_ue.IOSRuntimeSettings.md#indirectargumenttier)
- [LowSampleRate](ue_ue.IOSRuntimeSettings.md#lowsamplerate)
- [MaxSampleRate](ue_ue.IOSRuntimeSettings.md#maxsamplerate)
- [MaxShaderLanguageVersion](ue_ue.IOSRuntimeSettings.md#maxshaderlanguageversion)
- [MedSampleRate](ue_ue.IOSRuntimeSettings.md#medsamplerate)
- [MinSampleRate](ue_ue.IOSRuntimeSettings.md#minsamplerate)
- [MinimumiOSVersion](ue_ue.IOSRuntimeSettings.md#minimumiosversion)
- [MobileProvision](ue_ue.IOSRuntimeSettings.md#mobileprovision)
- [OcclusionPlugin](ue_ue.IOSRuntimeSettings.md#occlusionplugin)
- [PreferredLandscapeOrientation](ue_ue.IOSRuntimeSettings.md#preferredlandscapeorientation)
- [RSyncUsername](ue_ue.IOSRuntimeSettings.md#rsyncusername)
- [RemoteServerName](ue_ue.IOSRuntimeSettings.md#remoteservername)
- [ReverbPlugin](ue_ue.IOSRuntimeSettings.md#reverbplugin)
- [SSHPrivateKeyLocation](ue_ue.IOSRuntimeSettings.md#sshprivatekeylocation)
- [SSHPrivateKeyOverridePath](ue_ue.IOSRuntimeSettings.md#sshprivatekeyoverridepath)
- [SigningCertificate](ue_ue.IOSRuntimeSettings.md#signingcertificate)
- [SoundCueCookQualityIndex](ue_ue.IOSRuntimeSettings.md#soundcuecookqualityindex)
- [SpatializationPlugin](ue_ue.IOSRuntimeSettings.md#spatializationplugin)
- [UseFastIntrinsics](ue_ue.IOSRuntimeSettings.md#usefastintrinsics)
- [VersionInfo](ue_ue.IOSRuntimeSettings.md#versioninfo)
- [\_\_tid\_IOSRuntimeSettings\_\_](ue_ue.IOSRuntimeSettings.md#__tid_iosruntimesettings__)
- [\_\_tid\_Object\_\_](ue_ue.IOSRuntimeSettings.md#__tid_object__)
- [bAllowControllers](ue_ue.IOSRuntimeSettings.md#ballowcontrollers)
- [bAllowRemoteRotation](ue_ue.IOSRuntimeSettings.md#ballowremoterotation)
- [bAutomaticSigning](ue_ue.IOSRuntimeSettings.md#bautomaticsigning)
- [bBuildAsFramework](ue_ue.IOSRuntimeSettings.md#bbuildasframework)
- [bCookASTCTextures](ue_ue.IOSRuntimeSettings.md#bcookastctextures)
- [bCookPVRTCTextures](ue_ue.IOSRuntimeSettings.md#bcookpvrtctextures)
- [bDevForArm64](ue_ue.IOSRuntimeSettings.md#bdevforarm64)
- [bDevForArmV7](ue_ue.IOSRuntimeSettings.md#bdevforarmv7)
- [bDevForArmV7S](ue_ue.IOSRuntimeSettings.md#bdevforarmv7s)
- [bDisableHTTPS](ue_ue.IOSRuntimeSettings.md#bdisablehttps)
- [bDisableMotionData](ue_ue.IOSRuntimeSettings.md#bdisablemotiondata)
- [bEnableAdvertisingIdentifier](ue_ue.IOSRuntimeSettings.md#benableadvertisingidentifier)
- [bEnableBackgroundFetch](ue_ue.IOSRuntimeSettings.md#benablebackgroundfetch)
- [bEnableCloudKitSupport](ue_ue.IOSRuntimeSettings.md#benablecloudkitsupport)
- [bEnableFacebookSupport](ue_ue.IOSRuntimeSettings.md#benablefacebooksupport)
- [bEnableGameCenterSupport](ue_ue.IOSRuntimeSettings.md#benablegamecentersupport)
- [bEnableRemoteNotificationsSupport](ue_ue.IOSRuntimeSettings.md#benableremotenotificationssupport)
- [bGenerateCrashReportSymbols](ue_ue.IOSRuntimeSettings.md#bgeneratecrashreportsymbols)
- [bGenerateXCArchive](ue_ue.IOSRuntimeSettings.md#bgeneratexcarchive)
- [bGeneratedSYMBundle](ue_ue.IOSRuntimeSettings.md#bgeneratedsymbundle)
- [bGeneratedSYMFile](ue_ue.IOSRuntimeSettings.md#bgeneratedsymfile)
- [bResampleForDevice](ue_ue.IOSRuntimeSettings.md#bresamplefordevice)
- [bShipForArm64](ue_ue.IOSRuntimeSettings.md#bshipforarm64)
- [bShipForArmV7](ue_ue.IOSRuntimeSettings.md#bshipforarmv7)
- [bShipForArmV7S](ue_ue.IOSRuntimeSettings.md#bshipforarmv7s)
- [bShipForBitcode](ue_ue.IOSRuntimeSettings.md#bshipforbitcode)
- [bSupportsIPad](ue_ue.IOSRuntimeSettings.md#bsupportsipad)
- [bSupportsIPhone](ue_ue.IOSRuntimeSettings.md#bsupportsiphone)
- [bSupportsITunesFileSharing](ue_ue.IOSRuntimeSettings.md#bsupportsitunesfilesharing)
- [bSupportsLandscapeLeftOrientation](ue_ue.IOSRuntimeSettings.md#bsupportslandscapeleftorientation)
- [bSupportsLandscapeRightOrientation](ue_ue.IOSRuntimeSettings.md#bsupportslandscaperightorientation)
- [bSupportsMetal](ue_ue.IOSRuntimeSettings.md#bsupportsmetal)
- [bSupportsMetalMRT](ue_ue.IOSRuntimeSettings.md#bsupportsmetalmrt)
- [bSupportsPortraitOrientation](ue_ue.IOSRuntimeSettings.md#bsupportsportraitorientation)
- [bSupportsUpsideDownOrientation](ue_ue.IOSRuntimeSettings.md#bsupportsupsidedownorientation)
- [bTreatRemoteAsSeparateController](ue_ue.IOSRuntimeSettings.md#btreatremoteasseparatecontroller)
- [bUseAudioStreamCaching](ue_ue.IOSRuntimeSettings.md#buseaudiostreamcaching)
- [bUseIntegratedKeyboard](ue_ue.IOSRuntimeSettings.md#buseintegratedkeyboard)
- [bUseRSync](ue_ue.IOSRuntimeSettings.md#busersync)
- [bUseRemoteAbsoluteDpadValues](ue_ue.IOSRuntimeSettings.md#buseremoteabsolutedpadvalues)
- [bUseRemoteAsVirtualJoystick](ue_ue.IOSRuntimeSettings.md#buseremoteasvirtualjoystick)

### Methods

- [CreateDefaultSubobject](ue_ue.IOSRuntimeSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.IOSRuntimeSettings.md#executeubergraph)
- [GetClass](ue_ue.IOSRuntimeSettings.md#getclass)
- [GetName](ue_ue.IOSRuntimeSettings.md#getname)
- [GetOuter](ue_ue.IOSRuntimeSettings.md#getouter)
- [GetWorld](ue_ue.IOSRuntimeSettings.md#getworld)
- [Find](ue_ue.IOSRuntimeSettings.md#find)
- [Load](ue_ue.IOSRuntimeSettings.md#load)
- [StaticClass](ue_ue.IOSRuntimeSettings.md#staticclass)

## Constructors

### constructor

• **new IOSRuntimeSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AdditionalLinkerFlags

• **AdditionalLinkerFlags**: `string`

___

### AdditionalPlistData

• **AdditionalPlistData**: `string`

___

### AdditionalShippingLinkerFlags

• **AdditionalShippingLinkerFlags**: `string`

___

### AudioCallbackBufferFrameSize

• **AudioCallbackBufferFrameSize**: `number`

___

### AudioMaxChannels

• **AudioMaxChannels**: `number`

___

### AudioNumBuffersToEnqueue

• **AudioNumBuffersToEnqueue**: `number`

___

### AudioNumSourceWorkers

• **AudioNumSourceWorkers**: `number`

___

### AudioSampleRate

• **AudioSampleRate**: `number`

___

### AutoStreamingThreshold

• **AutoStreamingThreshold**: `number`

___

### BundleDisplayName

• **BundleDisplayName**: `string`

___

### BundleIdentifier

• **BundleIdentifier**: `string`

___

### BundleName

• **BundleName**: `string`

___

### CacheSizeKB

• **CacheSizeKB**: `number`

___

### ChunkSizeKB

• **ChunkSizeKB**: `number`

___

### CompressionOverrides

• **CompressionOverrides**: [`PlatformRuntimeAudioCompressionOverrides`](ue_ue.PlatformRuntimeAudioCompressionOverrides.md)

___

### CompressionQualityModifier

• **CompressionQualityModifier**: `number`

___

### DeltaCopyInstallPath

• **DeltaCopyInstallPath**: [`IOSBuildResourceDirectory`](ue_ue.IOSBuildResourceDirectory.md)

___

### EnableMathOptimisations

• **EnableMathOptimisations**: `boolean`

___

### EnableRemoteShaderCompile

• **EnableRemoteShaderCompile**: `boolean`

___

### FacebookAppID

• **FacebookAppID**: `string`

___

### ForceFloats

• **ForceFloats**: `boolean`

___

### FrameRateLock

• **FrameRateLock**: [`EPowerUsageFrameRateLock`](../enums/ue_ue.EPowerUsageFrameRateLock.md)

___

### HighSampleRate

• **HighSampleRate**: `number`

___

### IOSCloudKitSyncStrategy

• **IOSCloudKitSyncStrategy**: [`EIOSCloudKitSyncStrategy`](../enums/ue_ue.EIOSCloudKitSyncStrategy.md)

___

### IOSTeamID

• **IOSTeamID**: `string`

___

### IndirectArgumentTier

• **IndirectArgumentTier**: `number`

___

### LowSampleRate

• **LowSampleRate**: `number`

___

### MaxSampleRate

• **MaxSampleRate**: `number`

___

### MaxShaderLanguageVersion

• **MaxShaderLanguageVersion**: `number`

___

### MedSampleRate

• **MedSampleRate**: `number`

___

### MinSampleRate

• **MinSampleRate**: `number`

___

### MinimumiOSVersion

• **MinimumiOSVersion**: [`EIOSVersion`](../enums/ue_ue.EIOSVersion.md)

___

### MobileProvision

• **MobileProvision**: `string`

___

### OcclusionPlugin

• **OcclusionPlugin**: `string`

___

### PreferredLandscapeOrientation

• **PreferredLandscapeOrientation**: [`EIOSLandscapeOrientation`](../enums/ue_ue.EIOSLandscapeOrientation.md)

___

### RSyncUsername

• **RSyncUsername**: `string`

___

### RemoteServerName

• **RemoteServerName**: `string`

___

### ReverbPlugin

• **ReverbPlugin**: `string`

___

### SSHPrivateKeyLocation

• **SSHPrivateKeyLocation**: `string`

___

### SSHPrivateKeyOverridePath

• **SSHPrivateKeyOverridePath**: [`IOSBuildResourceFilePath`](ue_ue.IOSBuildResourceFilePath.md)

___

### SigningCertificate

• **SigningCertificate**: `string`

___

### SoundCueCookQualityIndex

• **SoundCueCookQualityIndex**: `number`

___

### SpatializationPlugin

• **SpatializationPlugin**: `string`

___

### UseFastIntrinsics

• **UseFastIntrinsics**: `boolean`

___

### VersionInfo

• **VersionInfo**: `string`

___

### \_\_tid\_IOSRuntimeSettings\_\_

• **\_\_tid\_IOSRuntimeSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAllowControllers

• **bAllowControllers**: `boolean`

___

### bAllowRemoteRotation

• **bAllowRemoteRotation**: `boolean`

___

### bAutomaticSigning

• **bAutomaticSigning**: `boolean`

___

### bBuildAsFramework

• **bBuildAsFramework**: `boolean`

___

### bCookASTCTextures

• **bCookASTCTextures**: `boolean`

___

### bCookPVRTCTextures

• **bCookPVRTCTextures**: `boolean`

___

### bDevForArm64

• **bDevForArm64**: `boolean`

___

### bDevForArmV7

• **bDevForArmV7**: `boolean`

___

### bDevForArmV7S

• **bDevForArmV7S**: `boolean`

___

### bDisableHTTPS

• **bDisableHTTPS**: `boolean`

___

### bDisableMotionData

• **bDisableMotionData**: `boolean`

___

### bEnableAdvertisingIdentifier

• **bEnableAdvertisingIdentifier**: `boolean`

___

### bEnableBackgroundFetch

• **bEnableBackgroundFetch**: `boolean`

___

### bEnableCloudKitSupport

• **bEnableCloudKitSupport**: `boolean`

___

### bEnableFacebookSupport

• **bEnableFacebookSupport**: `boolean`

___

### bEnableGameCenterSupport

• **bEnableGameCenterSupport**: `boolean`

___

### bEnableRemoteNotificationsSupport

• **bEnableRemoteNotificationsSupport**: `boolean`

___

### bGenerateCrashReportSymbols

• **bGenerateCrashReportSymbols**: `boolean`

___

### bGenerateXCArchive

• **bGenerateXCArchive**: `boolean`

___

### bGeneratedSYMBundle

• **bGeneratedSYMBundle**: `boolean`

___

### bGeneratedSYMFile

• **bGeneratedSYMFile**: `boolean`

___

### bResampleForDevice

• **bResampleForDevice**: `boolean`

___

### bShipForArm64

• **bShipForArm64**: `boolean`

___

### bShipForArmV7

• **bShipForArmV7**: `boolean`

___

### bShipForArmV7S

• **bShipForArmV7S**: `boolean`

___

### bShipForBitcode

• **bShipForBitcode**: `boolean`

___

### bSupportsIPad

• **bSupportsIPad**: `boolean`

___

### bSupportsIPhone

• **bSupportsIPhone**: `boolean`

___

### bSupportsITunesFileSharing

• **bSupportsITunesFileSharing**: `boolean`

___

### bSupportsLandscapeLeftOrientation

• **bSupportsLandscapeLeftOrientation**: `boolean`

___

### bSupportsLandscapeRightOrientation

• **bSupportsLandscapeRightOrientation**: `boolean`

___

### bSupportsMetal

• **bSupportsMetal**: `boolean`

___

### bSupportsMetalMRT

• **bSupportsMetalMRT**: `boolean`

___

### bSupportsPortraitOrientation

• **bSupportsPortraitOrientation**: `boolean`

___

### bSupportsUpsideDownOrientation

• **bSupportsUpsideDownOrientation**: `boolean`

___

### bTreatRemoteAsSeparateController

• **bTreatRemoteAsSeparateController**: `boolean`

___

### bUseAudioStreamCaching

• **bUseAudioStreamCaching**: `boolean`

___

### bUseIntegratedKeyboard

• **bUseIntegratedKeyboard**: `boolean`

___

### bUseRSync

• **bUseRSync**: `boolean`

___

### bUseRemoteAbsoluteDpadValues

• **bUseRemoteAbsoluteDpadValues**: `boolean`

___

### bUseRemoteAsVirtualJoystick

• **bUseRemoteAsVirtualJoystick**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`IOSRuntimeSettings`](ue_ue.IOSRuntimeSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`IOSRuntimeSettings`](ue_ue.IOSRuntimeSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`IOSRuntimeSettings`](ue_ue.IOSRuntimeSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`IOSRuntimeSettings`](ue_ue.IOSRuntimeSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
