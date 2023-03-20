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

#### Defined in

[ue/ue.d.ts:9777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9777)

## Properties

### DrawColor

• **DrawColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:9794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9794)

___

### EditorStreamingVolumes

• **EditorStreamingVolumes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreamingVolume`](ue_ue.LevelStreamingVolume.md)\>

#### Defined in

[ue/ue.d.ts:9796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9796)

___

### FolderPath

• **FolderPath**: `string`

#### Defined in

[ue/ue.d.ts:9805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9805)

___

### Keywords

• **Keywords**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:9798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9798)

___

### LODPackageNames

• **LODPackageNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:9781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9781)

___

### LevelColor

• **LevelColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:9795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9795)

___

### LevelLODIndex

• **LevelLODIndex**: `number`

#### Defined in

[ue/ue.d.ts:9783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9783)

___

### LevelTransform

• **LevelTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:9782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9782)

___

### LoadedLevel

• **LoadedLevel**: [`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:9803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9803)

___

### MinTimeBetweenVolumeUnloadRequests

• **MinTimeBetweenVolumeUnloadRequests**: `number`

#### Defined in

[ue/ue.d.ts:9797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9797)

___

### OnLevelHidden

• **OnLevelHidden**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:9802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9802)

___

### OnLevelLoaded

• **OnLevelLoaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:9799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9799)

___

### OnLevelShown

• **OnLevelShown**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:9801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9801)

___

### OnLevelUnloaded

• **OnLevelUnloaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:9800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9800)

___

### PackageName

• **PackageName**: `string`

#### Defined in

[ue/ue.d.ts:9778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9778)

___

### PackageNameToLoad

• **PackageNameToLoad**: `string`

#### Defined in

[ue/ue.d.ts:9780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9780)

___

### PendingUnloadLevel

• **PendingUnloadLevel**: [`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:9804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9804)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Defined in

[ue/ue.d.ts:9784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9784)

___

### WorldAsset

• **WorldAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>

#### Defined in

[ue/ue.d.ts:9779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9779)

___

### \_\_tid\_LevelStreaming\_\_

• **\_\_tid\_LevelStreaming\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9822)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDisableDistanceStreaming

• **bDisableDistanceStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:9792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9792)

___

### bDrawOnLevelStatusMap

• **bDrawOnLevelStatusMap**: `boolean`

#### Defined in

[ue/ue.d.ts:9793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9793)

___

### bIsStatic

• **bIsStatic**: `boolean`

#### Defined in

[ue/ue.d.ts:9789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9789)

___

### bLocked

• **bLocked**: `boolean`

#### Defined in

[ue/ue.d.ts:9788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9788)

___

### bShouldBeLoaded

• **bShouldBeLoaded**: `boolean`

#### Defined in

[ue/ue.d.ts:9787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9787)

___

### bShouldBeVisible

• **bShouldBeVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:9786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9786)

___

### bShouldBeVisibleInEditor

• **bShouldBeVisibleInEditor**: `boolean`

#### Defined in

[ue/ue.d.ts:9785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9785)

___

### bShouldBlockOnLoad

• **bShouldBlockOnLoad**: `boolean`

#### Defined in

[ue/ue.d.ts:9790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9790)

___

### bShouldBlockOnUnload

• **bShouldBlockOnUnload**: `boolean`

#### Defined in

[ue/ue.d.ts:9791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9791)

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

### CreateInstance

▸ **CreateInstance**(`UniqueInstanceName`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `UniqueInstanceName` | `string` |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Defined in

[ue/ue.d.ts:9806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9806)

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

### GetLevelScriptActor

▸ **GetLevelScriptActor**(): [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Returns

[`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Defined in

[ue/ue.d.ts:9807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9807)

___

### GetLoadedLevel

▸ **GetLoadedLevel**(): [`Level`](ue_ue.Level.md)

#### Returns

[`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:9808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9808)

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

### GetWorldAssetPackageFName

▸ **GetWorldAssetPackageFName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:9809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9809)

___

### IsLevelLoaded

▸ **IsLevelLoaded**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:9810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9810)

___

### IsLevelVisible

▸ **IsLevelVisible**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:9811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9811)

___

### IsStreamingStatePending

▸ **IsStreamingStatePending**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:9812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9812)

___

### SetLevelLODIndex

▸ **SetLevelLODIndex**(`LODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LODIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:9813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9813)

___

### SetPriority

▸ **SetPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:9814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9814)

___

### SetShouldBeLoaded

▸ **SetShouldBeLoaded**(`bInShouldBeLoaded`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldBeLoaded` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:9815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9815)

___

### SetShouldBeVisible

▸ **SetShouldBeVisible**(`bInShouldBeVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldBeVisible` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:9816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9816)

___

### ShouldBeLoaded

▸ **ShouldBeLoaded**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:9817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9817)

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

#### Defined in

[ue/ue.d.ts:9819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9819)

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

#### Defined in

[ue/ue.d.ts:9820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9820)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:9818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9818)
