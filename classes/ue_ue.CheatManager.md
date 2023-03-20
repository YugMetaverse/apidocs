[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CheatManager

# Class: CheatManager

[ue/ue](../modules/ue_ue.md).CheatManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CheatManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.CheatManager.md#constructor)

### Properties

- [DebugCameraControllerClass](ue_ue.CheatManager.md#debugcameracontrollerclass)
- [DebugCameraControllerRef](ue_ue.CheatManager.md#debugcameracontrollerref)
- [\_\_tid\_CheatManager\_\_](ue_ue.CheatManager.md#__tid_cheatmanager__)
- [\_\_tid\_Object\_\_](ue_ue.CheatManager.md#__tid_object__)

### Methods

- [BugIt](ue_ue.CheatManager.md#bugit)
- [BugItGo](ue_ue.CheatManager.md#bugitgo)
- [BugItStringCreator](ue_ue.CheatManager.md#bugitstringcreator)
- [ChangeSize](ue_ue.CheatManager.md#changesize)
- [CheatScript](ue_ue.CheatManager.md#cheatscript)
- [CreateDefaultSubobject](ue_ue.CheatManager.md#createdefaultsubobject)
- [DamageTarget](ue_ue.CheatManager.md#damagetarget)
- [DebugCapsuleSweep](ue_ue.CheatManager.md#debugcapsulesweep)
- [DebugCapsuleSweepCapture](ue_ue.CheatManager.md#debugcapsulesweepcapture)
- [DebugCapsuleSweepChannel](ue_ue.CheatManager.md#debugcapsulesweepchannel)
- [DebugCapsuleSweepClear](ue_ue.CheatManager.md#debugcapsulesweepclear)
- [DebugCapsuleSweepComplex](ue_ue.CheatManager.md#debugcapsulesweepcomplex)
- [DebugCapsuleSweepPawn](ue_ue.CheatManager.md#debugcapsulesweeppawn)
- [DebugCapsuleSweepSize](ue_ue.CheatManager.md#debugcapsulesweepsize)
- [DestroyAll](ue_ue.CheatManager.md#destroyall)
- [DestroyAllPawnsExceptTarget](ue_ue.CheatManager.md#destroyallpawnsexcepttarget)
- [DestroyPawns](ue_ue.CheatManager.md#destroypawns)
- [DestroyServerStatReplicator](ue_ue.CheatManager.md#destroyserverstatreplicator)
- [DestroyTarget](ue_ue.CheatManager.md#destroytarget)
- [DisableDebugCamera](ue_ue.CheatManager.md#disabledebugcamera)
- [DumpChatState](ue_ue.CheatManager.md#dumpchatstate)
- [DumpOnlineSessionState](ue_ue.CheatManager.md#dumponlinesessionstate)
- [DumpPartyState](ue_ue.CheatManager.md#dumppartystate)
- [DumpVoiceMutingState](ue_ue.CheatManager.md#dumpvoicemutingstate)
- [EnableDebugCamera](ue_ue.CheatManager.md#enabledebugcamera)
- [ExecuteUbergraph](ue_ue.CheatManager.md#executeubergraph)
- [FlushLog](ue_ue.CheatManager.md#flushlog)
- [Fly](ue_ue.CheatManager.md#fly)
- [FreezeFrame](ue_ue.CheatManager.md#freezeframe)
- [GetClass](ue_ue.CheatManager.md#getclass)
- [GetName](ue_ue.CheatManager.md#getname)
- [GetOuter](ue_ue.CheatManager.md#getouter)
- [GetWorld](ue_ue.CheatManager.md#getworld)
- [Ghost](ue_ue.CheatManager.md#ghost)
- [God](ue_ue.CheatManager.md#god)
- [InvertMouse](ue_ue.CheatManager.md#invertmouse)
- [LogLoc](ue_ue.CheatManager.md#logloc)
- [OnlyLoadLevel](ue_ue.CheatManager.md#onlyloadlevel)
- [PlayersOnly](ue_ue.CheatManager.md#playersonly)
- [ReceiveEndPlay](ue_ue.CheatManager.md#receiveendplay)
- [ReceiveInitCheatManager](ue_ue.CheatManager.md#receiveinitcheatmanager)
- [ServerToggleAILogging](ue_ue.CheatManager.md#servertoggleailogging)
- [SetMouseSensitivityToDefault](ue_ue.CheatManager.md#setmousesensitivitytodefault)
- [SetWorldOrigin](ue_ue.CheatManager.md#setworldorigin)
- [Slomo](ue_ue.CheatManager.md#slomo)
- [SpawnServerStatReplicator](ue_ue.CheatManager.md#spawnserverstatreplicator)
- [StreamLevelIn](ue_ue.CheatManager.md#streamlevelin)
- [StreamLevelOut](ue_ue.CheatManager.md#streamlevelout)
- [Summon](ue_ue.CheatManager.md#summon)
- [Teleport](ue_ue.CheatManager.md#teleport)
- [TestCollisionDistance](ue_ue.CheatManager.md#testcollisiondistance)
- [ToggleAILogging](ue_ue.CheatManager.md#toggleailogging)
- [ToggleDebugCamera](ue_ue.CheatManager.md#toggledebugcamera)
- [ToggleServerStatReplicatorClientOverwrite](ue_ue.CheatManager.md#toggleserverstatreplicatorclientoverwrite)
- [ToggleServerStatReplicatorUpdateStatNet](ue_ue.CheatManager.md#toggleserverstatreplicatorupdatestatnet)
- [UpdateSafeArea](ue_ue.CheatManager.md#updatesafearea)
- [ViewActor](ue_ue.CheatManager.md#viewactor)
- [ViewClass](ue_ue.CheatManager.md#viewclass)
- [ViewPlayer](ue_ue.CheatManager.md#viewplayer)
- [ViewSelf](ue_ue.CheatManager.md#viewself)
- [Walk](ue_ue.CheatManager.md#walk)
- [Find](ue_ue.CheatManager.md#find)
- [Load](ue_ue.CheatManager.md#load)
- [StaticClass](ue_ue.CheatManager.md#staticclass)

## Constructors

### constructor

• **new CheatManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:8332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8332)

## Properties

### DebugCameraControllerClass

• **DebugCameraControllerClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:8334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8334)

___

### DebugCameraControllerRef

• **DebugCameraControllerRef**: [`DebugCameraController`](ue_ue.DebugCameraController.md)

#### Defined in

[ue/ue.d.ts:8333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8333)

___

### \_\_tid\_CheatManager\_\_

• **\_\_tid\_CheatManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8394)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

### BugIt

▸ **BugIt**(`ScreenShotDescription?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenShotDescription?` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8335)

___

### BugItGo

▸ **BugItGo**(`X`, `Y`, `Z`, `Pitch`, `Yaw`, `Roll`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `X` | `number` |
| `Y` | `number` |
| `Z` | `number` |
| `Pitch` | `number` |
| `Yaw` | `number` |
| `Roll` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8336)

___

### BugItStringCreator

▸ **BugItStringCreator**(`ViewLocation`, `ViewRotation`, `GoString`, `LocString`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ViewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `ViewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `GoString` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `LocString` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8337)

___

### ChangeSize

▸ **ChangeSize**(`F`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `F` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8338)

___

### CheatScript

▸ **CheatScript**(`ScriptName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScriptName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8339)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### DamageTarget

▸ **DamageTarget**(`DamageAmount`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DamageAmount` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8340)

___

### DebugCapsuleSweep

▸ **DebugCapsuleSweep**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8341)

___

### DebugCapsuleSweepCapture

▸ **DebugCapsuleSweepCapture**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8342)

___

### DebugCapsuleSweepChannel

▸ **DebugCapsuleSweepChannel**(`Channel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Channel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8343)

___

### DebugCapsuleSweepClear

▸ **DebugCapsuleSweepClear**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8344)

___

### DebugCapsuleSweepComplex

▸ **DebugCapsuleSweepComplex**(`bTraceComplex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTraceComplex` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8345)

___

### DebugCapsuleSweepPawn

▸ **DebugCapsuleSweepPawn**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8346)

___

### DebugCapsuleSweepSize

▸ **DebugCapsuleSweepSize**(`HalfHeight`, `Radius`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HalfHeight` | `number` |
| `Radius` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8347)

___

### DestroyAll

▸ **DestroyAll**(`aClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `aClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8348)

___

### DestroyAllPawnsExceptTarget

▸ **DestroyAllPawnsExceptTarget**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8349)

___

### DestroyPawns

▸ **DestroyPawns**(`aClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `aClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8350](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8350)

___

### DestroyServerStatReplicator

▸ **DestroyServerStatReplicator**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8351](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8351)

___

### DestroyTarget

▸ **DestroyTarget**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8352)

___

### DisableDebugCamera

▸ **DisableDebugCamera**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8353)

___

### DumpChatState

▸ **DumpChatState**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8354)

___

### DumpOnlineSessionState

▸ **DumpOnlineSessionState**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8355)

___

### DumpPartyState

▸ **DumpPartyState**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8356)

___

### DumpVoiceMutingState

▸ **DumpVoiceMutingState**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8357)

___

### EnableDebugCamera

▸ **EnableDebugCamera**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8358)

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

### FlushLog

▸ **FlushLog**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8359)

___

### Fly

▸ **Fly**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8360)

___

### FreezeFrame

▸ **FreezeFrame**(`Delay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Delay` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8361)

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

### Ghost

▸ **Ghost**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8362)

___

### God

▸ **God**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8363)

___

### InvertMouse

▸ **InvertMouse**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8364)

___

### LogLoc

▸ **LogLoc**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8365)

___

### OnlyLoadLevel

▸ **OnlyLoadLevel**(`PackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8366)

___

### PlayersOnly

▸ **PlayersOnly**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8367)

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8368)

___

### ReceiveInitCheatManager

▸ **ReceiveInitCheatManager**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8369)

___

### ServerToggleAILogging

▸ **ServerToggleAILogging**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8370)

___

### SetMouseSensitivityToDefault

▸ **SetMouseSensitivityToDefault**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8371)

___

### SetWorldOrigin

▸ **SetWorldOrigin**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8372)

___

### Slomo

▸ **Slomo**(`NewTimeDilation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTimeDilation` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8373)

___

### SpawnServerStatReplicator

▸ **SpawnServerStatReplicator**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8374)

___

### StreamLevelIn

▸ **StreamLevelIn**(`PackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8375)

___

### StreamLevelOut

▸ **StreamLevelOut**(`PackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8376)

___

### Summon

▸ **Summon**(`ClassName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ClassName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8377)

___

### Teleport

▸ **Teleport**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8378)

___

### TestCollisionDistance

▸ **TestCollisionDistance**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8379)

___

### ToggleAILogging

▸ **ToggleAILogging**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8380)

___

### ToggleDebugCamera

▸ **ToggleDebugCamera**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8381)

___

### ToggleServerStatReplicatorClientOverwrite

▸ **ToggleServerStatReplicatorClientOverwrite**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8382)

___

### ToggleServerStatReplicatorUpdateStatNet

▸ **ToggleServerStatReplicatorUpdateStatNet**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8383)

___

### UpdateSafeArea

▸ **UpdateSafeArea**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8384)

___

### ViewActor

▸ **ViewActor**(`ActorName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8385)

___

### ViewClass

▸ **ViewClass**(`DesiredClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DesiredClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8386)

___

### ViewPlayer

▸ **ViewPlayer**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8387)

___

### ViewSelf

▸ **ViewSelf**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8388)

___

### Walk

▸ **Walk**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8389)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CheatManager`](ue_ue.CheatManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CheatManager`](ue_ue.CheatManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:8391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8391)

___

### Load

▸ `Static` **Load**(`InName`): [`CheatManager`](ue_ue.CheatManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CheatManager`](ue_ue.CheatManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:8392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8392)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:8390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8390)
