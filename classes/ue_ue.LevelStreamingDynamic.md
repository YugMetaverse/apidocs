[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelStreamingDynamic

# Class: LevelStreamingDynamic

[ue/ue](../modules/ue_ue.md).LevelStreamingDynamic

## Hierarchy

- [`LevelStreaming`](ue_ue.LevelStreaming.md)

  ↳ **`LevelStreamingDynamic`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelStreamingDynamic.md#constructor)

### Properties

- [DrawColor](ue_ue.LevelStreamingDynamic.md#drawcolor)
- [EditorStreamingVolumes](ue_ue.LevelStreamingDynamic.md#editorstreamingvolumes)
- [FolderPath](ue_ue.LevelStreamingDynamic.md#folderpath)
- [Keywords](ue_ue.LevelStreamingDynamic.md#keywords)
- [LODPackageNames](ue_ue.LevelStreamingDynamic.md#lodpackagenames)
- [LevelColor](ue_ue.LevelStreamingDynamic.md#levelcolor)
- [LevelLODIndex](ue_ue.LevelStreamingDynamic.md#levellodindex)
- [LevelTransform](ue_ue.LevelStreamingDynamic.md#leveltransform)
- [LoadedLevel](ue_ue.LevelStreamingDynamic.md#loadedlevel)
- [MinTimeBetweenVolumeUnloadRequests](ue_ue.LevelStreamingDynamic.md#mintimebetweenvolumeunloadrequests)
- [OnLevelHidden](ue_ue.LevelStreamingDynamic.md#onlevelhidden)
- [OnLevelLoaded](ue_ue.LevelStreamingDynamic.md#onlevelloaded)
- [OnLevelShown](ue_ue.LevelStreamingDynamic.md#onlevelshown)
- [OnLevelUnloaded](ue_ue.LevelStreamingDynamic.md#onlevelunloaded)
- [PackageName](ue_ue.LevelStreamingDynamic.md#packagename)
- [PackageNameToLoad](ue_ue.LevelStreamingDynamic.md#packagenametoload)
- [PendingUnloadLevel](ue_ue.LevelStreamingDynamic.md#pendingunloadlevel)
- [StreamingPriority](ue_ue.LevelStreamingDynamic.md#streamingpriority)
- [WorldAsset](ue_ue.LevelStreamingDynamic.md#worldasset)
- [\_\_tid\_LevelStreamingDynamic\_\_](ue_ue.LevelStreamingDynamic.md#__tid_levelstreamingdynamic__)
- [\_\_tid\_LevelStreaming\_\_](ue_ue.LevelStreamingDynamic.md#__tid_levelstreaming__)
- [\_\_tid\_Object\_\_](ue_ue.LevelStreamingDynamic.md#__tid_object__)
- [bDisableDistanceStreaming](ue_ue.LevelStreamingDynamic.md#bdisabledistancestreaming)
- [bDrawOnLevelStatusMap](ue_ue.LevelStreamingDynamic.md#bdrawonlevelstatusmap)
- [bInitiallyLoaded](ue_ue.LevelStreamingDynamic.md#binitiallyloaded)
- [bInitiallyVisible](ue_ue.LevelStreamingDynamic.md#binitiallyvisible)
- [bIsStatic](ue_ue.LevelStreamingDynamic.md#bisstatic)
- [bLocked](ue_ue.LevelStreamingDynamic.md#blocked)
- [bShouldBeLoaded](ue_ue.LevelStreamingDynamic.md#bshouldbeloaded)
- [bShouldBeVisible](ue_ue.LevelStreamingDynamic.md#bshouldbevisible)
- [bShouldBeVisibleInEditor](ue_ue.LevelStreamingDynamic.md#bshouldbevisibleineditor)
- [bShouldBlockOnLoad](ue_ue.LevelStreamingDynamic.md#bshouldblockonload)
- [bShouldBlockOnUnload](ue_ue.LevelStreamingDynamic.md#bshouldblockonunload)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelStreamingDynamic.md#createdefaultsubobject)
- [CreateInstance](ue_ue.LevelStreamingDynamic.md#createinstance)
- [ExecuteUbergraph](ue_ue.LevelStreamingDynamic.md#executeubergraph)
- [GetClass](ue_ue.LevelStreamingDynamic.md#getclass)
- [GetLevelScriptActor](ue_ue.LevelStreamingDynamic.md#getlevelscriptactor)
- [GetLoadedLevel](ue_ue.LevelStreamingDynamic.md#getloadedlevel)
- [GetName](ue_ue.LevelStreamingDynamic.md#getname)
- [GetOuter](ue_ue.LevelStreamingDynamic.md#getouter)
- [GetWorld](ue_ue.LevelStreamingDynamic.md#getworld)
- [GetWorldAssetPackageFName](ue_ue.LevelStreamingDynamic.md#getworldassetpackagefname)
- [IsLevelLoaded](ue_ue.LevelStreamingDynamic.md#islevelloaded)
- [IsLevelVisible](ue_ue.LevelStreamingDynamic.md#islevelvisible)
- [IsStreamingStatePending](ue_ue.LevelStreamingDynamic.md#isstreamingstatepending)
- [SetLevelLODIndex](ue_ue.LevelStreamingDynamic.md#setlevellodindex)
- [SetPriority](ue_ue.LevelStreamingDynamic.md#setpriority)
- [SetShouldBeLoaded](ue_ue.LevelStreamingDynamic.md#setshouldbeloaded)
- [SetShouldBeVisible](ue_ue.LevelStreamingDynamic.md#setshouldbevisible)
- [ShouldBeLoaded](ue_ue.LevelStreamingDynamic.md#shouldbeloaded)
- [Find](ue_ue.LevelStreamingDynamic.md#find)
- [Load](ue_ue.LevelStreamingDynamic.md#load)
- [LoadLevelInstance](ue_ue.LevelStreamingDynamic.md#loadlevelinstance)
- [LoadLevelInstanceBySoftObjectPtr](ue_ue.LevelStreamingDynamic.md#loadlevelinstancebysoftobjectptr)
- [StaticClass](ue_ue.LevelStreamingDynamic.md#staticclass)

## Constructors

### constructor

• **new LevelStreamingDynamic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[constructor](ue_ue.LevelStreaming.md#constructor)

## Properties

### DrawColor

• **DrawColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[DrawColor](ue_ue.LevelStreaming.md#drawcolor)

___

### EditorStreamingVolumes

• **EditorStreamingVolumes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreamingVolume`](ue_ue.LevelStreamingVolume.md)\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[EditorStreamingVolumes](ue_ue.LevelStreaming.md#editorstreamingvolumes)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[FolderPath](ue_ue.LevelStreaming.md#folderpath)

___

### Keywords

• **Keywords**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[Keywords](ue_ue.LevelStreaming.md#keywords)

___

### LODPackageNames

• **LODPackageNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LODPackageNames](ue_ue.LevelStreaming.md#lodpackagenames)

___

### LevelColor

• **LevelColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LevelColor](ue_ue.LevelStreaming.md#levelcolor)

___

### LevelLODIndex

• **LevelLODIndex**: `number`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LevelLODIndex](ue_ue.LevelStreaming.md#levellodindex)

___

### LevelTransform

• **LevelTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LevelTransform](ue_ue.LevelStreaming.md#leveltransform)

___

### LoadedLevel

• **LoadedLevel**: [`Level`](ue_ue.Level.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LoadedLevel](ue_ue.LevelStreaming.md#loadedlevel)

___

### MinTimeBetweenVolumeUnloadRequests

• **MinTimeBetweenVolumeUnloadRequests**: `number`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[MinTimeBetweenVolumeUnloadRequests](ue_ue.LevelStreaming.md#mintimebetweenvolumeunloadrequests)

___

### OnLevelHidden

• **OnLevelHidden**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelHidden](ue_ue.LevelStreaming.md#onlevelhidden)

___

### OnLevelLoaded

• **OnLevelLoaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelLoaded](ue_ue.LevelStreaming.md#onlevelloaded)

___

### OnLevelShown

• **OnLevelShown**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelShown](ue_ue.LevelStreaming.md#onlevelshown)

___

### OnLevelUnloaded

• **OnLevelUnloaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelUnloaded](ue_ue.LevelStreaming.md#onlevelunloaded)

___

### PackageName

• **PackageName**: `string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[PackageName](ue_ue.LevelStreaming.md#packagename)

___

### PackageNameToLoad

• **PackageNameToLoad**: `string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[PackageNameToLoad](ue_ue.LevelStreaming.md#packagenametoload)

___

### PendingUnloadLevel

• **PendingUnloadLevel**: [`Level`](ue_ue.Level.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[PendingUnloadLevel](ue_ue.LevelStreaming.md#pendingunloadlevel)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[StreamingPriority](ue_ue.LevelStreaming.md#streamingpriority)

___

### WorldAsset

• **WorldAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[WorldAsset](ue_ue.LevelStreaming.md#worldasset)

___

### \_\_tid\_LevelStreamingDynamic\_\_

• **\_\_tid\_LevelStreamingDynamic\_\_**: `boolean`

___

### \_\_tid\_LevelStreaming\_\_

• **\_\_tid\_LevelStreaming\_\_**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[__tid_LevelStreaming__](ue_ue.LevelStreaming.md#__tid_levelstreaming__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[__tid_Object__](ue_ue.LevelStreaming.md#__tid_object__)

___

### bDisableDistanceStreaming

• **bDisableDistanceStreaming**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bDisableDistanceStreaming](ue_ue.LevelStreaming.md#bdisabledistancestreaming)

___

### bDrawOnLevelStatusMap

• **bDrawOnLevelStatusMap**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bDrawOnLevelStatusMap](ue_ue.LevelStreaming.md#bdrawonlevelstatusmap)

___

### bInitiallyLoaded

• **bInitiallyLoaded**: `boolean`

___

### bInitiallyVisible

• **bInitiallyVisible**: `boolean`

___

### bIsStatic

• **bIsStatic**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bIsStatic](ue_ue.LevelStreaming.md#bisstatic)

___

### bLocked

• **bLocked**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bLocked](ue_ue.LevelStreaming.md#blocked)

___

### bShouldBeLoaded

• **bShouldBeLoaded**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBeLoaded](ue_ue.LevelStreaming.md#bshouldbeloaded)

___

### bShouldBeVisible

• **bShouldBeVisible**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBeVisible](ue_ue.LevelStreaming.md#bshouldbevisible)

___

### bShouldBeVisibleInEditor

• **bShouldBeVisibleInEditor**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBeVisibleInEditor](ue_ue.LevelStreaming.md#bshouldbevisibleineditor)

___

### bShouldBlockOnLoad

• **bShouldBlockOnLoad**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBlockOnLoad](ue_ue.LevelStreaming.md#bshouldblockonload)

___

### bShouldBlockOnUnload

• **bShouldBlockOnUnload**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBlockOnUnload](ue_ue.LevelStreaming.md#bshouldblockonunload)

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

[LevelStreaming](ue_ue.LevelStreaming.md).[CreateDefaultSubobject](ue_ue.LevelStreaming.md#createdefaultsubobject)

___

### CreateInstance

▸ **CreateInstance**(`UniqueInstanceName`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `UniqueInstanceName` | `string` |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[CreateInstance](ue_ue.LevelStreaming.md#createinstance)

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

[LevelStreaming](ue_ue.LevelStreaming.md).[ExecuteUbergraph](ue_ue.LevelStreaming.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetClass](ue_ue.LevelStreaming.md#getclass)

___

### GetLevelScriptActor

▸ **GetLevelScriptActor**(): [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Returns

[`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetLevelScriptActor](ue_ue.LevelStreaming.md#getlevelscriptactor)

___

### GetLoadedLevel

▸ **GetLoadedLevel**(): [`Level`](ue_ue.Level.md)

#### Returns

[`Level`](ue_ue.Level.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetLoadedLevel](ue_ue.LevelStreaming.md#getloadedlevel)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetName](ue_ue.LevelStreaming.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetOuter](ue_ue.LevelStreaming.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetWorld](ue_ue.LevelStreaming.md#getworld)

___

### GetWorldAssetPackageFName

▸ **GetWorldAssetPackageFName**(): `string`

#### Returns

`string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetWorldAssetPackageFName](ue_ue.LevelStreaming.md#getworldassetpackagefname)

___

### IsLevelLoaded

▸ **IsLevelLoaded**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[IsLevelLoaded](ue_ue.LevelStreaming.md#islevelloaded)

___

### IsLevelVisible

▸ **IsLevelVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[IsLevelVisible](ue_ue.LevelStreaming.md#islevelvisible)

___

### IsStreamingStatePending

▸ **IsStreamingStatePending**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[IsStreamingStatePending](ue_ue.LevelStreaming.md#isstreamingstatepending)

___

### SetLevelLODIndex

▸ **SetLevelLODIndex**(`LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |

#### Returns

`void`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetLevelLODIndex](ue_ue.LevelStreaming.md#setlevellodindex)

___

### SetPriority

▸ **SetPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetPriority](ue_ue.LevelStreaming.md#setpriority)

___

### SetShouldBeLoaded

▸ **SetShouldBeLoaded**(`bInShouldBeLoaded`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldBeLoaded` | `boolean` |

#### Returns

`void`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetShouldBeLoaded](ue_ue.LevelStreaming.md#setshouldbeloaded)

___

### SetShouldBeVisible

▸ **SetShouldBeVisible**(`bInShouldBeVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldBeVisible` | `boolean` |

#### Returns

`void`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetShouldBeVisible](ue_ue.LevelStreaming.md#setshouldbevisible)

___

### ShouldBeLoaded

▸ **ShouldBeLoaded**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[ShouldBeLoaded](ue_ue.LevelStreaming.md#shouldbeloaded)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[Find](ue_ue.LevelStreaming.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[Load](ue_ue.LevelStreaming.md#load)

___

### LoadLevelInstance

▸ `Static` **LoadLevelInstance**(`WorldContextObject`, `LevelName`, `Location`, `Rotation`, `bOutSuccess`): [`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LevelName` | `string` |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bOutSuccess` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

[`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

___

### LoadLevelInstanceBySoftObjectPtr

▸ `Static` **LoadLevelInstanceBySoftObjectPtr**(`WorldContextObject`, `Level`, `Location`, `Rotation`, `bOutSuccess`): [`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Level` | [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bOutSuccess` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

[`LevelStreamingDynamic`](ue_ue.LevelStreamingDynamic.md)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[StaticClass](ue_ue.LevelStreaming.md#staticclass)
