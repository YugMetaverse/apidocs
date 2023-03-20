[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelStreamingPersistent

# Class: LevelStreamingPersistent

[ue/ue](../modules/ue_ue.md).LevelStreamingPersistent

## Hierarchy

- [`LevelStreaming`](ue_ue.LevelStreaming.md)

  ↳ **`LevelStreamingPersistent`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelStreamingPersistent.md#constructor)

### Properties

- [DrawColor](ue_ue.LevelStreamingPersistent.md#drawcolor)
- [EditorStreamingVolumes](ue_ue.LevelStreamingPersistent.md#editorstreamingvolumes)
- [FolderPath](ue_ue.LevelStreamingPersistent.md#folderpath)
- [Keywords](ue_ue.LevelStreamingPersistent.md#keywords)
- [LODPackageNames](ue_ue.LevelStreamingPersistent.md#lodpackagenames)
- [LevelColor](ue_ue.LevelStreamingPersistent.md#levelcolor)
- [LevelLODIndex](ue_ue.LevelStreamingPersistent.md#levellodindex)
- [LevelTransform](ue_ue.LevelStreamingPersistent.md#leveltransform)
- [LoadedLevel](ue_ue.LevelStreamingPersistent.md#loadedlevel)
- [MinTimeBetweenVolumeUnloadRequests](ue_ue.LevelStreamingPersistent.md#mintimebetweenvolumeunloadrequests)
- [OnLevelHidden](ue_ue.LevelStreamingPersistent.md#onlevelhidden)
- [OnLevelLoaded](ue_ue.LevelStreamingPersistent.md#onlevelloaded)
- [OnLevelShown](ue_ue.LevelStreamingPersistent.md#onlevelshown)
- [OnLevelUnloaded](ue_ue.LevelStreamingPersistent.md#onlevelunloaded)
- [PackageName](ue_ue.LevelStreamingPersistent.md#packagename)
- [PackageNameToLoad](ue_ue.LevelStreamingPersistent.md#packagenametoload)
- [PendingUnloadLevel](ue_ue.LevelStreamingPersistent.md#pendingunloadlevel)
- [StreamingPriority](ue_ue.LevelStreamingPersistent.md#streamingpriority)
- [WorldAsset](ue_ue.LevelStreamingPersistent.md#worldasset)
- [\_\_tid\_LevelStreamingPersistent\_\_](ue_ue.LevelStreamingPersistent.md#__tid_levelstreamingpersistent__)
- [\_\_tid\_LevelStreaming\_\_](ue_ue.LevelStreamingPersistent.md#__tid_levelstreaming__)
- [\_\_tid\_Object\_\_](ue_ue.LevelStreamingPersistent.md#__tid_object__)
- [bDisableDistanceStreaming](ue_ue.LevelStreamingPersistent.md#bdisabledistancestreaming)
- [bDrawOnLevelStatusMap](ue_ue.LevelStreamingPersistent.md#bdrawonlevelstatusmap)
- [bIsStatic](ue_ue.LevelStreamingPersistent.md#bisstatic)
- [bLocked](ue_ue.LevelStreamingPersistent.md#blocked)
- [bShouldBeLoaded](ue_ue.LevelStreamingPersistent.md#bshouldbeloaded)
- [bShouldBeVisible](ue_ue.LevelStreamingPersistent.md#bshouldbevisible)
- [bShouldBeVisibleInEditor](ue_ue.LevelStreamingPersistent.md#bshouldbevisibleineditor)
- [bShouldBlockOnLoad](ue_ue.LevelStreamingPersistent.md#bshouldblockonload)
- [bShouldBlockOnUnload](ue_ue.LevelStreamingPersistent.md#bshouldblockonunload)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelStreamingPersistent.md#createdefaultsubobject)
- [CreateInstance](ue_ue.LevelStreamingPersistent.md#createinstance)
- [ExecuteUbergraph](ue_ue.LevelStreamingPersistent.md#executeubergraph)
- [GetClass](ue_ue.LevelStreamingPersistent.md#getclass)
- [GetLevelScriptActor](ue_ue.LevelStreamingPersistent.md#getlevelscriptactor)
- [GetLoadedLevel](ue_ue.LevelStreamingPersistent.md#getloadedlevel)
- [GetName](ue_ue.LevelStreamingPersistent.md#getname)
- [GetOuter](ue_ue.LevelStreamingPersistent.md#getouter)
- [GetWorld](ue_ue.LevelStreamingPersistent.md#getworld)
- [GetWorldAssetPackageFName](ue_ue.LevelStreamingPersistent.md#getworldassetpackagefname)
- [IsLevelLoaded](ue_ue.LevelStreamingPersistent.md#islevelloaded)
- [IsLevelVisible](ue_ue.LevelStreamingPersistent.md#islevelvisible)
- [IsStreamingStatePending](ue_ue.LevelStreamingPersistent.md#isstreamingstatepending)
- [SetLevelLODIndex](ue_ue.LevelStreamingPersistent.md#setlevellodindex)
- [SetPriority](ue_ue.LevelStreamingPersistent.md#setpriority)
- [SetShouldBeLoaded](ue_ue.LevelStreamingPersistent.md#setshouldbeloaded)
- [SetShouldBeVisible](ue_ue.LevelStreamingPersistent.md#setshouldbevisible)
- [ShouldBeLoaded](ue_ue.LevelStreamingPersistent.md#shouldbeloaded)
- [Find](ue_ue.LevelStreamingPersistent.md#find)
- [Load](ue_ue.LevelStreamingPersistent.md#load)
- [StaticClass](ue_ue.LevelStreamingPersistent.md#staticclass)

## Constructors

### constructor

• **new LevelStreamingPersistent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[constructor](ue_ue.LevelStreaming.md#constructor)

#### Defined in

[ue/ue.d.ts:45302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45302)

## Properties

### DrawColor

• **DrawColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[DrawColor](ue_ue.LevelStreaming.md#drawcolor)

#### Defined in

[ue/ue.d.ts:9794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9794)

___

### EditorStreamingVolumes

• **EditorStreamingVolumes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreamingVolume`](ue_ue.LevelStreamingVolume.md)\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[EditorStreamingVolumes](ue_ue.LevelStreaming.md#editorstreamingvolumes)

#### Defined in

[ue/ue.d.ts:9796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9796)

___

### FolderPath

• **FolderPath**: `string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[FolderPath](ue_ue.LevelStreaming.md#folderpath)

#### Defined in

[ue/ue.d.ts:9805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9805)

___

### Keywords

• **Keywords**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[Keywords](ue_ue.LevelStreaming.md#keywords)

#### Defined in

[ue/ue.d.ts:9798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9798)

___

### LODPackageNames

• **LODPackageNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LODPackageNames](ue_ue.LevelStreaming.md#lodpackagenames)

#### Defined in

[ue/ue.d.ts:9781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9781)

___

### LevelColor

• **LevelColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LevelColor](ue_ue.LevelStreaming.md#levelcolor)

#### Defined in

[ue/ue.d.ts:9795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9795)

___

### LevelLODIndex

• **LevelLODIndex**: `number`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LevelLODIndex](ue_ue.LevelStreaming.md#levellodindex)

#### Defined in

[ue/ue.d.ts:9783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9783)

___

### LevelTransform

• **LevelTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LevelTransform](ue_ue.LevelStreaming.md#leveltransform)

#### Defined in

[ue/ue.d.ts:9782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9782)

___

### LoadedLevel

• **LoadedLevel**: [`Level`](ue_ue.Level.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[LoadedLevel](ue_ue.LevelStreaming.md#loadedlevel)

#### Defined in

[ue/ue.d.ts:9803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9803)

___

### MinTimeBetweenVolumeUnloadRequests

• **MinTimeBetweenVolumeUnloadRequests**: `number`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[MinTimeBetweenVolumeUnloadRequests](ue_ue.LevelStreaming.md#mintimebetweenvolumeunloadrequests)

#### Defined in

[ue/ue.d.ts:9797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9797)

___

### OnLevelHidden

• **OnLevelHidden**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelHidden](ue_ue.LevelStreaming.md#onlevelhidden)

#### Defined in

[ue/ue.d.ts:9802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9802)

___

### OnLevelLoaded

• **OnLevelLoaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelLoaded](ue_ue.LevelStreaming.md#onlevelloaded)

#### Defined in

[ue/ue.d.ts:9799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9799)

___

### OnLevelShown

• **OnLevelShown**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelShown](ue_ue.LevelStreaming.md#onlevelshown)

#### Defined in

[ue/ue.d.ts:9801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9801)

___

### OnLevelUnloaded

• **OnLevelUnloaded**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[OnLevelUnloaded](ue_ue.LevelStreaming.md#onlevelunloaded)

#### Defined in

[ue/ue.d.ts:9800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9800)

___

### PackageName

• **PackageName**: `string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[PackageName](ue_ue.LevelStreaming.md#packagename)

#### Defined in

[ue/ue.d.ts:9778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9778)

___

### PackageNameToLoad

• **PackageNameToLoad**: `string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[PackageNameToLoad](ue_ue.LevelStreaming.md#packagenametoload)

#### Defined in

[ue/ue.d.ts:9780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9780)

___

### PendingUnloadLevel

• **PendingUnloadLevel**: [`Level`](ue_ue.Level.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[PendingUnloadLevel](ue_ue.LevelStreaming.md#pendingunloadlevel)

#### Defined in

[ue/ue.d.ts:9804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9804)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[StreamingPriority](ue_ue.LevelStreaming.md#streamingpriority)

#### Defined in

[ue/ue.d.ts:9784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9784)

___

### WorldAsset

• **WorldAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[WorldAsset](ue_ue.LevelStreaming.md#worldasset)

#### Defined in

[ue/ue.d.ts:9779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9779)

___

### \_\_tid\_LevelStreamingPersistent\_\_

• **\_\_tid\_LevelStreamingPersistent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45307)

___

### \_\_tid\_LevelStreaming\_\_

• **\_\_tid\_LevelStreaming\_\_**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[__tid_LevelStreaming__](ue_ue.LevelStreaming.md#__tid_levelstreaming__)

#### Defined in

[ue/ue.d.ts:9822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9822)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[__tid_Object__](ue_ue.LevelStreaming.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDisableDistanceStreaming

• **bDisableDistanceStreaming**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bDisableDistanceStreaming](ue_ue.LevelStreaming.md#bdisabledistancestreaming)

#### Defined in

[ue/ue.d.ts:9792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9792)

___

### bDrawOnLevelStatusMap

• **bDrawOnLevelStatusMap**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bDrawOnLevelStatusMap](ue_ue.LevelStreaming.md#bdrawonlevelstatusmap)

#### Defined in

[ue/ue.d.ts:9793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9793)

___

### bIsStatic

• **bIsStatic**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bIsStatic](ue_ue.LevelStreaming.md#bisstatic)

#### Defined in

[ue/ue.d.ts:9789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9789)

___

### bLocked

• **bLocked**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bLocked](ue_ue.LevelStreaming.md#blocked)

#### Defined in

[ue/ue.d.ts:9788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9788)

___

### bShouldBeLoaded

• **bShouldBeLoaded**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBeLoaded](ue_ue.LevelStreaming.md#bshouldbeloaded)

#### Defined in

[ue/ue.d.ts:9787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9787)

___

### bShouldBeVisible

• **bShouldBeVisible**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBeVisible](ue_ue.LevelStreaming.md#bshouldbevisible)

#### Defined in

[ue/ue.d.ts:9786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9786)

___

### bShouldBeVisibleInEditor

• **bShouldBeVisibleInEditor**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBeVisibleInEditor](ue_ue.LevelStreaming.md#bshouldbevisibleineditor)

#### Defined in

[ue/ue.d.ts:9785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9785)

___

### bShouldBlockOnLoad

• **bShouldBlockOnLoad**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBlockOnLoad](ue_ue.LevelStreaming.md#bshouldblockonload)

#### Defined in

[ue/ue.d.ts:9790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9790)

___

### bShouldBlockOnUnload

• **bShouldBlockOnUnload**: `boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[bShouldBlockOnUnload](ue_ue.LevelStreaming.md#bshouldblockonunload)

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

[LevelStreaming](ue_ue.LevelStreaming.md).[CreateDefaultSubobject](ue_ue.LevelStreaming.md#createdefaultsubobject)

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

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[CreateInstance](ue_ue.LevelStreaming.md#createinstance)

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

[LevelStreaming](ue_ue.LevelStreaming.md).[ExecuteUbergraph](ue_ue.LevelStreaming.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetClass](ue_ue.LevelStreaming.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetLevelScriptActor

▸ **GetLevelScriptActor**(): [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Returns

[`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetLevelScriptActor](ue_ue.LevelStreaming.md#getlevelscriptactor)

#### Defined in

[ue/ue.d.ts:9807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9807)

___

### GetLoadedLevel

▸ **GetLoadedLevel**(): [`Level`](ue_ue.Level.md)

#### Returns

[`Level`](ue_ue.Level.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetLoadedLevel](ue_ue.LevelStreaming.md#getloadedlevel)

#### Defined in

[ue/ue.d.ts:9808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9808)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetName](ue_ue.LevelStreaming.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetOuter](ue_ue.LevelStreaming.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetWorld](ue_ue.LevelStreaming.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### GetWorldAssetPackageFName

▸ **GetWorldAssetPackageFName**(): `string`

#### Returns

`string`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[GetWorldAssetPackageFName](ue_ue.LevelStreaming.md#getworldassetpackagefname)

#### Defined in

[ue/ue.d.ts:9809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9809)

___

### IsLevelLoaded

▸ **IsLevelLoaded**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[IsLevelLoaded](ue_ue.LevelStreaming.md#islevelloaded)

#### Defined in

[ue/ue.d.ts:9810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9810)

___

### IsLevelVisible

▸ **IsLevelVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[IsLevelVisible](ue_ue.LevelStreaming.md#islevelvisible)

#### Defined in

[ue/ue.d.ts:9811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9811)

___

### IsStreamingStatePending

▸ **IsStreamingStatePending**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[IsStreamingStatePending](ue_ue.LevelStreaming.md#isstreamingstatepending)

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

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetLevelLODIndex](ue_ue.LevelStreaming.md#setlevellodindex)

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

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetPriority](ue_ue.LevelStreaming.md#setpriority)

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

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetShouldBeLoaded](ue_ue.LevelStreaming.md#setshouldbeloaded)

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

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[SetShouldBeVisible](ue_ue.LevelStreaming.md#setshouldbevisible)

#### Defined in

[ue/ue.d.ts:9816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9816)

___

### ShouldBeLoaded

▸ **ShouldBeLoaded**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LevelStreaming](ue_ue.LevelStreaming.md).[ShouldBeLoaded](ue_ue.LevelStreaming.md#shouldbeloaded)

#### Defined in

[ue/ue.d.ts:9817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9817)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelStreamingPersistent`](ue_ue.LevelStreamingPersistent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelStreamingPersistent`](ue_ue.LevelStreamingPersistent.md)

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[Find](ue_ue.LevelStreaming.md#find)

#### Defined in

[ue/ue.d.ts:45304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45304)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelStreamingPersistent`](ue_ue.LevelStreamingPersistent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelStreamingPersistent`](ue_ue.LevelStreamingPersistent.md)

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[Load](ue_ue.LevelStreaming.md#load)

#### Defined in

[ue/ue.d.ts:45305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45305)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LevelStreaming](ue_ue.LevelStreaming.md).[StaticClass](ue_ue.LevelStreaming.md#staticclass)

#### Defined in

[ue/ue.d.ts:45303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45303)
