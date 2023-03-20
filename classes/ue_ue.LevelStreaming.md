[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelStreaming

# Class: LevelStreaming

[ue/ue](../modules/ue_ue.md).LevelStreaming

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LevelStreaming`**

  ↳↳ [`LevelStreamingAlwaysLoaded`](ue_ue.LevelStreamingAlwaysLoaded.md)

  ↳↳ [`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

  ↳↳ [`LevelStreamingPersistent`](ue_ue.LevelStreamingPersistent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.LevelStreaming.md#constructor)

### Properties

- [DrawColor](ue_ue.LevelStreaming.md#drawcolor)
- [EditorStreamingVolumes](ue_ue.LevelStreaming.md#editorstreamingvolumes)
- [FolderPath](ue_ue.LevelStreaming.md#folderpath)
- [Keywords](ue_ue.LevelStreaming.md#keywords)
- [LODPackageNames](ue_ue.LevelStreaming.md#lodpackagenames)
- [LevelColor](ue_ue.LevelStreaming.md#levelcolor)
- [LevelLODIndex](ue_ue.LevelStreaming.md#levellodindex)
- [LevelTransform](ue_ue.LevelStreaming.md#leveltransform)
- [LoadedLevel](ue_ue.LevelStreaming.md#loadedlevel)
- [MinTimeBetweenVolumeUnloadRequests](ue_ue.LevelStreaming.md#mintimebetweenvolumeunloadrequests)
- [OnLevelHidden](ue_ue.LevelStreaming.md#onlevelhidden)
- [OnLevelLoaded](ue_ue.LevelStreaming.md#onlevelloaded)
- [OnLevelShown](ue_ue.LevelStreaming.md#onlevelshown)
- [OnLevelUnloaded](ue_ue.LevelStreaming.md#onlevelunloaded)
- [PackageName](ue_ue.LevelStreaming.md#packagename)
- [PackageNameToLoad](ue_ue.LevelStreaming.md#packagenametoload)
- [PendingUnloadLevel](ue_ue.LevelStreaming.md#pendingunloadlevel)
- [StreamingPriority](ue_ue.LevelStreaming.md#streamingpriority)
- [WorldAsset](ue_ue.LevelStreaming.md#worldasset)
- [\_\_tid\_LevelStreaming\_\_](ue_ue.LevelStreaming.md#__tid_levelstreaming__)
- [\_\_tid\_Object\_\_](ue_ue.LevelStreaming.md#__tid_object__)
- [bDisableDistanceStreaming](ue_ue.LevelStreaming.md#bdisabledistancestreaming)
- [bDrawOnLevelStatusMap](ue_ue.LevelStreaming.md#bdrawonlevelstatusmap)
- [bIsStatic](ue_ue.LevelStreaming.md#bisstatic)
- [bLocked](ue_ue.LevelStreaming.md#blocked)
- [bShouldBeLoaded](ue_ue.LevelStreaming.md#bshouldbeloaded)
- [bShouldBeVisible](ue_ue.LevelStreaming.md#bshouldbevisible)
- [bShouldBeVisibleInEditor](ue_ue.LevelStreaming.md#bshouldbevisibleineditor)
- [bShouldBlockOnLoad](ue_ue.LevelStreaming.md#bshouldblockonload)
- [bShouldBlockOnUnload](ue_ue.LevelStreaming.md#bshouldblockonunload)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelStreaming.md#createdefaultsubobject)
- [CreateInstance](ue_ue.LevelStreaming.md#createinstance)
- [ExecuteUbergraph](ue_ue.LevelStreaming.md#executeubergraph)
- [GetClass](ue_ue.LevelStreaming.md#getclass)
- [GetLevelScriptActor](ue_ue.LevelStreaming.md#getlevelscriptactor)
- [GetLoadedLevel](ue_ue.LevelStreaming.md#getloadedlevel)
- [GetName](ue_ue.LevelStreaming.md#getname)
- [GetOuter](ue_ue.LevelStreaming.md#getouter)
- [GetWorld](ue_ue.LevelStreaming.md#getworld)
- [GetWorldAssetPackageFName](ue_ue.LevelStreaming.md#getworldassetpackagefname)
- [IsLevelLoaded](ue_ue.LevelStreaming.md#islevelloaded)
- [IsLevelVisible](ue_ue.LevelStreaming.md#islevelvisible)
- [IsStreamingStatePending](ue_ue.LevelStreaming.md#isstreamingstatepending)
- [SetLevelLODIndex](ue_ue.LevelStreaming.md#setlevellodindex)
- [SetPriority](ue_ue.LevelStreaming.md#setpriority)
- [SetShouldBeLoaded](ue_ue.LevelStreaming.md#setshouldbeloaded)
- [SetShouldBeVisible](ue_ue.LevelStreaming.md#setshouldbevisible)
- [ShouldBeLoaded](ue_ue.LevelStreaming.md#shouldbeloaded)
- [Find](ue_ue.LevelStreaming.md#find)
- [Load](ue_ue.LevelStreaming.md#load)
- [StaticClass](ue_ue.LevelStreaming.md#staticclass)

## Constructors

### constructor

• **new LevelStreaming**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DrawColor

• **DrawColor**: [`Color`](ue_ue_s.Color.md)

___

### EditorStreamingVolumes

• **EditorStreamingVolumes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreamingVolume`](ue_ue.LevelStreamingVolume.md)\>

___

### FolderPath

• **FolderPath**: `string`

___

### Keywords

• **Keywords**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### LODPackageNames

• **LODPackageNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### LevelColor

• **LevelColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LevelLODIndex

• **LevelLODIndex**: `number`

___

### LevelTransform

• **LevelTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### LoadedLevel

• **LoadedLevel**: [`Level`](ue_ue.Level.md)

___

### MinTimeBetweenVolumeUnloadRequests

• **MinTimeBetweenVolumeUnloadRequests**: `number`

___

### OnLevelHidden

• **OnLevelHidden**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnLevelLoaded

• **OnLevelLoaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnLevelShown

• **OnLevelShown**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnLevelUnloaded

• **OnLevelUnloaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### PackageName

• **PackageName**: `string`

___

### PackageNameToLoad

• **PackageNameToLoad**: `string`

___

### PendingUnloadLevel

• **PendingUnloadLevel**: [`Level`](ue_ue.Level.md)

___

### StreamingPriority

• **StreamingPriority**: `number`

___

### WorldAsset

• **WorldAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>

___

### \_\_tid\_LevelStreaming\_\_

• **\_\_tid\_LevelStreaming\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bDisableDistanceStreaming

• **bDisableDistanceStreaming**: `boolean`

___

### bDrawOnLevelStatusMap

• **bDrawOnLevelStatusMap**: `boolean`

___

### bIsStatic

• **bIsStatic**: `boolean`

___

### bLocked

• **bLocked**: `boolean`

___

### bShouldBeLoaded

• **bShouldBeLoaded**: `boolean`

___

### bShouldBeVisible

• **bShouldBeVisible**: `boolean`

___

### bShouldBeVisibleInEditor

• **bShouldBeVisibleInEditor**: `boolean`

___

### bShouldBlockOnLoad

• **bShouldBlockOnLoad**: `boolean`

___

### bShouldBlockOnUnload

• **bShouldBlockOnUnload**: `boolean`

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

### CreateInstance

▸ **CreateInstance**(`UniqueInstanceName`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `UniqueInstanceName` | `string` |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

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

### GetLevelScriptActor

▸ **GetLevelScriptActor**(): [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Returns

[`LevelScriptActor`](ue_ue.LevelScriptActor.md)

___

### GetLoadedLevel

▸ **GetLoadedLevel**(): [`Level`](ue_ue.Level.md)

#### Returns

[`Level`](ue_ue.Level.md)

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

### GetWorldAssetPackageFName

▸ **GetWorldAssetPackageFName**(): `string`

#### Returns

`string`

___

### IsLevelLoaded

▸ **IsLevelLoaded**(): `boolean`

#### Returns

`boolean`

___

### IsLevelVisible

▸ **IsLevelVisible**(): `boolean`

#### Returns

`boolean`

___

### IsStreamingStatePending

▸ **IsStreamingStatePending**(): `boolean`

#### Returns

`boolean`

___

### SetLevelLODIndex

▸ **SetLevelLODIndex**(`LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |

#### Returns

`void`

___

### SetPriority

▸ **SetPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

___

### SetShouldBeLoaded

▸ **SetShouldBeLoaded**(`bInShouldBeLoaded`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldBeLoaded` | `boolean` |

#### Returns

`void`

___

### SetShouldBeVisible

▸ **SetShouldBeVisible**(`bInShouldBeVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldBeVisible` | `boolean` |

#### Returns

`void`

___

### ShouldBeLoaded

▸ **ShouldBeLoaded**(): `boolean`

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
