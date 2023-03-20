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

## Properties

### DebugCameraControllerClass

• **DebugCameraControllerClass**: [`Class`](ue_ue.Class.md)

___

### DebugCameraControllerRef

• **DebugCameraControllerRef**: [`DebugCameraController`](ue_ue.DebugCameraController.md)

___

### \_\_tid\_CheatManager\_\_

• **\_\_tid\_CheatManager\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### BugIt

▸ **BugIt**(`ScreenShotDescription?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenShotDescription?` | `string` |

#### Returns

`void`

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

___

### ChangeSize

▸ **ChangeSize**(`F`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `F` | `number` |

#### Returns

`void`

___

### CheatScript

▸ **CheatScript**(`ScriptName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScriptName` | `string` |

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

### DamageTarget

▸ **DamageTarget**(`DamageAmount`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DamageAmount` | `number` |

#### Returns

`void`

___

### DebugCapsuleSweep

▸ **DebugCapsuleSweep**(): `void`

#### Returns

`void`

___

### DebugCapsuleSweepCapture

▸ **DebugCapsuleSweepCapture**(): `void`

#### Returns

`void`

___

### DebugCapsuleSweepChannel

▸ **DebugCapsuleSweepChannel**(`Channel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Channel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |

#### Returns

`void`

___

### DebugCapsuleSweepClear

▸ **DebugCapsuleSweepClear**(): `void`

#### Returns

`void`

___

### DebugCapsuleSweepComplex

▸ **DebugCapsuleSweepComplex**(`bTraceComplex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTraceComplex` | `boolean` |

#### Returns

`void`

___

### DebugCapsuleSweepPawn

▸ **DebugCapsuleSweepPawn**(): `void`

#### Returns

`void`

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

___

### DestroyAll

▸ **DestroyAll**(`aClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `aClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### DestroyAllPawnsExceptTarget

▸ **DestroyAllPawnsExceptTarget**(): `void`

#### Returns

`void`

___

### DestroyPawns

▸ **DestroyPawns**(`aClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `aClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### DestroyServerStatReplicator

▸ **DestroyServerStatReplicator**(): `void`

#### Returns

`void`

___

### DestroyTarget

▸ **DestroyTarget**(): `void`

#### Returns

`void`

___

### DisableDebugCamera

▸ **DisableDebugCamera**(): `void`

#### Returns

`void`

___

### DumpChatState

▸ **DumpChatState**(): `void`

#### Returns

`void`

___

### DumpOnlineSessionState

▸ **DumpOnlineSessionState**(): `void`

#### Returns

`void`

___

### DumpPartyState

▸ **DumpPartyState**(): `void`

#### Returns

`void`

___

### DumpVoiceMutingState

▸ **DumpVoiceMutingState**(): `void`

#### Returns

`void`

___

### EnableDebugCamera

▸ **EnableDebugCamera**(): `void`

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

### FlushLog

▸ **FlushLog**(): `void`

#### Returns

`void`

___

### Fly

▸ **Fly**(): `void`

#### Returns

`void`

___

### FreezeFrame

▸ **FreezeFrame**(`Delay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Delay` | `number` |

#### Returns

`void`

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

### Ghost

▸ **Ghost**(): `void`

#### Returns

`void`

___

### God

▸ **God**(): `void`

#### Returns

`void`

___

### InvertMouse

▸ **InvertMouse**(): `void`

#### Returns

`void`

___

### LogLoc

▸ **LogLoc**(): `void`

#### Returns

`void`

___

### OnlyLoadLevel

▸ **OnlyLoadLevel**(`PackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |

#### Returns

`void`

___

### PlayersOnly

▸ **PlayersOnly**(): `void`

#### Returns

`void`

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(): `void`

#### Returns

`void`

___

### ReceiveInitCheatManager

▸ **ReceiveInitCheatManager**(): `void`

#### Returns

`void`

___

### ServerToggleAILogging

▸ **ServerToggleAILogging**(): `void`

#### Returns

`void`

___

### SetMouseSensitivityToDefault

▸ **SetMouseSensitivityToDefault**(): `void`

#### Returns

`void`

___

### SetWorldOrigin

▸ **SetWorldOrigin**(): `void`

#### Returns

`void`

___

### Slomo

▸ **Slomo**(`NewTimeDilation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTimeDilation` | `number` |

#### Returns

`void`

___

### SpawnServerStatReplicator

▸ **SpawnServerStatReplicator**(): `void`

#### Returns

`void`

___

### StreamLevelIn

▸ **StreamLevelIn**(`PackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |

#### Returns

`void`

___

### StreamLevelOut

▸ **StreamLevelOut**(`PackageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackageName` | `string` |

#### Returns

`void`

___

### Summon

▸ **Summon**(`ClassName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ClassName` | `string` |

#### Returns

`void`

___

### Teleport

▸ **Teleport**(): `void`

#### Returns

`void`

___

### TestCollisionDistance

▸ **TestCollisionDistance**(): `void`

#### Returns

`void`

___

### ToggleAILogging

▸ **ToggleAILogging**(): `void`

#### Returns

`void`

___

### ToggleDebugCamera

▸ **ToggleDebugCamera**(): `void`

#### Returns

`void`

___

### ToggleServerStatReplicatorClientOverwrite

▸ **ToggleServerStatReplicatorClientOverwrite**(): `void`

#### Returns

`void`

___

### ToggleServerStatReplicatorUpdateStatNet

▸ **ToggleServerStatReplicatorUpdateStatNet**(): `void`

#### Returns

`void`

___

### UpdateSafeArea

▸ **UpdateSafeArea**(): `void`

#### Returns

`void`

___

### ViewActor

▸ **ViewActor**(`ActorName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorName` | `string` |

#### Returns

`void`

___

### ViewClass

▸ **ViewClass**(`DesiredClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DesiredClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### ViewPlayer

▸ **ViewPlayer**(`S`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`void`

___

### ViewSelf

▸ **ViewSelf**(): `void`

#### Returns

`void`

___

### Walk

▸ **Walk**(): `void`

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
