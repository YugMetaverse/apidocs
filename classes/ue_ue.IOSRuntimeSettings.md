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

#### Defined in

[ue/ue.d.ts:40465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40465)

## Properties

### AdditionalLinkerFlags

• **AdditionalLinkerFlags**: `string`

#### Defined in

[ue/ue.d.ts:40489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40489)

___

### AdditionalPlistData

• **AdditionalPlistData**: `string`

#### Defined in

[ue/ue.d.ts:40517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40517)

___

### AdditionalShippingLinkerFlags

• **AdditionalShippingLinkerFlags**: `string`

#### Defined in

[ue/ue.d.ts:40490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40490)

___

### AudioCallbackBufferFrameSize

• **AudioCallbackBufferFrameSize**: `number`

#### Defined in

[ue/ue.d.ts:40532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40532)

___

### AudioMaxChannels

• **AudioMaxChannels**: `number`

#### Defined in

[ue/ue.d.ts:40534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40534)

___

### AudioNumBuffersToEnqueue

• **AudioNumBuffersToEnqueue**: `number`

#### Defined in

[ue/ue.d.ts:40533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40533)

___

### AudioNumSourceWorkers

• **AudioNumSourceWorkers**: `number`

#### Defined in

[ue/ue.d.ts:40535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40535)

___

### AudioSampleRate

• **AudioSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:40531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40531)

___

### AutoStreamingThreshold

• **AutoStreamingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:40551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40551)

___

### BundleDisplayName

• **BundleDisplayName**: `string`

#### Defined in

[ue/ue.d.ts:40509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40509)

___

### BundleIdentifier

• **BundleIdentifier**: `string`

#### Defined in

[ue/ue.d.ts:40511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40511)

___

### BundleName

• **BundleName**: `string`

#### Defined in

[ue/ue.d.ts:40510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40510)

___

### CacheSizeKB

• **CacheSizeKB**: `number`

#### Defined in

[ue/ue.d.ts:40542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40542)

___

### ChunkSizeKB

• **ChunkSizeKB**: `number`

#### Defined in

[ue/ue.d.ts:40540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40540)

___

### CompressionOverrides

• **CompressionOverrides**: [`PlatformRuntimeAudioCompressionOverrides`](ue_ue.PlatformRuntimeAudioCompressionOverrides.md)

#### Defined in

[ue/ue.d.ts:40539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40539)

___

### CompressionQualityModifier

• **CompressionQualityModifier**: `number`

#### Defined in

[ue/ue.d.ts:40550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40550)

___

### DeltaCopyInstallPath

• **DeltaCopyInstallPath**: [`IOSBuildResourceDirectory`](ue_ue.IOSBuildResourceDirectory.md)

#### Defined in

[ue/ue.d.ts:40494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40494)

___

### EnableMathOptimisations

• **EnableMathOptimisations**: `boolean`

#### Defined in

[ue/ue.d.ts:40528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40528)

___

### EnableRemoteShaderCompile

• **EnableRemoteShaderCompile**: `boolean`

#### Defined in

[ue/ue.d.ts:40476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40476)

___

### FacebookAppID

• **FacebookAppID**: `string`

#### Defined in

[ue/ue.d.ts:40519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40519)

___

### ForceFloats

• **ForceFloats**: `boolean`

#### Defined in

[ue/ue.d.ts:40527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40527)

___

### FrameRateLock

• **FrameRateLock**: [`EPowerUsageFrameRateLock`](../enums/ue_ue.EPowerUsageFrameRateLock.md)

#### Defined in

[ue/ue.d.ts:40513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40513)

___

### HighSampleRate

• **HighSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:40546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40546)

___

### IOSCloudKitSyncStrategy

• **IOSCloudKitSyncStrategy**: [`EIOSCloudKitSyncStrategy`](../enums/ue_ue.EIOSCloudKitSyncStrategy.md)

#### Defined in

[ue/ue.d.ts:40468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40468)

___

### IOSTeamID

• **IOSTeamID**: `string`

#### Defined in

[ue/ue.d.ts:40523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40523)

___

### IndirectArgumentTier

• **IndirectArgumentTier**: `number`

#### Defined in

[ue/ue.d.ts:40529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40529)

___

### LowSampleRate

• **LowSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:40548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40548)

___

### MaxSampleRate

• **MaxSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:40545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40545)

___

### MaxShaderLanguageVersion

• **MaxShaderLanguageVersion**: `number`

#### Defined in

[ue/ue.d.ts:40525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40525)

___

### MedSampleRate

• **MedSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:40547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40547)

___

### MinSampleRate

• **MinSampleRate**: `number`

#### Defined in

[ue/ue.d.ts:40549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40549)

___

### MinimumiOSVersion

• **MinimumiOSVersion**: [`EIOSVersion`](../enums/ue_ue.EIOSVersion.md)

#### Defined in

[ue/ue.d.ts:40514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40514)

___

### MobileProvision

• **MobileProvision**: `string`

#### Defined in

[ue/ue.d.ts:40520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40520)

___

### OcclusionPlugin

• **OcclusionPlugin**: `string`

#### Defined in

[ue/ue.d.ts:40538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40538)

___

### PreferredLandscapeOrientation

• **PreferredLandscapeOrientation**: [`EIOSLandscapeOrientation`](../enums/ue_ue.EIOSLandscapeOrientation.md)

#### Defined in

[ue/ue.d.ts:40508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40508)

___

### RSyncUsername

• **RSyncUsername**: `string`

#### Defined in

[ue/ue.d.ts:40493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40493)

___

### RemoteServerName

• **RemoteServerName**: `string`

#### Defined in

[ue/ue.d.ts:40491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40491)

___

### ReverbPlugin

• **ReverbPlugin**: `string`

#### Defined in

[ue/ue.d.ts:40537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40537)

___

### SSHPrivateKeyLocation

• **SSHPrivateKeyLocation**: `string`

#### Defined in

[ue/ue.d.ts:40495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40495)

___

### SSHPrivateKeyOverridePath

• **SSHPrivateKeyOverridePath**: [`IOSBuildResourceFilePath`](ue_ue.IOSBuildResourceFilePath.md)

#### Defined in

[ue/ue.d.ts:40496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40496)

___

### SigningCertificate

• **SigningCertificate**: `string`

#### Defined in

[ue/ue.d.ts:40521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40521)

___

### SoundCueCookQualityIndex

• **SoundCueCookQualityIndex**: `number`

#### Defined in

[ue/ue.d.ts:40544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40544)

___

### SpatializationPlugin

• **SpatializationPlugin**: `string`

#### Defined in

[ue/ue.d.ts:40536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40536)

___

### UseFastIntrinsics

• **UseFastIntrinsics**: `boolean`

#### Defined in

[ue/ue.d.ts:40526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40526)

___

### VersionInfo

• **VersionInfo**: `string`

#### Defined in

[ue/ue.d.ts:40512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40512)

___

### \_\_tid\_IOSRuntimeSettings\_\_

• **\_\_tid\_IOSRuntimeSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:40556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40556)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAllowControllers

• **bAllowControllers**: `boolean`

#### Defined in

[ue/ue.d.ts:40501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40501)

___

### bAllowRemoteRotation

• **bAllowRemoteRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:40498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40498)

___

### bAutomaticSigning

• **bAutomaticSigning**: `boolean`

#### Defined in

[ue/ue.d.ts:40522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40522)

___

### bBuildAsFramework

• **bBuildAsFramework**: `boolean`

#### Defined in

[ue/ue.d.ts:40475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40475)

___

### bCookASTCTextures

• **bCookASTCTextures**: `boolean`

#### Defined in

[ue/ue.d.ts:40474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40474)

___

### bCookPVRTCTextures

• **bCookPVRTCTextures**: `boolean`

#### Defined in

[ue/ue.d.ts:40473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40473)

___

### bDevForArm64

• **bDevForArm64**: `boolean`

#### Defined in

[ue/ue.d.ts:40482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40482)

___

### bDevForArmV7

• **bDevForArmV7**: `boolean`

#### Defined in

[ue/ue.d.ts:40481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40481)

___

### bDevForArmV7S

• **bDevForArmV7S**: `boolean`

#### Defined in

[ue/ue.d.ts:40483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40483)

___

### bDisableHTTPS

• **bDisableHTTPS**: `boolean`

#### Defined in

[ue/ue.d.ts:40524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40524)

___

### bDisableMotionData

• **bDisableMotionData**: `boolean`

#### Defined in

[ue/ue.d.ts:40502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40502)

___

### bEnableAdvertisingIdentifier

• **bEnableAdvertisingIdentifier**: `boolean`

#### Defined in

[ue/ue.d.ts:40488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40488)

___

### bEnableBackgroundFetch

• **bEnableBackgroundFetch**: `boolean`

#### Defined in

[ue/ue.d.ts:40470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40470)

___

### bEnableCloudKitSupport

• **bEnableCloudKitSupport**: `boolean`

#### Defined in

[ue/ue.d.ts:40467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40467)

___

### bEnableFacebookSupport

• **bEnableFacebookSupport**: `boolean`

#### Defined in

[ue/ue.d.ts:40518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40518)

___

### bEnableGameCenterSupport

• **bEnableGameCenterSupport**: `boolean`

#### Defined in

[ue/ue.d.ts:40466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40466)

___

### bEnableRemoteNotificationsSupport

• **bEnableRemoteNotificationsSupport**: `boolean`

#### Defined in

[ue/ue.d.ts:40469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40469)

___

### bGenerateCrashReportSymbols

• **bGenerateCrashReportSymbols**: `boolean`

#### Defined in

[ue/ue.d.ts:40479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40479)

___

### bGenerateXCArchive

• **bGenerateXCArchive**: `boolean`

#### Defined in

[ue/ue.d.ts:40480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40480)

___

### bGeneratedSYMBundle

• **bGeneratedSYMBundle**: `boolean`

#### Defined in

[ue/ue.d.ts:40478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40478)

___

### bGeneratedSYMFile

• **bGeneratedSYMFile**: `boolean`

#### Defined in

[ue/ue.d.ts:40477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40477)

___

### bResampleForDevice

• **bResampleForDevice**: `boolean`

#### Defined in

[ue/ue.d.ts:40543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40543)

___

### bShipForArm64

• **bShipForArm64**: `boolean`

#### Defined in

[ue/ue.d.ts:40485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40485)

___

### bShipForArmV7

• **bShipForArmV7**: `boolean`

#### Defined in

[ue/ue.d.ts:40484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40484)

___

### bShipForArmV7S

• **bShipForArmV7S**: `boolean`

#### Defined in

[ue/ue.d.ts:40486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40486)

___

### bShipForBitcode

• **bShipForBitcode**: `boolean`

#### Defined in

[ue/ue.d.ts:40487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40487)

___

### bSupportsIPad

• **bSupportsIPad**: `boolean`

#### Defined in

[ue/ue.d.ts:40515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40515)

___

### bSupportsIPhone

• **bSupportsIPhone**: `boolean`

#### Defined in

[ue/ue.d.ts:40516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40516)

___

### bSupportsITunesFileSharing

• **bSupportsITunesFileSharing**: `boolean`

#### Defined in

[ue/ue.d.ts:40507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40507)

___

### bSupportsLandscapeLeftOrientation

• **bSupportsLandscapeLeftOrientation**: `boolean`

#### Defined in

[ue/ue.d.ts:40505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40505)

___

### bSupportsLandscapeRightOrientation

• **bSupportsLandscapeRightOrientation**: `boolean`

#### Defined in

[ue/ue.d.ts:40506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40506)

___

### bSupportsMetal

• **bSupportsMetal**: `boolean`

#### Defined in

[ue/ue.d.ts:40471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40471)

___

### bSupportsMetalMRT

• **bSupportsMetalMRT**: `boolean`

#### Defined in

[ue/ue.d.ts:40472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40472)

___

### bSupportsPortraitOrientation

• **bSupportsPortraitOrientation**: `boolean`

#### Defined in

[ue/ue.d.ts:40503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40503)

___

### bSupportsUpsideDownOrientation

• **bSupportsUpsideDownOrientation**: `boolean`

#### Defined in

[ue/ue.d.ts:40504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40504)

___

### bTreatRemoteAsSeparateController

• **bTreatRemoteAsSeparateController**: `boolean`

#### Defined in

[ue/ue.d.ts:40497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40497)

___

### bUseAudioStreamCaching

• **bUseAudioStreamCaching**: `boolean`

#### Defined in

[ue/ue.d.ts:40541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40541)

___

### bUseIntegratedKeyboard

• **bUseIntegratedKeyboard**: `boolean`

#### Defined in

[ue/ue.d.ts:40530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40530)

___

### bUseRSync

• **bUseRSync**: `boolean`

#### Defined in

[ue/ue.d.ts:40492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40492)

___

### bUseRemoteAbsoluteDpadValues

• **bUseRemoteAbsoluteDpadValues**: `boolean`

#### Defined in

[ue/ue.d.ts:40500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40500)

___

### bUseRemoteAsVirtualJoystick

• **bUseRemoteAsVirtualJoystick**: `boolean`

#### Defined in

[ue/ue.d.ts:40499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40499)

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

#### Defined in

[ue/ue.d.ts:40553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40553)

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

#### Defined in

[ue/ue.d.ts:40554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40554)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:40552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40552)
